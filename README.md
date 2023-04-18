# React-Practical-06 
## Generate development , staging and production build

#

### For Live demo (different build environments) : 

(For output => check in <b> console </b> and code of package.json , actions and app.js file)

1) Development Build : https://development-build.netlify.app/
2) Staging Build : https://staging-build.netlify.app
3) Production Build : https://production-build.netlify.app/


# Directory structure

![Screenshot 2023-04-18 at 8 10 47 PM](https://user-images.githubusercontent.com/60025285/232812407-f4cacb16-2522-492b-82b4-9874b41ba5fa.png)

#

<pre>
for git: two branch:
    1)"main" - main branch 
    2) "temp" - working branch
</pre>

#

# Configure different environment build

![Screenshot 2023-04-18 at 8 23 13 PM](https://user-images.githubusercontent.com/60025285/232816508-5b7fa97f-ac1e-40ab-ad44-768ebbb56a6a.png)


![Screenshot 2023-04-18 at 8 21 40 PM](https://user-images.githubusercontent.com/60025285/232815961-9a7e1003-1d60-4541-85ab-105588245c29.png)

![Screenshot 2023-04-18 at 8 18 54 PM](https://user-images.githubusercontent.com/60025285/232814702-738b8230-850b-46e0-993d-d169ad98211a.png)

#

#

# After configure => To run the React App 

(you must have node installed)

### Use following commands :

<pre>
To Installing dependencies
### `npm install`

1) Development Build :
### `npm run build:dev`

2) Staging Build :
### `npm run build:staging`

3) Production Build:
### `npm run build:pod`


The build folder is ready to be deployed.
You may serve it with a static server:

### `serve -s build`

</pre>

#

#

## To verify build type i use environment variable ( `actions/index.js and App.js` )

![Screenshot 2023-04-18 at 8 27 18 PM](https://user-images.githubusercontent.com/60025285/232817723-82df11ac-ebe2-473a-ac7b-91e360a188d2.png)

![Screenshot 2023-04-18 at 8 28 32 PM](https://user-images.githubusercontent.com/60025285/232819306-bbea14e6-761c-46ab-9009-ed7ba3f6869e.png)



#

#

# Output 

### (API fetch is working and console is show BUild Type):

#

![Screenshot 2023-04-18 at 8 35 20 PM](https://user-images.githubusercontent.com/60025285/232820487-37b0dc2e-1c64-4915-9936-458fe497ef6c.png)

#

![Screenshot 2023-04-18 at 8 37 51 PM](https://user-images.githubusercontent.com/60025285/232820696-4515bfb3-33c0-4b68-ae9d-8c3114574aa2.png)

#

![Screenshot 2023-04-18 at 8 38 00 PM](https://user-images.githubusercontent.com/60025285/232820782-1f81478e-fcfa-4c65-9255-e26d323f2f1b.png)



