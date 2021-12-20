# Practice Design System

CRA + TS + material UI + storybook 으로 design system 구축하기

# Install

```bash

# CRA
npx create-react-app my-app --template typescript

# Install material UI
yarn add @mui/material @emotion/react @emotion/styled

# Install storybook
npx -p @storybook/cli sb init

# Install Chromatic
yarn add --dev chromatic
npx chromatic --project-token={your token} # build 확인
```


# Getting Started 

`yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

# Getting Start Storybook

`yarn storybook`
