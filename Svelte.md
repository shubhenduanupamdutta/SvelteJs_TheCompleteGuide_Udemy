# Svelte

---

## What is _Svelte_?

---
**According to English Dictionary:**<br>
Svelte is an adjective that means slender and elegant.

**So Svelte is a framework that is all about creating a lightweight, slim application because when we control everything through _JavaScript_ in the browser, that means this _JavaScript_ code has to be downloaded by the users of our web page, before anything happens on the page. And the more complex our code is, the more code has to be downloaded and the slower our page therefore is. Svelte is a tool that allows us to build `lightweight modern web applications` that uses _JavaScript_, but highly optimized _JavaScript_ where you ship as little code as required and then also have code that is not just small in size, but also very efficient when it's executed in the browser.**

### How is this optimization in both loading and running of code achieved?
**Svelte is a compiler, not a framework. The idea behind frameworks like React, Angular and Vue is that you also write some modern JavaScript withing the rules of the framework you are using. And then you ship your code along with the framework or library you are using to the client side (browser). Huge advantage of this approach is that you typically have a lot of great concepts to use, a lot of built-in features, and therefore you have a good time building such applications, and modern frameworks are also pretty small, but by definition they're not as small as svelte. _Because svelte is `no framework`, there is no extra code (framework) being shipped, it instead `compiles your code at build time`._**

**Now, of course, being small is not everything that matters, but it definitely is one thing to consider. The idea behind Svelte is not that you ship your code in framework and then both work together, but you write code using a certain syntax, which you'll learn in this course, and then Svelte is a tool that runs over your code and generates pure vanilla JavaScript code, which is highly optimized, which contains a bunch of instructions which will basically make the things happen in the browser that you want to happen.**