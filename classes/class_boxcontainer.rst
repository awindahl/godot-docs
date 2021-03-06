.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the BoxContainer.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_BoxContainer:

BoxContainer
============

**Inherits:** :ref:`Container<class_container>` **<** :ref:`Control<class_control>` **<** :ref:`CanvasItem<class_canvasitem>` **<** :ref:`Node<class_node>` **<** :ref:`Object<class_object>`

**Inherited By:** :ref:`VBoxContainer<class_vboxcontainer>`, :ref:`HBoxContainer<class_hboxcontainer>`, :ref:`ColorPicker<class_colorpicker>`

**Category:** Core

Brief Description
-----------------

Base class for box containers.

Member Functions
----------------

+------------------------+------------------------------------------------------------------------------------------------------+
| void                   | :ref:`add_spacer<class_BoxContainer_add_spacer>`  **(** :ref:`bool<class_bool>` begin  **)**         |
+------------------------+------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`  | :ref:`get_alignment<class_BoxContainer_get_alignment>`  **(** **)** const                            |
+------------------------+------------------------------------------------------------------------------------------------------+
| void                   | :ref:`set_alignment<class_BoxContainer_set_alignment>`  **(** :ref:`int<class_int>` alignment  **)** |
+------------------------+------------------------------------------------------------------------------------------------------+

Member Variables
----------------

- :ref:`int<class_int>` **alignment** - The alignment of the container's children (must be one of ALIGN_BEGIN, ALIGN_CENTER, or ALIGN_END).

Numeric Constants
-----------------

- **ALIGN_BEGIN** = **0** --- Aligns children with the beginning of the container.
- **ALIGN_CENTER** = **1** --- Aligns children with the center of the container.
- **ALIGN_END** = **2** --- Aligns children with the end of the container.

Description
-----------

Arranges child controls vertically or horizontally, and rearranges the controls automatically when their minimum size changes.

Member Function Description
---------------------------

.. _class_BoxContainer_add_spacer:

- void  **add_spacer**  **(** :ref:`bool<class_bool>` begin  **)**

Adds a control to the box as a spacer. If ``true``, *begin* will insert the spacer control in front of other children.

.. _class_BoxContainer_get_alignment:

- :ref:`int<class_int>`  **get_alignment**  **(** **)** const

Return the alignment of children in the container.

.. _class_BoxContainer_set_alignment:

- void  **set_alignment**  **(** :ref:`int<class_int>` alignment  **)**

Set the alignment of children in the container(Must be one of ALIGN_BEGIN, ALIGN_CENTER or ALIGN_END).


