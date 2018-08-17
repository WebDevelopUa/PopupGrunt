# PopupGrunt

## Pop-up modal example with jQuery & Grunt Task Runner

### Requirements

1) Download and install **Ruby**


https://rubyinstaller.org/downloads/

https://github.com/oneclick/rubyinstaller2/releases/download/rubyinstaller-2.5.1-2/rubyinstaller-devkit-2.5.1-2-x64.exe

https://github.com/oneclick/rubyinstaller2/releases/download/rubyinstaller-2.4.4-2/rubyinstaller-devkit-2.4.4-2-x64.exe

https://github.com/oneclick/rubyinstaller2/releases/download/rubyinstaller-2.5.1-2/rubyinstaller-2.5.1-2-x64.7z

https://github.com/oneclick/rubyinstaller2/releases/download/rubyinstaller-2.4.4-2/rubyinstaller-2.4.4-2-x64.7z


```
ruby -v
```


2) Installing **Sass/SCSS**

Open the embedded Terminal (View | Tool Windows | Terminal or Alt+F12) type gem install sass at the command prompt.

The package is installed in the folder where the Ruby executable file and the gem.bat file are stored.

```
sass -v
gem install sass
```


3) Install **Node.js** & **npm**


https://nodejs.org/en/download/

https://nodejs.org/dist/v8.11.4/node-v8.11.4-x64.msi

https://nodejs.org/dist/v8.11.4/node-v8.11.4-win-x64.zip

https://www.npmjs.com/get-npm


```
node -v
npm -v
npm install npm@latest -g
```



4) Install **Grunt CLI** globally
```
npm install -g grunt-cli
```



5) Create ***package.json*** in a local directory

The packages we’re installing:

*grunt-contrib-sass* – compile Sass to CSS

*grunt-contrib-cssmin* – minify CSS

*grunt-contrib-uglify* – minify files with UglifyJS

*grunt-contrib-watch* – run predefined tasks whenever watched file patterns are added, changed or deleted


```
npm install --save-dev grunt-contrib-jshint
npm install --save-dev grunt-contrib-concat
npm install --save-dev grunt-contrib-watch
npm install --save-dev grunt-contrib-uglify
npm install --save-dev grunt-contrib-sass

npm install grunt@1.0.3
```

6) Create a local npm install in a local directory
```
npm install
```

7) Create ***Gruntfile.js***
- loading grunt,
- defining tasks,
- loading the plugins,
- registering the tasks

8) Run grunt command
```
grunt
```
9) Open ***index.html***
