# Function: <code>irqd_is_started</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810e990c)
Location: include/linux/irq.h:360
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_shutdown
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/irq.h:360
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
In kernel/irq/chip.c (ffffffff810f1ddc)
Location: include/linux/irq.h:372
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_shutdown
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/irq.h:372
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
In kernel/irq/chip.c (ffffffff810fa215)
Location: include/linux/irq.h:367
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_shutdown
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff810ff4d2)
Location: include/linux/irq.h:367
Inline: True
Inline callers:
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
In kernel/irq/chip.c (ffffffff811059d5)
Location: include/linux/irq.h:368
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_shutdown
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff8110acb2)
Location: include/linux/irq.h:368
Inline: True
Inline callers:
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
In kernel/irq/chip.c (ffffffff8110eee5)
Location: include/linux/irq.h:368
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff81114372)
Location: include/linux/irq.h:368
Inline: True
Inline callers:
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
In kernel/irq/chip.c (ffffffff8111b1a5)
Location: include/linux/irq.h:371
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff811204d2)
Location: include/linux/irq.h:371
Inline: True
Inline callers:
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
In kernel/irq/chip.c (ffffffff81127495)
Location: include/linux/irq.h:387
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff8112c9e1)
Location: include/linux/irq.h:387
Inline: True
Inline callers:
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
In kernel/irq/chip.c (ffffffff81123095)
Location: include/linux/irq.h:397
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff81128411)
Location: include/linux/irq.h:397
Inline: True
Inline callers:
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
In arch/x86/kernel/apic/msi.c (ffffffff8107505e)
Location: include/linux/irq.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In kernel/irq/chip.c (ffffffff81123397)
Location: include/linux/irq.h:397
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff811286d1)
Location: include/linux/irq.h:397
Inline: True
Inline callers:
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
In arch/x86/kernel/apic/msi.c (ffffffff8108250e)
Location: include/linux/irq.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In kernel/irq/chip.c (ffffffff81143967)
Location: include/linux/irq.h:399
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff81148ca1)
Location: include/linux/irq.h:399
Inline: True
Inline callers:
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
In arch/x86/kernel/apic/msi.c (ffffffff810920f6)
Location: include/linux/irq.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In kernel/irq/chip.c (ffffffff81167738)
Location: include/linux/irq.h:399
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff8116d892)
Location: include/linux/irq.h:399
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:migrate_one_irq
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
In arch/x86/kernel/apic/msi.c (ffffffff810a70e6)
Location: include/linux/irq.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In kernel/irq/chip.c (ffffffff8119bb08)
Location: include/linux/irq.h:401
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff811a2a92)
Location: include/linux/irq.h:401
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:migrate_one_irq
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
In arch/x86/kernel/apic/msi.c (ffffffff810aa346)
Location: include/linux/irq.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In kernel/irq/chip.c (ffffffff811ad765)
Location: include/linux/irq.h:404
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff811b4992)
Location: include/linux/irq.h:404
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:migrate_one_irq
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
In arch/x86/kernel/apic/msi.c (ffffffff810b13d6)
Location: include/linux/irq.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In kernel/irq/chip.c (ffffffff811bd365)
Location: include/linux/irq.h:401
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff811c4812)
Location: include/linux/irq.h:401
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:migrate_one_irq
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
In kernel/irq/chip.c (ffff80001017f0f8)
Location: include/linux/irq.h:371
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffff8000101862a4)
Location: include/linux/irq.h:371
Inline: True
Inline callers:
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
In kernel/irq/chip.c (c03cf2ec)
Location: include/linux/irq.h:371
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (c03d50dc)
Location: include/linux/irq.h:371
Inline: True
Inline callers:
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
In arch/powerpc/sysdev/xive/common.c (c0000000000be654)
Location: include/linux/irq.h:371
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/common.c:xive_irq_set_affinity
```
```
In kernel/irq/chip.c (c0000000001d99c4)
Location: include/linux/irq.h:371
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (c0000000001e0b04)
Location: include/linux/irq.h:371
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffe0001176ce)
Location: include/linux/irq.h:371
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
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
In kernel/irq/chip.c (ffffffff81113785)
Location: include/linux/irq.h:371
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff81118ab2)
Location: include/linux/irq.h:371
Inline: True
Inline callers:
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
In kernel/irq/chip.c (ffffffff81104495)
Location: include/linux/irq.h:371
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff81109b22)
Location: include/linux/irq.h:371
Inline: True
Inline callers:
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
In kernel/irq/chip.c (ffffffff81111675)
Location: include/linux/irq.h:371
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff811169a2)
Location: include/linux/irq.h:371
Inline: True
Inline callers:
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
In kernel/irq/chip.c (ffffffff8111cc35)
Location: include/linux/irq.h:371
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff81121fe0)
Location: include/linux/irq.h:371
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
</details>
</li>
</ul>

## Differences
