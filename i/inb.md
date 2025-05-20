# Function: <code>inb</code>

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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8102454d)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In arch/x86/kernel/x86_init.c (ffffffff81033234)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/x86_init.c:default_get_nmi_reason
```
```
In arch/x86/kernel/i8259.c (ffffffff8103342d)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:i8259A_irq_pending
  - arch/x86/kernel/i8259.c:i8259A_irq_pending
  - arch/x86/kernel/i8259.c:i8259A_suspend
  - arch/x86/kernel/i8259.c:i8259A_suspend
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:probe_8259A
```
```
In arch/x86/kernel/quirks.c (ffffffff81035610)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff81037f09)
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
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/rtc.c (ffffffff810387dd)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
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
In arch/x86/kernel/acpi/boot.c (ffffffff81f6e351)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff810505cf)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff81f6f2f6)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In arch/x86/kernel/mpparse.c (ffffffff81f70185)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81f72451)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In arch/x86/kernel/early_printk.c (ffffffff81061ce1)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_in
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff8113a14e)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state
  - kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state
  - kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state
```
```
In lib/iomap.c (ffffffff814026c2)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In drivers/pci/pci-sysfs.c (ffffffff8143afd1)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_resource_io
```
```
In drivers/video/console/vgacon.c (ffffffff8145d6ce)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/osl.c (ffffffff81479a90)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff81483076)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/processor_idle.c (ffffffff814ac5b3)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81505ab2)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
  - drivers/tty/serial/8250/8250_port.c:io_serial_in
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8150a0e5)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_in
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81fa7546)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In drivers/char/mem.c (ffffffff8151118f)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/char/mem.c:read_port
```
```
In drivers/ata/libata-sff.c (ffffffff815dbeb8)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8163001b)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81646b79)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/input/serio/i8042.c (ffffffff81664985)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_wait_write
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81677118)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In arch/x86/pci/direct.c (ffffffff816f698c)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf1_read
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
```
In arch/x86/pci/fixup.c (ffffffff816f8948)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff816f9071)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_serverworks_get
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:elcr_set_level_irq
```
```
In arch/x86/pci/early.c (ffffffff816fa8a3)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/pci/early.c:early_dump_pci_devices
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8102380d)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In arch/x86/kernel/x86_init.c (ffffffff81032404)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/x86_init.c:default_get_nmi_reason
```
```
In arch/x86/kernel/i8259.c (ffffffff8103285a)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:i8259A_suspend
  - arch/x86/kernel/i8259.c:i8259A_suspend
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:i8259A_irq_pending
  - arch/x86/kernel/i8259.c:i8259A_irq_pending
```
```
In arch/x86/kernel/quirks.c (ffffffff81034810)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff810373b2)
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
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
```
```
In arch/x86/kernel/rtc.c (ffffffff81037b3f)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
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
In arch/x86/kernel/acpi/boot.c (ffffffff81f96768)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff810507a9)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff81f97a8b)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In arch/x86/kernel/mpparse.c (ffffffff81f988cc)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81f9ac45)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In arch/x86/kernel/early_printk.c (ffffffff81061b17)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_in
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff811428ad)
Location: arch/x86/include/asm/io.h:316
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
In arch/x86/lib/kaslr.c (ffffffff8143e01c)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
```
In lib/iomap.c (ffffffff8144a375)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In drivers/pci/pci-sysfs.c (ffffffff81488479)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff814ab8db)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/osl.c (ffffffff814c8055)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff814d2199)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/processor_idle.c (ffffffff814fc992)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81558cf3)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:io_serial_in
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff8155c182)
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
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8155c4ce)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_in
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81fd39ff)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/char/mem.c (ffffffff8156370b)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/char/mem.c:read_port
```
```
In drivers/ata/libata-sff.c (ffffffff81635c38)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81690c7b)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816a76ad)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/input/serio/i8042.c (ffffffff816c4d4b)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_wait_write
```
```
In drivers/rtc/rtc-cmos.c (ffffffff816d7cdd)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In arch/x86/pci/direct.c (ffffffff81fe6382)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/fixup.c (ffffffff8175d628)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff8175ddf5)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_serverworks_get
  - arch/x86/pci/irq.c:elcr_set_level_irq
```
```
In arch/x86/pci/early.c (ffffffff8175fa1e)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/pci/early.c:early_dump_pci_devices
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff81023f3d)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In arch/x86/kernel/x86_init.c (ffffffff81032084)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/x86_init.c:default_get_nmi_reason
```
```
In arch/x86/kernel/i8259.c (ffffffff810324ca)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:i8259A_suspend
  - arch/x86/kernel/i8259.c:i8259A_suspend
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:i8259A_irq_pending
  - arch/x86/kernel/i8259.c:i8259A_irq_pending
```
```
In arch/x86/kernel/quirks.c (ffffffff81034450)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff81037142)
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
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
```
```
In arch/x86/kernel/rtc.c (ffffffff81037918)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
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
In arch/x86/kernel/acpi/boot.c (ffffffff81fd1c9c)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff81053019)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff81fd2f9d)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In arch/x86/kernel/mpparse.c (ffffffff81fd3d95)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81fd610c)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In arch/x86/kernel/early_printk.c (ffffffff81064bc7)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_in
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff8114c68d)
Location: arch/x86/include/asm/io.h:316
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
In arch/x86/lib/kaslr.c (ffffffff8145af9c)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
```
In lib/iomap.c (ffffffff81468d35)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In drivers/pci/pci-sysfs.c (ffffffff814a9c59)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff814cd9e8)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/osl.c (ffffffff814e9f65)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff814f4642)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/processor_idle.c (ffffffff8151f61a)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81585501)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:io_serial_in
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff8158894c)
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
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81588e0e)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_in
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff820113bf)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/char/mem.c (ffffffff8158fe6b)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/char/mem.c:read_port
```
```
In drivers/ata/libata-sff.c (ffffffff81666cd8)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff816bed2b)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816d57cd)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/input/serio/i8042.c (ffffffff816f2d6b)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_wait_write
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81707cdd)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In arch/x86/pci/direct.c (ffffffff82024bc6)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/fixup.c (ffffffff81789b58)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff8178a325)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_serverworks_get
  - arch/x86/pci/irq.c:elcr_set_level_irq
```
```
In arch/x86/pci/early.c (ffffffff8178bf5e)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - arch/x86/pci/early.c:early_dump_pci_devices
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101b74e)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In arch/x86/kernel/x86_init.c (ffffffff810302c4)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/kernel/x86_init.c:default_get_nmi_reason
```
```
In arch/x86/kernel/i8259.c (ffffffff8103070a)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:i8259A_suspend
  - arch/x86/kernel/i8259.c:i8259A_suspend
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:i8259A_irq_pending
  - arch/x86/kernel/i8259.c:i8259A_irq_pending
```
```
In arch/x86/kernel/quirks.c (ffffffff81032511)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff810351dc)
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
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
```
```
In arch/x86/kernel/rtc.c (ffffffff810359c8)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
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
In arch/x86/kernel/acpi/boot.c (ffffffff820b289a)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff81052b78)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff820b3c06)
Location: arch/x86/include/asm/io.h:340
Inline: True
```
```
In arch/x86/kernel/mpparse.c (ffffffff820b4a6c)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
```
```
In arch/x86/kernel/apic/vector.c (ffffffff820b6e3f)
Location: arch/x86/include/asm/io.h:340
Inline: True
```
```
In arch/x86/kernel/early_printk.c (ffffffff81063b47)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_in
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff8114e5fd)
Location: arch/x86/include/asm/io.h:340
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
In lib/iomap.c (ffffffff8146e415)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In drivers/pci/pci-sysfs.c (ffffffff814b41dd)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/video/console/vgacon.c (ffffffff814d99e8)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/osl.c (ffffffff814f5c5d)
Location: arch/x86/include/asm/io.h:340
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff81503577)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/processor_idle.c (ffffffff81530b85)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8159b347)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:io_serial_in
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff8159cdba)
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
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8159d28e)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_in
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff820f2f71)
Location: arch/x86/include/asm/io.h:340
Inline: True
```
```
In drivers/char/mem.c (ffffffff815a3f4b)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/char/mem.c:read_port
```
```
In drivers/ata/libata-sff.c (ffffffff8167b468)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff816d35e9)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816e99b4)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/input/serio/i8042.c (ffffffff8170869d)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_wait_write
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8171d8fe)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In arch/x86/pci/direct.c (ffffffff8210806c)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/fixup.c (ffffffff817a8cd1)
Location: arch/x86/include/asm/io.h:340
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff817a9465)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_serverworks_get
  - arch/x86/pci/irq.c:elcr_set_level_irq
```
```
In arch/x86/pci/early.c (ffffffff817aaefc)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/pci/early.c:early_dump_pci_devices
```
```
In arch/x86/lib/kaslr.c (ffffffff818fcd3c)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101c42e)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In arch/x86/kernel/x86_init.c (ffffffff81032654)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/x86_init.c:default_get_nmi_reason
```
```
In arch/x86/kernel/i8259.c (ffffffff81032aaa)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:i8259A_suspend
  - arch/x86/kernel/i8259.c:i8259A_suspend
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:i8259A_irq_pending
  - arch/x86/kernel/i8259.c:i8259A_irq_pending
```
```
In arch/x86/kernel/quirks.c (ffffffff81034841)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff8103752c)
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
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
```
```
In arch/x86/kernel/rtc.c (ffffffff81037ce8)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
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
In arch/x86/kernel/acpi/boot.c (ffffffff826b90d4)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff81056875)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff826ba443)
Location: arch/x86/include/asm/io.h:348
Inline: True
```
```
In arch/x86/kernel/mpparse.c (ffffffff826bb1c7)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
```
```
In arch/x86/kernel/apic/vector.c (ffffffff826bd75d)
Location: arch/x86/include/asm/io.h:348
Inline: True
```
```
In arch/x86/kernel/early_printk.c (ffffffff81067cb7)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_in
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff8115ae8d)
Location: arch/x86/include/asm/io.h:348
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
In lib/iomap.c (ffffffff8149a749)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In drivers/pci/pci-sysfs.c (ffffffff814f39ed)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/video/console/vgacon.c (ffffffff81519c0c)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/osl.c (ffffffff8153659d)
Location: arch/x86/include/asm/io.h:348
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff815459d7)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/processor_idle.c (ffffffff81591b95)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8160057d)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:io_serial_in
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81602291)
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
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8160279e)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_in
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81604b63)
Location: arch/x86/include/asm/io.h:348
Inline: True
```
```
In drivers/char/mem.c (ffffffff8160a95b)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - drivers/char/mem.c:read_port
```
```
In drivers/ata/libata-sff.c (ffffffff816e4ad8)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8173fca9)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817561a4)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/input/serio/i8042.c (ffffffff8177988d)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_wait_write
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8178eb7e)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In arch/x86/pci/direct.c (ffffffff827119b2)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/fixup.c (ffffffff8181ff71)
Location: arch/x86/include/asm/io.h:348
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff81820915)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_serverworks_get
  - arch/x86/pci/irq.c:elcr_set_level_irq
```
```
In arch/x86/pci/early.c (ffffffff818223ec)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - arch/x86/pci/early.c:early_dump_pci_devices
```
```
In arch/x86/lib/kaslr.c (ffffffff819847ec)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101ce31)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In arch/x86/kernel/x86_init.c (ffffffff81033970)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - arch/x86/kernel/x86_init.c:default_get_nmi_reason
```
```
In arch/x86/kernel/i8259.c (ffffffff81033dca)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:i8259A_suspend
  - arch/x86/kernel/i8259.c:i8259A_suspend
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:i8259A_irq_pending
  - arch/x86/kernel/i8259.c:i8259A_irq_pending
```
```
In arch/x86/kernel/quirks.c (ffffffff81035859)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff8103858e)
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
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
```
```
In arch/x86/kernel/rtc.c (ffffffff81038de8)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
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
In arch/x86/kernel/i8237.c (ffffffff826ddfb8)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - arch/x86/kernel/i8237.c:i8237A_init_ops
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff826e2e22)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff8105968f)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff826e40ae)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
```
In arch/x86/kernel/mpparse.c (ffffffff826e5090)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
```
```
In arch/x86/kernel/apic/vector.c (ffffffff826e6f77)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
```
```
In arch/x86/kernel/early_printk.c (ffffffff8106a8f0)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_in
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff81169acd)
Location: arch/x86/include/asm/io.h:333
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
In lib/iomap.c (ffffffff814cf9f6)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In drivers/pci/pci-sysfs.c (ffffffff81523c11)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/video/console/vgacon.c (ffffffff8154f6f5)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/osl.c (ffffffff8156c1d2)
Location: arch/x86/include/asm/io.h:333
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff8157bfa9)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/processor_idle.c (ffffffff815c8f68)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816390c1)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:io_serial_in
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff8163b53e)
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
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8163ba55)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_in
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff8163ddf0)
Location: arch/x86/include/asm/io.h:333
Inline: True
```
```
In drivers/char/mem.c (ffffffff816442a1)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - drivers/char/mem.c:read_port
```
```
In drivers/ata/libata-sff.c (ffffffff81721365)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8178066a)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81796509)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/input/serio/i8042.c (ffffffff82732120)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_wait_write
```
```
In drivers/rtc/rtc-cmos.c (ffffffff817d1444)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In arch/x86/pci/direct.c (ffffffff8273bc9e)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/fixup.c (ffffffff8186a1c1)
Location: arch/x86/include/asm/io.h:333
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff8186abb5)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_serverworks_get
  - arch/x86/pci/irq.c:elcr_set_level_irq
```
```
In arch/x86/pci/early.c (ffffffff8186c6e9)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - arch/x86/pci/early.c:early_dump_pci_devices
```
```
In arch/x86/lib/kaslr.c (ffffffff819e0d1c)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101caba)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In arch/x86/kernel/x86_init.c (ffffffff81034cd0)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/x86_init.c:default_get_nmi_reason
```
```
In arch/x86/kernel/i8259.c (ffffffff8103511a)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:i8259A_suspend
  - arch/x86/kernel/i8259.c:i8259A_suspend
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:i8259A_irq_pending
  - arch/x86/kernel/i8259.c:i8259A_irq_pending
```
```
In arch/x86/kernel/quirks.c (ffffffff81036a39)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff810390ae)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
```
```
In arch/x86/kernel/rtc.c (ffffffff81039ff8)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
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
In arch/x86/kernel/i8237.c (ffffffff828943fb)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/i8237.c:i8237A_init_ops
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff82899788)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff8105f39d)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff8289ab50)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
```
In arch/x86/kernel/mpparse.c (ffffffff8289bbb5)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8289dac0)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81065a73)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:irq_trigger
```
```
In arch/x86/kernel/early_printk.c (ffffffff81070680)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_in
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff8117690d)
Location: arch/x86/include/asm/io.h:342
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
In lib/iomap.c (ffffffff814e4306)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In drivers/pci/pci-sysfs.c (ffffffff81539a71)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/video/console/vgacon.c (ffffffff81566f65)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/osl.c (ffffffff81583e02)
Location: arch/x86/include/asm/io.h:342
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff81593669)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/processor_idle.c (ffffffff815e2538)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816573d3)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:io_serial_in
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff8165976e)
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
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81659c85)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_in
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff8165c042)
Location: arch/x86/include/asm/io.h:342
Inline: True
```
```
In drivers/char/mem.c (ffffffff81662572)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/char/mem.c:read_port
```
```
In drivers/ata/libata-sff.c (ffffffff81743c55)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817a6e8a)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817bce19)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/input/serio/i8042.c (ffffffff828eb634)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_wait_write
```
```
In drivers/rtc/rtc-cmos.c (ffffffff817f84f4)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In drivers/eisa/eisa-bus.c (ffffffff828edfbb)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/eisa/eisa-bus.c:eisa_init_device
```
```
In arch/x86/pci/direct.c (ffffffff828f5cb0)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/fixup.c (ffffffff8188a4b1)
Location: arch/x86/include/asm/io.h:342
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff8188ac85)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_serverworks_get
  - arch/x86/pci/irq.c:elcr_set_level_irq
```
```
In arch/x86/pci/early.c (ffffffff8188c676)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
```
```
In arch/x86/lib/kaslr.c (ffffffff81a1bccc)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101e5fa)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In arch/x86/kernel/x86_init.c (ffffffff81036c30)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/x86_init.c:default_get_nmi_reason
```
```
In arch/x86/kernel/i8259.c (ffffffff8103707a)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:i8259A_suspend
  - arch/x86/kernel/i8259.c:i8259A_suspend
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:i8259A_irq_pending
  - arch/x86/kernel/i8259.c:i8259A_irq_pending
```
```
In arch/x86/kernel/quirks.c (ffffffff81038a9b)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff8103b642)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
```
```
In arch/x86/kernel/rtc.c (ffffffff8103c5d6)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
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
In arch/x86/kernel/i8237.c (ffffffff828abbbe)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/i8237.c:i8237A_init_ops
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff828b148a)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff810627d8)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff828b28ae)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
```
In arch/x86/kernel/mpparse.c (ffffffff828b3883)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828b595a)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81069220)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:irq_trigger
```
```
In arch/x86/kernel/early_printk.c (ffffffff810746c0)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_in
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff811836fd)
Location: arch/x86/include/asm/io.h:339
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
In lib/iomap.c (ffffffff81510a62)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In drivers/pci/pci-sysfs.c (ffffffff81569391)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/video/console/vgacon.c (ffffffff815977a1)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/osl.c (ffffffff815b49e2)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff815c4633)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/processor_idle.c (ffffffff81614004)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8168d4c8)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:io_serial_in
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff8168edb7)
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
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8168f0f5)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_in
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81691718)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/char/mem.c (ffffffff81698128)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/char/mem.c:read_port
```
```
In drivers/ata/libata-sff.c (ffffffff8177f9f8)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817e609a)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817fc00f)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/input/serio/i8042.c (ffffffff82905be3)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_wait_write
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81839126)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In drivers/eisa/eisa-bus.c (ffffffff8290944a)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/eisa/eisa-bus.c:eisa_init_device
```
```
In arch/x86/pci/direct.c (ffffffff82911700)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/fixup.c (ffffffff818d4a91)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff818d55b5)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_serverworks_get
  - arch/x86/pci/irq.c:elcr_set_level_irq
```
```
In arch/x86/pci/early.c (ffffffff818d6fc4)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
```
```
In arch/x86/lib/kaslr.c (ffffffff81a8ba8e)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101ef7a)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In arch/x86/kernel/x86_init.c (ffffffff81037400)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/x86_init.c:default_get_nmi_reason
```
```
In arch/x86/kernel/i8259.c (ffffffff8103784a)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:i8259A_suspend
  - arch/x86/kernel/i8259.c:i8259A_suspend
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:i8259A_irq_pending
  - arch/x86/kernel/i8259.c:i8259A_irq_pending
```
```
In arch/x86/kernel/quirks.c (ffffffff8103926b)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff8103be12)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
```
```
In arch/x86/kernel/rtc.c (ffffffff8103cd96)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
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
In arch/x86/kernel/i8237.c (ffffffff828aebcc)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/i8237.c:i8237A_init_ops
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff828b48d9)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff81063048)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff828b5d00)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
```
In arch/x86/kernel/mpparse.c (ffffffff828b6cda)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828b8e1a)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81069ba0)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:irq_trigger
```
```
In arch/x86/kernel/early_printk.c (ffffffff81075690)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_in
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff828ca456)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff8118f56d)
Location: arch/x86/include/asm/io.h:339
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
In lib/iomap.c (ffffffff815314d2)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In drivers/pci/pci-sysfs.c (ffffffff8158a3c1)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/video/console/vgacon.c (ffffffff815b8b31)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/osl.c (ffffffff815d5c62)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff815e5873)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/processor_idle.c (ffffffff81635491)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816afa18)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:io_serial_in
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff816b15e7)
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
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816b1975)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_in
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff816b4208)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/char/mem.c (ffffffff816bad2e)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/char/mem.c:read_port
```
```
In drivers/ata/libata-sff.c (ffffffff817a36b8)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81816f5a)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8182ce5f)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/input/serio/i8042.c (ffffffff8290f61e)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_wait_write
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8186aa96)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In drivers/eisa/eisa-bus.c (ffffffff82912e4f)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/eisa/eisa-bus.c:eisa_init_device
```
```
In arch/x86/pci/direct.c (ffffffff8291b497)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/fixup.c (ffffffff81906e11)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff81907935)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_serverworks_get
  - arch/x86/pci/irq.c:elcr_set_level_irq
```
```
In arch/x86/pci/early.c (ffffffff81909344)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
```
```
In arch/x86/lib/kaslr.c (ffffffff81ac2d4e)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8102158a)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In arch/x86/kernel/x86_init.c (ffffffff810392b0)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/x86_init.c:default_get_nmi_reason
```
```
In arch/x86/kernel/i8259.c (ffffffff810396fa)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:i8259A_suspend
  - arch/x86/kernel/i8259.c:i8259A_suspend
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:i8259A_irq_pending
  - arch/x86/kernel/i8259.c:i8259A_irq_pending
```
```
In arch/x86/kernel/quirks.c (ffffffff8103bdac)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff8103ebcb)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:pit_calibrate_tsc
  - arch/x86/kernel/tsc.c:pit_calibrate_tsc
```
```
In arch/x86/kernel/rtc.c (ffffffff8103fc16)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
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
In arch/x86/kernel/i8237.c (ffffffff82cd3ab8)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/i8237.c:i8237A_init_ops
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff82cd9f24)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff81069140)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff82cdafc2)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
```
In arch/x86/kernel/mpparse.c (ffffffff82cdbe7a)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
```
```
In arch/x86/kernel/apic/vector.c (ffffffff82cdde04)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810715c4)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:irq_trigger
```
```
In arch/x86/kernel/early_printk.c (ffffffff8107c8a0)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_in
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff82cecb78)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff811a402d)
Location: arch/x86/include/asm/io.h:334
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
In lib/iomap.c (ffffffff81595772)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In arch/x86/lib/kaslr.c (ffffffff815ff3de)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
```
In drivers/pci/pci-sysfs.c (ffffffff8163153e)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/video/console/vgacon.c (ffffffff81663a57)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/osl.c (ffffffff8167f7f2)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff816915d8)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/processor_idle.c (ffffffff816e2065)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_idle_bm_check
  - drivers/acpi/processor_idle.c:acpi_idle_bm_check
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81760c07)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:io_serial_in
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff817648c0)
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
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81764ef5)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_in
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
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
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81767908)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/char/mem.c (ffffffff8176f111)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/char/mem.c:read_port
```
```
In drivers/ata/libata-sff.c (ffffffff81868d08)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff818e7fd9)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff818fdb5c)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
```
```
In drivers/input/serio/i8042.c (ffffffff819258ee)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_controller_init
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_kbd_write
  - drivers/input/serio/i8042.c:i8042_command
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_flush
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8193e616)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In drivers/eisa/eisa-bus.c (ffffffff82d25c1a)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/eisa/eisa-bus.c:decode_eisa_sig
```
```
In arch/x86/pci/direct.c (ffffffff82d31203)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/fixup.c (ffffffff81bb7311)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff81bb8055)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_serverworks_get
  - arch/x86/pci/irq.c:elcr_set_level_irq
```
```
In arch/x86/pci/early.c (ffffffff81bb9c23)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff81021d4a)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In arch/x86/kernel/x86_init.c (ffffffff81039b70)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/x86_init.c:default_get_nmi_reason
```
```
In arch/x86/kernel/i8259.c (ffffffff81039f5a)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:i8259A_suspend
  - arch/x86/kernel/i8259.c:i8259A_suspend
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:i8259A_irq_pending
  - arch/x86/kernel/i8259.c:i8259A_irq_pending
```
```
In arch/x86/kernel/quirks.c (ffffffff8103c51c)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff8103ec7b)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:pit_calibrate_tsc
  - arch/x86/kernel/tsc.c:pit_calibrate_tsc
```
```
In arch/x86/kernel/rtc.c (ffffffff8103fa96)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
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
In arch/x86/kernel/i8237.c (ffffffff82fbf8e1)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/i8237.c:i8237A_init_ops
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff82fc6342)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff8106adc0)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff82fc7416)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
```
In arch/x86/kernel/mpparse.c (ffffffff82fc82c5)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
```
```
In arch/x86/kernel/apic/vector.c (ffffffff82fca1c2)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81072bf3)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:irq_is_level
```
```
In arch/x86/kernel/early_printk.c (ffffffff8107c6f0)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_in
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff82fd91d2)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff811a118d)
Location: arch/x86/include/asm/io.h:334
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
In lib/iomap.c (ffffffff815b1202)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In arch/x86/lib/kaslr.c (ffffffff816243ae)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
```
In drivers/pci/pci-sysfs.c (ffffffff81656bde)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/video/console/vgacon.c (ffffffff816846e7)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/osl.c (ffffffff8169e2b2)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff816af318)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/processor_idle.c (ffffffff816fff31)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
  - drivers/acpi/processor_idle.c:acpi_idle_bm_check
  - drivers/acpi/processor_idle.c:acpi_idle_bm_check
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8177bc57)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:io_serial_in
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff8177f7e0)
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
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8177fdf5)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_in
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
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
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81782668)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/char/mem.c (ffffffff81789aea)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/char/mem.c:read_port
```
```
In drivers/ata/libata-sff.c (ffffffff81877b18)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff818f0fb9)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8190643c)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
```
```
In drivers/input/serio/i8042.c (ffffffff8192d44e)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_controller_init
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_kbd_write
  - drivers/input/serio/i8042.c:i8042_command
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_flush
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81944146)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In drivers/eisa/eisa-bus.c (ffffffff830141f6)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/eisa/eisa-bus.c:decode_eisa_sig
```
```
In arch/x86/pci/direct.c (ffffffff8302018d)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/fixup.c (ffffffff81bcc3a1)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff81bccc65)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_serverworks_get
  - arch/x86/pci/irq.c:elcr_set_level_irq
```
```
In arch/x86/pci/early.c (ffffffff81bce523)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff810240da)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In arch/x86/kernel/x86_init.c (ffffffff8103b640)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/x86_init.c:default_get_nmi_reason
```
```
In arch/x86/kernel/i8259.c (ffffffff8103ba2a)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:i8259A_suspend
  - arch/x86/kernel/i8259.c:i8259A_suspend
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:i8259A_irq_pending
  - arch/x86/kernel/i8259.c:i8259A_irq_pending
```
```
In arch/x86/kernel/quirks.c (ffffffff8103de69)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff810406f5)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
```
```
In arch/x86/kernel/rtc.c (ffffffff81041436)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
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
In arch/x86/kernel/i8237.c (ffffffff831c9f83)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/i8237.c:i8237A_init_ops
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff831d081c)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff8106b762)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff831d1cbe)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
```
In arch/x86/kernel/mpparse.c (ffffffff831d2b4e)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
```
```
In arch/x86/kernel/apic/vector.c (ffffffff831d4ae5)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81073336)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:irq_is_level
```
```
In arch/x86/kernel/early_printk.c (ffffffff8107d8a0)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_in
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff831e3a4b)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff811a1ded)
Location: arch/x86/include/asm/io.h:334
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
In lib/iomap.c (ffffffff815bc012)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In arch/x86/lib/kaslr.c (ffffffff81607d9e)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
```
In drivers/pci/pci-sysfs.c (ffffffff8163964e)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/video/console/vgacon.c (ffffffff81667677)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/osl.c (ffffffff81680ff2)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff81691928)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/processor_idle.c (ffffffff816e18ab)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81761857)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:io_serial_in
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81762fcc)
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
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81763725)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_in
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81765f68)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/char/mem.c (ffffffff8176d2b6)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/char/mem.c:read_port
```
```
In drivers/ata/libata-sff.c (ffffffff8185a2f8)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff818d47b9)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff818e9a4b)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
```
```
In drivers/input/serio/i8042.c (ffffffff8321cca4)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_kbd_write
  - drivers/input/serio/i8042.c:i8042_command
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_flush
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81927976)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In drivers/eisa/eisa-bus.c (ffffffff8321f179)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/eisa/eisa-bus.c:eisa_init_device
```
```
In arch/x86/pci/direct.c (ffffffff8322b385)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/fixup.c (ffffffff81bbfde1)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff81bc0695)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_serverworks_get
  - arch/x86/pci/irq.c:elcr_set_level_irq
```
```
In arch/x86/pci/early.c (ffffffff81bc1ed5)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff810284ab)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In arch/x86/kernel/x86_init.c (ffffffff810410a0)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/x86_init.c:default_get_nmi_reason
```
```
In arch/x86/kernel/i8259.c (ffffffff8104151a)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:i8259A_suspend
  - arch/x86/kernel/i8259.c:i8259A_suspend
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:i8259A_irq_pending
  - arch/x86/kernel/i8259.c:i8259A_irq_pending
```
```
In arch/x86/kernel/quirks.c (ffffffff81043beb)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff810467e5)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
```
```
In arch/x86/kernel/rtc.c (ffffffff810476c5)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
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
In arch/x86/kernel/i8237.c (ffffffff832ab384)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/i8237.c:i8237A_init_ops
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff832b2d64)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff81076250)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff832b4147)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
```
In arch/x86/kernel/mpparse.c (ffffffff832b54a6)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
```
```
In arch/x86/kernel/apic/vector.c (ffffffff832b766e)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8107f76e)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:irq_is_level
```
```
In arch/x86/kernel/early_printk.c (ffffffff8108c2d0)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_in
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff832c756d)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff811cb5ad)
Location: arch/x86/include/asm/io.h:334
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
In lib/iomap.c (ffffffff81622e62)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In arch/x86/lib/kaslr.c (ffffffff816769de)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
```
In drivers/pci/pci-sysfs.c (ffffffff816a9bea)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/video/console/vgacon.c (ffffffff816da8b7)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/osl.c (ffffffff816f5f82)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_port
```
```
In drivers/acpi/ec.c (ffffffff817073b1)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/processor_idle.c (ffffffff81759d0b)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff817e58b7)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:io_serial_in
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff817e721a)
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
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff817e7b05)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_in
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff817ea89f)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/char/mem.c (ffffffff817f2c46)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/char/mem.c:read_port
```
```
In drivers/ata/libata-sff.c (ffffffff818e8de8)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8196f089)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff819860eb)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
```
```
In drivers/input/serio/i8042.c (ffffffff819b17d9)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_controller_init
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_kbd_write
  - drivers/input/serio/i8042.c:i8042_command
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_flush
```
```
In drivers/rtc/rtc-cmos.c (ffffffff819ca766)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In drivers/eisa/eisa-bus.c (ffffffff833088ed)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/eisa/eisa-bus.c:eisa_init_device
```
```
In arch/x86/pci/direct.c (ffffffff83315b09)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/fixup.c (ffffffff81c8fd71)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff81c907b5)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_serverworks_get
  - arch/x86/pci/irq.c:pirq_esc_get
  - arch/x86/pci/irq.c:pirq_finali_lvl
  - arch/x86/pci/irq.c:pirq_finali_set
  - arch/x86/pci/irq.c:pirq_finali_get
  - arch/x86/pci/irq.c:elcr_set_level_irq
```
```
In arch/x86/pci/early.c (ffffffff81c924e5)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
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
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u8 inb(long unsigned int port);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/udbg_16550.c (c000000000068a74)
Location: arch/powerpc/include/asm/io-defs.h:23
Inline: True
Inline callers:
  - arch/powerpc/kernel/udbg_16550.c:udbg_uart_in_pio
```
```
In arch/powerpc/sysdev/i8259.c (c0000000000b9184)
Location: arch/powerpc/include/asm/io-defs.h:23
Inline: True
Inline callers:
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
In kernel/debug/kdb/kdb_keyboard.c (c000000000282f08)
Location: arch/powerpc/include/asm/io-defs.h:23
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state
  - kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state
  - kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state
  - kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state
  - kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state
  - kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
```
```
In lib/iomap.c (c0000000007e5a3c)
Location: arch/powerpc/include/asm/io-defs.h:23
Inline: True
```
```
In drivers/pci/pci-sysfs.c (c00000000086b738)
Location: arch/powerpc/include/asm/io-defs.h:23
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/video/console/vgacon.c (c00000000089cd44)
Location: arch/powerpc/include/asm/io-defs.h:23
Inline: True
Inline callers:
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
```
```
In drivers/tty/serial/8250/8250_port.c (c000000000933928)
Location: arch/powerpc/include/asm/io-defs.h:23
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:io_serial_in
  - drivers/tty/serial/8250/8250_port.c:io_serial_in
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (c0000000009384cc)
Location: arch/powerpc/include/asm/io-defs.h:23
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_in
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_in
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
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqopr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqopr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqopr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqopr
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
```
```
In drivers/tty/serial/8250/8250_early.c (c00000000093a6a0)
Location: arch/powerpc/include/asm/io-defs.h:23
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/char/mem.c (c000000000942864)
Location: arch/powerpc/include/asm/io-defs.h:23
Inline: True
Inline callers:
  - drivers/char/mem.c:read_port
```
```
In drivers/ata/libata-sff.c (c000000000a79b1c)
Location: arch/powerpc/include/asm/io-defs.h:23
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (c000000000b190c8)
Location: arch/powerpc/include/asm/io-defs.h:23
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (c000000000b3d328)
Location: arch/powerpc/include/asm/io-defs.h:23
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
```
```
In drivers/input/serio/i8042.c (c000000000b708a8)
Location: arch/powerpc/include/asm/io-defs.h:23
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_wait_write
  - drivers/input/serio/i8042.c:i8042_wait_write
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
```
```
In drivers/rtc/rtc-mc146818-lib.c (c000000000b8f044)
Location: arch/powerpc/include/asm/io-defs.h:23
Inline: True
Inline callers:
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
**Symbols:**

```
c000000000b70090-c000000000b70158: inb (STB_LOCAL)
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101f0da)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In arch/x86/kernel/x86_init.c (ffffffff81037560)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/x86_init.c:default_get_nmi_reason
```
```
In arch/x86/kernel/i8259.c (ffffffff810379aa)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:i8259A_suspend
  - arch/x86/kernel/i8259.c:i8259A_suspend
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:i8259A_irq_pending
  - arch/x86/kernel/i8259.c:i8259A_irq_pending
```
```
In arch/x86/kernel/quirks.c (ffffffff810393cb)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff8103bf72)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
```
```
In arch/x86/kernel/rtc.c (ffffffff8103cf16)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
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
In arch/x86/kernel/i8237.c (ffffffff8289cbeb)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/i8237.c:i8237A_init_ops
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff828a28f8)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff81062b38)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff828a3d0c)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
```
In arch/x86/kernel/mpparse.c (ffffffff828a4ce1)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828a6e21)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81069690)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:irq_trigger
```
```
In arch/x86/kernel/early_printk.c (ffffffff81074690)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_in
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff81187b8d)
Location: arch/x86/include/asm/io.h:339
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
In lib/iomap.c (ffffffff81529ab2)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157e251)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/video/console/vgacon.c (ffffffff815acc81)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/osl.c (ffffffff815c99c2)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff815d7763)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/processor_idle.c (ffffffff81604c81)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81675488)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:io_serial_in
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81677057)
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
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816773e5)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_in
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81679c68)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/char/mem.c (ffffffff8168078e)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/char/mem.c:read_port
```
```
In drivers/ata/libata-sff.c (ffffffff81768778)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817cf33a)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817e523f)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/input/serio/i8042.c (ffffffff828f63bd)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_wait_write
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8181d746)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In drivers/eisa/eisa-bus.c (ffffffff828f8c63)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/eisa/eisa-bus.c:eisa_init_device
```
```
In arch/x86/pci/direct.c (ffffffff829001a6)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/fixup.c (ffffffff818a61d1)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff818a6cf5)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_serverworks_get
  - arch/x86/pci/irq.c:elcr_set_level_irq
```
```
In arch/x86/pci/early.c (ffffffff818a8704)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
```
```
In arch/x86/lib/kaslr.c (ffffffff81a61b9e)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In arch/x86/kernel/x86_init.c (ffffffff81026f40)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/x86_init.c:default_get_nmi_reason
```
```
In arch/x86/kernel/i8259.c (ffffffff8102738a)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:i8259A_suspend
  - arch/x86/kernel/i8259.c:i8259A_suspend
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:i8259A_irq_pending
  - arch/x86/kernel/i8259.c:i8259A_irq_pending
```
```
In arch/x86/kernel/quirks.c (ffffffff81028cdb)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff8102b7c5)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
```
```
In arch/x86/kernel/rtc.c (ffffffff8102c5a6)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
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
In arch/x86/kernel/i8237.c (ffffffff82894d7e)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/i8237.c:i8237A_init_ops
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff8289aa3a)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff81052f08)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff8289be4e)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
```
In arch/x86/kernel/mpparse.c (ffffffff8289ce23)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8289ef29)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810599f0)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:irq_trigger
```
```
In arch/x86/kernel/early_printk.c (ffffffff810646c0)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_in
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff8117accd)
Location: arch/x86/include/asm/io.h:339
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
In lib/iomap.c (ffffffff81519d92)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In drivers/pci/pci-sysfs.c (ffffffff8156d021)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/video/console/vgacon.c (ffffffff8159be21)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/osl.c (ffffffff815b2a52)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff815c1323)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/processor_idle.c (ffffffff815efdef)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81654568)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:io_serial_in
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81656137)
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
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816564c5)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_in
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81658d58)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/char/mem.c (ffffffff8165e45e)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/char/mem.c:read_port
```
```
In drivers/ata/libata-sff.c (ffffffff817485d8)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817ad26a)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/input/serio/i8042.c (ffffffff828ed824)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_wait_write
```
```
In drivers/rtc/rtc-cmos.c (ffffffff817e4e16)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In drivers/eisa/eisa-bus.c (ffffffff828f074c)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/eisa/eisa-bus.c:eisa_init_device
```
```
In arch/x86/pci/direct.c (ffffffff828f87a4)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/fixup.c (ffffffff81860d01)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff81861815)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_serverworks_get
  - arch/x86/pci/irq.c:elcr_set_level_irq
```
```
In arch/x86/pci/early.c (ffffffff81863114)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
```
```
In arch/x86/lib/kaslr.c (ffffffff81a1ec0e)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101ef3a)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In arch/x86/kernel/x86_init.c (ffffffff810373c0)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/x86_init.c:default_get_nmi_reason
```
```
In arch/x86/kernel/i8259.c (ffffffff8103780a)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:i8259A_suspend
  - arch/x86/kernel/i8259.c:i8259A_suspend
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:i8259A_irq_pending
  - arch/x86/kernel/i8259.c:i8259A_irq_pending
```
```
In arch/x86/kernel/quirks.c (ffffffff8103922b)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff8103bdd2)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
```
```
In arch/x86/kernel/rtc.c (ffffffff8103cd56)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
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
In arch/x86/kernel/i8237.c (ffffffff828afbae)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/i8237.c:i8237A_init_ops
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff828b57f5)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff81062fe8)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff828b6c1c)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
```
In arch/x86/kernel/mpparse.c (ffffffff828b7bf1)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828b9d31)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81069b40)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:irq_trigger
```
```
In arch/x86/kernel/early_printk.c (ffffffff81074640)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_in
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff8118595d)
Location: arch/x86/include/asm/io.h:339
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
In lib/iomap.c (ffffffff81525b42)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157e111)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/video/console/vgacon.c (ffffffff815ad211)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/osl.c (ffffffff815c9f42)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff815d9b53)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/processor_idle.c (ffffffff81629771)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816a3858)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:io_serial_in
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff816a5427)
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
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816a57b5)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_in
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff816a8048)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/char/mem.c (ffffffff816aeb6e)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/char/mem.c:read_port
```
```
In drivers/ata/libata-sff.c (ffffffff81798538)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8180bdda)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81821cdf)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/input/serio/i8042.c (ffffffff8290a1b5)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_wait_write
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8185ec26)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In drivers/eisa/eisa-bus.c (ffffffff8290d49b)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/eisa/eisa-bus.c:eisa_init_device
```
```
In arch/x86/pci/direct.c (ffffffff829157a2)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/fixup.c (ffffffff818f7831)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff818f8355)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_serverworks_get
  - arch/x86/pci/irq.c:elcr_set_level_irq
```
```
In arch/x86/pci/early.c (ffffffff818f9d64)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
```
```
In arch/x86/lib/kaslr.c (ffffffff81acdf8e)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101f18a)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In arch/x86/kernel/x86_init.c (ffffffff810383c0)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/x86_init.c:default_get_nmi_reason
```
```
In arch/x86/kernel/i8259.c (ffffffff8103880a)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:probe_8259A
  - arch/x86/kernel/i8259.c:i8259A_suspend
  - arch/x86/kernel/i8259.c:i8259A_suspend
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/i8259.c:i8259A_irq_pending
  - arch/x86/kernel/i8259.c:i8259A_irq_pending
```
```
In arch/x86/kernel/quirks.c (ffffffff8103a22b)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff8103ce22)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
```
```
In arch/x86/kernel/rtc.c (ffffffff8103dde6)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
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
In arch/x86/kernel/i8237.c (ffffffff828afbdc)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/i8237.c:i8237A_init_ops
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff828b58dc)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff810645a8)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff828b6d03)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
```
In arch/x86/kernel/mpparse.c (ffffffff828b7cf2)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828b9e32)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:print_ICs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b2c0)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:irq_trigger
```
```
In arch/x86/kernel/early_printk.c (ffffffff810766a0)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_in
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff828cb493)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff811932ad)
Location: arch/x86/include/asm/io.h:339
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
In lib/iomap.c (ffffffff8153f4c2)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In drivers/pci/pci-sysfs.c (ffffffff815985c1)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/video/console/vgacon.c (ffffffff815c6cc1)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/osl.c (ffffffff815e3da2)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff815f3a13)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/processor_idle.c (ffffffff81643611)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816bdce8)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:io_serial_in
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff816bf887)
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
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816bfc15)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_in
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff816c24a8)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/char/mem.c (ffffffff816c90fe)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/char/mem.c:read_port
```
```
In drivers/ata/libata-sff.c (ffffffff817b23a8)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81825eea)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8183c3af)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/input/serio/i8042.c (ffffffff82910680)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_wait_write
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81879166)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In drivers/eisa/eisa-bus.c (ffffffff82913eb1)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/eisa/eisa-bus.c:eisa_init_device
```
```
In arch/x86/pci/direct.c (ffffffff8291c4f9)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/fixup.c (ffffffff81918931)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff81919455)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_pico_set
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_pico_get
  - arch/x86/pci/irq.c:pirq_serverworks_get
  - arch/x86/pci/irq.c:elcr_set_level_irq
```
```
In arch/x86/pci/early.c (ffffffff8191aec4)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
```
```
In arch/x86/lib/kaslr.c (ffffffff81ada49e)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
