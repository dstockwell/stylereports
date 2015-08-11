Based on 24846 `Document::updateStyle` observations.

Style update
------------

![](style_files/figure-markdown_github/unnamed-chunk-2-1.png) ![](style_files/figure-markdown_github/unnamed-chunk-2-2.png)

Callees
-------

2.22% of thread time spent in traced children.

![](style_files/figure-markdown_github/unnamed-chunk-4-1.png)

Callers
-------

There were 332 unique trace stacks. 46.08% of stacks and 42.75% of thread time involves `V8.Execute`.

![](style_files/figure-markdown_github/unnamed-chunk-6-1.png)

Style Sharing
-------------

Style sharing rate: 18.37%

![](style_files/figure-markdown_github/unnamed-chunk-8-1.png) ![](style_files/figure-markdown_github/unnamed-chunk-8-2.png) ![](style_files/figure-markdown_github/unnamed-chunk-8-3.png)

Matched properties cache
------------------------

Non-inherited hit rate: 63.5%

Inherited hit rate: 37.64%

![](style_files/figure-markdown_github/unnamed-chunk-9-1.png) ![](style_files/figure-markdown_github/unnamed-chunk-9-2.png) ![](style_files/figure-markdown_github/unnamed-chunk-9-3.png)

Rules matched / rejected
------------------------

Of the rules considered:

-   6.9% matched
-   69.13% were rejected by the bloom filter
-   23.97% were rejected by evaluation

![](style_files/figure-markdown_github/unnamed-chunk-11-1.png) ![](style_files/figure-markdown_github/unnamed-chunk-11-2.png) ![](style_files/figure-markdown_github/unnamed-chunk-11-3.png)

Styles un/changed
-----------------

Warning: This section isn't entirely accurate yet.

Based on 9910 `Document::updateStyle` observations.

23.78% of styles produced were identical to the previous state.

![](style_files/figure-markdown_github/unnamed-chunk-13-1.png)
