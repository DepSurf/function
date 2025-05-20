# Function: <code>next_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815469fd)
Location: drivers/base/core.c:1317
Inline: True
Inline callers:
  - drivers/base/core.c:device_for_each_child
  - drivers/base/core.c:device_find_child
```
```
In drivers/base/bus.c (ffffffff81549929)
Location: drivers/base/bus.c:269
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_for_each_dev
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
```
```
In drivers/base/driver.c (ffffffff8154c6ee)
Location: drivers/base/driver.c:21
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_for_each_device
  - drivers/base/driver.c:driver_find_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8159870b)
Location: drivers/base/core.c:1317
Inline: True
Inline callers:
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child
```
```
In drivers/base/bus.c (ffffffff8159b83d)
Location: drivers/base/bus.c:268
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
```
```
In drivers/base/driver.c (ffffffff8159e599)
Location: drivers/base/driver.c:21
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815c63ab)
Location: drivers/base/core.c:1908
Inline: True
Inline callers:
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child
```
```
In drivers/base/bus.c (ffffffff815c9d9d)
Location: drivers/base/bus.c:268
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
```
```
In drivers/base/driver.c (ffffffff815ccb49)
Location: drivers/base/driver.c:21
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815db15b)
Location: drivers/base/core.c:1906
Inline: True
Inline callers:
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child
```
```
In drivers/base/bus.c (ffffffff815deadd)
Location: drivers/base/bus.c:268
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
```
```
In drivers/base/driver.c (ffffffff815e16a7)
Location: drivers/base/driver.c:21
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8164211b)
Location: drivers/base/core.c:2041
Inline: True
Inline callers:
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child
```
```
In drivers/base/bus.c (ffffffff81645b0d)
Location: drivers/base/bus.c:268
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
```
```
In drivers/base/driver.c (ffffffff816487fb)
Location: drivers/base/driver.c:21
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8167d3a9)
Location: drivers/base/core.c:2088
Inline: True
Inline callers:
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child
```
```
In drivers/base/bus.c (ffffffff81680f6d)
Location: drivers/base/bus.c:266
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
```
```
In drivers/base/driver.c (ffffffff81683db5)
Location: drivers/base/driver.c:19
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169cd39)
Location: drivers/base/core.c:2163
Inline: True
Inline callers:
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child
```
```
In drivers/base/bus.c (ffffffff816a09fd)
Location: drivers/base/bus.c:269
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
```
```
In drivers/base/driver.c (ffffffff816a3a86)
Location: drivers/base/driver.c:19
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816d5c74)
Location: drivers/base/core.c:2389
Inline: True
Inline callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child
```
```
In drivers/base/bus.c (ffffffff816d993c)
Location: drivers/base/bus.c:259
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
```
```
In drivers/base/driver.c (ffffffff816dc977)
Location: drivers/base/driver.c:19
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816f9a64)
Location: drivers/base/core.c:2426
Inline: True
Inline callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child
```
```
In drivers/base/bus.c (ffffffff816fd91c)
Location: drivers/base/bus.c:259
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
```
```
In drivers/base/driver.c (ffffffff81700a1a)
Location: drivers/base/driver.c:19
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b29a4)
Location: drivers/base/core.c:2927
Inline: True
Inline callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_reorder_to_tail
```
```
In drivers/base/bus.c (ffffffff817b7521)
Location: drivers/base/bus.c:260
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
```
```
In drivers/base/driver.c (ffffffff817ba96a)
Location: drivers/base/driver.c:20
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817c74a4)
Location: drivers/base/core.c:3339
Inline: True
Inline callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_reorder_to_tail
```
```
In drivers/base/bus.c (ffffffff817cc241)
Location: drivers/base/bus.c:260
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
```
```
In drivers/base/driver.c (ffffffff817cf5aa)
Location: drivers/base/driver.c:20
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817aa914)
Location: drivers/base/core.c:3566
Inline: True
Inline callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_reorder_to_tail
```
```
In drivers/base/bus.c (ffffffff817afbb1)
Location: drivers/base/bus.c:260
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
```
```
In drivers/base/driver.c (ffffffff817b2fba)
Location: drivers/base/driver.c:20
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81833ad4)
Location: drivers/base/core.c:3631
Inline: True
Inline callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_reorder_to_tail
```
```
In drivers/base/bus.c (ffffffff81838e71)
Location: drivers/base/bus.c:256
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
```
```
In drivers/base/driver.c (ffffffff8183c4aa)
Location: drivers/base/driver.c:20
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff819752b4)
Location: drivers/base/core.c:3665
Inline: True
Inline callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_reorder_to_tail
  - drivers/base/core.c:device_is_dependent
```
```
In drivers/base/bus.c (ffffffff8197b3e0)
Location: drivers/base/bus.c:256
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
```
```
In drivers/base/driver.c (ffffffff8197eeb9)
Location: drivers/base/driver.c:20
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae2adf)
Location: drivers/base/core.c:3864
Inline: True
Inline callers:
  - drivers/base/core.c:device_find_any_child
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_reorder_to_tail
  - drivers/base/core.c:device_is_dependent
```
```
In drivers/base/bus.c (ffffffff81ae8460)
Location: drivers/base/bus.c:256
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
```
```
In drivers/base/driver.c (ffffffff81aec5a9)
Location: drivers/base/driver.c:20
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b309ff)
Location: drivers/base/core.c:3873
Inline: True
Inline callers:
  - drivers/base/core.c:device_find_any_child
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_reorder_to_tail
  - drivers/base/core.c:device_is_dependent
```
```
In drivers/base/bus.c (ffffffff81b36dae)
Location: drivers/base/bus.c:322
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/bus.c:bus_find_device
```
```
In drivers/base/driver.c (ffffffff81b3a799)
Location: drivers/base/driver.c:20
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b87fff)
Location: drivers/base/core.c:3887
Inline: True
Inline callers:
  - drivers/base/core.c:device_find_any_child
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_reorder_to_tail
  - drivers/base/core.c:device_is_dependent
```
```
In drivers/base/bus.c (ffffffff81b8e7ce)
Location: drivers/base/bus.c:322
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/bus.c:bus_find_device
```
```
In drivers/base/driver.c (ffffffff81b92259)
Location: drivers/base/driver.c:20
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e3ee0)
Location: drivers/base/core.c:2426
Inline: True
Inline callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child
```
```
In drivers/base/bus.c (ffff8000108e85a0)
Location: drivers/base/bus.c:259
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
```
```
In drivers/base/driver.c (ffff8000108ebe38)
Location: drivers/base/driver.c:19
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d2a24)
Location: drivers/base/core.c:2426
Inline: True
Inline callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child
```
```
In drivers/base/bus.c (c09d69a4)
Location: drivers/base/bus.c:259
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
```
```
In drivers/base/driver.c (c09d9e94)
Location: drivers/base/driver.c:19
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c0000000009790f4)
Location: drivers/base/core.c:2426
Inline: True
Inline callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child
```
```
In drivers/base/bus.c (c00000000097ea00)
Location: drivers/base/bus.c:259
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
```
```
In drivers/base/driver.c (c000000000983720)
Location: drivers/base/driver.c:19
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe000578f82)
Location: drivers/base/core.c:2426
Inline: True
Inline callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child
```
```
In drivers/base/bus.c (ffffffe00057c78e)
Location: drivers/base/bus.c:259
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
```
```
In drivers/base/driver.c (ffffffe00057f4ba)
Location: drivers/base/driver.c:19
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816bf254)
Location: drivers/base/core.c:2426
Inline: True
Inline callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child
```
```
In drivers/base/bus.c (ffffffff816c310c)
Location: drivers/base/bus.c:259
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
```
```
In drivers/base/driver.c (ffffffff816c620a)
Location: drivers/base/driver.c:19
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169a504)
Location: drivers/base/core.c:2426
Inline: True
Inline callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child
```
```
In drivers/base/bus.c (ffffffff8169e3bc)
Location: drivers/base/bus.c:259
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
```
```
In drivers/base/driver.c (ffffffff816a146a)
Location: drivers/base/driver.c:19
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816ed724)
Location: drivers/base/core.c:2426
Inline: True
Inline callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child
```
```
In drivers/base/bus.c (ffffffff816f15dc)
Location: drivers/base/bus.c:259
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
```
```
In drivers/base/driver.c (ffffffff816f46da)
Location: drivers/base/driver.c:19
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81707f64)
Location: drivers/base/core.c:2426
Inline: True
Inline callers:
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_for_each_child
```
```
In drivers/base/bus.c (ffffffff8170be1c)
Location: drivers/base/bus.c:259
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:bus_for_each_dev
```
```
In drivers/base/driver.c (ffffffff8170ef6a)
Location: drivers/base/driver.c:19
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_find_device
  - drivers/base/driver.c:driver_for_each_device
```
</details>
</li>
</ul>

## Differences
