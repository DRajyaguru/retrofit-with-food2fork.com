# retrofit-with-food2fork.com
This will provide food data in JSON form and display it using RecyclerView and CardView.

## **Usage** ##
![image](https://image.ibb.co/gnqRQT/ezgif_com_video_to_gif_2.gif)

**Gradle**

    allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}

    dependencies {
         implementation 'com.github.hajiyevelnur92:retrofit-with-food2fork.com:v1.0'
    }
#### **Code**

```json
{
count: 30,
recipes: [
{
publisher: "Closet Cooking",
f2f_url: "http://food2fork.com/view/35382",
title: "Jalapeno Popper Grilled Cheese Sandwich",
source_url: "http://www.closetcooking.com/2011/04/jalapeno-popper-grilled-cheese-sandwich.html",
recipe_id: "35382",
image_url: "http://static.food2fork.com/Jalapeno2BPopper2BGrilled2BCheese2BSandwich2B12B500fd186186.jpg",
social_rank: 100,
publisher_url: "http://closetcooking.com"
},
...
]}
```







### [License](./LICENSE)
