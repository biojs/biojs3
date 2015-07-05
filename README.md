# Draft of BioJS 3: Web components

<img width="50%" alt="Web components logo" src="http://webcomponents.org/img/logo.svg" />

Yeah, BioJS is moving to have every module as Web Component with Custom Elements.

This means
* __automatic encapsulation__ thanks to the __shadow DOM__ (no more problems with components modifying your site, id conflicts, css conflicts or problems to create multiple instances of a components)
* __Custom DOM Elements__ - imagine to use __only HTML__ to include a BioJS component into your website

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

## Heavy development and brainstorming is happening here  - you are very welcomed to help us

How to help?
------------

* you have an idea, proposal -> open an issue
* you want to port your (or a) component to polymer -> go for it & discuss your progress with us here :)
* have a look at our [roadmap](https://github.com/biojs/biojs3/wiki) (at the wiki) & get inspired
* you haven't found a task yet, browse through the open issues or ping us on [gitter](https://gitter.im/biojs/biojs)
