# booleanValue
bgc team module

how to use:
1. install coke-boolean and follow the command below
npm i coke-boolean

2. install types and follow the command below
npm install --save @types/node

3. Add types and typeRoots in tsconfig.json like below
"types": [ "node" ],
"typeRoots": [ "../node_modules/@types" ]

Implementation:
1. declare require variable in emport module area and follow code below.
declare var require: any; 

2. declare isReadOnlyComponent variable inside export class, like the code below.
isReadOnlyComponent = true;

3. Create your own funcation to use your module like the code below.

myFunction(){
var cokeBool = require('coke-boolean');
     const result = new cokeBool('1');
     this.isReadOnlyComponent =  result.shoHideMaster();
     console.log(this.isReadOnlyComponent);  
}
