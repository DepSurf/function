# Function: <code>fsl_spi_change_mode</code>

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
In drivers/spi/spi-fsl-spi.c (ffff8000109cbec0)
Location: drivers/spi/spi-fsl-spi.c:89
Inline: True
Direct callers:
  - drivers/spi/spi-fsl-spi.c:fsl_spi_setup_transfer
  - drivers/spi/spi-fsl-spi.c:fsl_spi_chipselect
```
**Symbols:**

```
ffff8000109cbec0-ffff8000109cbf5c: fsl_spi_change_mode.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fsl_spi_change_mode(struct spi_device *spi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-fsl-spi.c (c0ab4b7c)
Location: drivers/spi/spi-fsl-spi.c:89
Inline: False
Direct callers:
  - drivers/spi/spi-fsl-spi.c:fsl_spi_setup_transfer
  - drivers/spi/spi-fsl-spi.c:fsl_spi_chipselect
```
**Symbols:**

```
c0ab4b7c-c0ab4bf4: fsl_spi_change_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fsl_spi_change_mode(struct spi_device *spi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-fsl-spi.c (c000000000a8dbd0)
Location: drivers/spi/spi-fsl-spi.c:89
Inline: False
Direct callers:
  - drivers/spi/spi-fsl-spi.c:fsl_spi_setup_transfer
  - drivers/spi/spi-fsl-spi.c:fsl_spi_chipselect
```
**Symbols:**

```
c000000000a8dbd0-c000000000a8dc80: fsl_spi_change_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fsl_spi_change_mode(struct spi_device *spi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-fsl-spi.c (ffffffe00061b108)
Location: drivers/spi/spi-fsl-spi.c:89
Inline: False
Direct callers:
  - drivers/spi/spi-fsl-spi.c:fsl_spi_setup_transfer
  - drivers/spi/spi-fsl-spi.c:fsl_spi_chipselect
```
**Symbols:**

```
ffffffe00061b108-ffffffe00061b208: fsl_spi_change_mode (STB_LOCAL)
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
