# ArcAnimator
ArcAnimator helps to create arc transition animation: 2.3+

<img width="180" height="320" src="http://i.imgur.com/DSiQxbg.gif" />|<img width="180" height="320" src="http://i.imgur.com/aLcLrGk.gif" />

ArcAnimator Demo   |   TransitionLoop Demo*

*TransitionLoop Prototype  by Min-Sang Choi <a href="https://dribbble.com/shots/1828095-Chaining-Animation-with-framerjs">Dribbble</a>

- <a href="https://www.youtube.com/watch?v=ePvGyL-_0DA" target="_blank">YouTube Video for #1 gif</a>
- <a href="https://www.youtube.com/watch?v=jMNkmxqG0zQ" target="_blank">YouTube Video for #2 gif</a>

Usage
===
```java
  //set up clipView and coordinates where clipView will move
  ArcAnimator arcAnimator = ArcAnimator.createArcShift(clipView, endX, endY, DEGREE, SIDE)
                    .setDuration(500)
                    .start();
  
  //or specify nestView for clipView. Animator will take center x,y coordinates of nestView
  ArcAnimator arcAnimator = ArcAnimator.createArcShift(clipView, nestView, DEGREE, SIDE)
                    .setDuration(500)
                    .start();
```

Dependency
===
- Library uses Jake Wharton's <a href="https://github.com/JakeWharton/NineOldAndroids/">NineOldAndroids</a> to support 2.3.+ devices.
- Ozodrukh's <a href="https://github.com/ozodrukh/CircularReveal">CircularReveal</a> helped to create awesome TransitionLoop Demo

License
--------

    The MIT License (MIT)

    Copyright (c) 2015 Asylbek Isakov
    
    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:
    
    The above copyright notice and this permission notice shall be included in
    all copies or substantial portions of the Software.
    
    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
    THE SOFTWARE.
