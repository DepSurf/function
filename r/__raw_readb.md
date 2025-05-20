# Function: <code>__raw_readb</code>

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
In arch/arm64/kernel/io.c (ffff800010095d2c)
Location: arch/arm64/include/asm/io.h:49
Inline: True
Inline callers:
  - arch/arm64/kernel/io.c:__memcpy_fromio
  - arch/arm64/kernel/io.c:__memcpy_fromio
```
```
In lib/check_signature.c (ffff80001063e17c)
Location: arch/arm64/include/asm/io.h:49
Inline: True
Inline callers:
  - lib/check_signature.c:check_signature
```
```
In lib/logic_pio.c (ffff80001063e2a8)
Location: arch/arm64/include/asm/io.h:49
Inline: True
```
```
In drivers/bus/hisi_lpc.c (ffff80001067fbd8)
Location: arch/arm64/include/asm/io.h:49
Inline: True
Inline callers:
  - drivers/bus/hisi_lpc.c:hisi_lpc_target_in
```
```
In drivers/pinctrl/pinctrl-single.c (ffff80001069b5d0)
Location: arch/arm64/include/asm/io.h:49
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_readb
```
```
In drivers/pinctrl/sh-pfc/core.c (ffff8000106afc1c)
Location: arch/arm64/include/asm/io.h:49
Inline: True
```
```
In drivers/gpio/gpio-mmio.c (ffff8000106cc1e0)
Location: arch/arm64/include/asm/io.h:49
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_read8
```
```
In drivers/gpio/gpio-pl061.c (ffff8000106d3a18)
Location: arch/arm64/include/asm/io.h:49
Inline: True
Inline callers:
  - drivers/gpio/gpio-pl061.c:pl061_suspend
  - drivers/gpio/gpio-pl061.c:pl061_suspend
  - drivers/gpio/gpio-pl061.c:pl061_suspend
  - drivers/gpio/gpio-pl061.c:pl061_suspend
  - drivers/gpio/gpio-pl061.c:pl061_suspend
  - drivers/gpio/gpio-pl061.c:pl061_irq_unmask
  - drivers/gpio/gpio-pl061.c:pl061_irq_mask
  - drivers/gpio/gpio-pl061.c:pl061_irq_handler
  - drivers/gpio/gpio-pl061.c:pl061_irq_type
  - drivers/gpio/gpio-pl061.c:pl061_irq_type
  - drivers/gpio/gpio-pl061.c:pl061_irq_type
  - drivers/gpio/gpio-pl061.c:pl061_get_value
  - drivers/gpio/gpio-pl061.c:pl061_direction_output
  - drivers/gpio/gpio-pl061.c:pl061_direction_input
  - drivers/gpio/gpio-pl061.c:pl061_get_direction
```
```
In drivers/pci/access.c (ffff8000106da898)
Location: arch/arm64/include/asm/io.h:49
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffff8000106ef890)
Location: arch/arm64/include/asm/io.h:49
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (ffff8000106fca24)
Location: arch/arm64/include/asm/io.h:49
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffff8000107111bc)
Location: arch/arm64/include/asm/io.h:49
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_get_cur_bus_speed
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
```
```
In drivers/pci/controller/pcie-altera.c (ffff8000107271bc)
Location: arch/arm64/include/asm/io.h:49
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera.c:_altera_pcie_cfg_write
  - drivers/pci/controller/pcie-altera.c:_altera_pcie_cfg_read
  - drivers/pci/controller/pcie-altera.c:s10_rp_read_cfg
```
```
In drivers/pci/controller/pcie-mobiveil.c (0)
Location: arch/arm64/include/asm/io.h:49
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffff80001072cd74)
Location: arch/arm64/include/asm/io.h:49
Inline: True
```
```
In drivers/pci/controller/dwc/pci-layerscape.c (ffff80001147a534)
Location: arch/arm64/include/asm/io.h:49
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffff80001075d928)
Location: arch/arm64/include/asm/io.h:49
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/acpi/osl.c (ffff800010763b38)
Location: arch/arm64/include/asm/io.h:49
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffff8000107a9abc)
Location: arch/arm64/include/asm/io.h:49
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
```
```
In drivers/clk/renesas/renesas-cpg-mssr.c (ffff8000107ebfc4)
Location: arch/arm64/include/asm/io.h:49
Inline: True
Inline callers:
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_resume_noirq
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_resume_noirq
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mstp_clock_is_enabled
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mstp_clock_endisable
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mstp_clock_endisable
```
```
In drivers/virtio/virtio_mmio.c (ffff800010826c10)
Location: arch/arm64/include/asm/io.h:49
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/virtio/virtio_pci_modern.c (ffff8000108272b4)
Location: arch/arm64/include/asm/io.h:49
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_generation
  - drivers/virtio/virtio_pci_modern.c:vp_get
```
```
In drivers/virtio/virtio_pci_common.c (ffff8000108284fc)
Location: arch/arm64/include/asm/io.h:49
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_interrupt
```
```
In drivers/virtio/virtio_pci_legacy.c (ffff800010829078)
Location: arch/arm64/include/asm/io.h:49
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffff800010885b44)
Location: arch/arm64/include/asm/io.h:49
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffff80001088fd3c)
Location: arch/arm64/include/asm/io.h:49
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:f815xxa_mem_serial_out
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
```
```
In drivers/tty/serial/8250/8250_early.c (ffff800010890788)
Location: arch/arm64/include/asm/io.h:49
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/tty/serial/8250/8250_dw.c (ffff800010890abc)
Location: arch/arm64/include/asm/io.h:49
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dw.c:dw8250_serial_in
  - drivers/tty/serial/8250/8250_dw.c:dw8250_serial_out38x
```
```
In drivers/tty/serial/sccnxp.c (ffff80001089f8bc)
Location: arch/arm64/include/asm/io.h:49
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_read
```
```
In drivers/char/tpm/tpm_tis.c (ffff8000108c26a8)
Location: arch/arm64/include/asm/io.h:49
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes
```
```
In drivers/base/regmap/regmap-mmio.c (ffff80001091c44c)
Location: arch/arm64/include/asm/io.h:49
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read8
```
```
In drivers/ata/libata-sff.c (ffff8000109b17a8)
Location: arch/arm64/include/asm/io.h:49
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_bmdma_status
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
```
```
In drivers/ata/ahci_imx.c (ffff8000109b72f4)
Location: arch/arm64/include/asm/io.h:49
Inline: True
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fbe90)
Location: arch/arm64/include/asm/io.h:49
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_enable_device
  - drivers/net/ethernet/smsc/smc91x.c:smc_enable_device
  - drivers/net/ethernet/smsc/smc91x.c:smc_enable_device
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_timeout
  - drivers/net/ethernet/smsc/smc91x.c:smc_timeout
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_tx
  - drivers/net/ethernet/smsc/smc91x.c:smc_tx
  - drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit
  - drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
  - drivers/net/ethernet/smsc/smc91x.c:smc_rcv
```
```
In drivers/usb/host/pci-quirks.c (ffff800010a51358)
Location: arch/arm64/include/asm/io.h:49
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffff800010a591c0)
Location: arch/arm64/include/asm/io.h:49
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
```
In drivers/i2c/busses/i2c-sprd.c (ffff800010abc8d0)
Location: arch/arm64/include/asm/io.h:49
Inline: True
```
```
In drivers/firmware/arm_scmi/perf.c (ffff800010b57f04)
Location: arch/arm64/include/asm/io.h:49
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db
```
```
In drivers/clocksource/sh_tmu.c (ffff800010b65bb4)
Location: arch/arm64/include/asm/io.h:49
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_start_stop_ch
  - drivers/clocksource/sh_tmu.c:sh_tmu_start_stop_ch
```
```
In drivers/mailbox/pcc.c (ffff800010b7b728)
Location: arch/arm64/include/asm/io.h:49
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:read_register
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
In arch/arm/kernel/smp_scu.c (c0314660)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - arch/arm/kernel/smp_scu.c:scu_get_cpu_power_mode
  - arch/arm/kernel/smp_scu.c:scu_cpu_power_enable
  - arch/arm/kernel/smp_scu.c:scu_power_mode
```
```
In arch/arm/kernel/io.c (c0319de0)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - arch/arm/kernel/io.c:_memcpy_fromio
```
```
In arch/arm/mach-tegra/cpuidle-tegra20.c (c034ba0c)
Location: arch/arm/include/asm/io.h:100
Inline: True
```
```
In kernel/debug/kdb/kdb_keyboard.c (c0445954)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state
  - kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state
  - kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
```
```
In lib/check_signature.c (c07e4190)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - lib/check_signature.c:check_signature
```
```
In drivers/irqchip/irq-renesas-intc-irqpin.c (c081ed28)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_read8
```
```
In drivers/pinctrl/pinctrl-rza2.c (c083c570)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rza2.c:rza2_set_mux
  - drivers/pinctrl/pinctrl-rza2.c:rza2_set_mux
  - drivers/pinctrl/pinctrl-rza2.c:rza2_chip_set
  - drivers/pinctrl/pinctrl-rza2.c:rza2_chip_get
```
```
In drivers/pinctrl/pinctrl-single.c (c083e39c)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_readb
```
```
In drivers/pinctrl/sh-pfc/core.c (c0853600)
Location: arch/arm/include/asm/io.h:100
Inline: True
```
```
In drivers/pinctrl/sh-pfc/pfc-r8a7740.c (c08556dc)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/pfc-r8a7740.c:r8a7740_pinmux_set_bias
  - drivers/pinctrl/sh-pfc/pfc-r8a7740.c:r8a7740_pinmux_get_bias
```
```
In drivers/pinctrl/sh-pfc/pfc-sh73a0.c (c0855ba8)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/pfc-sh73a0.c:sh73a0_pinmux_set_bias
  - drivers/pinctrl/sh-pfc/pfc-sh73a0.c:sh73a0_pinmux_get_bias
```
```
In drivers/gpio/gpio-mmio.c (c0867290)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_read8
```
```
In drivers/gpio/gpio-pl061.c (c086eaec)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/gpio/gpio-pl061.c:pl061_suspend
  - drivers/gpio/gpio-pl061.c:pl061_suspend
  - drivers/gpio/gpio-pl061.c:pl061_suspend
  - drivers/gpio/gpio-pl061.c:pl061_suspend
  - drivers/gpio/gpio-pl061.c:pl061_suspend
  - drivers/gpio/gpio-pl061.c:pl061_suspend
  - drivers/gpio/gpio-pl061.c:pl061_irq_unmask
  - drivers/gpio/gpio-pl061.c:pl061_irq_mask
  - drivers/gpio/gpio-pl061.c:pl061_irq_handler
  - drivers/gpio/gpio-pl061.c:pl061_irq_type
  - drivers/gpio/gpio-pl061.c:pl061_irq_type
  - drivers/gpio/gpio-pl061.c:pl061_irq_type
  - drivers/gpio/gpio-pl061.c:pl061_direction_output
  - drivers/gpio/gpio-pl061.c:pl061_direction_input
  - drivers/gpio/gpio-pl061.c:pl061_get_direction
```
```
In drivers/pci/access.c (c0877084)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/pci-sysfs.c (c0889e7c)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/pci/rom.c (c088a468)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (c0895064)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/controller/pci-mvebu.c (c08a946c)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_rd_conf
```
```
In drivers/pci/controller/pci-v3-semi.c (c08b16c8)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_irq
```
```
In drivers/pci/controller/pcie-altera.c (c08b1e04)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera.c:_altera_pcie_cfg_write
  - drivers/pci/controller/pcie-altera.c:_altera_pcie_cfg_read
  - drivers/pci/controller/pcie-altera.c:s10_rp_read_cfg
```
```
In drivers/pci/controller/dwc/pcie-designware.c (c08b65e8)
Location: arch/arm/include/asm/io.h:100
Inline: True
```
```
In drivers/video/fbdev/asiliantfb.c (c08e02e0)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/clk/renesas/renesas-cpg-mssr.c (c0905818)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_resume_noirq
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_resume_noirq
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mstp_clock_is_enabled
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mstp_clock_endisable
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mstp_clock_endisable
```
```
In drivers/clk/renesas/clk-mstp.c (c09059c0)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/clk/renesas/clk-mstp.c:cpg_mstp_clock_is_enabled
  - drivers/clk/renesas/clk-mstp.c:cpg_mstp_clock_is_enabled
  - drivers/clk/renesas/clk-mstp.c:cpg_mstp_clock_endisable
  - drivers/clk/renesas/clk-mstp.c:cpg_mstp_clock_endisable
  - drivers/clk/renesas/clk-mstp.c:cpg_mstp_clock_endisable
```
```
In drivers/virtio/virtio_mmio.c (c0944304)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/virtio/virtio_pci_modern.c (c0945038)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_generation
  - drivers/virtio/virtio_pci_modern.c:vp_get
```
```
In drivers/virtio/virtio_pci_common.c (c0945f90)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_interrupt
```
```
In drivers/virtio/virtio_pci_legacy.c (c0946d0c)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_get
```
```
In drivers/tty/serial/8250/8250_port.c (c0988cfc)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:io_serial_in
  - drivers/tty/serial/8250/8250_port.c:mem_serial_in
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (c0989fb0)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_in
  - drivers/tty/serial/8250/8250_pci.c:f815xxa_mem_serial_out
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqopr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqopr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqopr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqopr
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
```
```
In drivers/tty/serial/8250/8250_early.c (c098cdb8)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/tty/serial/sccnxp.c (c09996b0)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_get_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_port_read
```
```
In drivers/char/mem.c (c09a6e30)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/char/mem.c:read_port
```
```
In drivers/char/tpm/tpm_tis.c (c09baeb4)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes
```
```
In drivers/base/regmap/regmap-mmio.c (c0a01ac0)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read8
```
```
In drivers/mfd/t7l66xb.c (c0a127d8)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/mfd/t7l66xb.c:t7l66xb_probe
  - drivers/mfd/t7l66xb.c:t7l66xb_irq_unmask
  - drivers/mfd/t7l66xb.c:t7l66xb_irq_mask
  - drivers/mfd/t7l66xb.c:t7l66xb_irq
  - drivers/mfd/t7l66xb.c:t7l66xb_irq
  - drivers/mfd/t7l66xb.c:t7l66xb_mmc_disable
  - drivers/mfd/t7l66xb.c:t7l66xb_mmc_enable
```
```
In drivers/mfd/tc6393xb.c (c0a132f0)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/mfd/tc6393xb.c:tc6393xb_suspend
  - drivers/mfd/tc6393xb.c:tc6393xb_suspend
  - drivers/mfd/tc6393xb.c:tc6393xb_suspend
  - drivers/mfd/tc6393xb.c:tc6393xb_suspend
  - drivers/mfd/tc6393xb.c:tc6393xb_probe
  - drivers/mfd/tc6393xb.c:tc6393xb_irq_unmask
  - drivers/mfd/tc6393xb.c:tc6393xb_irq_mask
  - drivers/mfd/tc6393xb.c:tc6393xb_irq
  - drivers/mfd/tc6393xb.c:tc6393xb_irq
  - drivers/mfd/tc6393xb.c:tc6393xb_gpio_direction_output
  - drivers/mfd/tc6393xb.c:tc6393xb_gpio_direction_input
  - drivers/mfd/tc6393xb.c:__tc6393xb_gpio_set
  - drivers/mfd/tc6393xb.c:tc6393xb_gpio_get
  - drivers/mfd/tc6393xb.c:tc6393xb_lcd_set_power
  - drivers/mfd/tc6393xb.c:tc6393xb_ohci_disable
  - drivers/mfd/tc6393xb.c:tc6393xb_ohci_enable
```
```
In drivers/ata/libata-sff.c (c0a804a4)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
  - drivers/ata/libata-sff.c:ata_bmdma_status
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
```
```
In drivers/ata/ahci_imx.c (c0a8a468)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
```
```
In drivers/mtd/maps/map_funcs.c (c0a99608)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/mtd/maps/map_funcs.c:simple_map_read
```
```
In drivers/mtd/nand/raw/nand_legacy.c (c0aa2fc8)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/nand_legacy.c:nand_read_byte
```
```
In drivers/mtd/nand/raw/omap2.c (c0aa9e08)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/omap2.c:omap_wait
  - drivers/mtd/nand/raw/omap2.c:omap_wait
```
```
In drivers/usb/host/pci-quirks.c (c0b222fc)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/ehci-hcd.c (c0b2edac)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
```
In drivers/usb/host/ohci-hcd.c (c0b36dc8)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_tmio_drv_resume
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_tmio_drv_suspend
  - drivers/usb/host/ohci-hcd.c:tmio_start_hc
```
```
In drivers/usb/host/uhci-hcd.c (c0b3d61c)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
```
```
In drivers/usb/musb/musb_core.c (c0b65a0c)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/usb/musb/musb_core.c:musb_default_read_fifo
  - drivers/usb/musb/musb_core.c:musb_default_readb
```
```
In drivers/rtc/rtc-mc146818-lib.c (c0b8aa18)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
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
In drivers/rtc/rtc-omap.c (c0b8bab0)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/rtc/rtc-omap.c:omap_rtc_shutdown
  - drivers/rtc/rtc-omap.c:omap_rtc_suspend
  - drivers/rtc/rtc-omap.c:omap_rtc_remove
  - drivers/rtc/rtc-omap.c:omap_rtc_probe
  - drivers/rtc/rtc-omap.c:omap_rtc_probe
  - drivers/rtc/rtc-omap.c:omap_rtc_probe
  - drivers/rtc/rtc-omap.c:omap_rtc_probe
  - drivers/rtc/rtc-omap.c:omap_rtc_power_off_program
  - drivers/rtc/rtc-omap.c:omap_rtc_power_off_program
  - drivers/rtc/rtc-omap.c:omap_rtc_power_off_program
  - drivers/rtc/rtc-omap.c:omap_rtc_power_off_program
  - drivers/rtc/rtc-omap.c:omap_rtc_set_alarm
  - drivers/rtc/rtc-omap.c:omap_rtc_set_alarm
  - drivers/rtc/rtc-omap.c:omap_rtc_set_alarm
  - drivers/rtc/rtc-omap.c:omap_rtc_read_alarm
  - drivers/rtc/rtc-omap.c:omap_rtc_read_alarm
  - drivers/rtc/rtc-omap.c:omap_rtc_read_alarm
  - drivers/rtc/rtc-omap.c:omap_rtc_read_alarm
  - drivers/rtc/rtc-omap.c:omap_rtc_read_alarm
  - drivers/rtc/rtc-omap.c:omap_rtc_read_alarm
  - drivers/rtc/rtc-omap.c:omap_rtc_read_alarm
  - drivers/rtc/rtc-omap.c:omap_rtc_read_alarm
  - drivers/rtc/rtc-omap.c:omap_rtc_set_time
  - drivers/rtc/rtc-omap.c:omap_rtc_read_time
  - drivers/rtc/rtc-omap.c:omap_rtc_read_time_raw
  - drivers/rtc/rtc-omap.c:omap_rtc_read_time_raw
  - drivers/rtc/rtc-omap.c:omap_rtc_read_time_raw
  - drivers/rtc/rtc-omap.c:omap_rtc_read_time_raw
  - drivers/rtc/rtc-omap.c:omap_rtc_read_time_raw
  - drivers/rtc/rtc-omap.c:omap_rtc_read_time_raw
  - drivers/rtc/rtc-omap.c:omap_rtc_alarm_irq_enable
  - drivers/rtc/rtc-omap.c:omap_rtc_alarm_irq_enable
  - drivers/rtc/rtc-omap.c:omap_rtc_alarm_irq_enable
  - drivers/rtc/rtc-omap.c:omap_rtc_alarm_irq_enable
  - drivers/rtc/rtc-omap.c:rtc_irq
```
```
In drivers/rtc/rtc-s3c.c (c0b8ddc0)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/rtc/rtc-s3c.c:s3c24xx_rtc_save_tick_cnt
  - drivers/rtc/rtc-s3c.c:s3c24xx_rtc_enable_tick
  - drivers/rtc/rtc-s3c.c:s3c2443_rtc_setfreq
  - drivers/rtc/rtc-s3c.c:s3c2416_rtc_setfreq
  - drivers/rtc/rtc-s3c.c:s3c2410_rtc_setfreq
  - drivers/rtc/rtc-s3c.c:s3c24xx_rtc_disable
  - drivers/rtc/rtc-s3c.c:s3c_rtc_setalarm
  - drivers/rtc/rtc-s3c.c:s3c_rtc_getalarm
  - drivers/rtc/rtc-s3c.c:s3c_rtc_getalarm
  - drivers/rtc/rtc-s3c.c:s3c_rtc_getalarm
  - drivers/rtc/rtc-s3c.c:s3c_rtc_getalarm
  - drivers/rtc/rtc-s3c.c:s3c_rtc_getalarm
  - drivers/rtc/rtc-s3c.c:s3c_rtc_getalarm
  - drivers/rtc/rtc-s3c.c:s3c_rtc_getalarm
  - drivers/rtc/rtc-s3c.c:s3c_rtc_gettime
  - drivers/rtc/rtc-s3c.c:s3c_rtc_gettime
  - drivers/rtc/rtc-s3c.c:s3c_rtc_gettime
  - drivers/rtc/rtc-s3c.c:s3c_rtc_gettime
  - drivers/rtc/rtc-s3c.c:s3c_rtc_gettime
  - drivers/rtc/rtc-s3c.c:s3c_rtc_gettime
  - drivers/rtc/rtc-s3c.c:s3c_rtc_setaie
```
```
In drivers/i2c/busses/i2c-imx.c (c0b9b390)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
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
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_read
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_read
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_read
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_read
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_read
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_read
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_isr
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_start
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_bus_busy
```
```
In drivers/i2c/busses/i2c-s3c2410.c (c0b9ea98)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-s3c2410.c:i2c_s3c_irq_nextbyte
```
```
In drivers/thermal/samsung/exynos_tmu.c (c0bbda58)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/thermal/samsung/exynos_tmu.c:exynos4412_tmu_read
  - drivers/thermal/samsung/exynos_tmu.c:exynos4210_tmu_read
  - drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_initialize
```
```
In drivers/mmc/host/sdhci.c (c0c26860)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci.c:sdhci_cqe_enable
  - drivers/mmc/host/sdhci.c:sdhci_resume_host
  - drivers/mmc/host/sdhci.c:sdhci_suspend_host
  - drivers/mmc/host/sdhci.c:sdhci_set_ios
  - drivers/mmc/host/sdhci.c:sdhci_set_bus_width
  - drivers/mmc/host/sdhci.c:sdhci_prepare_data
  - drivers/mmc/host/sdhci.c:sdhci_led_control
  - drivers/mmc/host/sdhci.c:sdhci_led_control
  - drivers/mmc/host/sdhci.c:sdhci_reset
  - drivers/mmc/host/sdhci.c:sdhci_dumpregs
  - drivers/mmc/host/sdhci.c:sdhci_dumpregs
  - drivers/mmc/host/sdhci.c:sdhci_dumpregs
  - drivers/mmc/host/sdhci.c:sdhci_dumpregs
  - drivers/mmc/host/sdhci.c:sdhci_dumpregs
```
```
In drivers/mmc/host/sdhci-esdhc-imx.c (c0c2df24)
Location: arch/arm/include/asm/io.h:100
Inline: True
```
```
In drivers/firmware/arm_scmi/perf.c (c0c396d4)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db
```
```
In drivers/clocksource/sh_mtu2.c (c0c45b2c)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/clocksource/sh_mtu2.c:sh_mtu2_interrupt
  - drivers/clocksource/sh_mtu2.c:sh_mtu2_start_stop_ch
```
```
In drivers/clocksource/renesas-ostm.c (c15aa928)
Location: arch/arm/include/asm/io.h:100
Inline: True
Inline callers:
  - drivers/clocksource/renesas-ostm.c:ostm_init
  - drivers/clocksource/renesas-ostm.c:ostm_timer_interrupt
  - drivers/clocksource/renesas-ostm.c:ostm_set_periodic
  - drivers/clocksource/renesas-ostm.c:ostm_shutdown
  - drivers/clocksource/renesas-ostm.c:ostm_clock_event_next
```
```
In drivers/clocksource/sh_tmu.c (c0c45eec)
Location: arch/arm/include/asm/io.h:100
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
In lib/check_signature.c (ffffffe00046b9ec)
Location: arch/riscv/include/asm/io.h:59
Inline: True
Inline callers:
  - lib/check_signature.c:check_signature
```
```
In drivers/pinctrl/pinctrl-single.c (ffffffe00049fccc)
Location: arch/riscv/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_readb
```
```
In drivers/gpio/gpio-mmio.c (ffffffe0004ad202)
Location: arch/riscv/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_read8
```
```
In drivers/pci/access.c (ffffffe0004b390e)
Location: arch/riscv/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffe0004c36d0)
Location: arch/riscv/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (ffffffe0004cc6b8)
Location: arch/riscv/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffe0004dd0a8)
Location: arch/riscv/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_get_cur_bus_speed
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffe0004e75d8)
Location: arch/riscv/include/asm/io.h:59
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffe0004f097c)
Location: arch/riscv/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffe0005077ee)
Location: arch/riscv/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/virtio/virtio_mmio.c (ffffffe00051cccc)
Location: arch/riscv/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffe00051d738)
Location: arch/riscv/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_generation
  - drivers/virtio/virtio_pci_modern.c:vp_get
```
```
In drivers/virtio/virtio_pci_common.c (ffffffe00051e6d2)
Location: arch/riscv/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_interrupt
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffe00051f4f4)
Location: arch/riscv/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffe000554d12)
Location: arch/riscv/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:io_serial_in
  - drivers/tty/serial/8250/8250_port.c:mem_serial_in
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffe000556068)
Location: arch/riscv/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:sio_write_mask_reg
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffe000556ae8)
Location: arch/riscv/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_in
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
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqopr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqopr
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffe000559790)
Location: arch/riscv/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/tty/serial/sccnxp.c (ffffffe00055c04a)
Location: arch/riscv/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_get_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_port_read
```
```
In drivers/char/mem.c (ffffffe00055fd7c)
Location: arch/riscv/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/char/mem.c:read_port
```
```
In drivers/char/tpm/tpm_tis.c (ffffffe000573882)
Location: arch/riscv/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffe00059beae)
Location: arch/riscv/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read8
```
```
In drivers/ata/libata-sff.c (ffffffe00060e00e)
Location: arch/riscv/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
  - drivers/ata/libata-sff.c:ata_bmdma_status
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
```
```
In drivers/usb/host/pci-quirks.c (ffffffe00066c8e8)
Location: arch/riscv/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/ehci-hcd.c (ffffffe000676816)
Location: arch/riscv/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
```
In drivers/usb/host/uhci-hcd.c (ffffffe000683268)
Location: arch/riscv/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
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
