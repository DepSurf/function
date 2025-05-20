# Function: <code>in_8</code>

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
In arch/powerpc/kernel/eeh.c (c000000000043a34)
Location: arch/powerpc/include/asm/io.h:138
Inline: True
Inline callers:
  - arch/powerpc/kernel/eeh.c:eeh_dev_break_write
```
```
In arch/powerpc/kernel/legacy_serial.c (c0000000000686f4)
Location: arch/powerpc/include/asm/io.h:138
Inline: True
```
```
In arch/powerpc/kernel/udbg_16550.c (c0000000000689cc)
Location: arch/powerpc/include/asm/io.h:138
Inline: True
Inline callers:
  - arch/powerpc/kernel/udbg_16550.c:udbg_uart_in_mmio
  - arch/powerpc/kernel/udbg_16550.c:udbg_uart_in_pio
```
```
In arch/powerpc/kernel/pci-common.c (c00000000006d9a4)
Location: arch/powerpc/include/asm/io.h:138
Inline: True
Inline callers:
  - arch/powerpc/kernel/pci-common.c:pci_legacy_read
```
```
In arch/powerpc/sysdev/i8259.c (c0000000000b9300)
Location: arch/powerpc/include/asm/io.h:138
Inline: True
Inline callers:
  - arch/powerpc/sysdev/i8259.c:i8259_mask_and_ack_irq
  - arch/powerpc/sysdev/i8259.c:i8259_mask_and_ack_irq
  - arch/powerpc/sysdev/i8259.c:i8259_irq
  - arch/powerpc/sysdev/i8259.c:i8259_irq
  - arch/powerpc/sysdev/i8259.c:i8259_irq
  - arch/powerpc/sysdev/i8259.c:i8259_irq
```
```
In kernel/debug/kdb/kdb_keyboard.c (c000000000282f50)
Location: arch/powerpc/include/asm/io.h:138
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
In lib/iomap.c (c0000000007e5b00)
Location: arch/powerpc/include/asm/io.h:138
Inline: True
```
```
In lib/check_signature.c (c0000000007e8108)
Location: arch/powerpc/include/asm/io.h:138
Inline: True
Inline callers:
  - lib/check_signature.c:check_signature
```
```
In drivers/pinctrl/pinctrl-single.c (c000000000833c18)
Location: arch/powerpc/include/asm/io.h:138
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_readb
```
```
In drivers/gpio/gpio-mmio.c (c000000000849068)
Location: arch/powerpc/include/asm/io.h:138
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_read8
```
```
In drivers/pci/access.c (c000000000853a20)
Location: arch/powerpc/include/asm/io.h:138
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/pci-sysfs.c (c00000000086b860)
Location: arch/powerpc/include/asm/io.h:138
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/pci/rom.c (c00000000086c830)
Location: arch/powerpc/include/asm/io.h:138
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (c00000000087a48c)
Location: arch/powerpc/include/asm/io.h:138
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/video/console/vgacon.c (c00000000089d200)
Location: arch/powerpc/include/asm/io.h:138
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/asiliantfb.c (c0000000008c23c8)
Location: arch/powerpc/include/asm/io.h:138
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/virtio/virtio_mmio.c (c0000000008d273c)
Location: arch/powerpc/include/asm/io.h:138
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (c000000000933a20)
Location: arch/powerpc/include/asm/io.h:138
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
In drivers/tty/serial/8250/8250_pci.c (c000000000938540)
Location: arch/powerpc/include/asm/io.h:138
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
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
```
```
In drivers/tty/serial/8250/8250_early.c (c00000000093a850)
Location: arch/powerpc/include/asm/io.h:138
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/tty/serial/sccnxp.c (c00000000093c310)
Location: arch/powerpc/include/asm/io.h:138
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_read
```
```
In drivers/char/mem.c (c000000000942880)
Location: arch/powerpc/include/asm/io.h:138
Inline: True
Inline callers:
  - drivers/char/mem.c:read_port
```
```
In drivers/base/regmap/regmap-mmio.c (c0000000009c10b0)
Location: arch/powerpc/include/asm/io.h:138
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read8
```
```
In drivers/ata/libata-sff.c (c000000000a79c60)
Location: arch/powerpc/include/asm/io.h:138
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (c000000000b196a0)
Location: arch/powerpc/include/asm/io.h:138
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/ehci-hcd.c (c000000000b2911c)
Location: arch/powerpc/include/asm/io.h:138
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
```
In drivers/usb/host/uhci-hcd.c (c000000000b3d980)
Location: arch/powerpc/include/asm/io.h:138
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
```
```
In drivers/input/serio/i8042.c (c000000000b708cc)
Location: arch/powerpc/include/asm/io.h:138
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_wait_write
```
```
In drivers/rtc/rtc-mc146818-lib.c (c000000000b8f5a4)
Location: arch/powerpc/include/asm/io.h:138
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
