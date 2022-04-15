# react-babel-setup
This project what to prepare when making a React project Without CRA(Create-React-App)



## What is
### package.json 
	 file that record metadata about your project ,install some dependencies ,running scripts and etc
### package-lock.json
	 log all dependencies of node modules
### node_modules 
	  store all dependencies or packages installed or added with npm


### public
	a folder that stores files such as html , css , compiled files and etc
	after processing webpack
### src 
	containing some react components


## initiation npm porject and installing dependencies
```
npm init // to inititate npm project
npm install lite-server (optional)
npm install @babel/cli @babel/core @babel/preset-react
```
## Add React CDN
	for this you can go React DOCS and go CDN pages

## Babelrc preset setting
```
1. Make file In the outer folder location name it .babelrc
2. add your preset react to this file
```

### run website
```
npm run serve (to run lite-server)
npm run build (to compiling jsx component / element)
npm run start (to run server and run build)
```
