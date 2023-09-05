u_down.py:  Turn the u template weight back down to 12, but leave the g at 50. I think this should make the u band execute unifomrly again.

ug_down.py: Turn u and g template weights back to 12

all_down.py: Turn all template weights to zero. 


baseline_stripped_1.py:  Go down to just the pair_33 and greedy
baseline_stripped_2.py: strip out the nobsperyear basis function
baseline_stripped_3.py: also strip out the StrictFilterBasisFunction basis function
I guess try cranking up the footprint weight?--stripped 4 and 5

no_m5.py:  Like stripped_1, but remove the m5 diff basis function. 



OK, updating and running the old v2.99 code, there is a platue after 1 year that wasn't there originally. So something has probably changed in rubin_sim that is making this behavior.

Maybe something about the footprint object? The dark sky map?
