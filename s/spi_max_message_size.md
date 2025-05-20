# Function: <code>spi_max_message_size</code>

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
In drivers/spi/spi-mem.c (ffffffff81757228)
Location: include/linux/spi/spi.h:942
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
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
In drivers/spi/spi-mem.c (ffffffff8179389b)
Location: include/linux/spi/spi.h:994
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
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
In drivers/spi/spi-mem.c (ffffffff817b73eb)
Location: include/linux/spi/spi.h:997
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
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
In drivers/spi/spi-mem.c (ffffffff8187db3b)
Location: include/linux/spi/spi.h:1108
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
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
In drivers/spi/spi-mem.c (ffffffff8188c0a3)
Location: include/linux/spi/spi.h:1133
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
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
In drivers/spi/spi-mem.c (ffffffff8186ea03)
Location: include/linux/spi/spi.h:1123
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
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
In drivers/spi/spi-mem.c (ffffffff818feb13)
Location: include/linux/spi/spi.h:1122
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
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
In drivers/base/regmap/regmap-spi.c (ffffffff819b0a78)
Location: include/linux/spi/spi.h:1111
Inline: True
```
```
In drivers/spi/spi-mem.c (ffffffff81a511f9)
Location: include/linux/spi/spi.h:1111
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
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
In drivers/base/regmap/regmap-spi.c (ffffffff81b247dd)
Location: include/linux/spi/spi.h:1191
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_get_spi_bus
  - drivers/base/regmap/regmap-spi.c:regmap_get_spi_bus
```
```
In drivers/spi/spi.c (ffffffff81bd68fe)
Location: include/linux/spi/spi.h:1191
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_transfer_message
```
```
In drivers/spi/spi-mem.c (ffffffff81bda409)
Location: include/linux/spi/spi.h:1191
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
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
In drivers/base/regmap/regmap-spi.c (ffffffff81b748ed)
Location: include/linux/spi/spi.h:1221
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_get_spi_bus
  - drivers/base/regmap/regmap-spi.c:regmap_get_spi_bus
```
```
In drivers/spi/spi.c (ffffffff81c2d32e)
Location: include/linux/spi/spi.h:1221
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_transfer_message
```
```
In drivers/spi/spi-mem.c (ffffffff81c30ea9)
Location: include/linux/spi/spi.h:1221
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
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
In drivers/base/regmap/regmap-spi.c (ffffffff81bc873d)
Location: include/linux/spi/spi.h:1266
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_get_spi_bus
  - drivers/base/regmap/regmap-spi.c:regmap_get_spi_bus
```
```
In drivers/spi/spi.c (ffffffff81cdfd2e)
Location: include/linux/spi/spi.h:1266
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_transfer_message
```
```
In drivers/spi/spi-mem.c (ffffffff81ce3d39)
Location: include/linux/spi/spi.h:1266
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
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
In drivers/spi/spi-mem.c (ffff8000109cb14c)
Location: include/linux/spi/spi.h:997
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
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
In drivers/spi/spi-mem.c (c0ab449c)
Location: include/linux/spi/spi.h:997
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
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
In drivers/spi/spi-mem.c (c000000000a8cb50)
Location: include/linux/spi/spi.h:997
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
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
In drivers/spi/spi-mem.c (ffffffe00061a9a2)
Location: include/linux/spi/spi.h:997
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
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
In drivers/spi/spi-mem.c (ffffffff8177becb)
Location: include/linux/spi/spi.h:997
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
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
In drivers/spi/spi-mem.c (ffffffff8175bc7b)
Location: include/linux/spi/spi.h:997
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
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
In drivers/spi/spi-mem.c (ffffffff817ac26b)
Location: include/linux/spi/spi.h:997
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
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
In drivers/spi/spi-mem.c (ffffffff817c61fb)
Location: include/linux/spi/spi.h:997
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
  - drivers/spi/spi-mem.c:spi_mem_adjust_op_size
```
</details>
</li>
</ul>

## Differences
