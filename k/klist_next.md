# Function: <code>klist_next</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct klist_node *klist_next(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81817740)
Location: lib/klist.c:375
Inline: False
Direct callers:
  - drivers/base/core.c:device_for_each_child
  - drivers/base/core.c:device_find_child
  - drivers/base/bus.c:bus_for_each_dev
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:subsys_dev_iter_next
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/driver.c:driver_find_device
  - drivers/base/class.c:class_dev_iter_next
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff81817740-ffffffff81817836: klist_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct klist_node *klist_next(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff818911f0)
Location: lib/klist.c:375
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child
  - drivers/base/bus.c:subsys_dev_iter_next
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_dev_iter_next
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff818911f0-ffffffff818912e6: klist_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct klist_node *klist_next(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff818c5980)
Location: lib/klist.c:375
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child
  - drivers/base/bus.c:subsys_dev_iter_next
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_dev_iter_next
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff818c5980-ffffffff818c5a76: klist_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct klist_node *klist_next(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff818ed9e0)
Location: lib/klist.c:375
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child
  - drivers/base/bus.c:subsys_dev_iter_next
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_dev_iter_next
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff818ed9e0-ffffffff818eda8d: klist_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct klist_node *klist_next(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81973c10)
Location: lib/klist.c:375
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child
  - drivers/base/bus.c:subsys_dev_iter_next
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_dev_iter_next
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff81973c10-ffffffff81973cd3: klist_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct klist_node *klist_next(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff819d03a0)
Location: lib/klist.c:376
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child
  - drivers/base/bus.c:subsys_dev_iter_next
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_dev_iter_next
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff819d03a0-ffffffff819d049e: klist_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct klist_node *klist_next(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81a09900)
Location: lib/klist.c:376
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child
  - drivers/base/bus.c:subsys_dev_iter_next
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_dev_iter_next
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff81a09900-ffffffff81a099fe: klist_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct klist_node *klist_next(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81a79250)
Location: lib/klist.c:375
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child
  - drivers/base/bus.c:subsys_dev_iter_next
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_dev_iter_next
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff81a79250-ffffffff81a7933e: klist_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct klist_node *klist_next(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81ab05f0)
Location: lib/klist.c:375
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child
  - drivers/base/bus.c:subsys_dev_iter_next
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_dev_iter_next
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff81ab05f0-ffffffff81ab06de: klist_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct klist_node *klist_next(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff815ea670)
Location: lib/klist.c:375
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_reorder_to_tail
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:bus_for_each_drv
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
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff815ea670-ffffffff815ea7be: klist_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct klist_node *klist_next(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff8160efb0)
Location: lib/klist.c:375
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_reorder_to_tail
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:bus_for_each_drv
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
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff8160efb0-ffffffff8160f0fe: klist_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct klist_node *klist_next(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff815f2730)
Location: lib/klist.c:375
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_reorder_to_tail
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:bus_for_each_drv
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
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff815f2730-ffffffff815f287e: klist_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct klist_node *klist_next(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff8165f610)
Location: lib/klist.c:375
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_reorder_to_tail
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:bus_for_each_drv
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
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff8165f610-ffffffff8165f75e: klist_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct klist_node *klist_next(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81778d60)
Location: lib/klist.c:375
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_reorder_to_tail
  - drivers/base/core.c:device_is_dependent
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:bus_for_each_drv
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
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:do_attribute_container_device_trigger_safe
  - drivers/base/attribute_container.c:do_attribute_container_device_trigger_safe
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff81778d60-ffffffff81778ebe: klist_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct klist_node *klist_next(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff82021b70)
Location: lib/klist.c:375
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_any_child
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_reorder_to_tail
  - drivers/base/core.c:device_is_dependent
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:bus_for_each_drv
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
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:do_attribute_container_device_trigger_safe
  - drivers/base/attribute_container.c:do_attribute_container_device_trigger_safe
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff82021b70-ffffffff82021cce: klist_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct klist_node *klist_next(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff820a1bb0)
Location: lib/klist.c:375
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_any_child
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_reorder_to_tail
  - drivers/base/core.c:device_is_dependent
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:bus_find_device
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:do_attribute_container_device_trigger_safe
  - drivers/base/attribute_container.c:do_attribute_container_device_trigger_safe
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff820a1bb0-ffffffff820a1d19: klist_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct klist_node *klist_next(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff82179c30)
Location: lib/klist.c:375
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_any_child
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_reorder_to_tail
  - drivers/base/core.c:device_is_dependent
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:bus_find_device
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:do_attribute_container_device_trigger_safe
  - drivers/base/attribute_container.c:do_attribute_container_device_trigger_safe
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff82179c30-ffffffff82179d99: klist_next (STB_GLOBAL)
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
struct klist_node *klist_next(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffff800010d89bf0)
Location: lib/klist.c:375
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child
  - drivers/base/bus.c:subsys_dev_iter_next
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_dev_iter_next
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffff800010d89bf0-ffff800010d89d3c: klist_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct klist_node *klist_next(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (c0e849b0)
Location: lib/klist.c:375
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child
  - drivers/base/bus.c:subsys_dev_iter_next
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_dev_iter_next
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
c0e849b0-c0e84aac: klist_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct klist_node *klist_next(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (c000000000ecad50)
Location: lib/klist.c:375
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child
  - drivers/base/bus.c:subsys_dev_iter_next
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_dev_iter_next
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
c000000000ecad50-c000000000ecaef0: klist_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct klist_node *klist_next(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffe0008b3588)
Location: lib/klist.c:375
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child
  - drivers/base/bus.c:subsys_dev_iter_next
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_dev_iter_next
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffe0008b3588-ffffffe0008b365e: klist_next (STB_GLOBAL)
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
struct klist_node *klist_next(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81a4f440)
Location: lib/klist.c:375
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child
  - drivers/base/bus.c:subsys_dev_iter_next
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_dev_iter_next
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff81a4f440-ffffffff81a4f52e: klist_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct klist_node *klist_next(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81a0c540)
Location: lib/klist.c:375
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child
  - drivers/base/bus.c:subsys_dev_iter_next
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_dev_iter_next
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff81a0c540-ffffffff81a0c62e: klist_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct klist_node *klist_next(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81abb830)
Location: lib/klist.c:375
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child
  - drivers/base/bus.c:subsys_dev_iter_next
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_dev_iter_next
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff81abb830-ffffffff81abb91e: klist_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct klist_node *klist_next(struct klist_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81ac7cb0)
Location: lib/klist.c:375
Inline: False
Direct callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child
  - drivers/base/bus.c:subsys_dev_iter_next
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/class.c:class_dev_iter_next
  - drivers/base/attribute_container.c:attribute_container_find_class_device
  - drivers/base/attribute_container.c:attribute_container_device_trigger
  - drivers/base/attribute_container.c:attribute_container_remove_device
```
**Symbols:**

```
ffffffff81ac7cb0-ffffffff81ac7d9e: klist_next (STB_GLOBAL)
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
