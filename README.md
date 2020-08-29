# fast-Javascript-SHA1
This is an implementation of SHA1 in Javascript with pre-calculated routines to make it ultra fast, no long winded looping etc.

usage example

var $ = new s2SHA1();
console.log($.sha1('the quick brown fox jumped over the lazy dog'));
//3e4991b48bcb1bd9d3c4c14a1f24c415deaba466

console.log($.sha1('all bound for mu mu land'));
//54cbad8fc5d0455dae4aa57ba1b6896915579095
