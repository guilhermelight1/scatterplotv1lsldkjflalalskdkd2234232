Block-a-Day #10. In this Gapminder recreation, continents can be exploded into their constituent countries with a paintball-splatter-like effect.

**Data Sources:** [Gapminder](http://www.gapminder.org/data/).

**What I Learned:** I've wanted to build something with this technique ever since I saw [Nadieh Bremer's](http://bl.ocks.org/nbremer) demonstrations of it. My addition is to create a separate filter definition for each continent, enabling them to be individually transitioned. For more details, check out her [original blog post](http://www.visualcinnamon.com/2015/05/gooey-effect.html) and [follow-up](http://www.visualcinnamon.com/2016/06/fun-data-visualizations-svg-gooey-effect.html).

**What I'd Do With More Time:** The explosions have to wait until the next year tick. I'd like to be able to explode them immediately, but I'm not aware of a way to do this with d3.transition alone, so it would probably require a custom animation loop.

## Block-a-Day

Just what it sounds like. For fifteen days, I will make a [D3.js v4](https://d3js.org) block every single day. Rules:

1. Ideas over implementation. Do something novel, don't sweat the details.
2. No more than two hours can be spent on coding (give or take).
3. Every. Single. Day.

### Previously

* [Map to Force-Directed Graph](https://bl.ocks.org/cmgiven/4cfa1a95f9b952622280a90138842b79)
* [Brushable Scatterplot/Choropleth](https://bl.ocks.org/cmgiven/abca90f6ba5f0a14c54d1eb952f8949c)
* [Treemap Bar Chart](https://bl.ocks.org/cmgiven/018fd027d443b177e18fffb9afcdb5bd)
* [Triangular Scatterplot](https://bl.ocks.org/cmgiven/a0f58034cea5331a814b30b74aacb8af)
* [Choropleth with Animated Stripes](http://bl.ocks.org/cmgiven/09140e2ac8119340048f62d1b241977e)
* [Collatz Conjecture](https://bl.ocks.org/cmgiven/231f779f9655025f38b5b4b828f3b7b0)
* [Bouncing Logo](https://bl.ocks.org/cmgiven/a325f14550a65dc8ff6898ef0f9feeb4)
* [Rectangular Collision Detection](https://bl.ocks.org/cmgiven/547658968d365bcc324f3e62e175709b)
* [Demers Catogram](https://bl.ocks.org/cmgiven/9d6bc46cf586738458c13dd2b5dadd84)


forked from <a href='http://bl.ocks.org/cmgiven/'>cmgiven</a>'s block: <a href='http://bl.ocks.org/cmgiven/e5dfe0888968ee8c507f5469a4d62b6f'>Gooey Exploding Scatterplot</a>