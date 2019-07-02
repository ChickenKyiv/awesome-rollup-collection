
@TODO Create a few practical tasks, related to basic Rollup homework. Like a create a simple module, install and use lodash, read file, generate file.

---

https://www.rithmschool.com/courses/javascript/javascript-arrays-exercise

https://www.w3resource.com/javascript-exercises/javascript-array-exercises.php

---

#### Class project  

As we didn't touch a topic of how to publish your module on npm. You can read about it here - link.
You'll need to publish all 3 modules at npm, so other people can use them at their projects, nodejs projects.

1) ModuleI
It will contain methods that will operate with arrays.
a) Write a JS function, to check whether an argument of function is an array or not.
b) Write a JS function, that will clone an array
c) Write a JS function to get the first element of an array. Passing an argument "n" will return the first "n" elements of array.
d) Write a JS function to get the last element of an array. Passing an argument "n" will return the last "n" elements of array.
e) Write a JS function, that will print information about array elements with some additional formatting.
i.e [1,2,3,4,5] --> result:
- starting to print an array
element: "index"
value: "value"
--> Each row/value should be printed on the next line for readability.

- end of array

2) ModuleII
Will read JSON file(sample file link) and return data(array) from this file
You need to download that file to your computer.

For reading local file --> use "fs" module.
It will help you with this task. For passing path to that file, use module "path"
Examples of how to do it you can find at Google search. "How to read file in Nodejs" should help you.

3) ModuleIII
You will install ModuleI and ModuleII inside of this module.
It will be our major module, that will make main work.
Local file should be stored inside of this module.
Using methods from MII you'll read the data from that file, then you'll manipulate with arrays, using methods from MI

All 3 modules hosuld be published at NPM.
