# Function: <code>stmpe_init</code>

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
int stmpe_init();
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe-i2c.c (ffff800011498a38)
Location: drivers/mfd/stmpe-i2c.c:127
Inline: False
```
```
In drivers/mfd/stmpe-spi.c (ffff800011498a60)
Location: drivers/mfd/stmpe-spi.c:147
Inline: False
```
**Symbols:**

```
ffff800011498a38-ffff800011498a60: stmpe_init (STB_LOCAL)
ffff800011498a60-ffff800011498a88: stmpe_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
int stmpe_init();
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe-i2c.c (c159988c)
Location: drivers/mfd/stmpe-i2c.c:127
Inline: False
```
```
In drivers/mfd/stmpe-spi.c (c15998b4)
Location: drivers/mfd/stmpe-spi.c:147
Inline: False
```
**Symbols:**

```
c159988c-c15998b4: stmpe_init (STB_LOCAL)
c15998b4-c15998dc: stmpe_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
int stmpe_init();
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe-i2c.c (c0000000013abed4)
Location: drivers/mfd/stmpe-i2c.c:127
Inline: False
```
```
In drivers/mfd/stmpe-spi.c (c0000000013abf14)
Location: drivers/mfd/stmpe-spi.c:147
Inline: False
```
**Symbols:**

```
c0000000013abed4-c0000000013abf14: stmpe_init (STB_LOCAL)
c0000000013abf14-c0000000013abf54: stmpe_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
int stmpe_init();
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe-i2c.c (ffffffe000031fa8)
Location: drivers/mfd/stmpe-i2c.c:127
Inline: False
```
```
In drivers/mfd/stmpe-spi.c (ffffffe000031fd4)
Location: drivers/mfd/stmpe-spi.c:147
Inline: False
```
**Symbols:**

```
ffffffe000031fa8-ffffffe000031fd4: stmpe_init (STB_LOCAL)
ffffffe000031fd4-ffffffe000032000: stmpe_init (STB_LOCAL)
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
