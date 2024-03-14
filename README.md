-------------------------------------------------------------------------
                REDUX - STATE MANAGEMENT TOOL
-------------------------------------------------------------------------

- To avoid props drilling to achieve state management 
- Install REDUX : npm install @reduxjs/toolkit 
                  npm install react-redux

                  OR
                 npm install @reduxjs/toolkit react-redux
- REDUX TOOLKIT 
  - configureStore() : creating a Redux store 
    - Combining the slice reducers into the root reducer 
  - Provider from react-redux : Provide store to react App
  - createSlice() : used o hold both action and reducer together and it return reducer,actions 
  - useSelector : hook used to access state from store to component 
  - useDispatch() : hook used dispatch/execute the action from component
    - @returns — The dispatch function from the Redux store.
  - createAsyncThunk : A function that accepts a Redux action type string and a callback function that should return a promise. 
  - extraReducers : used to hndle action returing promise



------------------------------
   Basic commands
------------------------------
1. to create react app : npx create-react-app project-name
2. to run react app : npm start / npm run dev
3. install vite : npm i -g create-vite 
4. to create project using vite : npm create vite@latest / 
    npm create vite@latest react-app-name -- --template react
5. to run vite app : npm run dev 
6. installing MUI : npm install @mui/material @emotion/react @emotion/styled
7. installing React Bootstrap : npm install react-bootstrap bootstrap
  - Add bootstrap themes : using https://bootswatch.com/ website, download bootstrap.min.css file and add it in src folder , import css file into main.jsx
8. install axios : npm i axios
9. install REDUX : npm install @reduxjs/toolkit react-redux
10. install react-router-dom package : npm i react-router-dom
11. install react tostify : npm i react-toastify


