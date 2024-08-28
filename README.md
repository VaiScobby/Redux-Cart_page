
# Redux-Cart_Page

This is an sample cart page website which is based on React-Redux which was designed by me using React. It's Guvi-Zen class Roadmap session: Day-32 and React-Redux: Day-12 Task.

## Tech Stack

- HTML
- CSS
- Javascript
- Bootstrap
- FontAwesome
- React(react-redux, @reduxjs/toolkit)

## Features

- Responsive and Interactive Design

## Lessons Learned

Through this task I learned why we use Redux and how to use Redux functionalities.

<b>Why we use Context API</b>: 
- Complex State Management
- Predictable Data Flow
- Large-Scale Applications.
  
<b>Usage</b>: 
- <b>Create Slice(</b>:
	-  {createSlice} from ‘@redux/toolkit’
  - name, initialState,reducers (3 things important) 
- <b>Creating store</b>:
  -  {configureStore -> reducer{}} from ‘@redux/toolkit’
- <b>Provider</b>:
	- It is used to consume a React context within a functional component.
- <b>Use Selector</b>:
	- {useSelector} from ‘react-redux’ – fetch purpose
- <b>UseDispatch</b>:
	- {useDispatch} from ‘react-redux’ – update purpose


## Website

[Redux-Cart_page](https://vaijai-redux-cart-page.netlify.app/)


## Screenshots

![App Screenshot](./public/Images/demo.png)


## React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh


## Setup

Followig are the requirements to run this project:
- vite --> React Project Build Tool
- Node Package Manager (NPM)
- npm i react-redux @reduxjs/toolkit
- React

## npm run dev

Runs the app in the development mode.\
Open [http://localhost:5173](http://localhost:5173) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

## Feedback

If you have any feedback, please reach out to me at vaijai.smily06@gmail.com