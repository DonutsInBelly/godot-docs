:github_url: hide

.. Generated automatically by doc/tools/make_rst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the PhysicsDirectSpaceState3DExtension.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_PhysicsDirectSpaceState3DExtension:

PhysicsDirectSpaceState3DExtension
==================================

**Inherits:** :ref:`PhysicsDirectSpaceState3D<class_PhysicsDirectSpaceState3D>` **<** :ref:`Object<class_Object>`



Methods
-------

+-------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`       | :ref:`_cast_motion<class_PhysicsDirectSpaceState3DExtension_method__cast_motion>` **(** :ref:`RID<class_RID>` shape_rid, :ref:`Transform3D<class_Transform3D>` transform, :ref:`Vector3<class_Vector3>` motion, :ref:`float<class_float>` margin, :ref:`int<class_int>` collision_mask, :ref:`bool<class_bool>` collide_with_bodies, :ref:`bool<class_bool>` collide_with_areas, float* closest_safe, float* closest_unsafe, PhysicsServer3DExtensionShapeRestInfo* info **)** |virtual|      |
+-------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`       | :ref:`_collide_shape<class_PhysicsDirectSpaceState3DExtension_method__collide_shape>` **(** :ref:`RID<class_RID>` shape_rid, :ref:`Transform3D<class_Transform3D>` transform, :ref:`Vector3<class_Vector3>` motion, :ref:`float<class_float>` margin, :ref:`int<class_int>` collision_mask, :ref:`bool<class_bool>` collide_with_bodies, :ref:`bool<class_bool>` collide_with_areas, void* results, :ref:`int<class_int>` max_results, int32_t* result_count **)** |virtual|                  |
+-------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>` | :ref:`_get_closest_point_to_object_volume<class_PhysicsDirectSpaceState3DExtension_method__get_closest_point_to_object_volume>` **(** :ref:`RID<class_RID>` object, :ref:`Vector3<class_Vector3>` point **)** |virtual| |const|                                                                                                                                                                                                                                                               |
+-------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`         | :ref:`_intersect_point<class_PhysicsDirectSpaceState3DExtension_method__intersect_point>` **(** :ref:`Vector3<class_Vector3>` position, :ref:`int<class_int>` collision_mask, :ref:`bool<class_bool>` collide_with_bodies, :ref:`bool<class_bool>` collide_with_areas, PhysicsServer3DExtensionShapeResult* results, :ref:`int<class_int>` max_results **)** |virtual|                                                                                                                        |
+-------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`       | :ref:`_intersect_ray<class_PhysicsDirectSpaceState3DExtension_method__intersect_ray>` **(** :ref:`Vector3<class_Vector3>` from, :ref:`Vector3<class_Vector3>` to, :ref:`int<class_int>` collision_mask, :ref:`bool<class_bool>` collide_with_bodies, :ref:`bool<class_bool>` collide_with_areas, :ref:`bool<class_bool>` hit_from_inside, :ref:`bool<class_bool>` hit_back_faces, PhysicsServer3DExtensionRayResult* result **)** |virtual|                                                   |
+-------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`         | :ref:`_intersect_shape<class_PhysicsDirectSpaceState3DExtension_method__intersect_shape>` **(** :ref:`RID<class_RID>` shape_rid, :ref:`Transform3D<class_Transform3D>` transform, :ref:`Vector3<class_Vector3>` motion, :ref:`float<class_float>` margin, :ref:`int<class_int>` collision_mask, :ref:`bool<class_bool>` collide_with_bodies, :ref:`bool<class_bool>` collide_with_areas, PhysicsServer3DExtensionShapeResult* result_count, :ref:`int<class_int>` max_results **)** |virtual| |
+-------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`       | :ref:`_rest_info<class_PhysicsDirectSpaceState3DExtension_method__rest_info>` **(** :ref:`RID<class_RID>` shape_rid, :ref:`Transform3D<class_Transform3D>` transform, :ref:`Vector3<class_Vector3>` motion, :ref:`float<class_float>` margin, :ref:`int<class_int>` collision_mask, :ref:`bool<class_bool>` collide_with_bodies, :ref:`bool<class_bool>` collide_with_areas, PhysicsServer3DExtensionShapeRestInfo* rest_info **)** |virtual|                                                 |
+-------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Method Descriptions
-------------------

.. _class_PhysicsDirectSpaceState3DExtension_method__cast_motion:

- :ref:`bool<class_bool>` **_cast_motion** **(** :ref:`RID<class_RID>` shape_rid, :ref:`Transform3D<class_Transform3D>` transform, :ref:`Vector3<class_Vector3>` motion, :ref:`float<class_float>` margin, :ref:`int<class_int>` collision_mask, :ref:`bool<class_bool>` collide_with_bodies, :ref:`bool<class_bool>` collide_with_areas, float* closest_safe, float* closest_unsafe, PhysicsServer3DExtensionShapeRestInfo* info **)** |virtual|

----

.. _class_PhysicsDirectSpaceState3DExtension_method__collide_shape:

- :ref:`bool<class_bool>` **_collide_shape** **(** :ref:`RID<class_RID>` shape_rid, :ref:`Transform3D<class_Transform3D>` transform, :ref:`Vector3<class_Vector3>` motion, :ref:`float<class_float>` margin, :ref:`int<class_int>` collision_mask, :ref:`bool<class_bool>` collide_with_bodies, :ref:`bool<class_bool>` collide_with_areas, void* results, :ref:`int<class_int>` max_results, int32_t* result_count **)** |virtual|

----

.. _class_PhysicsDirectSpaceState3DExtension_method__get_closest_point_to_object_volume:

- :ref:`Vector3<class_Vector3>` **_get_closest_point_to_object_volume** **(** :ref:`RID<class_RID>` object, :ref:`Vector3<class_Vector3>` point **)** |virtual| |const|

----

.. _class_PhysicsDirectSpaceState3DExtension_method__intersect_point:

- :ref:`int<class_int>` **_intersect_point** **(** :ref:`Vector3<class_Vector3>` position, :ref:`int<class_int>` collision_mask, :ref:`bool<class_bool>` collide_with_bodies, :ref:`bool<class_bool>` collide_with_areas, PhysicsServer3DExtensionShapeResult* results, :ref:`int<class_int>` max_results **)** |virtual|

----

.. _class_PhysicsDirectSpaceState3DExtension_method__intersect_ray:

- :ref:`bool<class_bool>` **_intersect_ray** **(** :ref:`Vector3<class_Vector3>` from, :ref:`Vector3<class_Vector3>` to, :ref:`int<class_int>` collision_mask, :ref:`bool<class_bool>` collide_with_bodies, :ref:`bool<class_bool>` collide_with_areas, :ref:`bool<class_bool>` hit_from_inside, :ref:`bool<class_bool>` hit_back_faces, PhysicsServer3DExtensionRayResult* result **)** |virtual|

----

.. _class_PhysicsDirectSpaceState3DExtension_method__intersect_shape:

- :ref:`int<class_int>` **_intersect_shape** **(** :ref:`RID<class_RID>` shape_rid, :ref:`Transform3D<class_Transform3D>` transform, :ref:`Vector3<class_Vector3>` motion, :ref:`float<class_float>` margin, :ref:`int<class_int>` collision_mask, :ref:`bool<class_bool>` collide_with_bodies, :ref:`bool<class_bool>` collide_with_areas, PhysicsServer3DExtensionShapeResult* result_count, :ref:`int<class_int>` max_results **)** |virtual|

----

.. _class_PhysicsDirectSpaceState3DExtension_method__rest_info:

- :ref:`bool<class_bool>` **_rest_info** **(** :ref:`RID<class_RID>` shape_rid, :ref:`Transform3D<class_Transform3D>` transform, :ref:`Vector3<class_Vector3>` motion, :ref:`float<class_float>` margin, :ref:`int<class_int>` collision_mask, :ref:`bool<class_bool>` collide_with_bodies, :ref:`bool<class_bool>` collide_with_areas, PhysicsServer3DExtensionShapeRestInfo* rest_info **)** |virtual|

.. |virtual| replace:: :abbr:`virtual (This method should typically be overridden by the user to have any effect.)`
.. |const| replace:: :abbr:`const (This method has no side effects. It doesn't modify any of the instance's member variables.)`
.. |vararg| replace:: :abbr:`vararg (This method accepts any number of arguments after the ones described here.)`
.. |constructor| replace:: :abbr:`constructor (This method is used to construct a type.)`
.. |static| replace:: :abbr:`static (This method doesn't need an instance to be called, so it can be called directly using the class name.)`
.. |operator| replace:: :abbr:`operator (This method describes a valid operator to use with this type as left-hand operand.)`