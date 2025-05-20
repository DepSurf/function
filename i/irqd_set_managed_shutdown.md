# Function: <code>irqd_set_managed_shutdown</code>

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
In kernel/irq/chip.c (ffffffff810e9ae3)
Location: kernel/irq/internals.h:205
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff810ee918)
Location: kernel/irq/internals.h:205
Inline: True
Inline callers:
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
In kernel/irq/chip.c (ffffffff810f1fc0)
Location: kernel/irq/internals.h:208
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff810f73ca)
Location: kernel/irq/internals.h:208
Inline: True
Inline callers:
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
In kernel/irq/chip.c (ffffffff810fa40c)
Location: kernel/irq/internals.h:208
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff810ff6f9)
Location: kernel/irq/internals.h:208
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
In kernel/irq/chip.c (ffffffff81105bcc)
Location: kernel/irq/internals.h:208
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff8110aeeb)
Location: kernel/irq/internals.h:208
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
In kernel/irq/chip.c (ffffffff8110f08a)
Location: kernel/irq/internals.h:215
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff811145aa)
Location: kernel/irq/internals.h:215
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
In kernel/irq/chip.c (ffffffff8111b34a)
Location: kernel/irq/internals.h:213
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff8112070a)
Location: kernel/irq/internals.h:213
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
In kernel/irq/chip.c (ffffffff811274fb)
Location: kernel/irq/internals.h:213
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff8112cba8)
Location: kernel/irq/internals.h:213
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
In kernel/irq/chip.c (ffffffff811230fb)
Location: kernel/irq/internals.h:213
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff811285d8)
Location: kernel/irq/internals.h:213
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
In kernel/irq/chip.c (ffffffff811233ee)
Location: kernel/irq/internals.h:213
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff8112889f)
Location: kernel/irq/internals.h:213
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
In kernel/irq/chip.c (ffffffff811439be)
Location: kernel/irq/internals.h:213
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff81148e6c)
Location: kernel/irq/internals.h:213
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
In kernel/irq/chip.c (ffffffff81167828)
Location: kernel/irq/internals.h:215
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff8116d9ec)
Location: kernel/irq/internals.h:215
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
```
In kernel/irq/msi.c (ffffffff8116f70a)
Location: kernel/irq/internals.h:215
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
In kernel/irq/chip.c (ffffffff8119bbf8)
Location: kernel/irq/internals.h:217
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff811a2be8)
Location: kernel/irq/internals.h:217
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
```
In kernel/irq/msi.c (ffffffff811a4bdf)
Location: kernel/irq/internals.h:217
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
In kernel/irq/chip.c (ffffffff811ad9f7)
Location: kernel/irq/internals.h:222
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff811b4ae8)
Location: kernel/irq/internals.h:222
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
```
In kernel/irq/msi.c (ffffffff811b6b0e)
Location: kernel/irq/internals.h:222
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
In kernel/irq/chip.c (ffffffff811bd5f7)
Location: kernel/irq/internals.h:222
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff811c4968)
Location: kernel/irq/internals.h:222
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
```
In kernel/irq/msi.c (ffffffff811c69e0)
Location: kernel/irq/internals.h:222
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
In kernel/irq/chip.c (ffff80001017f310)
Location: kernel/irq/internals.h:213
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffff8000101863bc)
Location: kernel/irq/internals.h:213
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
In kernel/irq/chip.c (c03cf4fc)
Location: kernel/irq/internals.h:213
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (c03d52b0)
Location: kernel/irq/internals.h:213
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
In kernel/irq/chip.c (c0000000001d9ccc)
Location: kernel/irq/internals.h:213
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (c0000000001e0cc0)
Location: kernel/irq/internals.h:213
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
In kernel/irq/chip.c (ffffffe00011788a)
Location: kernel/irq/internals.h:213
Inline: True
Inline callers:
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
In kernel/irq/chip.c (ffffffff8111392a)
Location: kernel/irq/internals.h:213
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff81118cea)
Location: kernel/irq/internals.h:213
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
In kernel/irq/chip.c (ffffffff8110463a)
Location: kernel/irq/internals.h:213
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff81109d5a)
Location: kernel/irq/internals.h:213
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
In kernel/irq/chip.c (ffffffff8111181a)
Location: kernel/irq/internals.h:213
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff81116bda)
Location: kernel/irq/internals.h:213
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
In kernel/irq/chip.c (ffffffff8111cdda)
Location: kernel/irq/internals.h:213
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/cpuhotplug.c (ffffffff81122253)
Location: kernel/irq/internals.h:213
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
</details>
</li>
</ul>

## Differences
