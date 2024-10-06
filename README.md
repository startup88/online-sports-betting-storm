# 🎰 Sports Betting

## Installation

- First, install node verion +18 environment.
  Then, run the following scripts:

```
npm install
npm run dev
```

- Second, install python.
  run index.py using Python.

## Application

In its initial iteration, Four Alpha uses an in-house Python engine to gather odds from 15+ international bookmakers on 60+ sports betting markets. The engine parses the response and algorithmically detects arbitrage opportunities for a given event. We run the engine on both historical odds to generate a record of past arbitrage opportunities as well as live odds to detect current available arbitrage opportunities.

When arbitrage is detected, a record of it is created and stored in Firebase. Our React front end connects to the Cloud Firestore and grabs all of the arbitrage records to put on display. The front end is deployed and hosted on Vercel.

## Softwares and Technologies

<div align="center">
 <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54"/>
  <img src ="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"/>
<img src ="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" />
</div>
<div align="center">
<img src ="https://img.shields.io/badge/firebase-ffca28?style=for-the-badge&logo=firebase&logoColor=black" />
  <img src ="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)DF1E"/>
   <img src ="https://img.shields.io/badge/Tailwind%20CSS-06B6D4.svg?style=for-the-badge&logo=Tailwind-CSS&logoColor=white"/>
   <img src="https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white"/>
</div>

---

_© 2023 Four Alpha_
