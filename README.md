# Draft of BioJS 3: Web components

<img width="50%" alt="Web components logo" src="http://webcomponents.org/img/logo.svg" />

Yeah, BioJS is moving forward to have every module as Web Component with Custom Elements!
 
[![Join the chat at https://gitter.im/biojs/biojs3](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/biojs/biojs3?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

As an overview you might want to watch _[A jump through web wormholes](https://www.youtube.com/watch?v=zja0ghmVqjw) by [@greenify](github.com/greenify) that givens an introduction why Web Components are the future for BioJS.

What are Web Components?
------------------------

"Web Components are a set of standards currently being produced by Google engineers as a W3C specification that allow for the creation of reusable widgets or components in web documents and web applications. The intention behind them is to bring component-based software engineering to the World Wide Web." (Wikipedia)

Why Web Components?
-------------------

* __automatic encapsulation__ thanks to the __shadow DOM__ (no more problems with components modifying your site, id conflicts, css conflicts or problems to create multiple instances of a components)
* __Custom DOM Elements__ (new HTML elements e.g. just for biological data)

Everyone is familiar with HTML and can add a `<button>` DOM element to their website. Why not let them add a `<biojs-msa>` element?

Imagine to include an multiple sequence alignment into your website with a short HTML snippet like this:

```
<biojs-msa>
  <biojs-io-fasta url="./Q7T2N8.fasta" />
</biojs-msa>
```

Why now?
--------

* The first official release of Polymer (version 1.0) was at this year's Google I/O (2015-05-29)
* The Polymer project worked hard to reduce the Web Component polyfill to a lightweight shim
* Supported in Chrome since version 36
* Web components will be the __future__!

Not convinced yet?
------------------

Have a look at the presentations listed at [webcomponents.org](http://webcomponents.org/presentations/) - especially:
* [Polymer and modern web APIs: In production at Google scale](https://www.youtube.com/watch?v=fD2As5RmM8Q) at this year'S Google I/O by the Polymer dev team
* [Why you should be using Web Components now. And how](https://leggetter.github.io/web-components-now/dunddd-2014/#1) by Phil Leggetter (@leggetter)
* [Componentize The Web: Back To The Browser!](https://www.youtube.com/watch?v=GOPXVLxp9Nc) by Addy Osmani
(@addyosmani)
* [Polymer and Web Components change everything you know about Web development](https://www.youtube.com/watch?v=8OJ7ih8EE7s) by Eric Bidelman (@ebidel)
* [A future called Web Components](https://vimeo.com/97308701) by Zeno Rocha (@zenorocha)

What is the roadmap?
---------------------

Our roadmap is work in progress, please look at our [github wiki](https://github.com/biojs/biojs3/wiki).

How to help?
------------

Currently there is development and brainstorming is happening [here at github](https://github.com/biojs/biojs3)

* If you have an idea, proposal -> don’t hesitate to open an issue
* IF you want to port your (or a) component to polymer -> go for it & discuss your progress with us here :)
* Have a look at our [roadmap](https://github.com/biojs/biojs3/wiki) (at the wiki) & get inspired
* If you haven't found a task yet, browse through the open issues or ping us on [gitter](https://gitter.im/biojs/biojs)
