Based on 28202 `Document::updateStyle` observations over 801 runs.

Style update
------------

![](style_files/figure-markdown_github/unnamed-chunk-2-1.png) ![](style_files/figure-markdown_github/unnamed-chunk-2-2.png) ![](style_files/figure-markdown_github/unnamed-chunk-2-3.png)

Rail
----

Found 3266 RAIL interaction records. 18.55% of observations were not classified:

-   214 response
-   211 animate
-   1387 idle
-   1454 load

Individual observations:

![](style_files/figure-markdown_github/unnamed-chunk-4-1.png)

Aggregated by RAIL iteraction record:

![](style_files/figure-markdown_github/unnamed-chunk-5-1.png)

Callees
-------

2.3% of thread time spent in traced children.

![](style_files/figure-markdown_github/unnamed-chunk-7-1.png)

Callers
-------

There were 361 unique trace stacks. 45.73% of stacks and 42.61% of thread time involves `V8.Execute`.

![](style_files/figure-markdown_github/unnamed-chunk-9-1.png)

Style Sharing
-------------

Style sharing rate: 19.4%

![](style_files/figure-markdown_github/unnamed-chunk-11-1.png) ![](style_files/figure-markdown_github/unnamed-chunk-11-2.png) ![](style_files/figure-markdown_github/unnamed-chunk-11-3.png)

Matched properties cache
------------------------

Non-inherited hit rate: 62.93%

Inherited hit rate: 37.04%

![](style_files/figure-markdown_github/unnamed-chunk-12-1.png) ![](style_files/figure-markdown_github/unnamed-chunk-12-2.png) ![](style_files/figure-markdown_github/unnamed-chunk-12-3.png)

Rules matched / rejected
------------------------

Of the rules considered:

-   6.97% matched
-   68.85% were rejected by the bloom filter
-   24.18% were rejected by evaluation

![](style_files/figure-markdown_github/unnamed-chunk-14-1.png) ![](style_files/figure-markdown_github/unnamed-chunk-14-2.png) ![](style_files/figure-markdown_github/unnamed-chunk-14-3.png)

Styles un/changed
-----------------

Warning: This section isn't entirely accurate yet.

Based on 12589 `Document::updateStyle` observations.

20.69% of styles produced were identical to the previous state.

![](style_files/figure-markdown_github/unnamed-chunk-16-1.png)
