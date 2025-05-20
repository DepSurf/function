# Function: <code>irqd_affinity_is_managed</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (0)
Location: include/linux/irq.h:310
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (0)
Location: include/linux/irq.h:312
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
In kernel/irq/manage.c (ffffffff810e776e)
Location: include/linux/irq.h:340
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/chip.c (0)
Location: include/linux/irq.h:340
Inline: True
```
```
In kernel/irq/cpuhotplug.c (ffffffff810ee996)
Location: include/linux/irq.h:340
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
In arch/x86/kernel/apic/vector.c (ffffffff8105b4e0)
Location: include/linux/irq.h:352
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In kernel/irq/manage.c (ffffffff810efaee)
Location: include/linux/irq.h:352
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/chip.c (ffffffff810f201c)
Location: include/linux/irq.h:352
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff810f7446)
Location: include/linux/irq.h:352
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff8105edc7)
Location: include/linux/irq.h:347
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In kernel/irq/manage.c (ffffffff810f7f1b)
Location: include/linux/irq.h:347
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
```
```
In kernel/irq/chip.c (ffffffff810fa465)
Location: include/linux/irq.h:347
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff810ff756)
Location: include/linux/irq.h:347
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff81064d27)
Location: include/linux/irq.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In kernel/irq/manage.c (ffffffff81103669)
Location: include/linux/irq.h:348
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
```
```
In kernel/irq/chip.c (ffffffff81105c25)
Location: include/linux/irq.h:348
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff8110af56)
Location: include/linux/irq.h:348
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff8106842e)
Location: include/linux/irq.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In kernel/irq/manage.c (ffffffff8110c089)
Location: include/linux/irq.h:348
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
```
```
In kernel/irq/chip.c (ffffffff8110f0e5)
Location: include/linux/irq.h:348
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff81114617)
Location: include/linux/irq.h:348
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff81068d6e)
Location: include/linux/irq.h:351
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In kernel/irq/manage.c (ffffffff811184b9)
Location: include/linux/irq.h:351
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
```
```
In kernel/irq/chip.c (ffffffff8111b3a5)
Location: include/linux/irq.h:351
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff81120777)
Location: include/linux/irq.h:351
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff8106f9c6)
Location: include/linux/irq.h:367
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In kernel/irq/manage.c (ffffffff81123da9)
Location: include/linux/irq.h:367
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
```
```
In kernel/irq/chip.c (ffffffff81127545)
Location: include/linux/irq.h:367
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:__irq_startup_managed
```
```
In kernel/irq/cpuhotplug.c (ffffffff8112cd14)
Location: include/linux/irq.h:367
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff81070ea6)
Location: include/linux/irq.h:377
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In kernel/irq/manage.c (ffffffff8111fc09)
Location: include/linux/irq.h:377
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
```
```
In kernel/irq/chip.c (ffffffff81123145)
Location: include/linux/irq.h:377
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:__irq_startup_managed
```
```
In kernel/irq/cpuhotplug.c (ffffffff81128744)
Location: include/linux/irq.h:377
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff81071686)
Location: include/linux/irq.h:377
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In kernel/irq/manage.c (ffffffff8111feb9)
Location: include/linux/irq.h:377
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
```
```
In kernel/irq/chip.c (ffffffff811234a5)
Location: include/linux/irq.h:377
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff811289a5)
Location: include/linux/irq.h:377
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff8107dea6)
Location: include/linux/irq.h:379
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In kernel/irq/manage.c (ffffffff811403c9)
Location: include/linux/irq.h:379
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
```
```
In kernel/irq/chip.c (ffffffff81143a75)
Location: include/linux/irq.h:379
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff81148f85)
Location: include/linux/irq.h:379
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff8108cb65)
Location: include/linux/irq.h:379
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In kernel/irq/manage.c (ffffffff81163d29)
Location: include/linux/irq.h:379
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
```
```
In kernel/irq/chip.c (ffffffff81167865)
Location: include/linux/irq.h:379
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff8116db05)
Location: include/linux/irq.h:379
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
```
In kernel/irq/msi.c (ffffffff8116f4d1)
Location: include/linux/irq.h:379
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
In arch/x86/kernel/apic/vector.c (ffffffff810a1175)
Location: include/linux/irq.h:381
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In kernel/irq/manage.c (ffffffff81197a49)
Location: include/linux/irq.h:381
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
```
```
In kernel/irq/chip.c (ffffffff8119bc45)
Location: include/linux/irq.h:381
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff811a2d35)
Location: include/linux/irq.h:381
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
```
In kernel/irq/msi.c (ffffffff811a4afe)
Location: include/linux/irq.h:381
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
In arch/x86/kernel/apic/vector.c (ffffffff810a4165)
Location: include/linux/irq.h:384
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In kernel/irq/manage.c (ffffffff811a9709)
Location: include/linux/irq.h:384
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
```
```
In kernel/irq/chip.c (ffffffff811ae30e)
Location: include/linux/irq.h:384
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff811b4c35)
Location: include/linux/irq.h:384
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
```
In kernel/irq/msi.c (ffffffff811b6a2e)
Location: include/linux/irq.h:384
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
In arch/x86/kernel/apic/vector.c (ffffffff810ab195)
Location: include/linux/irq.h:381
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In kernel/irq/manage.c (ffffffff811b9269)
Location: include/linux/irq.h:381
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
```
```
In kernel/irq/chip.c (ffffffff811bdf0e)
Location: include/linux/irq.h:381
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff811c4ab5)
Location: include/linux/irq.h:381
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
```
In kernel/irq/msi.c (ffffffff811c68fd)
Location: include/linux/irq.h:381
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
In kernel/irq/manage.c (ffff80001017ad38)
Location: include/linux/irq.h:351
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/chip.c (ffff80001017f394)
Location: include/linux/irq.h:351
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffff8000101865c4)
Location: include/linux/irq.h:351
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
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
In kernel/irq/manage.c (c03cbf28)
Location: include/linux/irq.h:351
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
```
```
In kernel/irq/chip.c (c03cf5b0)
Location: include/linux/irq.h:351
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (c03d5344)
Location: include/linux/irq.h:351
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
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
In kernel/irq/manage.c (c0000000001d52b0)
Location: include/linux/irq.h:351
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
```
```
In kernel/irq/chip.c (c0000000001d9d54)
Location: include/linux/irq.h:351
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (c0000000001e0db0)
Location: include/linux/irq.h:351
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
In kernel/irq/manage.c (ffffffe000114a24)
Location: include/linux/irq.h:351
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
```
```
In kernel/irq/chip.c (ffffffe0001178e8)
Location: include/linux/irq.h:351
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
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
In arch/x86/kernel/apic/vector.c (ffffffff8106885e)
Location: include/linux/irq.h:351
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In kernel/irq/manage.c (ffffffff81110a99)
Location: include/linux/irq.h:351
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
```
```
In kernel/irq/chip.c (ffffffff81113985)
Location: include/linux/irq.h:351
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff81118d57)
Location: include/linux/irq.h:351
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff81058bce)
Location: include/linux/irq.h:351
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In kernel/irq/manage.c (ffffffff811017c9)
Location: include/linux/irq.h:351
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
```
```
In kernel/irq/chip.c (ffffffff81104695)
Location: include/linux/irq.h:351
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff81109dc7)
Location: include/linux/irq.h:351
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff81068d0e)
Location: include/linux/irq.h:351
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In kernel/irq/manage.c (ffffffff8110e989)
Location: include/linux/irq.h:351
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
```
```
In kernel/irq/chip.c (ffffffff81111875)
Location: include/linux/irq.h:351
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff81116c47)
Location: include/linux/irq.h:351
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff8106a4c0)
Location: include/linux/irq.h:351
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In kernel/irq/manage.c (ffffffff81119eb9)
Location: include/linux/irq.h:351
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
```
```
In kernel/irq/chip.c (ffffffff8111ce35)
Location: include/linux/irq.h:351
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff811222c7)
Location: include/linux/irq.h:351
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
</details>
</li>
</ul>

## Differences
