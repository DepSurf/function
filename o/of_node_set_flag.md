# Function: <code>of_node_set_flag</code>

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
In drivers/clk/clk.c (ffff8000114833c8)
Location: include/linux/of.h:199
Inline: True
Inline callers:
  - drivers/clk/clk.c:of_clk_init
```
```
In drivers/of/platform.c (ffff800010b6de78)
Location: include/linux/of.h:199
Inline: True
Inline callers:
  - drivers/of/platform.c:of_platform_populate
  - drivers/of/platform.c:of_platform_bus_create
```
```
In drivers/of/dynamic.c (ffff800010b709a4)
Location: include/linux/of.h:199
Inline: True
Inline callers:
  - drivers/of/dynamic.c:of_changeset_destroy
  - drivers/of/dynamic.c:__of_node_dup
  - drivers/of/dynamic.c:__of_node_dup
  - drivers/of/dynamic.c:__of_detach_node
```
```
In drivers/of/fdt.c (ffff800010b72104)
Location: include/linux/of.h:199
Inline: True
Inline callers:
  - drivers/of/fdt.c:__unflatten_device_tree
```
```
In drivers/of/irq.c (ffff8000114ac138)
Location: include/linux/of.h:199
Inline: True
Inline callers:
  - drivers/of/irq.c:of_irq_init
```
```
In drivers/of/overlay.c (ffff800010b78280)
Location: include/linux/of.h:199
Inline: True
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
In drivers/clk/clk.c (c1554244)
Location: include/linux/of.h:199
Inline: True
Inline callers:
  - drivers/clk/clk.c:of_clk_init
```
```
In drivers/of/platform.c (c0c50d4c)
Location: include/linux/of.h:199
Inline: True
Inline callers:
  - drivers/of/platform.c:of_platform_populate
  - drivers/of/platform.c:of_platform_bus_create
```
```
In drivers/of/dynamic.c (c0c52fec)
Location: include/linux/of.h:199
Inline: True
Inline callers:
  - drivers/of/dynamic.c:of_changeset_destroy
  - drivers/of/dynamic.c:__of_node_dup
  - drivers/of/dynamic.c:__of_node_dup
  - drivers/of/dynamic.c:__of_detach_node
```
```
In drivers/of/fdt.c (c0c5470c)
Location: include/linux/of.h:199
Inline: True
Inline callers:
  - drivers/of/fdt.c:__unflatten_device_tree
```
```
In drivers/of/irq.c (c15b08b4)
Location: include/linux/of.h:199
Inline: True
Inline callers:
  - drivers/of/irq.c:of_irq_init
```
```
In drivers/of/overlay.c (c0c5a354)
Location: include/linux/of.h:199
Inline: True
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
In arch/powerpc/platforms/pseries/reconfig.c (c0000000000eccbc)
Location: include/linux/of.h:199
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/reconfig.c:ofdt_write
```
```
In arch/powerpc/platforms/pseries/dlpar.c (c0000000000f3090)
Location: include/linux/of.h:199
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/dlpar.c:dlpar_parse_cc_node
```
```
In drivers/of/platform.c (c000000000c486a0)
Location: include/linux/of.h:199
Inline: True
Inline callers:
  - drivers/of/platform.c:of_platform_populate
  - drivers/of/platform.c:of_platform_bus_create
```
```
In drivers/of/dynamic.c (c000000000c4c17c)
Location: include/linux/of.h:199
Inline: True
Inline callers:
  - drivers/of/dynamic.c:of_changeset_destroy
  - drivers/of/dynamic.c:__of_node_dup
  - drivers/of/dynamic.c:__of_node_dup
  - drivers/of/dynamic.c:__of_detach_node
```
```
In drivers/of/fdt.c (c000000000c4e560)
Location: include/linux/of.h:199
Inline: True
Inline callers:
  - drivers/of/fdt.c:__unflatten_device_tree
```
```
In drivers/of/irq.c (c0000000013bc518)
Location: include/linux/of.h:199
Inline: True
Inline callers:
  - drivers/of/irq.c:of_irq_init
```
```
In drivers/of/overlay.c (c000000000c57ac0)
Location: include/linux/of.h:199
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
In drivers/clk/clk.c (ffffffe00002d2b0)
Location: include/linux/of.h:199
Inline: True
Inline callers:
  - drivers/clk/clk.c:of_clk_init
```
```
In drivers/of/platform.c (ffffffe000722852)
Location: include/linux/of.h:199
Inline: True
Inline callers:
  - drivers/of/platform.c:of_platform_populate
  - drivers/of/platform.c:of_platform_bus_create
```
```
In drivers/of/dynamic.c (ffffffe0007248d0)
Location: include/linux/of.h:199
Inline: True
Inline callers:
  - drivers/of/dynamic.c:of_changeset_destroy
  - drivers/of/dynamic.c:__of_node_dup
  - drivers/of/dynamic.c:__of_node_dup
  - drivers/of/dynamic.c:__of_detach_node
```
```
In drivers/of/fdt.c (ffffffe000725d9e)
Location: include/linux/of.h:199
Inline: True
Inline callers:
  - drivers/of/fdt.c:__unflatten_device_tree
```
```
In drivers/of/irq.c (ffffffe00003c332)
Location: include/linux/of.h:199
Inline: True
Inline callers:
  - drivers/of/irq.c:of_irq_init
```
```
In drivers/of/overlay.c (ffffffe00072ae52)
Location: include/linux/of.h:199
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
