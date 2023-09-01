u_down.py:  Turn the u template weight back down to 12, but leave the g at 50. I think this should make the u band execute unifomrly again.

ug_down.py: Turn u and g template weights back to 12

all_down.py: Turn all template weights to zero. 


baseline_stripped_1.py:  Go down to just the pair_33 and greedy
baseline_stripped_2.py: strip out the nobsperyear basis function
baseline_stripped_3.py: also strip out the StrictFilterBasisFunction basis function
I guess try cranking up the footprint weight?
