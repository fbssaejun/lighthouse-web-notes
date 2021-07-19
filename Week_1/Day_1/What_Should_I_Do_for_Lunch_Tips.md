### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
const whatToDoForLunch = function(hungry, availableTime) {
  if (hungry && availableTime < 20) {
    console.log("Pick up something and eat in back in the lab or in the kitchen!");
  } else if (hungry &&  availableTime >= 20 && availableTime <= 30) {
    console.log("You deserve a break, so try some place in Gastown!");
  } else if (hungry && availableTime > 30) {
    console.log("You should probably reconsider, this is a bootcamp!");
  } else {
    console.log("Get back to work!");
  }
};
```