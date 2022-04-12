# nodejs_app_testing

Steps 

1. npm init -y 
2. npm install jest
3. check and change node package
    "script":{
       "test" : " jest --coverage"
    }
5. create a program file e.g program.js
6. export the mothods in the file e.g module.export = add    
8. save your test program as program.test.js

how to write cases
1. import the method in the test file e.g const add = require('./program')
2. check base on test(()=>{ expect('statemnt ').toBe() or toStrictEqual() etc })tte
3. npm test, make sure you are the folder directory
    
