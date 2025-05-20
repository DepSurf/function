# Function: <code>out_le16</code>

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
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/pci-common.c (c00000000006daec)
Location: arch/powerpc/include/asm/io.h:159
Inline: True
Inline callers:
  - arch/powerpc/kernel/pci-common.c:pci_legacy_write
```
```
In lib/iomap.c (c0000000007e53c0)
Location: arch/powerpc/include/asm/io.h:159
Inline: True
```
```
In drivers/pinctrl/pinctrl-single.c (c00000000083261c)
Location: arch/powerpc/include/asm/io.h:159
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_writew
```
```
In drivers/gpio/gpio-mmio.c (c000000000847cdc)
Location: arch/powerpc/include/asm/io.h:159
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_write16
```
```
In drivers/pci/access.c (c000000000852664)
Location: arch/powerpc/include/asm/io.h:159
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/pci-sysfs.c (c00000000086b660)
Location: arch/powerpc/include/asm/io.h:159
Inline: True
```
```
In drivers/pci/quirks.c (c000000000879210)
Location: arch/powerpc/include/asm/io.h:159
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/pci/controller/pcie-cadence-host.c (c00000000088eab8)
Location: arch/powerpc/include/asm/io.h:159
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
```
In drivers/pci/controller/pcie-cadence-ep.c (c00000000088fc64)
Location: arch/powerpc/include/asm/io.h:159
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_msi
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
```
```
In drivers/pci/controller/pci-ftpci100.c (c0000000008912dc)
Location: arch/powerpc/include/asm/io.h:159
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_write_config
```
```
In drivers/video/console/vgacon.c (c00000000089c1c4)
Location: arch/powerpc/include/asm/io.h:159
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
```
```
In drivers/virtio/virtio_mmio.c (c0000000008d11c0)
Location: arch/powerpc/include/asm/io.h:159
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (c00000000092c6a0)
Location: arch/powerpc/include/asm/io.h:159
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (c00000000093825c)
Location: arch/powerpc/include/asm/io.h:159
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (c00000000093a4cc)
Location: arch/powerpc/include/asm/io.h:159
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/base/regmap/regmap-mmio.c (c0000000009c0bd4)
Location: arch/powerpc/include/asm/io.h:159
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16le
```
```
In drivers/usb/host/pci-quirks.c (c000000000b18b64)
Location: arch/powerpc/include/asm/io.h:159
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (c000000000b3e6b0)
Location: arch/powerpc/include/asm/io.h:159
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:start_rh
  - drivers/usb/host/uhci-hcd.c:start_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:configure_hc
  - drivers/usb/host/uhci-hcd.c:finish_reset
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
In drivers/i2c/busses/i2c-designware-common.c (c000000000b9bb48)
Location: arch/powerpc/include/asm/io.h:159
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_writel
  - drivers/i2c/busses/i2c-designware-common.c:dw_writel
```
</details>
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
