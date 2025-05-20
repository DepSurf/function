# Function: <code>mcspi_cached_chconf0</code>

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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-omap2-mcspi.c (ffff8000109ce9a8)
Location: drivers/spi/spi-omap2-mcspi.c:175
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup_transfer
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_tx_callback
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_callback
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_fifo
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_cs
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-omap2-mcspi.c (c0ab779c)
Location: drivers/spi/spi-omap2-mcspi.c:175
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup_transfer
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_tx_callback
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_callback
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_cs
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
