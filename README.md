# Hiring Channels App

Hirring Channels is an application created for the purpose of facilitating job seekers and employers, where job seekers and employers only register in this application and find their respective matches, without having to meet in an event and uses the web in the application of hirirng channels operation.

![](hirringChannels.PNG)

## pre-Instalation

before installing this application, first install Node JS

_https://nodejs.org/en/download/

## Installation

OS X & Linux & Windows:

```sh
npm init
```

```sh
npm install
```


## Development setup

Before using this application, first enter the project folder _your_project and create a dotEnv file:

Linux :
```sh
cp example.ENV .ENV
```

Windows :
```sh
copy example.ENV .ENV /a
```

then edit the file as follows :
```sh
API_ENDPOINT=http://34.202.135.29:4000/api/v1/

ONESIGNAL_API_KEY=1bf005c4-154a-4587-851d-b502ebc6ea62

DARK_GREEN = #035943
GREEN = #68CAA2
WHITE = #FFFFFF
BLUE = #686FCA
```


## Running

To run this application, you must run the following command :

```sh
npx react-native run-android
```
