# Function: <code>irq_to_desc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct irq_desc *irq_to_desc(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810d9f90)
Location: kernel/irq/irqdesc.c:111
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_irq
  - kernel/irq/irqdesc.c:free_desc
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
  - kernel/irq/irqdesc.c:irq_set_percpu_devid
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
  - kernel/irq/irqdesc.c:kstat_irqs_cpu
  - kernel/irq/irqdesc.c:kstat_irqs
Direct callers:
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:setup_vector_irq
  - arch/x86/kernel/apic/vector.c:setup_vector_irq
  - arch/x86/kernel/apic/vector.c:setup_vector_irq
  - arch/x86/kernel/apic/io_apic.c:setup_ioapic_dest
  - kernel/irq/manage.c:synchronize_hardirq
  - kernel/irq/manage.c:set_irq_wake_real
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/manage.c:irq_wake_thread
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:remove_irq
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_can_set_affinity
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/manage.c:irq_select_affinity_usr
  - kernel/irq/manage.c:setup_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:request_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/chip.c:irq_get_irq_data
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/irq/proc.c:irq_node_proc_show
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/pm.c:suspend_device_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/pci/msi.c:free_msi_irqs
```
**Symbols:**

```
ffffffff810d9f90-ffffffff810d9fa9: irq_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct irq_desc *irq_to_desc(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810dfaa6)
Location: kernel/irq/irqdesc.c:133
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:kstat_irqs_cpu
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
  - kernel/irq/irqdesc.c:generic_handle_irq
  - kernel/irq/irqdesc.c:free_desc
Direct callers:
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/apic/vector.c:setup_vector_irq
  - arch/x86/kernel/apic/vector.c:setup_vector_irq
  - arch/x86/kernel/apic/vector.c:setup_vector_irq
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/io_apic.c:setup_ioapic_dest
  - kernel/irq/manage.c:request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:setup_irq
  - kernel/irq/manage.c:irq_wake_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:set_irq_wake_real
  - kernel/irq/manage.c:irq_select_affinity_usr
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/manage.c:synchronize_hardirq
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_get_irq_data
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/irq/proc.c:irq_node_proc_show
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
**Symbols:**

```
ffffffff810df450-ffffffff810df469: irq_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct irq_desc *irq_to_desc(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810e6436)
Location: kernel/irq/irqdesc.c:309
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:kstat_irqs_cpu
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
  - kernel/irq/irqdesc.c:generic_handle_irq
  - kernel/irq/irqdesc.c:free_desc
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/apic/vector.c:setup_vector_irq
  - arch/x86/kernel/apic/vector.c:setup_vector_irq
  - arch/x86/kernel/apic/vector.c:setup_vector_irq
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/io_apic.c:setup_ioapic_dest
  - kernel/irq/manage.c:request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:setup_irq
  - kernel/irq/manage.c:irq_wake_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:set_irq_wake_real
  - kernel/irq/manage.c:irq_select_affinity_usr
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/manage.c:synchronize_hardirq
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_get_irq_data
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/irq/proc.c:irq_node_proc_show
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
**Symbols:**

```
ffffffff810e5a90-ffffffff810e5aa9: irq_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct irq_desc *irq_to_desc(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810e5a96)
Location: kernel/irq/irqdesc.c:321
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:kstat_irqs_cpu
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
  - kernel/irq/irqdesc.c:generic_handle_irq
  - kernel/irq/irqdesc.c:free_desc
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/apic/vector.c:setup_vector_irq
  - arch/x86/kernel/apic/vector.c:setup_vector_irq
  - arch/x86/kernel/apic/vector.c:setup_vector_irq
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/io_apic.c:setup_ioapic_dest
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:setup_irq
  - kernel/irq/manage.c:irq_wake_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:set_irq_wake_real
  - kernel/irq/manage.c:irq_select_affinity_usr
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/manage.c:synchronize_hardirq
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_get_irq_data
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/irq/proc.c:irq_node_proc_show
  - kernel/irq/proc.c:irq_effective_aff_list_proc_show
  - kernel/irq/proc.c:irq_effective_aff_proc_show
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
**Symbols:**

```
ffffffff810e50a0-ffffffff810e50b9: irq_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct irq_desc *irq_to_desc(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810edcf6)
Location: kernel/irq/irqdesc.c:319
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:kstat_irqs_cpu
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
  - kernel/irq/irqdesc.c:generic_handle_irq
  - kernel/irq/irqdesc.c:free_desc
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/apic/vector.c:lapic_online
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:setup_irq
  - kernel/irq/manage.c:irq_wake_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:set_irq_wake_real
  - kernel/irq/manage.c:irq_select_affinity_usr
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/manage.c:synchronize_hardirq
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_get_irq_data
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/irq/proc.c:irq_node_proc_show
  - kernel/irq/proc.c:irq_effective_aff_list_proc_show
  - kernel/irq/proc.c:irq_effective_aff_proc_show
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
**Symbols:**

```
ffffffff810ed300-ffffffff810ed319: irq_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct irq_desc *irq_to_desc(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810f6135)
Location: kernel/irq/irqdesc.c:336
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:kstat_irqs_cpu
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
  - kernel/irq/irqdesc.c:generic_handle_irq
  - kernel/irq/irqdesc.c:free_desc
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/apic/vector.c:lapic_online
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
  - kernel/irq/manage.c:setup_irq
  - kernel/irq/manage.c:irq_wake_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:set_irq_wake_real
  - kernel/irq/manage.c:irq_select_affinity_usr
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/manage.c:synchronize_hardirq
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_get_irq_data
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/irq/proc.c:irq_node_proc_show
  - kernel/irq/proc.c:irq_effective_aff_list_proc_show
  - kernel/irq/proc.c:irq_effective_aff_proc_show
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
**Symbols:**

```
ffffffff810f56c0-ffffffff810f56d9: irq_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct irq_desc *irq_to_desc(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811018c5)
Location: kernel/irq/irqdesc.c:336
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:kstat_irqs_cpu
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
  - kernel/irq/irqdesc.c:generic_handle_irq
  - kernel/irq/irqdesc.c:free_desc
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/apic/vector.c:lapic_online
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
  - kernel/irq/manage.c:setup_irq
  - kernel/irq/manage.c:irq_wake_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:set_irq_wake_real
  - kernel/irq/manage.c:irq_select_affinity_usr
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/manage.c:synchronize_hardirq
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_get_irq_data
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/irq/proc.c:irq_node_proc_show
  - kernel/irq/proc.c:irq_effective_aff_list_proc_show
  - kernel/irq/proc.c:irq_effective_aff_proc_show
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
**Symbols:**

```
ffffffff81100e50-ffffffff81100e69: irq_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct irq_desc *irq_to_desc(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8110a0c5)
Location: kernel/irq/irqdesc.c:351
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:kstat_irqs_cpu
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
  - kernel/irq/irqdesc.c:generic_handle_irq
  - kernel/irq/irqdesc.c:free_desc
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/apic/vector.c:lapic_online
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_nmi
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
  - kernel/irq/manage.c:setup_irq
  - kernel/irq/manage.c:irq_wake_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:set_irq_wake_real
  - kernel/irq/manage.c:irq_select_affinity_usr
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/manage.c:synchronize_hardirq
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_get_irq_data
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/irq/proc.c:irq_node_proc_show
  - kernel/irq/proc.c:irq_effective_aff_list_proc_show
  - kernel/irq/proc.c:irq_effective_aff_proc_show
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
**Symbols:**

```
ffffffff81109650-ffffffff81109669: irq_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct irq_desc *irq_to_desc(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81116495)
Location: kernel/irq/irqdesc.c:351
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:kstat_irqs_cpu
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
  - kernel/irq/irqdesc.c:generic_handle_irq
  - kernel/irq/irqdesc.c:free_desc
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/apic/vector.c:lapic_online
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_nmi
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
  - kernel/irq/manage.c:setup_irq
  - kernel/irq/manage.c:irq_wake_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:set_irq_wake_real
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/manage.c:synchronize_hardirq
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_get_irq_data
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/irq/proc.c:irq_node_proc_show
  - kernel/irq/proc.c:irq_effective_aff_list_proc_show
  - kernel/irq/proc.c:irq_effective_aff_proc_show
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
**Symbols:**

```
ffffffff81115a20-ffffffff81115a39: irq_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct irq_desc *irq_to_desc(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81122095)
Location: kernel/irq/irqdesc.c:351
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
  - kernel/irq/irqdesc.c:generic_handle_irq
  - kernel/irq/irqdesc.c:free_desc
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:per_cpu_count_show
Direct callers:
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/apic/vector.c:lapic_online
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_nmi
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_any_context_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:irq_wake_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:misrouted_irq
  - kernel/irq/spurious.c:misrouted_irq
  - kernel/irq/resend.c:resend_irqs
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_get_irq_data
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/irq/proc.c:irq_node_proc_show
  - kernel/irq/proc.c:irq_effective_aff_list_proc_show
  - kernel/irq/proc.c:irq_effective_aff_proc_show
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
**Symbols:**

```
ffffffff811213d0-ffffffff811213e9: irq_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct irq_desc *irq_to_desc(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8111d5e5)
Location: kernel/irq/irqdesc.c:351
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:kstat_irqs_cpu
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
  - kernel/irq/irqdesc.c:generic_handle_irq
  - kernel/irq/irqdesc.c:free_desc
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/apic/vector.c:lapic_online
  - kernel/irq/manage.c:irq_check_status_bit
  - kernel/irq/manage.c:irq_has_action
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_nmi
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_any_context_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:irq_wake_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:misrouted_irq
  - kernel/irq/spurious.c:misrouted_irq
  - kernel/irq/resend.c:resend_irqs
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_get_irq_data
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/irq/proc.c:irq_node_proc_show
  - kernel/irq/proc.c:irq_effective_aff_list_proc_show
  - kernel/irq/proc.c:irq_effective_aff_proc_show
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - kernel/irq/pm.c:suspend_device_irqs
```
**Symbols:**

```
ffffffff8111de70-ffffffff8111de89: irq_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct irq_desc *irq_to_desc(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8111e3be)
Location: kernel/irq/irqdesc.c:351
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs_usr
  - kernel/irq/irqdesc.c:kstat_irqs_cpu
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
  - kernel/irq/irqdesc.c:generic_handle_irq
  - kernel/irq/irqdesc.c:free_desc
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_msi_domain_free_irqs
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/apic/vector.c:lapic_online
  - kernel/irq/manage.c:irq_check_status_bit
  - kernel/irq/manage.c:irq_has_action
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_nmi
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_any_context_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:irq_wake_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/resend.c:resend_irqs
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_get_irq_data
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/irq/proc.c:irq_node_proc_show
  - kernel/irq/proc.c:irq_effective_aff_list_proc_show
  - kernel/irq/proc.c:irq_effective_aff_proc_show
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - kernel/irq/pm.c:suspend_device_irqs
```
**Symbols:**

```
ffffffff8111e100-ffffffff8111e119: irq_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct irq_desc *irq_to_desc(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8113e852)
Location: kernel/irq/irqdesc.c:351
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs_usr
  - kernel/irq/irqdesc.c:kstat_irqs_cpu
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
  - kernel/irq/irqdesc.c:generic_handle_irq
  - kernel/irq/irqdesc.c:free_desc
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_msi_domain_free_irqs
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/apic/vector.c:lapic_online
  - kernel/irq/manage.c:irq_check_status_bit
  - kernel/irq/manage.c:irq_has_action
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_nmi
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_any_context_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:irq_wake_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/irq/manage.c:irq_force_affinity
  - kernel/irq/manage.c:irq_set_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/resend.c:resend_irqs
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_get_irq_data
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/irq/proc.c:irq_node_proc_show
  - kernel/irq/proc.c:irq_effective_aff_list_proc_show
  - kernel/irq/proc.c:irq_effective_aff_proc_show
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - kernel/irq/pm.c:suspend_device_irqs
```
**Symbols:**

```
ffffffff8113e580-ffffffff8113e599: irq_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct irq_desc *irq_to_desc(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81161e2b)
Location: kernel/irq/irqdesc.c:351
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs_usr
  - kernel/irq/irqdesc.c:kstat_irqs_cpu
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
  - kernel/irq/irqdesc.c:generic_handle_irq_safe
  - kernel/irq/irqdesc.c:generic_handle_irq
  - kernel/irq/irqdesc.c:free_desc
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/apic/vector.c:lapic_online
  - kernel/irq/manage.c:irq_check_status_bit
  - kernel/irq/manage.c:irq_has_action
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_nmi
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_any_context_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:irq_wake_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:__irq_apply_affinity_hint
  - kernel/irq/manage.c:irq_force_affinity
  - kernel/irq/manage.c:irq_set_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/resend.c:resend_irqs
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_get_irq_data
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irq_sim.c:irq_sim_handle_irq
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/irq/proc.c:irq_node_proc_show
  - kernel/irq/proc.c:irq_effective_aff_list_proc_show
  - kernel/irq/proc.c:irq_effective_aff_proc_show
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - kernel/irq/pm.c:suspend_device_irqs
```
**Symbols:**

```
ffffffff811619b0-ffffffff811619d1: irq_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct irq_desc *irq_to_desc(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8119565d)
Location: kernel/irq/irqdesc.c:354
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs_usr
  - kernel/irq/irqdesc.c:kstat_irqs_cpu
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
  - kernel/irq/irqdesc.c:generic_handle_irq_safe
  - kernel/irq/irqdesc.c:generic_handle_irq
  - kernel/irq/irqdesc.c:free_desc
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/apic/vector.c:lapic_online
  - kernel/irq/manage.c:irq_check_status_bit
  - kernel/irq/manage.c:irq_has_action
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_nmi
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_any_context_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:irq_wake_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:__irq_apply_affinity_hint
  - kernel/irq/manage.c:irq_force_affinity
  - kernel/irq/manage.c:irq_set_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/resend.c:resend_irqs
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_get_irq_data
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irq_sim.c:irq_sim_handle_irq
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/irq/proc.c:irq_node_proc_show
  - kernel/irq/proc.c:irq_effective_aff_list_proc_show
  - kernel/irq/proc.c:irq_effective_aff_proc_show
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - kernel/irq/pm.c:suspend_device_irqs
```
**Symbols:**

```
ffffffff81195080-ffffffff811950a1: irq_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct irq_desc *irq_to_desc(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811a702d)
Location: kernel/irq/irqdesc.c:379
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs_usr
  - kernel/irq/irqdesc.c:kstat_irqs_cpu
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
  - kernel/irq/irqdesc.c:generic_handle_irq_safe
  - kernel/irq/irqdesc.c:generic_handle_irq
  - kernel/irq/irqdesc.c:free_desc
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/apic/vector.c:lapic_online
  - kernel/irq/manage.c:irq_check_status_bit
  - kernel/irq/manage.c:irq_has_action
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_nmi
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_any_context_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:irq_wake_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:__irq_apply_affinity_hint
  - kernel/irq/manage.c:irq_force_affinity
  - kernel/irq/manage.c:irq_set_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/resend.c:check_irq_resend
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_get_irq_data
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irq_sim.c:irq_sim_handle_irq
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/irq/proc.c:irq_node_proc_show
  - kernel/irq/proc.c:irq_effective_aff_list_proc_show
  - kernel/irq/proc.c:irq_effective_aff_proc_show
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - kernel/irq/pm.c:suspend_device_irqs
```
**Symbols:**

```
ffffffff811a6a10-ffffffff811a6a31: irq_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct irq_desc *irq_to_desc(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811b6b8d)
Location: kernel/irq/irqdesc.c:379
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs_usr
  - kernel/irq/irqdesc.c:kstat_irqs_cpu
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
  - kernel/irq/irqdesc.c:generic_handle_irq_safe
  - kernel/irq/irqdesc.c:generic_handle_irq
  - kernel/irq/irqdesc.c:free_desc
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/apic/vector.c:lapic_online
  - kernel/irq/manage.c:irq_check_status_bit
  - kernel/irq/manage.c:irq_has_action
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_nmi
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_any_context_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:irq_wake_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:disable_irq
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:__irq_apply_affinity_hint
  - kernel/irq/manage.c:irq_force_affinity
  - kernel/irq/manage.c:irq_set_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/resend.c:check_irq_resend
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_get_irq_data
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irq_sim.c:irq_sim_handle_irq
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/irq/proc.c:irq_node_proc_show
  - kernel/irq/proc.c:irq_effective_aff_list_proc_show
  - kernel/irq/proc.c:irq_effective_aff_proc_show
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - kernel/irq/pm.c:suspend_device_irqs
```
**Symbols:**

```
ffffffff811b6530-ffffffff811b6551: irq_to_desc (STB_GLOBAL)
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
struct irq_desc *irq_to_desc(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffff8000101781a8)
Location: kernel/irq/irqdesc.c:351
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:kstat_irqs_cpu
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
  - kernel/irq/irqdesc.c:generic_handle_irq
  - kernel/irq/irqdesc.c:free_desc
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - arch/arm64/kernel/machine_kexec.c:machine_crash_shutdown
  - arch/arm64/kernel/machine_kexec.c:machine_crash_shutdown
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_map_phys_irq
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_nmi
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
  - kernel/irq/manage.c:setup_irq
  - kernel/irq/manage.c:irq_wake_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:set_irq_wake_real
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/manage.c:synchronize_hardirq
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/resend.c:resend_irqs
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_get_irq_data
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/irq/proc.c:irq_node_proc_show
  - kernel/irq/proc.c:irq_effective_aff_list_proc_show
  - kernel/irq/proc.c:irq_effective_aff_proc_show
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/irqchip/irq-gic.c:gic_irq_domain_map
  - drivers/irqchip/irq-gic-v3.c:gic_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3.c:gic_irq_nmi_teardown
  - drivers/irqchip/irq-gic-v3.c:gic_irq_nmi_setup
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_alloc
  - drivers/irqchip/irq-partition-percpu.c:partition_create_desc
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_map
  - drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_unmask_leg_irq
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_mask_leg_irq
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_unmask_intx_irq
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_mask_intx_irq
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/perf/arm_pmu.c:arm_perf_starting_cpu
  - drivers/perf/arm_pmu.c:armpmu_request_irq
  - drivers/perf/arm_pmu.c:armpmu_free_irq
  - drivers/perf/arm_pmu_platform.c:pmu_parse_irqs
  - drivers/perf/arm_pmu_platform.c:pmu_parse_irqs
  - drivers/perf/arm_pmu_acpi.c:arm_pmu_acpi_cpu_starting
  - drivers/perf/arm_pmu_acpi.c:arm_pmu_acpi_cpu_starting
```
**Symbols:**

```
ffff800010177238-ffff80001017726c: irq_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct irq_desc *irq_to_desc(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (c03c9a80)
Location: kernel/irq/irqdesc.c:351
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:kstat_irqs_cpu
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
  - kernel/irq/irqdesc.c:generic_handle_irq
  - kernel/irq/irqdesc.c:free_desc
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - arch/arm/kernel/machine_kexec.c:machine_crash_shutdown
  - arch/arm/kernel/machine_kexec.c:machine_crash_shutdown
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_nmi
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
  - kernel/irq/manage.c:setup_irq
  - kernel/irq/manage.c:irq_wake_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:set_irq_wake_real
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/manage.c:synchronize_hardirq
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/resend.c:resend_irqs
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_get_irq_data
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/irq/proc.c:irq_node_proc_show
  - kernel/irq/proc.c:irq_effective_aff_list_proc_show
  - kernel/irq/proc.c:irq_effective_aff_proc_show
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/irqchip/irq-hip04.c:hip04_irq_domain_map
  - drivers/irqchip/irq-gic.c:gic_irq_domain_map
  - drivers/irqchip/irq-gic-v3.c:gic_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3.c:gic_irq_nmi_teardown
  - drivers/irqchip/irq-gic-v3.c:gic_irq_nmi_setup
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_alloc
  - drivers/irqchip/irq-partition-percpu.c:partition_create_desc
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_irq_map
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_irq_domain_map
  - drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/perf/arm_pmu.c:arm_perf_starting_cpu
  - drivers/perf/arm_pmu.c:armpmu_request_irq
  - drivers/perf/arm_pmu.c:armpmu_free_irq
  - drivers/perf/arm_pmu_platform.c:arm_pmu_device_probe
  - drivers/perf/arm_pmu_platform.c:arm_pmu_device_probe
```
**Symbols:**

```
c03c8ea0-c03c8ec8: irq_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct irq_desc *irq_to_desc(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (c0000000001d1cf4)
Location: kernel/irq/irqdesc.c:351
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:kstat_irqs_cpu
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
  - kernel/irq/irqdesc.c:generic_handle_irq
  - kernel/irq/irqdesc.c:free_desc
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - arch/powerpc/kernel/eeh_driver.c:eeh_set_irq_state
  - arch/powerpc/kernel/machine_kexec.c:machine_kexec_mask_interrupts
  - arch/powerpc/kernel/machine_kexec.c:machine_kexec_mask_interrupts
  - arch/powerpc/sysdev/xics/xics-common.c:xics_migrate_irqs_away
  - arch/powerpc/sysdev/xics/xics-common.c:xics_migrate_irqs_away
  - arch/powerpc/sysdev/xics/xics-common.c:xics_migrate_irqs_away
  - arch/powerpc/sysdev/xive/common.c:xive_scan_interrupts
  - arch/powerpc/xmon/xmon.c:dump
  - arch/powerpc/xmon/xmon.c:dump
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_nmi
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
  - kernel/irq/manage.c:setup_irq
  - kernel/irq/manage.c:irq_wake_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:set_irq_wake_real
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/manage.c:synchronize_hardirq
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/resend.c:resend_irqs
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_get_irq_data
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/irq/proc.c:irq_node_proc_show
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
**Symbols:**

```
c0000000001d0b50-c0000000001d0b90: irq_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct irq_desc *irq_to_desc(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffe000112d4c)
Location: kernel/irq/irqdesc.c:351
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:kstat_irqs_cpu
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
  - kernel/irq/irqdesc.c:generic_handle_irq
  - kernel/irq/irqdesc.c:free_desc
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_nmi
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
  - kernel/irq/manage.c:setup_irq
  - kernel/irq/manage.c:irq_wake_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:set_irq_wake_real
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/manage.c:synchronize_hardirq
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_get_irq_data
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/irq/proc.c:irq_node_proc_show
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
**Symbols:**

```
ffffffe000112110-ffffffe000112146: irq_to_desc (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct irq_desc *irq_to_desc(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8110ea75)
Location: kernel/irq/irqdesc.c:351
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:kstat_irqs_cpu
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
  - kernel/irq/irqdesc.c:generic_handle_irq
  - kernel/irq/irqdesc.c:free_desc
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/apic/vector.c:lapic_online
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_nmi
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
  - kernel/irq/manage.c:setup_irq
  - kernel/irq/manage.c:irq_wake_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:set_irq_wake_real
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/manage.c:synchronize_hardirq
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_get_irq_data
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/irq/proc.c:irq_node_proc_show
  - kernel/irq/proc.c:irq_effective_aff_list_proc_show
  - kernel/irq/proc.c:irq_effective_aff_proc_show
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
**Symbols:**

```
ffffffff8110e000-ffffffff8110e019: irq_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct irq_desc *irq_to_desc(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810ff7c5)
Location: kernel/irq/irqdesc.c:351
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:kstat_irqs_cpu
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
  - kernel/irq/irqdesc.c:generic_handle_irq
  - kernel/irq/irqdesc.c:free_desc
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/apic/vector.c:lapic_online
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_nmi
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
  - kernel/irq/manage.c:setup_irq
  - kernel/irq/manage.c:irq_wake_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:set_irq_wake_real
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/manage.c:synchronize_hardirq
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_get_irq_data
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irq_sim.c:irq_sim_handle_irq
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/irq/proc.c:irq_node_proc_show
  - kernel/irq/proc.c:irq_effective_aff_list_proc_show
  - kernel/irq/proc.c:irq_effective_aff_proc_show
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
**Symbols:**

```
ffffffff810fed60-ffffffff810fed79: irq_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct irq_desc *irq_to_desc(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8110c965)
Location: kernel/irq/irqdesc.c:351
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:kstat_irqs_cpu
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
  - kernel/irq/irqdesc.c:generic_handle_irq
  - kernel/irq/irqdesc.c:free_desc
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/apic/vector.c:lapic_online
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_nmi
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
  - kernel/irq/manage.c:setup_irq
  - kernel/irq/manage.c:irq_wake_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:set_irq_wake_real
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/manage.c:synchronize_hardirq
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_get_irq_data
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/irq/proc.c:irq_node_proc_show
  - kernel/irq/proc.c:irq_effective_aff_list_proc_show
  - kernel/irq/proc.c:irq_effective_aff_proc_show
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
**Symbols:**

```
ffffffff8110bef0-ffffffff8110bf09: irq_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct irq_desc *irq_to_desc(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81117e75)
Location: kernel/irq/irqdesc.c:351
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:kstat_irqs_cpu
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
  - kernel/irq/irqdesc.c:generic_handle_irq
  - kernel/irq/irqdesc.c:free_desc
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/apic/vector.c:lapic_online
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_nmi
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
  - kernel/irq/manage.c:setup_irq
  - kernel/irq/manage.c:irq_wake_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:set_irq_wake_real
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/manage.c:synchronize_hardirq
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:irq_get_irq_data
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/irq/proc.c:irq_node_proc_show
  - kernel/irq/proc.c:irq_effective_aff_list_proc_show
  - kernel/irq/proc.c:irq_effective_aff_proc_show
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
**Symbols:**

```
ffffffff81117420-ffffffff81117439: irq_to_desc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
