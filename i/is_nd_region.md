# Function: <code>is_nd_region</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8162df8d)
Location: drivers/nvdimm/nd-core.h:69
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:to_bus_provider
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
```
```
In drivers/nvdimm/region_devs.c (ffffffff81632051)
Location: drivers/nvdimm/nd-core.h:69
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816332c2)
Location: drivers/nvdimm/nd-core.h:69
Inline: True
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
In drivers/nvdimm/bus.c (ffffffff8169673d)
Location: drivers/nvdimm/nd-core.h:68
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:to_bus_provider
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
```
```
In drivers/nvdimm/region_devs.c (ffffffff8169a9b1)
Location: drivers/nvdimm/nd-core.h:68
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8169bc32)
Location: drivers/nvdimm/nd-core.h:68
Inline: True
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
In drivers/nvdimm/bus.c (ffffffff816d26b5)
Location: drivers/nvdimm/nd-core.h:68
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
```
```
In drivers/nvdimm/region_devs.c (ffffffff816d6d81)
Location: drivers/nvdimm/nd-core.h:68
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816d8055)
Location: drivers/nvdimm/nd-core.h:68
Inline: True
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
In drivers/nvdimm/bus.c (ffffffff816f39ed)
Location: drivers/nvdimm/nd-core.h:124
Inline: True
```
```
In drivers/nvdimm/region_devs.c (ffffffff816f8bd1)
Location: drivers/nvdimm/nd-core.h:124
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816fa075)
Location: drivers/nvdimm/nd-core.h:124
Inline: True
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
In drivers/nvdimm/bus.c (ffffffff8172cd56)
Location: drivers/nvdimm/nd-core.h:118
Inline: True
```
```
In drivers/nvdimm/region_devs.c (ffffffff817322cf)
Location: drivers/nvdimm/nd-core.h:118
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81733b25)
Location: drivers/nvdimm/nd-core.h:118
Inline: True
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
In drivers/nvdimm/bus.c (ffffffff817519f5)
Location: drivers/nvdimm/nd-core.h:105
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff817578b5)
Location: drivers/nvdimm/nd-core.h:105
Inline: True
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
In drivers/nvdimm/bus.c (ffffffff8180fd64)
Location: drivers/nvdimm/nd-core.h:105
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81817865)
Location: drivers/nvdimm/nd-core.h:105
Inline: True
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
In drivers/nvdimm/bus.c (ffffffff8181eca4)
Location: drivers/nvdimm/nd-core.h:106
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff818269a3)
Location: drivers/nvdimm/nd-core.h:106
Inline: True
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
In drivers/nvdimm/bus.c (ffffffff81801fc4)
Location: drivers/nvdimm/nd-core.h:106
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81809c03)
Location: drivers/nvdimm/nd-core.h:106
Inline: True
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
In drivers/nvdimm/bus.c (ffffffff8188c484)
Location: drivers/nvdimm/nd-core.h:106
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81894533)
Location: drivers/nvdimm/nd-core.h:106
Inline: True
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
In drivers/nvdimm/bus.c (ffffffff819d58f3)
Location: drivers/nvdimm/nd-core.h:88
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff819e0395)
Location: drivers/nvdimm/nd-core.h:88
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:__reserve_free_pmem
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
In drivers/nvdimm/bus.c (ffffffff81b50433)
Location: drivers/nvdimm/nd-core.h:88
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81b5bd8b)
Location: drivers/nvdimm/nd-core.h:88
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:__reserve_free_pmem
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
In drivers/nvdimm/bus.c (ffffffff81ba3903)
Location: drivers/nvdimm/nd-core.h:88
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81baf351)
Location: drivers/nvdimm/nd-core.h:88
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:__reserve_free_pmem
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
In drivers/nvdimm/bus.c (ffffffff81bf7af3)
Location: drivers/nvdimm/nd-core.h:88
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81c0377f)
Location: drivers/nvdimm/nd-core.h:88
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:__reserve_free_pmem
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
In drivers/nvdimm/bus.c (ffff800010952078)
Location: drivers/nvdimm/nd-core.h:105
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
```
```
In drivers/nvdimm/namespace_devs.c (ffff800010958fec)
Location: drivers/nvdimm/nd-core.h:105
Inline: True
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (c0000000009fee20)
Location: drivers/nvdimm/nd-core.h:105
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
```
```
In drivers/nvdimm/namespace_devs.c (c000000000a08b44)
Location: drivers/nvdimm/nd-core.h:105
Inline: True
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
In drivers/nvdimm/bus.c (ffffffe0005c1c1e)
Location: drivers/nvdimm/nd-core.h:105
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
```
```
In drivers/nvdimm/namespace_devs.c (ffffffe0005c8526)
Location: drivers/nvdimm/nd-core.h:105
Inline: True
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
In drivers/nvdimm/bus.c (ffffffff817060e5)
Location: drivers/nvdimm/nd-core.h:105
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8170bfa5)
Location: drivers/nvdimm/nd-core.h:105
Inline: True
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
In drivers/nvdimm/bus.c (ffffffff816d9b65)
Location: drivers/nvdimm/nd-core.h:105
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816dfa25)
Location: drivers/nvdimm/nd-core.h:105
Inline: True
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
In drivers/nvdimm/bus.c (ffffffff81744eb5)
Location: drivers/nvdimm/nd-core.h:105
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8174ad75)
Location: drivers/nvdimm/nd-core.h:105
Inline: True
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
In drivers/nvdimm/bus.c (ffffffff817602f5)
Location: drivers/nvdimm/nd-core.h:105
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff817661f5)
Location: drivers/nvdimm/nd-core.h:105
Inline: True
```
</details>
</li>
</ul>

## Differences
