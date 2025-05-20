# Function: <code>klist_iter_exit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff818178d0)
Location: lib/klist.c:312
Inline: False
Direct callers:
  - drivers/base/core.c:device_for_each_child
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child_reverse
  - drivers/base/bus.c:bus_for_each_dev
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/driver.c:driver_find_device
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff818178d0-ffffffff818178f7: klist_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81891380)
Location: lib/klist.c:312
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child_reverse
  - drivers/base/core.c:device_for_each_child
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff81891380-ffffffff818913a3: klist_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff818c5b10)
Location: lib/klist.c:312
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child_reverse
  - drivers/base/core.c:device_for_each_child
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff818c5b10-ffffffff818c5b33: klist_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff818ed900)
Location: lib/klist.c:312
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child_reverse
  - drivers/base/core.c:device_for_each_child
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff818ed900-ffffffff818ed928: klist_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81973d70)
Location: lib/klist.c:312
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child_reverse
  - drivers/base/core.c:device_for_each_child
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff81973d70-ffffffff81973d98: klist_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff819d0260)
Location: lib/klist.c:312
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child_reverse
  - drivers/base/core.c:device_for_each_child
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff819d0260-ffffffff819d0287: klist_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81a097c0)
Location: lib/klist.c:312
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child_reverse
  - drivers/base/core.c:device_for_each_child
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff81a097c0-ffffffff81a097e7: klist_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81a79130)
Location: lib/klist.c:311
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child_reverse
  - drivers/base/core.c:device_for_each_child
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff81a79130-ffffffff81a79153: klist_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81ab04d0)
Location: lib/klist.c:311
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child_reverse
  - drivers/base/core.c:device_for_each_child
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff81ab04d0-ffffffff81ab04f3: klist_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff815ea540)
Location: lib/klist.c:311
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child_reverse
  - drivers/base/core.c:device_reorder_to_tail
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff815ea540-ffffffff815ea566: klist_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff8160ee80)
Location: lib/klist.c:311
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child_reverse
  - drivers/base/core.c:device_reorder_to_tail
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff8160ee80-ffffffff8160eea6: klist_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff815f2610)
Location: lib/klist.c:311
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child_reverse
  - drivers/base/core.c:device_reorder_to_tail
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff815f2610-ffffffff815f2636: klist_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff8165f800)
Location: lib/klist.c:311
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child_reverse
  - drivers/base/core.c:device_reorder_to_tail
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff8165f800-ffffffff8165f826: klist_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81779000)
Location: lib/klist.c:311
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child_reverse
  - drivers/base/core.c:device_reorder_to_tail
  - drivers/base/core.c:device_is_dependent
  - drivers/base/core.c:device_is_dependent
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:do_attribute_container_device_trigger_safe
  - drivers/base/attribute_container.c:do_attribute_container_device_trigger_safe
  - drivers/base/attribute_container.c:do_attribute_container_device_trigger_safe
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff81779000-ffffffff8177902e: klist_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff82021e50)
Location: lib/klist.c:311
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_any_child
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_for_each_child_reverse
  - drivers/base/core.c:device_reorder_to_tail
  - drivers/base/core.c:device_is_dependent
  - drivers/base/core.c:device_is_dependent
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:do_attribute_container_device_trigger_safe
  - drivers/base/attribute_container.c:do_attribute_container_device_trigger_safe
  - drivers/base/attribute_container.c:do_attribute_container_device_trigger_safe
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff82021e50-ffffffff82021e7e: klist_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff820a1ea0)
Location: lib/klist.c:311
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_any_child
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_for_each_child_reverse
  - drivers/base/core.c:device_reorder_to_tail
  - drivers/base/core.c:device_is_dependent
  - drivers/base/core.c:device_is_dependent
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:bus_find_device
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:do_attribute_container_device_trigger_safe
  - drivers/base/attribute_container.c:do_attribute_container_device_trigger_safe
  - drivers/base/attribute_container.c:do_attribute_container_device_trigger_safe
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff820a1ea0-ffffffff820a1ece: klist_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff82179f20)
Location: lib/klist.c:311
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_any_child
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_for_each_child_reverse
  - drivers/base/core.c:device_reorder_to_tail
  - drivers/base/core.c:device_is_dependent
  - drivers/base/core.c:device_is_dependent
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:bus_find_device
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:do_attribute_container_device_trigger_safe
  - drivers/base/attribute_container.c:do_attribute_container_device_trigger_safe
  - drivers/base/attribute_container.c:do_attribute_container_device_trigger_safe
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff82179f20-ffffffff82179f4e: klist_iter_exit (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffff800010d8a1f0)
Location: lib/klist.c:311
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child_reverse
  - drivers/base/core.c:device_for_each_child
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffff800010d8a1f0-ffff800010d8a220: klist_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (c0e84760)
Location: lib/klist.c:311
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child_reverse
  - drivers/base/core.c:device_for_each_child
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
c0e84760-c0e84790: klist_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (c000000000ecab60)
Location: lib/klist.c:311
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child_reverse
  - drivers/base/core.c:device_for_each_child
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
c000000000ecab60-c000000000ecabac: klist_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffe0008b3996)
Location: lib/klist.c:311
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child_reverse
  - drivers/base/core.c:device_for_each_child
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffe0008b3996-ffffffe0008b39be: klist_iter_exit (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81a4f320)
Location: lib/klist.c:311
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child_reverse
  - drivers/base/core.c:device_for_each_child
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff81a4f320-ffffffff81a4f343: klist_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81a0c420)
Location: lib/klist.c:311
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child_reverse
  - drivers/base/core.c:device_for_each_child
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff81a0c420-ffffffff81a0c443: klist_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81abb710)
Location: lib/klist.c:311
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child_reverse
  - drivers/base/core.c:device_for_each_child
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff81abb710-ffffffff81abb733: klist_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81ac7b90)
Location: lib/klist.c:311
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child_reverse
  - drivers/base/core.c:device_for_each_child
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff81ac7b90-ffffffff81ac7bb3: klist_iter_exit (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
