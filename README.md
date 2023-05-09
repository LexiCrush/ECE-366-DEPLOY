# Deploying Lexicrush
This guide provides instructions for deploying Lexicrush on an Ubuntu Droplet server from Digital Ocean. 

## Steps 
1. Spawn and enter Droplet.
2. Run the following commands:
    ```
    sudo apt update
    sudo apt install openjdk-17-jre-headless
    mkdir /artifact
    cd artifact
3. Clone [lexicrush-frontend](https://github.com/LexiCrush/lexicrush-frontend) & [lexicrush-server](https://github.com/LexiCrush/lexicrush-server)
4. Copy in run.sh
    <pre><code class="language-sh">
    cd /artifact/lexicrush-server
    nohup mvn spring-boot:run &
    cd /artifact/lexicrush-frontend
    npm i
    nohup npm start &
    </code></pre>
5. 
    ``` 
    ./run.sh

The game is now running on http://DropletIP:3000

# Ethics 
## Disclaimers
- Lexicrush stores passwords and access tokens in plain text and does not embed signatures from client or server side. As a result, data is not secure and is vulnerable to SQL injections or any other type of attack (please do not submit vulnerable or private information into any field).
#### 1. We accept full responsibility for our work.
The negative and positive aspects of our game are the product of our work. 
#### 2. Provided service in our areas of competence, being honest and forthright about any limitations in our experience and education.
We had to modify our original plan to account for some limitations in our knowledge. 
#### 3. Strived to fully understand the specifications for software on which we worked.
We looked through online documentation to understand the softwares used. 
#### 4. Assisted colleagues in professional development.
We helped each other overcome any obstacles or worked on certain parts together if we were struggling on our own. 
#### 5. Credited fully the work of others and refrained from taking undue credit.
We divided up tasks for each of us to avoid taking undue credit. 
#### 6. Ensured proper and achievable goals and objectives for the project.
We made sure our project consisted of tasks we can properly implement, even if this meant revising our original plan. 
#### 7. Assigned work only after taking into account appropriate contributions of education and experienced tempered with a desire to further that education and experience.
We each decided to work on parts of the project that we had some familiarity with and areas that we are interested in. 
#### 8. Used only accurate data derived by ethical and lawful means and used it only in ways properly authorized.
All data used to produce our game was obtained legally from publically accessible sites and was not used inappropriately.  
#### 9. Improved our understanding of the software and related documents on which we worked and of the environment in which they will be used.
We used online sources to understand how the softwares we used could be used to implement different aspects of our project.     
#### 10. Did not influence others to undertake any action that involved a break of this Code.
We ensured that each of us were abiding by this Code and did not convince anyone to go against this Code. 


# Sources
Space: https://codepen.io/DXC/pen/KXePxm
Login Page: https://codepen.io/mamislimen/pen/jOwwLvy
Alien: https://codepen.io/SofiaSergio/pen/aYqEQv
Profile: https://codepen.io/alvaromontoro/pen/ebPEWb
Astronaut: https://codepen.io/Coding-Artist/pen/gjZJOZ
Glitch Text: https://codepen.io/kevinpowell/pen/YzqerQm
