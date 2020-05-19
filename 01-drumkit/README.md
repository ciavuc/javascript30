# JS30 - Drumkit
[![Netlify Status](https://api.netlify.com/api/v1/badges/fd025c35-3846-4d58-8e5d-7e0a644fb322/deploy-status)](https://app.netlify.com/sites/amazing-kare-d58ebf/deploys)

##### [30 day Vanilla JS challenge](https://github.com/wesbos/JavaScript30) by Wesbos

🕑 Coding time: ~30mins

🔗 URL: [Ciavuc.co - JS30 - 01 - Drumkit](https://amazing-kare-d58ebf.netlify.app/)

A drumkit that takes a key input, uses the data-key attribute to play an associated sound with that key. 

#### 🧐 Findings
For me, selecting all keys, then looping through each with `keys.forEach(key => key.addEventListener('transitionend', removeTransition));` on every single keydown seemed less efficient than just setting a timeout to remove the animation once finished, so I left that part out.
