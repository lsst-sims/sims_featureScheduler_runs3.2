Starting with https://github.com/lsst-sims/sims_featureScheduler_runs3.1/blob/main/ender/ender_a1.py

Previous changes from v3.0:
* using a u and g first year coverage weighting of 50 each
* executing long_gaps every 3 days (rather than 6)
* run the twilight neo with a 45 degree solar elongation limit, go from airmass limit 2.0 to 2.5
* update start date to May 1 2025

* Minor update to the footprint to include small Euclid swath
* Updated to newer cloud database
* Telescope now parks with r-filter in. Should be no filter change time added when coming out of park.
* Updated long gaps survey to only attempt log gaps if early pair was sucessful. Also only attempt one starting blob in a night.
* Changing the pair_x surveys to not have az limits.
* Fixed bug in projection for solving blob path. Might be a slight slewtime improvement from it.
* Fix bug that was letting DDFs execute in twilight time


Further updates

* changing to u swap with y
* updating the near sun survey to alternate through filters more uniformly
