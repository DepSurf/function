# Function: <code>__inb</code>

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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (ffffffff8102cb17)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In arch/x86/kernel/x86_init.c (ffffffff81048c30)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/x86_init.c:default_get_nmi_reason
```
```
In arch/x86/kernel/i8259.c (ffffffff8104917a)
Location: arch/x86/include/asm/shared/io.h:22
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
In arch/x86/kernel/quirks.c (ffffffff8104bddb)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff8104f080)
Location: arch/x86/include/asm/shared/io.h:22
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
In arch/x86/kernel/rtc.c (ffffffff810505a9)
Location: arch/x86/include/asm/shared/io.h:22
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
In arch/x86/kernel/i8237.c (ffffffff8345b36b)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/i8237.c:i8237A_init_ops
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff834642f6)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff81084f90)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff83465913)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
```
In arch/x86/kernel/mpparse.c (ffffffff83467018)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8346929b)
Location: arch/x86/include/asm/shared/io.h:22
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8108e0fa)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:irq_is_level
```
```
In arch/x86/kernel/early_printk.c (ffffffff8109cbf0)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_in
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8347a39e)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff811ff27d)
Location: arch/x86/include/asm/shared/io.h:22
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
In lib/iomap.c (ffffffff816f2be2)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In arch/x86/lib/kaslr.c (ffffffff81791923)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
```
In drivers/pci/pci-sysfs.c (ffffffff817cca40)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/video/console/vgacon.c (ffffffff81803543)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/osl.c (ffffffff81822efc)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff81835365)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/processor_idle.c (ffffffff81f29672)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8192196e)
Location: arch/x86/include/asm/shared/io.h:22
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
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81926bb7)
Location: arch/x86/include/asm/shared/io.h:22
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
In drivers/tty/serial/8250/8250_pci.c (ffffffff81927625)
Location: arch/x86/include/asm/shared/io.h:22
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
In drivers/tty/serial/8250/8250_early.c (ffffffff8192a61a)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/char/mem.c (ffffffff81933180)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/char/mem.c:read_port
```
```
In drivers/ata/libata-sff.c (ffffffff81a3a588)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81acab90)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81ae1fc9)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
```
```
In drivers/input/serio/i8042.c (ffffffff81b103eb)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_controller_init
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_kbd_write
  - drivers/input/serio/i8042.c:__i8042_command
  - drivers/input/serio/i8042.c:__i8042_command
  - drivers/input/serio/i8042.c:__i8042_command
  - drivers/input/serio/i8042.c:__i8042_command
  - drivers/input/serio/i8042.c:__i8042_command
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_flush
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81b2b7f6)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In drivers/eisa/eisa-bus.c (ffffffff834c1ebd)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/eisa/eisa-bus.c:eisa_init_device
```
```
In arch/x86/pci/direct.c (ffffffff834d024a)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_check_type2
  - arch/x86/pci/direct.c:pci_check_type2
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/fixup.c (ffffffff81e3eec5)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff81e3f955)
Location: arch/x86/include/asm/shared/io.h:22
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
In arch/x86/pci/early.c (ffffffff81e41bd0)
Location: arch/x86/include/asm/shared/io.h:22
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
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (ffffffff81033c97)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In arch/x86/kernel/x86_init.c (ffffffff81053a60)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/x86_init.c:default_get_nmi_reason
```
```
In arch/x86/kernel/i8259.c (ffffffff81054157)
Location: arch/x86/include/asm/shared/io.h:22
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
In arch/x86/kernel/quirks.c (ffffffff8105803a)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff8105c220)
Location: arch/x86/include/asm/shared/io.h:22
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
In arch/x86/kernel/rtc.c (ffffffff8105d8bd)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:rtc_cmos_read
```
```
In arch/x86/kernel/i8237.c (ffffffff83e7b6b5)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/i8237.c:i8237A_init_ops
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff83e8719c)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff81098300)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff83e88f02)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
```
In arch/x86/kernel/mpparse.c (ffffffff83e8a9d2)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
```
```
In arch/x86/kernel/apic/vector.c (ffffffff83e8ddc3)
Location: arch/x86/include/asm/shared/io.h:22
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
In arch/x86/kernel/apic/io_apic.c (ffffffff810a286f)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:irq_is_level
```
```
In arch/x86/kernel/early_printk.c (ffffffff810b3a40)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_in
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff83ea49d5)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff81246b7d)
Location: arch/x86/include/asm/shared/io.h:22
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
In lib/iomap.c (ffffffff817e4a52)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In drivers/pci/pci-sysfs.c (ffffffff818ebe00)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/video/console/vgacon.c (ffffffff81931d03)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/osl.c (ffffffff81953fbc)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff81968d45)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/processor_idle.c (ffffffff820d54a2)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a7e1ae)
Location: arch/x86/include/asm/shared/io.h:22
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
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81a839e7)
Location: arch/x86/include/asm/shared/io.h:22
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
In drivers/tty/serial/8250/8250_pci.c (ffffffff81a84375)
Location: arch/x86/include/asm/shared/io.h:22
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
In drivers/tty/serial/8250/8250_early.c (ffffffff81a87a4a)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/char/mem.c (ffffffff81a91ea0)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/char/mem.c:read_port
```
```
In drivers/ata/libata-sff.c (ffffffff81bbf9e8)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81c551d0)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81c6d9c9)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
```
```
In drivers/input/serio/i8042.c (ffffffff81ca0adb)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_controller_init
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_kbd_write
  - drivers/input/serio/i8042.c:__i8042_command
  - drivers/input/serio/i8042.c:__i8042_command
  - drivers/input/serio/i8042.c:__i8042_command
  - drivers/input/serio/i8042.c:__i8042_command
  - drivers/input/serio/i8042.c:__i8042_command
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_flush
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81cbf666)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In drivers/eisa/eisa-bus.c (ffffffff83f016d4)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/eisa/eisa-bus.c:eisa_init_device
```
```
In arch/x86/pci/direct.c (ffffffff83f140f1)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_check_type2
  - arch/x86/pci/direct.c:pci_check_type2
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/fixup.c (ffffffff82018bb5)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff820198e5)
Location: arch/x86/include/asm/shared/io.h:22
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
In arch/x86/pci/early.c (ffffffff8201c2c0)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
```
```
In arch/x86/lib/kaslr.c (ffffffff8204f603)
Location: arch/x86/include/asm/shared/io.h:22
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
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (ffffffff81033c27)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In arch/x86/kernel/x86_init.c (ffffffff81054a40)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/x86_init.c:default_get_nmi_reason
```
```
In arch/x86/kernel/i8259.c (ffffffff810551b7)
Location: arch/x86/include/asm/shared/io.h:22
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
In arch/x86/kernel/quirks.c (ffffffff810591da)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff8105dd30)
Location: arch/x86/include/asm/shared/io.h:22
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
In arch/x86/kernel/rtc.c (ffffffff8105ef0d)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:rtc_cmos_read
```
```
In arch/x86/kernel/i8237.c (ffffffff8369dd45)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/i8237.c:i8237A_init_ops
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff836aa73c)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff8109b38f)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff836ac422)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
```
In arch/x86/kernel/mpparse.c (ffffffff836ae0a2)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
```
```
In arch/x86/kernel/apic/vector.c (ffffffff836b1663)
Location: arch/x86/include/asm/shared/io.h:22
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
In arch/x86/kernel/apic/io_apic.c (ffffffff810a590f)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:irq_is_level
```
```
In arch/x86/kernel/early_printk.c (ffffffff810b6b40)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_in
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff836c8d55)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff8125dbed)
Location: arch/x86/include/asm/shared/io.h:22
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
In lib/iomap.c (ffffffff81824a92)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In drivers/pci/pci-sysfs.c (ffffffff8192f310)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/video/console/vgacon.c (ffffffff81976173)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_set_cursor_size
  - drivers/video/console/vgacon.c:vgacon_set_cursor_size
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/osl.c (ffffffff8199a3bc)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff819af326)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/processor_idle.c (ffffffff82143b9d)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:io_idle
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81ac97ae)
Location: arch/x86/include/asm/shared/io.h:22
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
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81acf0ae)
Location: arch/x86/include/asm/shared/io.h:22
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
In drivers/tty/serial/8250/8250_pci.c (ffffffff81acfb65)
Location: arch/x86/include/asm/shared/io.h:22
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
In drivers/tty/serial/8250/8250_early.c (ffffffff81ad2e6a)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/char/mem.c (ffffffff81add713)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/char/mem.c:read_port
```
```
In drivers/ata/libata-sff.c (ffffffff81c174d8)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81cbc750)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81cd4fd6)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
```
```
In drivers/input/serio/i8042.c (ffffffff81d07e2b)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_controller_init
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_kbd_write
  - drivers/input/serio/i8042.c:__i8042_command
  - drivers/input/serio/i8042.c:__i8042_command
  - drivers/input/serio/i8042.c:__i8042_command
  - drivers/input/serio/i8042.c:__i8042_command
  - drivers/input/serio/i8042.c:__i8042_command
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_flush
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81d26fc6)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In drivers/eisa/eisa-bus.c (ffffffff83727584)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/eisa/eisa-bus.c:eisa_init_device
```
```
In arch/x86/pci/direct.c (ffffffff8373a871)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_check_type2
  - arch/x86/pci/direct.c:pci_check_type2
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/fixup.c (ffffffff82099245)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff82099f65)
Location: arch/x86/include/asm/shared/io.h:22
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
In arch/x86/pci/early.c (ffffffff8209c960)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
```
```
In arch/x86/lib/kaslr.c (ffffffff820cde83)
Location: arch/x86/include/asm/shared/io.h:22
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
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (ffffffff81039f27)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In arch/x86/kernel/x86_init.c (ffffffff8105bc80)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/x86_init.c:default_get_nmi_reason
```
```
In arch/x86/kernel/i8259.c (ffffffff8105be65)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
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
In arch/x86/kernel/quirks.c (ffffffff810603fa)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff81064df0)
Location: arch/x86/include/asm/shared/io.h:22
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
In arch/x86/kernel/rtc.c (ffffffff81065fbd)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:rtc_cmos_read
```
```
In arch/x86/kernel/i8237.c (ffffffff838cd905)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/i8237.c:i8237A_init_ops
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff838daf1c)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff810a29bc)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff838dcbb2)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
```
In arch/x86/kernel/mpparse.c (ffffffff838de622)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
```
```
In arch/x86/kernel/apic/vector.c (ffffffff838e1af3)
Location: arch/x86/include/asm/shared/io.h:22
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
In arch/x86/kernel/apic/io_apic.c (ffffffff810ac88f)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:irq_is_level
```
```
In arch/x86/kernel/early_printk.c (ffffffff810bdf80)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_in
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff838f99b5)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff81277b2d)
Location: arch/x86/include/asm/shared/io.h:22
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
In lib/iomap.c (ffffffff818764a2)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In drivers/pci/pci-sysfs.c (ffffffff81977c80)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/video/console/vgacon.c (ffffffff819c01e3)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_set_cursor_size
  - drivers/video/console/vgacon.c:vgacon_set_cursor_size
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/osl.c (ffffffff819e283c)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff819f97d6)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/processor_idle.c (ffffffff822262bd)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:io_idle
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1c88e)
Location: arch/x86/include/asm/shared/io.h:22
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
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81b2216e)
Location: arch/x86/include/asm/shared/io.h:22
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
In drivers/tty/serial/8250/8250_early.c (ffffffff81b228aa)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81b259f9)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_moxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_moxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_moxa_init
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
In drivers/char/mem.c (ffffffff81b30b03)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/char/mem.c:read_port
```
```
In drivers/ata/libata-sff.c (ffffffff81c6c588)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81d714c0)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81d89fb6)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
```
```
In drivers/input/serio/i8042.c (ffffffff81dbda5b)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_controller_init
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_kbd_write
  - drivers/input/serio/i8042.c:__i8042_command
  - drivers/input/serio/i8042.c:__i8042_command
  - drivers/input/serio/i8042.c:__i8042_command
  - drivers/input/serio/i8042.c:__i8042_command
  - drivers/input/serio/i8042.c:__i8042_command
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_flush
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81ddcdb6)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In drivers/eisa/eisa-bus.c (ffffffff8395b5c4)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/eisa/eisa-bus.c:eisa_init_device
```
```
In arch/x86/pci/direct.c (ffffffff8396f0f1)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_check_type2
  - arch/x86/pci/direct.c:pci_check_type2
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/fixup.c (ffffffff82170725)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff82171695)
Location: arch/x86/include/asm/shared/io.h:22
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
In arch/x86/pci/early.c (ffffffff82174140)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
```
```
In arch/x86/lib/kaslr.c (ffffffff821a86a3)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In <code>ppc64el</code>: Absent ⚠️
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
