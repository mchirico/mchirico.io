[![codebeat badge](https://codebeat.co/badges/423a7797-60b7-4d87-97ed-d908175be5e1)](https://codebeat.co/projects/github-com-mchirico-mchirico-master)
[![codecov](https://codecov.io/gh/mchirico/mchirico/branch/master/graph/badge.svg)](https://codecov.io/gh/mchirico/mchirico)
[![Maintainability](https://api.codeclimate.com/v1/badges/bb775144336d4a1df5d1/maintainability)](https://codeclimate.com/github/mchirico/mchirico/maintainability)

![Angular](https://github.com/mchirico/mchirico/workflows/Angular/badge.svg)
![CI](https://github.com/mchirico/mchirico/workflows/CI/badge.svg)


# mchirico

Typescript project:

- Node backend
- Angular front-end 
- Firebase 

Live demo [tsexpress.cwxstat.io](https://mchirico.io/) Make sure
you install all missing packages.

StackBlitz [ts-express](https://stackblitz.com/github/mchirico/mchirico/tree/master/angular)


This is meant to be a very simple starter project, for quickly
testing Typescript code. It does contain angular 10

## Running Tests

Run the Firebase emulator when testing.

```
firebase emulators:start
```


For live pull of pubSub messages reference: 
<a href='https://github.com/mchirico/go-pubsub'>https://github.com/mchirico/go-pubsub</a>


# upgrade

```
# install npm-check-updates
ncu -u
npm install
```

## Starting

Also see the Makefile

```
git clone https://github.com/mchirico/ts.git
git co express
npm install
npm test

```

