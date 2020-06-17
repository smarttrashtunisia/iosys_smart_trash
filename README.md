# iosys_smart_trash

## Introduction

<p align="center">
  <img src="/frontend/src/assets/images/logo_pi.png" width="250" title="hover text">
</p>

This is an academic project aiming to monitor public waste using a Web App linked with and embedded system.

## Configuration
#### 1) Clone the repository
```
git clone https://github.com/smarttrashtunisia/iosys_smart_trash.git
```
#### 2) Install packages
```
cd api
mkdir public && mkdir uploads
npm install
cd ../frontend
npm install
```
#### 2) Run the web App
```
cd ../api
nodemon app.js
cd ../frontend
ng serve -o
```
