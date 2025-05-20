# Function: <code>__set_fixmap</code>

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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81f5ceb5)
Location: arch/x86/include/asm/paravirt.h:683
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
```
```
In arch/x86/xen/enlighten.c (ffffffff8101d5dc)
Location: arch/x86/include/asm/paravirt.h:683
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_setup_shared_info
```
```
In arch/x86/kernel/traps.c (ffffffff81f659fe)
Location: arch/x86/include/asm/paravirt.h:683
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:trap_init
```
```
In arch/x86/kernel/alternative.c (ffffffff810367e4)
Location: arch/x86/include/asm/paravirt.h:683
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke
  - arch/x86/kernel/alternative.c:text_poke
  - arch/x86/kernel/alternative.c:text_poke
  - arch/x86/kernel/alternative.c:text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81f6a58a)
Location: arch/x86/include/asm/paravirt.h:683
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_probe
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81f71931)
Location: arch/x86/include/asm/paravirt.h:683
Inline: True
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81f72fbb)
Location: arch/x86/include/asm/paravirt.h:683
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
```
```
In arch/x86/kernel/pvclock.c (ffffffff81f749bd)
Location: arch/x86/include/asm/paravirt.h:683
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_init_vsyscall
```
```
In mm/early_ioremap.c (ffffffff81f8de5f)
Location: arch/x86/include/asm/paravirt.h:683
Inline: True
Inline callers:
  - mm/early_ioremap.c:__early_ioremap
  - mm/early_ioremap.c:early_iounmap
```
```
In drivers/tty/serial/earlycon.c (ffffffff81fa6d1e)
Location: arch/x86/include/asm/paravirt.h:683
Inline: True
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff81fb0d2a)
Location: arch/x86/include/asm/paravirt.h:683
Inline: True
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81f84e06)
Location: arch/x86/include/asm/paravirt.h:656
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
```
```
In arch/x86/xen/enlighten.c (ffffffff8101c979)
Location: arch/x86/include/asm/paravirt.h:656
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_setup_shared_info
```
```
In arch/x86/kernel/traps.c (ffffffff81f8d86d)
Location: arch/x86/include/asm/paravirt.h:656
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:trap_init
```
```
In arch/x86/kernel/alternative.c (ffffffff810359e1)
Location: arch/x86/include/asm/paravirt.h:656
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke
  - arch/x86/kernel/alternative.c:text_poke
  - arch/x86/kernel/alternative.c:text_poke
  - arch/x86/kernel/alternative.c:text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81f927e9)
Location: arch/x86/include/asm/paravirt.h:656
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_probe
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81f9a110)
Location: arch/x86/include/asm/paravirt.h:656
Inline: True
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105872f)
Location: arch/x86/include/asm/paravirt.h:656
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In mm/early_ioremap.c (ffffffff81fb864f)
Location: arch/x86/include/asm/paravirt.h:656
Inline: True
Inline callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
```
In drivers/tty/serial/earlycon.c (ffffffff81fd32c8)
Location: arch/x86/include/asm/paravirt.h:656
Inline: True
Inline callers:
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff81fdd857)
Location: arch/x86/include/asm/paravirt.h:656
Inline: True
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81fc021a)
Location: arch/x86/include/asm/paravirt.h:647
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
```
```
In arch/x86/xen/enlighten.c (ffffffff8101d0a9)
Location: arch/x86/include/asm/paravirt.h:647
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_setup_shared_info
```
```
In arch/x86/kernel/traps.c (ffffffff81fc8c81)
Location: arch/x86/include/asm/paravirt.h:647
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:trap_init
```
```
In arch/x86/kernel/alternative.c (ffffffff81035700)
Location: arch/x86/include/asm/paravirt.h:647
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke
  - arch/x86/kernel/alternative.c:text_poke
  - arch/x86/kernel/alternative.c:text_poke
  - arch/x86/kernel/alternative.c:text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81fcdab8)
Location: arch/x86/include/asm/paravirt.h:647
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_probe
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81fd55e7)
Location: arch/x86/include/asm/paravirt.h:647
Inline: True
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105b4bf)
Location: arch/x86/include/asm/paravirt.h:647
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In mm/early_ioremap.c (ffffffff81ff4fc1)
Location: arch/x86/include/asm/paravirt.h:647
Inline: True
Inline callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
```
In drivers/tty/serial/earlycon.c (ffffffff82010c88)
Location: arch/x86/include/asm/paravirt.h:647
Inline: True
Inline callers:
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff8201b46e)
Location: arch/x86/include/asm/paravirt.h:647
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff820a03fa)
Location: arch/x86/include/asm/paravirt.h:694
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8101fb1d)
Location: arch/x86/include/asm/paravirt.h:694
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_setup_shared_info
```
```
In arch/x86/kernel/traps.c (ffffffff820a937c)
Location: arch/x86/include/asm/paravirt.h:694
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:trap_init
```
```
In arch/x86/kernel/alternative.c (ffffffff810336cc)
Location: arch/x86/include/asm/paravirt.h:694
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke
  - arch/x86/kernel/alternative.c:text_poke
  - arch/x86/kernel/alternative.c:text_poke
  - arch/x86/kernel/alternative.c:text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff820ae107)
Location: arch/x86/include/asm/paravirt.h:694
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_probe
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103ec80)
Location: arch/x86/include/asm/paravirt.h:694
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/apic/apic.c (ffffffff820b6318)
Location: arch/x86/include/asm/paravirt.h:694
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:register_lapic_address
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105aa47)
Location: arch/x86/include/asm/paravirt.h:694
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In mm/early_ioremap.c (ffffffff820d7739)
Location: arch/x86/include/asm/paravirt.h:694
Inline: True
Inline callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
```
In drivers/tty/serial/earlycon.c (ffffffff820f27b8)
Location: arch/x86/include/asm/paravirt.h:694
Inline: True
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff820fdd09)
Location: arch/x86/include/asm/paravirt.h:694
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff826a6517)
Location: arch/x86/include/asm/paravirt.h:658
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8102078e)
Location: arch/x86/include/asm/paravirt.h:658
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_setup_shared_info
```
```
In arch/x86/kernel/alternative.c (ffffffff81035a04)
Location: arch/x86/include/asm/paravirt.h:658
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke
  - arch/x86/kernel/alternative.c:text_poke
  - arch/x86/kernel/alternative.c:text_poke
  - arch/x86/kernel/alternative.c:text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff826b4667)
Location: arch/x86/include/asm/paravirt.h:658
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_probe
```
```
In arch/x86/kernel/apic/apic.c (ffffffff826bcb14)
Location: arch/x86/include/asm/paravirt.h:658
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:register_lapic_address
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105ef87)
Location: arch/x86/include/asm/paravirt.h:658
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In mm/early_ioremap.c (ffffffff826e03b7)
Location: arch/x86/include/asm/paravirt.h:658
Inline: True
Inline callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
```
In drivers/acpi/apei/ghes.c (ffffffff8159f0f2)
Location: arch/x86/include/asm/paravirt.h:658
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
```
```
In drivers/tty/serial/earlycon.c (ffffffff826fbfb4)
Location: arch/x86/include/asm/paravirt.h:658
Inline: True
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff827075f5)
Location: arch/x86/include/asm/paravirt.h:658
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff826cf69d)
Location: arch/x86/include/asm/paravirt.h:663
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8102122a)
Location: arch/x86/include/asm/paravirt.h:663
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_setup_shared_info
```
```
In arch/x86/kernel/alternative.c (ffffffff8103698e)
Location: arch/x86/include/asm/paravirt.h:663
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke
  - arch/x86/kernel/alternative.c:text_poke
  - arch/x86/kernel/alternative.c:text_poke
  - arch/x86/kernel/alternative.c:text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff826dde79)
Location: arch/x86/include/asm/paravirt.h:663
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_probe
```
```
In arch/x86/kernel/apic/apic.c (ffffffff826e68db)
Location: arch/x86/include/asm/paravirt.h:663
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:register_lapic_address
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81061e2f)
Location: arch/x86/include/asm/paravirt.h:663
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In mm/early_ioremap.c (ffffffff8270a8c2)
Location: arch/x86/include/asm/paravirt.h:663
Inline: True
Inline callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
```
In drivers/acpi/apei/ghes.c (ffffffff815d6e0a)
Location: arch/x86/include/asm/paravirt.h:663
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
```
```
In drivers/tty/serial/earlycon.c (ffffffff827262c4)
Location: arch/x86/include/asm/paravirt.h:663
Inline: True
Inline callers:
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff827314f8)
Location: arch/x86/include/asm/paravirt.h:663
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff828856ca)
Location: arch/x86/include/asm/paravirt.h:641
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101e005)
Location: arch/x86/include/asm/paravirt.h:641
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8288af50)
Location: arch/x86/include/asm/paravirt.h:641
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
```
```
In arch/x86/kernel/alternative.c (ffffffff81037b9c)
Location: arch/x86/include/asm/paravirt.h:641
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke
  - arch/x86/kernel/alternative.c:text_poke
  - arch/x86/kernel/alternative.c:text_poke
  - arch/x86/kernel/alternative.c:text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff828942bc)
Location: arch/x86/include/asm/paravirt.h:641
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_probe
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8289d424)
Location: arch/x86/include/asm/paravirt.h:641
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:register_lapic_address
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81067b0f)
Location: arch/x86/include/asm/paravirt.h:641
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In mm/early_ioremap.c (ffffffff828c1aa6)
Location: arch/x86/include/asm/paravirt.h:641
Inline: True
Inline callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
```
In drivers/acpi/apei/ghes.c (ffffffff815eff73)
Location: arch/x86/include/asm/paravirt.h:641
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
```
```
In drivers/tty/serial/earlycon.c (ffffffff828de4a2)
Location: arch/x86/include/asm/paravirt.h:641
Inline: True
Inline callers:
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff828ea1ac)
Location: arch/x86/include/asm/paravirt.h:641
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8289c748)
Location: arch/x86/include/asm/paravirt.h:642
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101fb95)
Location: arch/x86/include/asm/paravirt.h:642
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a2410)
Location: arch/x86/include/asm/paravirt.h:642
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
```
```
In arch/x86/kernel/tboot.c (ffffffff828aba7b)
Location: arch/x86/include/asm/paravirt.h:642
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_probe
```
```
In arch/x86/kernel/apic/apic.c (ffffffff828b54d2)
Location: arch/x86/include/asm/paravirt.h:642
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:register_lapic_address
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b27c)
Location: arch/x86/include/asm/paravirt.h:642
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In mm/early_ioremap.c (ffffffff828dae8e)
Location: arch/x86/include/asm/paravirt.h:642
Inline: True
Inline callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
```
In drivers/acpi/apei/ghes.c (ffffffff81621d0c)
Location: arch/x86/include/asm/paravirt.h:642
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
```
```
In drivers/tty/serial/earlycon.c (ffffffff828f8ecb)
Location: arch/x86/include/asm/paravirt.h:642
Inline: True
Inline callers:
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff82904bd4)
Location: arch/x86/include/asm/paravirt.h:642
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8289f738)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
```
```
In arch/x86/xen/suspend_pv.c (ffffffff810204f5)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a5450)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
```
```
In arch/x86/kernel/tboot.c (ffffffff828aea89)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_probe
```
```
In arch/x86/kernel/apic/apic.c (ffffffff828b893c)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:register_lapic_address
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106bc1c)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In mm/early_ioremap.c (ffffffff828e32c4)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
```
In drivers/acpi/apei/ghes.c (ffffffff816437ec)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
```
```
In drivers/tty/serial/earlycon.c (ffffffff82901dce)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff8290e61a)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff82cc5c26)
Location: arch/x86/include/asm/paravirt.h:644
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
```
```
In arch/x86/xen/suspend_pv.c (ffffffff81022b55)
Location: arch/x86/include/asm/paravirt.h:644
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff82ccb740)
Location: arch/x86/include/asm/paravirt.h:644
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
```
```
In arch/x86/kernel/tboot.c (ffffffff82cd3975)
Location: arch/x86/include/asm/paravirt.h:644
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_probe
```
```
In arch/x86/kernel/apic/apic.c (ffffffff82cdd9cc)
Location: arch/x86/include/asm/paravirt.h:644
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:register_lapic_address
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81072f0d)
Location: arch/x86/include/asm/paravirt.h:644
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In mm/early_ioremap.c (ffffffff82d005b0)
Location: arch/x86/include/asm/paravirt.h:644
Inline: True
Inline callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f0c46)
Location: arch/x86/include/asm/paravirt.h:644
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
```
```
In drivers/tty/serial/earlycon.c (ffffffff82d19009)
Location: arch/x86/include/asm/paravirt.h:644
Inline: True
Inline callers:
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff82d227ae)
Location: arch/x86/include/asm/paravirt.h:644
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff82fb151a)
Location: arch/x86/include/asm/paravirt.h:542
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
```
```
In arch/x86/xen/suspend_pv.c (ffffffff81023129)
Location: arch/x86/include/asm/paravirt.h:542
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff82fb7623)
Location: arch/x86/include/asm/paravirt.h:542
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
```
```
In arch/x86/kernel/tboot.c (ffffffff82fbf79e)
Location: arch/x86/include/asm/paravirt.h:542
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_probe
```
```
In arch/x86/kernel/apic/apic.c (ffffffff82fc9d73)
Location: arch/x86/include/asm/paravirt.h:542
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:register_lapic_address
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8107436d)
Location: arch/x86/include/asm/paravirt.h:542
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In mm/early_ioremap.c (ffffffff82fecf75)
Location: arch/x86/include/asm/paravirt.h:542
Inline: True
Inline callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
```
In drivers/acpi/apei/ghes.c (ffffffff8170dee6)
Location: arch/x86/include/asm/paravirt.h:542
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
```
```
In drivers/tty/serial/earlycon.c (ffffffff83006c32)
Location: arch/x86/include/asm/paravirt.h:542
Inline: True
Inline callers:
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff830105a7)
Location: arch/x86/include/asm/paravirt.h:542
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff831bb6a5)
Location: arch/x86/include/asm/paravirt.h:573
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
```
```
In arch/x86/xen/suspend_pv.c (ffffffff81025439)
Location: arch/x86/include/asm/paravirt.h:573
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff831c1dcb)
Location: arch/x86/include/asm/paravirt.h:573
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
```
```
In arch/x86/kernel/tboot.c (ffffffff831c9f5a)
Location: arch/x86/include/asm/paravirt.h:573
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_probe
```
```
In arch/x86/kernel/apic/apic.c (ffffffff831d468c)
Location: arch/x86/include/asm/paravirt.h:573
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:register_lapic_address
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81074e1d)
Location: arch/x86/include/asm/paravirt.h:573
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In mm/early_ioremap.c (ffffffff831f77a9)
Location: arch/x86/include/asm/paravirt.h:573
Inline: True
Inline callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
```
In drivers/acpi/apei/ghes.c (ffffffff816ef686)
Location: arch/x86/include/asm/paravirt.h:573
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
```
```
In drivers/tty/serial/earlycon.c (ffffffff8321181c)
Location: arch/x86/include/asm/paravirt.h:573
Inline: True
Inline callers:
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff8321b472)
Location: arch/x86/include/asm/paravirt.h:573
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8329bbe2)
Location: arch/x86/include/asm/paravirt.h:573
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
```
```
In arch/x86/xen/suspend_pv.c (ffffffff81029949)
Location: arch/x86/include/asm/paravirt.h:573
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff832a2819)
Location: arch/x86/include/asm/paravirt.h:573
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
```
```
In arch/x86/kernel/tboot.c (ffffffff832ab35b)
Location: arch/x86/include/asm/paravirt.h:573
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_probe
```
```
In arch/x86/kernel/apic/apic.c (ffffffff832b7218)
Location: arch/x86/include/asm/paravirt.h:573
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:register_lapic_address
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81082153)
Location: arch/x86/include/asm/paravirt.h:573
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In mm/early_ioremap.c (ffffffff832de4ff)
Location: arch/x86/include/asm/paravirt.h:573
Inline: True
Inline callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
```
In drivers/acpi/apei/ghes.c (ffffffff817696e6)
Location: arch/x86/include/asm/paravirt.h:573
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
```
```
In drivers/tty/serial/earlycon.c (ffffffff832fa8df)
Location: arch/x86/include/asm/paravirt.h:573
Inline: True
Inline callers:
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff833051c6)
Location: arch/x86/include/asm/paravirt.h:573
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8344a3eb)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8102e1f9)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8345194f)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
```
```
In arch/x86/kernel/tboot.c (ffffffff8345b32c)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_probe
```
```
In arch/x86/kernel/apic/apic.c (ffffffff83468d8d)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:register_lapic_address
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81091cb3)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
```
```
In mm/early_ioremap.c (ffffffff83493d7a)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
```
In drivers/acpi/apei/ghes.c (ffffffff8189e058)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
```
```
In drivers/tty/serial/earlycon.c (ffffffff834b3208)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff834be2c5)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83e64a75)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
```
```
In arch/x86/xen/suspend_pv.c (ffffffff81035619)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff83e6e608)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
```
```
In arch/x86/kernel/tboot.c (ffffffff83e7b64e)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_probe
```
```
In arch/x86/kernel/apic/apic.c (ffffffff83e8d669)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:register_lapic_address
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a6abc)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In mm/early_ioremap.c (ffffffff83ec8013)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
```
In drivers/acpi/apei/ghes.c (ffffffff819e7018)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
```
```
In drivers/tty/serial/earlycon.c (ffffffff83eedc42)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - drivers/tty/serial/earlycon.c:register_earlycon
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff83efc170)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff836850f5)
Location: arch/x86/include/asm/paravirt.h:574
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
```
```
In arch/x86/xen/suspend_pv.c (ffffffff81035599)
Location: arch/x86/include/asm/paravirt.h:574
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8368f9f8)
Location: arch/x86/include/asm/paravirt.h:574
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
```
```
In arch/x86/kernel/tboot.c (ffffffff8369dcde)
Location: arch/x86/include/asm/paravirt.h:574
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_probe
```
```
In arch/x86/kernel/apic/apic.c (ffffffff836b0ef9)
Location: arch/x86/include/asm/paravirt.h:574
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:register_lapic_address
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a9cde)
Location: arch/x86/include/asm/paravirt.h:574
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_set_fixmap
```
```
In mm/early_ioremap.c (ffffffff836ed06e)
Location: arch/x86/include/asm/paravirt.h:574
Inline: True
Inline callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a2f728)
Location: arch/x86/include/asm/paravirt.h:574
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
```
```
In drivers/tty/serial/earlycon.c (ffffffff8371394a)
Location: arch/x86/include/asm/paravirt.h:574
Inline: True
Inline callers:
  - drivers/tty/serial/earlycon.c:register_earlycon
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff83721f7a)
Location: arch/x86/include/asm/paravirt.h:574
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff838b4295)
Location: arch/x86/include/asm/paravirt.h:572
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8103b799)
Location: arch/x86/include/asm/paravirt.h:572
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff838bf6e8)
Location: arch/x86/include/asm/paravirt.h:572
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
```
```
In arch/x86/kernel/tboot.c (ffffffff838cd89e)
Location: arch/x86/include/asm/paravirt.h:572
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_probe
```
```
In arch/x86/kernel/apic/apic.c (ffffffff838e0d7d)
Location: arch/x86/include/asm/paravirt.h:572
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_set_fixmap
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810b0d6e)
Location: arch/x86/include/asm/paravirt.h:572
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_set_fixmap
```
```
In mm/early_ioremap.c (ffffffff8392006e)
Location: arch/x86/include/asm/paravirt.h:572
Inline: True
Inline callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7aa68)
Location: arch/x86/include/asm/paravirt.h:572
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
```
```
In drivers/tty/serial/earlycon.c (ffffffff839473aa)
Location: arch/x86/include/asm/paravirt.h:572
Inline: True
Inline callers:
  - drivers/tty/serial/earlycon.c:register_earlycon
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff83955daa)
Location: arch/x86/include/asm/paravirt.h:572
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __set_fixmap(enum fixed_addresses idx, phys_addr_t phys, pgprot_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/mmu.c (ffff8000100ae5b0)
Location: arch/arm64/mm/mmu.c:864
Inline: True
Direct callers:
  - arch/arm64/kernel/insn.c:__aarch64_insn_write
  - arch/arm64/kernel/insn.c:__aarch64_insn_write
  - arch/arm64/mm/mmu.c:paging_init
  - arch/arm64/mm/mmu.c:paging_init
  - arch/arm64/mm/mmu.c:map_entry_trampoline
  - arch/arm64/mm/mmu.c:map_entry_trampoline
  - arch/arm64/mm/mmu.c:alloc_init_pud
  - arch/arm64/mm/mmu.c:alloc_init_pud
  - arch/arm64/mm/mmu.c:init_pmd
  - arch/arm64/mm/mmu.c:init_pmd
  - arch/arm64/mm/mmu.c:init_pmd
  - arch/arm64/mm/mmu.c:init_pmd
  - arch/arm64/mm/mmu.c:early_pgtable_alloc
  - arch/arm64/mm/mmu.c:early_pgtable_alloc
  - arch/arm64/mm/mmu.c:set_swapper_pgd
  - arch/arm64/mm/mmu.c:set_swapper_pgd
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
```
**Symbols:**

```
ffff8000100ae5b0-ffff8000100ae6ac: __set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __set_fixmap(enum fixed_addresses idx, phys_addr_t phys, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/mm/mmu.c (c031fab0)
Location: arch/arm/mm/mmu.c:406
Inline: False
Direct callers:
  - arch/arm/kernel/patch.c:__patch_text_real
  - arch/arm/kernel/patch.c:__patch_text_real
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
**Symbols:**

```
c031fab0-c031fbf0: __set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __set_fixmap(enum fixed_addresses idx, phys_addr_t phys, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/riscv/mm/init.c (ffffffe000003d9a)
Location: arch/riscv/mm/init.c:160
Inline: True
Inline callers:
  - arch/riscv/mm/init.c:paging_init
  - arch/riscv/mm/init.c:paging_init
  - arch/riscv/mm/init.c:get_pmd_virt
  - arch/riscv/mm/init.c:get_pmd_virt
  - arch/riscv/mm/init.c:get_pte_virt
  - arch/riscv/mm/init.c:get_pte_virt
Direct callers:
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
**Symbols:**

```
ffffffe0000b9b1a-ffffffe0000b9b70: __set_fixmap (STB_GLOBAL)
```
</details>
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8288d738)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
```
```
In arch/x86/xen/suspend_pv.c (ffffffff81020655)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff82893459)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
```
```
In arch/x86/kernel/tboot.c (ffffffff8289caa8)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_probe
```
```
In arch/x86/kernel/apic/apic.c (ffffffff828a6943)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:register_lapic_address
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b70c)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In mm/early_ioremap.c (ffffffff828cc178)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
```
In drivers/tty/serial/earlycon.c (ffffffff828e95b5)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff828f5774)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8288b659)
Location: arch/x86/include/asm/fixmap.h:163
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
```
```
In arch/x86/kernel/tboot.c (ffffffff82894c38)
Location: arch/x86/include/asm/fixmap.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_probe
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8289ea5c)
Location: arch/x86/include/asm/fixmap.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:register_lapic_address
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105ba3c)
Location: arch/x86/include/asm/fixmap.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In mm/early_ioremap.c (ffffffff828c4898)
Location: arch/x86/include/asm/fixmap.h:163
Inline: True
Inline callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
```
In drivers/tty/serial/earlycon.c (ffffffff828e0a5a)
Location: arch/x86/include/asm/fixmap.h:163
Inline: True
Inline callers:
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff828ed081)
Location: arch/x86/include/asm/fixmap.h:163
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff828a0738)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
```
```
In arch/x86/xen/suspend_pv.c (ffffffff810204b5)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a6450)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
```
```
In arch/x86/kernel/tboot.c (ffffffff828afa6b)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_probe
```
```
In arch/x86/kernel/apic/apic.c (ffffffff828b9853)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:register_lapic_address
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106bbbc)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In mm/early_ioremap.c (ffffffff828deef8)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
```
In drivers/acpi/apei/ghes.c (ffffffff8163762c)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
```
```
In drivers/tty/serial/earlycon.c (ffffffff828fd0f1)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff82909a15)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff828a073d)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
```
```
In arch/x86/xen/suspend_pv.c (ffffffff81020705)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a6424)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
```
```
In arch/x86/kernel/tboot.c (ffffffff828afa99)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_probe
```
```
In arch/x86/kernel/apic/apic.c (ffffffff828b9954)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:register_lapic_address
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106d2bc)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In mm/early_ioremap.c (ffffffff828e430f)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
```
In drivers/acpi/apei/ghes.c (ffffffff8165193c)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
```
```
In drivers/tty/serial/earlycon.c (ffffffff82902e30)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff8290f67c)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
