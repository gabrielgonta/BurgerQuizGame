# 🕹️ Burger Quiz - React Version

## Description

Welcome to Burger Quiz - React Version! 🎉 This project is an adaptation of the famous TV game show Burger Quiz, developed with the React library.

The game retains the fun principles of the show: two teams, "Ketchup" and "Mayo," compete with each other in absurd, quirky, but always entertaining questions. With a modern and responsive interface, you can relive the Burger Quiz experience directly from your browser, either solo or with friends.

## Prerequisites
Install NodeJs : https://nodejs.org/fr/

## Installation

Clone the repository:

```
git clone https://github.com/gabrielgonta/BurgerQuizGame.git
```

Navigate to the root directory where the 'package.json' file is located, then run the command to install the dependencies :

```
cd BurgerQuizGame
npm install
```

## Deployment

Once the dependencies are installed, you can start the application :

```
node server.js
```

By default, the server listens on port **3000**. 

You can now access the application via this address : http://localhost:3000/, which allows you to select a team (Ketchup / Mayo) :

<p align="center">
<img src="https://user-images.githubusercontent.com/25900708/52507764-ce9d3500-2bf2-11e9-91ba-4518018d0a5f.png" height="300"> 
</p>

Open a second tab and type the following address : http://localhost:3000/game :

You will arrive at a screen where players can scan a **QR-Code** to join and directly choose their teams:

<p align="center">
<img src="https://user-images.githubusercontent.com/25900708/80916842-8fa95100-8d5b-11ea-8a51-c097a5bee720.PNG" height="300"> 
</p>

Once everyone is ready, you can click the button: **Everyone is ready !**.

You will finally arrive at the game screen :
<p align="center">
<img src="https://user-images.githubusercontent.com/25900708/52507593-461e9480-2bf2-11e9-9882-60ca26b7a568.png" height="300"> 
</p>

This page is the main screen of the application. 
It displays each team's score, triggers various transitions (nuggets, salt & pepper, menus, bill, burger of death), and allows activating the cheese buzzer.

Finally, open one last tab: http://localhost:3000/admin :

<p align="center">
<img src="https://user-images.githubusercontent.com/25900708/52508059-977b5380-2bf3-11e9-8e7f-9c875a5a5718.png" height="300"> 
</p>

This page allows you to manage the game. You can add points for the teams, trigger transitions, and lock/unlock the cheese buzzer.

**NOTE** : If you are using **Google Chrome**, click on the game window once, as you may encounter an error like **'Uncaught (in promise) DOMException'**, preventing the animation from starting.

## Authors

* **Gabriel Gonta** - *Initial work* - [BurgerQuizGame](https://github.com/gabrielgonta/BurgerQuizGame.git)




