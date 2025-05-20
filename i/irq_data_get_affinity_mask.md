# Function: <code>irq_data_get_affinity_mask</code>

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
In arch/x86/kernel/irq.c (ffffffff81030f24)
Location: include/linux/irq.h:679
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81f73707)
Location: include/linux/irq.h:679
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:setup_ioapic_dest
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
In arch/x86/kernel/irq.c (ffffffff8102ffc0)
Location: include/linux/irq.h:708
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (0)
Location: include/linux/irq.h:708
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
In arch/x86/kernel/irq.c (ffffffff8102ff5e)
Location: include/linux/irq.h:725
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81fd748f)
Location: include/linux/irq.h:725
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:setup_ioapic_dest
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
In arch/x86/kernel/irq.c (ffffffff8102e1ba)
Location: include/linux/irq.h:775
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff820b81af)
Location: include/linux/irq.h:775
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:setup_ioapic_dest
```
```
In kernel/irq/chip.c (ffffffff810e9a5d)
Location: include/linux/irq.h:775
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff810ee9ae)
Location: include/linux/irq.h:775
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff8105c08a)
Location: include/linux/irq.h:804
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
```
```
In kernel/irq/chip.c (ffffffff810f1f3d)
Location: include/linux/irq.h:804
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff810f745e)
Location: include/linux/irq.h:804
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff8105f0a8)
Location: include/linux/irq.h:806
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/irq/chip.c (ffffffff810fa37a)
Location: include/linux/irq.h:806
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff810ff756)
Location: include/linux/irq.h:806
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff81064a88)
Location: include/linux/irq.h:807
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
```
```
In kernel/irq/chip.c (ffffffff81105b3a)
Location: include/linux/irq.h:807
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff8110af56)
Location: include/linux/irq.h:807
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff81068172)
Location: include/linux/irq.h:820
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
```
```
In kernel/irq/chip.c (ffffffff8110effa)
Location: include/linux/irq.h:820
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff81114617)
Location: include/linux/irq.h:820
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff81068ab2)
Location: include/linux/irq.h:838
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
```
```
In kernel/irq/chip.c (ffffffff8111b2ba)
Location: include/linux/irq.h:838
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff81120777)
Location: include/linux/irq.h:838
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff8106ed75)
Location: include/linux/irq.h:868
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:vector_free_reserved_and_managed
  - arch/x86/kernel/apic/vector.c:activate_managed
  - arch/x86/kernel/apic/vector.c:activate_reserved
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:reserve_managed_vector
```
```
In kernel/irq/chip.c (ffffffff81127475)
Location: include/linux/irq.h:868
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff8112cd0f)
Location: include/linux/irq.h:868
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:migrate_one_irq
  - kernel/irq/cpuhotplug.c:migrate_one_irq
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
In arch/x86/kernel/apic/vector.c (ffffffff81070365)
Location: include/linux/irq.h:881
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:vector_free_reserved_and_managed
  - arch/x86/kernel/apic/vector.c:activate_managed
  - arch/x86/kernel/apic/vector.c:activate_reserved
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:reserve_managed_vector
```
```
In kernel/irq/chip.c (ffffffff81123075)
Location: include/linux/irq.h:881
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff8112873f)
Location: include/linux/irq.h:881
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:migrate_one_irq
  - kernel/irq/cpuhotplug.c:migrate_one_irq
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
In arch/x86/kernel/apic/vector.c (ffffffff81071d4b)
Location: include/linux/irq.h:883
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:activate_managed
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
```
In kernel/irq/chip.c (ffffffff81123389)
Location: include/linux/irq.h:883
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff8112899c)
Location: include/linux/irq.h:883
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:migrate_one_irq
  - kernel/irq/cpuhotplug.c:migrate_one_irq
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
In arch/x86/kernel/apic/vector.c (ffffffff8107db48)
Location: include/linux/irq.h:885
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:activate_managed
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
```
In kernel/irq/chip.c (ffffffff81143959)
Location: include/linux/irq.h:885
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff81148f7c)
Location: include/linux/irq.h:885
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:migrate_one_irq
  - kernel/irq/cpuhotplug.c:migrate_one_irq
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
In arch/x86/kernel/apic/vector.c (ffffffff8108d395)
Location: include/linux/irq.h:889
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:activate_managed
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
```
In kernel/irq/chip.c (ffffffff81167722)
Location: include/linux/irq.h:889
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff8116dafc)
Location: include/linux/irq.h:889
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:migrate_one_irq
  - kernel/irq/cpuhotplug.c:irq_needs_fixup
```
```
In kernel/irq/msi.c (ffffffff8116f6f6)
Location: include/linux/irq.h:889
Inline: True
Inline callers:
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff810a149a)
Location: include/linux/irq.h:885
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:activate_managed
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
```
In kernel/irq/chip.c (ffffffff8119baf2)
Location: include/linux/irq.h:885
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff811a2d2c)
Location: include/linux/irq.h:885
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:migrate_one_irq
  - kernel/irq/cpuhotplug.c:irq_needs_fixup
```
```
In kernel/irq/msi.c (ffffffff811a4bcb)
Location: include/linux/irq.h:885
Inline: True
Inline callers:
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff810a448a)
Location: include/linux/irq.h:898
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:activate_managed
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
```
In kernel/irq/chip.c (ffffffff811ad942)
Location: include/linux/irq.h:898
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff811b4c2c)
Location: include/linux/irq.h:898
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:migrate_one_irq
  - kernel/irq/cpuhotplug.c:irq_needs_fixup
```
```
In kernel/irq/msi.c (ffffffff811b6afa)
Location: include/linux/irq.h:898
Inline: True
Inline callers:
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff810aba1a)
Location: include/linux/irq.h:880
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:activate_managed
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
```
In kernel/irq/chip.c (ffffffff811bd542)
Location: include/linux/irq.h:880
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff811c4aac)
Location: include/linux/irq.h:880
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:migrate_one_irq
  - kernel/irq/cpuhotplug.c:irq_needs_fixup
```
```
In kernel/irq/msi.c (ffffffff811c69cc)
Location: include/linux/irq.h:880
Inline: True
Inline callers:
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
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
In kernel/irq/chip.c (ffff80001017f270)
Location: include/linux/irq.h:838
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffff8000101865c4)
Location: include/linux/irq.h:838
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
```
In drivers/irqchip/irq-bcm7038-l1.c (0)
Location: include/linux/irq.h:838
Inline: True
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
In kernel/irq/chip.c (c03cf458)
Location: include/linux/irq.h:838
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (c03d5340)
Location: include/linux/irq.h:838
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
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
In arch/powerpc/sysdev/xics/ics-rtas.c (c0000000000bba70)
Location: include/linux/irq.h:838
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xics/ics-rtas.c:ics_rtas_unmask_irq
```
```
In arch/powerpc/sysdev/xics/ics-opal.c (c0000000000bc1c0)
Location: include/linux/irq.h:838
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xics/ics-opal.c:ics_opal_unmask_irq
```
```
In arch/powerpc/sysdev/xive/common.c (c0000000000be870)
Location: include/linux/irq.h:838
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/common.c:xive_irq_startup
```
```
In kernel/irq/chip.c (c0000000001d9be4)
Location: include/linux/irq.h:838
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (c0000000001e0db0)
Location: include/linux/irq.h:838
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
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
In kernel/irq/chip.c (ffffffe0001177f6)
Location: include/linux/irq.h:838
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In drivers/irqchip/irq-sifive-plic.c (ffffffe0004957b0)
Location: include/linux/irq.h:838
Inline: True
Inline callers:
  - drivers/irqchip/irq-sifive-plic.c:plic_irq_unmask
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
In arch/x86/kernel/apic/vector.c (ffffffff810685a2)
Location: include/linux/irq.h:838
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
```
```
In kernel/irq/chip.c (ffffffff8111389a)
Location: include/linux/irq.h:838
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff81118d57)
Location: include/linux/irq.h:838
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff81058912)
Location: include/linux/irq.h:838
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
```
```
In kernel/irq/chip.c (ffffffff811045aa)
Location: include/linux/irq.h:838
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff81109dc7)
Location: include/linux/irq.h:838
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff81068a52)
Location: include/linux/irq.h:838
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
```
```
In kernel/irq/chip.c (ffffffff8111178a)
Location: include/linux/irq.h:838
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff81116c47)
Location: include/linux/irq.h:838
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff8106a1bb)
Location: include/linux/irq.h:838
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
```
```
In kernel/irq/chip.c (ffffffff8111cd4a)
Location: include/linux/irq.h:838
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff811222c7)
Location: include/linux/irq.h:838
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
</details>
</li>
</ul>

## Differences
