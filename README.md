# nearby

There are really two variables of important in this code: an array with a bunch of values in it, and an array with a single value.

This code finds the value in the large array that is closest to the single value. This is quite useful with consistently increasing arrays. It's a little iffy with arrays that don't consistently increase because it identifies the first closest value. If there's a closer value later on it won't find that.
