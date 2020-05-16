# 0.8.0
## Changed:
 - Deprecated `RTree::nearest_neighbor_iter_with_distance`. The name is misleading, use `RTree::nearest_neighbor_iter_with_distance_2` instead.
## Added
 - Added `nearest_neighbor_iter_with_distance_2` #31
# 0.7.1 - 2020-01-16
## Changed:
 - `RTree::intersection_candidates_with_other_tree` can now calculate intersections of trees of different item types (see #23)
# 0.7.0 - 2019-11-25
## Added:
 - `RTree::remove_with_selection_function`
 - `RTree::pop_nearest_neighbor`
 - Added CHANGELOG.md