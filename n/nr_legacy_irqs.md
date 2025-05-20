# Function: <code>nr_legacy_irqs</code>

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
In arch/x86/kernel/time.c (ffffffff81f65ae5)
Location: arch/x86/include/asm/i8259.h:71
Inline: True
```
```
In arch/x86/kernel/i8259.c (ffffffff8103369c)
Location: arch/x86/include/asm/i8259.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:probe_8259A
```
```
In arch/x86/kernel/irqinit.c (ffffffff81f66afb)
Location: arch/x86/include/asm/i8259.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81f6dba1)
Location: arch/x86/include/asm/i8259.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81054f75)
Location: arch/x86/include/asm/i8259.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:arch_probe_nr_irqs
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/vector.c:setup_vector_irq
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810560d9)
Location: arch/x86/include/asm/i8259.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - arch/x86/kernel/apic/io_apic.c:arch_early_ioapic_init
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:disable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_ioapic_dest
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
```
```
In drivers/xen/events/events_base.c (ffffffff814c79a8)
Location: arch/x86/include/asm/i8259.h:71
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
```
```
In arch/x86/pci/xen.c (ffffffff816f752f)
Location: arch/x86/include/asm/i8259.h:71
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
  - arch/x86/pci/xen.c:pci_xen_initial_domain
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
In arch/x86/kernel/time.c (ffffffff81f8d954)
Location: arch/x86/include/asm/i8259.h:71
Inline: True
```
```
In arch/x86/kernel/i8259.c (ffffffff8103286c)
Location: arch/x86/include/asm/i8259.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:probe_8259A
```
```
In arch/x86/kernel/irqinit.c (ffffffff81f8ed74)
Location: arch/x86/include/asm/i8259.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81f96c30)
Location: arch/x86/include/asm/i8259.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81055a86)
Location: arch/x86/include/asm/i8259.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:setup_vector_irq
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/vector.c:arch_probe_nr_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81057edf)
Location: arch/x86/include/asm/i8259.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:setup_ioapic_dest
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:disable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - arch/x86/kernel/apic/io_apic.c:arch_early_ioapic_init
```
```
In drivers/xen/events/events_base.c (ffffffff81519892)
Location: arch/x86/include/asm/i8259.h:71
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_free_irq
```
```
In arch/x86/pci/xen.c (ffffffff8175c1cf)
Location: arch/x86/include/asm/i8259.h:71
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
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
In arch/x86/kernel/time.c (ffffffff81fc8d68)
Location: arch/x86/include/asm/i8259.h:71
Inline: True
```
```
In arch/x86/kernel/i8259.c (ffffffff810324dc)
Location: arch/x86/include/asm/i8259.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:probe_8259A
```
```
In arch/x86/kernel/irqinit.c (ffffffff81fca103)
Location: arch/x86/include/asm/i8259.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81fd212e)
Location: arch/x86/include/asm/i8259.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81058826)
Location: arch/x86/include/asm/i8259.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:setup_vector_irq
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/vector.c:arch_probe_nr_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105ac6f)
Location: arch/x86/include/asm/i8259.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:setup_ioapic_dest
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:disable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - arch/x86/kernel/apic/io_apic.c:arch_early_ioapic_init
```
```
In drivers/xen/events/events_base.c (ffffffff81545d62)
Location: arch/x86/include/asm/i8259.h:71
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_free_irq
```
```
In arch/x86/pci/xen.c (ffffffff8178873f)
Location: arch/x86/include/asm/i8259.h:71
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
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
In arch/x86/kernel/time.c (ffffffff820a9484)
Location: arch/x86/include/asm/i8259.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/time.c:hpet_time_init
```
```
In arch/x86/kernel/i8259.c (ffffffff8103071c)
Location: arch/x86/include/asm/i8259.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:probe_8259A
```
```
In arch/x86/kernel/irqinit.c (ffffffff820aa889)
Location: arch/x86/include/asm/i8259.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff820b1fba)
Location: arch/x86/include/asm/i8259.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81058006)
Location: arch/x86/include/asm/i8259.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:setup_vector_irq
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/vector.c:arch_probe_nr_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105a25f)
Location: arch/x86/include/asm/i8259.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:setup_ioapic_dest
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:disable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - arch/x86/kernel/apic/io_apic.c:arch_early_ioapic_init
```
```
In drivers/xen/events/events_base.c (ffffffff81559b98)
Location: arch/x86/include/asm/i8259.h:71
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_free_irq
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8171d78d)
Location: arch/x86/include/asm/i8259.h:71
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
```
In arch/x86/pci/xen.c (ffffffff817a7841)
Location: arch/x86/include/asm/i8259.h:71
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
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
In arch/x86/kernel/time.c (ffffffff826afffc)
Location: arch/x86/include/asm/i8259.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/time.c:hpet_time_init
```
```
In arch/x86/kernel/i8259.c (ffffffff81032abc)
Location: arch/x86/include/asm/i8259.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:probe_8259A
```
```
In arch/x86/kernel/irqinit.c (ffffffff826b1006)
Location: arch/x86/include/asm/i8259.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff826b9563)
Location: arch/x86/include/asm/i8259.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8105c5f1)
Location: arch/x86/include/asm/i8259.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_online
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:arch_probe_nr_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105e74e)
Location: arch/x86/include/asm/i8259.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:disable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - arch/x86/kernel/apic/io_apic.c:arch_early_ioapic_init
```
```
In drivers/xen/events/events_base.c (ffffffff815bdfe8)
Location: arch/x86/include/asm/i8259.h:72
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_free_irq
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8178ea0d)
Location: arch/x86/include/asm/i8259.h:72
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
```
In arch/x86/pci/xen.c (ffffffff8181eb51)
Location: arch/x86/include/asm/i8259.h:72
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
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
In arch/x86/kernel/i8259.c (ffffffff81033de0)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:probe_8259A
```
```
In arch/x86/kernel/irqinit.c (ffffffff826da6c4)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff826e32ba)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
```
```
In arch/x86/kernel/apic/vector.c (ffffffff826e6f35)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:lapic_online
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:arch_probe_nr_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810616f0)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - arch/x86/kernel/apic/io_apic.c:arch_early_ioapic_init
```
```
In drivers/xen/events/events_base.c (ffffffff815f6638)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_free_irq
```
```
In drivers/rtc/rtc-cmos.c (ffffffff817d106b)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
```
In arch/x86/pci/xen.c (ffffffff81868c7d)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
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
In arch/x86/kernel/i8259.c (ffffffff81035130)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:probe_8259A
```
```
In arch/x86/kernel/irqinit.c (ffffffff82890aa6)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
  - arch/x86/kernel/irqinit.c:init_IRQ
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff82899c2a)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8289da7e)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:lapic_online
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:arch_probe_nr_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810673d0)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - arch/x86/kernel/apic/io_apic.c:irq_trigger
  - arch/x86/kernel/apic/io_apic.c:arch_early_ioapic_init
```
```
In drivers/xen/events/events_base.c (ffffffff816116d8)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_free_irq
```
```
In drivers/rtc/rtc-cmos.c (ffffffff817f839b)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
```
In arch/x86/pci/xen.c (ffffffff81888cfd)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
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
In arch/x86/kernel/i8259.c (ffffffff81037090)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:probe_8259A
```
```
In arch/x86/kernel/irqinit.c (ffffffff828a8019)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
  - arch/x86/kernel/irqinit.c:init_IRQ
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff828b1937)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828b5918)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:lapic_online
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:arch_probe_nr_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106ab70)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - arch/x86/kernel/apic/io_apic.c:irq_trigger
  - arch/x86/kernel/apic/io_apic.c:arch_early_ioapic_init
```
```
In drivers/xen/events/events_base.c (ffffffff816454a6)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_free_irq
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81838fcd)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
```
In arch/x86/pci/xen.c (ffffffff818d363d)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
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
In arch/x86/kernel/i8259.c (ffffffff81037860)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:probe_8259A
```
```
In arch/x86/kernel/irqinit.c (ffffffff828ab07b)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
  - arch/x86/kernel/irqinit.c:init_IRQ
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff828b4d86)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828b8dd9)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:lapic_online
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:arch_probe_nr_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b510)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - arch/x86/kernel/apic/io_apic.c:irq_trigger
  - arch/x86/kernel/apic/io_apic.c:arch_early_ioapic_init
```
```
In drivers/xen/events/events_base.c (ffffffff81667a46)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_free_irq
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8186a93d)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
```
In arch/x86/pci/xen.c (ffffffff819059bd)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
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
In arch/x86/kernel/i8259.c (ffffffff81039710)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:probe_8259A
```
```
In arch/x86/kernel/irqinit.c (ffffffff82cd02d0)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
  - arch/x86/kernel/irqinit.c:init_IRQ
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff82cd9a4e)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
```
```
In arch/x86/kernel/apic/vector.c (ffffffff82cdddc2)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:lapic_online
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:arch_probe_nr_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8107297a)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - arch/x86/kernel/apic/io_apic.c:irq_trigger
  - arch/x86/kernel/apic/io_apic.c:arch_early_ioapic_init
```
```
In drivers/xen/events/events_base.c (ffffffff81715ffd)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:restore_cpu_ipis
  - drivers/xen/events/events_base.c:restore_cpu_virqs
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
  - drivers/xen/events/events_base.c:cpu_from_evtchn
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8193e5bd)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
```
In arch/x86/pci/xen.c (ffffffff81bb5f9d)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
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
In arch/x86/kernel/i8259.c (ffffffff81039f70)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:probe_8259A
```
```
In arch/x86/kernel/irqinit.c (ffffffff82fbc110)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
  - arch/x86/kernel/irqinit.c:init_IRQ
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff82fc5fa3)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
```
```
In arch/x86/kernel/apic/vector.c (ffffffff82fca180)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:lapic_online
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:arch_probe_nr_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81073e01)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - arch/x86/kernel/apic/io_apic.c:irq_is_level
  - arch/x86/kernel/apic/io_apic.c:arch_early_ioapic_init
```
```
In drivers/xen/events/events_base.c (ffffffff8173305d)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:restore_cpu_ipis
  - drivers/xen/events/events_base.c:restore_cpu_virqs
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_ack_dynirq
  - drivers/xen/events/events_base.c:mask_ack_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
  - drivers/xen/events/events_base.c:cpu_from_evtchn
```
```
In drivers/rtc/rtc-cmos.c (ffffffff819453dd)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
```
In arch/x86/pci/xen.c (ffffffff81bcb01d)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
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
In arch/x86/kernel/i8259.c (ffffffff8103ba40)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:probe_8259A
```
```
In arch/x86/kernel/irqinit.c (ffffffff831c68bb)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
  - arch/x86/kernel/irqinit.c:init_IRQ
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff831d06be)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
```
```
In arch/x86/kernel/apic/vector.c (ffffffff831d4aa3)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:lapic_online
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_update_legacy_vectors
  - arch/x86/kernel/apic/vector.c:arch_probe_nr_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8107489a)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - arch/x86/kernel/apic/io_apic.c:irq_is_level
  - arch/x86/kernel/apic/io_apic.c:arch_early_ioapic_init
```
```
In drivers/xen/events/events_base.c (ffffffff817198c8)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_ack_dynirq
  - drivers/xen/events/events_base.c:mask_ack_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
  - drivers/xen/events/events_base.c:cpu_from_evtchn
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81928bdd)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
```
In arch/x86/pci/xen.c (ffffffff81bbe95d)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
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
In arch/x86/kernel/i8259.c (ffffffff81041530)
Location: arch/x86/include/asm/i8259.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:probe_8259A
```
```
In arch/x86/kernel/irqinit.c (ffffffff832a76e1)
Location: arch/x86/include/asm/i8259.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
  - arch/x86/kernel/irqinit.c:init_IRQ
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff832b2bb4)
Location: arch/x86/include/asm/i8259.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
```
```
In arch/x86/kernel/apic/vector.c (ffffffff832b762f)
Location: arch/x86/include/asm/i8259.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:lapic_online
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_update_legacy_vectors
  - arch/x86/kernel/apic/vector.c:arch_probe_nr_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81080d1e)
Location: arch/x86/include/asm/i8259.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - arch/x86/kernel/apic/io_apic.c:irq_is_level
  - arch/x86/kernel/apic/io_apic.c:arch_early_ioapic_init
```
```
In drivers/xen/events/events_base.c (ffffffff8179777c)
Location: arch/x86/include/asm/i8259.h:80
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_ack_dynirq
  - drivers/xen/events/events_base.c:mask_ack_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:pirq_needs_eoi_flag
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
  - drivers/xen/events/events_base.c:cpu_from_evtchn
```
```
In drivers/rtc/rtc-cmos.c (ffffffff819cb59d)
Location: arch/x86/include/asm/i8259.h:80
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
```
In arch/x86/pci/xen.c (ffffffff81c8e8bd)
Location: arch/x86/include/asm/i8259.h:80
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
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
In arch/x86/kernel/i8259.c (ffffffff81049190)
Location: arch/x86/include/asm/i8259.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:probe_8259A
```
```
In arch/x86/kernel/irqinit.c (ffffffff83456a28)
Location: arch/x86/include/asm/i8259.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
  - arch/x86/kernel/irqinit.c:init_IRQ
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff83463b8b)
Location: arch/x86/include/asm/i8259.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8346925c)
Location: arch/x86/include/asm/i8259.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:lapic_online
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_update_legacy_vectors
  - arch/x86/kernel/apic/vector.c:arch_probe_nr_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8108ff77)
Location: arch/x86/include/asm/i8259.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - arch/x86/kernel/apic/io_apic.c:irq_is_level
  - arch/x86/kernel/apic/io_apic.c:arch_early_ioapic_init
```
```
In drivers/xen/events/events_base.c (ffffffff818d07eb)
Location: arch/x86/include/asm/i8259.h:80
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_ack_dynirq
  - drivers/xen/events/events_base.c:mask_ack_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:pirq_needs_eoi_flag
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
  - drivers/xen/events/events_base.c:cpu_from_evtchn
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81b2d245)
Location: arch/x86/include/asm/i8259.h:80
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
```
In arch/x86/pci/xen.c (ffffffff81e3d971)
Location: arch/x86/include/asm/i8259.h:80
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
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
In arch/x86/kernel/i8259.c (ffffffff81054183)
Location: arch/x86/include/asm/i8259.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:probe_8259A
```
```
In arch/x86/kernel/irqinit.c (ffffffff83e75056)
Location: arch/x86/include/asm/i8259.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
  - arch/x86/kernel/irqinit.c:init_IRQ
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff83e868f0)
Location: arch/x86/include/asm/i8259.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
```
```
In arch/x86/kernel/apic/vector.c (ffffffff83e8dd95)
Location: arch/x86/include/asm/i8259.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:lapic_online
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_update_legacy_vectors
  - arch/x86/kernel/apic/vector.c:arch_probe_nr_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a4f37)
Location: arch/x86/include/asm/i8259.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - arch/x86/kernel/apic/io_apic.c:irq_is_level
  - arch/x86/kernel/apic/io_apic.c:arch_early_ioapic_init
```
```
In drivers/xen/events/events_base.c (ffffffff81a21fea)
Location: arch/x86/include/asm/i8259.h:80
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_ack_dynirq
  - drivers/xen/events/events_base.c:mask_ack_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:pirq_needs_eoi_flag
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
  - drivers/xen/events/events_base.c:cpu_from_evtchn
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81cc15a3)
Location: arch/x86/include/asm/i8259.h:80
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
```
In arch/x86/pci/xen.c (ffffffff82016e74)
Location: arch/x86/include/asm/i8259.h:80
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
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
In arch/x86/kernel/i8259.c (ffffffff810551e3)
Location: arch/x86/include/asm/i8259.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:probe_8259A
```
```
In arch/x86/kernel/irqinit.c (ffffffff83696b36)
Location: arch/x86/include/asm/i8259.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff836a9e30)
Location: arch/x86/include/asm/i8259.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
```
```
In arch/x86/kernel/apic/vector.c (ffffffff836b1635)
Location: arch/x86/include/asm/i8259.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:lapic_online
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_update_legacy_vectors
  - arch/x86/kernel/apic/vector.c:arch_probe_nr_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a801d)
Location: arch/x86/include/asm/i8259.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - arch/x86/kernel/apic/io_apic.c:irq_is_level
  - arch/x86/kernel/apic/io_apic.c:arch_early_ioapic_init
```
```
In drivers/xen/events/events_base.c (ffffffff81a6b381)
Location: arch/x86/include/asm/i8259.h:80
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_ack_dynirq
  - drivers/xen/events/events_base.c:mask_ack_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:pirq_needs_eoi_flag
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
  - drivers/xen/events/events_base.c:cpu_from_evtchn
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81d28f73)
Location: arch/x86/include/asm/i8259.h:80
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
```
In arch/x86/pci/xen.c (ffffffff8209721a)
Location: arch/x86/include/asm/i8259.h:80
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
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
In arch/x86/kernel/i8259.c (ffffffff8105c57f)
Location: arch/x86/include/asm/i8259.h:82
Inline: True
```
```
In arch/x86/kernel/irqinit.c (ffffffff838c6856)
Location: arch/x86/include/asm/i8259.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff838da5d0)
Location: arch/x86/include/asm/i8259.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
```
```
In arch/x86/kernel/apic/vector.c (ffffffff838e1ac5)
Location: arch/x86/include/asm/i8259.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_PIC
  - arch/x86/kernel/apic/vector.c:lapic_online
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_update_legacy_vectors
  - arch/x86/kernel/apic/vector.c:arch_probe_nr_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810af0ac)
Location: arch/x86/include/asm/i8259.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - arch/x86/kernel/apic/io_apic.c:irq_is_level
  - arch/x86/kernel/apic/io_apic.c:arch_early_ioapic_init
```
```
In drivers/xen/events/events_base.c (ffffffff81abd450)
Location: arch/x86/include/asm/i8259.h:82
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_ack_dynirq
  - drivers/xen/events/events_base.c:mask_ack_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:xen_allocate_irq_dynamic
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:notify_remote_via_irq
  - drivers/xen/events/events_base.c:irq_evtchn_from_virq
  - drivers/xen/events/events_base.c:delayed_free_irq
  - drivers/xen/events/events_base.c:delayed_free_irq
  - drivers/xen/events/events_base.c:evtchn_to_info
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81ddedf3)
Location: arch/x86/include/asm/i8259.h:82
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
```
In arch/x86/pci/xen.c (ffffffff8216e6fa)
Location: arch/x86/include/asm/i8259.h:82
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: arch/arm64/include/asm/irq.h:11
Inline: True
```
</details>
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/i8259.c (ffffffff810379c0)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:probe_8259A
```
```
In arch/x86/kernel/irqinit.c (ffffffff8289908d)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
  - arch/x86/kernel/irqinit.c:init_IRQ
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff828a2da5)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828a6de0)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:lapic_online
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:arch_probe_nr_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b000)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - arch/x86/kernel/apic/io_apic.c:irq_trigger
  - arch/x86/kernel/apic/io_apic.c:arch_early_ioapic_init
```
```
In drivers/xen/events/events_base.c (ffffffff8162d776)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_free_irq
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8181d5ed)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
```
In arch/x86/pci/xen.c (ffffffff818a4d7d)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
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
In arch/x86/kernel/i8259.c (ffffffff810273a0)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:probe_8259A
```
```
In arch/x86/kernel/irqinit.c (ffffffff82891388)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
  - arch/x86/kernel/irqinit.c:init_IRQ
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff8289aee7)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8289eee8)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:lapic_online
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:arch_probe_nr_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105b353)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - arch/x86/kernel/apic/io_apic.c:irq_trigger
  - arch/x86/kernel/apic/io_apic.c:arch_early_ioapic_init
```
```
In drivers/rtc/rtc-cmos.c (ffffffff817e4ccd)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
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
In arch/x86/kernel/i8259.c (ffffffff81037820)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:probe_8259A
```
```
In arch/x86/kernel/irqinit.c (ffffffff828ac06d)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
  - arch/x86/kernel/irqinit.c:init_IRQ
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff828b5ca2)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828b9cf0)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:lapic_online
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:arch_probe_nr_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b4b0)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - arch/x86/kernel/apic/io_apic.c:irq_trigger
  - arch/x86/kernel/apic/io_apic.c:arch_early_ioapic_init
```
```
In drivers/xen/events/events_base.c (ffffffff8165b886)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_free_irq
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8185eacd)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
```
In arch/x86/pci/xen.c (ffffffff818f63dd)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
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
In arch/x86/kernel/i8259.c (ffffffff81038820)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:probe_8259A
```
```
In arch/x86/kernel/irqinit.c (ffffffff828ac08b)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
  - arch/x86/kernel/irqinit.c:init_IRQ
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff828b5d89)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828b9df1)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:lapic_online
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:arch_probe_nr_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106cbb0)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - arch/x86/kernel/apic/io_apic.c:irq_trigger
  - arch/x86/kernel/apic/io_apic.c:arch_early_ioapic_init
```
```
In drivers/xen/events/events_base.c (ffffffff81675e76)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_free_irq
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8187a90d)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
```
In arch/x86/pci/xen.c (ffffffff819176cd)
Location: arch/x86/include/asm/i8259.h:78
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
</details>
</li>
</ul>

## Differences
