### BFC
A **block formatting context** is a part of a visual CSS rendering of a web page. It's the region in which the layout of blocks boxes occurs and in which floats interact with other elements.

Block formatting contexts are important for the positioning and clearing of floats. The rules for positioning and clearing of floats apply only to things within the same block formatting context . Floats don't affect the layout of the content inside other block formatting contexts,and clear only clears pass floats in the same block formatting context.Margin collapsing also occurs only between blocks that belong to the same block formatting context.