# Function: <code>kset_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff813eb844)
Location: include/linux/kobject.h:192
Inline: True
Inline callers:
  - lib/kobject.c:kobj_kset_leave
```
```
In drivers/base/bus.c (ffffffff815497e7)
Location: include/linux/kobject.h:192
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_create_file
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_driver
```
```
In drivers/base/class.c (ffffffff8154cf2b)
Location: include/linux/kobject.h:192
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81431c34)
Location: include/linux/kobject.h:192
Inline: True
Inline callers:
  - lib/kobject.c:kobj_kset_leave
```
```
In drivers/base/bus.c (ffffffff8159bb33)
Location: include/linux/kobject.h:192
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/class.c (ffffffff8159ed1b)
Location: include/linux/kobject.h:192
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8144dea4)
Location: include/linux/kobject.h:192
Inline: True
Inline callers:
  - lib/kobject.c:kobj_kset_leave
```
```
In drivers/base/bus.c (ffffffff815ca093)
Location: include/linux/kobject.h:192
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/class.c (ffffffff815cd2db)
Location: include/linux/kobject.h:192
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
  - drivers/base/class.c:__class_register
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff815deddf)
Location: include/linux/kobject.h:194
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/class.c (ffffffff815e1dd7)
Location: include/linux/kobject.h:194
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
```
```
In lib/kobject.c (ffffffff818ee2c4)
Location: include/linux/kobject.h:194
Inline: True
Inline callers:
  - lib/kobject.c:kobj_kset_leave
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81645e15)
Location: include/linux/kobject.h:196
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/class.c (ffffffff81648f4d)
Location: include/linux/kobject.h:196
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
```
```
In lib/kobject.c (ffffffff81974374)
Location: include/linux/kobject.h:196
Inline: True
Inline callers:
  - lib/kobject.c:kobj_kset_leave
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81681259)
Location: include/linux/kobject.h:199
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/class.c (ffffffff81684511)
Location: include/linux/kobject.h:199
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
```
```
In lib/kobject.c (ffffffff819d0894)
Location: include/linux/kobject.h:199
Inline: True
Inline callers:
  - lib/kobject.c:kobj_kset_leave
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816a0ce9)
Location: include/linux/kobject.h:216
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/class.c (ffffffff816a41d1)
Location: include/linux/kobject.h:216
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
```
```
In lib/kobject.c (ffffffff81a09eb4)
Location: include/linux/kobject.h:216
Inline: True
Inline callers:
  - lib/kobject.c:kobj_kset_leave
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816d9c29)
Location: include/linux/kobject.h:217
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/class.c (ffffffff816dd101)
Location: include/linux/kobject.h:217
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
```
```
In lib/kobject.c (ffffffff81a79704)
Location: include/linux/kobject.h:217
Inline: True
Inline callers:
  - lib/kobject.c:kobj_kset_leave
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816fdbd9)
Location: include/linux/kobject.h:217
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/class.c (ffffffff817011b1)
Location: include/linux/kobject.h:217
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
```
```
In lib/kobject.c (ffffffff81ab0a64)
Location: include/linux/kobject.h:217
Inline: True
Inline callers:
  - lib/kobject.c:kobj_kset_leave
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff815eace4)
Location: include/linux/kobject.h:217
Inline: True
Inline callers:
  - lib/kobject.c:__kobject_del
  - lib/kobject.c:kobject_add_internal
```
```
In drivers/base/bus.c (ffffffff817b764a)
Location: include/linux/kobject.h:217
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/base/class.c (ffffffff817bb6a2)
Location: include/linux/kobject.h:217
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8160f5fb)
Location: include/linux/kobject.h:216
Inline: True
Inline callers:
  - lib/kobject.c:__kobject_del
  - lib/kobject.c:kobject_add_internal
```
```
In drivers/base/bus.c (ffffffff817cc36a)
Location: include/linux/kobject.h:216
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/base/class.c (ffffffff817d0292)
Location: include/linux/kobject.h:216
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff815f2d3b)
Location: include/linux/kobject.h:216
Inline: True
Inline callers:
  - lib/kobject.c:__kobject_del
  - lib/kobject.c:kobject_add_internal
```
```
In drivers/base/bus.c (ffffffff817afcde)
Location: include/linux/kobject.h:216
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/base/class.c (ffffffff817b3cb6)
Location: include/linux/kobject.h:216
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8165ff1b)
Location: include/linux/kobject.h:216
Inline: True
Inline callers:
  - lib/kobject.c:__kobject_del
  - lib/kobject.c:kobject_add_internal
```
```
In drivers/base/bus.c (ffffffff81838f9e)
Location: include/linux/kobject.h:216
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/base/class.c (ffffffff8183d196)
Location: include/linux/kobject.h:216
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff817799f9)
Location: include/linux/kobject.h:196
Inline: True
Inline callers:
  - lib/kobject.c:__kobject_del
  - lib/kobject.c:kobject_add_internal
```
```
In drivers/base/bus.c (ffffffff8197b598)
Location: include/linux/kobject.h:196
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/base/class.c (ffffffff8197fda0)
Location: include/linux/kobject.h:196
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81ae8638)
Location: include/linux/kobject.h:196
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/base/class.c (ffffffff81aed6d0)
Location: include/linux/kobject.h:196
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
```
```
In lib/kobject.c (ffffffff820229c9)
Location: include/linux/kobject.h:196
Inline: True
Inline callers:
  - lib/kobject.c:__kobject_del
  - lib/kobject.c:kobject_add_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b2f067)
Location: include/linux/kobject.h:189
Inline: True
Inline callers:
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:get_device_parent
```
```
In drivers/base/bus.c (ffffffff81b366bc)
Location: include/linux/kobject.h:189
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_get_dev_root
  - drivers/base/bus.c:bus_is_registered
  - drivers/base/bus.c:driver_find
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_sort_breadthfirst
  - drivers/base/bus.c:bus_get_kset
  - drivers/base/bus.c:bus_notify
  - drivers/base/bus.c:bus_unregister_notifier
  - drivers/base/bus.c:bus_register_notifier
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_uevent_store
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_probe_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:drivers_autoprobe_store
  - drivers/base/bus.c:drivers_autoprobe_show
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/base/class.c (ffffffff81b3b475)
Location: include/linux/kobject.h:189
Inline: True
Inline callers:
  - drivers/base/class.c:class_is_registered
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
  - drivers/base/class.c:class_for_each_device
  - drivers/base/class.c:class_unregister
  - drivers/base/class.c:class_remove_file_ns
  - drivers/base/class.c:class_create_file_ns
```
```
In lib/kobject.c (ffffffff820a2a39)
Location: include/linux/kobject.h:189
Inline: True
Inline callers:
  - lib/kobject.c:__kobject_del
  - lib/kobject.c:kobject_add_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b86867)
Location: include/linux/kobject.h:191
Inline: True
Inline callers:
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:get_device_parent
```
```
In drivers/base/bus.c (ffffffff81b8e0dc)
Location: include/linux/kobject.h:191
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_get_dev_root
  - drivers/base/bus.c:bus_is_registered
  - drivers/base/bus.c:driver_find
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_sort_breadthfirst
  - drivers/base/bus.c:bus_get_kset
  - drivers/base/bus.c:bus_notify
  - drivers/base/bus.c:bus_unregister_notifier
  - drivers/base/bus.c:bus_register_notifier
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_uevent_store
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_probe_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:drivers_autoprobe_store
  - drivers/base/bus.c:drivers_autoprobe_show
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/base/class.c (ffffffff81b92fc5)
Location: include/linux/kobject.h:191
Inline: True
Inline callers:
  - drivers/base/class.c:class_is_registered
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
  - drivers/base/class.c:class_for_each_device
  - drivers/base/class.c:class_unregister
  - drivers/base/class.c:class_remove_file_ns
  - drivers/base/class.c:class_create_file_ns
```
```
In lib/kobject.c (ffffffff8217aab9)
Location: include/linux/kobject.h:191
Inline: True
Inline callers:
  - lib/kobject.c:__kobject_del
  - lib/kobject.c:kobject_add_internal
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffff8000108e8844)
Location: include/linux/kobject.h:217
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/class.c (ffff8000108ec9e4)
Location: include/linux/kobject.h:217
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
```
```
In lib/kobject.c (ffff800010d8aab0)
Location: include/linux/kobject.h:217
Inline: True
Inline callers:
  - lib/kobject.c:kobj_kset_leave
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (c09d6c68)
Location: include/linux/kobject.h:217
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/class.c (c09da88c)
Location: include/linux/kobject.h:217
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
```
```
In lib/kobject.c (c0e85284)
Location: include/linux/kobject.h:217
Inline: True
Inline callers:
  - lib/kobject.c:kobj_kset_leave
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (c00000000097f000)
Location: include/linux/kobject.h:217
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/class.c (c000000000984400)
Location: include/linux/kobject.h:217
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
```
```
In lib/kobject.c (c000000000ecbbac)
Location: include/linux/kobject.h:217
Inline: True
Inline callers:
  - lib/kobject.c:kobj_kset_leave
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffe00057cafe)
Location: include/linux/kobject.h:217
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/class.c (ffffffe00057fca2)
Location: include/linux/kobject.h:217
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
```
```
In lib/kobject.c (ffffffe0008b402a)
Location: include/linux/kobject.h:217
Inline: True
Inline callers:
  - lib/kobject.c:kobj_kset_leave
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816c33c9)
Location: include/linux/kobject.h:217
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/class.c (ffffffff816c69a1)
Location: include/linux/kobject.h:217
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
```
```
In lib/kobject.c (ffffffff81a4f8b4)
Location: include/linux/kobject.h:217
Inline: True
Inline callers:
  - lib/kobject.c:kobj_kset_leave
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8169e679)
Location: include/linux/kobject.h:217
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/class.c (ffffffff816a1c01)
Location: include/linux/kobject.h:217
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
```
```
In lib/kobject.c (ffffffff81a0c9b4)
Location: include/linux/kobject.h:217
Inline: True
Inline callers:
  - lib/kobject.c:kobj_kset_leave
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816f1899)
Location: include/linux/kobject.h:217
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/class.c (ffffffff816f4e71)
Location: include/linux/kobject.h:217
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
```
```
In lib/kobject.c (ffffffff81abbca4)
Location: include/linux/kobject.h:217
Inline: True
Inline callers:
  - lib/kobject.c:kobj_kset_leave
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8170c0d9)
Location: include/linux/kobject.h:217
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/class.c (ffffffff8170f701)
Location: include/linux/kobject.h:217
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
```
```
In lib/kobject.c (ffffffff81ac8132)
Location: include/linux/kobject.h:217
Inline: True
Inline callers:
  - lib/kobject.c:kobj_kset_leave
```
</details>
</li>
</ul>

## Differences
