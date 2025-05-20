# Function: <code>irq_desc_get_irq_data</code>

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
In arch/x86/kernel/irq.c (ffffffff81030f79)
Location: include/linux/irqdesc.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81055873)
Location: include/linux/irqdesc.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:setup_vector_irq
  - arch/x86/kernel/apic/vector.c:setup_vector_irq
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81f73724)
Location: include/linux/irqdesc.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:setup_ioapic_dest
```
```
In kernel/irq/manage.c (ffffffff810dac84)
Location: include/linux/irqdesc.h:109
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:__irq_set_affinity
```
```
In kernel/irq/migration.c (ffffffff810e26ac)
Location: include/linux/irqdesc.h:109
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_irq
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81422ef5)
Location: include/linux/irqdesc.h:109
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
```
```
In drivers/gpio/gpio-intel-mid.c (ffffffff81429ac6)
Location: include/linux/irqdesc.h:109
Inline: True
Inline callers:
  - drivers/gpio/gpio-intel-mid.c:intel_mid_irq_handler
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8142a546)
Location: include/linux/irqdesc.h:109
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
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
In arch/x86/kernel/irq.c (ffffffff8103001f)
Location: include/linux/irqdesc.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81055c9c)
Location: include/linux/irqdesc.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
  - arch/x86/kernel/apic/vector.c:setup_vector_irq
  - arch/x86/kernel/apic/vector.c:setup_vector_irq
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81f9bf61)
Location: include/linux/irqdesc.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:setup_ioapic_dest
```
```
In kernel/irq/manage.c (ffffffff810e044e)
Location: include/linux/irqdesc.h:116
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:__irq_set_affinity
```
```
In kernel/irq/migration.c (ffffffff810e813c)
Location: include/linux/irqdesc.h:116
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_irq
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8146c0c1)
Location: include/linux/irqdesc.h:116
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81475336)
Location: include/linux/irqdesc.h:116
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
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
In arch/x86/kernel/irq.c (ffffffff8102ffdd)
Location: include/linux/irqdesc.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81058a37)
Location: include/linux/irqdesc.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
  - arch/x86/kernel/apic/vector.c:setup_vector_irq
  - arch/x86/kernel/apic/vector.c:setup_vector_irq
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81fd74ac)
Location: include/linux/irqdesc.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:setup_ioapic_dest
```
```
In kernel/irq/manage.c (ffffffff810e6d9e)
Location: include/linux/irqdesc.h:119
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:__irq_set_affinity
```
```
In kernel/irq/migration.c (ffffffff810eeb7c)
Location: include/linux/irqdesc.h:119
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_irq
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8148c4a8)
Location: include/linux/irqdesc.h:119
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81497906)
Location: include/linux/irqdesc.h:119
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
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
In arch/x86/kernel/irq.c (ffffffff8102e3ca)
Location: include/linux/irqdesc.h:126
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8190ec40)
Location: include/linux/irqdesc.h:126
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
  - arch/x86/kernel/apic/vector.c:setup_vector_irq
  - arch/x86/kernel/apic/vector.c:setup_vector_irq
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff820b81a3)
Location: include/linux/irqdesc.h:126
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:setup_ioapic_dest
```
```
In kernel/irq/manage.c (ffffffff810e649e)
Location: include/linux/irqdesc.h:126
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:__irq_set_affinity
```
```
In kernel/irq/chip.c (ffffffff810e9af3)
Location: include/linux/irqdesc.h:126
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/migration.c (ffffffff810ee6ac)
Location: include/linux/irqdesc.h:126
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff810ee9fb)
Location: include/linux/irqdesc.h:126
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81495e18)
Location: include/linux/irqdesc.h:126
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff814a15c6)
Location: include/linux/irqdesc.h:126
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
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
In arch/x86/kernel/irq.c (ffffffff8103024d)
Location: include/linux/irqdesc.h:128
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In kernel/irq/manage.c (ffffffff810ee74e)
Location: include/linux/irqdesc.h:128
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:__irq_set_affinity
```
```
In kernel/irq/chip.c (ffffffff810f2043)
Location: include/linux/irqdesc.h:128
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/migration.c (ffffffff810f70dc)
Location: include/linux/irqdesc.h:128
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff810f74ab)
Location: include/linux/irqdesc.h:128
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff814d2128)
Location: include/linux/irqdesc.h:128
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff814dff86)
Location: include/linux/irqdesc.h:128
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
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
In arch/x86/kernel/irq.c (ffffffff810314bd)
Location: include/linux/irqdesc.h:128
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In kernel/irq/manage.c (ffffffff810f6b3e)
Location: include/linux/irqdesc.h:128
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:__irq_set_affinity
```
```
In kernel/irq/chip.c (ffffffff810fa465)
Location: include/linux/irqdesc.h:128
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/migration.c (ffffffff810ff400)
Location: include/linux/irqdesc.h:128
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff810ff752)
Location: include/linux/irqdesc.h:128
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81503128)
Location: include/linux/irqdesc.h:128
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8150f325)
Location: include/linux/irqdesc.h:128
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
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
In arch/x86/kernel/irq.c (ffffffff8103275d)
Location: include/linux/irqdesc.h:128
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In kernel/irq/manage.c (ffffffff811022ae)
Location: include/linux/irqdesc.h:128
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:__irq_set_affinity
```
```
In kernel/irq/chip.c (ffffffff81105c25)
Location: include/linux/irqdesc.h:128
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/migration.c (ffffffff8110abe0)
Location: include/linux/irqdesc.h:128
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff8110af52)
Location: include/linux/irqdesc.h:128
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81518a98)
Location: include/linux/irqdesc.h:128
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff815249be)
Location: include/linux/irqdesc.h:128
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
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
In arch/x86/kernel/irq.c (ffffffff8103446f)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In kernel/irq/manage.c (ffffffff8110a9be)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/chip.c (ffffffff8110f0e5)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/migration.c (ffffffff81114290)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff81114612)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81546aa0)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8155309e)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
```
```
In drivers/xen/events/events_base.c (ffffffff816449c5)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_set_affinity_evtchn
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
In arch/x86/kernel/irq.c (ffffffff81034d2f)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In kernel/irq/manage.c (ffffffff81116d8e)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/chip.c (ffffffff8111b3a5)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/migration.c (ffffffff81120400)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff81120772)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff815679d0)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8157473e)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
```
```
In drivers/xen/events/events_base.c (ffffffff81666f75)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_set_affinity_evtchn
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
In arch/x86/kernel/irq.c (ffffffff81036b2f)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/irqdesc.h:130
Inline: True
```
```
In kernel/irq/manage.c (ffffffff8112287e)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/chip.c (ffffffff81127545)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
  - kernel/irq/chip.c:__irq_startup_managed
```
```
In kernel/irq/migration.c (ffffffff8112c940)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff8112cd0f)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81609ae0)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
```
```
In drivers/gpio/gpio-msic.c (ffffffff81619115)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - drivers/gpio/gpio-msic.c:msic_gpio_irq_handler
```
```
In drivers/xen/events/events_base.c (ffffffff81716d85)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_set_affinity_evtchn
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
In arch/x86/kernel/irq.c (ffffffff81037d1e)
Location: include/linux/irqdesc.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/irqdesc.h:132
Inline: True
```
```
In kernel/irq/manage.c (ffffffff8111e6ae)
Location: include/linux/irqdesc.h:132
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/chip.c (ffffffff81123145)
Location: include/linux/irqdesc.h:132
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
  - kernel/irq/chip.c:__irq_startup_managed
```
```
In kernel/irq/migration.c (ffffffff81128370)
Location: include/linux/irqdesc.h:132
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff8112873f)
Location: include/linux/irqdesc.h:132
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8162e1f0)
Location: include/linux/irqdesc.h:132
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
```
```
In drivers/gpio/gpio-msic.c (ffffffff8163f945)
Location: include/linux/irqdesc.h:132
Inline: True
Inline callers:
  - drivers/gpio/gpio-msic.c:msic_gpio_irq_handler
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
In arch/x86/kernel/irq.c (ffffffff810398be)
Location: include/linux/irqdesc.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/irqdesc.h:132
Inline: True
```
```
In kernel/irq/manage.c (ffffffff8111e9be)
Location: include/linux/irqdesc.h:132
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/chip.c (ffffffff811234a5)
Location: include/linux/irqdesc.h:132
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/migration.c (ffffffff81128630)
Location: include/linux/irqdesc.h:132
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff8112899c)
Location: include/linux/irqdesc.h:132
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81612545)
Location: include/linux/irqdesc.h:132
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
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
In arch/x86/kernel/irq.c (ffffffff8103f134)
Location: include/linux/irqdesc.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/irqdesc.h:132
Inline: True
```
```
In kernel/irq/manage.c (ffffffff8113ee4e)
Location: include/linux/irqdesc.h:132
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/irq/manage.c:irq_force_affinity
  - kernel/irq/manage.c:irq_set_affinity
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/chip.c (ffffffff81143a75)
Location: include/linux/irqdesc.h:132
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/migration.c (ffffffff81148c00)
Location: include/linux/irqdesc.h:132
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff81148f7c)
Location: include/linux/irqdesc.h:132
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81681745)
Location: include/linux/irqdesc.h:132
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
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
In arch/x86/kernel/irq.c (ffffffff81046744)
Location: include/linux/irqdesc.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/irqdesc.h:132
Inline: True
```
```
In kernel/irq/manage.c (ffffffff8116249a)
Location: include/linux/irqdesc.h:132
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:__irq_apply_affinity_hint
  - kernel/irq/manage.c:irq_force_affinity
  - kernel/irq/manage.c:irq_set_affinity
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/chip.c (ffffffff81167865)
Location: include/linux/irqdesc.h:132
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/migration.c (ffffffff8116d740)
Location: include/linux/irqdesc.h:132
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff8116dafc)
Location: include/linux/irqdesc.h:132
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8179c735)
Location: include/linux/irqdesc.h:132
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
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
In arch/x86/kernel/irq.c (ffffffff810507a4)
Location: include/linux/irqdesc.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/irqdesc.h:132
Inline: True
```
```
In kernel/irq/manage.c (ffffffff8119600a)
Location: include/linux/irqdesc.h:132
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:__irq_apply_affinity_hint
  - kernel/irq/manage.c:irq_force_affinity
  - kernel/irq/manage.c:irq_set_affinity
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/chip.c (ffffffff8119bc45)
Location: include/linux/irqdesc.h:132
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/migration.c (ffffffff811a28f0)
Location: include/linux/irqdesc.h:132
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff811a2d2c)
Location: include/linux/irqdesc.h:132
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff818b31d5)
Location: include/linux/irqdesc.h:132
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
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
In arch/x86/kernel/irq.c (ffffffff810514d4)
Location: include/linux/irqdesc.h:135
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/irqdesc.h:135
Inline: True
```
```
In kernel/irq/manage.c (ffffffff811a79ca)
Location: include/linux/irqdesc.h:135
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:__irq_apply_affinity_hint
  - kernel/irq/manage.c:irq_force_affinity
  - kernel/irq/manage.c:irq_set_affinity
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/chip.c (ffffffff811ad942)
Location: include/linux/irqdesc.h:135
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/migration.c (ffffffff811b47f0)
Location: include/linux/irqdesc.h:135
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff811b4c2c)
Location: include/linux/irqdesc.h:135
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff818f6225)
Location: include/linux/irqdesc.h:135
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
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
In arch/x86/kernel/irq.c (ffffffff810586f9)
Location: include/linux/irqdesc.h:135
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/irqdesc.h:135
Inline: True
```
```
In kernel/irq/manage.c (ffffffff811b752a)
Location: include/linux/irqdesc.h:135
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:__irq_apply_affinity_hint
  - kernel/irq/manage.c:irq_force_affinity
  - kernel/irq/manage.c:irq_set_affinity
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/chip.c (ffffffff811bd542)
Location: include/linux/irqdesc.h:135
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/migration.c (ffffffff811c4670)
Location: include/linux/irqdesc.h:135
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff811c4aac)
Location: include/linux/irqdesc.h:135
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8193d005)
Location: include/linux/irqdesc.h:135
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In virt/kvm/arm/vgic/vgic.c (ffff8000100dc72c)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_map_phys_irq
```
```
In kernel/irq/manage.c (ffff800010178d00)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/chip.c (ffff80001017f394)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffff8000101865c0)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
```
In drivers/irqchip/irq-gic.c (0)
Location: include/linux/irqdesc.h:130
Inline: True
```
```
In drivers/irqchip/irq-gic-v3.c (0)
Location: include/linux/irqdesc.h:130
Inline: True
```
```
In drivers/irqchip/irq-gic-v3-its.c (0)
Location: include/linux/irqdesc.h:130
Inline: True
```
```
In drivers/irqchip/irq-partition-percpu.c (ffff800010675944)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - drivers/irqchip/irq-partition-percpu.c:partition_irq_set_type
  - drivers/irqchip/irq-partition-percpu.c:partition_irq_get_irqchip_state
  - drivers/irqchip/irq-partition-percpu.c:partition_irq_set_irqchip_state
  - drivers/irqchip/irq-partition-percpu.c:partition_irq_unmask
  - drivers/irqchip/irq-partition-percpu.c:partition_irq_mask
```
```
In drivers/irqchip/irq-bcm7038-l1.c (0)
Location: include/linux/irqdesc.h:130
Inline: True
```
```
In drivers/xen/events/events_base.c (ffff800010830c54)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_set_affinity_evtchn
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c03ca698)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/chip.c (c03cf5b0)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/cpuhotplug.c (c03d5340)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
```
In drivers/irqchip/irq-hip04.c (0)
Location: include/linux/irqdesc.h:130
Inline: True
```
```
In drivers/irqchip/irq-gic.c (0)
Location: include/linux/irqdesc.h:130
Inline: True
```
```
In drivers/irqchip/irq-gic-v3.c (0)
Location: include/linux/irqdesc.h:130
Inline: True
```
```
In drivers/irqchip/irq-gic-v3-its.c (0)
Location: include/linux/irqdesc.h:130
Inline: True
```
```
In drivers/irqchip/irq-partition-percpu.c (c081ddcc)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - drivers/irqchip/irq-partition-percpu.c:partition_irq_set_type
  - drivers/irqchip/irq-partition-percpu.c:partition_irq_get_irqchip_state
  - drivers/irqchip/irq-partition-percpu.c:partition_irq_set_irqchip_state
  - drivers/irqchip/irq-partition-percpu.c:partition_irq_unmask
  - drivers/irqchip/irq-partition-percpu.c:partition_irq_mask
```
```
In drivers/irqchip/irq-armada-370-xp.c (0)
Location: include/linux/irqdesc.h:130
Inline: True
```
```
In drivers/mfd/asic3.c (c0a0e8ac)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - drivers/mfd/asic3.c:asic3_irq_demux
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/sysdev/xive/common.c (c0000000000bdffc)
Location: include/linux/irqdesc.h:130
Inline: True
```
```
In arch/powerpc/xmon/xmon.c (c00000000010e188)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - arch/powerpc/xmon/xmon.c:dump
```
```
In kernel/irq/manage.c (c0000000001d2fd0)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/chip.c (c0000000001d9bd8)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/cpuhotplug.c (c0000000001e0dac)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffe0001137ae)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/chip.c (ffffffe0001178e8)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
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
In arch/x86/kernel/irq.c (ffffffff81034e8f)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In kernel/irq/manage.c (ffffffff8110f36e)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/chip.c (ffffffff81113985)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/migration.c (ffffffff811189e0)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff81118d52)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8155eea0)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
```
```
In drivers/xen/events/events_base.c (ffffffff8162cca5)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_set_affinity_evtchn
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
In arch/x86/kernel/irq.c (ffffffff810247cf)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In kernel/irq/manage.c (ffffffff811000ae)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/chip.c (ffffffff81104695)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/migration.c (ffffffff81109a50)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff81109dc2)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8154dfe0)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8155ad4e)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
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
In arch/x86/kernel/irq.c (ffffffff81034cef)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In kernel/irq/manage.c (ffffffff8110d25e)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/chip.c (ffffffff81111875)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/migration.c (ffffffff811168d0)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff81116c42)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8155bd00)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81568a6e)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
```
```
In drivers/xen/events/events_base.c (ffffffff8165adb5)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_set_affinity_evtchn
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
In arch/x86/kernel/irq.c (ffffffff81035c43)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In kernel/irq/manage.c (ffffffff811187be)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/chip.c (ffffffff8111ce35)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/migration.c (ffffffff81121f10)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff811222c2)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81574f90)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8158298e)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
```
```
In drivers/xen/events/events_base.c (ffffffff816753a5)
Location: include/linux/irqdesc.h:130
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_set_affinity_evtchn
```
</details>
</li>
</ul>

## Differences
