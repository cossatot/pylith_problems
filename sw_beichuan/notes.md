## Stresses
### General
- Do topo stresses need to be explicitly balanced beforehand with BC stresses?
- Balanced 'tectonic' stresses could indicate that over the EQ cycle, these stresses are balanced by variable stress drop
- No necessary balance would mean... not that.

### How to apply tectonic stresses
- make 1d (line), top to bottom of model, w/ 0 at 0 and whatever at bottom
- Have x_neg = x_pos, y_neg=y_pos
- z = free [?]



### modeling steps
- Make mesh
- Apply BCs to domain sides -- what type?
- add topographic and tectonic stresses
- rotate stresses into model coords
    - vertical axis, should be cake
- Make topo stress spatialdb, interpolate onto fault
- do quasi-static/dynamic rupture modeling
- win
