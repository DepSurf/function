# Function: <code>stmpe_probe</code>

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
int stmpe_probe(struct stmpe_client_info *ci, enum stmpe_partnum partnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe.c (ffff80001092f688)
Location: drivers/mfd/stmpe.c:1378
Inline: False
Direct callers:
  - drivers/mfd/stmpe-i2c.c:stmpe_i2c_probe
  - drivers/mfd/stmpe-spi.c:stmpe_spi_probe
```
**Symbols:**

```
ffff80001092f688-ffff80001092ffd8: stmpe_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int stmpe_probe(struct stmpe_client_info *ci, enum stmpe_partnum partnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe.c (c0a10cf4)
Location: drivers/mfd/stmpe.c:1378
Inline: False
Direct callers:
  - drivers/mfd/stmpe-i2c.c:stmpe_i2c_probe
  - drivers/mfd/stmpe-spi.c:stmpe_spi_probe
```
**Symbols:**

```
c0a10cf4-c0a1165c: stmpe_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int stmpe_probe(struct stmpe_client_info *ci, enum stmpe_partnum partnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe.c (c0000000009cf3a0)
Location: drivers/mfd/stmpe.c:1378
Inline: False
Direct callers:
  - drivers/mfd/stmpe-i2c.c:stmpe_i2c_probe
  - drivers/mfd/stmpe-spi.c:stmpe_spi_probe
```
**Symbols:**

```
c0000000009cf3a0-c0000000009cfebc: stmpe_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int stmpe_probe(struct stmpe_client_info *ci, enum stmpe_partnum partnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe.c (ffffffe0005a6032)
Location: drivers/mfd/stmpe.c:1378
Inline: False
Direct callers:
  - drivers/mfd/stmpe-i2c.c:stmpe_i2c_probe
  - drivers/mfd/stmpe-spi.c:stmpe_spi_probe
```
**Symbols:**

```
ffffffe0005a6032-ffffffe0005a67fc: stmpe_probe (STB_GLOBAL)
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
