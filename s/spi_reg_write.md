# Function: <code>spi_reg_write</code>

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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int spi_reg_write(struct stmpe *stmpe, u8 reg, u8 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe-spi.c (ffff800010930630)
Location: drivers/mfd/stmpe-spi.c:28
Inline: True
Inline callers:
  - drivers/mfd/stmpe-spi.c:spi_init
  - drivers/mfd/stmpe-spi.c:spi_block_write
```
**Symbols:**

```
ffff800010930658-ffff8000109306c4: spi_reg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int spi_reg_write(struct stmpe *stmpe, u8 reg, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe-spi.c (c0a11a08)
Location: drivers/mfd/stmpe-spi.c:28
Inline: False
Direct callers:
  - drivers/mfd/stmpe-spi.c:spi_init
  - drivers/mfd/stmpe-spi.c:spi_block_write
```
**Symbols:**

```
c0a11a08-c0a11a98: spi_reg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int spi_reg_write(struct stmpe *stmpe, u8 reg, u8 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe-spi.c (c0000000009d0700)
Location: drivers/mfd/stmpe-spi.c:28
Inline: True
Inline callers:
  - drivers/mfd/stmpe-spi.c:spi_init
  - drivers/mfd/stmpe-spi.c:spi_block_write
```
**Symbols:**

```
c0000000009d0730-c0000000009d07a0: spi_reg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int spi_reg_write(struct stmpe *stmpe, u8 reg, u8 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe-spi.c (ffffffe0005a6d42)
Location: drivers/mfd/stmpe-spi.c:28
Inline: True
Inline callers:
  - drivers/mfd/stmpe-spi.c:spi_init
  - drivers/mfd/stmpe-spi.c:spi_block_write
```
**Symbols:**

```
ffffffe0005a6d62-ffffffe0005a6da8: spi_reg_write (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
