# Function: <code>ndelay</code>

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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/mach-qcom/platsmp.c (c0348fb4)
Location: include/linux/delay.h:49
Inline: True
Inline callers:
  - arch/arm/mach-qcom/platsmp.c:kpssv1_release_secondary
```
```
In drivers/clk/mvebu/dove-divider.c (c0903dc4)
Location: include/linux/delay.h:49
Inline: True
Inline callers:
  - drivers/clk/mvebu/dove-divider.c:dove_set_clock
```
```
In drivers/tty/serial/sccnxp.c (c09996bc)
Location: include/linux/delay.h:49
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_get_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_port_read
  - drivers/tty/serial/sccnxp.c:sccnxp_write
```
```
In drivers/ata/libata-sff.c (c0a807fc)
Location: include/linux/delay.h:49
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_dev_select
```
```
In drivers/mtd/nand/raw/nand_base.c (c0aa04fc)
Location: include/linux/delay.h:49
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/nand_base.c:nand_soft_waitrdy
```
```
In drivers/mtd/nand/raw/nand_legacy.c (c0aa39d4)
Location: include/linux/delay.h:49
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/nand_legacy.c:nand_command_lp
  - drivers/mtd/nand/raw/nand_legacy.c:nand_command
```
```
In drivers/spi/spi.c (c0ab05f4)
Location: include/linux/delay.h:49
Inline: True
```
```
In drivers/spi/spi-fsl-spi.c (c0ab5908)
Location: include/linux/delay.h:49
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
```
```
In drivers/usb/dwc2/core.c (c0b0dd28)
Location: include/linux/delay.h:49
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
```
```
In drivers/i2c/i2c-core-base.c (c0b92c70)
Location: include/linux/delay.h:49
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
```
```
In drivers/i2c/busses/i2c-s3c2410.c (c0b9edac)
Location: include/linux/delay.h:49
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-s3c2410.c:i2c_s3c_irq_nextbyte
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_message_start
```
```
In drivers/mmc/host/mmci.c (c0c2012c)
Location: include/linux/delay.h:49
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_runtime_resume
  - drivers/mmc/host/mmci.c:mmci_runtime_suspend
  - drivers/mmc/host/mmci.c:mmci_set_ios
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
In drivers/tty/serial/sccnxp.c (c00000000093c660)
Location: include/linux/delay.h:49
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_write
  - drivers/tty/serial/sccnxp.c:sccnxp_read
```
```
In drivers/ata/libata-sff.c (c000000000a78fcc)
Location: include/linux/delay.h:49
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_dev_select
```
```
In drivers/spi/spi.c (c000000000a86ed0)
Location: include/linux/delay.h:49
Inline: True
```
```
In drivers/spi/spi-fsl-spi.c (c000000000a8e9e0)
Location: include/linux/delay.h:49
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
```
```
In drivers/usb/dwc2/core.c (c000000000af856c)
Location: include/linux/delay.h:49
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
```
```
In drivers/i2c/i2c-core-base.c (c000000000b9161c)
Location: include/linux/delay.h:49
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ndelay(long unsigned int nsecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/lib/delay.c (ffffffe0008c3c2a)
Location: arch/riscv/lib/delay.c:98
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_get_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_port_read
  - drivers/tty/serial/sccnxp.c:sccnxp_write
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
```
**Symbols:**

```
ffffffe0008c3c2a-ffffffe0008c3c80: ndelay (STB_GLOBAL)
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
