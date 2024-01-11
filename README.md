
# Project Title

Store Project


## Overview
This project involves stores and items. Each store contains specific items, and the warehouse encompasses all the stores. The stores and items are linked throught the randomly generated ids. 
## Deployment



```bash
sudo docker build -t rest-api .

```

```bash
sudo docker run -p 5000:5000 rest-api

```

To auto run the docker whenever some changes are done in the app. (Optional)


```bash
sudo docker run -dp 5000:5000 -w /app -v "$(pwd):/app" rest-api
```
## Example

items = {67ddd636b0ed42a0adc8c7881d16c28d : "Name" : :Chair",
                                             "Price" : 17.99,
                                             "item id" : 67ddd636b0ed42a0adc8c7881d16c28d
                                             };


store = {9805c262c62b4643becc07dc51f84a51 : {"id": "9805c262c62b4643becc07dc51f84a51",
   					     "name": "My Store2"
  				             },
                   
## Screenshots

Create (post) a new store

![Screenshot from 2024-01-11 19-55-08](https://github.com/rkirtii/Store-Hub-API/assets/142138548/5f1d0f12-5051-41f7-a207-388bf5f63415)


Get all stores

![Screenshot from 2024-01-11 19-54-39](https://github.com/rkirtii/Store-Hub-API/assets/142138548/c6c4497e-0b9a-4e61-9d47-d9664b459506)

Get specific store from store id

![Screenshot from 2024-01-11 19-54-48](https://github.com/rkirtii/Store-Hub-API/assets/142138548/dfe27967-64de-4c41-bb8b-f1f96456e7e1)

Get all store items

![Screenshot from 2024-01-11 19-54-57](https://github.com/rkirtii/Store-Hub-API/assets/142138548/6013453f-ff52-4c4a-99bb-40c0cd049628)


