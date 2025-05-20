# Function: <code>device_set_pm_not_required</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (ffffffff816df0d7)
Location: include/linux/device.h:1196
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
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
In drivers/base/cpu.c (ffffffff81703327)
Location: include/linux/device.h:1438
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
```
```
In drivers/base/power/wakeup_stats.c (ffffffff81714042)
Location: include/linux/device.h:1438
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
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
In drivers/base/cpu.c (ffffffff817bd4c7)
Location: include/linux/device.h:745
Inline: True
Inline callers:
  - drivers/base/cpu.c:__cpu_device_create
```
```
In drivers/base/power/wakeup_stats.c (ffffffff817cfb22)
Location: include/linux/device.h:745
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
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
In drivers/base/core.c (ffffffff817c9b25)
Location: include/linux/device.h:713
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/cpu.c (ffffffff817d2237)
Location: include/linux/device.h:713
Inline: True
Inline callers:
  - drivers/base/cpu.c:__cpu_device_create
```
```
In drivers/base/power/wakeup_stats.c (ffffffff817e40e2)
Location: include/linux/device.h:713
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
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
In drivers/base/core.c (ffffffff817ad31e)
Location: include/linux/device.h:719
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/cpu.c (ffffffff817b5c97)
Location: include/linux/device.h:719
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
```
```
In drivers/base/power/wakeup_stats.c (ffffffff817c8522)
Location: include/linux/device.h:719
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
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
In drivers/base/core.c (ffffffff81836608)
Location: include/linux/device.h:736
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/cpu.c (ffffffff8183f197)
Location: include/linux/device.h:736
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
```
```
In drivers/base/power/wakeup_stats.c (ffffffff81852a22)
Location: include/linux/device.h:736
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
```
```
In drivers/nvdimm/bus.c (ffffffff8188cd63)
Location: include/linux/device.h:736
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
  - drivers/nvdimm/bus.c:nvdimm_bus_register
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
In drivers/base/core.c (ffffffff81978608)
Location: include/linux/device.h:811
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/cpu.c (ffffffff819823be)
Location: include/linux/device.h:811
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
```
```
In drivers/base/power/wakeup_stats.c (ffffffff8199897a)
Location: include/linux/device.h:811
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
```
```
In drivers/nvdimm/bus.c (ffffffff819d6273)
Location: include/linux/device.h:811
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
  - drivers/nvdimm/bus.c:nvdimm_bus_register
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
In drivers/base/core.c (ffffffff81ae4ec2)
Location: include/linux/device.h:808
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/cpu.c (ffffffff81af01fe)
Location: include/linux/device.h:808
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
```
```
In drivers/base/power/wakeup_stats.c (ffffffff81b09afa)
Location: include/linux/device.h:808
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
```
```
In drivers/nvdimm/bus.c (ffffffff81b50ed3)
Location: include/linux/device.h:808
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
  - drivers/nvdimm/bus.c:nvdimm_bus_register
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
In drivers/base/core.c (ffffffff81b33264)
Location: include/linux/device.h:934
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/cpu.c (ffffffff81b3e35e)
Location: include/linux/device.h:934
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
```
```
In drivers/base/power/wakeup_stats.c (ffffffff81b57b0a)
Location: include/linux/device.h:934
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
```
```
In drivers/nvdimm/bus.c (ffffffff81ba4373)
Location: include/linux/device.h:934
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
  - drivers/nvdimm/bus.c:nvdimm_bus_register
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
In drivers/base/core.c (ffffffff81b8aba3)
Location: include/linux/device.h:966
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/cpu.c (ffffffff81b95fed)
Location: include/linux/device.h:966
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
```
```
In drivers/base/power/wakeup_stats.c (ffffffff81bb0129)
Location: include/linux/device.h:966
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
```
```
In drivers/nvdimm/bus.c (ffffffff81bf8593)
Location: include/linux/device.h:966
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
  - drivers/nvdimm/bus.c:nvdimm_bus_register
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
In drivers/base/cpu.c (ffff8000108eeb1c)
Location: include/linux/device.h:1438
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
```
```
In drivers/base/power/wakeup_stats.c (ffff800010905a64)
Location: include/linux/device.h:1438
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
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
In drivers/base/cpu.c (c09dc52c)
Location: include/linux/device.h:1438
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
```
```
In drivers/base/power/wakeup_stats.c (c09ef260)
Location: include/linux/device.h:1438
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
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
In drivers/base/cpu.c (c000000000987ea8)
Location: include/linux/device.h:1438
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
```
```
In drivers/base/power/wakeup_stats.c (c0000000009a4448)
Location: include/linux/device.h:1438
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (ffffffe00058196e)
Location: include/linux/device.h:1438
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
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
In drivers/base/cpu.c (ffffffff816c8a77)
Location: include/linux/device.h:1438
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
```
```
In drivers/base/power/wakeup_stats.c (ffffffff816da372)
Location: include/linux/device.h:1438
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
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
In drivers/base/cpu.c (ffffffff816a3da7)
Location: include/linux/device.h:1438
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
```
```
In drivers/base/power/wakeup_stats.c (ffffffff816b49f2)
Location: include/linux/device.h:1438
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
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
In drivers/base/cpu.c (ffffffff816f6fe7)
Location: include/linux/device.h:1438
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
```
```
In drivers/base/power/wakeup_stats.c (ffffffff81707d02)
Location: include/linux/device.h:1438
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
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
In drivers/base/cpu.c (ffffffff81711887)
Location: include/linux/device.h:1438
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
```
```
In drivers/base/power/wakeup_stats.c (ffffffff81722732)
Location: include/linux/device.h:1438
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
```
</details>
</li>
</ul>

## Differences
