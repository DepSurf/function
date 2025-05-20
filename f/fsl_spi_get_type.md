# Function: <code>fsl_spi_get_type</code>

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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi-fsl-spi.c (ffff8000109cbac8)
Location: drivers/spi/spi-fsl-spi.c:77
Inline: True
Direct callers:
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
```
**Symbols:**

```
ffff8000109cbac8-ffff8000109cbb20: fsl_spi_get_type.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fsl_spi_get_type(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-fsl-spi.c (c0ab4f7c)
Location: drivers/spi/spi-fsl-spi.c:77
Inline: False
Direct callers:
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
```
**Symbols:**

```
c0ab4f7c-c0ab4fcc: fsl_spi_get_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fsl_spi_get_type(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-fsl-spi.c (c000000000a8d840)
Location: drivers/spi/spi-fsl-spi.c:77
Inline: False
Direct callers:
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
```
**Symbols:**

```
c000000000a8d840-c000000000a8d8c8: fsl_spi_get_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fsl_spi_get_type(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-fsl-spi.c (ffffffe00061afa2)
Location: drivers/spi/spi-fsl-spi.c:77
Inline: False
Direct callers:
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
```
**Symbols:**

```
ffffffe00061afa2-ffffffe00061afec: fsl_spi_get_type (STB_LOCAL)
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
