# Function: <code>__raw_writeb</code>

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
In arch/arm64/kernel/io.c (ffff800010095c74)
Location: arch/arm64/include/asm/io.h:25
Inline: True
Inline callers:
  - arch/arm64/kernel/io.c:__memset_io
  - arch/arm64/kernel/io.c:__memset_io
  - arch/arm64/kernel/io.c:__memcpy_toio
  - arch/arm64/kernel/io.c:__memcpy_toio
```
```
In lib/logic_pio.c (ffff80001063e328)
Location: arch/arm64/include/asm/io.h:25
Inline: True
```
```
In drivers/irqchip/irq-gic-v3.c (ffff80001066e848)
Location: arch/arm64/include/asm/io.h:25
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_irq_set_prio
```
```
In drivers/bus/hisi_lpc.c (ffff80001067f8e0)
Location: arch/arm64/include/asm/io.h:25
Inline: True
Inline callers:
  - drivers/bus/hisi_lpc.c:hisi_lpc_target_out
```
```
In drivers/pinctrl/pinctrl-single.c (ffff80001069b690)
Location: arch/arm64/include/asm/io.h:25
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_writeb
```
```
In drivers/pinctrl/sh-pfc/core.c (ffff8000106afcbc)
Location: arch/arm64/include/asm/io.h:25
Inline: True
```
```
In drivers/gpio/gpio-mmio.c (ffff8000106cc1b8)
Location: arch/arm64/include/asm/io.h:25
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_write8
```
```
In drivers/gpio/gpio-pl061.c (ffff8000106d384c)
Location: arch/arm64/include/asm/io.h:25
Inline: True
Inline callers:
  - drivers/gpio/gpio-pl061.c:pl061_resume
  - drivers/gpio/gpio-pl061.c:pl061_resume
  - drivers/gpio/gpio-pl061.c:pl061_resume
  - drivers/gpio/gpio-pl061.c:pl061_resume
  - drivers/gpio/gpio-pl061.c:pl061_probe
  - drivers/gpio/gpio-pl061.c:pl061_irq_ack
  - drivers/gpio/gpio-pl061.c:pl061_irq_unmask
  - drivers/gpio/gpio-pl061.c:pl061_irq_mask
  - drivers/gpio/gpio-pl061.c:pl061_irq_type
  - drivers/gpio/gpio-pl061.c:pl061_irq_type
  - drivers/gpio/gpio-pl061.c:pl061_irq_type
  - drivers/gpio/gpio-pl061.c:pl061_set_value
  - drivers/gpio/gpio-pl061.c:pl061_direction_output
  - drivers/gpio/gpio-pl061.c:pl061_direction_output
  - drivers/gpio/gpio-pl061.c:pl061_direction_output
  - drivers/gpio/gpio-pl061.c:pl061_direction_input
```
```
In drivers/pci/access.c (ffff8000106da488)
Location: arch/arm64/include/asm/io.h:25
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/quirks.c (ffff8000106ff070)
Location: arch/arm64/include/asm/io.h:25
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/controller/pcie-cadence-host.c (ffff80001071dac8)
Location: arch/arm64/include/asm/io.h:25
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
```
In drivers/pci/controller/pcie-cadence-ep.c (ffff80001071dd9c)
Location: arch/arm64/include/asm/io.h:25
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
```
```
In drivers/pci/controller/pci-ftpci100.c (ffff80001071ef94)
Location: arch/arm64/include/asm/io.h:25
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_write_config
```
```
In drivers/pci/controller/pcie-altera.c (ffff800010726b5c)
Location: arch/arm64/include/asm/io.h:25
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera.c:s10_rp_write_cfg
```
```
In drivers/pci/controller/pcie-mobiveil.c (0)
Location: arch/arm64/include/asm/io.h:25
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffff80001072ce6c)
Location: arch/arm64/include/asm/io.h:25
Inline: True
```
```
In drivers/pci/controller/dwc/pci-layerscape.c (ffff800010733560)
Location: arch/arm64/include/asm/io.h:25
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_host_init
```
```
In drivers/video/fbdev/asiliantfb.c (ffff80001075d554)
Location: arch/arm64/include/asm/io.h:25
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
```
```
In drivers/acpi/osl.c (ffff800010763e04)
Location: arch/arm64/include/asm/io.h:25
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/acpi/cppc_acpi.c (ffff8000107aaaf8)
Location: arch/arm64/include/asm/io.h:25
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
```
```
In drivers/clk/renesas/renesas-cpg-mssr.c (ffff8000107ec0f0)
Location: arch/arm64/include/asm/io.h:25
Inline: True
Inline callers:
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_resume_noirq
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mstp_clock_endisable
```
```
In drivers/virtio/virtio_mmio.c (ffff800010825d9c)
Location: arch/arm64/include/asm/io.h:25
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/virtio/virtio_pci_modern.c (ffff8000108272a4)
Location: arch/arm64/include/asm/io.h:25
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_set
```
```
In drivers/virtio/virtio_pci_legacy.c (ffff8000108292d4)
Location: arch/arm64/include/asm/io.h:25
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffff800010885ba8)
Location: arch/arm64/include/asm/io.h:25
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffff80001088fd34)
Location: arch/arm64/include/asm/io.h:25
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:f815xxa_mem_serial_out
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffff800010890670)
Location: arch/arm64/include/asm/io.h:25
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/tty/serial/8250/8250_dw.c (ffff800010890e44)
Location: arch/arm64/include/asm/io.h:25
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dw.c:dw8250_serial_out
  - drivers/tty/serial/8250/8250_dw.c:dw8250_serial_out38x
  - drivers/tty/serial/8250/8250_dw.c:dw8250_check_lcr
```
```
In drivers/tty/serial/amba-pl011.c (ffff800010895a18)
Location: arch/arm64/include/asm/io.h:25
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_putc
```
```
In drivers/tty/serial/sccnxp.c (ffff80001089f920)
Location: arch/arm64/include/asm/io.h:25
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_write
```
```
In drivers/char/tpm/tpm_tis.c (ffff8000108c2740)
Location: arch/arm64/include/asm/io.h:25
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes
```
```
In drivers/base/regmap/regmap-mmio.c (ffff80001091c338)
Location: arch/arm64/include/asm/io.h:25
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write8
```
```
In drivers/ata/libata-sff.c (ffff8000109b168c)
Location: arch/arm64/include/asm/io.h:25
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_postreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_freeze
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
```
```
In drivers/ata/ahci_imx.c (ffff8000109b72d0)
Location: arch/arm64/include/asm/io.h:25
Inline: True
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fbed0)
Location: arch/arm64/include/asm/io.h:25
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_enable_device
  - drivers/net/ethernet/smsc/smc91x.c:smc_enable_device
  - drivers/net/ethernet/smsc/smc91x.c:smc_enable_device
  - drivers/net/ethernet/smsc/smc91x.c:smc_enable_device
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_tx
  - drivers/net/ethernet/smsc/smc91x.c:smc_tx
  - drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit
  - drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
  - drivers/net/ethernet/smsc/smc91x.c:smc_shutdown
  - drivers/net/ethernet/smsc/smc91x.c:smc_enable
  - drivers/net/ethernet/smsc/smc91x.c:smc_reset
```
```
In drivers/i2c/busses/i2c-sprd.c (ffff800010abd2e4)
Location: arch/arm64/include/asm/io.h:25
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_data_transfer
```
```
In drivers/firmware/arm_scmi/perf.c (ffff800010b57ed8)
Location: arch/arm64/include/asm/io.h:25
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db
```
```
In drivers/clocksource/sh_tmu.c (ffff800010b65c18)
Location: arch/arm64/include/asm/io.h:25
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_start_stop_ch
  - drivers/clocksource/sh_tmu.c:sh_tmu_start_stop_ch
```
```
In drivers/mailbox/pcc.c (ffff800010b7b838)
Location: arch/arm64/include/asm/io.h:25
Inline: True
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
In arch/arm/kernel/bios32.c (c0311234)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - arch/arm/kernel/bios32.c:pci_fixup_83c553
```
```
In arch/arm/kernel/smp_scu.c (c0314624)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - arch/arm/kernel/smp_scu.c:scu_cpu_power_enable
  - arch/arm/kernel/smp_scu.c:scu_power_mode
```
```
In arch/arm/kernel/io.c (c0319ed4)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - arch/arm/kernel/io.c:_memset_io
  - arch/arm/kernel/io.c:_memcpy_toio
```
```
In arch/arm/mach-shmobile/setup-r8a7740.c (c15198d0)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_init_irq_of
  - arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_init_irq_of
  - arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_init_irq_of
  - arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_init_irq_of
```
```
In drivers/irqchip/irq-gic-v3.c (0)
Location: arch/arm/include/asm/io.h:86
Inline: True
```
```
In drivers/irqchip/irq-renesas-intc-irqpin.c (c081efa8)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_write8
```
```
In drivers/irqchip/irq-crossbar.c (c0820974)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/irqchip/irq-crossbar.c:crossbar_writeb
```
```
In drivers/pinctrl/pinctrl-rza2.c (c083c598)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rza2.c:rza2_set_mux
  - drivers/pinctrl/pinctrl-rza2.c:rza2_set_mux
  - drivers/pinctrl/pinctrl-rza2.c:rza2_set_mux
  - drivers/pinctrl/pinctrl-rza2.c:rza2_set_mux
  - drivers/pinctrl/pinctrl-rza2.c:rza2_set_mux
  - drivers/pinctrl/pinctrl-rza2.c:rza2_set_mux
  - drivers/pinctrl/pinctrl-rza2.c:rza2_set_mux
  - drivers/pinctrl/pinctrl-rza2.c:rza2_chip_set
```
```
In drivers/pinctrl/pinctrl-single.c (c083f240)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_writeb
```
```
In drivers/pinctrl/sh-pfc/core.c (c0853674)
Location: arch/arm/include/asm/io.h:86
Inline: True
```
```
In drivers/pinctrl/sh-pfc/pfc-r8a7740.c (c085570c)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/pfc-r8a7740.c:r8a7740_pinmux_set_bias
```
```
In drivers/pinctrl/sh-pfc/pfc-sh73a0.c (c0855bd8)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/pfc-sh73a0.c:sh73a0_pinmux_set_bias
```
```
In drivers/gpio/gpio-mmio.c (c0867f50)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_write8
```
```
In drivers/gpio/gpio-pl061.c (c086ed20)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/gpio/gpio-pl061.c:pl061_resume
  - drivers/gpio/gpio-pl061.c:pl061_resume
  - drivers/gpio/gpio-pl061.c:pl061_resume
  - drivers/gpio/gpio-pl061.c:pl061_resume
  - drivers/gpio/gpio-pl061.c:pl061_probe
  - drivers/gpio/gpio-pl061.c:pl061_irq_ack
  - drivers/gpio/gpio-pl061.c:pl061_irq_unmask
  - drivers/gpio/gpio-pl061.c:pl061_irq_mask
  - drivers/gpio/gpio-pl061.c:pl061_irq_type
  - drivers/gpio/gpio-pl061.c:pl061_irq_type
  - drivers/gpio/gpio-pl061.c:pl061_irq_type
  - drivers/gpio/gpio-pl061.c:pl061_set_value
  - drivers/gpio/gpio-pl061.c:pl061_direction_output
  - drivers/gpio/gpio-pl061.c:pl061_direction_output
  - drivers/gpio/gpio-pl061.c:pl061_direction_output
  - drivers/gpio/gpio-pl061.c:pl061_direction_input
```
```
In drivers/pci/access.c (c08773f8)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/pci-sysfs.c (c0889b58)
Location: arch/arm/include/asm/io.h:86
Inline: True
```
```
In drivers/pci/quirks.c (c08947cc)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/controller/pcie-cadence-host.c (c08a6b04)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
```
In drivers/pci/controller/pcie-cadence-ep.c (c08a7050)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
```
```
In drivers/pci/controller/pci-ftpci100.c (c08a7f60)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_write_config
```
```
In drivers/pci/controller/pci-mvebu.c (c08a9300)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_wr_conf
```
```
In drivers/pci/controller/pci-v3-semi.c (c08b1604)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_irq
```
```
In drivers/pci/controller/pcie-altera.c (c08b1f74)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera.c:s10_rp_write_cfg
```
```
In drivers/pci/controller/dwc/pcie-designware.c (c08b6688)
Location: arch/arm/include/asm/io.h:86
Inline: True
```
```
In drivers/video/fbdev/asiliantfb.c (c08dffe0)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:mm_write_cr
  - drivers/video/fbdev/asiliantfb.c:mm_write_cr
  - drivers/video/fbdev/asiliantfb.c:mm_write_fr
  - drivers/video/fbdev/asiliantfb.c:mm_write_fr
  - drivers/video/fbdev/asiliantfb.c:mm_write_xr
  - drivers/video/fbdev/asiliantfb.c:mm_write_xr
```
```
In drivers/clk/renesas/renesas-cpg-mssr.c (c09058d8)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_resume_noirq
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mstp_clock_endisable
```
```
In drivers/clk/renesas/clk-mstp.c (c0905a80)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/clk/renesas/clk-mstp.c:cpg_mstp_clock_endisable
```
```
In drivers/dma/ti/dma-crossbar.c (c09337cc)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/dma/ti/dma-crossbar.c:ti_dma_xbar_probe
  - drivers/dma/ti/dma-crossbar.c:ti_dma_xbar_probe
  - drivers/dma/ti/dma-crossbar.c:ti_am335x_xbar_route_allocate
  - drivers/dma/ti/dma-crossbar.c:ti_am335x_xbar_route_allocate
  - drivers/dma/ti/dma-crossbar.c:ti_am335x_xbar_free
  - drivers/dma/ti/dma-crossbar.c:ti_am335x_xbar_free
```
```
In drivers/virtio/virtio_mmio.c (c094440c)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/virtio/virtio_pci_modern.c (c0945020)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_set
```
```
In drivers/virtio/virtio_pci_legacy.c (c0946ef4)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_set
```
```
In drivers/tty/serial/8250/8250_port.c (c0988ce4)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:io_serial_out
  - drivers/tty/serial/8250/8250_port.c:mem_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (c098a198)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:f815xxa_mem_serial_out
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqopr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqopr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqopr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqopr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqopr
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
```
```
In drivers/tty/serial/8250/8250_early.c (c098cea8)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/tty/serial/amba-pl011.c (c098f490)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_putc
```
```
In drivers/tty/serial/sccnxp.c (c0999948)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_write
```
```
In drivers/char/mem.c (c09a7234)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
```
```
In drivers/char/tpm/tpm_tis.c (c09bafe4)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes
```
```
In drivers/base/regmap/regmap-mmio.c (c0a01c24)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write8
```
```
In drivers/mfd/tmio_core.c (c0a0f438)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/mfd/tmio_core.c:tmio_core_mmc_clk_div
  - drivers/mfd/tmio_core.c:tmio_core_mmc_pwr
  - drivers/mfd/tmio_core.c:tmio_core_mmc_enable
  - drivers/mfd/tmio_core.c:tmio_core_mmc_enable
  - drivers/mfd/tmio_core.c:tmio_core_mmc_enable
```
```
In drivers/mfd/t7l66xb.c (c0a127cc)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/mfd/t7l66xb.c:t7l66xb_probe
  - drivers/mfd/t7l66xb.c:t7l66xb_irq_unmask
  - drivers/mfd/t7l66xb.c:t7l66xb_irq_mask
  - drivers/mfd/t7l66xb.c:t7l66xb_mmc_disable
  - drivers/mfd/t7l66xb.c:t7l66xb_mmc_enable
```
```
In drivers/mfd/tc6393xb.c (c0a13da8)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/mfd/tc6393xb.c:tc6393xb_resume
  - drivers/mfd/tc6393xb.c:tc6393xb_resume
  - drivers/mfd/tc6393xb.c:tc6393xb_resume
  - drivers/mfd/tc6393xb.c:tc6393xb_resume
  - drivers/mfd/tc6393xb.c:tc6393xb_resume
  - drivers/mfd/tc6393xb.c:tc6393xb_resume
  - drivers/mfd/tc6393xb.c:tc6393xb_probe
  - drivers/mfd/tc6393xb.c:tc6393xb_probe
  - drivers/mfd/tc6393xb.c:tc6393xb_probe
  - drivers/mfd/tc6393xb.c:tc6393xb_irq_unmask
  - drivers/mfd/tc6393xb.c:tc6393xb_irq_mask
  - drivers/mfd/tc6393xb.c:tc6393xb_gpio_direction_output
  - drivers/mfd/tc6393xb.c:tc6393xb_gpio_direction_input
  - drivers/mfd/tc6393xb.c:__tc6393xb_gpio_set
  - drivers/mfd/tc6393xb.c:tc6393xb_lcd_set_power
  - drivers/mfd/tc6393xb.c:tc6393xb_ohci_disable
  - drivers/mfd/tc6393xb.c:tc6393xb_ohci_enable
  - drivers/mfd/tc6393xb.c:tc6393xb_nand_enable
```
```
In drivers/mfd/omap-usb-tll.c (c0a3596c)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/mfd/omap-usb-tll.c:omap_tll_init
```
```
In drivers/ata/libata-sff.c (c0a7ec40)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_set_devctl
```
```
In drivers/ata/ahci_imx.c (c0a8a450)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
```
```
In drivers/mtd/maps/map_funcs.c (c0a996fc)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/mtd/maps/map_funcs.c:simple_map_write
```
```
In drivers/mtd/nand/raw/omap2.c (c0aa9dd4)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/omap2.c:omap_wait
  - drivers/mtd/nand/raw/omap2.c:omap_write_buf_pref
  - drivers/mtd/nand/raw/omap2.c:omap_write_buf8
```
```
In drivers/usb/host/pci-quirks.c (c0b222ec)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/ohci-hcd.c (c0b36de4)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_tmio_drv_resume
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_tmio_drv_suspend
  - drivers/usb/host/ohci-hcd.c:tmio_start_hc
  - drivers/usb/host/ohci-hcd.c:tmio_start_hc
  - drivers/usb/host/ohci-hcd.c:tmio_stop_hc
  - drivers/usb/host/ohci-hcd.c:tmio_stop_hc
```
```
In drivers/usb/host/uhci-hcd.c (c0b3cfbc)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:configure_hc
  - drivers/usb/host/uhci-hcd.c:configure_hc
```
```
In drivers/usb/musb/musb_core.c (c0b658fc)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/usb/musb/musb_core.c:musb_default_write_fifo
  - drivers/usb/musb/musb_core.c:musb_default_writeb
```
```
In drivers/rtc/rtc-mc146818-lib.c (c0b8aa08)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
```
```
In drivers/rtc/rtc-omap.c (c0b8bacc)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/rtc/rtc-omap.c:omap_rtc_shutdown
  - drivers/rtc/rtc-omap.c:omap_rtc_resume
  - drivers/rtc/rtc-omap.c:omap_rtc_suspend
  - drivers/rtc/rtc-omap.c:omap_rtc_remove
  - drivers/rtc/rtc-omap.c:omap_rtc_remove
  - drivers/rtc/rtc-omap.c:omap_rtc_probe
  - drivers/rtc/rtc-omap.c:omap_rtc_probe
  - drivers/rtc/rtc-omap.c:omap_rtc_power_off_program
  - drivers/rtc/rtc-omap.c:omap_rtc_power_off_program
  - drivers/rtc/rtc-omap.c:omap_rtc_power_off_program
  - drivers/rtc/rtc-omap.c:omap_rtc_power_off_program
  - drivers/rtc/rtc-omap.c:omap_rtc_power_off_program
  - drivers/rtc/rtc-omap.c:omap_rtc_power_off_program
  - drivers/rtc/rtc-omap.c:omap_rtc_set_alarm
  - drivers/rtc/rtc-omap.c:omap_rtc_set_alarm
  - drivers/rtc/rtc-omap.c:omap_rtc_set_alarm
  - drivers/rtc/rtc-omap.c:omap_rtc_set_alarm
  - drivers/rtc/rtc-omap.c:omap_rtc_set_alarm
  - drivers/rtc/rtc-omap.c:omap_rtc_set_alarm
  - drivers/rtc/rtc-omap.c:omap_rtc_set_alarm
  - drivers/rtc/rtc-omap.c:omap_rtc_set_alarm
  - drivers/rtc/rtc-omap.c:omap_rtc_set_time
  - drivers/rtc/rtc-omap.c:omap_rtc_set_time
  - drivers/rtc/rtc-omap.c:omap_rtc_set_time
  - drivers/rtc/rtc-omap.c:omap_rtc_set_time
  - drivers/rtc/rtc-omap.c:omap_rtc_set_time
  - drivers/rtc/rtc-omap.c:omap_rtc_set_time
  - drivers/rtc/rtc-omap.c:omap_rtc_alarm_irq_enable
  - drivers/rtc/rtc-omap.c:omap_rtc_alarm_irq_enable
  - drivers/rtc/rtc-omap.c:rtc_irq
```
```
In drivers/rtc/rtc-s3c.c (c0b8e07c)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/rtc/rtc-s3c.c:s3c24xx_rtc_restore_tick_cnt
  - drivers/rtc/rtc-s3c.c:s3c6410_rtc_irq
  - drivers/rtc/rtc-s3c.c:s3c24xx_rtc_disable
  - drivers/rtc/rtc-s3c.c:s3c_rtc_setalarm
  - drivers/rtc/rtc-s3c.c:s3c_rtc_setalarm
  - drivers/rtc/rtc-s3c.c:s3c_rtc_setalarm
  - drivers/rtc/rtc-s3c.c:s3c_rtc_setalarm
  - drivers/rtc/rtc-s3c.c:s3c_rtc_setalarm
  - drivers/rtc/rtc-s3c.c:s3c_rtc_setalarm
  - drivers/rtc/rtc-s3c.c:s3c_rtc_setalarm
  - drivers/rtc/rtc-s3c.c:s3c_rtc_settime
  - drivers/rtc/rtc-s3c.c:s3c_rtc_settime
  - drivers/rtc/rtc-s3c.c:s3c_rtc_settime
  - drivers/rtc/rtc-s3c.c:s3c_rtc_settime
  - drivers/rtc/rtc-s3c.c:s3c_rtc_settime
  - drivers/rtc/rtc-s3c.c:s3c_rtc_settime
  - drivers/rtc/rtc-s3c.c:s3c_rtc_setaie
```
```
In drivers/i2c/busses/i2c-imx.c (c0b9c31c)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_remove
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_remove
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_remove
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_remove
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_xfer
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_xfer
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_xfer
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_xfer
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_xfer
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_xfer
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_xfer
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_xfer
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_xfer
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_read
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_read
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_read
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_read
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_read
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_read
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_read
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_read
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_isr
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_start
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_start
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_start
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_start
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_start
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_bus_busy
```
```
In drivers/i2c/busses/i2c-s3c2410.c (c0b9de68)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_init
  - drivers/i2c/busses/i2c-s3c2410.c:i2c_s3c_irq_nextbyte
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_message_start
```
```
In drivers/thermal/samsung/exynos_tmu.c (c0bbef90)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/thermal/samsung/exynos_tmu.c:exynos4210_tmu_set_trip_temp
  - drivers/thermal/samsung/exynos_tmu.c:exynos4210_tmu_set_trip_temp
```
```
In drivers/mmc/host/sdhci.c (c0c268a8)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci.c:sdhci_cqe_enable
  - drivers/mmc/host/sdhci.c:sdhci_resume_host
  - drivers/mmc/host/sdhci.c:sdhci_suspend_host
  - drivers/mmc/host/sdhci.c:sdhci_set_ios
  - drivers/mmc/host/sdhci.c:sdhci_set_ios
  - drivers/mmc/host/sdhci.c:sdhci_set_ios
  - drivers/mmc/host/sdhci.c:sdhci_set_bus_width
  - drivers/mmc/host/sdhci.c:sdhci_set_power
  - drivers/mmc/host/sdhci.c:sdhci_set_power
  - drivers/mmc/host/sdhci.c:sdhci_set_power_noreg
  - drivers/mmc/host/sdhci.c:sdhci_set_power_noreg
  - drivers/mmc/host/sdhci.c:sdhci_set_power_noreg
  - drivers/mmc/host/sdhci.c:sdhci_set_power_noreg
  - drivers/mmc/host/sdhci.c:sdhci_prepare_data
  - drivers/mmc/host/sdhci.c:sdhci_led_control
  - drivers/mmc/host/sdhci.c:sdhci_reset
```
```
In drivers/firmware/arm_scmi/perf.c (c0c396fc)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db
```
```
In drivers/clocksource/sh_mtu2.c (c0c45b40)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/clocksource/sh_mtu2.c:sh_mtu2_interrupt
  - drivers/clocksource/sh_mtu2.c:sh_mtu2_start_stop_ch
```
```
In drivers/clocksource/renesas-ostm.c (c15aa964)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/clocksource/renesas-ostm.c:ostm_init
  - drivers/clocksource/renesas-ostm.c:ostm_init
  - drivers/clocksource/renesas-ostm.c:ostm_set_periodic
  - drivers/clocksource/renesas-ostm.c:ostm_set_periodic
  - drivers/clocksource/renesas-ostm.c:ostm_clock_event_next
  - drivers/clocksource/renesas-ostm.c:ostm_clock_event_next
```
```
In drivers/clocksource/sh_tmu.c (c0c45f38)
Location: arch/arm/include/asm/io.h:86
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_start_stop_ch
  - drivers/clocksource/sh_tmu.c:sh_tmu_start_stop_ch
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-single.c (ffffffe00049fd54)
Location: arch/riscv/include/asm/io.h:33
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_writeb
```
```
In drivers/gpio/gpio-mmio.c (ffffffe0004ad1b6)
Location: arch/riscv/include/asm/io.h:33
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_write8
```
```
In drivers/pci/access.c (ffffffe0004b39be)
Location: arch/riscv/include/asm/io.h:33
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/quirks.c (ffffffe0004cbe48)
Location: arch/riscv/include/asm/io.h:33
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/controller/pcie-cadence-host.c (ffffffe0004e483e)
Location: arch/riscv/include/asm/io.h:33
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
```
In drivers/pci/controller/pcie-cadence-ep.c (ffffffe0004e4bb0)
Location: arch/riscv/include/asm/io.h:33
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
```
```
In drivers/pci/controller/pci-ftpci100.c (ffffffe0004e6058)
Location: arch/riscv/include/asm/io.h:33
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffe0004e768e)
Location: arch/riscv/include/asm/io.h:33
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffe0004f0bc4)
Location: arch/riscv/include/asm/io.h:33
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffe000507476)
Location: arch/riscv/include/asm/io.h:33
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:mm_write_cr
  - drivers/video/fbdev/asiliantfb.c:mm_write_cr
  - drivers/video/fbdev/asiliantfb.c:mm_write_fr
  - drivers/video/fbdev/asiliantfb.c:mm_write_fr
  - drivers/video/fbdev/asiliantfb.c:mm_write_xr
  - drivers/video/fbdev/asiliantfb.c:mm_write_xr
```
```
In drivers/virtio/virtio_mmio.c (ffffffe00051cb50)
Location: arch/riscv/include/asm/io.h:33
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffe00051d700)
Location: arch/riscv/include/asm/io.h:33
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_set
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffe00051f6f4)
Location: arch/riscv/include/asm/io.h:33
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffe000554d22)
Location: arch/riscv/include/asm/io.h:33
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:io_serial_out
  - drivers/tty/serial/8250/8250_port.c:mem_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffe0005561a6)
Location: arch/riscv/include/asm/io.h:33
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_enter_key
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_enter_key
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_enter_key
  - drivers/tty/serial/8250/8250_fintek.c:sio_write_mask_reg
  - drivers/tty/serial/8250/8250_fintek.c:sio_write_mask_reg
  - drivers/tty/serial/8250/8250_fintek.c:sio_write_mask_reg
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffe000556a76)
Location: arch/riscv/include/asm/io.h:33
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:f815xxa_mem_serial_out
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqopr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqopr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqopr
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffe0005598f4)
Location: arch/riscv/include/asm/io.h:33
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/tty/serial/sccnxp.c (ffffffe00055c162)
Location: arch/riscv/include/asm/io.h:33
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_write
```
```
In drivers/char/mem.c (ffffffe00055fcbc)
Location: arch/riscv/include/asm/io.h:33
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
```
```
In drivers/char/tpm/tpm_tis.c (ffffffe0005738fe)
Location: arch/riscv/include/asm/io.h:33
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffe00059bd1c)
Location: arch/riscv/include/asm/io.h:33
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write8
```
```
In drivers/ata/libata-sff.c (ffffffe00060c67e)
Location: arch/riscv/include/asm/io.h:33
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
```
```
In drivers/usb/host/pci-quirks.c (ffffffe00066c8d2)
Location: arch/riscv/include/asm/io.h:33
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffe000680bfc)
Location: arch/riscv/include/asm/io.h:33
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:configure_hc
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
