# Function: <code>eeh_readw</code>

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
In lib/iomap.c (c0000000007e54e0)
Location: arch/powerpc/include/asm/eeh.h:391
Inline: True
```
```
In drivers/pinctrl/pinctrl-single.c (c000000000833b78)
Location: arch/powerpc/include/asm/eeh.h:391
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_readw
```
```
In drivers/gpio/gpio-mmio.c (c000000000848fc8)
Location: arch/powerpc/include/asm/eeh.h:391
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_read16
```
```
In drivers/pci/access.c (c0000000008539d0)
Location: arch/powerpc/include/asm/eeh.h:391
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/pci-sysfs.c (c00000000086b8d0)
Location: arch/powerpc/include/asm/eeh.h:391
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/pci/rom.c (c00000000086c7bc)
Location: arch/powerpc/include/asm/eeh.h:391
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (c000000000879170)
Location: arch/powerpc/include/asm/eeh.h:391
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/pci/controller/pcie-cadence-ep.c (c00000000088fee0)
Location: arch/powerpc/include/asm/eeh.h:391
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_get_msi
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_msi
```
```
In drivers/virtio/virtio_mmio.c (c0000000008d2638)
Location: arch/powerpc/include/asm/eeh.h:391
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (c00000000092d6bc)
Location: arch/powerpc/include/asm/eeh.h:391
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (c000000000938234)
Location: arch/powerpc/include/asm/eeh.h:391
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (c00000000093a658)
Location: arch/powerpc/include/asm/eeh.h:391
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/base/regmap/regmap-mmio.c (c0000000009c1000)
Location: arch/powerpc/include/asm/eeh.h:391
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16le
```
```
In drivers/usb/host/pci-quirks.c (c000000000b18e50)
Location: arch/powerpc/include/asm/eeh.h:391
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (c000000000b39fec)
Location: arch/powerpc/include/asm/eeh.h:391
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
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
```
```
In drivers/i2c/busses/i2c-designware-common.c (c000000000b9b978)
Location: arch/powerpc/include/asm/eeh.h:391
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_readl
  - drivers/i2c/busses/i2c-designware-common.c:dw_readl
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
