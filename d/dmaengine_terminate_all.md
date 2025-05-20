# Function: <code>dmaengine_terminate_all</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_dma.c (ffffffff815099b0)
Location: include/linux/dmaengine.h:831
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8155b930)
Location: include/linux/dmaengine.h:893
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma_flush
```
</details>
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
In drivers/video/fbdev/mx3fb.c (ffff80001075f84c)
Location: include/linux/dmaengine.h:914
Inline: True
Inline callers:
  - drivers/video/fbdev/mx3fb.c:sdc_disable_channel
```
```
In drivers/tty/serial/amba-pl011.c (ffff8000108961d4)
Location: include/linux/dmaengine.h:914
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_poll
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_callback
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_trigger_dma
```
```
In drivers/tty/serial/imx.c (ffff80001089c764)
Location: include/linux/dmaengine.h:914
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_flush_buffer
```
```
In drivers/tty/serial/msm_serial.c (ffff8000108a3ecc)
Location: include/linux/dmaengine.h:914
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_stop_dma
```
```
In drivers/mmc/host/mmci.c (ffff800010b460c8)
Location: include/linux/dmaengine.h:914
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_dmae_unprep_data
  - drivers/mmc/host/mmci.c:mmci_dmae_error
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
In drivers/video/fbdev/mx3fb.c (c08e18cc)
Location: include/linux/dmaengine.h:914
Inline: True
Inline callers:
  - drivers/video/fbdev/mx3fb.c:sdc_disable_channel
```
```
In drivers/soc/tegra/fuse/fuse-tegra20.c (c093a938)
Location: include/linux/dmaengine.h:914
Inline: True
Inline callers:
  - drivers/soc/tegra/fuse/fuse-tegra20.c:tegra20_fuse_read
```
```
In drivers/tty/serial/amba-pl011.c (c0992344)
Location: include/linux/dmaengine.h:914
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_poll
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_callback
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_trigger_dma
```
```
In drivers/tty/serial/imx.c (c09974f4)
Location: include/linux/dmaengine.h:914
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_flush_buffer
```
```
In drivers/tty/serial/msm_serial.c (c099d488)
Location: include/linux/dmaengine.h:914
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_stop_dma
```
```
In drivers/i2c/busses/i2c-imx.c (c0b9ba04)
Location: include/linux/dmaengine.h:914
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_xfer
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_read
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_dma_xfer
```
```
In drivers/mmc/host/mmci.c (c0c1feb4)
Location: include/linux/dmaengine.h:914
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_dmae_unprep_data
  - drivers/mmc/host/mmci.c:mmci_dmae_error
```
```
In drivers/mmc/host/omap_hsmmc.c (c0c2c700)
Location: include/linux/dmaengine.h:914
Inline: True
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
