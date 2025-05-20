# Function: <code>klist_iter_init_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void klist_iter_init_node(struct klist *k, struct klist_iter *i, struct klist_node *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81817431)
Location: lib/klist.c:281
Inline: True
Inline callers:
  - lib/klist.c:klist_iter_init
Direct callers:
  - drivers/base/bus.c:bus_for_each_dev
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/driver.c:driver_find_device
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_interface_unregister
```
**Symbols:**

```
ffffffff81817450-ffffffff8181749b: klist_iter_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void klist_iter_init_node(struct klist *k, struct klist_iter *i, struct klist_node *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81890ef1)
Location: lib/klist.c:281
Inline: True
Inline callers:
  - lib/klist.c:klist_iter_init
Direct callers:
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
```
**Symbols:**

```
ffffffff81890f10-ffffffff81890f5b: klist_iter_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void klist_iter_init_node(struct klist *k, struct klist_iter *i, struct klist_node *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff818c5681)
Location: lib/klist.c:281
Inline: True
Inline callers:
  - lib/klist.c:klist_iter_init
Direct callers:
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
```
**Symbols:**

```
ffffffff818c56a0-ffffffff818c56eb: klist_iter_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void klist_iter_init_node(struct klist *k, struct klist_iter *i, struct klist_node *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff818ed781)
Location: lib/klist.c:281
Inline: True
Inline callers:
  - lib/klist.c:klist_iter_init
Direct callers:
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
```
**Symbols:**

```
ffffffff818edb80-ffffffff818edbbe: klist_iter_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void klist_iter_init_node(struct klist *k, struct klist_iter *i, struct klist_node *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81973901)
Location: lib/klist.c:281
Inline: True
Inline callers:
  - lib/klist.c:klist_iter_init
Direct callers:
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
```
**Symbols:**

```
ffffffff81973a00-ffffffff81973a69: klist_iter_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void klist_iter_init_node(struct klist *k, struct klist_iter *i, struct klist_node *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff819cfdd0)
Location: lib/klist.c:281
Inline: True
Inline callers:
  - lib/klist.c:klist_iter_init
Direct callers:
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
```
**Symbols:**

```
ffffffff819cfde0-ffffffff819cfe48: klist_iter_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void klist_iter_init_node(struct klist *k, struct klist_iter *i, struct klist_node *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81a09330)
Location: lib/klist.c:281
Inline: True
Inline callers:
  - lib/klist.c:klist_iter_init
Direct callers:
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
```
**Symbols:**

```
ffffffff81a09420-ffffffff81a09488: klist_iter_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void klist_iter_init_node(struct klist *k, struct klist_iter *i, struct klist_node *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81a78cd0)
Location: lib/klist.c:280
Inline: True
Inline callers:
  - lib/klist.c:klist_iter_init
Direct callers:
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
```
**Symbols:**

```
ffffffff81a78dc0-ffffffff81a78dfb: klist_iter_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void klist_iter_init_node(struct klist *k, struct klist_iter *i, struct klist_node *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81ab0080)
Location: lib/klist.c:280
Inline: True
Inline callers:
  - lib/klist.c:klist_iter_init
Direct callers:
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
```
**Symbols:**

```
ffffffff81ab0170-ffffffff81ab01ab: klist_iter_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void klist_iter_init_node(struct klist *k, struct klist_iter *i, struct klist_node *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff815ea060)
Location: lib/klist.c:280
Inline: True
Inline callers:
  - lib/klist.c:klist_iter_init
Direct callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_rescan_devices
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
```
**Symbols:**

```
ffffffff815ea0b0-ffffffff815ea103: klist_iter_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void klist_iter_init_node(struct klist *k, struct klist_iter *i, struct klist_node *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff8160e9a0)
Location: lib/klist.c:280
Inline: True
Inline callers:
  - lib/klist.c:klist_iter_init
Direct callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_rescan_devices
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
```
**Symbols:**

```
ffffffff8160e9f0-ffffffff8160ea43: klist_iter_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void klist_iter_init_node(struct klist *k, struct klist_iter *i, struct klist_node *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff815f2130)
Location: lib/klist.c:280
Inline: True
Inline callers:
  - lib/klist.c:klist_iter_init
Direct callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_rescan_devices
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
```
**Symbols:**

```
ffffffff815f2180-ffffffff815f21d4: klist_iter_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void klist_iter_init_node(struct klist *k, struct klist_iter *i, struct klist_node *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff8165f2e0)
Location: lib/klist.c:280
Inline: True
Inline callers:
  - lib/klist.c:klist_iter_init
Direct callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_rescan_devices
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
```
**Symbols:**

```
ffffffff8165f2f0-ffffffff8165f344: klist_iter_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void klist_iter_init_node(struct klist *k, struct klist_iter *i, struct klist_node *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81778bd0)
Location: lib/klist.c:280
Inline: True
Inline callers:
  - lib/klist.c:klist_iter_init
Direct callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_rescan_devices
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
```
**Symbols:**

```
ffffffff81778ec0-ffffffff81778f2f: klist_iter_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void klist_iter_init_node(struct klist *k, struct klist_iter *i, struct klist_node *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff820219b0)
Location: lib/klist.c:280
Inline: True
Inline callers:
  - lib/klist.c:klist_iter_init
Direct callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_rescan_devices
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
```
**Symbols:**

```
ffffffff82021ce0-ffffffff82021d4f: klist_iter_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void klist_iter_init_node(struct klist *k, struct klist_iter *i, struct klist_node *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff820a19f0)
Location: lib/klist.c:280
Inline: True
Inline callers:
  - lib/klist.c:klist_iter_init
Direct callers:
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
```
**Symbols:**

```
ffffffff820a1d30-ffffffff820a1da0: klist_iter_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void klist_iter_init_node(struct klist *k, struct klist_iter *i, struct klist_node *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff82179a70)
Location: lib/klist.c:280
Inline: True
Inline callers:
  - lib/klist.c:klist_iter_init
Direct callers:
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
```
**Symbols:**

```
ffffffff82179db0-ffffffff82179e20: klist_iter_init_node (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void klist_iter_init_node(struct klist *k, struct klist_iter *i, struct klist_node *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffff800010d89a18)
Location: lib/klist.c:280
Inline: True
Inline callers:
  - lib/klist.c:klist_iter_init
Direct callers:
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
```
**Symbols:**

```
ffff800010d89a68-ffff800010d89aa8: klist_iter_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void klist_iter_init_node(struct klist *k, struct klist_iter *i, struct klist_node *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/klist.c (c0e8457c)
Location: lib/klist.c:280
Inline: True
Inline callers:
  - lib/klist.c:klist_iter_init
Direct callers:
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
```
**Symbols:**

```
c0e84c94-c0e84cc8: klist_iter_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void klist_iter_init_node(struct klist *k, struct klist_iter *i, struct klist_node *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/klist.c (c000000000eca880)
Location: lib/klist.c:280
Inline: True
Inline callers:
  - lib/klist.c:klist_iter_init
Direct callers:
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
```
**Symbols:**

```
c000000000eca820-c000000000eca874: klist_iter_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void klist_iter_init_node(struct klist *k, struct klist_iter *i, struct klist_node *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffe0008b3396)
Location: lib/klist.c:280
Inline: True
Inline callers:
  - lib/klist.c:klist_iter_init
Direct callers:
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
```
**Symbols:**

```
ffffffe0008b335e-ffffffe0008b3396: klist_iter_init_node (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void klist_iter_init_node(struct klist *k, struct klist_iter *i, struct klist_node *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81a4eed0)
Location: lib/klist.c:280
Inline: True
Inline callers:
  - lib/klist.c:klist_iter_init
Direct callers:
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
```
**Symbols:**

```
ffffffff81a4efc0-ffffffff81a4effb: klist_iter_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void klist_iter_init_node(struct klist *k, struct klist_iter *i, struct klist_node *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81a0bfd0)
Location: lib/klist.c:280
Inline: True
Inline callers:
  - lib/klist.c:klist_iter_init
Direct callers:
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
```
**Symbols:**

```
ffffffff81a0c0c0-ffffffff81a0c0fb: klist_iter_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void klist_iter_init_node(struct klist *k, struct klist_iter *i, struct klist_node *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81abb2c0)
Location: lib/klist.c:280
Inline: True
Inline callers:
  - lib/klist.c:klist_iter_init
Direct callers:
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
```
**Symbols:**

```
ffffffff81abb3b0-ffffffff81abb3eb: klist_iter_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void klist_iter_init_node(struct klist *k, struct klist_iter *i, struct klist_node *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81ac7720)
Location: lib/klist.c:280
Inline: True
Inline callers:
  - lib/klist.c:klist_iter_init
Direct callers:
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
```
**Symbols:**

```
ffffffff81ac7820-ffffffff81ac785b: klist_iter_init_node (STB_GLOBAL)
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
