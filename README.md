# LeaderBoard
## Hosted Link:-  https://rohitdhawale07.github.io/LeaderBoard/
This project is consists of creating a leaderboard which will show the all data about a perticular player.
While creating a html we created four type of inputs and one add button.
## HTML code
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link rel="stylesheet" href="./style.css" />
  </head>
  <body>
    <div class="mainContainer">
      <h1>LeaderBoard</h1>
      <div class="form">
        <input type="text" id="fName" placeholder="First Name" />
        <input type="text" id="lName" placeholder="Last Name" />
        <input type="text" id="country" placeholder="Country" />
        <input type="number" id="score" placeholder="Score" />
        <button id="AddDetailsButton">Add Player</button>
      </div>
      <div id="scoreMainContainer"></div>
    </div>
    <script src="./index.js"></script>
  </body>
</html>
```

## CSS code
```
body {
    background: #f1eeee;
    color: black;
  }
  
  .mainContainer {
    width: 65%;
    margin: auto;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
  }
  
  #scoreMainContainer {
    width: 100%;
  }
  
  .scoreBoard{
    display: flex;
    justify-content: space-around;
    align-items: center;
    margin: 1.5rem 0;
    border-radius: 10px;
    border: 1px solid black;
    background-color: rgb(250, 215, 169);
  }
  
  .scoreBoard p {
    width: 20%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 1.5rem;
    font-weight: 600;
  }
  
  input {
    padding: 0.5rem 0.8rem;  
    outline: none;
    background-color: transparent;
    color: black;
    border-radius: 7px;
    font-weight: 600;
  }
  
  button{
      padding: .3rem .5rem;
      border: none;
      background-color: rgb(91, 91, 241);
      color: white;
      font-size: 1rem;
      font-weight: 900;
      cursor: pointer;
      border-radius: 4px;
  }
  button:hover{
    background-color: white;
    color: black;
    border: 2px solid black;
    border-radius: 3px;
  }
  ```
While creating a JAVASCRIPT part we added "click" type of event to the addbutton.
when we click on add button it will perform its predefined function.
For displaying player data we created one div tag and multiple paragraph tags inside it for storing first name, last name, country, score and delete icon.

## JAVASCRIPT code
```
body {
    background: #f1eeee;
    color: black;
  }
  
  .mainContainer {
    width: 65%;
    margin: auto;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
  }
  
  #scoreMainContainer {
    width: 100%;
  }
  
  .scoreBoard{
    display: flex;
    justify-content: space-around;
    align-items: center;
    margin: 1.5rem 0;
    border-radius: 10px;
    border: 1px solid black;
    background-color: rgb(250, 215, 169);
  }
  
  .scoreBoard p {
    width: 20%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 1.5rem;
    font-weight: 600;
  }
  
  input {
    padding: 0.5rem 0.8rem;  
    outline: none;
    background-color: transparent;
    color: black;
    border-radius: 7px;
    font-weight: 600;
  }
  
  button{
      padding: .3rem .5rem;
      border: none;
      background-color: rgb(91, 91, 241);
      color: white;
      font-size: 1rem;
      font-weight: 900;
      cursor: pointer;
      border-radius: 4px;
  }
  button:hover{
    background-color: white;
    color: black;
    border: 2px solid black;
    border-radius: 3px;
  }
  ```
