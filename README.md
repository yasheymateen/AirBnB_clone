# AirBnB_clone
This project encompasses all of the concepts we have learned in Python. The project built here is a clone of AirBnB. It consists of the console, a portion of the backend, and web static files, a portion for the front-end.  <hr/>
## Updated Version: November 25, 2019
* Previous Version: November 14, 2019


# Command Interpreter (Console)
This particular project focuses on creating a command interpreter to manage AirBnb objects.<br/>

### Models: <br/>
* BaseModel
* User
* State
* City
* Amenity
* Place
* Review


Each model is given a unique id, the 'created_at' attribute specifying when the oject was creeated, 'updated_at' specifying when the object was updated at, adn '__class__' specifiying the object's type.

### Installation
Clone the repository, and you will have the console and the webpage files.

### Usage: <br/>
Run ./console.py in the root directory.
```
./console.py

Documented commands - type help <topic>:
========================================
EOF  all  create  destroy  help  quit  show  update

(hbnb)
```
For the webpage, simply open the 8-index.html file onto your browser. 

### Commands: <br/>
* update  - updates an attribute name by its 'object id' with its attribute value.
* destroy - deletes an object by its 'object id'
* create - creates an object of a specific type.
* show - displays object by its 'object id'
* all - displays all objects of a specific type
* help [command] - shows help of information of a command.

### Example:

```
(hbnb) create BaseModel
e2beccb3-166b-4862-8ac2-595b3438d5ff

(hbnb) update BaseModel e2beccb3-166b-4862-8ac2-595b3438d5ff first_name "Beyonce"

(hbnb) show BaseModel e2beccb3-166b-4862-8ac2-595b3438d5ff
[BaseModel] (49faff9a-6318-451f-87b6-910505c55907) {'first_name': 'Beyonce', 'id': '49faff9a-6318-451f-87b6-910505c55907', 'created_at': datetime.datetime(2017, 10, 2, 3, 10, 25, 903293), 'updated_at': datetime.datetime(2017, 10, 2, 3, 11, 3, 49401)}


```


### AUTHORS (Version 1- Console)
* **Yashar Mateen** - [yasheymateen](https://github.com/yasheymateen)<br/>
* **Aalaa Satti** - [alaksatti](https://github.com/alaksatti)<br/>


## License

MIT License

Copyright (c) [2019]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.