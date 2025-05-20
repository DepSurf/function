# Function: <code>spi_block_write</code>

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
<summary>In <code>arm64</code>: ✅</summary>

```c
int spi_block_write(struct stmpe *stmpe, u8 reg, u8 length, const u8 *values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe-spi.c (ffff8000109304e0)
Location: drivers/mfd/stmpe-spi.c:50
Inline: False
```
**Symbols:**

```
ffff8000109304e0-ffff800010930590: spi_block_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int spi_block_write(struct stmpe *stmpe, u8 reg, u8 length, const u8 *values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe-spi.c (c0a11b14)
Location: drivers/mfd/stmpe-spi.c:50
Inline: False
```
**Symbols:**

```
c0a11b14-c0a11b70: spi_block_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int spi_block_write(struct stmpe *stmpe, u8 reg, u8 length, const u8 *values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe-spi.c (c0000000009d0540)
Location: drivers/mfd/stmpe-spi.c:50
Inline: False
```
**Symbols:**

```
c0000000009d0540-c0000000009d0638: spi_block_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int spi_block_write(struct stmpe *stmpe, u8 reg, u8 length, const u8 *values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe-spi.c (ffffffe0005a6c42)
Location: drivers/mfd/stmpe-spi.c:50
Inline: False
```
**Symbols:**

```
ffffffe0005a6c42-ffffffe0005a6cca: spi_block_write (STB_LOCAL)
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
