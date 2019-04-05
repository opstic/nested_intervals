A library to deal with interval sets.

We can
- [x] build them
- [x] check for overlap with a query range -> has_overlap
- [x] query for overlapping with a query range -> query_overlapping
- [x] query for overlapping with a query set -> filter_to_overlapping_multiple
- [x] query for non-overlapping with a query set -> filter_to_non_overlapping
- [x] check for internally overlapping -> any_overlapping
- [x] remove duplicate intervals (start&stop!)-> remove_duplicates
- [x] remove duplicate intervals and complain about non-duplicate overlapping ->
  remove_duplictes & any_overlapping
- [x] merge internally overlapping by joining them -> merge_hull
- [ ] merge internally overlapping by intersecting them? what does than even mean for
  nested intervals?
- [x] merge internally overlapping by dropping them -> merge_drop
- [ ] find the closest interval to a point - //needs more definition.
- [x] find the interval with the closest start to the left of a point -> find_closest_start_left
- [x] find the interval with the closest start to the right of a point -> find_closest_start_right
- [ ] find the interval with the closest end to the left of a point //going be expensive
  O(n/2)
- [ ] find the interval with the closest end to the right of a point //going be
  expensiv O(n/2)
- [x] calculate the units covered by the intervals -> covered_units() 
- [x] find the mean size of the intervals -> mean_interval_size()
- [x] build the union of n interval sets -> union()
- [x] substract two interval sets  -> substract() (should this be named difference?)
- [x] keep only those overlapping with n other sets -> filter_to_overlapping_k_others
- [x] remove those overlapping with more than n other sets ->filter_to_non_overlapping_k_others
- [x] invert an interval set (given outer borders)
- [ ] intersect to interval sets
- [ ] split intervalsets into non-overlapping subsets
- [ ]
- [ ]
