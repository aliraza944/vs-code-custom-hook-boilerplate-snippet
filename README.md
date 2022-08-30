# vs-code-custom-hook-boilerplate-snippet
A vs code snippet for creating the boiler plate for cutom hooks in react

## How to use

To use this snippet, in your vs code editor open up the **command palette** by typing `cmd+shift+p` on MAC or `ctrl+shift+p` on windows. Once you open the command palette type **snippet** and select `Preferences: Configure User Snippets`. This will ask you to selecte a language for which you want to create the snippet. Selecte the `javascript react` options.<br/>
This will open a `javascriptreact.json` file. Remove everthing from `javascritptreact.json` and copy paste the snippet.txt content into the file and save it.
<br />
Whenever you type `cbh` it will open paste the following code boiler plate code into the file.
```javascript

import {useState} from 'react';
  
  const your_file_name = () => {
  
  
  return {
  
  }
  }
  
  export default your_file_name;
```
