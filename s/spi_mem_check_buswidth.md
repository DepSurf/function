# Function: <code>spi_mem_check_buswidth</code>

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
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool spi_mem_check_buswidth(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff8186eb20)
Location: drivers/spi/spi-mem.c:140
Inline: True
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_dtr_supports_op
```
**Symbols:**

```
ffffffff8186eb20-ffffffff8186ebe8: spi_mem_check_buswidth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool spi_mem_check_buswidth(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff818fec30)
Location: drivers/spi/spi-mem.c:141
Inline: True
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_dtr_supports_op
```
**Symbols:**

```
ffffffff818fec30-ffffffff818fecf8: spi_mem_check_buswidth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff81a50493)
Location: drivers/spi/spi-mem.c:142
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_default_supports_op
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff81bd9623)
Location: drivers/spi/spi-mem.c:142
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_default_supports_op
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff81c30023)
Location: drivers/spi/spi-mem.c:142
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_default_supports_op
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff81ce2ee3)
Location: drivers/spi/spi-mem.c:142
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_default_supports_op
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
