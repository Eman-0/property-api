#### Configuration
<p>
server.js expects a .env that contains:
<br />
LISTEN_PORT={}
</p>

#### Building
<p>
npm install
</p>

#### Running
<p>
npm run dev
</p>

#### Unit Testing Issues
<p>
We could get the unit testing to work locally but we're unable to run our unit tests in the esal4 enviorment due to it saying that we were missing a chai module.
Our tests Working Locally: https://ibb.co/PrwDW5T
Resolving the issue by installing chai in our scripts prior to deployment: https://ibb.co/K2GYgpr
Being unable to run our tests due to an issue with chai: https://ibb.co/Tmp1bzw

In conclusion, we were unable to figure out how to resolve this issue and hope that we can recive partial points for the unit testing secrion.
</p>
