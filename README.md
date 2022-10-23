# dropFont
A jQuery function that gives an element a 3D effect
## Usage
First include the file in your project.
Usage:

    $("h1").dropFont(15);
    
   To animate this effect you can do:
   

    function animateDrop() {
      setTimeout(function() {
        $("h1").dropFont(i);
        i++;
        if (i < dropHeight)
          animateDrop();
      }, 25)
    } 
## Result
![result](https://i.imgur.com/RbMFIVJ.png)
## Demo
[View on codepen](https://codepen.io/w0o0o/pen/rNvXbGg)
