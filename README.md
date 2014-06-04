exact-segment-intersection
==========================
Exactly computes the intersection of a pair of line segments as a homogeneous vector of non-overlapping increasing sequences.

# Example

```javascript
var exactIntersect = require("exact-segment-intersection")

var a = [-1,0]
var b = [1,0]
var c = [0,-1]
var d = [0,1]

console.log(exactIntersect(a, b, c, d))
```

Output:

```javascript
[ [0], [0], [1] ]
```

# Install

```
npm install exact-segment-intersection
```

# API

#### `require("exact-segment-intersection")(a,b,c,d)`
Exactly computes the intersection of the line segments `[a,b]` and `[c,d]`

* `a,b` are the vertices of the first segment
* `c,d` are the vertices of the second segment

**Returns** A homogeneous 3 vector encoding the exact point of intersection

# Credits
(c) 2014 Mikola Lysenko. MIT License