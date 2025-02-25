:github_url: hide

.. Generated automatically by doc/tools/make_rst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the ButtonGroup.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_ButtonGroup:

ButtonGroup
===========

**Inherits:** :ref:`Resource<class_Resource>` **<** :ref:`RefCounted<class_RefCounted>` **<** :ref:`Object<class_Object>`

Group of Buttons.

Description
-----------

Group of :ref:`Button<class_Button>`. All direct and indirect children buttons become radios. Only one allows being pressed.

:ref:`BaseButton.toggle_mode<class_BaseButton_property_toggle_mode>` should be ``true``.

Properties
----------

+-------------------------+-------------------------+------------------------------+
| :ref:`bool<class_bool>` | resource_local_to_scene | ``true`` *(parent override)* |
+-------------------------+-------------------------+------------------------------+

Methods
-------

+-------------------------------------+------------------------------------------------------------------------------------+
| :ref:`Array<class_Array>`           | :ref:`get_buttons<class_ButtonGroup_method_get_buttons>` **(** **)**               |
+-------------------------------------+------------------------------------------------------------------------------------+
| :ref:`BaseButton<class_BaseButton>` | :ref:`get_pressed_button<class_ButtonGroup_method_get_pressed_button>` **(** **)** |
+-------------------------------------+------------------------------------------------------------------------------------+

Signals
-------

.. _class_ButtonGroup_signal_pressed:

- **pressed** **(** :ref:`Object<class_Object>` button **)**

Emitted when one of the buttons of the group is pressed.

Method Descriptions
-------------------

.. _class_ButtonGroup_method_get_buttons:

- :ref:`Array<class_Array>` **get_buttons** **(** **)**

Returns an :ref:`Array<class_Array>` of :ref:`Button<class_Button>`\ s who have this as their ``ButtonGroup`` (see :ref:`BaseButton.button_group<class_BaseButton_property_button_group>`).

----

.. _class_ButtonGroup_method_get_pressed_button:

- :ref:`BaseButton<class_BaseButton>` **get_pressed_button** **(** **)**

Returns the current pressed button.

.. |virtual| replace:: :abbr:`virtual (This method should typically be overridden by the user to have any effect.)`
.. |const| replace:: :abbr:`const (This method has no side effects. It doesn't modify any of the instance's member variables.)`
.. |vararg| replace:: :abbr:`vararg (This method accepts any number of arguments after the ones described here.)`
.. |constructor| replace:: :abbr:`constructor (This method is used to construct a type.)`
.. |static| replace:: :abbr:`static (This method doesn't need an instance to be called, so it can be called directly using the class name.)`
.. |operator| replace:: :abbr:`operator (This method describes a valid operator to use with this type as left-hand operand.)`
