# Function: <code>writeb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8140279e)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In drivers/pci/access.c (ffffffff8142dd87)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/quirks.c (ffffffff81444612)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/video/console/vgacon.c (ffffffff8145df04)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff814769bf)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
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
```
```
In drivers/acpi/osl.c (ffffffff8147a20e)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff814c0586)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81505b29)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8150ae77)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81fa75da)
Location: arch/x86/include/asm/io.h:64
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8150e7ac)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_stop_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_break_ctl
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff8156b378)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_gather_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8144a44e)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In drivers/pci/access.c (ffffffff81479118)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/quirks.c (ffffffff814904e5)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/host/pcie-designware.c (ffffffff814a5174)
Location: arch/x86/include/asm/io.h:64
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff814ac126)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff814c5729)
Location: arch/x86/include/asm/io.h:64
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
```
```
In drivers/acpi/osl.c (ffffffff814c87c5)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81510be0)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff815572d9)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8155da07)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81fd3a33)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81561e3f)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_break_ctl
  - drivers/tty/serial/sccnxp.c:sccnxp_stop_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff815bfaee)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write8
```
```
In drivers/mailbox/pcc.c (ffffffff817507ef)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_send_data
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
In lib/iomap.c (ffffffff81468e0e)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In drivers/pci/access.c (ffffffff8149a528)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/quirks.c (ffffffff814b1d35)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/host/pcie-designware.c (ffffffff814c73e4)
Location: arch/x86/include/asm/io.h:64
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff814ce556)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff814e7719)
Location: arch/x86/include/asm/io.h:64
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
```
```
In drivers/acpi/osl.c (ffffffff814ea709)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8153cd50)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81583ad9)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8158a1d7)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff820113f3)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8158e5af)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_break_ctl
  - drivers/tty/serial/sccnxp.c:sccnxp_stop_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff815eef2e)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write8
```
```
In drivers/mailbox/pcc.c (ffffffff8177c156)
Location: arch/x86/include/asm/io.h:64
Inline: True
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
In lib/iomap.c (ffffffff8146e4d9)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In drivers/pci/access.c (ffffffff814a40b4)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/quirks.c (ffffffff814bc171)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/dwc/pcie-designware.c (ffffffff814d2f08)
Location: arch/x86/include/asm/io.h:64
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff814d95bd)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff814f3359)
Location: arch/x86/include/asm/io.h:64
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
```
```
In drivers/acpi/osl.c (ffffffff814f6574)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81550bdf)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81597ee9)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8159eac3)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff820f2ed5)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/tty/serial/sccnxp.c (ffffffff815a263e)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_break_ctl
  - drivers/tty/serial/sccnxp.c:sccnxp_stop_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff8160316e)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write8
```
```
In drivers/mailbox/pcc.c (ffffffff8179aca6)
Location: arch/x86/include/asm/io.h:64
Inline: True
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
In lib/iomap.c (ffffffff8149a80e)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In drivers/pci/access.c (ffffffff814e2e3a)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/quirks.c (ffffffff814fc5e1)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/dwc/pcie-designware.c (ffffffff815133a8)
Location: arch/x86/include/asm/io.h:65
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff81519822)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff81533a19)
Location: arch/x86/include/asm/io.h:65
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
```
```
In drivers/acpi/osl.c (ffffffff81536d24)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff815b43df)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff815fcb29)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81603fb3)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81604af8)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8160843d)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_break_ctl
  - drivers/tty/serial/sccnxp.c:sccnxp_stop_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff8166b53e)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write8
```
```
In drivers/mailbox/pcc.c (ffffffff8181108c)
Location: arch/x86/include/asm/io.h:65
Inline: True
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
In lib/iomap.c (ffffffff814cfaad)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In drivers/pci/access.c (ffffffff81512ca5)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/quirks.c (ffffffff8152d2c5)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81548788)
Location: arch/x86/include/asm/io.h:65
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff81550258)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff815694bb)
Location: arch/x86/include/asm/io.h:65
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
```
```
In drivers/acpi/osl.c (ffffffff8156c932)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff815ec7cd)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81635f09)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8163d372)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff8163dd88)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81641a66)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_break_ctl
  - drivers/tty/serial/sccnxp.c:sccnxp_stop_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff816a6f1b)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write8
```
```
In drivers/mailbox/pcc.c (ffffffff8185aed6)
Location: arch/x86/include/asm/io.h:65
Inline: True
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
In lib/iomap.c (ffffffff814e43bd)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In drivers/pci/access.c (ffffffff81528505)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/quirks.c (ffffffff81544115)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8155ee48)
Location: arch/x86/include/asm/io.h:65
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff815675a8)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff81580f1b)
Location: arch/x86/include/asm/io.h:65
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
```
```
In drivers/acpi/osl.c (ffffffff81584562)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8160739d)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816541b9)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8165b5f2)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff8165bfa7)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8165e7cb)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_write
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff816c7a5b)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write8
```
```
In drivers/mailbox/pcc.c (ffffffff8187a336)
Location: arch/x86/include/asm/io.h:65
Inline: True
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
In lib/iomap.c (ffffffff81510bbe)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In drivers/pci/access.c (ffffffff81557795)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/quirks.c (ffffffff81576c11)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8158f4a7)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
```
```
In drivers/video/console/vgacon.c (ffffffff81597df6)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff815b158f)
Location: arch/x86/include/asm/io.h:65
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
In drivers/acpi/osl.c (ffffffff815b5168)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8163b1be)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81688c09)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81690d57)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff816916c4)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81693db8)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_write
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81702d0b)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write8
```
```
In drivers/mailbox/pcc.c (ffffffff818bf997)
Location: arch/x86/include/asm/io.h:65
Inline: True
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106d4ce)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat_disable
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat_enable
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat
```
```
In lib/iomap.c (ffffffff8153162e)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In drivers/pci/access.c (ffffffff81578dc5)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/quirks.c (ffffffff81598324)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815b1217)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
```
```
In drivers/video/console/vgacon.c (ffffffff815b9196)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff815d250f)
Location: arch/x86/include/asm/io.h:65
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
In drivers/acpi/osl.c (ffffffff815d6398)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8165d68e)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816ab299)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816b1950)
Location: arch/x86/include/asm/io.h:65
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
In drivers/tty/serial/8250/8250_early.c (ffffffff816b41b4)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816b6958)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_write
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff8172705b)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write8
```
```
In drivers/mailbox/pcc.c (ffffffff818f24b7)
Location: arch/x86/include/asm/io.h:65
Inline: True
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8107451e)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat_disable
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat_enable
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat
```
```
In lib/iomap.c (ffffffff81595b69)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In drivers/pci/access.c (ffffffff8161ddd5)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/quirks.c (ffffffff81646bee)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8165aa47)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
```
```
In drivers/video/console/vgacon.c (ffffffff81663256)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff8167c2bc)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:init_asiliant
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
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
In drivers/acpi/osl.c (ffffffff81680098)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8170ca15)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175df39)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81764ed0)
Location: arch/x86/include/asm/io.h:65
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
In drivers/tty/serial/8250/8250_early.c (ffffffff81767a54)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8176be62)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_break_ctl
  - drivers/tty/serial/sccnxp.c:sccnxp_stop_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff817e362b)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write8
```
```
In drivers/mailbox/pcc.c (ffffffff819c7f27)
Location: arch/x86/include/asm/io.h:65
Inline: True
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
In lib/iomap.c (ffffffff815b15f9)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In drivers/pci/access.c (ffffffff816445f5)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/quirks.c (ffffffff81bfa7bf)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8167b017)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
```
```
In drivers/video/console/vgacon.c (ffffffff81683ed6)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff8169c29c)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:init_asiliant
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
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
In drivers/acpi/osl.c (ffffffff8169eb85)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81729838)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81778db9)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8177fdd0)
Location: arch/x86/include/asm/io.h:65
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
In drivers/tty/serial/8250/8250_early.c (ffffffff817827b4)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81786a42)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_break_ctl
  - drivers/tty/serial/sccnxp.c:sccnxp_stop_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff817f829b)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write8
```
```
In drivers/mailbox/pcc.c (ffffffff819c7df7)
Location: arch/x86/include/asm/io.h:65
Inline: True
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
In lib/iomap.c (ffffffff815bc409)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In drivers/pci/access.c (ffffffff81627376)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/quirks.c (ffffffff81bec61a)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8165da7c)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
```
```
In drivers/video/console/vgacon.c (ffffffff81667e53)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff8167efaf)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
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
In drivers/acpi/osl.c (ffffffff81681837)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8170e0e5)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175c7d9)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81763700)
Location: arch/x86/include/asm/io.h:65
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
In drivers/tty/serial/8250/8250_early.c (ffffffff817660b4)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8176a3a2)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_break_ctl
  - drivers/tty/serial/sccnxp.c:sccnxp_stop_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff817dca2b)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write8
```
```
In drivers/mailbox/pcc.c (ffffffff819acd37)
Location: arch/x86/include/asm/io.h:65
Inline: True
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
In lib/iomap.c (ffffffff81623259)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In drivers/pci/access.c (ffffffff81696c46)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/quirks.c (ffffffff81ce71e5)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff816d04ec)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
```
```
In drivers/video/console/vgacon.c (ffffffff816db0bf)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff816f3f60)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
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
In drivers/acpi/osl.c (ffffffff816f6927)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8178a855)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff817e09c3)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff817e7ae0)
Location: arch/x86/include/asm/io.h:65
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
In drivers/tty/serial/8250/8250_early.c (ffffffff817eaa74)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/tty/serial/sccnxp.c (ffffffff817eeff6)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_disable_irq
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff8186842b)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write8
```
```
In drivers/mailbox/pcc.c (ffffffff81a5b244)
Location: arch/x86/include/asm/io.h:65
Inline: True
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
In lib/iomap.c (ffffffff816f3049)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In arch/x86/lib/iomem.c (ffffffff81775c82)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - arch/x86/lib/iomem.c:memset_io
```
```
In drivers/gpio/gpio-mmio.c (ffffffff817b18b5)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_write8
```
```
In drivers/pci/access.c (ffffffff817b7c20)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/quirks.c (ffffffff81eae2c1)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff817f9381)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
```
```
In drivers/video/console/vgacon.c (ffffffff81805438)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff8182079d)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
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
In drivers/acpi/osl.c (ffffffff8182377e)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff818c20cd)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8191f7b3)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff819275f0)
Location: arch/x86/include/asm/io.h:67
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
In drivers/tty/serial/8250/8250_early.c (ffffffff8192a853)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8192f126)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_disable_irq
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff819b0e6b)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write8
```
```
In drivers/mailbox/pcc.c (ffffffff81bcaefd)
Location: arch/x86/include/asm/io.h:67
Inline: True
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
In lib/iomap.c (ffffffff817e4f39)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In arch/x86/lib/iomem.c (ffffffff818a69b2)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - arch/x86/lib/iomem.c:memset_io
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff818b02ca)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_set_mux
```
```
In drivers/gpio/gpio-mmio.c (ffffffff818cb6b5)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_write8
```
```
In drivers/pci/access.c (ffffffff818d2470)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/quirks.c (ffffffff81906fcd)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff819256c9)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
```
```
In drivers/video/console/vgacon.c (ffffffff81933ce8)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff8194fa78)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
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
In drivers/acpi/osl.c (ffffffff819549de)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81a120fd)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a7bd03)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81a84330)
Location: arch/x86/include/asm/io.h:67
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
In drivers/tty/serial/8250/8250_early.c (ffffffff81a87ca3)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81a8d496)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_disable_irq
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81b24dbb)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write8
```
```
In drivers/mailbox/pcc.c (ffffffff81d746bd)
Location: arch/x86/include/asm/io.h:67
Inline: True
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
In lib/iomap.c (ffffffff81824f79)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In arch/x86/lib/iomem.c (ffffffff818e9822)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - arch/x86/lib/iomem.c:memset_io
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff818f32aa)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_set_mux
```
```
In drivers/gpio/gpio-mmio.c (ffffffff8190e725)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_write8
```
```
In drivers/pci/access.c (ffffffff81915470)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/quirks.c (ffffffff8194a61d)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81969479)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
```
```
In drivers/video/console/vgacon.c (ffffffff819781a7)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff81995f68)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
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
In drivers/acpi/osl.c (ffffffff8199adde)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81a5b149)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81ac78c3)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81acfb20)
Location: arch/x86/include/asm/io.h:67
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
In drivers/tty/serial/8250/8250_early.c (ffffffff81ad2ffa)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81ad8c16)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_disable_irq
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81b74ebb)
Location: arch/x86/include/asm/io.h:67
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write8
```
```
In drivers/mailbox/pcc.c (ffffffff81de25f8)
Location: arch/x86/include/asm/io.h:67
Inline: True
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
In lib/iomap.c (ffffffff81876989)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In arch/x86/lib/iomem.c (ffffffff81930cc2)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - arch/x86/lib/iomem.c:memset_io
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8193aada)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_set_mux
```
```
In drivers/gpio/gpio-mmio.c (ffffffff81956495)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_write8
```
```
In drivers/pci/access.c (ffffffff8195d3e0)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/quirks.c (ffffffff819939cd)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff819b1d19)
Location: arch/x86/include/asm/io.h:64
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff819c2247)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff819e05e8)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
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
In drivers/acpi/osl.c (ffffffff819e325e)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81aac5b9)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1a4e3)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_out
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81b22a3a)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81b23980)
Location: arch/x86/include/asm/io.h:64
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
In drivers/tty/serial/sccnxp.c (ffffffff81b2bf06)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_disable_irq
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81bc8d3b)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write8
```
```
In drivers/mailbox/pcc.c (ffffffff81e98658)
Location: arch/x86/include/asm/io.h:64
Inline: True
```
</details>
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
Location: arch/powerpc/include/asm/io-defs.h:10
Inline: True
Inline callers:
  - arch/powerpc/kernel/legacy_serial.c:tsi_serial_out
```
```
In arch/powerpc/kernel/udbg_16550.c (c000000000068980)
Location: arch/powerpc/include/asm/io-defs.h:10
Inline: True
Inline callers:
  - arch/powerpc/kernel/udbg_16550.c:udbg_uart_out_pio
```
```
In arch/powerpc/sysdev/i8259.c (c0000000000b9c20)
Location: arch/powerpc/include/asm/io-defs.h:10
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
In lib/iomap.c (c0000000007e5630)
Location: arch/powerpc/include/asm/io-defs.h:10
Inline: True
```
```
In drivers/pinctrl/pinctrl-single.c (c0000000008325fc)
Location: arch/powerpc/include/asm/io-defs.h:10
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_writeb
```
```
In drivers/gpio/gpio-mmio.c (c000000000847cbc)
Location: arch/powerpc/include/asm/io-defs.h:10
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_write8
```
```
In drivers/pci/access.c (c000000000852694)
Location: arch/powerpc/include/asm/io-defs.h:10
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/pci-sysfs.c (c00000000086b630)
Location: arch/powerpc/include/asm/io-defs.h:10
Inline: True
```
```
In drivers/pci/quirks.c (c00000000087a544)
Location: arch/powerpc/include/asm/io-defs.h:10
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/controller/pcie-cadence-host.c (c00000000088eafc)
Location: arch/powerpc/include/asm/io-defs.h:10
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
```
In drivers/pci/controller/pcie-cadence-ep.c (c00000000088ee70)
Location: arch/powerpc/include/asm/io-defs.h:10
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
```
```
In drivers/pci/controller/pci-ftpci100.c (c0000000008908e4)
Location: arch/powerpc/include/asm/io-defs.h:10
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_write_config
```
```
In drivers/video/console/vgacon.c (c00000000089d86c)
Location: arch/powerpc/include/asm/io-defs.h:10
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
Location: arch/powerpc/include/asm/io-defs.h:10
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
Location: arch/powerpc/include/asm/io-defs.h:10
Inline: True
Inline callers:
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
```
```
In drivers/virtio/virtio_mmio.c (c0000000008d124c)
Location: arch/powerpc/include/asm/io-defs.h:10
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (c0000000009339c0)
Location: arch/powerpc/include/asm/io-defs.h:10
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
Location: arch/powerpc/include/asm/io-defs.h:10
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
Location: arch/powerpc/include/asm/io-defs.h:10
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/tty/serial/sccnxp.c (c00000000093c648)
Location: arch/powerpc/include/asm/io-defs.h:10
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_write
```
```
In drivers/char/mem.c (c000000000942ae4)
Location: arch/powerpc/include/asm/io-defs.h:10
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
```
```
In drivers/base/regmap/regmap-mmio.c (c0000000009c0ba4)
Location: arch/powerpc/include/asm/io-defs.h:10
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write8
```
```
In drivers/ata/libata-sff.c (c000000000a79bc0)
Location: arch/powerpc/include/asm/io-defs.h:10
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (c000000000b19440)
Location: arch/powerpc/include/asm/io-defs.h:10
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (c000000000b378a4)
Location: arch/powerpc/include/asm/io-defs.h:10
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:configure_hc
```
```
In drivers/input/serio/i8042.c (c000000000b70af0)
Location: arch/powerpc/include/asm/io-defs.h:10
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_kbd_write
```
```
In drivers/rtc/rtc-mc146818-lib.c (c000000000b8f578)
Location: arch/powerpc/include/asm/io-defs.h:10
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81529c0e)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In drivers/gpio/gpio-mmio.c (ffffffff815699f5)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_write8
```
```
In drivers/pci/access.c (ffffffff8156d2e5)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/quirks.c (ffffffff8158c1b4)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815a49d7)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
```
```
In drivers/video/console/vgacon.c (ffffffff815ad2e6)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff815c651f)
Location: arch/x86/include/asm/io.h:65
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
In drivers/acpi/osl.c (ffffffff815ca0f8)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8162352e)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81670d09)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816773c0)
Location: arch/x86/include/asm/io.h:65
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
In drivers/tty/serial/8250/8250_early.c (ffffffff81679c14)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8167c3b8)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_write
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff816ece3b)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write8
```
```
In drivers/mailbox/pcc.c (ffffffff818937e7)
Location: arch/x86/include/asm/io.h:65
Inline: True
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
In lib/iomap.c (ffffffff81519eee)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In drivers/pci/access.c (ffffffff8155ba55)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/quirks.c (ffffffff8157acf4)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81593b77)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
```
```
In drivers/video/console/vgacon.c (ffffffff8159c486)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
```
```
In drivers/acpi/osl.c (ffffffff815b3178)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81617b7e)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8164fe09)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816564a0)
Location: arch/x86/include/asm/io.h:65
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
In drivers/tty/serial/8250/8250_early.c (ffffffff81658d04)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8165b4a8)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_write
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff816c747b)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write8
```
```
In drivers/mailbox/pcc.c (ffffffff8184bce7)
Location: arch/x86/include/asm/io.h:65
Inline: True
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
In lib/iomap.c (ffffffff81525c9e)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In drivers/pci/access.c (ffffffff8156cb15)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/quirks.c (ffffffff8158c074)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815a4f67)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
```
```
In drivers/video/console/vgacon.c (ffffffff815ad876)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff815c6aaf)
Location: arch/x86/include/asm/io.h:65
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
In drivers/acpi/osl.c (ffffffff815ca678)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff816514ce)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8169f0d9)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816a5790)
Location: arch/x86/include/asm/io.h:65
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
In drivers/tty/serial/8250/8250_early.c (ffffffff816a7ff4)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816aa798)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_write
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff8171a51b)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write8
```
```
In drivers/mailbox/pcc.c (ffffffff818e72e7)
Location: arch/x86/include/asm/io.h:65
Inline: True
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106eb9e)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat_disable
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat_enable
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat
```
```
In lib/iomap.c (ffffffff8153f61e)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In drivers/pci/access.c (ffffffff81587015)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/quirks.c (ffffffff815a6524)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815bf367)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
```
```
In drivers/video/console/vgacon.c (ffffffff815c7326)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff815e064f)
Location: arch/x86/include/asm/io.h:65
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
In drivers/acpi/osl.c (ffffffff815e451e)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8166bb5e)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816b9599)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816bfbf0)
Location: arch/x86/include/asm/io.h:65
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
In drivers/tty/serial/8250/8250_early.c (ffffffff816c2454)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816c4bf8)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_write
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff8173587b)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write8
```
```
In drivers/mailbox/pcc.c (ffffffff81903f67)
Location: arch/x86/include/asm/io.h:65
Inline: True
```
</details>
</li>
</ul>

## Differences
