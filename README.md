# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
"# lms-frontend" 


#LMS Frontend 

## Setup Instruction

'''

git clone https://github.com/sandeepmehta30/lms-frontend.git

'''

2. move into directory
'''
  cd lms-frontend

'''

3. Install dependencies
  npm i

'''

4. Run the server
  npm run dev

'''

### Setup instruction for tailwind css

[tail wind official instruction doc] (https://tailwindcss.com/docs/installation)


1. Installed tailwindcss 
'''
  npm install -D tailwindcss
'''

2. Create tailwind config file
'''
npx tailwindcss init
'''

3. Add file extension t wailwind config file in the content property
'''
"./src/**/*.{html,js,jsx,ts,tsx}"

'''

4. Add the tailwind directive at the top of the index.css file
'''
@tailwind base;
@tailwind components;
@tailwind utilities;
'''