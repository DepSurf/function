# Function: <code>of_property_set_flag</code>

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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/of/dynamic.c (ffff800010b712e0)
Location: include/linux/of.h:215
Inline: True
Inline callers:
  - drivers/of/dynamic.c:__of_prop_dup
```
```
In drivers/of/overlay.c (ffff800010b77878)
Location: include/linux/of.h:215
Inline: True
Inline callers:
  - drivers/of/overlay.c:dup_and_fixup_symbol_prop
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
In drivers/of/dynamic.c (c0c539a8)
Location: include/linux/of.h:215
Inline: True
Inline callers:
  - drivers/of/dynamic.c:__of_prop_dup
```
```
In drivers/of/overlay.c (c0c59e48)
Location: include/linux/of.h:215
Inline: True
Inline callers:
  - drivers/of/overlay.c:dup_and_fixup_symbol_prop
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
In arch/powerpc/mm/drmem.c (c00000000008a2c8)
Location: include/linux/of.h:215
Inline: True
```
```
In arch/powerpc/platforms/pseries/hotplug-memory.c (c0000000000fc504)
Location: include/linux/of.h:215
Inline: True
```
```
In drivers/of/dynamic.c (c000000000c4cf30)
Location: include/linux/of.h:215
Inline: True
Inline callers:
  - drivers/of/dynamic.c:__of_prop_dup
```
```
In drivers/of/overlay.c (c000000000c56d88)
Location: include/linux/of.h:215
Inline: True
Inline callers:
  - drivers/of/overlay.c:dup_and_fixup_symbol_prop
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
In drivers/of/dynamic.c (ffffffe0007251a2)
Location: include/linux/of.h:215
Inline: True
Inline callers:
  - drivers/of/dynamic.c:__of_prop_dup
```
```
In drivers/of/overlay.c (ffffffe00072ab72)
Location: include/linux/of.h:215
Inline: True
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
