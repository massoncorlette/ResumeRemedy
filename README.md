# React + Vite

User can add 3 work experiences + 2 education references
The containers to add to resume, I can reset upon adding to resume

Notes on being modular using React. So it seems that we will use 
App.jsx to import all of our components from directory. This way we 
can keep things modular and organized. 

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh


Pseudo: 
Within UserInfo we will want to setState for person object upon every instance of change.
We can then pass the props to ResumePreview which seems to have to be a 
child component? 