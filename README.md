# Front end challenge

Mrs. Peppers produces tasteous mangos in his farm and all of his clients love him. One day Mrs. Elephant called him at night and desesperated asked him to send the maximum number of mangos he could, because he would have a big party next day!

Mrs. Peppers wants us to help him, so we need to design a way in which he can package almost everything in his truck. So imagine that his truck is **300x192cm** and his boxes are **54x42cm**, so the maximum he can put on his truck 25 boxes.

Our challenge is to create an algoritm to show how he can layout the box position to fit everything, like this:

```
Bad layout example:

           300
x-------------------------x
|         |         |     |              
|         |         |     |
|  54x42  |  54x42  |     | 192
|         |         |     |     
|         |         |     |          
x-------------------------x

Total: 2 boxes


Good layout example!

           300
x-------------------------x
|         |               |
|         |     42x52     |
|  54x42  |---------------| 192
|         |     42x52     |
|         |               | 
x-------------------------x

Total: 3 boxes

```

Be creative!
