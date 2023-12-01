# Dex Starter Repo (Moralis Blueprint)

Create a Dencentralized Exchange using React and Moralis 

1. Install the backend and the frontend: $ npm install

2. Start the servers

Start the backend: $ node index.js 

Start the frontend: $ npm start

A metamask account with coins in your wallet are needed to make the dex and swap functionality work.

Full tutorial available here: 
https://www.youtube.com/watch?v=t8U7GRrlYW8&pp=ygUTYnVpbGQgYSBkZXggbW9yYWxpcw%3D%3D

With the current implementation we can't use decimal numbers for the token we want to swap.

It can take time for the information to propagate to the 1inch API after a swap. We may need to connect and disconnet our wallet to get the updated data.

