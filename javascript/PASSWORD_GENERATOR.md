# JavaScript Password Generator

The goal of this project is to randomly generate passwords, if you want to go above and beyond you can add customized settings, or even password copying and generator settings! This project will teach you some basic methods that will be important to many other projects, such as using the `Math` object.

## Hint(s)
<details>
  <summary>How to generate a random string.</summary>
    It's pretty simple to generate a random string, all you have to do is:
```
  
    function randomize(length) {
      let possible = "qwertyuiopasdfghjklzxcvbnmQWERTYUIOPASDFGHJKLZXCVBNM!";
      let characterArray = possible.split('');
      let final = "";
      for(let i = 0; i < length; i++){
        final+=characterArray[Math.floor(Math.random() * characterArray.length)];
      }
      return final;
    }
    /* now you can use randomize(10) and get a random string that is 10 characters long! */
```
</details>

Submitted by [sqwyer](https://github.com/sqwyer)
