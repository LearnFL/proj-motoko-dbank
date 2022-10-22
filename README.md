# Motoko DBank

### Commands
1) dxf new AppName</br>
2) dfx start
3) dfx deploy
4) npm start</br>

<b>Must deploey after each change</b></br>
<b>If this error:</b></br>
  <i>No production canister_ids.json found. Continuing with local</i></br>
  <i>[webpack-cli] TypeError: cli.isMultipleCompiler is not a function</i></br>
  <i>at Command.<anonymous> (/Users/davidmartinezgil/proyect/node_modules/@webpack-cli/serve/lib/index.js:146:35)</i></br>
  <i>at async Promise.all (index 1)</i></br>
  <i>at async Command.<anonymous> (/Users/davidmartinezgil/proyect/node_modules/webpack-cli/lib/webpack-cli.js:1674:</i></br>
  
<b>Run these commands:</b> </br>
  <i>npm install --save-dev webpack-cli</br>
  npm upgrade --save-dev webpack-cli</i></br>

### DBUG
<i>import Debug "mo:base/Debug";</i></br>
<i>Debug.print(debug_show(currentValue));</i></br>

### Class Canister
<i>actor DBank {}</i>

### Variable
<i>var a = 20;</i></br>
To replace value use walrus:</br>
<i>var a := 25;</i>

### Constant
<i>let id = 54534564564;</i>

### Function
Private function:</br>
<i>func Name() {}</i></br>
Public function</br>
<i>public func Name() {}</i>
