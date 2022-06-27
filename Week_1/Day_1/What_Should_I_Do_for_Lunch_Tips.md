### Tips

```javascript
const whatToDoForLunch = function(hungry, availableTime) {
  console.log("I don't know what to do!");
 
  //check if i am even hungry
  if (hungry === true) {
    //check the time I have to eat if im hungry
    if (availableTime < 20) {
      console.log("I should just grab a snack.");
    } else if (availableTime >= 20 && availableTime <= 30) {
      console.log("I can grab lunch at a nearby place quickly.");
    } else if (availableTime > 30) {
      console.log("I really dont have more than 30 minutes, I should just grab lunch somewhere nearby and get back to work.");
    }
  } else {
    console.log("I am not hungry, I should get back to work");
  }
};
```
