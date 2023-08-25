There can be some rapid filter swaps in twilight. Let's fiddle with some parameters to see if we can get rid of those

for tight_t1 -- change StrictFilterBasisFunction to FilterChangeBasisFunction. Should eliminate a few 
tight_t2:  Like the baseline, but increase the stay filter weight from 3 to 30
tight_t3: baseline, but remove the 15 minute pairs. 
tight_t4: remove pair_15, increase stay filter weight on greedy only
tight_t5: remove pair_15, increase stay filter weight on greedy only, greedy use FilterChangeBasisFunction


Even getting rid of pair_15, still a lot of greedy/greedy swaps

by default, greedy is r,i,z,y
twilight near sun is r,i,z
