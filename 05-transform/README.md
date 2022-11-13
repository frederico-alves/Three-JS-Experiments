# TRANSFORM OBJECTS

There are 4 properties to transform objects
- position
- scale
- rotation
- quaternion (rotation)

https://threejs.org/docs/?q=persp#api/en/cameras/PerspectiveCamera

`mesh.position.x = 0.7`
`mesh.position.y = - 0.6`
`mesh.position.z = 0`

mesh.position is a Vector3 object, which has x, y, z properties

`mesh.position.set(0.7, -0.6, 1)` (?)

mesh.position.normalize() - normalize the vector
mesh.position.length() - get the length of the vector

mesh.position.lengthSq() - get the length of the vector squared
mesh.position.distanceTo() - get the distance between two vectors
mesh.position.distanceToSquared() - get the distance between two vectors squared
mesh.position.lerp() - linear interpolation between two vectors
mesh.position.equals() - check if two vectors are equal
mesh.position.clone() - clone the vector
mesh.position.copy() - copy the vector
mesh.position.add() - add two vectors
mesh.position.sub() - subtract two vectors
mesh.position.multiply() - multiply two vectors
mesh.position.divide() - divide two vectors
mesh.position.min() - get the minimum of two vectors
mesh.position.max() - get the maximum of two vectors
mesh.position.clamp() - clamp the vector
mesh.position.clampScalar() - clamp the vector between two scalars
mesh.position.floor() - round the vector down
mesh.position.ceil() - round the vector up
mesh.position.round() - round the vector
mesh.position.roundToZero() - round the vector towards zero
mesh.position.negate() - negate the vector
mesh.position.dot() - dot product of two vectors
mesh.position.cross() - cross product of two vectors
mesh.position.crossVectors() - cross product of two vectors
mesh.position.project() - project the vector onto a plane
mesh.position.projectOnPlane() - project the vector onto a plane
mesh.position.reflect() - reflect the vector off a plane
mesh.position.angleTo() - get the angle between two vectors
mesh.position.distanceToPlane() - get the distance to a plane
mesh.position.setLength() - set the length of the vector


# AXES HELPER

https://threejs.org/docs/?q=axes#api/en/helpers/AxesHelper

`const axesHelper = new THREE.AxesHelper()`
`scene.add(axesHelper)`

# SCALE

`mesh.scale.x = 0.5`

# ROTATION

`mesh.rotation.reorder('YXZ')`

`mesh.rotation.x = Math.PI * 0.25`
`mesh.rotation.y = Math.PI * 0.25`

# SCENE GRAPH

https://threejs.org/docs/?q=scene#manual/en/introduction/Scene-graph

# GROUP

https://threejs.org/docs/?q=group#api/en/objects/Group

`const group = new THREE.Group()`
`scene.add(group)`
`group.add(mesh)`
`group.add(mesh2)`
`group.add(mesh3)`
`group.position.y = 1`
`group.scale.y = 2`
`group.rotation.y = 1`



