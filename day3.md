Q15) How do you create a simple Express.js application?.

            const express = require('express')
            const app = express();

            app.get('/',(req,res)=>{
                    res.send("welcome to my world")
            });

            app.listen(4000, ()=>{
                    console.log("port is running)
            });
            6) Implementation of all type of exports in backend application?.

=> default Export const Mycomponent =()=>{} export default Mycomponent;

Named Export

     export from Mycomputer.js file
     export const Mycomponent = ()=>{}
     Q11)Explain CORS?. => CORS is a mechanism that uses additional HTTP header to inform a browser to allow a web application running at one origin (domain) have permission to access selected resources from a server at a different origin.
     Q17) Create a middleware which applicalbles to all routes?
     => In route folder it is made..