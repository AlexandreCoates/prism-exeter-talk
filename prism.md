## PRISM Exeter 2021

---
### An introduction

I'm Alex (he/him), and

---

### Let's start with a picture a friend made for me
#### Now try navigating downwards to the sub-slide <!-- .element: class="fragment" -->
<section> 
    <img class="r-stretch" src="img/alex_drawing.png"> 
</section>

--

## Hi

You can hit ESC or 'O' to see an overview of the whole slideshow

#### You can move on now 

Go on... 

---

### Animations of Localisation

_While this format can output to pdf, an advantage is that is can support videos_. Scroll down to see some animations I've made. 

1. Anderson Localisation
2. Wannier-Stark Localisation

--

### Increasing linear potential applied to a length 20 chain

<section>
    <video controls class="r-stretch" src="img/gradient_localisationN20.mp4"></video>
</section>

--

### Random disorder on a chain of 20 sites
<section>
    <video controls class="r-stretch" src="img/anderson_localisationN20.mp4"></video>
</section>

---

#### We can also do some maths typesetting with MathJax

$$ A = \frac{4}{3} \pi r^2 $$

$$ |\Psi (t)\rangle =e^{-i{\hat {H}}t/\hbar }|\Psi (0)\rangle$$

---

#### Last but not least, code highlighting

<section>
    <pre><code data-trim data-noescape data-line-numbers="1-6,15">
def fib(): #fibonacci sequence
    x,y = 0,1
    while True:
        yield x
        x,y = y, x+y
def even(seq): #evaluate if element is even
    for number in seq:
        if not number % 2:
            yield number
def under_a_million(seq): #if <1million then add to sum
    for number in seq:
        if number > 1000000:
            break
        yield number   
print sum(even(under_a_million(fib())))
    </code></pre>
</section>

--

## Slide 1.2
subslide

---

## Slide 2
next slide

---

# Slide 3

What about two subslides?

--

## Slide 3.1

--

## Slide 3.2

Hello, you are at the bottom. 