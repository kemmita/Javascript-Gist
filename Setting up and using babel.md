1. Node and npm will need to be installed.
```
sudo npm i -g babel-cli@6.24.1
```
```
sudo npm install -g live-server
```
2. In your public directory run 
```
live-server
```
3. open another termninal and mind your current directory. from there you will need to define your src file and out
file paths respectivley.
```
babel src/app.js --out-file=public/scripts/app.js --presets=env,react --watch
```
