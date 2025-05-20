# Function: <code>irqd_is_activated</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810edd05)
Location: include/linux/irq.h:317
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:irq_domain_activate_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ed6b5)
Location: include/linux/irq.h:345
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:irq_domain_activate_irq
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
In arch/x86/kernel/apic/vector.c (ffffffff8105bee3)
Location: include/linux/irq.h:357
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In kernel/irq/chip.c (ffffffff810f1ecd)
Location: include/linux/irq.h:357
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/irqdomain.c (ffffffff810f60e5)
Location: include/linux/irq.h:357
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:irq_domain_activate_irq
```
```
In kernel/irq/msi.c (ffffffff810f826d)
Location: include/linux/irq.h:357
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_alloc_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff8105ed8c)
Location: include/linux/irq.h:352
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In kernel/irq/chip.c (ffffffff810fa301)
Location: include/linux/irq.h:352
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/irqdomain.c (ffffffff810fe455)
Location: include/linux/irq.h:352
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:irq_domain_activate_irq
```
```
In kernel/irq/msi.c (ffffffff81100650)
Location: include/linux/irq.h:352
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_alloc_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff81064cec)
Location: include/linux/irq.h:353
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In kernel/irq/chip.c (ffffffff81105ac1)
Location: include/linux/irq.h:353
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/irqdomain.c (ffffffff81109c25)
Location: include/linux/irq.h:353
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:irq_domain_activate_irq
```
```
In kernel/irq/msi.c (ffffffff8110be20)
Location: include/linux/irq.h:353
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_alloc_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff810683f1)
Location: include/linux/irq.h:353
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In kernel/irq/chip.c (ffffffff8110ef81)
Location: include/linux/irq.h:353
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/irqdomain.c (ffffffff811131f5)
Location: include/linux/irq.h:353
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:irq_domain_activate_irq
```
```
In kernel/irq/msi.c (ffffffff81115506)
Location: include/linux/irq.h:353
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_alloc_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff81068d31)
Location: include/linux/irq.h:356
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In kernel/irq/chip.c (ffffffff8111b241)
Location: include/linux/irq.h:356
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/irqdomain.c (ffffffff8111f495)
Location: include/linux/irq.h:356
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:irq_domain_activate_irq
```
```
In kernel/irq/msi.c (ffffffff81121718)
Location: include/linux/irq.h:356
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_alloc_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff8106f985)
Location: include/linux/irq.h:372
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In kernel/irq/manage.c (ffffffff81123a5b)
Location: include/linux/irq.h:372
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/chip.c (ffffffff81127411)
Location: include/linux/irq.h:372
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/irqdomain.c (ffffffff8112b9d5)
Location: include/linux/irq.h:372
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:irq_domain_activate_irq
```
```
In kernel/irq/msi.c (ffffffff8112dca7)
Location: include/linux/irq.h:372
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_alloc_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff81070e65)
Location: include/linux/irq.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In kernel/irq/manage.c (ffffffff8111f8ab)
Location: include/linux/irq.h:382
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/chip.c (ffffffff81123011)
Location: include/linux/irq.h:382
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/irqdomain.c (ffffffff81127495)
Location: include/linux/irq.h:382
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:irq_domain_activate_irq
```
```
In kernel/irq/msi.c (ffffffff811297ac)
Location: include/linux/irq.h:382
Inline: True
Inline callers:
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff81071645)
Location: include/linux/irq.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In kernel/irq/manage.c (ffffffff8111fb6b)
Location: include/linux/irq.h:382
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/chip.c (ffffffff81123311)
Location: include/linux/irq.h:382
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/irqdomain.c (ffffffff81127755)
Location: include/linux/irq.h:382
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:irq_domain_activate_irq
```
```
In kernel/irq/msi.c (ffffffff81129265)
Location: include/linux/irq.h:382
Inline: True
Inline callers:
  - kernel/irq/msi.c:__msi_domain_free_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff8107de65)
Location: include/linux/irq.h:384
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In kernel/irq/manage.c (ffffffff8114000b)
Location: include/linux/irq.h:384
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/chip.c (ffffffff811438e1)
Location: include/linux/irq.h:384
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/irqdomain.c (ffffffff81147cc5)
Location: include/linux/irq.h:384
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:irq_domain_activate_irq
```
```
In kernel/irq/msi.c (ffffffff81149a85)
Location: include/linux/irq.h:384
Inline: True
Inline callers:
  - kernel/irq/msi.c:__msi_domain_free_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff8108cb25)
Location: include/linux/irq.h:384
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In kernel/irq/manage.c (ffffffff8116390b)
Location: include/linux/irq.h:384
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/chip.c (ffffffff811676a1)
Location: include/linux/irq.h:384
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/irqdomain.c (ffffffff8116c185)
Location: include/linux/irq.h:384
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:irq_domain_activate_irq
```
```
In kernel/irq/msi.c (ffffffff8116eba4)
Location: include/linux/irq.h:384
Inline: True
Inline callers:
  - kernel/irq/msi.c:__msi_domain_free_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff810a1135)
Location: include/linux/irq.h:386
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
```
```
In kernel/irq/manage.c (ffffffff811975db)
Location: include/linux/irq.h:386
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/chip.c (ffffffff8119ba61)
Location: include/linux/irq.h:386
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/irqdomain.c (ffffffff811a10c5)
Location: include/linux/irq.h:386
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:irq_domain_activate_irq
```
```
In kernel/irq/msi.c (ffffffff811a4712)
Location: include/linux/irq.h:386
Inline: True
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
In arch/x86/kernel/apic/vector.c (ffffffff810a4125)
Location: include/linux/irq.h:389
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
```
```
In kernel/irq/manage.c (ffffffff811a917f)
Location: include/linux/irq.h:389
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/chip.c (ffffffff811ad8b1)
Location: include/linux/irq.h:389
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/irqdomain.c (ffffffff811b2f25)
Location: include/linux/irq.h:389
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:irq_domain_activate_irq
```
```
In kernel/irq/msi.c (ffffffff811b66fa)
Location: include/linux/irq.h:389
Inline: True
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
In arch/x86/kernel/apic/vector.c (ffffffff810ab155)
Location: include/linux/irq.h:386
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In kernel/irq/manage.c (ffffffff811b8cdf)
Location: include/linux/irq.h:386
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/chip.c (ffffffff811bd4b1)
Location: include/linux/irq.h:386
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/irqdomain.c (ffffffff811c2d45)
Location: include/linux/irq.h:386
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:irq_domain_activate_irq
```
```
In kernel/irq/msi.c (ffffffff811c65ea)
Location: include/linux/irq.h:386
Inline: True
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
In kernel/irq/chip.c (ffff80001017f1bc)
Location: include/linux/irq.h:356
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/irqdomain.c (ffff800010185120)
Location: include/linux/irq.h:356
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:irq_domain_activate_irq
```
```
In kernel/irq/msi.c (ffff8000101879bc)
Location: include/linux/irq.h:356
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_alloc_irqs
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
In kernel/irq/chip.c (c03cf3a4)
Location: include/linux/irq.h:356
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/irqdomain.c (c03d41e8)
Location: include/linux/irq.h:356
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:irq_domain_activate_irq
```
```
In kernel/irq/msi.c (c03d65a4)
Location: include/linux/irq.h:356
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (c0000000001d9afc)
Location: include/linux/irq.h:356
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_startup
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
In kernel/irq/chip.c (ffffffe00011777c)
Location: include/linux/irq.h:356
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/irqdomain.c (ffffffe00011beaa)
Location: include/linux/irq.h:356
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:irq_domain_activate_irq
```
```
In kernel/irq/msi.c (ffffffe00011d4a4)
Location: include/linux/irq.h:356
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_alloc_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff81068821)
Location: include/linux/irq.h:356
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In kernel/irq/chip.c (ffffffff81113821)
Location: include/linux/irq.h:356
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/irqdomain.c (ffffffff81117a75)
Location: include/linux/irq.h:356
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:irq_domain_activate_irq
```
```
In kernel/irq/msi.c (ffffffff81119cf8)
Location: include/linux/irq.h:356
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_alloc_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff81058b91)
Location: include/linux/irq.h:356
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In kernel/irq/chip.c (ffffffff81104531)
Location: include/linux/irq.h:356
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/irqdomain.c (ffffffff81108765)
Location: include/linux/irq.h:356
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:irq_domain_activate_irq
```
```
In kernel/irq/msi.c (ffffffff8110ad68)
Location: include/linux/irq.h:356
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_alloc_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff81068cd1)
Location: include/linux/irq.h:356
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In kernel/irq/chip.c (ffffffff81111711)
Location: include/linux/irq.h:356
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/irqdomain.c (ffffffff81115965)
Location: include/linux/irq.h:356
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:irq_domain_activate_irq
```
```
In kernel/irq/msi.c (ffffffff81117be8)
Location: include/linux/irq.h:356
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_alloc_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff8106a483)
Location: include/linux/irq.h:356
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In kernel/irq/chip.c (ffffffff8111ccd1)
Location: include/linux/irq.h:356
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_startup
```
```
In kernel/irq/irqdomain.c (ffffffff81120f95)
Location: include/linux/irq.h:356
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:irq_domain_activate_irq
```
```
In kernel/irq/msi.c (ffffffff81123278)
Location: include/linux/irq.h:356
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
</details>
</li>
</ul>

## Differences
