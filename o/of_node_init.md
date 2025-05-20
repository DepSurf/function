# Function: <code>of_node_init</code>

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
In drivers/of/dynamic.c (ffff800010b713c4)
Location: include/linux/of.h:106
Inline: True
Inline callers:
  - drivers/of/dynamic.c:__of_node_dup
```
```
In drivers/of/fdt.c (ffff800010b71bd0)
Location: include/linux/of.h:106
Inline: True
Inline callers:
  - drivers/of/fdt.c:unflatten_dt_nodes
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
In drivers/of/dynamic.c (c0c53a58)
Location: include/linux/of.h:106
Inline: True
Inline callers:
  - drivers/of/dynamic.c:__of_node_dup
```
```
In drivers/of/fdt.c (c0c54164)
Location: include/linux/of.h:106
Inline: True
Inline callers:
  - drivers/of/fdt.c:unflatten_dt_nodes
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
In arch/powerpc/platforms/pseries/reconfig.c (c0000000000ecccc)
Location: include/linux/of.h:106
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/reconfig.c:ofdt_write
```
```
In arch/powerpc/platforms/pseries/dlpar.c (c0000000000f30a8)
Location: include/linux/of.h:106
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/dlpar.c:dlpar_parse_cc_node
```
```
In drivers/of/dynamic.c (c000000000c4d060)
Location: include/linux/of.h:106
Inline: True
Inline callers:
  - drivers/of/dynamic.c:__of_node_dup
```
```
In drivers/of/fdt.c (c000000000c4da5c)
Location: include/linux/of.h:106
Inline: True
Inline callers:
  - drivers/of/fdt.c:unflatten_dt_nodes
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
In drivers/of/dynamic.c (ffffffe00072524e)
Location: include/linux/of.h:106
Inline: True
Inline callers:
  - drivers/of/dynamic.c:__of_node_dup
```
```
In drivers/of/fdt.c (ffffffe000725b38)
Location: include/linux/of.h:106
Inline: True
Inline callers:
  - drivers/of/fdt.c:unflatten_dt_nodes
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
