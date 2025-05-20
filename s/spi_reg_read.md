# Function: <code>spi_reg_read</code>

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
int spi_reg_read(struct stmpe *stmpe, u8 reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe-spi.c (ffff8000109302e8)
Location: drivers/mfd/stmpe-spi.c:20
Inline: False
Direct callers:
  - drivers/mfd/stmpe-spi.c:spi_block_read
```
**Symbols:**

```
ffff8000109302e8-ffff800010930368: spi_reg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int spi_reg_read(struct stmpe *stmpe, u8 reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe-spi.c (c0a11898)
Location: drivers/mfd/stmpe-spi.c:20
Inline: False
Direct callers:
  - drivers/mfd/stmpe-spi.c:spi_block_read
```
**Symbols:**

```
c0a11898-c0a1191c: spi_reg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int spi_reg_read(struct stmpe *stmpe, u8 reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe-spi.c (c0000000009d0280)
Location: drivers/mfd/stmpe-spi.c:20
Inline: False
Direct callers:
  - drivers/mfd/stmpe-spi.c:spi_block_read
```
**Symbols:**

```
c0000000009d0280-c0000000009d030c: spi_reg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int spi_reg_read(struct stmpe *stmpe, u8 reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe-spi.c (ffffffe0005a6aba)
Location: drivers/mfd/stmpe-spi.c:20
Inline: False
Direct callers:
  - drivers/mfd/stmpe-spi.c:spi_block_read
```
**Symbols:**

```
ffffffe0005a6aba-ffffffe0005a6b0a: spi_reg_read (STB_LOCAL)
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
