<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tfg.geometry.transformation.quaternion.inverse" />
<meta itemprop="path" content="Stable" />
</div>

# tfg.geometry.transformation.quaternion.inverse

Computes the inverse of a quaternion.

``` python
tfg.geometry.transformation.quaternion.inverse(
    quaternion,
    name=None
)
```



Defined in [`geometry/transformation/quaternion.py`](https://github.com/tensorflow/graphics/blob/master/tensorflow_graphics/geometry/transformation/quaternion.py).

<!-- Placeholder for "Used in" -->

#### Note:

In the following, A1 to An are optional batch dimensions.


#### Args:

* <b>`quaternion`</b>:  A tensor of shape `[A1, ..., An, 4]`, where the last dimension
  represents a normalized quaternion.
* <b>`name`</b>: A name for this op that defaults to "quaternion_inverse".


#### Returns:

A tensor of shape `[A1, ..., An, 4]`, where the last dimension represents
a normalized quaternion.


#### Raises:

* <b>`ValueError`</b>: If the shape of `quaternion` is not supported.