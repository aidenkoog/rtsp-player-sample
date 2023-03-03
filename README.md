## RTSP Player

#### Summary

This project contains logic related to RTSP video play.

- Language: Typescript
- Library: React (A library for creating user interfaces.)

#### Release Note

- 2023/03/02: Initialized project source code.
- 2023/03/03: Initialized react-native project source code. / Added web local server code for testing.
- 2023/03/03: Added VLC-Player view that plays rtsp video.

#### How To Setup Environment

It's mandantory to set up the development environment and build the app by following the instructions below:

- Web
  - Local Server Setup
    - git clone https://github.com/deepch/RTSPtoWeb
    - cd RTSPtoWeb
    - Update config.json
      - streams
    - Execute server
      - GO111MODULE=on go run \*.go
        - (localhost:8083)
  - React Client Setup
    - Visit https://ko.reactjs.org/
    - npm create vite@latest
      - react / typescript selection.
    - Integrate VideoJs
      - npm install --save-dev video.js @types/video.js
    - yarn install
    - npm start or npm run dev
      - Please refer to your package.json file content.
- Mobile
  - npx react-native init PROJECT_NAME
  - Create local.properties in android directory.
  - yarn install
  - npm run android or npm run ios

#### Link:

If you are interested in information about me or other activities, please access the link below.

| **Page**        | **LINK**                                             |
| --------------- | ---------------------------------------------------- |
| **Github page** | [https://aidenkoog.github.io/]                       |
| **LinkedIn**    | [https://www.linkedin.com/in/dongwan-koo-2041bb13b/] |
