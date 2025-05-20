# Function: <code>spi_new_ancillary_device</code>

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
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct spi_device *spi_new_ancillary_device(struct spi_device *spi, u8 chip_select);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2199
Inline: False
```
**Symbols:**

```
ffffffff81d0fe7b-ffffffff81d0feb6: spi_new_ancillary_device.cold (STB_LOCAL)
ffffffff818fcdb0-ffffffff818fce92: spi_new_ancillary_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct spi_device *spi_new_ancillary_device(struct spi_device *spi, u8 chip_select);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2243
Inline: False
```
**Symbols:**

```
ffffffff81edab7a-ffffffff81edabb5: spi_new_ancillary_device.cold (STB_LOCAL)
ffffffff81a4e3a0-ffffffff81a4e498: spi_new_ancillary_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct spi_device *spi_new_ancillary_device(struct spi_device *spi, u8 chip_select);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81bd8960)
Location: drivers/spi/spi.c:2423
Inline: False
```
**Symbols:**

```
ffffffff81bd8960-ffffffff81bd8a97: spi_new_ancillary_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct spi_device *spi_new_ancillary_device(struct spi_device *spi, u8 chip_select);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81c2f350)
Location: drivers/spi/spi.c:2432
Inline: False
```
**Symbols:**

```
ffffffff81c2f350-ffffffff81c2f487: spi_new_ancillary_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct spi_device *spi_new_ancillary_device(struct spi_device *spi, u8 chip_select);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81ce13b0)
Location: drivers/spi/spi.c:2541
Inline: False
```
**Symbols:**

```
ffffffff81ce13b0-ffffffff81ce14eb: spi_new_ancillary_device (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
