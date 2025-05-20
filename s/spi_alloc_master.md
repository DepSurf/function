# Function: <code>spi_alloc_master</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct spi_master *spi_alloc_master(struct device *dev, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff815e9410)
Location: drivers/spi/spi.c:1693
Inline: False
```
**Symbols:**

```
ffffffff815e9410-ffffffff815e948a: spi_alloc_master (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct spi_master *spi_alloc_master(struct device *dev, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81647af0)
Location: drivers/spi/spi.c:1782
Inline: False
```
**Symbols:**

```
ffffffff81647af0-ffffffff81647b71: spi_alloc_master (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct spi_master *spi_alloc_master(struct device *dev, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81678be0)
Location: drivers/spi/spi.c:1809
Inline: False
```
**Symbols:**

```
ffffffff81678be0-ffffffff81678c61: spi_alloc_master (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-fsl-spi.c (ffff8000109cbbd8)
Location: include/linux/spi/spi.h:654
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
```
```
In drivers/spi/spi-omap2-mcspi.c (ffff8000109cda90)
Location: include/linux/spi/spi.h:654
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-fsl-spi.c (c0ab532c)
Location: include/linux/spi/spi.h:654
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
```
```
In drivers/spi/spi-omap2-mcspi.c (c0ab7ac8)
Location: include/linux/spi/spi.h:654
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-fsl-spi.c (c000000000a8e228)
Location: include/linux/spi/spi.h:654
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-fsl-spi.c (ffffffe00061bd78)
Location: include/linux/spi/spi.h:654
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
```
```
In drivers/spi/spi-sifive.c (ffffffe00061c2b0)
Location: include/linux/spi/spi.h:654
Inline: True
Inline callers:
  - drivers/spi/spi-sifive.c:sifive_spi_probe
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
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
