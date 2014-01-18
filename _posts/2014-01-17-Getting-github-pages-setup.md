---
title: something or other with code
---
{% include header.html param="thing" %}

Just working on getting a post setup, we'll see how this publishes

# Highlighting some code

## Here is some python
{% highlight python %}

import sys

def main(argv = None):
    if argv is None:
        argv = sys.argv[1:]
    print "Got %s" % ' '.join(argv)
    return 0

if __name__ == "__main__":
    sys.exit(main)

{% endhighlight %}

## And maybe here is some Erlang
{% highlight erlang %}
-module(shape).
-export([area/1, area/2])
area(X,Y) ->
    area({square, X, Y}).

area({square, X, Y}) when X > 0 andalso Y > 0 ->
    X * Y.

{% endhighlight %}

{% include footer.html %}
