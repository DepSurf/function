# Function: <code>irqd_is_per_cpu</code>

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
In arch/x86/kernel/irq.c (ffffffff81030f12)
Location: include/linux/irq.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In kernel/irq/migration.c (ffffffff810e25cd)
Location: include/linux/irq.h:218
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
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
In arch/x86/kernel/irq.c (ffffffff8102ffb4)
Location: include/linux/irq.h:226
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
```
```
In kernel/irq/migration.c (ffffffff810e805d)
Location: include/linux/irq.h:226
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
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
In arch/x86/kernel/irq.c (ffffffff8102ff75)
Location: include/linux/irq.h:228
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
```
```
In kernel/irq/migration.c (ffffffff810eea9d)
Location: include/linux/irq.h:228
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
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
In arch/x86/kernel/irq.c (ffffffff8102e1e2)
Location: include/linux/irq.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
```
```
In kernel/irq/migration.c (ffffffff810ee5dd)
Location: include/linux/irq.h:242
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/irq.h:242
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
In kernel/irq/migration.c (ffffffff810f700d)
Location: include/linux/irq.h:247
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/irq.h:247
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
In kernel/irq/migration.c (ffffffff810ff33d)
Location: include/linux/irq.h:242
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff810ff4c5)
Location: include/linux/irq.h:242
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
In kernel/irq/migration.c (ffffffff8110ab1d)
Location: include/linux/irq.h:243
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff8110aca5)
Location: include/linux/irq.h:243
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
In kernel/irq/migration.c (ffffffff811141cd)
Location: include/linux/irq.h:243
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff81114365)
Location: include/linux/irq.h:243
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
In kernel/irq/migration.c (ffffffff8112033d)
Location: include/linux/irq.h:246
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff811204c5)
Location: include/linux/irq.h:246
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
In kernel/irq/migration.c (ffffffff8112c87d)
Location: include/linux/irq.h:252
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff8112c9d8)
Location: include/linux/irq.h:252
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
In kernel/irq/migration.c (ffffffff811282ad)
Location: include/linux/irq.h:257
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff81128408)
Location: include/linux/irq.h:257
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
In kernel/irq/migration.c (ffffffff8112856d)
Location: include/linux/irq.h:257
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff811286c8)
Location: include/linux/irq.h:257
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
In kernel/irq/migration.c (ffffffff81148b3d)
Location: include/linux/irq.h:259
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff81148c98)
Location: include/linux/irq.h:259
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
In kernel/irq/migration.c (ffffffff8116d679)
Location: include/linux/irq.h:259
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff8116d889)
Location: include/linux/irq.h:259
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
In kernel/irq/migration.c (ffffffff811a2819)
Location: include/linux/irq.h:261
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff811a2a89)
Location: include/linux/irq.h:261
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
In kernel/irq/migration.c (ffffffff811b4719)
Location: include/linux/irq.h:264
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff811b4989)
Location: include/linux/irq.h:264
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
In kernel/irq/migration.c (ffffffff811c4599)
Location: include/linux/irq.h:261
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff811c4809)
Location: include/linux/irq.h:261
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/cpuhotplug.c (ffff80001018629c)
Location: include/linux/irq.h:246
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/cpuhotplug.c (c03d50cc)
Location: include/linux/irq.h:246
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
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
In kernel/irq/cpuhotplug.c (c0000000001e0af8)
Location: include/linux/irq.h:246
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
</details>
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
In kernel/irq/migration.c (ffffffff8111891d)
Location: include/linux/irq.h:246
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff81118aa5)
Location: include/linux/irq.h:246
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
In kernel/irq/migration.c (ffffffff8110998d)
Location: include/linux/irq.h:246
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff81109b15)
Location: include/linux/irq.h:246
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
In kernel/irq/migration.c (ffffffff8111680d)
Location: include/linux/irq.h:246
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff81116995)
Location: include/linux/irq.h:246
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
In kernel/irq/migration.c (ffffffff81121e4d)
Location: include/linux/irq.h:246
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff81121fd3)
Location: include/linux/irq.h:246
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
</details>
</li>
</ul>

## Differences
