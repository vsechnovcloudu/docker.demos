Simple Docker demos
===================

Collection of examples to demonstrate differences between classic operational 
model of classic servers VS operations of containers.

# Litlleserver

Written in Node JS, run it with `node little.js` - on purpose the code is very 
simple, just open your browser and go to `localhost:1234`.  
Do the `docker build .` and study `Dockerfile`. Note down **image id**.  
Finally, run command `docker run -p 1234:1234 <your-image-id>` and access again 
your `localhost:1234`.
