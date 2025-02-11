:github_url: hide

.. Generated automatically by doc/tools/make_rst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the VisualShaderNodeTransformFunc.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_VisualShaderNodeTransformFunc:

VisualShaderNodeTransformFunc
=============================

**Inherits:** :ref:`VisualShaderNode<class_VisualShaderNode>` **<** :ref:`Resource<class_Resource>` **<** :ref:`RefCounted<class_RefCounted>` **<** :ref:`Object<class_Object>`

Computes a :ref:`Transform3D<class_Transform3D>` function within the visual shader graph.

Description
-----------

Computes an inverse or transpose function on the provided :ref:`Transform3D<class_Transform3D>`.

Properties
----------

+--------------------------------------------------------------+------------------------------------------------------------------------+-------+
| :ref:`Function<enum_VisualShaderNodeTransformFunc_Function>` | :ref:`function<class_VisualShaderNodeTransformFunc_property_function>` | ``0`` |
+--------------------------------------------------------------+------------------------------------------------------------------------+-------+

Enumerations
------------

.. _enum_VisualShaderNodeTransformFunc_Function:

.. _class_VisualShaderNodeTransformFunc_constant_FUNC_INVERSE:

.. _class_VisualShaderNodeTransformFunc_constant_FUNC_TRANSPOSE:

.. _class_VisualShaderNodeTransformFunc_constant_FUNC_MAX:

enum **Function**:

- **FUNC_INVERSE** = **0** --- Perform the inverse operation on the :ref:`Transform3D<class_Transform3D>` matrix.

- **FUNC_TRANSPOSE** = **1** --- Perform the transpose operation on the :ref:`Transform3D<class_Transform3D>` matrix.

- **FUNC_MAX** = **2** --- Represents the size of the :ref:`Function<enum_VisualShaderNodeTransformFunc_Function>` enum.

Property Descriptions
---------------------

.. _class_VisualShaderNodeTransformFunc_property_function:

- :ref:`Function<enum_VisualShaderNodeTransformFunc_Function>` **function**

+-----------+---------------------+
| *Default* | ``0``               |
+-----------+---------------------+
| *Setter*  | set_function(value) |
+-----------+---------------------+
| *Getter*  | get_function()      |
+-----------+---------------------+

The function to be computed. See :ref:`Function<enum_VisualShaderNodeTransformFunc_Function>` for options.

.. |virtual| replace:: :abbr:`virtual (This method should typically be overridden by the user to have any effect.)`
.. |const| replace:: :abbr:`const (This method has no side effects. It doesn't modify any of the instance's member variables.)`
.. |vararg| replace:: :abbr:`vararg (This method accepts any number of arguments after the ones described here.)`
.. |constructor| replace:: :abbr:`constructor (This method is used to construct a type.)`
.. |static| replace:: :abbr:`static (This method doesn't need an instance to be called, so it can be called directly using the class name.)`
.. |operator| replace:: :abbr:`operator (This method describes a valid operator to use with this type as left-hand operand.)`
