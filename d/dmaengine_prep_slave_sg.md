# Function: <code>dmaengine_prep_slave_sg</code>

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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/mx3fb.c (ffff80001075f4fc)
Location: include/linux/dmaengine.h:837
Inline: True
Inline callers:
  - drivers/video/fbdev/mx3fb.c:mx3fb_pan_display
  - drivers/video/fbdev/mx3fb.c:sdc_enable_channel
```
```
In drivers/tty/serial/amba-pl011.c (ffff800010893778)
Location: include/linux/dmaengine.h:837
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_trigger_dma
  - drivers/tty/serial/amba-pl011.c:pl011_dma_tx_refill
```
```
In drivers/tty/serial/imx.c (ffff80001089aabc)
Location: include/linux/dmaengine.h:837
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_dma_tx
```
```
In drivers/spi/spi-omap2-mcspi.c (ffff8000109ce124)
Location: include/linux/dmaengine.h:837
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma
```
```
In drivers/mmc/host/mmci.c (ffff800010b45948)
Location: include/linux/dmaengine.h:837
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:_mmci_dmae_prep_data
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
In drivers/video/fbdev/mx3fb.c (c08e25a8)
Location: include/linux/dmaengine.h:837
Inline: True
Inline callers:
  - drivers/video/fbdev/mx3fb.c:mx3fb_pan_display
  - drivers/video/fbdev/mx3fb.c:sdc_enable_channel
```
```
In drivers/tty/serial/amba-pl011.c (c098ea2c)
Location: include/linux/dmaengine.h:837
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_trigger_dma
  - drivers/tty/serial/amba-pl011.c:pl011_dma_tx_refill
```
```
In drivers/tty/serial/imx.c (c0997a00)
Location: include/linux/dmaengine.h:837
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_dma_tx
```
```
In drivers/mtd/nand/raw/omap2.c (c0aac5bc)
Location: include/linux/dmaengine.h:837
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/omap2.c:omap_write_buf_dma_pref
  - drivers/mtd/nand/raw/omap2.c:omap_read_buf_dma_pref
```
```
In drivers/spi/spi-omap2-mcspi.c (c0ab7008)
Location: include/linux/dmaengine.h:837
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma
```
```
In drivers/mmc/host/mmci.c (c0c1f864)
Location: include/linux/dmaengine.h:837
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:_mmci_dmae_prep_data
```
```
In drivers/mmc/host/omap_hsmmc.c (c0c2bc94)
Location: include/linux/dmaengine.h:837
Inline: True
Inline callers:
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_request
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
