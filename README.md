# Eye-Exercise
## Eye Exercise
<img src = "oneeye.png" width = "300" />

**Project description:**


Making use of the mouse on web pages makes practical use of the mouse where the eyes follow the movement of the mouse cursor across the screen.
The main command is as follows:
```js
document.onmousemove = (event) => {...}
```


**How it is executed:**

The core part of the movement of the eyes are in the following function: 

 ```js
for (let i = 0; i < 2; i++) {
    balls[i].style.left = x;
    balls[i].style.top = y;
    balls[i].transform = 'translate(-' + x + ',-' + y + ')';
  }
```

But you can see all the code in the following link: <a href="">Eyes</a>



**Roadmap of Future Improvments:**


We could include a row of eyes that go following the movement of the courses, also make the eyes open and close, also make a productivity app in tasks where it opens the eyes while a task is being performed and close when the time of the task has been executed.

**License Information** 

MIT License


