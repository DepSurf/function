# Function: <code>out_8</code>

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
In arch/powerpc/kernel/legacy_serial.c (c000000000068678)
Location: arch/powerpc/include/asm/io.h:139
Inline: True
Inline callers:
  - arch/powerpc/kernel/legacy_serial.c:tsi_serial_out
```
```
In arch/powerpc/kernel/udbg_16550.c (c000000000068a1c)
Location: arch/powerpc/include/asm/io.h:139
Inline: True
Inline callers:
  - arch/powerpc/kernel/udbg_16550.c:udbg_uart_out_mmio
  - arch/powerpc/kernel/udbg_16550.c:udbg_uart_out_pio
```
```
In arch/powerpc/kernel/pci-common.c (c00000000006daa8)
Location: arch/powerpc/include/asm/io.h:139
Inline: True
Inline callers:
  - arch/powerpc/kernel/pci-common.c:pci_legacy_write
```
```
In arch/powerpc/sysdev/fsl_lbc.c (c0000000000b80c0)
Location: arch/powerpc/include/asm/io.h:139
Inline: True
Inline callers:
  - arch/powerpc/sysdev/fsl_lbc.c:fsl_upm_run_pattern
```
```
In arch/powerpc/sysdev/i8259.c (c0000000000b9c20)
Location: arch/powerpc/include/asm/io.h:139
Inline: True
Inline callers:
  - arch/powerpc/sysdev/i8259.c:i8259_init
  - arch/powerpc/sysdev/i8259.c:i8259_init
  - arch/powerpc/sysdev/i8259.c:i8259_init
  - arch/powerpc/sysdev/i8259.c:i8259_init
  - arch/powerpc/sysdev/i8259.c:i8259_init
  - arch/powerpc/sysdev/i8259.c:i8259_init
  - arch/powerpc/sysdev/i8259.c:i8259_init
  - arch/powerpc/sysdev/i8259.c:i8259_init
  - arch/powerpc/sysdev/i8259.c:i8259_init
  - arch/powerpc/sysdev/i8259.c:i8259_init
  - arch/powerpc/sysdev/i8259.c:i8259_init
  - arch/powerpc/sysdev/i8259.c:i8259_init
  - arch/powerpc/sysdev/i8259.c:i8259_init
  - arch/powerpc/sysdev/i8259.c:i8259_init
  - arch/powerpc/sysdev/i8259.c:i8259_mask_and_ack_irq
  - arch/powerpc/sysdev/i8259.c:i8259_mask_and_ack_irq
  - arch/powerpc/sysdev/i8259.c:i8259_mask_and_ack_irq
  - arch/powerpc/sysdev/i8259.c:i8259_mask_and_ack_irq
  - arch/powerpc/sysdev/i8259.c:i8259_irq
  - arch/powerpc/sysdev/i8259.c:i8259_irq
  - arch/powerpc/sysdev/i8259.c:i8259_irq
```
```
In arch/powerpc/sysdev/xics/icp-native.c (c0000000000bac74)
Location: arch/powerpc/include/asm/io.h:139
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xics/icp-native.c:icp_native_ipi_action
  - arch/powerpc/sysdev/xics/icp-native.c:xics_wake_cpu
  - arch/powerpc/sysdev/xics/icp-native.c:icp_native_flush_interrupt
  - arch/powerpc/sysdev/xics/icp-native.c:icp_native_cause_ipi
  - arch/powerpc/sysdev/xics/icp-native.c:icp_native_teardown_cpu
  - arch/powerpc/sysdev/xics/icp-native.c:icp_native_set_cpu_priority
```
```
In arch/powerpc/sysdev/xive/common.c (c0000000000bef0c)
Location: arch/powerpc/include/asm/io.h:139
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/common.c:xive_teardown_cpu
  - arch/powerpc/sysdev/xive/common.c:xive_smp_disable_cpu
  - arch/powerpc/sysdev/xive/common.c:xive_smp_disable_cpu
  - arch/powerpc/sysdev/xive/common.c:xive_setup_cpu
  - arch/powerpc/sysdev/xive/common.c:xive_scan_interrupts
```
```
In lib/iomap.c (c0000000007e5630)
Location: arch/powerpc/include/asm/io.h:139
Inline: True
```
```
In drivers/pinctrl/pinctrl-single.c (c0000000008325fc)
Location: arch/powerpc/include/asm/io.h:139
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_writeb
```
```
In drivers/gpio/gpio-mmio.c (c000000000847cbc)
Location: arch/powerpc/include/asm/io.h:139
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_write8
```
```
In drivers/pci/access.c (c000000000852694)
Location: arch/powerpc/include/asm/io.h:139
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/pci-sysfs.c (c00000000086b630)
Location: arch/powerpc/include/asm/io.h:139
Inline: True
```
```
In drivers/pci/quirks.c (c00000000087a544)
Location: arch/powerpc/include/asm/io.h:139
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/controller/pcie-cadence-host.c (c00000000088eafc)
Location: arch/powerpc/include/asm/io.h:139
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
```
In drivers/pci/controller/pcie-cadence-ep.c (c00000000088ee70)
Location: arch/powerpc/include/asm/io.h:139
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
```
```
In drivers/pci/controller/pci-ftpci100.c (c0000000008908e4)
Location: arch/powerpc/include/asm/io.h:139
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_write_config
```
```
In drivers/video/console/vgacon.c (c00000000089d86c)
Location: arch/powerpc/include/asm/io.h:139
Inline: True
Inline callers:
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
In drivers/video/fbdev/asiliantfb.c (c0000000008c1f9c)
Location: arch/powerpc/include/asm/io.h:139
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
In drivers/video/fbdev/offb.c (c0000000008c45f0)
Location: arch/powerpc/include/asm/io.h:139
Inline: True
Inline callers:
  - drivers/video/fbdev/offb.c:offb_blank
  - drivers/video/fbdev/offb.c:offb_blank
  - drivers/video/fbdev/offb.c:offb_blank
  - drivers/video/fbdev/offb.c:offb_blank
  - drivers/video/fbdev/offb.c:offb_blank
  - drivers/video/fbdev/offb.c:offb_blank
  - drivers/video/fbdev/offb.c:offb_setcolreg
  - drivers/video/fbdev/offb.c:offb_setcolreg
  - drivers/video/fbdev/offb.c:offb_setcolreg
  - drivers/video/fbdev/offb.c:offb_setcolreg
  - drivers/video/fbdev/offb.c:offb_setcolreg
  - drivers/video/fbdev/offb.c:offb_setcolreg
  - drivers/video/fbdev/offb.c:offb_setcolreg
  - drivers/video/fbdev/offb.c:offb_setcolreg
```
```
In drivers/virtio/virtio_mmio.c (c0000000008d124c)
Location: arch/powerpc/include/asm/io.h:139
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (c0000000009339c0)
Location: arch/powerpc/include/asm/io.h:139
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
In drivers/tty/serial/8250/8250_pci.c (c0000000009383c8)
Location: arch/powerpc/include/asm/io.h:139
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
In drivers/tty/serial/8250/8250_early.c (c00000000093a5c0)
Location: arch/powerpc/include/asm/io.h:139
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/tty/serial/sccnxp.c (c00000000093c648)
Location: arch/powerpc/include/asm/io.h:139
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_write
```
```
In drivers/char/mem.c (c000000000942ae4)
Location: arch/powerpc/include/asm/io.h:139
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
```
```
In drivers/base/regmap/regmap-mmio.c (c0000000009c0ba4)
Location: arch/powerpc/include/asm/io.h:139
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write8
```
```
In drivers/ata/libata-sff.c (c000000000a79bc0)
Location: arch/powerpc/include/asm/io.h:139
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (c000000000b19440)
Location: arch/powerpc/include/asm/io.h:139
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (c000000000b378a4)
Location: arch/powerpc/include/asm/io.h:139
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:configure_hc
```
```
In drivers/input/serio/i8042.c (c000000000b70af0)
Location: arch/powerpc/include/asm/io.h:139
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_kbd_write
```
```
In drivers/rtc/rtc-mc146818-lib.c (c000000000b8f578)
Location: arch/powerpc/include/asm/io.h:139
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
