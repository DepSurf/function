# Function: <code>__raw_readw</code>

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
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u16 __raw_readw(volatile const void *addr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/logic_pio.c (ffff80001063e4d8)
Location: arch/arm64/include/asm/io.h:60
Inline: True
```
```
In drivers/pinctrl/pinctrl-single.c (ffff80001069b610)
Location: arch/arm64/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_readw
```
```
In drivers/pinctrl/sh-pfc/core.c (ffff8000106afbf8)
Location: arch/arm64/include/asm/io.h:60
Inline: True
```
```
In drivers/gpio/gpio-mmio.c (ffff8000106cc2e0)
Location: arch/arm64/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_read16be
  - drivers/gpio/gpio-mmio.c:bgpio_read16
```
```
In drivers/pci/access.c (ffff8000106da864)
Location: arch/arm64/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffff8000106ef840)
Location: arch/arm64/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (ffff8000106fcaf4)
Location: arch/arm64/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffff80001070f9d4)
Location: arch/arm64/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_get_cur_bus_speed
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
```
```
In drivers/pci/controller/pcie-cadence-ep.c (ffff80001071e90c)
Location: arch/arm64/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_get_msi
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_msi
```
```
In drivers/pci/controller/pcie-altera.c (ffff800010727038)
Location: arch/arm64/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera.c:s10_rp_read_cfg
  - drivers/pci/controller/pcie-altera.c:s10_altera_pcie_link_up
```
```
In drivers/pci/controller/pcie-mobiveil.c (0)
Location: arch/arm64/include/asm/io.h:60
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffff80001072cdbc)
Location: arch/arm64/include/asm/io.h:60
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-qcom.c (ffff800010733880)
Location: arch/arm64/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_link_up
```
```
In drivers/acpi/osl.c (ffff800010763ac8)
Location: arch/arm64/include/asm/io.h:60
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffff8000107a99f4)
Location: arch/arm64/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/clk/renesas/rcar-usb2-clock-sel.c (ffff8000107eb400)
Location: arch/arm64/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:usb2_clock_sel_enable_extal_only
```
```
In drivers/virtio/virtio_mmio.c (ffff800010826b80)
Location: arch/arm64/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/virtio/virtio_pci_modern.c (ffff8000108274b0)
Location: arch/arm64/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_config_vector
  - drivers/virtio/virtio_pci_modern.c:vp_get
```
```
In drivers/virtio/virtio_pci_legacy.c (ffff800010829358)
Location: arch/arm64/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_config_vector
```
```
In drivers/tty/serial/8250/8250_port.c (ffff800010885c34)
Location: arch/arm64/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffff80001088fbfc)
Location: arch/arm64/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffff80001089074c)
Location: arch/arm64/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/tty/serial/amba-pl011.c (ffff800010893718)
Location: arch/arm64/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_read
```
```
In drivers/char/tpm/tpm_tis.c (ffff8000108c2784)
Location: arch/arm64/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read16
```
```
In drivers/base/regmap/regmap-mmio.c (ffff80001091c494)
Location: arch/arm64/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16be
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16le
```
```
In drivers/ata/libata-sff.c (ffff8000109b0684)
Location: arch/arm64/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_data_xfer32
  - drivers/ata/libata-sff.c:ata_sff_data_xfer
  - drivers/ata/libata-sff.c:ata_sff_data_xfer
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fb2d8)
Location: arch/arm64/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_timeout
  - drivers/net/ethernet/smsc/smc91x.c:smc_timeout
  - drivers/net/ethernet/smsc/smc91x.c:smc_timeout
  - drivers/net/ethernet/smsc/smc91x.c:smc_timeout
  - drivers/net/ethernet/smsc/smc91x.c:smc_timeout
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_10bt_check_media
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_write
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_read
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_read
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_read
  - drivers/net/ethernet/smsc/smc91x.c:smc_mii_out
  - drivers/net/ethernet/smsc/smc91x.c:smc_tx
  - drivers/net/ethernet/smsc/smc91x.c:smc_tx
  - drivers/net/ethernet/smsc/smc91x.c:smc_tx
  - drivers/net/ethernet/smsc/smc91x.c:smc_tx
  - drivers/net/ethernet/smsc/smc91x.c:smc_tx
  - drivers/net/ethernet/smsc/smc91x.c:smc_tx
  - drivers/net/ethernet/smsc/smc91x.c:smc_tx
  - drivers/net/ethernet/smsc/smc91x.c:smc_tx
  - drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit
  - drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit
  - drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
  - drivers/net/ethernet/smsc/smc91x.c:smc_rcv
  - drivers/net/ethernet/smsc/smc91x.c:smc_rcv
  - drivers/net/ethernet/smsc/smc91x.c:smc_rcv
  - drivers/net/ethernet/smsc/smc91x.c:smc_rcv
  - drivers/net/ethernet/smsc/smc91x.c:smc_rcv
  - drivers/net/ethernet/smsc/smc91x.c:smc_rcv
  - drivers/net/ethernet/smsc/smc91x.c:smc_rcv
  - drivers/net/ethernet/smsc/smc91x.c:smc_rcv
  - drivers/net/ethernet/smsc/smc91x.c:smc_rcv
  - drivers/net/ethernet/smsc/smc91x.c:smc_rcv
  - drivers/net/ethernet/smsc/smc91x.c:smc_shutdown
  - drivers/net/ethernet/smsc/smc91x.c:smc_reset
  - drivers/net/ethernet/smsc/smc91x.c:smc_reset
  - drivers/net/ethernet/smsc/smc91x.c:smc_reset
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffff800010ab8af0)
Location: arch/arm64/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_readl
  - drivers/i2c/busses/i2c-designware-common.c:dw_readl
```
```
In drivers/i2c/busses/i2c-omap.c (ffff800010abb5d4)
Location: arch/arm64/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_runtime_suspend
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_runtime_suspend
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_runtime_suspend
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_unprepare_recovery
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_prepare_recovery
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_set_scl
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_get_sda
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_get_scl
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_isr
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_isr
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_common
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_common
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_wait_for_bb
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_recover_bus
Direct callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
```
```
In drivers/firmware/arm_scmi/perf.c (ffff800010b57f68)
Location: arch/arm64/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db
```
```
In drivers/clocksource/sh_cmt.c (ffff800010b63c8c)
Location: arch/arm64/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_read16
```
```
In drivers/clocksource/sh_tmu.c (ffff800010b660c8)
Location: arch/arm64/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_set_next
```
```
In drivers/clocksource/mmio.c (ffff800010b663b0)
Location: arch/arm64/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/clocksource/mmio.c:clocksource_mmio_readw_down
  - drivers/clocksource/mmio.c:clocksource_mmio_readw_up
```
```
In drivers/mailbox/pcc.c (ffff800010b7b688)
Location: arch/arm64/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:read_register
```
**Symbols:**

```
ffff800010abada0-ffff800010abada8: __raw_readw (STB_LOCAL)
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
In arch/arm/mach-omap2/omap_hwmod.c (c0336b9c)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap_hwmod.c:_wait_softreset_complete
  - arch/arm/mach-omap2/omap_hwmod.c:_wait_softreset_complete
```
```
In drivers/irqchip/irq-renesas-rza1.c (c0820008)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-rza1.c:rza1_irqc_set_type
  - drivers/irqchip/irq-renesas-rza1.c:rza1_irqc_eoi
```
```
In drivers/irqchip/irq-vf610-mscm-ir.c (c0820b28)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/irqchip/irq-vf610-mscm-ir.c:vf610_mscm_ir_enable
```
```
In drivers/bus/ti-sysc.c (c0827060)
Location: arch/arm/include/asm/io.h:75
Inline: True
```
```
In drivers/pinctrl/pinctrl-rza1.c (c083c220)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rza1.c:rza1_set_mux
  - drivers/pinctrl/pinctrl-rza1.c:rza1_set_mux
  - drivers/pinctrl/pinctrl-rza1.c:rza1_set_mux
  - drivers/pinctrl/pinctrl-rza1.c:rza1_set_mux
  - drivers/pinctrl/pinctrl-rza1.c:rza1_set_mux
  - drivers/pinctrl/pinctrl-rza1.c:rza1_set_mux
  - drivers/pinctrl/pinctrl-rza1.c:rza1_set_mux
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_set
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_get
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_output
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_output
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_output
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_output
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_input
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_input
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_input
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_get_direction
  - drivers/pinctrl/pinctrl-rza1.c:rza1_pin_reset
  - drivers/pinctrl/pinctrl-rza1.c:rza1_pin_reset
  - drivers/pinctrl/pinctrl-rza1.c:rza1_pin_reset
  - drivers/pinctrl/pinctrl-rza1.c:rza1_pin_reset
  - drivers/pinctrl/pinctrl-rza1.c:rza1_pin_reset
```
```
In drivers/pinctrl/pinctrl-rza2.c (c083c540)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rza2.c:rza2_set_mux
  - drivers/pinctrl/pinctrl-rza2.c:rza2_chip_get_direction
  - drivers/pinctrl/pinctrl-rza2.c:rza2_pin_to_gpio
```
```
In drivers/pinctrl/pinctrl-single.c (c083e3c0)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_readw
```
```
In drivers/pinctrl/sh-pfc/core.c (c08535f0)
Location: arch/arm/include/asm/io.h:75
Inline: True
```
```
In drivers/gpio/gpio-mmio.c (c0867ff0)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_read16be
  - drivers/gpio/gpio-mmio.c:bgpio_read16
```
```
In drivers/gpio/gpio-htc-egpio.c (c0869060)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/gpio/gpio-htc-egpio.c:egpio_write_cache
  - drivers/gpio/gpio-htc-egpio.c:egpio_get
  - drivers/gpio/gpio-htc-egpio.c:egpio_handler
```
```
In drivers/gpio/gpio-omap.c (c086dae0)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/gpio/gpio-omap.c:omap_gpio_probe
```
```
In drivers/pci/access.c (c0877068)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/pci-sysfs.c (c0889eac)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/pci/rom.c (c088a438)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (c0895164)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/pci/controller/pcie-cadence-ep.c (c08a7818)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_get_msi
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_msi
```
```
In drivers/pci/controller/pci-mvebu.c (c08a94ac)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_rd_conf
```
```
In drivers/pci/controller/pci-v3-semi.c (c08b0fac)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_irq
```
```
In drivers/pci/controller/pcie-altera.c (c08b1d58)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera.c:s10_rp_read_cfg
  - drivers/pci/controller/pcie-altera.c:s10_altera_pcie_link_up
```
```
In drivers/pci/controller/dwc/pcie-designware.c (c08b6624)
Location: arch/arm/include/asm/io.h:75
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-qcom.c (c08bc190)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_link_up
```
```
In drivers/clk/renesas/clk-rz.c (c157e884)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/clk/renesas/clk-rz.c:rz_cpg_clocks_init
```
```
In drivers/clk/renesas/rcar-usb2-clock-sel.c (c0904a70)
Location: arch/arm/include/asm/io.h:75
Inline: True
```
```
In drivers/clk/ti/adpll.c (c091b5a0)
Location: arch/arm/include/asm/io.h:75
Inline: True
```
```
In drivers/dma/ti/omap-dma.c (c09310f8)
Location: arch/arm/include/asm/io.h:75
Inline: True
```
```
In drivers/virtio/virtio_mmio.c (c094435c)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/virtio/virtio_pci_modern.c (c0944e54)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_config_vector
  - drivers/virtio/virtio_pci_modern.c:vp_get
```
```
In drivers/virtio/virtio_pci_legacy.c (c0946dc8)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_config_vector
```
```
In drivers/tty/serial/8250/8250_port.c (c0984340)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (c098b260)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (c098cd88)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/tty/serial/amba-pl011.c (c15953f8)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_console_setup
  - drivers/tty/serial/amba-pl011.c:pl011_console_setup
  - drivers/tty/serial/amba-pl011.c:pl011_console_setup
  - drivers/tty/serial/amba-pl011.c:pl011_console_setup
  - drivers/tty/serial/amba-pl011.c:pl011_console_setup
  - drivers/tty/serial/amba-pl011.c:pl011_console_write
  - drivers/tty/serial/amba-pl011.c:pl011_console_write
  - drivers/tty/serial/amba-pl011.c:pl011_console_putchar
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_enable_interrupts
  - drivers/tty/serial/amba-pl011.c:pl011_enable_interrupts
  - drivers/tty/serial/amba-pl011.c:pl011_put_poll_char
  - drivers/tty/serial/amba-pl011.c:pl011_get_poll_char
  - drivers/tty/serial/amba-pl011.c:pl011_get_poll_char
  - drivers/tty/serial/amba-pl011.c:pl011_get_poll_char
  - drivers/tty/serial/amba-pl011.c:pl011_get_poll_char
  - drivers/tty/serial/amba-pl011.c:pl011_break_ctl
  - drivers/tty/serial/amba-pl011.c:pl011_set_mctrl
  - drivers/tty/serial/amba-pl011.c:pl011_get_mctrl
  - drivers/tty/serial/amba-pl011.c:pl011_tx_empty
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_tx_char
  - drivers/tty/serial/amba-pl011.c:pl011_start_tx
  - drivers/tty/serial/amba-pl011.c:pl011_fifo_to_tty
  - drivers/tty/serial/amba-pl011.c:pl011_fifo_to_tty
```
```
In drivers/tty/serial/omap-serial.c (c099e67c)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/tty/serial/omap-serial.c:serial_omap_mdr1_errataset
  - drivers/tty/serial/omap-serial.c:serial_omap_mdr1_errataset
  - drivers/tty/serial/omap-serial.c:serial_omap_console_write
  - drivers/tty/serial/omap-serial.c:omap_serial_early_putc
  - drivers/tty/serial/omap-serial.c:serial_omap_poll_get_char
  - drivers/tty/serial/omap-serial.c:serial_omap_poll_get_char
  - drivers/tty/serial/omap-serial.c:serial_omap_pm
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_shutdown
  - drivers/tty/serial/omap-serial.c:serial_omap_shutdown
  - drivers/tty/serial/omap-serial.c:serial_omap_shutdown
  - drivers/tty/serial/omap-serial.c:serial_omap_set_mctrl
  - drivers/tty/serial/omap-serial.c:serial_omap_set_mctrl
  - drivers/tty/serial/omap-serial.c:serial_omap_tx_empty
  - drivers/tty/serial/omap-serial.c:serial_omap_irq
  - drivers/tty/serial/omap-serial.c:serial_omap_irq
  - drivers/tty/serial/omap-serial.c:serial_omap_irq
  - drivers/tty/serial/omap-serial.c:serial_omap_irq
  - drivers/tty/serial/omap-serial.c:check_modem_status
```
```
In drivers/char/tpm/tpm_tis.c (c09baef0)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read16
```
```
In drivers/base/regmap/regmap-mmio.c (c0a01cf4)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16be
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16le
```
```
In drivers/mfd/asic3.c (c0a0eebc)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/mfd/asic3.c:asic3_clk_disable
  - drivers/mfd/asic3.c:asic3_clk_enable
  - drivers/mfd/asic3.c:asic3_gpio_set
  - drivers/mfd/asic3.c:asic3_gpio_get
  - drivers/mfd/asic3.c:asic3_gpio_direction
  - drivers/mfd/asic3.c:asic3_gpio_irq_type
  - drivers/mfd/asic3.c:asic3_gpio_irq_type
  - drivers/mfd/asic3.c:asic3_gpio_irq_type
  - drivers/mfd/asic3.c:asic3_unmask_irq
  - drivers/mfd/asic3.c:asic3_unmask_gpio_irq
  - drivers/mfd/asic3.c:asic3_mask_irq
  - drivers/mfd/asic3.c:asic3_mask_gpio_irq
  - drivers/mfd/asic3.c:asic3_irq_demux
  - drivers/mfd/asic3.c:asic3_irq_demux
  - drivers/mfd/asic3.c:asic3_irq_demux
  - drivers/mfd/asic3.c:asic3_set_register
```
```
In drivers/mfd/tc6393xb.c (c0a132d8)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/mfd/tc6393xb.c:tc6393xb_suspend
  - drivers/mfd/tc6393xb.c:tc6393xb_fb_disable
  - drivers/mfd/tc6393xb.c:tc6393xb_fb_enable
  - drivers/mfd/tc6393xb.c:tc6393xb_ohci_disable
  - drivers/mfd/tc6393xb.c:tc6393xb_ohci_enable
```
```
In drivers/ata/libata-sff.c (c0a7ffd8)
Location: arch/arm/include/asm/io.h:75
Inline: True
```
```
In drivers/mtd/maps/map_funcs.c (c0a995fc)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/mtd/maps/map_funcs.c:simple_map_read
```
```
In drivers/mtd/nand/raw/nand_legacy.c (c0aa2ff0)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/nand_legacy.c:nand_read_byte16
```
```
In drivers/usb/host/pci-quirks.c (c0b22918)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (c0b3b294)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_get_frame_number
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_get_frame_number
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:start_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_generic_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_generic_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_generic_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_generic_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_generic_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_generic_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:any_ports_active
  - drivers/usb/host/uhci-hcd.c:any_ports_active
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
```
```
In drivers/usb/musb/musb_core.c (c0b659f4)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/usb/musb/musb_core.c:musb_default_read_fifo
  - drivers/usb/musb/musb_core.c:musb_default_readw
```
```
In drivers/rtc/rtc-s3c.c (c0b8df7c)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/rtc/rtc-s3c.c:s3c6410_rtc_restore_tick_cnt
  - drivers/rtc/rtc-s3c.c:s3c6410_rtc_save_tick_cnt
  - drivers/rtc/rtc-s3c.c:s3c6410_rtc_enable_tick
  - drivers/rtc/rtc-s3c.c:s3c2416_rtc_select_tick_clk
  - drivers/rtc/rtc-s3c.c:s3c_rtc_probe
  - drivers/rtc/rtc-s3c.c:s3c6410_rtc_disable
  - drivers/rtc/rtc-s3c.c:s3c24xx_rtc_disable
  - drivers/rtc/rtc-s3c.c:s3c24xx_rtc_enable
  - drivers/rtc/rtc-s3c.c:s3c24xx_rtc_enable
  - drivers/rtc/rtc-s3c.c:s3c24xx_rtc_enable
  - drivers/rtc/rtc-s3c.c:s3c24xx_rtc_enable
```
```
In drivers/i2c/busses/i2c-designware-common.c (c0b980c4)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
```
```
In drivers/i2c/busses/i2c-omap.c (c0b9c764)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_runtime_suspend
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_runtime_suspend
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_runtime_suspend
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_unprepare_recovery
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_prepare_recovery
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_set_scl
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_get_sda
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_get_scl
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_isr
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_isr
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_common
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_common
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_wait_for_bb
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_recover_bus
```
```
In drivers/thermal/samsung/exynos_tmu.c (c0bbda80)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/thermal/samsung/exynos_tmu.c:exynos7_tmu_read
```
```
In drivers/mmc/host/sdhci.c (c0c24e20)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci.c:sdhci_setup_host
  - drivers/mmc/host/sdhci.c:__sdhci_read_caps
  - drivers/mmc/host/sdhci.c:sdhci_irq
  - drivers/mmc/host/sdhci.c:sdhci_irq
  - drivers/mmc/host/sdhci.c:sdhci_irq
  - drivers/mmc/host/sdhci.c:sdhci_irq
  - drivers/mmc/host/sdhci.c:sdhci_execute_tuning
  - drivers/mmc/host/sdhci.c:sdhci_reset_tuning
  - drivers/mmc/host/sdhci.c:sdhci_start_tuning
  - drivers/mmc/host/sdhci.c:sdhci_start_signal_voltage_switch
  - drivers/mmc/host/sdhci.c:sdhci_start_signal_voltage_switch
  - drivers/mmc/host/sdhci.c:sdhci_start_signal_voltage_switch
  - drivers/mmc/host/sdhci.c:sdhci_set_ios
  - drivers/mmc/host/sdhci.c:sdhci_set_ios
  - drivers/mmc/host/sdhci.c:sdhci_set_ios
  - drivers/mmc/host/sdhci.c:sdhci_set_uhs_signaling
  - drivers/mmc/host/sdhci.c:sdhci_enable_clk
  - drivers/mmc/host/sdhci.c:sdhci_enable_clk
  - drivers/mmc/host/sdhci.c:sdhci_calc_clk
  - drivers/mmc/host/sdhci.c:sdhci_get_preset_value
  - drivers/mmc/host/sdhci.c:sdhci_get_preset_value
  - drivers/mmc/host/sdhci.c:sdhci_get_preset_value
  - drivers/mmc/host/sdhci.c:sdhci_get_preset_value
  - drivers/mmc/host/sdhci.c:sdhci_get_preset_value
  - drivers/mmc/host/sdhci.c:sdhci_get_preset_value
  - drivers/mmc/host/sdhci.c:sdhci_send_command
  - drivers/mmc/host/sdhci.c:sdhci_send_command
  - drivers/mmc/host/sdhci.c:sdhci_prepare_data
  - drivers/mmc/host/sdhci.c:sdhci_prepare_data
  - drivers/mmc/host/sdhci.c:sdhci_do_enable_v4_mode
  - drivers/mmc/host/sdhci.c:sdhci_dumpregs
  - drivers/mmc/host/sdhci.c:sdhci_dumpregs
  - drivers/mmc/host/sdhci.c:sdhci_dumpregs
  - drivers/mmc/host/sdhci.c:sdhci_dumpregs
  - drivers/mmc/host/sdhci.c:sdhci_dumpregs
  - drivers/mmc/host/sdhci.c:sdhci_dumpregs
  - drivers/mmc/host/sdhci.c:sdhci_dumpregs
  - drivers/mmc/host/sdhci.c:sdhci_dumpregs
  - drivers/mmc/host/sdhci.c:sdhci_dumpregs
```
```
In drivers/mmc/host/sdhci-esdhc-imx.c (c0c2e218)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_cqe_enable
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_readw_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_readw_le
```
```
In drivers/firmware/arm_scmi/perf.c (c0c39748)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db
```
```
In drivers/clocksource/sh_cmt.c (c0c44090)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_read16
```
```
In drivers/clocksource/sh_mtu2.c (0)
Location: arch/arm/include/asm/io.h:75
Inline: True
```
```
In drivers/clocksource/sh_tmu.c (c0c46328)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_set_next
```
```
In drivers/clocksource/mmio.c (c0c47188)
Location: arch/arm/include/asm/io.h:75
Inline: True
Inline callers:
  - drivers/clocksource/mmio.c:clocksource_mmio_readw_down
  - drivers/clocksource/mmio.c:clocksource_mmio_readw_up
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
In arch/powerpc/sysdev/xive/native.c (c0000000000bfae0)
Location: arch/powerpc/include/asm/io.h:306
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/native.c:xive_native_update_pending
```
```
In arch/powerpc/sysdev/xive/spapr.c (c0000000000c0e7c)
Location: arch/powerpc/include/asm/io.h:306
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/spapr.c:xive_spapr_update_pending
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
In drivers/pinctrl/pinctrl-single.c (ffffffe00049fcf8)
Location: arch/riscv/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_readw
```
```
In drivers/gpio/gpio-mmio.c (ffffffe0004ad3a6)
Location: arch/riscv/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_read16be
  - drivers/gpio/gpio-mmio.c:bgpio_read16
```
```
In drivers/pci/access.c (ffffffe0004b38f8)
Location: arch/riscv/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffe0004c36a6)
Location: arch/riscv/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (ffffffe0004cc768)
Location: arch/riscv/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffe0004dc3de)
Location: arch/riscv/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_get_cur_bus_speed
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
```
In drivers/pci/controller/pcie-cadence-ep.c (ffffffe0004e581a)
Location: arch/riscv/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_get_msi
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_msi
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffe0004e7628)
Location: arch/riscv/include/asm/io.h:68
Inline: True
```
```
In drivers/virtio/virtio_mmio.c (ffffffe00051cc20)
Location: arch/riscv/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffe00051d59e)
Location: arch/riscv/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_config_vector
  - drivers/virtio/virtio_pci_modern.c:vp_get
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffe00051f59a)
Location: arch/riscv/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_config_vector
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffe000550ec0)
Location: arch/riscv/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffe0005573fa)
Location: arch/riscv/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffe000559748)
Location: arch/riscv/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/char/tpm/tpm_tis.c (ffffffe00057394a)
Location: arch/riscv/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read16
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffe00059bf26)
Location: arch/riscv/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16be
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16le
```
```
In drivers/ata/libata-sff.c (ffffffe00060ca84)
Location: arch/riscv/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_data_xfer32
  - drivers/ata/libata-sff.c:ata_sff_data_xfer
  - drivers/ata/libata-sff.c:ata_sff_data_xfer
```
```
In drivers/usb/host/pci-quirks.c (ffffffe00066cf58)
Location: arch/riscv/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffe000682242)
Location: arch/riscv/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_get_frame_number
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:any_ports_active
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffe0006bda14)
Location: arch/riscv/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_readl
  - drivers/i2c/busses/i2c-designware-common.c:dw_readl
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
