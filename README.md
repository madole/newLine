##NewLine Node Module

Pass it a string and an optional boolean to return a string with a new line ('\n') appended or prepended to the string. 

    var nl = require('newLine');
    
    var str = 'String to have a new line concated';
    
    console.log(nl(str)); // 'String to have a new line concated\n'
    console.log(nl(str, true)); // '\nString to have a new line concated'
  
  
To run tests

    npm install -g mocha
    
    mocha tests/newLineTests.js
    
   
   
###Install from Github

    npm install git://github.com/madole/newLine.git
    
###Install from NPM
    
    npm install newlinetostring