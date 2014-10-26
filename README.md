Flip-It
=======

"Flip-It" is a .css plugin which will flip your html contents. 


=======
General things to be noted
1) It uses Prespective property of css 
2) Each WHOLE DIV called "FLIP" contains two DIVS called FRONT and BACK.
      ->The FRONT div contains the contents of the front portion of the FLIP div.
      ->The BACK div contains the contents of the back portion of the FLIP div.
3) Finally, by rotating the whole FLIP div in the 3D-Prespective we get a 3D FLip animation..
Very simple isn't it??

========
for FLIP ON JS EVENTS

There are two .js files and two functions to ba called
->For filpping in X-axis on any js events include the flip-it-X-axis-on-js-events.min.js at the end of the body and
you have to call a function flipX(start,stop);
->For filpping in Y-axis on any js events include the flip-it-Y-axis-on-js-events.min.js at the end of the body and
you have to call a function flipY(start,stop);

========
about the function calls:
the two parameters in the two functions flipX() and flipY() allows you to define your js events.

For Example:
flipX('mouseover','click');

Here, it means on 'mouseover' it will flip the FLIP div about 180deg and again on 'click' it will flip the FLIP div
to its original position.

Same case for flipY();

========

See demo for clarifications 

========

Product website http://praneshravi.in/flipit/
For More Projects http://praneshravi.in/
Contact me talkto@praneshravi.in


