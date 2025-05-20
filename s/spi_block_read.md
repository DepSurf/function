# Function: <code>spi_block_read</code>

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
int spi_block_read(struct stmpe *stmpe, u8 reg, u8 length, u8 *values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe-spi.c (ffff800010930368)
Location: drivers/mfd/stmpe-spi.c:36
Inline: False
```
**Symbols:**

```
ffff800010930368-ffff8000109303ec: spi_block_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int spi_block_read(struct stmpe *stmpe, u8 reg, u8 length, u8 *values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe-spi.c (c0a1191c)
Location: drivers/mfd/stmpe-spi.c:36
Inline: False
```
**Symbols:**

```
c0a1191c-c0a11974: spi_block_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int spi_block_read(struct stmpe *stmpe, u8 reg, u8 length, u8 *values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe-spi.c (c0000000009d0310)
Location: drivers/mfd/stmpe-spi.c:36
Inline: False
```
**Symbols:**

```
c0000000009d0310-c0000000009d03e4: spi_block_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int spi_block_read(struct stmpe *stmpe, u8 reg, u8 length, u8 *values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe-spi.c (ffffffe0005a6b0a)
Location: drivers/mfd/stmpe-spi.c:36
Inline: False
```
**Symbols:**

```
ffffffe0005a6b0a-ffffffe0005a6b7c: spi_block_read (STB_LOCAL)
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
