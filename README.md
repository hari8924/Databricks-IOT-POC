Databricks Project 
we haave data from iot device that is smartwatch it will send data about users registration user profile
bpm data of user, workout session data of user, login/logout user from gym, etc. frequently
we are loading that data using kafka framework , doing transformation on that data using different methods.

**As shown in above diagram we have **5 storage layer directories in the DLS**. then we have **databricks unity catalog** we created dev catalog to implement security for the development environment, behind the dev catalog we are creating 3 databases we have setup dev, qa, and production environment according to the design shown above.**

**The above image shows the flow of working**
