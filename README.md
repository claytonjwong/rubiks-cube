# Rubik's Cube
![](rubiks_cube.png)

> Whether you think you can, or you think you can't - you're right.
>
[-Henry Ford](https://en.wikipedia.org/wiki/Henry_Ford)

First off, let me begin with the end in mind.  That is, anyone can solve a Rubik's cube.  It's just something new to learn.  Like all things in life, acquiring a new skill is a simple but *not* easy process which requires humility and continual effort (ie. be humble and don't give up).  For example, look at a child learning how to walk.  The child basically falls over and over again, but keeps getting back up and trying again.  That's how we learn.  We are primitive creatures with primitive brains which are *not* designed to efficiently handle the modern world's "problems".  Our brains require repetition along with focused and diffused modes of thinking to learn.  Our brains operate as a left/right synergistic pair capable of generating understanding, meaning, or semantics, that is, what has been learned, which can only be acquired in hindsight (ie. there is no magical foresight to learning, it takes time and effort).

> Real genius is nothing else but the supernatural virtue of humility in the domain of thought.
>
[-Simone Weil](https://en.wikipedia.org/wiki/Simone_Weil)

I first learned to solve a Rubik's cube with the Beginner's Method.  This took me about 1-year to accomplish.  And 6 months later, I could easily solve the cube with the Beginnner's Method in under 2 minutes.  At this time, I had put enough time and effort into this puzzle to autonomously understand the fundamental movements of the cube and the side-effects of those movements with adjacent and opposite pieces.  The Fridrich Method (ie. CFOP: Cross, F2L, OLL, PLL) followed as a natural progression of this intuition.  Basically when formulating a bottom-up solution, properly placed pieces remain immutable while incorrectly placed pieces are allowed to move freely.  Thus, loop invariance and idemptotence are vital, fundamental concepts and building blocks towards a solution which sequentially builds upon itself.

## Tutorial
> I can only show you the door. You’re the one that has to walk through it.
>
[-Morpheus (The Matrix, 1999)](https://en.wikipedia.org/wiki/The_Matrix)

* [Introduction and Overview](https://www.youtube.com/watch?v=FpV8LeDJlXQ)
* [Know Your Cube](https://www.youtube.com/watch?v=KRiHwcC6oCo)
* [White Cross](https://www.youtube.com/watch?v=4U1eGLw3X8k)
* [White Corners](https://www.youtube.com/watch?v=xIC4tbCTcqo)
* [Middle Layer](https://www.youtube.com/watch?v=DAm2iH-lDFU)

## Demonstration
* [Rubik's Cube Solutions: Beginner's Method and Fridrich Method](http://www.youtube.com/watch?v=lbKGoJQKRRE)

## Beginner's Method

> Take the first step in faith. You don't have to see the whole staircase, just take the first step.
>
[-Martin Luther King Jr.](https://en.wikipedia.org/wiki/Martin_Luther_King_Jr.)

* [https://www.youcandothecube.com/solve-it/3-x-3-solution](https://www.youcandothecube.com/solve-it/3-x-3-solution)
* [https://ruwix.com/the-rubiks-cube/how-to-solve-the-rubiks-cube-beginners-method/](https://ruwix.com/the-rubiks-cube/how-to-solve-the-rubiks-cube-beginners-method/)
* [https://www.ryanheise.com/cube/beginner.html](https://www.ryanheise.com/cube/beginner.html)

## Fridrich Method (ie. CFOP: Cross, F2L, OLL, PLL)
> What are you waiting for? You're faster than this. Don't think you are, know you are.
>
[-Morpheus (The Matrix, 1999)](https://en.wikipedia.org/wiki/The_Matrix)

* [http://en.lerubikscube.com/fridrich-method-3x3/](http://en.lerubikscube.com/fridrich-method-3x3/)
* [http://loki.ist.unomaha.edu/~jtrimm/project/ollpll.html](http://loki.ist.unomaha.edu/~jtrimm/project/ollpll.html)

## 3 Look OLL - Orientation of the Last Layer

> To be yourself in a world that is constantly trying to make you something else is the greatest accomplishment.
>
[—Ralph Waldo Emerson](https://en.wikipedia.org/wiki/Ralph_Waldo_Emerson)

In order to solve the cube using the Fridrich Method, over 80 algorithms are needed.  Honestly, I've never really cared to learn all of these sequences.  Instead I ended up creating what I like to refer to as a **3 Look OLL**, for which only 4 algorithms are necessary (obviously this is slower, but only by a few seconds, so that's good enough for me!):

### 1. First Look OLL

Generate the yellow cross

### 2. Second Look OLL

Repeat the sequence (```R U R' U R U2 R'```) while the yellow-side is in any of the following states:

* Fish Swimming Left
* Fish Swimming Right
* Diagonals (ie. double headed fish)
* Double Headlights
* Chameleon Car

**Note:** refer to [http://loki.ist.unomaha.edu/~jtrimm/project/ollpll.html](http://loki.ist.unomaha.edu/~jtrimm/project/ollpll.html) for detailed descriptions of the above yellow-side states

### 3. Third Look OLL

After the Second Look OLL is finished, the yellow-side is in one of the following 3 states:

* Solved
* Headlights
* Chameleon

If the yellow side is solved, then move onto the permutations of the last layer (ie. PLL) to properly align the corners and edges of the last layer.  Otherwise, solve the Headlights/Chameleon:

* **Headlights:**
	* Turn the cube so that the headlights are on the front face
	* Perform the sequence (```R2 D R' U2 R D' R' U2 R'```)
* **Chameleon:**
	* Turn the cube so that the chameleon is facing you.  Perform an X' turn (the whole cube rotated counterclockwise on X axis, ie. the top should now be front)
	* Perform the sequence (```R U R' D R U' R' D'```)

**Note:** refer to [http://loki.ist.unomaha.edu/~jtrimm/project/ollpll.html](http://loki.ist.unomaha.edu/~jtrimm/project/ollpll.html) for detailed descriptions of the above yellow-side states

## Resources
* [ruwix.com](https://ruwix.com/)
* [rubiks-cu.be](https://rubiks-cu.be/)
* [rubiks-cube-solver.com](https://rubiks-cube-solver.com/)