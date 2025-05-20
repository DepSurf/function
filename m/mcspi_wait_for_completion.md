# Function: <code>mcspi_wait_for_completion</code>

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
In drivers/spi/spi-omap2-mcspi.c (ffff8000109ce204)
Location: drivers/spi/spi-omap2-mcspi.c:356
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma
Direct callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma
```
**Symbols:**

```
ffff8000109cccf8-ffff8000109ccd44: mcspi_wait_for_completion.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int mcspi_wait_for_completion(struct omap2_mcspi *mcspi, struct completion *x);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-omap2-mcspi.c (c0ab688c)
Location: drivers/spi/spi-omap2-mcspi.c:356
Inline: True
Direct callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma
```
**Symbols:**

```
c0ab688c-c0ab68e8: mcspi_wait_for_completion (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
