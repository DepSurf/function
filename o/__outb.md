# Function: <code>__outb</code>

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
In arch/x86/kernel/nmi.c (ffffffff81e48136)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
```
```
In arch/x86/kernel/i8259.c (ffffffff810491d3)
Location: arch/x86/include/asm/shared/io.h:22
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
In arch/x86/kernel/quirks.c (ffffffff8104bdcc)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff8104f082)
Location: arch/x86/include/asm/shared/io.h:22
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
In arch/x86/kernel/rtc.c (ffffffff81050475)
Location: arch/x86/include/asm/shared/io.h:22
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
In arch/x86/kernel/i8237.c (ffffffff8105a788)
Location: arch/x86/include/asm/shared/io.h:22
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
In arch/x86/kernel/acpi/boot.c (ffffffff83464357)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff81084f9a)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff8346590b)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
```
In arch/x86/kernel/apic/vector.c (ffffffff834692e7)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
```
```
In arch/x86/kernel/early_printk.c (ffffffff8109cc12)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_out
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8347a39a)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In lib/iomap.c (ffffffff816f3062)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In arch/x86/lib/kaslr.c (ffffffff8179191f)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
```
In drivers/pci/pci-sysfs.c (ffffffff817cc500)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff817e27e9)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_disable_broadcom_boot_interrupt
  - drivers/pci/quirks.c:quirk_disable_broadcom_boot_interrupt
```
```
In drivers/video/console/vgacon.c (ffffffff8180353c)
Location: arch/x86/include/asm/shared/io.h:22
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
In drivers/video/fbdev/vesafb.c (ffffffff81821089)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff81822f7a)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff81834139)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81916335)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81923363)
Location: arch/x86/include/asm/shared/io.h:22
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
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81926b96)
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
In drivers/tty/serial/8250/8250_pci.c (ffffffff819276d5)
Location: arch/x86/include/asm/shared/io.h:22
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
In drivers/tty/serial/8250/8250_early.c (ffffffff8192a7dd)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/char/mem.c (ffffffff8193308a)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8194a1f3)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
```
```
In drivers/ata/libata-sff.c (ffffffff81a3a589)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81acab7b)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81ae4980)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff81b0cc8d)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
```
```
In drivers/input/serio/i8042.c (ffffffff81b10448)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_kbd_write
  - drivers/input/serio/i8042.c:__i8042_command
  - drivers/input/serio/i8042.c:__i8042_command
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81b2b8ad)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In drivers/eisa/eisa-bus.c (ffffffff834c1e8f)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
```
```
In drivers/clocksource/i8253.c (ffffffff81bc3f39)
Location: arch/x86/include/asm/shared/io.h:22
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
In arch/x86/pci/direct.c (ffffffff834d0232)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_check_type2
  - arch/x86/pci/direct.c:pci_check_type2
  - arch/x86/pci/direct.c:pci_check_type2
  - arch/x86/pci/direct.c:pci_check_type1
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
In arch/x86/pci/fixup.c (ffffffff81e3eeb4)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff81e3f949)
Location: arch/x86/include/asm/shared/io.h:22
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
In arch/x86/pci/early.c (ffffffff81e41ac3)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_byte
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
In arch/x86/kernel/nmi.c (ffffffff810526ae)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
```
```
In arch/x86/kernel/i8259.c (ffffffff810541d3)
Location: arch/x86/include/asm/shared/io.h:22
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
In arch/x86/kernel/quirks.c (ffffffff8105802b)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff8105c222)
Location: arch/x86/include/asm/shared/io.h:22
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
In arch/x86/kernel/rtc.c (ffffffff8105d8e5)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:rtc_cmos_write
  - arch/x86/kernel/rtc.c:rtc_cmos_write
  - arch/x86/kernel/rtc.c:rtc_cmos_read
```
```
In arch/x86/kernel/i8237.c (ffffffff81068528)
Location: arch/x86/include/asm/shared/io.h:22
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
In arch/x86/kernel/acpi/boot.c (ffffffff83e871db)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff8109830a)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff83e88ef7)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
```
In arch/x86/kernel/apic/vector.c (ffffffff83e8dddb)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
```
```
In arch/x86/kernel/early_printk.c (ffffffff810b3a72)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_out
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff83ea49ce)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In lib/iomap.c (ffffffff817e4f52)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In drivers/pci/pci-sysfs.c (ffffffff818ea720)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff819064b2)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_disable_broadcom_boot_interrupt
  - drivers/pci/quirks.c:quirk_disable_broadcom_boot_interrupt
```
```
In drivers/video/console/vgacon.c (ffffffff81931cfc)
Location: arch/x86/include/asm/shared/io.h:22
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
In drivers/video/fbdev/vesafb.c (ffffffff81951129)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff8195404a)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff81967bad)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81a71a1f)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a7fc7f)
Location: arch/x86/include/asm/shared/io.h:22
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
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81a839c6)
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
In drivers/tty/serial/8250/8250_pci.c (ffffffff81a84455)
Location: arch/x86/include/asm/shared/io.h:22
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
In drivers/tty/serial/8250/8250_early.c (ffffffff81a87c2d)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/char/mem.c (ffffffff81a91d9a)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81aad7d3)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
```
```
In drivers/ata/libata-sff.c (ffffffff81bbf9e9)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81c551bb)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81c70540)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff81c9cccd)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
```
```
In drivers/input/serio/i8042.c (ffffffff81ca0b38)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_kbd_write
  - drivers/input/serio/i8042.c:__i8042_command
  - drivers/input/serio/i8042.c:__i8042_command
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81cbf4fd)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In drivers/eisa/eisa-bus.c (ffffffff83f016c0)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
```
```
In drivers/clocksource/i8253.c (ffffffff81d695d9)
Location: arch/x86/include/asm/shared/io.h:22
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
In arch/x86/pci/direct.c (ffffffff83f140d9)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_check_type2
  - arch/x86/pci/direct.c:pci_check_type2
  - arch/x86/pci/direct.c:pci_check_type2
  - arch/x86/pci/direct.c:pci_check_type1
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
In arch/x86/pci/fixup.c (ffffffff82018ba4)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff820198d9)
Location: arch/x86/include/asm/shared/io.h:22
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
In arch/x86/pci/early.c (ffffffff8201c193)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_byte
```
```
In arch/x86/lib/kaslr.c (ffffffff8204f5ff)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
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
In arch/x86/kernel/nmi.c (ffffffff8105340e)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
```
```
In arch/x86/kernel/i8259.c (ffffffff81055233)
Location: arch/x86/include/asm/shared/io.h:22
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
In arch/x86/kernel/quirks.c (ffffffff810591cb)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff8105dd32)
Location: arch/x86/include/asm/shared/io.h:22
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
In arch/x86/kernel/rtc.c (ffffffff8105ef35)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:rtc_cmos_write
  - arch/x86/kernel/rtc.c:rtc_cmos_write
  - arch/x86/kernel/rtc.c:rtc_cmos_read
```
```
In arch/x86/kernel/i8237.c (ffffffff81069e48)
Location: arch/x86/include/asm/shared/io.h:22
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
In arch/x86/kernel/acpi/boot.c (ffffffff836aa77b)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff8109b399)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff836ac417)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
```
In arch/x86/kernel/apic/vector.c (ffffffff836b167b)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
```
```
In arch/x86/kernel/early_printk.c (ffffffff810b6b72)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_out
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff836c8d4e)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In lib/iomap.c (ffffffff81824f92)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In drivers/pci/pci-sysfs.c (ffffffff8192dc94)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff81949b02)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_disable_broadcom_boot_interrupt
  - drivers/pci/quirks.c:quirk_disable_broadcom_boot_interrupt
```
```
In drivers/video/console/vgacon.c (ffffffff8197616c)
Location: arch/x86/include/asm/shared/io.h:22
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
  - drivers/video/console/vgacon.c:vgacon_set_cursor_size
  - drivers/video/console/vgacon.c:vgacon_set_cursor_size
  - drivers/video/console/vgacon.c:vgacon_set_cursor_size
  - drivers/video/console/vgacon.c:vgacon_set_cursor_size
  - drivers/video/console/vgacon.c:vgacon_set_cursor_size
  - drivers/video/console/vgacon.c:vgacon_set_cursor_size
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff819975f1)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff8199a45a)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff819ae2b0)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81abc2cf)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81acb198)
Location: arch/x86/include/asm/shared/io.h:22
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
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81acf0a8)
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
In drivers/tty/serial/8250/8250_pci.c (ffffffff81acfc45)
Location: arch/x86/include/asm/shared/io.h:22
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
In drivers/tty/serial/8250/8250_early.c (ffffffff81ad3013)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/char/mem.c (ffffffff81add5f9)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81af906c)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
```
```
In drivers/ata/libata-sff.c (ffffffff81c174d9)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81cbc73b)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81cd7b31)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff81d040cf)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
```
```
In drivers/input/serio/i8042.c (ffffffff81d07e88)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_kbd_write
  - drivers/input/serio/i8042.c:__i8042_command
  - drivers/input/serio/i8042.c:__i8042_command
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81d26e5d)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In drivers/eisa/eisa-bus.c (ffffffff83727570)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
```
```
In drivers/clocksource/i8253.c (ffffffff81dd4ac9)
Location: arch/x86/include/asm/shared/io.h:22
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
In arch/x86/pci/direct.c (ffffffff8373a859)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_check_type2
  - arch/x86/pci/direct.c:pci_check_type2
  - arch/x86/pci/direct.c:pci_check_type2
  - arch/x86/pci/direct.c:pci_check_type1
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
In arch/x86/pci/fixup.c (ffffffff82099234)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff82099f59)
Location: arch/x86/include/asm/shared/io.h:22
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
In arch/x86/pci/early.c (ffffffff8209c833)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_byte
```
```
In arch/x86/lib/kaslr.c (ffffffff820cde7f)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
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
In arch/x86/kernel/nmi.c (ffffffff8105a62e)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
```
```
In arch/x86/kernel/i8259.c (ffffffff8105c3f3)
Location: arch/x86/include/asm/shared/io.h:22
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
In arch/x86/kernel/quirks.c (ffffffff810603eb)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/tsc.c (ffffffff81064df2)
Location: arch/x86/include/asm/shared/io.h:22
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
In arch/x86/kernel/rtc.c (ffffffff81065fe5)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:rtc_cmos_write
  - arch/x86/kernel/rtc.c:rtc_cmos_write
  - arch/x86/kernel/rtc.c:rtc_cmos_read
```
```
In arch/x86/kernel/i8237.c (ffffffff81071318)
Location: arch/x86/include/asm/shared/io.h:22
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
In arch/x86/kernel/acpi/boot.c (ffffffff838daf5b)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
  - arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger
```
```
In arch/x86/kernel/reboot.c (ffffffff810a29c6)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/early-quirks.c (ffffffff838dcba7)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
```
In arch/x86/kernel/apic/vector.c (ffffffff838e1b0b)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:print_PIC
```
```
In arch/x86/kernel/early_printk.c (ffffffff810bdfb2)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:io_serial_out
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff838f99ae)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In lib/iomap.c (ffffffff818769a2)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - lib/iomap.c:iowrite8
```
```
In drivers/pci/pci-sysfs.c (ffffffff81976614)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff81992eb2)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_disable_broadcom_boot_interrupt
  - drivers/pci/quirks.c:quirk_disable_broadcom_boot_interrupt
```
```
In drivers/video/console/vgacon.c (ffffffff819c01dc)
Location: arch/x86/include/asm/shared/io.h:22
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
  - drivers/video/console/vgacon.c:vgacon_set_cursor_size
  - drivers/video/console/vgacon.c:vgacon_set_cursor_size
  - drivers/video/console/vgacon.c:vgacon_set_cursor_size
  - drivers/video/console/vgacon.c:vgacon_set_cursor_size
  - drivers/video/console/vgacon.c:vgacon_set_cursor_size
  - drivers/video/console/vgacon.c:vgacon_set_cursor_size
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/osl.c (ffffffff819e28da)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff819f8730)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81b0f01f)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1fa68)
Location: arch/x86/include/asm/shared/io.h:22
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
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81b22168)
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
In drivers/tty/serial/8250/8250_early.c (ffffffff81b22a53)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81b259e6)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_moxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_moxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_moxa_init
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
In drivers/char/mem.c (ffffffff81b309e9)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81b4c68c)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
```
```
In drivers/ata/libata-sff.c (ffffffff81c6c589)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81d714ab)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81d8cb41)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff81db9c8f)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
```
```
In drivers/input/serio/i8042.c (ffffffff81dbdab8)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_kbd_write
  - drivers/input/serio/i8042.c:__i8042_command
  - drivers/input/serio/i8042.c:__i8042_command
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81ddcc4d)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_write
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
```
```
In drivers/eisa/eisa-bus.c (ffffffff8395b5b0)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
```
```
In drivers/clocksource/i8253.c (ffffffff81e8cc19)
Location: arch/x86/include/asm/shared/io.h:22
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
In arch/x86/pci/direct.c (ffffffff8396f0d9)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_check_type2
  - arch/x86/pci/direct.c:pci_check_type2
  - arch/x86/pci/direct.c:pci_check_type2
  - arch/x86/pci/direct.c:pci_check_type1
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
In arch/x86/pci/fixup.c (ffffffff82170714)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff82171689)
Location: arch/x86/include/asm/shared/io.h:22
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
In arch/x86/pci/early.c (ffffffff82174013)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_byte
```
```
In arch/x86/lib/kaslr.c (ffffffff821a869f)
Location: arch/x86/include/asm/shared/io.h:22
Inline: True
Inline callers:
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
