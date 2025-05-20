# Function: <code>spi_max_transfer_size</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff81757221)
Location: include/linux/spi/spi.h:952
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff81793894)
Location: include/linux/spi/spi.h:1004
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff817b73e4)
Location: include/linux/spi/spi.h:1007
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff8187db34)
Location: include/linux/spi/spi.h:1118
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff8188c09c)
Location: include/linux/spi/spi.h:1143
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff8186e9fc)
Location: include/linux/spi/spi.h:1133
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff818feb0c)
Location: include/linux/spi/spi.h:1132
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
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
In drivers/base/regmap/regmap-spi.c (ffffffff819b0a65)
Location: include/linux/spi/spi.h:1121
Inline: True
```
```
In drivers/spi/spi-mem.c (ffffffff81a511f2)
Location: include/linux/spi/spi.h:1121
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
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
In drivers/base/regmap/regmap-spi.c (ffffffff81b247c5)
Location: include/linux/spi/spi.h:1201
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_get_spi_bus
```
```
In drivers/spi/spi.c (ffffffff81bd68f7)
Location: include/linux/spi/spi.h:1201
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_transfer_message
```
```
In drivers/spi/spi-mem.c (ffffffff81bda402)
Location: include/linux/spi/spi.h:1201
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
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
In drivers/base/regmap/regmap-spi.c (ffffffff81b748d5)
Location: include/linux/spi/spi.h:1231
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_get_spi_bus
```
```
In drivers/spi/spi.c (ffffffff81c2d327)
Location: include/linux/spi/spi.h:1231
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_transfer_message
```
```
In drivers/spi/spi-mem.c (ffffffff81c30ea2)
Location: include/linux/spi/spi.h:1231
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
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
In drivers/base/regmap/regmap-spi.c (ffffffff81bc8725)
Location: include/linux/spi/spi.h:1276
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_get_spi_bus
```
```
In drivers/spi/spi.c (ffffffff81cdfd27)
Location: include/linux/spi/spi.h:1276
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_transfer_message
```
```
In drivers/spi/spi-mem.c (ffffffff81ce3d32)
Location: include/linux/spi/spi.h:1276
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
```
</details>
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
In drivers/spi/spi-mem.c (ffff8000109cb148)
Location: include/linux/spi/spi.h:1007
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
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
In drivers/spi/spi-mem.c (c0ab4498)
Location: include/linux/spi/spi.h:1007
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (c000000000a8cb4c)
Location: include/linux/spi/spi.h:1007
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
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
In drivers/spi/spi-mem.c (ffffffe00061a99e)
Location: include/linux/spi/spi.h:1007
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff8177bec4)
Location: include/linux/spi/spi.h:1007
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff8175bc74)
Location: include/linux/spi/spi.h:1007
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff817ac264)
Location: include/linux/spi/spi.h:1007
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff817c61f4)
Location: include/linux/spi/spi.h:1007
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
```
</details>
</li>
</ul>

## Differences
