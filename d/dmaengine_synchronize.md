# Function: <code>dmaengine_synchronize</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff8150d656)
Location: include/linux/dmaengine.h:948
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81539786)
Location: include/linux/dmaengine.h:972
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff815880e9)
Location: include/linux/dmaengine.h:972
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff8154cfe7)
Location: include/linux/dmaengine.h:983
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8159c674)
Location: include/linux/dmaengine.h:983
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff815b0547)
Location: include/linux/dmaengine.h:972
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81601974)
Location: include/linux/dmaengine.h:972
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff815e8996)
Location: include/linux/dmaengine.h:976
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8163ac5c)
Location: include/linux/dmaengine.h:976
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81602746)
Location: include/linux/dmaengine.h:979
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81658e42)
Location: include/linux/dmaengine.h:979
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81634fd3)
Location: include/linux/dmaengine.h:967
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8168e348)
Location: include/linux/dmaengine.h:967
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81656ceb)
Location: include/linux/dmaengine.h:969
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816b0918)
Location: include/linux/dmaengine.h:969
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff8170757f)
Location: include/linux/dmaengine.h:1106
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81763cf8)
Location: include/linux/dmaengine.h:1106
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff817247cf)
Location: include/linux/dmaengine.h:1151
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8177ecbc)
Location: include/linux/dmaengine.h:1151
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81705a8f)
Location: include/linux/dmaengine.h:1153
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8176261c)
Location: include/linux/dmaengine.h:1153
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff8178135f)
Location: include/linux/dmaengine.h:1151
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff817e66e9)
Location: include/linux/dmaengine.h:1151
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff818b7ccf)
Location: include/linux/dmaengine.h:1174
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81925c6a)
Location: include/linux/dmaengine.h:1174
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81a04f6f)
Location: include/linux/dmaengine.h:1154
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81a826aa)
Location: include/linux/dmaengine.h:1154
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81a4ddcf)
Location: include/linux/dmaengine.h:1155
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81acdcc0)
Location: include/linux/dmaengine.h:1155
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81a99a6f)
Location: include/linux/dmaengine.h:1154
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81b20d90)
Location: include/linux/dmaengine.h:1154
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
</details>
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
In drivers/dma/dmaengine.c (ffff8000107fcbe4)
Location: include/linux/dmaengine.h:969
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffff80001088bdd0)
Location: include/linux/dmaengine.h:969
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/tty/serial/imx.c (ffff80001089cb3c)
Location: include/linux/dmaengine.h:969
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_dma_exit
  - drivers/tty/serial/imx.c:imx_uart_dma_exit
```
```
In drivers/spi/spi-omap2-mcspi.c (ffff8000109ce330)
Location: include/linux/dmaengine.h:969
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma
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
In drivers/dma/dmaengine.c (c091df28)
Location: include/linux/dmaengine.h:969
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (c09897a4)
Location: include/linux/dmaengine.h:969
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/tty/serial/imx.c (c0997824)
Location: include/linux/dmaengine.h:969
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_dma_exit
  - drivers/tty/serial/imx.c:imx_uart_dma_exit
```
```
In drivers/spi/spi-omap2-mcspi.c (c0ab7218)
Location: include/linux/dmaengine.h:969
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma
```
```
In sound/core/pcm_dmaengine.c (c0c9cc90)
Location: include/linux/dmaengine.h:969
Inline: True
Inline callers:
  - sound/core/pcm_dmaengine.c:snd_dmaengine_pcm_close_release_chan
  - sound/core/pcm_dmaengine.c:snd_dmaengine_pcm_close
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (c0000000008c7f58)
Location: include/linux/dmaengine.h:969
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (c000000000934870)
Location: include/linux/dmaengine.h:969
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
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
In drivers/dma/dmaengine.c (ffffffe000516c3e)
Location: include/linux/dmaengine.h:969
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffe0005556cc)
Location: include/linux/dmaengine.h:969
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff8161cb8b)
Location: include/linux/dmaengine.h:969
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81676388)
Location: include/linux/dmaengine.h:969
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff8161127b)
Location: include/linux/dmaengine.h:969
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81655468)
Location: include/linux/dmaengine.h:969
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff8164ab2b)
Location: include/linux/dmaengine.h:969
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816a4758)
Location: include/linux/dmaengine.h:969
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff816650cd)
Location: include/linux/dmaengine.h:969
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816beac4)
Location: include/linux/dmaengine.h:969
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
</details>
</li>
</ul>

## Differences
