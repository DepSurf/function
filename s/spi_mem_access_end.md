# Function: <code>spi_mem_access_end</code>

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
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff81756cf0)
Location: drivers/spi/spi-mem.c:250
Inline: True
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_write
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
**Symbols:**

```
ffffffff81756cf0-ffffffff81756d35: spi_mem_access_end.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff81793340)
Location: drivers/spi/spi-mem.c:250
Inline: True
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_write
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
**Symbols:**

```
ffffffff81793340-ffffffff81793386: spi_mem_access_end.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff817b6e90)
Location: drivers/spi/spi-mem.c:250
Inline: True
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_write
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
**Symbols:**

```
ffffffff817b6e90-ffffffff817b6ed6: spi_mem_access_end.isra.0 (STB_LOCAL)
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
In drivers/spi/spi-mem.c (ffffffff8187e418)
Location: drivers/spi/spi-mem.c:252
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_write
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
  - drivers/spi/spi-mem.c:spi_mem_exec_op
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
In drivers/spi/spi-mem.c (ffffffff8188c988)
Location: drivers/spi/spi-mem.c:259
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_write
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
  - drivers/spi/spi-mem.c:spi_mem_exec_op
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
In drivers/spi/spi-mem.c (ffffffff8186f47b)
Location: drivers/spi/spi-mem.c:275
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_write
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi-mem.c (0)
Location: drivers/spi/spi-mem.c:276
Inline: True
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/spi/spi-mem.c:spi_mem_dirmap_write
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
**Symbols:**

```
ffffffff818fe880-ffffffff818fe8db: spi_mem_access_end.isra.0 (STB_LOCAL)
ffffffff81d10107-ffffffff81d1011c: spi_mem_access_end.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi-mem.c (0)
Location: drivers/spi/spi-mem.c:289
Inline: True
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/spi/spi-mem.c:spi_mem_dirmap_write
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
**Symbols:**

```
ffffffff81a501d0-ffffffff81a5023f: spi_mem_access_end.isra.0 (STB_LOCAL)
ffffffff81edae1a-ffffffff81edae2f: spi_mem_access_end.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi-mem.c (0)
Location: drivers/spi/spi-mem.c:289
Inline: True
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/spi/spi-mem.c:spi_mem_dirmap_write
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
**Symbols:**

```
ffffffff81bd9330-ffffffff81bd939f: spi_mem_access_end.isra.0 (STB_LOCAL)
ffffffff8209d431-ffffffff8209d446: spi_mem_access_end.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi-mem.c (0)
Location: drivers/spi/spi-mem.c:289
Inline: True
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/spi/spi-mem.c:spi_mem_dirmap_write
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
**Symbols:**

```
ffffffff81c2fd30-ffffffff81c2fd9f: spi_mem_access_end.isra.0 (STB_LOCAL)
ffffffff8211e2ee-ffffffff8211e303: spi_mem_access_end.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi-mem.c (0)
Location: drivers/spi/spi-mem.c:289
Inline: True
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/spi/spi-mem.c:spi_mem_dirmap_write
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
**Symbols:**

```
ffffffff81ce2bf0-ffffffff81ce2c5f: spi_mem_access_end.isra.0 (STB_LOCAL)
ffffffff821ff87c-ffffffff821ff891: spi_mem_access_end.isra.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi-mem.c (ffff8000109caca8)
Location: drivers/spi/spi-mem.c:250
Inline: True
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_write
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
**Symbols:**

```
ffff8000109caca8-ffff8000109cad00: spi_mem_access_end.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void spi_mem_access_end(struct spi_mem *mem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (c0ab3b5c)
Location: drivers/spi/spi-mem.c:250
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_write
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
**Symbols:**

```
c0ab3b5c-c0ab3ba4: spi_mem_access_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi-mem.c (c000000000a8c550)
Location: drivers/spi/spi-mem.c:250
Inline: True
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_write
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
**Symbols:**

```
c000000000a8c550-c000000000a8c5d4: spi_mem_access_end.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffe00061a57c)
Location: drivers/spi/spi-mem.c:250
Inline: True
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_write
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
**Symbols:**

```
ffffffe00061a57c-ffffffe00061a5d4: spi_mem_access_end.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff8177b970)
Location: drivers/spi/spi-mem.c:250
Inline: True
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_write
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
**Symbols:**

```
ffffffff8177b970-ffffffff8177b9b6: spi_mem_access_end.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff8175b720)
Location: drivers/spi/spi-mem.c:250
Inline: True
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_write
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
**Symbols:**

```
ffffffff8175b720-ffffffff8175b766: spi_mem_access_end.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff817abd10)
Location: drivers/spi/spi-mem.c:250
Inline: True
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_write
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
**Symbols:**

```
ffffffff817abd10-ffffffff817abd56: spi_mem_access_end.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff817c5ca0)
Location: drivers/spi/spi-mem.c:250
Inline: True
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_write
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
**Symbols:**

```
ffffffff817c5ca0-ffffffff817c5ce6: spi_mem_access_end.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
