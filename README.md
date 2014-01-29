waterfall
=========

a fluid css framework to change the way we work

It's CSS for those who know css, little shortcuts.

without changing away from your html markup, you can completely design the contruct for your page.

"But Bootstrap does that already, and it's responsive".

Yes you are right, but this is CSS that has no limits.
You can make anything you want with the fluid width system, that is designed so that any human can understand how it works

"thirty  t-fifty p-eighty-five"

If you can figure out what those classes above stand for then you are on the right track.

Lets add some "display" classes and see if you catch those...

"fourty-five left t-sixty float-none t-block t-m-auto p-ninety-five"

ah yes a width of 45% that is floating left, and on a table it is a width of 60% and blocked in the center, and on a phone its a width of 95% still in the center because of the the tablet's "centered" properties.

Lets do a responsive 60 - 30 split div

<code>
<div class="sixty inline-block va-t p-ninety-five p-block">
  <p>I'm Sixty... on a desktop.</p>
</div>
<code>

<div class="thirty inline-block va-t p-ninety-five p-block">I'm Thirty... on a desktop.</div>


In that example I used inline-block instead of floats; Why you may ask? I just perfer to write my code that way, thats why. Oh an va-t stands for vertical-align: top; in case you are unaware how blocks perform.

Lets use that same example, but this time lets make the text "conditional"

<div class="sixty inline-block va-t p-ninety-five p-block">
  <p class="p-none">I'm Sixty... on a desktop.</p>
  <p class="none p-block">Now I am 95%!</p>

</div>
<div class="thirty inline-block va-t p-ninety-five p-block">
    <p class="p-none">I'm Thirty... on a desktop.</p>
    <p class="none p-block">Now I am 95%!</p>
</div>

Just blow your mind? I apologize.




