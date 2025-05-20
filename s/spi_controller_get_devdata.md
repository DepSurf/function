# Function: <code>spi_controller_get_devdata</code>

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
In drivers/spi/spi-fsl-lib.c (ffff8000109cb6b4)
Location: include/linux/spi/spi.h:612
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-lib.c:mpc8xxx_spi_probe
```
```
In drivers/spi/spi-fsl-spi.c (ffff8000109cbc28)
Location: include/linux/spi/spi.h:612
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:fsl_spi_grlib_cs_control
  - drivers/spi/spi-fsl-spi.c:fsl_spi_setup
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_setup_transfer
  - drivers/spi/spi-fsl-spi.c:fsl_spi_chipselect
```
```
In drivers/spi/spi-omap2-mcspi.c (ffff8000109cca44)
Location: include/linux/spi/spi.h:612
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_resume
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_suspend
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_remove
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap_mcspi_runtime_resume
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_can_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_prepare_message
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_slave_abort
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_irq_handler
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_release_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup_transfer
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma
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
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-fsl-lib.c (c0ab4960)
Location: include/linux/spi/spi.h:612
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-lib.c:mpc8xxx_spi_probe
```
```
In drivers/spi/spi-fsl-spi.c (c0ab5380)
Location: include/linux/spi/spi.h:612
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:fsl_spi_grlib_cs_control
  - drivers/spi/spi-fsl-spi.c:fsl_spi_setup
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_setup_transfer
  - drivers/spi/spi-fsl-spi.c:fsl_spi_chipselect
  - drivers/spi/spi-fsl-spi.c:fsl_spi_change_mode
```
```
In drivers/spi/spi-omap2-mcspi.c (c0ab5c64)
Location: include/linux/spi/spi.h:612
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_resume
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_suspend
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_remove
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap_mcspi_runtime_resume
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_can_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_prepare_message
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_slave_abort
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_irq_handler
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_release_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup_transfer
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_tx_callback
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_callback
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_cs
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
In drivers/spi/spi-fsl-lib.c (c000000000a8d49c)
Location: include/linux/spi/spi.h:612
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-lib.c:mpc8xxx_spi_probe
```
```
In drivers/spi/spi-fsl-spi.c (c000000000a8e288)
Location: include/linux/spi/spi.h:612
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:fsl_spi_grlib_cs_control
  - drivers/spi/spi-fsl-spi.c:fsl_spi_setup
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_setup_transfer
  - drivers/spi/spi-fsl-spi.c:fsl_spi_chipselect
  - drivers/spi/spi-fsl-spi.c:fsl_spi_change_mode
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
In drivers/spi/spi-fsl-lib.c (ffffffe00061ada4)
Location: include/linux/spi/spi.h:612
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-lib.c:mpc8xxx_spi_probe
```
```
In drivers/spi/spi-fsl-spi.c (ffffffe00061bdbc)
Location: include/linux/spi/spi.h:612
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:fsl_spi_grlib_cs_control
  - drivers/spi/spi-fsl-spi.c:fsl_spi_setup
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_setup_transfer
  - drivers/spi/spi-fsl-spi.c:fsl_spi_chipselect
  - drivers/spi/spi-fsl-spi.c:fsl_spi_change_mode
```
```
In drivers/spi/spi-sifive.c (ffffffe00061c230)
Location: include/linux/spi/spi.h:612
Inline: True
Inline callers:
  - drivers/spi/spi-sifive.c:sifive_spi_remove
  - drivers/spi/spi-sifive.c:sifive_spi_probe
  - drivers/spi/spi-sifive.c:sifive_spi_transfer_one
  - drivers/spi/spi-sifive.c:sifive_spi_set_cs
  - drivers/spi/spi-sifive.c:sifive_spi_prepare_message
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
