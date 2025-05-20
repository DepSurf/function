# Function: <code>of_property_read_u64_array</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (0)
Location: include/linux/of.h:534
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (0)
Location: include/linux/of.h:558
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (0)
Location: include/linux/of.h:678
Inline: True
```
</details>
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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (ffff800010b6fcd8)
Location: include/linux/of.h:520
Inline: True
Inline callers:
  - drivers/of/property.c:of_fwnode_property_read_int_array
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (c0c516d0)
Location: include/linux/of.h:520
Inline: True
Inline callers:
  - drivers/of/property.c:of_fwnode_property_read_int_array
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
In arch/powerpc/platforms/powernv/opal.c (c00000000135b2fc)
Location: include/linux/of.h:520
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal.c:opal_init
```
```
In arch/powerpc/platforms/powernv/idle.c (c0000000000c8aa8)
Location: include/linux/of.h:520
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/idle.c:pnv_parse_cpuidle_dt
  - arch/powerpc/platforms/powernv/idle.c:pnv_parse_cpuidle_dt
```
```
In arch/powerpc/platforms/powernv/opal-imc.c (c0000000000e022c)
Location: include/linux/of.h:520
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-imc.c:opal_imc_counters_probe
```
```
In drivers/of/property.c (c000000000c494a4)
Location: include/linux/of.h:520
Inline: True
Inline callers:
  - drivers/of/property.c:of_fwnode_property_read_int_array
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
In drivers/of/property.c (ffffffe000724036)
Location: include/linux/of.h:520
Inline: True
Inline callers:
  - drivers/of/property.c:of_fwnode_property_read_int_array
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
