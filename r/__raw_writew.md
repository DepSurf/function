# Function: <code>__raw_writew</code>

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
In lib/logic_pio.c (ffff80001063e558)
Location: arch/arm64/include/asm/io.h:31
Inline: True
```
```
In drivers/pinctrl/pinctrl-single.c (ffff80001069b6c0)
Location: arch/arm64/include/asm/io.h:31
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_writew
```
```
In drivers/pinctrl/sh-pfc/core.c (ffff8000106afca4)
Location: arch/arm64/include/asm/io.h:31
Inline: True
```
```
In drivers/gpio/gpio-mmio.c (ffff8000106ccde8)
Location: arch/arm64/include/asm/io.h:31
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_write16be
  - drivers/gpio/gpio-mmio.c:bgpio_write16
```
```
In drivers/pci/access.c (ffff8000106da468)
Location: arch/arm64/include/asm/io.h:31
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffff80001070fb88)
Location: arch/arm64/include/asm/io.h:31
Inline: True
```
```
In drivers/pci/controller/pcie-cadence-host.c (ffff80001071da94)
Location: arch/arm64/include/asm/io.h:31
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
```
In drivers/pci/controller/pcie-cadence-ep.c (ffff80001071e798)
Location: arch/arm64/include/asm/io.h:31
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_msi
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
```
```
In drivers/pci/controller/pci-ftpci100.c (ffff80001071f694)
Location: arch/arm64/include/asm/io.h:31
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_write_config
```
```
In drivers/pci/controller/pcie-altera.c (ffff800010726b90)
Location: arch/arm64/include/asm/io.h:31
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera.c:s10_rp_write_cfg
```
```
In drivers/pci/controller/pcie-rockchip-ep.c (0)
Location: arch/arm64/include/asm/io.h:31
Inline: True
```
```
In drivers/pci/controller/pcie-mediatek.c (ffff80001072b700)
Location: arch/arm64/include/asm/io.h:31
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
```
```
In drivers/pci/controller/pcie-mobiveil.c (0)
Location: arch/arm64/include/asm/io.h:31
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffff80001072ceb8)
Location: arch/arm64/include/asm/io.h:31
Inline: True
```
```
In drivers/pci/controller/dwc/pci-keystone.c (ffff80001147a378)
Location: arch/arm64/include/asm/io.h:31
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_host_init
```
```
In drivers/acpi/osl.c (ffff800010763dcc)
Location: arch/arm64/include/asm/io.h:31
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/acpi/cppc_acpi.c (ffff8000107aa954)
Location: arch/arm64/include/asm/io.h:31
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/clk/renesas/rcar-usb2-clock-sel.c (ffff8000107eb590)
Location: arch/arm64/include/asm/io.h:31
Inline: True
Inline callers:
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_suspend
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:usb2_clock_sel_disable
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:usb2_clock_sel_enable_extal_only
```
```
In drivers/virtio/virtio_mmio.c (ffff800010825d38)
Location: arch/arm64/include/asm/io.h:31
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/virtio/virtio_pci_modern.c (ffff800010827480)
Location: arch/arm64/include/asm/io.h:31
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_config_vector
  - drivers/virtio/virtio_pci_modern.c:vp_set
```
```
In drivers/virtio/virtio_pci_common.c (ffff8000108285ec)
Location: arch/arm64/include/asm/io.h:31
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_notify
```
```
In drivers/virtio/virtio_pci_legacy.c (ffff800010829038)
Location: arch/arm64/include/asm/io.h:31
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_config_vector
```
```
In drivers/tty/serial/8250/8250_port.c (ffff800010885bf8)
Location: arch/arm64/include/asm/io.h:31
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffff80001088fc14)
Location: arch/arm64/include/asm/io.h:31
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffff80001089062c)
Location: arch/arm64/include/asm/io.h:31
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/tty/serial/amba-pl011.c (ffff8000108944c0)
Location: arch/arm64/include/asm/io.h:31
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_register_port
  - drivers/tty/serial/amba-pl011.c:pl011_register_port
  - drivers/tty/serial/amba-pl011.c:pl011_console_write
  - drivers/tty/serial/amba-pl011.c:pl011_console_write
  - drivers/tty/serial/amba-pl011.c:pl011_console_putchar
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_disable_interrupts
  - drivers/tty/serial/amba-pl011.c:pl011_disable_interrupts
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown_channel
  - drivers/tty/serial/amba-pl011.c:pl011_enable_interrupts
  - drivers/tty/serial/amba-pl011.c:pl011_enable_interrupts
  - drivers/tty/serial/amba-pl011.c:pl011_allocate_irq
  - drivers/tty/serial/amba-pl011.c:pl011_put_poll_char
  - drivers/tty/serial/amba-pl011.c:pl011_break_ctl
  - drivers/tty/serial/amba-pl011.c:pl011_set_mctrl
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_tx_chars
  - drivers/tty/serial/amba-pl011.c:pl011_tx_chars
  - drivers/tty/serial/amba-pl011.c:pl011_tx_chars
  - drivers/tty/serial/amba-pl011.c:pl011_tx_char
  - drivers/tty/serial/amba-pl011.c:pl011_stop_rx
  - drivers/tty/serial/amba-pl011.c:pl011_stop_rx
  - drivers/tty/serial/amba-pl011.c:pl011_start_tx
  - drivers/tty/serial/amba-pl011.c:pl011_start_tx
  - drivers/tty/serial/amba-pl011.c:pl011_start_tx
  - drivers/tty/serial/amba-pl011.c:pl011_start_tx
  - drivers/tty/serial/amba-pl011.c:pl011_stop_tx
  - drivers/tty/serial/amba-pl011.c:pl011_stop_tx
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_poll
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_poll
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_callback
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_chars
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_trigger_dma
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_trigger_dma
  - drivers/tty/serial/amba-pl011.c:pl011_dma_tx_refill
  - drivers/tty/serial/amba-pl011.c:pl011_dma_tx_callback
```
```
In drivers/base/regmap/regmap-mmio.c (ffff80001091c638)
Location: arch/arm64/include/asm/io.h:31
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16be
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16le
```
```
In drivers/ata/libata-sff.c (ffff8000109b061c)
Location: arch/arm64/include/asm/io.h:31
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_data_xfer32
  - drivers/ata/libata-sff.c:ata_sff_data_xfer
  - drivers/ata/libata-sff.c:ata_sff_data_xfer
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fb57c)
Location: arch/arm64/include/asm/io.h:31
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
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_set_multicast_list
  - drivers/net/ethernet/smsc/smc91x.c:smc_set_multicast_list
  - drivers/net/ethernet/smsc/smc91x.c:smc_set_multicast_list
  - drivers/net/ethernet/smsc/smc91x.c:smc_set_multicast_list
  - drivers/net/ethernet/smsc/smc91x.c:smc_set_multicast_list
  - drivers/net/ethernet/smsc/smc91x.c:smc_set_multicast_list
  - drivers/net/ethernet/smsc/smc91x.c:smc_set_multicast_list
  - drivers/net/ethernet/smsc/smc91x.c:smc_set_multicast_list
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
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_10bt_check_media
  - drivers/net/ethernet/smsc/smc91x.c:smc_10bt_check_media
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_configure
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_configure
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_configure
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_check_media
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_check_media
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_fixed
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_fixed
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_fixed
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_write
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_write
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_write
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_read
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_read
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_read
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_read
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_read
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_read
  - drivers/net/ethernet/smsc/smc91x.c:smc_mii_out
  - drivers/net/ethernet/smsc/smc91x.c:smc_mii_out
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
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
  - drivers/net/ethernet/smsc/smc91x.c:smc_rcv
  - drivers/net/ethernet/smsc/smc91x.c:smc_rcv
  - drivers/net/ethernet/smsc/smc91x.c:smc_rcv
  - drivers/net/ethernet/smsc/smc91x.c:smc_rcv
  - drivers/net/ethernet/smsc/smc91x.c:smc_shutdown
  - drivers/net/ethernet/smsc/smc91x.c:smc_shutdown
  - drivers/net/ethernet/smsc/smc91x.c:smc_shutdown
  - drivers/net/ethernet/smsc/smc91x.c:smc_shutdown
  - drivers/net/ethernet/smsc/smc91x.c:smc_shutdown
  - drivers/net/ethernet/smsc/smc91x.c:smc_shutdown
  - drivers/net/ethernet/smsc/smc91x.c:smc_shutdown
  - drivers/net/ethernet/smsc/smc91x.c:smc_enable
  - drivers/net/ethernet/smsc/smc91x.c:smc_enable
  - drivers/net/ethernet/smsc/smc91x.c:smc_enable
  - drivers/net/ethernet/smsc/smc91x.c:smc_enable
  - drivers/net/ethernet/smsc/smc91x.c:smc_enable
  - drivers/net/ethernet/smsc/smc91x.c:smc_enable
  - drivers/net/ethernet/smsc/smc91x.c:smc_enable
  - drivers/net/ethernet/smsc/smc91x.c:smc_enable
  - drivers/net/ethernet/smsc/smc91x.c:smc_enable
  - drivers/net/ethernet/smsc/smc91x.c:smc_reset
  - drivers/net/ethernet/smsc/smc91x.c:smc_reset
  - drivers/net/ethernet/smsc/smc91x.c:smc_reset
  - drivers/net/ethernet/smsc/smc91x.c:smc_reset
  - drivers/net/ethernet/smsc/smc91x.c:smc_reset
  - drivers/net/ethernet/smsc/smc91x.c:smc_reset
  - drivers/net/ethernet/smsc/smc91x.c:smc_reset
  - drivers/net/ethernet/smsc/smc91x.c:smc_reset
  - drivers/net/ethernet/smsc/smc91x.c:smc_reset
  - drivers/net/ethernet/smsc/smc91x.c:smc_reset
  - drivers/net/ethernet/smsc/smc91x.c:smc_reset
  - drivers/net/ethernet/smsc/smc91x.c:smc_reset
  - drivers/net/ethernet/smsc/smc91x.c:smc_reset
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffff800010ab9360)
Location: arch/arm64/include/asm/io.h:31
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
```
```
In drivers/i2c/busses/i2c-omap.c (ffff800010abb5f4)
Location: arch/arm64/include/asm/io.h:31
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_runtime_suspend
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_runtime_suspend
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_runtime_suspend
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_remove
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_unprepare_recovery
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_prepare_recovery
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_set_scl
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
  - drivers/i2c/busses/i2c-omap.c:__omap_i2c_init
  - drivers/i2c/busses/i2c-omap.c:__omap_i2c_init
  - drivers/i2c/busses/i2c-omap.c:__omap_i2c_init
  - drivers/i2c/busses/i2c-omap.c:__omap_i2c_init
  - drivers/i2c/busses/i2c-omap.c:__omap_i2c_init
  - drivers/i2c/busses/i2c-omap.c:__omap_i2c_init
  - drivers/i2c/busses/i2c-omap.c:__omap_i2c_init
```
```
In drivers/firmware/arm_scmi/perf.c (ffff800010b57f3c)
Location: arch/arm64/include/asm/io.h:31
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db
```
```
In drivers/clocksource/sh_cmt.c (ffff800010b63d20)
Location: arch/arm64/include/asm/io.h:31
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_write16
```
```
In drivers/clocksource/sh_tmu.c (ffff800010b653f8)
Location: arch/arm64/include/asm/io.h:31
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_interrupt
  - drivers/clocksource/sh_tmu.c:sh_tmu_interrupt
  - drivers/clocksource/sh_tmu.c:sh_tmu_set_next
  - drivers/clocksource/sh_tmu.c:__sh_tmu_disable
  - drivers/clocksource/sh_tmu.c:__sh_tmu_enable
```
```
In drivers/mailbox/pcc.c (ffff800010b7b7c4)
Location: arch/arm64/include/asm/io.h:31
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
In arch/arm/mach-imx/system.c (c0331d74)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - arch/arm/mach-imx/system.c:mxc_restart
  - arch/arm/mach-imx/system.c:mxc_restart
  - arch/arm/mach-imx/system.c:mxc_restart
```
```
In arch/arm/mach-omap2/omap_hwmod.c (c03380f4)
Location: arch/arm/include/asm/io.h:68
Inline: True
```
```
In drivers/irqchip/irq-renesas-rza1.c (c0820020)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-rza1.c:rza1_irqc_set_type
  - drivers/irqchip/irq-renesas-rza1.c:rza1_irqc_eoi
```
```
In drivers/irqchip/irq-crossbar.c (c0820948)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/irqchip/irq-crossbar.c:crossbar_writew
```
```
In drivers/irqchip/irq-vf610-mscm-ir.c (c0820aec)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/irqchip/irq-vf610-mscm-ir.c:vf610_mscm_ir_disable
  - drivers/irqchip/irq-vf610-mscm-ir.c:vf610_mscm_ir_enable
```
```
In drivers/bus/ti-sysc.c (c0826e9c)
Location: arch/arm/include/asm/io.h:68
Inline: True
```
```
In drivers/pinctrl/pinctrl-rza1.c (c083c244)
Location: arch/arm/include/asm/io.h:68
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
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_output
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_output
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_output
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_output
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_input
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_input
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_input
  - drivers/pinctrl/pinctrl-rza1.c:rza1_pin_reset
  - drivers/pinctrl/pinctrl-rza1.c:rza1_pin_reset
  - drivers/pinctrl/pinctrl-rza1.c:rza1_pin_reset
  - drivers/pinctrl/pinctrl-rza1.c:rza1_pin_reset
  - drivers/pinctrl/pinctrl-rza1.c:rza1_pin_reset
```
```
In drivers/pinctrl/pinctrl-rza2.c (c083c564)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rza2.c:rza2_set_mux
  - drivers/pinctrl/pinctrl-rza2.c:rza2_pin_to_gpio
```
```
In drivers/pinctrl/pinctrl-single.c (c083f210)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_writew
```
```
In drivers/pinctrl/sh-pfc/core.c (c0853660)
Location: arch/arm/include/asm/io.h:68
Inline: True
```
```
In drivers/gpio/gpio-mmio.c (c0867fd4)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_write16be
  - drivers/gpio/gpio-mmio.c:bgpio_write16
```
```
In drivers/gpio/gpio-htc-egpio.c (c0869030)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/gpio/gpio-htc-egpio.c:egpio_write_cache
  - drivers/gpio/gpio-htc-egpio.c:egpio_set
  - drivers/gpio/gpio-htc-egpio.c:egpio_handler
```
```
In drivers/pci/access.c (c08773dc)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/pci-sysfs.c (c0889b38)
Location: arch/arm/include/asm/io.h:68
Inline: True
```
```
In drivers/pci/quirks.c (c08939d4)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/pci/controller/pcie-cadence-host.c (c08a6ac4)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
```
In drivers/pci/controller/pcie-cadence-ep.c (c08a6ed4)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_msi
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
```
```
In drivers/pci/controller/pci-ftpci100.c (c08a82a8)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_write_config
```
```
In drivers/pci/controller/pci-mvebu.c (c08a9344)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_wr_conf
```
```
In drivers/pci/controller/pci-v3-semi.c (c08b0fec)
Location: arch/arm/include/asm/io.h:68
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
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_irq
  - drivers/pci/controller/pci-v3-semi.c:v3_unmap_bus
  - drivers/pci/controller/pci-v3-semi.c:v3_map_bus
```
```
In drivers/pci/controller/pcie-altera.c (c08b1f8c)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera.c:s10_rp_write_cfg
```
```
In drivers/pci/controller/pcie-rockchip-ep.c (0)
Location: arch/arm/include/asm/io.h:68
Inline: True
```
```
In drivers/pci/controller/pcie-mediatek.c (c08b58dc)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
```
```
In drivers/pci/controller/dwc/pcie-designware.c (c08b66a8)
Location: arch/arm/include/asm/io.h:68
Inline: True
```
```
In drivers/clk/renesas/clk-rz.c (c157e87c)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/clk/renesas/clk-rz.c:rz_cpg_clocks_init
```
```
In drivers/clk/renesas/rcar-usb2-clock-sel.c (c0904bb4)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_suspend
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:usb2_clock_sel_disable
```
```
In drivers/dma/ti/omap-dma.c (c0930830)
Location: arch/arm/include/asm/io.h:68
Inline: True
```
```
In drivers/dma/ti/dma-crossbar.c (c093353c)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/dma/ti/dma-crossbar.c:ti_dra7_xbar_probe
  - drivers/dma/ti/dma-crossbar.c:ti_dra7_xbar_probe
  - drivers/dma/ti/dma-crossbar.c:ti_dra7_xbar_route_allocate
  - drivers/dma/ti/dma-crossbar.c:ti_dra7_xbar_free
```
```
In drivers/virtio/virtio_mmio.c (c0944474)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/virtio/virtio_pci_modern.c (c0944e0c)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_config_vector
  - drivers/virtio/virtio_pci_modern.c:vp_set
```
```
In drivers/virtio/virtio_pci_common.c (c0946334)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_notify
```
```
In drivers/virtio/virtio_pci_legacy.c (c0946cbc)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_config_vector
```
```
In drivers/tty/serial/8250/8250_port.c (c0984db0)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (c098b274)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (c098ce84)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/tty/serial/amba-pl011.c (c0990570)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_register_port
  - drivers/tty/serial/amba-pl011.c:pl011_register_port
  - drivers/tty/serial/amba-pl011.c:pl011_console_write
  - drivers/tty/serial/amba-pl011.c:pl011_console_write
  - drivers/tty/serial/amba-pl011.c:pl011_console_putchar
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_disable_interrupts
  - drivers/tty/serial/amba-pl011.c:pl011_disable_interrupts
  - drivers/tty/serial/amba-pl011.c:pl011_enable_interrupts
  - drivers/tty/serial/amba-pl011.c:pl011_enable_interrupts
  - drivers/tty/serial/amba-pl011.c:pl011_allocate_irq
  - drivers/tty/serial/amba-pl011.c:pl011_put_poll_char
  - drivers/tty/serial/amba-pl011.c:pl011_get_poll_char
  - drivers/tty/serial/amba-pl011.c:pl011_get_poll_char
  - drivers/tty/serial/amba-pl011.c:pl011_break_ctl
  - drivers/tty/serial/amba-pl011.c:pl011_set_mctrl
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_tx_chars
  - drivers/tty/serial/amba-pl011.c:pl011_tx_chars
  - drivers/tty/serial/amba-pl011.c:pl011_tx_chars
  - drivers/tty/serial/amba-pl011.c:pl011_tx_char
  - drivers/tty/serial/amba-pl011.c:pl011_stop_rx
  - drivers/tty/serial/amba-pl011.c:pl011_stop_rx
  - drivers/tty/serial/amba-pl011.c:pl011_start_tx
  - drivers/tty/serial/amba-pl011.c:pl011_start_tx
  - drivers/tty/serial/amba-pl011.c:pl011_start_tx
  - drivers/tty/serial/amba-pl011.c:pl011_start_tx
  - drivers/tty/serial/amba-pl011.c:pl011_stop_tx
  - drivers/tty/serial/amba-pl011.c:pl011_stop_tx
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_poll
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_poll
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_callback
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_chars
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_trigger_dma
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_trigger_dma
  - drivers/tty/serial/amba-pl011.c:pl011_dma_tx_refill
  - drivers/tty/serial/amba-pl011.c:pl011_dma_tx_callback
```
```
In drivers/tty/serial/omap-serial.c (c099e758)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/tty/serial/omap-serial.c:serial_omap_restore_context
  - drivers/tty/serial/omap-serial.c:serial_omap_restore_context
  - drivers/tty/serial/omap-serial.c:serial_omap_restore_context
  - drivers/tty/serial/omap-serial.c:serial_omap_restore_context
  - drivers/tty/serial/omap-serial.c:serial_omap_restore_context
  - drivers/tty/serial/omap-serial.c:serial_omap_restore_context
  - drivers/tty/serial/omap-serial.c:serial_omap_restore_context
  - drivers/tty/serial/omap-serial.c:serial_omap_restore_context
  - drivers/tty/serial/omap-serial.c:serial_omap_restore_context
  - drivers/tty/serial/omap-serial.c:serial_omap_restore_context
  - drivers/tty/serial/omap-serial.c:serial_omap_restore_context
  - drivers/tty/serial/omap-serial.c:serial_omap_restore_context
  - drivers/tty/serial/omap-serial.c:serial_omap_restore_context
  - drivers/tty/serial/omap-serial.c:serial_omap_restore_context
  - drivers/tty/serial/omap-serial.c:serial_omap_restore_context
  - drivers/tty/serial/omap-serial.c:serial_omap_restore_context
  - drivers/tty/serial/omap-serial.c:serial_omap_restore_context
  - drivers/tty/serial/omap-serial.c:serial_omap_restore_context
  - drivers/tty/serial/omap-serial.c:serial_omap_restore_context
  - drivers/tty/serial/omap-serial.c:serial_omap_mdr1_errataset
  - drivers/tty/serial/omap-serial.c:serial_omap_mdr1_errataset
  - drivers/tty/serial/omap-serial.c:serial_omap_config_rs485
  - drivers/tty/serial/omap-serial.c:serial_omap_config_rs485
  - drivers/tty/serial/omap-serial.c:serial_omap_config_rs485
  - drivers/tty/serial/omap-serial.c:serial_omap_console_write
  - drivers/tty/serial/omap-serial.c:serial_omap_console_write
  - drivers/tty/serial/omap-serial.c:serial_omap_console_putchar
  - drivers/tty/serial/omap-serial.c:omap_serial_early_putc
  - drivers/tty/serial/omap-serial.c:serial_omap_poll_put_char
  - drivers/tty/serial/omap-serial.c:serial_omap_pm
  - drivers/tty/serial/omap-serial.c:serial_omap_pm
  - drivers/tty/serial/omap-serial.c:serial_omap_pm
  - drivers/tty/serial/omap-serial.c:serial_omap_pm
  - drivers/tty/serial/omap-serial.c:serial_omap_pm
  - drivers/tty/serial/omap-serial.c:serial_omap_pm
  - drivers/tty/serial/omap-serial.c:serial_omap_pm
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_shutdown
  - drivers/tty/serial/omap-serial.c:serial_omap_shutdown
  - drivers/tty/serial/omap-serial.c:serial_omap_shutdown
  - drivers/tty/serial/omap-serial.c:serial_omap_shutdown
  - drivers/tty/serial/omap-serial.c:serial_omap_shutdown
  - drivers/tty/serial/omap-serial.c:serial_omap_break_ctl
  - drivers/tty/serial/omap-serial.c:serial_omap_set_mctrl
  - drivers/tty/serial/omap-serial.c:serial_omap_set_mctrl
  - drivers/tty/serial/omap-serial.c:serial_omap_set_mctrl
  - drivers/tty/serial/omap-serial.c:serial_omap_set_mctrl
  - drivers/tty/serial/omap-serial.c:serial_omap_irq
  - drivers/tty/serial/omap-serial.c:serial_omap_irq
  - drivers/tty/serial/omap-serial.c:serial_omap_unthrottle
  - drivers/tty/serial/omap-serial.c:serial_omap_throttle
  - drivers/tty/serial/omap-serial.c:serial_omap_start_tx
  - drivers/tty/serial/omap-serial.c:serial_omap_start_tx
  - drivers/tty/serial/omap-serial.c:serial_omap_stop_rx
  - drivers/tty/serial/omap-serial.c:serial_omap_stop_tx
  - drivers/tty/serial/omap-serial.c:serial_omap_stop_tx
  - drivers/tty/serial/omap-serial.c:serial_omap_stop_tx
  - drivers/tty/serial/omap-serial.c:serial_omap_stop_tx
  - drivers/tty/serial/omap-serial.c:serial_omap_stop_tx
  - drivers/tty/serial/omap-serial.c:serial_omap_enable_ms
```
```
In drivers/base/regmap/regmap-mmio.c (c0a01cd0)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16be
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16le
```
```
In drivers/mfd/asic3.c (c0a0f280)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/mfd/asic3.c:asic3_remove
  - drivers/mfd/asic3.c:asic3_probe
  - drivers/mfd/asic3.c:asic3_probe
  - drivers/mfd/asic3.c:asic3_probe
  - drivers/mfd/asic3.c:asic3_probe
  - drivers/mfd/asic3.c:asic3_probe
  - drivers/mfd/asic3.c:asic3_probe
  - drivers/mfd/asic3.c:asic3_probe
  - drivers/mfd/asic3.c:asic3_probe
  - drivers/mfd/asic3.c:asic3_probe
  - drivers/mfd/asic3.c:asic3_probe
  - drivers/mfd/asic3.c:asic3_mmc_enable
  - drivers/mfd/asic3.c:asic3_clk_disable
  - drivers/mfd/asic3.c:asic3_clk_enable
  - drivers/mfd/asic3.c:asic3_gpio_set
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
  - drivers/mfd/asic3.c:asic3_set_register
```
```
In drivers/mfd/tmio_core.c (c0a0f380)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/mfd/tmio_core.c:tmio_core_mmc_resume
  - drivers/mfd/tmio_core.c:tmio_core_mmc_resume
  - drivers/mfd/tmio_core.c:tmio_core_mmc_resume
  - drivers/mfd/tmio_core.c:tmio_core_mmc_enable
  - drivers/mfd/tmio_core.c:tmio_core_mmc_enable
  - drivers/mfd/tmio_core.c:tmio_core_mmc_enable
```
```
In drivers/mfd/tc6393xb.c (c0a13dbc)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/mfd/tc6393xb.c:tc6393xb_resume
  - drivers/mfd/tc6393xb.c:tc6393xb_resume
  - drivers/mfd/tc6393xb.c:tc6393xb_resume
  - drivers/mfd/tc6393xb.c:tc6393xb_resume
  - drivers/mfd/tc6393xb.c:tc6393xb_probe
  - drivers/mfd/tc6393xb.c:tc6393xb_probe
  - drivers/mfd/tc6393xb.c:tc6393xb_probe
  - drivers/mfd/tc6393xb.c:tc6393xb_probe
  - drivers/mfd/tc6393xb.c:tc6393xb_lcd_mode
  - drivers/mfd/tc6393xb.c:tc6393xb_lcd_mode
  - drivers/mfd/tc6393xb.c:tc6393xb_fb_disable
  - drivers/mfd/tc6393xb.c:tc6393xb_fb_enable
  - drivers/mfd/tc6393xb.c:tc6393xb_ohci_disable
  - drivers/mfd/tc6393xb.c:tc6393xb_ohci_enable
```
```
In drivers/mtd/maps/map_funcs.c (c0a996f4)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/mtd/maps/map_funcs.c:simple_map_write
```
```
In drivers/mtd/nand/raw/omap2.c (c0aa9cc4)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/omap2.c:omap_write_buf_pref
  - drivers/mtd/nand/raw/omap2.c:omap_write_buf16
```
```
In drivers/usb/host/pci-quirks.c (c0b22840)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/ohci-hcd.c (c0b324ec)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:tmio_start_hc
  - drivers/usb/host/ohci-hcd.c:tmio_start_hc
  - drivers/usb/host/ohci-hcd.c:tmio_start_hc
  - drivers/usb/host/ohci-hcd.c:tmio_stop_hc
  - drivers/usb/host/ohci-hcd.c:tmio_stop_hc
  - drivers/usb/host/ohci-hcd.c:tmio_stop_hc
```
```
In drivers/usb/host/uhci-hcd.c (c0b3f460)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:start_rh
  - drivers/usb/host/uhci-hcd.c:start_rh
  - drivers/usb/host/uhci-hcd.c:start_rh
  - drivers/usb/host/uhci-hcd.c:start_rh
  - drivers/usb/host/uhci-hcd.c:start_rh
  - drivers/usb/host/uhci-hcd.c:start_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:configure_hc
  - drivers/usb/host/uhci-hcd.c:configure_hc
  - drivers/usb/host/uhci-hcd.c:uhci_generic_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_generic_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_generic_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_generic_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_generic_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_generic_reset_hc
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:finish_reset
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
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
```
```
In drivers/usb/musb/musb_core.c (c0b658e4)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/usb/musb/musb_core.c:musb_default_write_fifo
  - drivers/usb/musb/musb_core.c:musb_default_writew
```
```
In drivers/rtc/rtc-s3c.c (c0b8df9c)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/rtc/rtc-s3c.c:s3c6410_rtc_restore_tick_cnt
  - drivers/rtc/rtc-s3c.c:s3c2416_rtc_select_tick_clk
  - drivers/rtc/rtc-s3c.c:s3c6410_rtc_disable
  - drivers/rtc/rtc-s3c.c:s3c24xx_rtc_disable
  - drivers/rtc/rtc-s3c.c:s3c24xx_rtc_enable
  - drivers/rtc/rtc-s3c.c:s3c24xx_rtc_enable
  - drivers/rtc/rtc-s3c.c:s3c24xx_rtc_enable
```
```
In drivers/i2c/busses/i2c-designware-common.c (c0b98994)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable
```
```
In drivers/i2c/busses/i2c-omap.c (c0b9c784)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_runtime_suspend
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_runtime_suspend
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_runtime_suspend
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_remove
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_unprepare_recovery
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_prepare_recovery
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_set_scl
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
  - drivers/i2c/busses/i2c-omap.c:__omap_i2c_init
  - drivers/i2c/busses/i2c-omap.c:__omap_i2c_init
  - drivers/i2c/busses/i2c-omap.c:__omap_i2c_init
  - drivers/i2c/busses/i2c-omap.c:__omap_i2c_init
  - drivers/i2c/busses/i2c-omap.c:__omap_i2c_init
  - drivers/i2c/busses/i2c-omap.c:__omap_i2c_init
  - drivers/i2c/busses/i2c-omap.c:__omap_i2c_init
```
```
In drivers/mmc/host/sdhci.c (c0c268d8)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci.c:sdhci_cqe_enable
  - drivers/mmc/host/sdhci.c:sdhci_send_tuning
  - drivers/mmc/host/sdhci.c:sdhci_send_tuning
  - drivers/mmc/host/sdhci.c:sdhci_reset_tuning
  - drivers/mmc/host/sdhci.c:sdhci_start_tuning
  - drivers/mmc/host/sdhci.c:sdhci_start_signal_voltage_switch
  - drivers/mmc/host/sdhci.c:sdhci_start_signal_voltage_switch
  - drivers/mmc/host/sdhci.c:sdhci_set_ios
  - drivers/mmc/host/sdhci.c:sdhci_set_ios
  - drivers/mmc/host/sdhci.c:sdhci_set_ios
  - drivers/mmc/host/sdhci.c:sdhci_set_uhs_signaling
  - drivers/mmc/host/sdhci.c:sdhci_enable_clk
  - drivers/mmc/host/sdhci.c:sdhci_enable_clk
  - drivers/mmc/host/sdhci.c:sdhci_enable_clk
  - drivers/mmc/host/sdhci.c:sdhci_send_command
  - drivers/mmc/host/sdhci.c:sdhci_send_command
  - drivers/mmc/host/sdhci.c:sdhci_send_command
  - drivers/mmc/host/sdhci.c:sdhci_prepare_data
  - drivers/mmc/host/sdhci.c:sdhci_prepare_data
  - drivers/mmc/host/sdhci.c:sdhci_prepare_data
  - drivers/mmc/host/sdhci.c:sdhci_prepare_data
  - drivers/mmc/host/sdhci.c:sdhci_prepare_data
  - drivers/mmc/host/sdhci.c:sdhci_do_enable_v4_mode
```
```
In drivers/mmc/host/sdhci-esdhc-imx.c (c0c2e264)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_cqe_enable
```
```
In drivers/firmware/arm_scmi/perf.c (c0c39770)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db
```
```
In drivers/clocksource/sh_cmt.c (c0c441d8)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_write16
```
```
In drivers/clocksource/sh_mtu2.c (c0c45488)
Location: arch/arm/include/asm/io.h:68
Inline: True
```
```
In drivers/clocksource/sh_tmu.c (c0c45e1c)
Location: arch/arm/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_interrupt
  - drivers/clocksource/sh_tmu.c:sh_tmu_interrupt
  - drivers/clocksource/sh_tmu.c:sh_tmu_set_next
  - drivers/clocksource/sh_tmu.c:__sh_tmu_disable
  - drivers/clocksource/sh_tmu.c:__sh_tmu_enable
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
In drivers/pinctrl/pinctrl-single.c (ffffffe00049fda8)
Location: arch/riscv/include/asm/io.h:39
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_writew
```
```
In drivers/gpio/gpio-mmio.c (ffffffe0004adffe)
Location: arch/riscv/include/asm/io.h:39
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_write16be
  - drivers/gpio/gpio-mmio.c:bgpio_write16
```
```
In drivers/pci/access.c (ffffffe0004b39b4)
Location: arch/riscv/include/asm/io.h:39
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/quirks.c (ffffffe0004cb0c6)
Location: arch/riscv/include/asm/io.h:39
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffe0004dc546)
Location: arch/riscv/include/asm/io.h:39
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
```
In drivers/pci/controller/pcie-cadence-host.c (ffffffe0004e47e2)
Location: arch/riscv/include/asm/io.h:39
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
```
In drivers/pci/controller/pcie-cadence-ep.c (ffffffe0004e4e6a)
Location: arch/riscv/include/asm/io.h:39
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_msi
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
```
```
In drivers/pci/controller/pci-ftpci100.c (ffffffe0004e6514)
Location: arch/riscv/include/asm/io.h:39
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffe0004e76d6)
Location: arch/riscv/include/asm/io.h:39
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffe0004f1b34)
Location: arch/riscv/include/asm/io.h:39
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
```
```
In drivers/virtio/virtio_mmio.c (ffffffe00051ca3a)
Location: arch/riscv/include/asm/io.h:39
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffe00051d54c)
Location: arch/riscv/include/asm/io.h:39
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_config_vector
  - drivers/virtio/virtio_pci_modern.c:vp_set
```
```
In drivers/virtio/virtio_pci_common.c (ffffffe00051ea5c)
Location: arch/riscv/include/asm/io.h:39
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_notify
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffe00051f4a0)
Location: arch/riscv/include/asm/io.h:39
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_config_vector
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffe000550e68)
Location: arch/riscv/include/asm/io.h:39
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffe000557406)
Location: arch/riscv/include/asm/io.h:39
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffe0005598b4)
Location: arch/riscv/include/asm/io.h:39
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffe00059c148)
Location: arch/riscv/include/asm/io.h:39
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16be
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16le
```
```
In drivers/ata/libata-sff.c (ffffffe00060ca1e)
Location: arch/riscv/include/asm/io.h:39
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_data_xfer32
  - drivers/ata/libata-sff.c:ata_sff_data_xfer
  - drivers/ata/libata-sff.c:ata_sff_data_xfer
```
```
In drivers/usb/host/pci-quirks.c (ffffffe00066cea2)
Location: arch/riscv/include/asm/io.h:39
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffe000684824)
Location: arch/riscv/include/asm/io.h:39
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:configure_hc
  - drivers/usb/host/uhci-hcd.c:uhci_hc_died
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffe0006be174)
Location: arch/riscv/include/asm/io.h:39
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
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
