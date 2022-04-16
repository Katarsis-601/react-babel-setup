# react-babel-setup
Manually React Setup



## What's inside ? 
### package.json 

file that record metadata about your project ,install some dependencies ,running scripts and etc

### package-lock.json
	 Log all dependencies of node modules
### node_modules 
	  Store all dependencies or packages installed or added with npm


### public
	Folder that stores files such as html , css , compiled files and etc
	after processing webpack
### src 
	Folder that containing some react components


# Initiation npm porject and installing dependencies
```
npm init // to inititate npm project
npm install lite-server (optional)
npm install @babel/cli @babel/core @babel/preset-react
```
### Add React CDN
For this you can go React DOCS and go CDN pages

### Babelrc preset setting
```
1. Make file In the outer folder location name it .babelrc
2. add your preset react to this file
```

### Run website 
```
npm run serve (to run lite-server)
npm run build (to compiling jsx component / element)
npm run start (to run server and run build)
```
