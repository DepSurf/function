# Function: <code>spi_get_csgpiod</code>

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
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81c2b1fc)
Location: include/linux/spi/spi.h:289
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_validate
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_set_cs
  - drivers/spi/spi.c:spi_set_cs
  - drivers/spi/spi.c:spi_set_cs
  - drivers/spi/spi.c:spi_set_cs
  - drivers/spi/spi.c:spi_set_cs
```
```
In drivers/spi/spi-mem.c (ffffffff81c30b97)
Location: include/linux/spi/spi.h:289
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/spi/spi-mem.c:spi_mem_exec_op
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
In drivers/spi/spi.c (ffffffff81cdda52)
Location: include/linux/spi/spi.h:302
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_validate
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_set_cs
  - drivers/spi/spi.c:spi_set_cs
  - drivers/spi/spi.c:spi_set_cs
  - drivers/spi/spi.c:spi_set_cs
```
```
In drivers/spi/spi-mem.c (ffffffff81ce3a27)
Location: include/linux/spi/spi.h:302
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
