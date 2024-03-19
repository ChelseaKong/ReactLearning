## 1 Install dev
- 1 Install Node.js
- 2 Download Sandbox
- 3 Terminal, cd to Sandbox
- 4 npm install
- 5 npm start - http://localhost:3000/ will show something

## 2 src has three files: App.js, index.js, and styles.css

### 1 App.js
```
export default function Square() {
  return <button className='Square'> X </button>
}
```
- 1 App.js created a **component**. In React, a component is a piece of reusable code that represents a part of a user interface.
- 2 Square() is a function. JavaScript **export** keyword allows this function can be accessed outside of this file. **default** keyword defined this function is the main function in your file.
- 3 **<button>** is a **JSX element**. A JSX element is a combination of JavaScript code and HTML tags that describes what you'd like to display. **className=""** is a button property that tells CSS how to style the button.

### 2 styles.css
- This file defines the styles for your React app.

-
<details>
  <summary>Click to show detailed code.</summary>
  <code>
        * {
          box-sizing: border-box;
        }
        
        body {
          font-family: sans-serif;
          margin: 20px;
          padding: 0;
        }
        
        h1 {
          margin-top: 0;
          font-size: 22px;
        }
        
        h2 {
          margin-top: 0;
          font-size: 20px;
        }
        
        h3 {
          margin-top: 0;
          font-size: 18px;
        }
        
        h4 {
          margin-top: 0;
          font-size: 16px;
        }
        
        h5 {
          margin-top: 0;
          font-size: 14px;
        }
        
        h6 {
          margin-top: 0;
          font-size: 12px;
        }
        
        code {
          font-size: 1.2em;
        }
        
        ul {
          padding-inline-start: 20px;
        }
        
        * {
          box-sizing: border-box;
        }
        
        body {
          font-family: sans-serif;
          margin: 20px;
          padding: 0;
        }
        
        .square {
          background: #fff;
          border: 1px solid #999;
          float: left;
          font-size: 24px;
          font-weight: bold;
          line-height: 34px;
          height: 34px;
          margin-right: -1px;
          margin-top: -1px;
          padding: 0;
          text-align: center;
          width: 34px;
        }
        
        .board-row:after {
          clear: both;
          content: '';
          display: table;
        }
        
        .status {
          margin-bottom: 10px;
        }
        .game {
          display: flex;
          flex-direction: row;
        }
        
        .game-info {
          margin-left: 20px;
        }
  </code>
</details>

