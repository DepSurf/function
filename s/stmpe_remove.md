# Function: <code>stmpe_remove</code>

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
int stmpe_remove(struct stmpe *stmpe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe.c (ffff80001092ffd8)
Location: drivers/mfd/stmpe.c:1495
Inline: False
Direct callers:
  - drivers/mfd/stmpe-i2c.c:stmpe_i2c_remove
  - drivers/mfd/stmpe-spi.c:stmpe_spi_remove
```
**Symbols:**

```
ffff80001092ffd8-ffff800010930040: stmpe_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int stmpe_remove(struct stmpe *stmpe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe.c (c0a1165c)
Location: drivers/mfd/stmpe.c:1495
Inline: False
Direct callers:
  - drivers/mfd/stmpe-i2c.c:stmpe_i2c_remove
  - drivers/mfd/stmpe-spi.c:stmpe_spi_remove
```
**Symbols:**

```
c0a1165c-c0a116bc: stmpe_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int stmpe_remove(struct stmpe *stmpe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe.c (c0000000009cfec0)
Location: drivers/mfd/stmpe.c:1495
Inline: False
Direct callers:
  - drivers/mfd/stmpe-i2c.c:stmpe_i2c_remove
  - drivers/mfd/stmpe-spi.c:stmpe_spi_remove
```
**Symbols:**

```
c0000000009cfec0-c0000000009cff5c: stmpe_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int stmpe_remove(struct stmpe *stmpe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe.c (ffffffe0005a67fc)
Location: drivers/mfd/stmpe.c:1495
Inline: False
Direct callers:
  - drivers/mfd/stmpe-i2c.c:stmpe_i2c_remove
  - drivers/mfd/stmpe-spi.c:stmpe_spi_remove
```
**Symbols:**

```
ffffffe0005a67fc-ffffffe0005a6854: stmpe_remove (STB_GLOBAL)
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
