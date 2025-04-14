# ✅ PASSO A PASSO
1- passo
npm create vite@latest primeiro-projeto

2- passo
react

3- passo
javascript

4-passo
cd primeiro-projeto (nome da pasta)

5-passo
npm intall

6-passo
npm run dev 

7-passo
npm install --save-dev jest @testing-library/react @testing-library/jest-dom babel-jest

8-passo
npm install --save-dev jest-environment-jsdom

9- passo
instalar na raiz 
{
    "presets": ["@babel/preset-env", "@babel/preset-react"]
}
10- passo
 npm install --save-dev @babel/preset-env @babel/preset-react

11-passo
export default {
    testEnvironment: 'jsdom',
    moduleNameMapper: {
        '//.(css|less)$': 'identity-obj-proxy'
    },
    setupFilesAfterEnv: ['<rootDir>/setupTests.js'],
    transform: {
        '^.+//.jsx?$': 'babel-jest'
    }
}
npm install --save-dev identity-obj-proxy

12-passo
import '@testing-library/jest-dom'
