# Function: <code>fsl_spi_chipselect</code>

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
void fsl_spi_chipselect(struct spi_device *spi, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-fsl-spi.c (ffff8000109cbf60)
Location: drivers/spi/spi-fsl-spi.c:114
Inline: False
Direct callers:
  - drivers/spi/spi-fsl-spi.c:fsl_spi_setup
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
```
**Symbols:**

```
ffff8000109cbf60-ffff8000109cc020: fsl_spi_chipselect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fsl_spi_chipselect(struct spi_device *spi, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-fsl-spi.c (c0ab4bf4)
Location: drivers/spi/spi-fsl-spi.c:114
Inline: False
Direct callers:
  - drivers/spi/spi-fsl-spi.c:fsl_spi_setup
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
```
**Symbols:**

```
c0ab4bf4-c0ab4c94: fsl_spi_chipselect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fsl_spi_chipselect(struct spi_device *spi, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-fsl-spi.c (c000000000a8dc80)
Location: drivers/spi/spi-fsl-spi.c:114
Inline: False
Direct callers:
  - drivers/spi/spi-fsl-spi.c:fsl_spi_setup
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
```
**Symbols:**

```
c000000000a8dc80-c000000000a8dda0: fsl_spi_chipselect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fsl_spi_chipselect(struct spi_device *spi, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-fsl-spi.c (ffffffe00061b208)
Location: drivers/spi/spi-fsl-spi.c:114
Inline: False
Direct callers:
  - drivers/spi/spi-fsl-spi.c:fsl_spi_setup
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
```
**Symbols:**

```
ffffffe00061b208-ffffffe00061b2a0: fsl_spi_chipselect (STB_LOCAL)
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
