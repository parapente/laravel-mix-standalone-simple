# laravel-mix-standalone-simple
Use [laravel-mix](https://laravel-mix.com) to create a site without the [laravel](https://laravel.com) framework

## Setup
### Node
You need to have npm installed on your system to use laravel-mix. Go to [the official nodejs web page](https://nodejs.org/) for installation instructions. When you are ready to continue run the command below to install the necessary npm packages:
```
npm ci
```

## Usage
After the installation process you can use laravel-mix by running one of the following scripts:
```
npm run dev
```
Prepare the project for development.

```
npm run watch
```
Prepare the project for development and run [browsersync](https://browsersync.io). Browsersync includes a simple standalone server for previewing webpages.

```
npm run prod
```
Prepare the project to be used in production.
