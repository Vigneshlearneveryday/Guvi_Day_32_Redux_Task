
# Redux-Cart-Page

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