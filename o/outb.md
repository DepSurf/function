# Function: <code>outb</code>

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
In arch/x86/kernel/nmi.c (ffffffff81032771)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In arch/x86/kernel/i8259.c (ffffffff8103332f)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:mask_8259A_irq
  - arch/x86/kernel/i8259.c:mask_8259A_irq
  - arch/x86/kernel/i8259.c:unmask_8259A_irq
  - arch/x86/kernel/i8259.c:unmask_8259A_irq
  - arch/x86/kernel/i8259.c:i8259A_shutdown
  - arch/x86/kernel/i8259.c:i8259A_shutdown
  - arch/x86/kernel/i8259.c:mask_8259A
  - arch/x86/kernel/i8259.c:mask_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:i8259A_resume
  - arch/x86/kernel/i8259.c:i8259A_resume
```
```
In arch/x86/kernel/quirks.c (ffffffff81035601)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff81037f0b)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/rtc.c (ffffffff810387d6)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In arch/x86/kernel/i8237.c (ffffffff8103e488)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81f6e3be)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff81050664)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff81f6f2ee)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81f724a7)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In arch/x86/kernel/early_printk.c (ffffffff81061cf3)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_out
```
```
In lib/iomap.c (ffffffff81402782)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In drivers/pci/pci-sysfs.c (ffffffff8143afab)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_resource_io
```
```
In drivers/pci/quirks.c (ffffffff81445c95)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff8145d6e4)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
```
```
In drivers/video/fbdev/vesafb.c (ffffffff814779bf)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff81479adb)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff814835ce)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff814ff896)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81505a95)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:io_serial_out
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8150b275)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
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
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81fa7601)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In drivers/char/mem.c (ffffffff81511227)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
```
```
In drivers/ata/libata-sff.c (ffffffff815dbeb9)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8163000c)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81649a62)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff81662c9b)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
```
```
In drivers/input/serio/i8042.c (ffffffff81664a14)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_kbd_write
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81677114)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
```
```
In drivers/clocksource/i8253.c (ffffffff816d53a5)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:pit_set_oneshot
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_next_event
```
```
In arch/x86/pci/direct.c (ffffffff816f6a7c)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
```
In arch/x86/pci/fixup.c (ffffffff816f8937)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff816f9068)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_serverworks_get
  - arch/x86/pci/irq.c:pirq_serverworks_set
  - arch/x86/pci/irq.c:pirq_serverworks_set
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:elcr_set_level_irq
```
```
In arch/x86/pci/early.c (ffffffff816fa973)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_byte
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
In arch/x86/kernel/nmi.c (ffffffff810318e9)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In arch/x86/kernel/i8259.c (ffffffff81032913)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A
  - arch/x86/kernel/i8259.c:mask_8259A
  - arch/x86/kernel/i8259.c:mask_8259A
  - arch/x86/kernel/i8259.c:i8259A_shutdown
  - arch/x86/kernel/i8259.c:i8259A_shutdown
  - arch/x86/kernel/i8259.c:i8259A_resume
  - arch/x86/kernel/i8259.c:i8259A_resume
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A_irq
  - arch/x86/kernel/i8259.c:unmask_8259A_irq
  - arch/x86/kernel/i8259.c:mask_8259A_irq
  - arch/x86/kernel/i8259.c:mask_8259A_irq
```
```
In arch/x86/kernel/quirks.c (ffffffff81034801)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff810373ba)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
```
```
In arch/x86/kernel/rtc.c (ffffffff81037a56)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:rtc_cmos_write
  - arch/x86/kernel/rtc.c:rtc_cmos_write
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In arch/x86/kernel/i8237.c (ffffffff8103e2b8)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81f967d1)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff81050815)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff81f97a83)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81f9ac5d)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In arch/x86/kernel/early_printk.c (ffffffff81061b29)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_out
```
```
In arch/x86/lib/kaslr.c (ffffffff8143e013)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
```
In lib/iomap.c (ffffffff8144a435)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In drivers/pci/pci-sysfs.c (ffffffff81488450)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff81491e15)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff814ac233)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff814c5efc)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff814c80a0)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff814d2157)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81558cd1)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:io_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff8155c17c)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8155dd5a)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
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
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81fd3a65)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/char/mem.c (ffffffff815637d0)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
```
```
In drivers/ata/libata-sff.c (ffffffff81635c39)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81690c6c)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816aa4ca)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff816c2ee4)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
```
```
In drivers/input/serio/i8042.c (ffffffff816c4d8b)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_kbd_write
```
```
In drivers/rtc/rtc-cmos.c (ffffffff816d7d86)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In drivers/clocksource/i8253.c (ffffffff81739659)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_oneshot
```
```
In arch/x86/pci/direct.c (ffffffff81fe6288)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_write
```
```
In arch/x86/pci/fixup.c (ffffffff8175d617)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff8175ddf3)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_serverworks_set
  - arch/x86/pci/irq.c:pirq_serverworks_set
  - arch/x86/pci/irq.c:pirq_serverworks_get
  - arch/x86/pci/irq.c:elcr_set_level_irq
```
```
In arch/x86/pci/early.c (ffffffff8175f7f5)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_byte
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
In arch/x86/kernel/nmi.c (ffffffff81031539)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In arch/x86/kernel/i8259.c (ffffffff81032583)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A
  - arch/x86/kernel/i8259.c:mask_8259A
  - arch/x86/kernel/i8259.c:mask_8259A
  - arch/x86/kernel/i8259.c:i8259A_shutdown
  - arch/x86/kernel/i8259.c:i8259A_shutdown
  - arch/x86/kernel/i8259.c:i8259A_resume
  - arch/x86/kernel/i8259.c:i8259A_resume
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A_irq
  - arch/x86/kernel/i8259.c:unmask_8259A_irq
  - arch/x86/kernel/i8259.c:mask_8259A_irq
  - arch/x86/kernel/i8259.c:mask_8259A_irq
```
```
In arch/x86/kernel/quirks.c (ffffffff81034441)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff8103714a)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
```
```
In arch/x86/kernel/rtc.c (ffffffff81037816)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:rtc_cmos_write
  - arch/x86/kernel/rtc.c:rtc_cmos_write
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In arch/x86/kernel/i8237.c (ffffffff8103db68)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81fd1d05)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff81053085)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff81fd2f95)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81fd6124)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In arch/x86/kernel/early_printk.c (ffffffff81064bd9)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_out
```
```
In arch/x86/lib/kaslr.c (ffffffff8145af93)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
```
In lib/iomap.c (ffffffff81468df5)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In drivers/pci/pci-sysfs.c (ffffffff814a9c30)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff814b3685)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff814ce663)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff814e7f53)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff814e9fb0)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff814f4600)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff815854df)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:io_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81588946)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8158a52a)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
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
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff82011425)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/char/mem.c (ffffffff8158ff30)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
```
```
In drivers/ata/libata-sff.c (ffffffff81666cd9)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff816bed1c)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816d860a)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff816f0ea4)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
```
```
In drivers/input/serio/i8042.c (ffffffff816f2dab)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_kbd_write
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81707d86)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In drivers/clocksource/i8253.c (ffffffff8176c889)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_oneshot
```
```
In arch/x86/pci/direct.c (ffffffff82024acc)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_write
```
```
In arch/x86/pci/fixup.c (ffffffff81789b47)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff8178a323)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_serverworks_set
  - arch/x86/pci/irq.c:pirq_serverworks_set
  - arch/x86/pci/irq.c:pirq_serverworks_get
  - arch/x86/pci/irq.c:elcr_set_level_irq
```
```
In arch/x86/pci/early.c (ffffffff8178bd35)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_byte
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
In arch/x86/kernel/nmi.c (ffffffff8102f73a)
Location: arch/x86/include/asm/io.h:340
Inline: True
```
```
In arch/x86/kernel/i8259.c (ffffffff810307c3)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A
  - arch/x86/kernel/i8259.c:mask_8259A
  - arch/x86/kernel/i8259.c:mask_8259A
  - arch/x86/kernel/i8259.c:i8259A_shutdown
  - arch/x86/kernel/i8259.c:i8259A_shutdown
  - arch/x86/kernel/i8259.c:i8259A_resume
  - arch/x86/kernel/i8259.c:i8259A_resume
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A_irq
  - arch/x86/kernel/i8259.c:unmask_8259A_irq
  - arch/x86/kernel/i8259.c:mask_8259A_irq
  - arch/x86/kernel/i8259.c:mask_8259A_irq
```
```
In arch/x86/kernel/quirks.c (ffffffff81032502)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff810351e4)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
```
```
In arch/x86/kernel/rtc.c (ffffffff810358c6)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:rtc_cmos_write
  - arch/x86/kernel/rtc.c:rtc_cmos_write
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In arch/x86/kernel/i8237.c (ffffffff8103bc08)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff820b2903)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff81052b9d)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff820b3bfe)
Location: arch/x86/include/asm/io.h:340
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (ffffffff820b6e91)
Location: arch/x86/include/asm/io.h:340
Inline: True
```
```
In arch/x86/kernel/early_printk.c (ffffffff81063b59)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_out
```
```
In lib/iomap.c (ffffffff8146e4d5)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In drivers/pci/pci-sysfs.c (ffffffff814b3ff6)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_write_resource_io
```
```
In drivers/pci/quirks.c (ffffffff814bdc7a)
Location: arch/x86/include/asm/io.h:340
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff814d94b8)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff814f3b1d)
Location: arch/x86/include/asm/io.h:340
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff814f5c9b)
Location: arch/x86/include/asm/io.h:340
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff8150281b)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8159ace6)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:io_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff8159cdaa)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8159e5bb)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
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
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff820f2eff)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/char/mem.c (ffffffff815a3ff6)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff815bec14)
Location: arch/x86/include/asm/io.h:340
Inline: True
```
```
In drivers/ata/libata-sff.c (ffffffff8167b469)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff816d35da)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816ecafa)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff81706718)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
```
```
In drivers/input/serio/i8042.c (ffffffff817086e0)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_kbd_write
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8171d9dc)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In drivers/clocksource/i8253.c (ffffffff8178ac09)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_oneshot
```
```
In arch/x86/pci/direct.c (ffffffff82107f72)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_write
```
```
In arch/x86/pci/fixup.c (ffffffff817a8cc0)
Location: arch/x86/include/asm/io.h:340
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff817a9463)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_serverworks_set
  - arch/x86/pci/irq.c:pirq_serverworks_set
  - arch/x86/pci/irq.c:pirq_serverworks_get
  - arch/x86/pci/irq.c:elcr_set_level_irq
```
```
In arch/x86/pci/early.c (ffffffff817aacf5)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_byte
```
```
In arch/x86/lib/kaslr.c (ffffffff818fcd33)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In arch/x86/kernel/nmi.c (ffffffff8103173a)
Location: arch/x86/include/asm/io.h:348
Inline: True
```
```
In arch/x86/kernel/i8259.c (ffffffff81032b63)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A
  - arch/x86/kernel/i8259.c:mask_8259A
  - arch/x86/kernel/i8259.c:mask_8259A
  - arch/x86/kernel/i8259.c:i8259A_shutdown
  - arch/x86/kernel/i8259.c:i8259A_shutdown
  - arch/x86/kernel/i8259.c:i8259A_resume
  - arch/x86/kernel/i8259.c:i8259A_resume
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A_irq
  - arch/x86/kernel/i8259.c:unmask_8259A_irq
  - arch/x86/kernel/i8259.c:mask_8259A_irq
  - arch/x86/kernel/i8259.c:mask_8259A_irq
```
```
In arch/x86/kernel/quirks.c (ffffffff81034832)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff81037534)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
```
```
In arch/x86/kernel/rtc.c (ffffffff81037be6)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:rtc_cmos_write
  - arch/x86/kernel/rtc.c:rtc_cmos_write
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In arch/x86/kernel/i8237.c (ffffffff8103e628)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff826b913d)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff8105689a)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff826ba43b)
Location: arch/x86/include/asm/io.h:348
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (ffffffff826bd7af)
Location: arch/x86/include/asm/io.h:348
Inline: True
```
```
In arch/x86/kernel/early_printk.c (ffffffff81067cc9)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_out
```
```
In lib/iomap.c (ffffffff8149a809)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In drivers/pci/pci-sysfs.c (ffffffff814f3802)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_write_resource_io
```
```
In drivers/pci/quirks.c (ffffffff814fe00a)
Location: arch/x86/include/asm/io.h:348
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff815196e8)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815341dd)
Location: arch/x86/include/asm/io.h:348
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff815365db)
Location: arch/x86/include/asm/io.h:348
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff81544c94)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff815f5015)
Location: arch/x86/include/asm/io.h:348
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff815ffecb)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:io_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81602283)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
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
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81603aaa)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
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
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81604af1)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/char/mem.c (ffffffff8160aa16)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81623acb)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
```
```
In drivers/ata/libata-sff.c (ffffffff816e4ad9)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8173fc9a)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817592f0)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff817778d8)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
```
```
In drivers/input/serio/i8042.c (ffffffff817798d0)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_kbd_write
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8178ec5c)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In drivers/clocksource/i8253.c (ffffffff81801259)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_oneshot
```
```
In arch/x86/pci/direct.c (ffffffff827118b8)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_write
```
```
In arch/x86/pci/fixup.c (ffffffff8181ff60)
Location: arch/x86/include/asm/io.h:348
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff81820913)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_serverworks_set
  - arch/x86/pci/irq.c:pirq_serverworks_set
  - arch/x86/pci/irq.c:pirq_serverworks_get
  - arch/x86/pci/irq.c:elcr_set_level_irq
```
```
In arch/x86/pci/early.c (ffffffff818221e5)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_byte
```
```
In arch/x86/lib/kaslr.c (ffffffff819847e3)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In arch/x86/kernel/nmi.c (ffffffff81032d23)
Location: arch/x86/include/asm/io.h:333
Inline: True
```
```
In arch/x86/kernel/i8259.c (ffffffff81033e63)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A
  - arch/x86/kernel/i8259.c:mask_8259A
  - arch/x86/kernel/i8259.c:mask_8259A
  - arch/x86/kernel/i8259.c:i8259A_shutdown
  - arch/x86/kernel/i8259.c:i8259A_shutdown
  - arch/x86/kernel/i8259.c:i8259A_resume
  - arch/x86/kernel/i8259.c:i8259A_resume
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A_irq
  - arch/x86/kernel/i8259.c:unmask_8259A_irq
  - arch/x86/kernel/i8259.c:mask_8259A_irq
  - arch/x86/kernel/i8259.c:mask_8259A_irq
```
```
In arch/x86/kernel/quirks.c (ffffffff8103584a)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff81038590)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
```
```
In arch/x86/kernel/rtc.c (ffffffff81038d15)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:rtc_cmos_write
  - arch/x86/kernel/rtc.c:rtc_cmos_write
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In arch/x86/kernel/i8237.c (ffffffff8103fbe8)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff826e2e7f)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff8105969b)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff826e40a6)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
```
In arch/x86/kernel/apic/vector.c (ffffffff826e6fc9)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
```
```
In arch/x86/kernel/early_printk.c (ffffffff8106a900)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_out
```
```
In lib/iomap.c (ffffffff814cfabb)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In drivers/pci/pci-sysfs.c (ffffffff81523a0b)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_write_resource_io
```
```
In drivers/pci/quirks.c (ffffffff8152e8d8)
Location: arch/x86/include/asm/io.h:333
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff8155037e)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff81569c7e)
Location: arch/x86/include/asm/io.h:333
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff8156c21e)
Location: arch/x86/include/asm/io.h:333
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff8157adde)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8162dcc6)
Location: arch/x86/include/asm/io.h:333
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816390d3)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:io_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff8163b532)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
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
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8163cea3)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
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
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff8163dd7c)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/char/mem.c (ffffffff81644358)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8165d9ca)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
```
```
In drivers/ata/libata-sff.c (ffffffff81721369)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8178064a)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817993c0)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff817b8608)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
```
```
In drivers/input/serio/i8042.c (ffffffff817ba5a0)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_kbd_write
```
```
In drivers/rtc/rtc-cmos.c (ffffffff817d13cd)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In drivers/clocksource/i8253.c (ffffffff8184ae79)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_oneshot
```
```
In arch/x86/pci/direct.c (ffffffff8273bbac)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_write
```
```
In arch/x86/pci/fixup.c (ffffffff8186a1b0)
Location: arch/x86/include/asm/io.h:333
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff8186aba9)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_serverworks_set
  - arch/x86/pci/irq.c:pirq_serverworks_set
  - arch/x86/pci/irq.c:pirq_serverworks_get
  - arch/x86/pci/irq.c:elcr_set_level_irq
```
```
In arch/x86/pci/early.c (ffffffff8186c4b3)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_byte
```
```
In arch/x86/lib/kaslr.c (ffffffff819e0d18)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In arch/x86/kernel/nmi.c (ffffffff810340a2)
Location: arch/x86/include/asm/io.h:342
Inline: True
```
```
In arch/x86/kernel/i8259.c (ffffffff810351b3)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A
  - arch/x86/kernel/i8259.c:mask_8259A
  - arch/x86/kernel/i8259.c:mask_8259A
  - arch/x86/kernel/i8259.c:i8259A_shutdown
  - arch/x86/kernel/i8259.c:i8259A_shutdown
  - arch/x86/kernel/i8259.c:i8259A_resume
  - arch/x86/kernel/i8259.c:i8259A_resume
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A_irq
  - arch/x86/kernel/i8259.c:unmask_8259A_irq
  - arch/x86/kernel/i8259.c:mask_8259A_irq
  - arch/x86/kernel/i8259.c:mask_8259A_irq
```
```
In arch/x86/kernel/quirks.c (ffffffff81036a2a)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff810390b0)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
```
```
In arch/x86/kernel/rtc.c (ffffffff81039f25)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:rtc_cmos_write
  - arch/x86/kernel/rtc.c:rtc_cmos_write
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In arch/x86/kernel/i8237.c (ffffffff810411e8)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff828997e5)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff8105f3a7)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff8289ab48)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8289db12)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
```
```
In arch/x86/kernel/early_printk.c (ffffffff81070690)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_out
```
```
In lib/iomap.c (ffffffff814e43cb)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In drivers/pci/pci-sysfs.c (ffffffff8153986b)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_write_resource_io
```
```
In drivers/pci/quirks.c (ffffffff81545758)
Location: arch/x86/include/asm/io.h:342
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff815676ce)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815816de)
Location: arch/x86/include/asm/io.h:342
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff81583e4e)
Location: arch/x86/include/asm/io.h:342
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff81592985)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8164c2ad)
Location: arch/x86/include/asm/io.h:342
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816573e5)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:io_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81659762)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
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
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8165b123)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
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
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff8165bfb7)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/char/mem.c (ffffffff81662638)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8167be8a)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
```
```
In drivers/ata/libata-sff.c (ffffffff81743c59)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817a6e6a)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817bfd30)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff817ded08)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
```
```
In drivers/input/serio/i8042.c (ffffffff817e19c0)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_kbd_write
```
```
In drivers/rtc/rtc-cmos.c (ffffffff817f85ad)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In drivers/eisa/eisa-bus.c (ffffffff828edfb5)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
```
```
In drivers/clocksource/i8253.c (ffffffff81877d69)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_oneshot
```
```
In arch/x86/pci/direct.c (ffffffff828f5bbe)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_write
```
```
In arch/x86/pci/fixup.c (ffffffff8188a4a0)
Location: arch/x86/include/asm/io.h:342
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff8188ac79)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_serverworks_set
  - arch/x86/pci/irq.c:pirq_serverworks_set
  - arch/x86/pci/irq.c:pirq_serverworks_get
  - arch/x86/pci/irq.c:elcr_set_level_irq
```
```
In arch/x86/pci/early.c (ffffffff8188c593)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_byte
```
```
In arch/x86/lib/kaslr.c (ffffffff81a1bcc8)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In arch/x86/kernel/nmi.c (ffffffff81035e82)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In arch/x86/kernel/i8259.c (ffffffff81037123)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A
  - arch/x86/kernel/i8259.c:mask_8259A
  - arch/x86/kernel/i8259.c:mask_8259A
  - arch/x86/kernel/i8259.c:i8259A_shutdown
  - arch/x86/kernel/i8259.c:i8259A_shutdown
  - arch/x86/kernel/i8259.c:i8259A_resume
  - arch/x86/kernel/i8259.c:i8259A_resume
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A_irq
  - arch/x86/kernel/i8259.c:unmask_8259A_irq
  - arch/x86/kernel/i8259.c:mask_8259A_irq
  - arch/x86/kernel/i8259.c:mask_8259A_irq
```
```
In arch/x86/kernel/quirks.c (ffffffff81038a8c)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff8103b644)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
```
```
In arch/x86/kernel/rtc.c (ffffffff8103c4e5)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:rtc_cmos_write
  - arch/x86/kernel/rtc.c:rtc_cmos_write
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In arch/x86/kernel/i8237.c (ffffffff810438d8)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff828b14ed)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff810627dc)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff828b28a6)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828b59ac)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
```
```
In arch/x86/kernel/early_printk.c (ffffffff810746d0)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_out
```
```
In lib/iomap.c (ffffffff81510bca)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In drivers/pci/pci-sysfs.c (ffffffff8156918d)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_write_resource_io
```
```
In drivers/pci/quirks.c (ffffffff81574b1e)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff81597ef1)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815b1d82)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff815b4a2e)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff815c3a52)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81681098)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8168d4db)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:io_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff8168ed7f)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
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
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816908a3)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
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
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff8169168f)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/char/mem.c (ffffffff816981e5)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816b2bc7)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
```
```
In drivers/ata/libata-sff.c (ffffffff8177f9f9)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817e607a)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817ff5e3)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff8181f740)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
```
```
In drivers/input/serio/i8042.c (ffffffff818222c1)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_kbd_write
```
```
In drivers/rtc/rtc-cmos.c (ffffffff818391e0)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In drivers/eisa/eisa-bus.c (ffffffff82909444)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
```
```
In drivers/clocksource/i8253.c (ffffffff818bc5e9)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_oneshot
```
```
In arch/x86/pci/direct.c (ffffffff8291160a)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_write
```
```
In arch/x86/pci/fixup.c (ffffffff818d4a80)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff818d55a9)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_serverworks_set
  - arch/x86/pci/irq.c:pirq_serverworks_set
  - arch/x86/pci/irq.c:pirq_serverworks_get
  - arch/x86/pci/irq.c:elcr_set_level_irq
```
```
In arch/x86/pci/early.c (ffffffff818d6ed3)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_byte
```
```
In arch/x86/lib/kaslr.c (ffffffff81a8ba8a)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In arch/x86/kernel/nmi.c (ffffffff810366a2)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In arch/x86/kernel/i8259.c (ffffffff810378f3)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A
  - arch/x86/kernel/i8259.c:mask_8259A
  - arch/x86/kernel/i8259.c:mask_8259A
  - arch/x86/kernel/i8259.c:i8259A_shutdown
  - arch/x86/kernel/i8259.c:i8259A_shutdown
  - arch/x86/kernel/i8259.c:i8259A_resume
  - arch/x86/kernel/i8259.c:i8259A_resume
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A_irq
  - arch/x86/kernel/i8259.c:unmask_8259A_irq
  - arch/x86/kernel/i8259.c:mask_8259A_irq
  - arch/x86/kernel/i8259.c:mask_8259A_irq
```
```
In arch/x86/kernel/quirks.c (ffffffff8103925c)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff8103be14)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
```
```
In arch/x86/kernel/rtc.c (ffffffff8103cca5)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:rtc_cmos_write
  - arch/x86/kernel/rtc.c:rtc_cmos_write
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In arch/x86/kernel/i8237.c (ffffffff81044028)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff828b493c)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff8106304c)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff828b5cf8)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828b8e6c)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
```
```
In arch/x86/kernel/early_printk.c (ffffffff810756a0)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_out
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff828ca452)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In lib/iomap.c (ffffffff8153163a)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In drivers/pci/pci-sysfs.c (ffffffff8158a1d4)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff815961ce)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff815b9291)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815d2d02)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff815d5cae)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff815e4c92)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816a3748)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816afa2b)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:io_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff816b15af)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
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
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816b32e4)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
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
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff816b417f)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/char/mem.c (ffffffff816badf5)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816d58a7)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
```
```
In drivers/ata/libata-sff.c (ffffffff817a36b9)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81816f3a)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81830443)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff81850bb0)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
```
```
In drivers/input/serio/i8042.c (ffffffff81853731)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_kbd_write
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8186ab50)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In drivers/eisa/eisa-bus.c (ffffffff82912e49)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
```
```
In drivers/clocksource/i8253.c (ffffffff818ef0b9)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_oneshot
```
```
In arch/x86/pci/direct.c (ffffffff8291b3a1)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_write
```
```
In arch/x86/pci/fixup.c (ffffffff81906e00)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff81907929)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_serverworks_set
  - arch/x86/pci/irq.c:pirq_serverworks_set
  - arch/x86/pci/irq.c:pirq_serverworks_get
  - arch/x86/pci/irq.c:elcr_set_level_irq
```
```
In arch/x86/pci/early.c (ffffffff81909253)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_byte
```
```
In arch/x86/lib/kaslr.c (ffffffff81ac2d4a)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In arch/x86/kernel/nmi.c (ffffffff810383c6)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In arch/x86/kernel/i8259.c (ffffffff81039743)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A
  - arch/x86/kernel/i8259.c:mask_8259A
  - arch/x86/kernel/i8259.c:mask_8259A
  - arch/x86/kernel/i8259.c:i8259A_shutdown
  - arch/x86/kernel/i8259.c:i8259A_shutdown
  - arch/x86/kernel/i8259.c:i8259A_resume
  - arch/x86/kernel/i8259.c:i8259A_resume
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:enable_8259A_irq
  - arch/x86/kernel/i8259.c:enable_8259A_irq
  - arch/x86/kernel/i8259.c:disable_8259A_irq
  - arch/x86/kernel/i8259.c:disable_8259A_irq
```
```
In arch/x86/kernel/quirks.c (ffffffff8103bd9d)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff8103ebcd)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:pit_calibrate_tsc
  - arch/x86/kernel/tsc.c:pit_calibrate_tsc
  - arch/x86/kernel/tsc.c:pit_calibrate_tsc
  - arch/x86/kernel/tsc.c:pit_calibrate_tsc
```
```
In arch/x86/kernel/rtc.c (ffffffff8103fb35)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:rtc_cmos_write
  - arch/x86/kernel/rtc.c:rtc_cmos_write
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In arch/x86/kernel/i8237.c (ffffffff81047c78)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff82cd9f87)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff8106914a)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff82cdafba)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
```
In arch/x86/kernel/apic/vector.c (ffffffff82cdde56)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
```
```
In arch/x86/kernel/early_printk.c (ffffffff8107c8b0)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_out
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff82cecb74)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In lib/iomap.c (ffffffff81595b76)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In arch/x86/lib/kaslr.c (ffffffff815ff3da)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
```
In drivers/pci/pci-sysfs.c (ffffffff816312c1)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff816448ce)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff81663a4a)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff8167c8a2)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff8167f83e)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff816900bf)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81755cb1)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81761c16)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:io_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81764885)
Location: arch/x86/include/asm/io.h:334
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
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81767369)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
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
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81767a1f)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/char/mem.c (ffffffff8176ef28)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81789caa)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
```
```
In drivers/ata/libata-sff.c (ffffffff81868d09)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff818e7fb8)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81901323)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff819224fb)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:ehci_reset_port
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
```
```
In drivers/input/serio/i8042.c (ffffffff81925931)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_kbd_write
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8193e6d0)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In drivers/eisa/eisa-bus.c (ffffffff82d25acb)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:decode_eisa_sig
```
```
In drivers/clocksource/i8253.c (ffffffff819c2c99)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_oneshot
```
```
In arch/x86/pci/direct.c (ffffffff82d31107)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_write
```
```
In arch/x86/pci/fixup.c (ffffffff81bb7300)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff81bb8049)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_serverworks_set
  - arch/x86/pci/irq.c:pirq_serverworks_set
  - arch/x86/pci/irq.c:pirq_serverworks_get
  - arch/x86/pci/irq.c:elcr_set_level_irq
```
```
In arch/x86/pci/early.c (ffffffff81bb9b33)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_byte
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
In arch/x86/kernel/nmi.c (ffffffff81bd399c)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In arch/x86/kernel/i8259.c (ffffffff81039fa3)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A
  - arch/x86/kernel/i8259.c:mask_8259A
  - arch/x86/kernel/i8259.c:mask_8259A
  - arch/x86/kernel/i8259.c:i8259A_shutdown
  - arch/x86/kernel/i8259.c:i8259A_shutdown
  - arch/x86/kernel/i8259.c:i8259A_resume
  - arch/x86/kernel/i8259.c:i8259A_resume
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:enable_8259A_irq
  - arch/x86/kernel/i8259.c:enable_8259A_irq
  - arch/x86/kernel/i8259.c:disable_8259A_irq
  - arch/x86/kernel/i8259.c:disable_8259A_irq
```
```
In arch/x86/kernel/quirks.c (ffffffff8103c50d)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff8103ec7d)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:pit_calibrate_tsc
  - arch/x86/kernel/tsc.c:pit_calibrate_tsc
  - arch/x86/kernel/tsc.c:pit_calibrate_tsc
  - arch/x86/kernel/tsc.c:pit_calibrate_tsc
```
```
In arch/x86/kernel/rtc.c (ffffffff8103f9b5)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:rtc_cmos_write
  - arch/x86/kernel/rtc.c:rtc_cmos_write
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In arch/x86/kernel/i8237.c (ffffffff81047138)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff82fc63a5)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff8106adca)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff82fc740e)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
```
In arch/x86/kernel/apic/vector.c (ffffffff82fca214)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
```
```
In arch/x86/kernel/early_printk.c (ffffffff8107c702)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_out
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff82fd91ce)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In lib/iomap.c (ffffffff815b1606)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In arch/x86/lib/kaslr.c (ffffffff816243aa)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
```
In drivers/pci/pci-sysfs.c (ffffffff81656961)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff8166acde)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff816846da)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff8169c632)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff8169e2fe)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff816adf0b)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81770f21)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8177d04b)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:io_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff8177f7a5)
Location: arch/x86/include/asm/io.h:334
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
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8177fe75)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_init
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
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff8178277f)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/char/mem.c (ffffffff81789811)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff817a0b9a)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
```
```
In drivers/ata/libata-sff.c (ffffffff81877b19)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff818f0f98)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81909bf3)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff81929beb)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:ehci_reset_port
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
```
```
In drivers/input/serio/i8042.c (ffffffff8192d491)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_kbd_write
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81944200)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In drivers/eisa/eisa-bus.c (ffffffff8301406c)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:decode_eisa_sig
```
```
In drivers/clocksource/i8253.c (ffffffff819c30b9)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_oneshot
```
```
In arch/x86/pci/direct.c (ffffffff83020091)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_write
```
```
In arch/x86/pci/fixup.c (ffffffff81bcc390)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff81bccc59)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_serverworks_set
  - arch/x86/pci/irq.c:pirq_serverworks_set
  - arch/x86/pci/irq.c:pirq_serverworks_get
  - arch/x86/pci/irq.c:elcr_set_level_irq
```
```
In arch/x86/pci/early.c (ffffffff81bce433)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_byte
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
In arch/x86/kernel/nmi.c (ffffffff81bc5e0e)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In arch/x86/kernel/i8259.c (ffffffff8103ba73)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A
  - arch/x86/kernel/i8259.c:mask_8259A
  - arch/x86/kernel/i8259.c:mask_8259A
  - arch/x86/kernel/i8259.c:i8259A_shutdown
  - arch/x86/kernel/i8259.c:i8259A_shutdown
  - arch/x86/kernel/i8259.c:i8259A_resume
  - arch/x86/kernel/i8259.c:i8259A_resume
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:enable_8259A_irq
  - arch/x86/kernel/i8259.c:enable_8259A_irq
  - arch/x86/kernel/i8259.c:disable_8259A_irq
  - arch/x86/kernel/i8259.c:disable_8259A_irq
```
```
In arch/x86/kernel/quirks.c (ffffffff8103de5a)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff810406f7)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
```
```
In arch/x86/kernel/rtc.c (ffffffff81041355)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:rtc_cmos_write
  - arch/x86/kernel/rtc.c:rtc_cmos_write
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In arch/x86/kernel/i8237.c (ffffffff81048af8)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff831d087f)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff8106b76c)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff831d1cb6)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
```
In arch/x86/kernel/apic/vector.c (ffffffff831d4b37)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
```
```
In arch/x86/kernel/early_printk.c (ffffffff8107d8b2)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_out
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff831e3a47)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In lib/iomap.c (ffffffff815bc416)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In arch/x86/lib/kaslr.c (ffffffff81607d9a)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
```
In drivers/pci/pci-sysfs.c (ffffffff81639581)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff8164d02e)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff8166766a)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
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
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff8167f43a)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff8168103e)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff8169055c)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff817549e1)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8176047b)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:io_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81762fba)
Location: arch/x86/include/asm/io.h:334
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
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff817637a5)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_init
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
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff8176607f)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/char/mem.c (ffffffff8176d0c0)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff817837a9)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
```
```
In drivers/ata/libata-sff.c (ffffffff8185a2f9)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff818d4798)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff818ee313)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff8190d87b)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
```
```
In drivers/input/serio/i8042.c (ffffffff819108e4)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_kbd_write
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81927a30)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In drivers/eisa/eisa-bus.c (ffffffff8321f173)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
```
```
In drivers/clocksource/i8253.c (ffffffff819a74f9)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_oneshot
```
```
In arch/x86/pci/direct.c (ffffffff8322b284)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_write
```
```
In arch/x86/pci/fixup.c (ffffffff81bbfdd0)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff81bc0689)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_serverworks_set
  - arch/x86/pci/irq.c:pirq_serverworks_set
  - arch/x86/pci/irq.c:pirq_serverworks_get
  - arch/x86/pci/irq.c:elcr_set_level_irq
```
```
In arch/x86/pci/early.c (ffffffff81bc1df1)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_byte
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
In arch/x86/kernel/nmi.c (ffffffff81c98b58)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In arch/x86/kernel/i8259.c (ffffffff81041563)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A
  - arch/x86/kernel/i8259.c:mask_8259A
  - arch/x86/kernel/i8259.c:mask_8259A
  - arch/x86/kernel/i8259.c:i8259A_shutdown
  - arch/x86/kernel/i8259.c:i8259A_shutdown
  - arch/x86/kernel/i8259.c:i8259A_resume
  - arch/x86/kernel/i8259.c:i8259A_resume
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A_irq
  - arch/x86/kernel/i8259.c:unmask_8259A_irq
  - arch/x86/kernel/i8259.c:mask_8259A_irq
  - arch/x86/kernel/i8259.c:mask_8259A_irq
```
```
In arch/x86/kernel/quirks.c (ffffffff81043bdc)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff810467e7)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
```
```
In arch/x86/kernel/rtc.c (ffffffff810475d5)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:rtc_cmos_write
  - arch/x86/kernel/rtc.c:rtc_cmos_write
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In arch/x86/kernel/i8237.c (ffffffff8104f4c8)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff832b2dc7)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff8107625a)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff832b413f)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
```
In arch/x86/kernel/apic/vector.c (ffffffff832b76ba)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
```
```
In arch/x86/kernel/early_printk.c (ffffffff8108c2e2)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_out
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff832c7569)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In lib/iomap.c (ffffffff81623266)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In arch/x86/lib/kaslr.c (ffffffff816769da)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
```
In drivers/pci/pci-sysfs.c (ffffffff816a9a6a)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff816bee5e)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff816da8aa)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
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
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff816f43f9)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff816f611e)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff81705f17)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff817d809e)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff817e43eb)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:io_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff817e7214)
Location: arch/x86/include/asm/io.h:334
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
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff817e7b85)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_init
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
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff817eaa16)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/char/mem.c (ffffffff817f2890)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8180a1c9)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
```
```
In drivers/ata/libata-sff.c (ffffffff818e8de9)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8196f068)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8198aae3)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff819ae4f8)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
```
```
In drivers/input/serio/i8042.c (ffffffff819b1827)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_kbd_write
```
```
In drivers/rtc/rtc-cmos.c (ffffffff819caa50)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In drivers/eisa/eisa-bus.c (ffffffff833088b7)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
```
```
In drivers/clocksource/i8253.c (ffffffff81a549f9)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_oneshot
```
```
In arch/x86/pci/direct.c (ffffffff83315a08)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_write
```
```
In arch/x86/pci/fixup.c (ffffffff81c8fd60)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff81c907a9)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_serverworks_set
  - arch/x86/pci/irq.c:pirq_serverworks_set
  - arch/x86/pci/irq.c:pirq_serverworks_get
  - arch/x86/pci/irq.c:pirq_esc_set
  - arch/x86/pci/irq.c:pirq_esc_set
  - arch/x86/pci/irq.c:pirq_esc_set
  - arch/x86/pci/irq.c:pirq_esc_set
  - arch/x86/pci/irq.c:pirq_esc_set
  - arch/x86/pci/irq.c:pirq_esc_set
  - arch/x86/pci/irq.c:pirq_esc_get
  - arch/x86/pci/irq.c:pirq_esc_get
  - arch/x86/pci/irq.c:pirq_esc_get
  - arch/x86/pci/irq.c:pirq_esc_get
  - arch/x86/pci/irq.c:pirq_esc_get
  - arch/x86/pci/irq.c:pirq_finali_lvl
  - arch/x86/pci/irq.c:pirq_finali_lvl
  - arch/x86/pci/irq.c:pirq_finali_lvl
  - arch/x86/pci/irq.c:pirq_finali_lvl
  - arch/x86/pci/irq.c:pirq_finali_lvl
  - arch/x86/pci/irq.c:pirq_finali_lvl
  - arch/x86/pci/irq.c:pirq_finali_lvl
  - arch/x86/pci/irq.c:pirq_finali_set
  - arch/x86/pci/irq.c:pirq_finali_set
  - arch/x86/pci/irq.c:pirq_finali_set
  - arch/x86/pci/irq.c:pirq_finali_set
  - arch/x86/pci/irq.c:pirq_finali_set
  - arch/x86/pci/irq.c:pirq_finali_set
  - arch/x86/pci/irq.c:pirq_finali_set
  - arch/x86/pci/irq.c:pirq_finali_get
  - arch/x86/pci/irq.c:pirq_finali_get
  - arch/x86/pci/irq.c:pirq_finali_get
  - arch/x86/pci/irq.c:pirq_finali_get
  - arch/x86/pci/irq.c:pirq_finali_get
  - arch/x86/pci/irq.c:elcr_set_level_irq
```
```
In arch/x86/pci/early.c (ffffffff81c92401)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_byte
```
</details>
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
In arch/powerpc/kernel/udbg_16550.c (c000000000068930)
Location: arch/powerpc/include/asm/io-defs.h:26
Inline: True
Inline callers:
  - arch/powerpc/kernel/udbg_16550.c:udbg_uart_out_pio
```
```
In arch/powerpc/sysdev/i8259.c (c0000000000b994c)
Location: arch/powerpc/include/asm/io-defs.h:26
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
  - arch/powerpc/sysdev/i8259.c:i8259_mask_and_ack_irq
  - arch/powerpc/sysdev/i8259.c:i8259_mask_and_ack_irq
  - arch/powerpc/sysdev/i8259.c:i8259_mask_and_ack_irq
  - arch/powerpc/sysdev/i8259.c:i8259_mask_and_ack_irq
  - arch/powerpc/sysdev/i8259.c:i8259_mask_and_ack_irq
  - arch/powerpc/sysdev/i8259.c:i8259_irq
  - arch/powerpc/sysdev/i8259.c:i8259_irq
  - arch/powerpc/sysdev/i8259.c:i8259_irq
  - arch/powerpc/sysdev/i8259.c:i8259_irq
  - arch/powerpc/sysdev/i8259.c:i8259_irq
  - arch/powerpc/sysdev/i8259.c:i8259_irq
```
```
In lib/iomap.c (c0000000007e55d8)
Location: arch/powerpc/include/asm/io-defs.h:26
Inline: True
```
```
In drivers/pci/pci-sysfs.c (c00000000086b598)
Location: arch/powerpc/include/asm/io-defs.h:26
Inline: True
```
```
In drivers/video/console/vgacon.c (c00000000089dadc)
Location: arch/powerpc/include/asm/io-defs.h:26
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
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/tty/serial/8250/8250_port.c (c0000000009338dc)
Location: arch/powerpc/include/asm/io-defs.h:26
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:io_serial_out
  - drivers/tty/serial/8250/8250_port.c:io_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (c0000000009397fc)
Location: arch/powerpc/include/asm/io-defs.h:26
Inline: True
Inline callers:
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
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqopr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqopr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqopr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqopr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqopr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqopr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqopr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqopr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqopr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqopr
```
```
In drivers/tty/serial/8250/8250_early.c (c00000000093a484)
Location: arch/powerpc/include/asm/io-defs.h:26
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/char/mem.c (c000000000942aa8)
Location: arch/powerpc/include/asm/io-defs.h:26
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
```
```
In drivers/ata/libata-sff.c (c000000000a79b44)
Location: arch/powerpc/include/asm/io-defs.h:26
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (c000000000b190a0)
Location: arch/powerpc/include/asm/io-defs.h:26
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (c000000000b377f4)
Location: arch/powerpc/include/asm/io-defs.h:26
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:configure_hc
```
```
In drivers/input/serio/i8042.c (c000000000b70980)
Location: arch/powerpc/include/asm/io-defs.h:26
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_kbd_write
  - drivers/input/serio/i8042.c:i8042_kbd_write
```
```
In drivers/rtc/rtc-mc146818-lib.c (c000000000b8f01c)
Location: arch/powerpc/include/asm/io-defs.h:26
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
In arch/x86/kernel/nmi.c (ffffffff81036802)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In arch/x86/kernel/i8259.c (ffffffff81037a53)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A
  - arch/x86/kernel/i8259.c:mask_8259A
  - arch/x86/kernel/i8259.c:mask_8259A
  - arch/x86/kernel/i8259.c:i8259A_shutdown
  - arch/x86/kernel/i8259.c:i8259A_shutdown
  - arch/x86/kernel/i8259.c:i8259A_resume
  - arch/x86/kernel/i8259.c:i8259A_resume
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A_irq
  - arch/x86/kernel/i8259.c:unmask_8259A_irq
  - arch/x86/kernel/i8259.c:mask_8259A_irq
  - arch/x86/kernel/i8259.c:mask_8259A_irq
```
```
In arch/x86/kernel/quirks.c (ffffffff810393bc)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff8103bf74)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
```
```
In arch/x86/kernel/rtc.c (ffffffff8103ce25)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:rtc_cmos_write
  - arch/x86/kernel/rtc.c:rtc_cmos_write
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In arch/x86/kernel/i8237.c (ffffffff810441a8)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff828a295b)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff81062b3c)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff828a3d04)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828a6e73)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
```
```
In arch/x86/kernel/early_printk.c (ffffffff810746a0)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_out
```
```
In lib/iomap.c (ffffffff81529c1a)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157e064)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff8158a05e)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff815ad3e1)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815c6d12)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff815c9a0e)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff815d6b82)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816691a8)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8167549b)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:io_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff8167701f)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
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
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81678d43)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
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
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81679bdf)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/char/mem.c (ffffffff81680855)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8169b2f7)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
```
```
In drivers/ata/libata-sff.c (ffffffff81768779)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817cf31a)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817e8823)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff81806980)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
```
```
In drivers/input/serio/i8042.c (ffffffff81808811)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_kbd_write
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8181d800)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In drivers/eisa/eisa-bus.c (ffffffff828f8c5d)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
```
```
In drivers/clocksource/i8253.c (ffffffff81890489)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_oneshot
```
```
In arch/x86/pci/direct.c (ffffffff829000b0)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_write
```
```
In arch/x86/pci/fixup.c (ffffffff818a61c0)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff818a6ce9)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_serverworks_set
  - arch/x86/pci/irq.c:pirq_serverworks_set
  - arch/x86/pci/irq.c:pirq_serverworks_get
  - arch/x86/pci/irq.c:elcr_set_level_irq
```
```
In arch/x86/pci/early.c (ffffffff818a8613)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_byte
```
```
In arch/x86/lib/kaslr.c (ffffffff81a61b9a)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In arch/x86/kernel/nmi.c (ffffffff81026142)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In arch/x86/kernel/i8259.c (ffffffff81027433)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A
  - arch/x86/kernel/i8259.c:mask_8259A
  - arch/x86/kernel/i8259.c:mask_8259A
  - arch/x86/kernel/i8259.c:i8259A_shutdown
  - arch/x86/kernel/i8259.c:i8259A_shutdown
  - arch/x86/kernel/i8259.c:i8259A_resume
  - arch/x86/kernel/i8259.c:i8259A_resume
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A_irq
  - arch/x86/kernel/i8259.c:unmask_8259A_irq
  - arch/x86/kernel/i8259.c:mask_8259A_irq
  - arch/x86/kernel/i8259.c:mask_8259A_irq
```
```
In arch/x86/kernel/quirks.c (ffffffff81028ccc)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff8102b7c7)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
```
```
In arch/x86/kernel/rtc.c (ffffffff8102c4b5)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:rtc_cmos_write
  - arch/x86/kernel/rtc.c:rtc_cmos_write
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In arch/x86/kernel/i8237.c (ffffffff810337c8)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff8289aa9d)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff81052f0c)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff8289be46)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8289ef7b)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
```
```
In arch/x86/kernel/early_printk.c (ffffffff810646d0)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_out
```
```
In lib/iomap.c (ffffffff81519efa)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In drivers/pci/pci-sysfs.c (ffffffff8156ce34)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff81578b9e)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff8159c581)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/osl.c (ffffffff815b2a9e)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff815c0742)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8165457b)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:io_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff816560ff)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
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
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81657e34)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
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
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81658ccf)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/char/mem.c (ffffffff8165e525)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81678ce7)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
```
```
In drivers/ata/libata-sff.c (ffffffff817485d9)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817ad24a)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff817ce0b0)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
```
```
In drivers/input/serio/i8042.c (ffffffff817cfef1)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_kbd_write
```
```
In drivers/rtc/rtc-cmos.c (ffffffff817e4ed0)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In drivers/eisa/eisa-bus.c (ffffffff828f0746)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
```
```
In drivers/clocksource/i8253.c (ffffffff81849749)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_oneshot
```
```
In arch/x86/pci/direct.c (ffffffff828f86ba)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_write
```
```
In arch/x86/pci/fixup.c (ffffffff81860cf0)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff81861809)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_serverworks_set
  - arch/x86/pci/irq.c:pirq_serverworks_set
  - arch/x86/pci/irq.c:pirq_serverworks_get
  - arch/x86/pci/irq.c:elcr_set_level_irq
```
```
In arch/x86/pci/early.c (ffffffff81863023)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_byte
```
```
In arch/x86/lib/kaslr.c (ffffffff81a1ec0a)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In arch/x86/kernel/nmi.c (ffffffff81036662)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In arch/x86/kernel/i8259.c (ffffffff810378b3)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A
  - arch/x86/kernel/i8259.c:mask_8259A
  - arch/x86/kernel/i8259.c:mask_8259A
  - arch/x86/kernel/i8259.c:i8259A_shutdown
  - arch/x86/kernel/i8259.c:i8259A_shutdown
  - arch/x86/kernel/i8259.c:i8259A_resume
  - arch/x86/kernel/i8259.c:i8259A_resume
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A_irq
  - arch/x86/kernel/i8259.c:unmask_8259A_irq
  - arch/x86/kernel/i8259.c:mask_8259A_irq
  - arch/x86/kernel/i8259.c:mask_8259A_irq
```
```
In arch/x86/kernel/quirks.c (ffffffff8103921c)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff8103bdd4)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
```
```
In arch/x86/kernel/rtc.c (ffffffff8103cc65)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:rtc_cmos_write
  - arch/x86/kernel/rtc.c:rtc_cmos_write
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In arch/x86/kernel/i8237.c (ffffffff81043fe8)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff828b5858)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff81062fec)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff828b6c14)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828b9d83)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
```
```
In arch/x86/kernel/early_printk.c (ffffffff81074650)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_out
```
```
In lib/iomap.c (ffffffff81525caa)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157df24)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff81589f1e)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff815ad971)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815c72a2)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff815c9f8e)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff815d8f72)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81697588)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816a386b)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:io_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff816a53ef)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
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
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816a7124)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
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
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff816a7fbf)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/char/mem.c (ffffffff816aec35)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816c9567)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
```
```
In drivers/ata/libata-sff.c (ffffffff81798539)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8180bdba)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff818252c3)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff81845a30)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
```
```
In drivers/input/serio/i8042.c (ffffffff818478c1)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_kbd_write
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8185ece0)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In drivers/eisa/eisa-bus.c (ffffffff8290d495)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
```
```
In drivers/clocksource/i8253.c (ffffffff818e3ee9)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_oneshot
```
```
In arch/x86/pci/direct.c (ffffffff829156ac)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_write
```
```
In arch/x86/pci/fixup.c (ffffffff818f7820)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff818f8349)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_serverworks_set
  - arch/x86/pci/irq.c:pirq_serverworks_set
  - arch/x86/pci/irq.c:pirq_serverworks_get
  - arch/x86/pci/irq.c:elcr_set_level_irq
```
```
In arch/x86/pci/early.c (ffffffff818f9c73)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_byte
```
```
In arch/x86/lib/kaslr.c (ffffffff81acdf8a)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In arch/x86/kernel/nmi.c (ffffffff81037662)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In arch/x86/kernel/i8259.c (ffffffff810388b3)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A
  - arch/x86/kernel/i8259.c:mask_8259A
  - arch/x86/kernel/i8259.c:mask_8259A
  - arch/x86/kernel/i8259.c:i8259A_shutdown
  - arch/x86/kernel/i8259.c:i8259A_shutdown
  - arch/x86/kernel/i8259.c:i8259A_resume
  - arch/x86/kernel/i8259.c:i8259A_resume
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:unmask_8259A_irq
  - arch/x86/kernel/i8259.c:unmask_8259A_irq
  - arch/x86/kernel/i8259.c:mask_8259A_irq
  - arch/x86/kernel/i8259.c:mask_8259A_irq
```
```
In arch/x86/kernel/quirks.c (ffffffff8103a21c)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff8103ce24)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
```
```
In arch/x86/kernel/rtc.c (ffffffff8103dcf5)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:rtc_cmos_write
  - arch/x86/kernel/rtc.c:rtc_cmos_write
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In arch/x86/kernel/i8237.c (ffffffff810453e8)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
  - arch/x86/kernel/i8237.c:i8237A_resume
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff828b593f)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff810645ac)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff828b6cfb)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828b9e84)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
```
```
In arch/x86/kernel/early_printk.c (ffffffff810766b0)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_out
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff828cb48f)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In lib/iomap.c (ffffffff8153f62a)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In drivers/pci/pci-sysfs.c (ffffffff815983d4)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff815a43ce)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff815c7421)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815e0e42)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff815e3dee)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff815f2e32)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816b1c48)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816bdcfb)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:io_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff816bf84f)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
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
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816c1584)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
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
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff816c241f)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/char/mem.c (ffffffff816c91c5)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816e3a47)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
```
```
In drivers/ata/libata-sff.c (ffffffff817b23a9)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81825eca)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8183ad03)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff8185ffb0)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
```
```
In drivers/input/serio/i8042.c (ffffffff81862b01)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_kbd_write
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81879210)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In drivers/eisa/eisa-bus.c (ffffffff82913eab)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
```
```
In drivers/clocksource/i8253.c (ffffffff81900b39)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_oneshot
```
```
In arch/x86/pci/direct.c (ffffffff8291c403)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_write
```
```
In arch/x86/pci/fixup.c (ffffffff81918920)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff81919449)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_serverworks_set
  - arch/x86/pci/irq.c:pirq_serverworks_set
  - arch/x86/pci/irq.c:pirq_serverworks_get
  - arch/x86/pci/irq.c:elcr_set_level_irq
```
```
In arch/x86/pci/early.c (ffffffff8191add3)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_byte
```
```
In arch/x86/lib/kaslr.c (ffffffff81ada49a)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
</details>
</li>
</ul>

## Differences
