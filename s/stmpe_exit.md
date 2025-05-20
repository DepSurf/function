# Function: <code>stmpe_exit</code>

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
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
void stmpe_exit();
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe-i2c.c (ffff8000114b9d48)
Location: drivers/mfd/stmpe-i2c.c:133
Inline: False
```
```
In drivers/mfd/stmpe-spi.c (ffff8000114b9d64)
Location: drivers/mfd/stmpe-spi.c:153
Inline: False
```
**Symbols:**

```
ffff8000114b9d48-ffff8000114b9d64: stmpe_exit (STB_LOCAL)
ffff8000114b9d64-ffff8000114b9d84: stmpe_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
void stmpe_exit();
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe-i2c.c (c15bfdc4)
Location: drivers/mfd/stmpe-i2c.c:133
Inline: False
```
```
In drivers/mfd/stmpe-spi.c (c15bfde0)
Location: drivers/mfd/stmpe-spi.c:153
Inline: False
```
**Symbols:**

```
c15bfdc4-c15bfde0: stmpe_exit (STB_LOCAL)
c15bfde0-c15bfdfc: stmpe_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
void stmpe_exit();
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe-i2c.c (c0000000013cd0b8)
Location: drivers/mfd/stmpe-i2c.c:133
Inline: False
```
```
In drivers/mfd/stmpe-spi.c (c0000000013cd0ec)
Location: drivers/mfd/stmpe-spi.c:153
Inline: False
```
**Symbols:**

```
c0000000013cd0b8-c0000000013cd0ec: stmpe_exit (STB_LOCAL)
c0000000013cd0ec-c0000000013cd120: stmpe_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
void stmpe_exit();
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe-i2c.c (ffffffe0000a181c)
Location: drivers/mfd/stmpe-i2c.c:133
Inline: False
```
```
In drivers/mfd/stmpe-spi.c (ffffffe0000a183c)
Location: drivers/mfd/stmpe-spi.c:153
Inline: False
```
**Symbols:**

```
ffffffe0000a181c-ffffffe0000a183c: stmpe_exit (STB_LOCAL)
ffffffe0000a183c-ffffffe0000a185c: stmpe_exit (STB_LOCAL)
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
