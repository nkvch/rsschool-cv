# Stanislau Stankevich
### JS Front-End developer (student)

#### Contact:
- GitHub

    <https://github.com/nkvch>
- Email

    nkvch.st@gmail.com


### About me

I am a student of [Warsaw University of Technology](https://www.pw.edu.pl/engpw) in Warsaw studying the Automatics and Robotics. Besides of that I attend the [**RSSchool**](https://rs.school/) course of JS Front-End developing. I successfully combine the studying in the university with other activities. Currenctly **interested** in JS Front-End developing (already finished one course in the university related to the web-dev and now start the following in the university and other one in **RSSchol**). I perfectly learn new things on my own from web-sources. 

### Familiar with:

- **Git**
    Using it from Linux terminal. Familiar with GitHub and Git-Lab.
- **Linux terminal (Bash)**
- **Python**
    Have one small study project on **Tkinter** lib. Also a ROS-based study project.
- **ROS** (Robot Operating System :) )
- **C++**
    Have one group project-game.
- **JS, Node JS**
    Have a small fullstack example-app written in NodeJS (Express framework)
- **Java**
    Familiar with syntax.
- **SQL basics**
- **Non-relating DB (MongoDB) basics**

### Example code (server on NodeJS (Express) ):
```
const express = require('express')
const app = express();
const port = 3000

const {MongoClient} = require('mongodb');
var url = "mongodb://localhost:27017";

app.use((req, res, next) => {
  console.log(req.method, req.url);
  next();
 });

var bodyParser = require('body-parser');
app.use(bodyParser.json()); // support json encoded bodies
app.use(bodyParser.urlencoded({ extended: true })); // support encoded bodies


app.use(express.static('static'))

app.listen(port, () => {
    console.log(`Example app listening at ` + 
                `http://localhost:${port}`   );
  })

```

### English level

**B2** with speaking experience.
