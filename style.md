Based on 50380 `Document::updateStyle` observations over 1200 runs.

Style update
------------

![](style_files/figure-markdown_github/unnamed-chunk-2-1.png) ![](style_files/figure-markdown_github/unnamed-chunk-2-2.png) ![](style_files/figure-markdown_github/unnamed-chunk-2-3.png)

Rail
----

Found 4880 RAIL interaction records. 27.36% of observations were not classified:

-   229 response
-   232 animate
-   2099 idle
-   2320 load

Individual observations:

![](style_files/figure-markdown_github/unnamed-chunk-4-1.png)

Aggregated by RAIL iteraction record:

![](style_files/figure-markdown_github/unnamed-chunk-5-1.png)

Callees
-------

4.71% of thread time spent in traced children.

![](style_files/figure-markdown_github/unnamed-chunk-7-1.png)

Callers
-------

There were 511 unique trace stacks. 39.65% of stacks and 44.25% of thread time involves `V8.Execute`.

![](style_files/figure-markdown_github/unnamed-chunk-9-1.png)

Style Sharing
-------------

Style sharing rate: 18.25%

![](style_files/figure-markdown_github/unnamed-chunk-11-1.png) ![](style_files/figure-markdown_github/unnamed-chunk-11-2.png) ![](style_files/figure-markdown_github/unnamed-chunk-11-3.png)

Matched properties cache
------------------------

Non-inherited hit rate: 61.35%

Inherited hit rate: 36.66%

![](style_files/figure-markdown_github/unnamed-chunk-12-1.png) ![](style_files/figure-markdown_github/unnamed-chunk-12-2.png) ![](style_files/figure-markdown_github/unnamed-chunk-12-3.png)

Rules matched / rejected
------------------------

Of the rules considered:

-   7.13% matched
-   68.26% were rejected by the bloom filter
-   24.61% were rejected by evaluation

![](style_files/figure-markdown_github/unnamed-chunk-14-1.png) ![](style_files/figure-markdown_github/unnamed-chunk-14-2.png) ![](style_files/figure-markdown_github/unnamed-chunk-14-3.png)

Styles un/changed
-----------------

Warning: This section isn't entirely accurate yet.

Based on 34751 `Document::updateStyle` observations.

17.57% of styles produced were identical to the previous state.

![](style_files/figure-markdown_github/unnamed-chunk-16-1.png)
