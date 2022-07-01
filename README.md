# Pauleta's Boilerplate

I'm glad to present you to my custom Laravel boilerplate. It uses:
- Laravel for the backend
- Laravel Sail as development enviroment
- Composer as PHP Package Manager
- PEST for backend Unit Testing
- XDebug for debugging
- Inertia as the glue between Frontend and Backend
- Vite as JavaScript Package Compiler
- Yarn as JavaScript Package Manager
- Typescript as Frontend language
- React for the Frontend
- Ziggy to access the backend routes on the frontend
- JEST for Frontend Unit Testing
- Mantine as UI Component Library
- Tailwind for the CSS
- Laravel Jetstream as Starter Kit
- MySQL for the Database

## To Do
I still need to install and setup:
- Mantine (convert the Jetstream UI to use Mantine)
- PEST (rewrite the tests with PEST)
- JEST (check if it is possible to use JEST with Inertia, if yes, write the needed tests)
- Redis (I'm wondering on getting Redis in the project)
- AWS S3 (or similar, for the file storage)
- Laravel Websockets (to allow for real time data)
- Email (for the password recovery, etc.)
- Log Viewer on the frontend
- Database manager on the frontend
- Maybe install Larastan

## Installation

You just need the Docker installed to run the app.

After cloning the repo you need to:

```sh
./vendor/bin/sail up -d
sail composer install
sail yarn install
```
