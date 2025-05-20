# Function: <code>spin_is_locked</code>

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
In kernel/futex.c (ffffffff810ff943)
Location: include/linux/spinlock.h:385
Inline: True
Inline callers:
  - kernel/futex.c:__unqueue_futex
```
```
In ipc/sem.c (ffffffff813286b4)
Location: include/linux/spinlock.h:385
Inline: True
Inline callers:
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
```
```
In arch/x86/pci/i386.c (ffffffff816f5f95)
Location: include/linux/spinlock.h:385
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_fwaddrmap_lookup
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
In kernel/futex.c (ffffffff81106d53)
Location: include/linux/spinlock.h:385
Inline: True
Inline callers:
  - kernel/futex.c:__unqueue_futex
```
```
In ipc/sem.c (ffffffff8135d307)
Location: include/linux/spinlock.h:385
Inline: True
Inline callers:
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
```
```
In arch/x86/pci/i386.c (ffffffff8175ac55)
Location: include/linux/spinlock.h:385
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_fwaddrmap_lookup
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
In kernel/futex.c (ffffffff8110e513)
Location: include/linux/spinlock.h:385
Inline: True
Inline callers:
  - kernel/futex.c:__unqueue_futex
```
```
In arch/x86/pci/i386.c (ffffffff817871b5)
Location: include/linux/spinlock.h:385
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_fwaddrmap_lookup
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
In kernel/futex.c (ffffffff8110fc83)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - kernel/futex.c:__unqueue_futex
```
```
In drivers/md/md.c (ffffffff817398de)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - drivers/md/md.c:set_in_sync
```
```
In arch/x86/pci/i386.c (ffffffff817a63c5)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_fwaddrmap_lookup
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
In kernel/futex.c (ffffffff8111af73)
Location: include/linux/spinlock.h:383
Inline: True
Inline callers:
  - kernel/futex.c:__unqueue_futex
```
```
In arch/x86/pci/i386.c (ffffffff8181d645)
Location: include/linux/spinlock.h:383
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_fwaddrmap_lookup
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
In kernel/futex.c (ffffffff81127e33)
Location: include/linux/spinlock.h:401
Inline: True
Inline callers:
  - kernel/futex.c:__unqueue_futex
```
```
In arch/x86/pci/i386.c (ffffffff81867815)
Location: include/linux/spinlock.h:401
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_fwaddrmap_lookup
```
```
In net/core/dev.c (0)
Location: include/linux/spinlock.h:401
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff818cd9e9)
Location: include/linux/spinlock.h:401
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In net/core/dev.c (0)
Location: include/linux/spinlock.h:420
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff818f8c29)
Location: include/linux/spinlock.h:420
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In net/core/dev.c (0)
Location: include/linux/spinlock.h:429
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff819583f9)
Location: include/linux/spinlock.h:429
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In net/core/dev.c (0)
Location: include/linux/spinlock.h:429
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff8198e8a9)
Location: include/linux/spinlock.h:429
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In net/core/dev.c (0)
Location: include/linux/spinlock.h:444
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81a666bf)
Location: include/linux/spinlock.h:444
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In net/core/dev.c (0)
Location: include/linux/spinlock.h:445
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81a6e79f)
Location: include/linux/spinlock.h:445
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In net/core/dev.c (0)
Location: include/linux/spinlock.h:445
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81a5702f)
Location: include/linux/spinlock.h:445
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In net/core/dev.c (0)
Location: include/linux/spinlock.h:454
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81b0fe64)
Location: include/linux/spinlock.h:454
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In net/core/dev.c (0)
Location: include/linux/spinlock.h:440
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81c96fef)
Location: include/linux/spinlock.h:440
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In net/core/dev.c (0)
Location: include/linux/spinlock.h:441
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81e52dcf)
Location: include/linux/spinlock.h:441
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In net/core/dev.c (0)
Location: include/linux/spinlock.h:442
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81eae65b)
Location: include/linux/spinlock.h:442
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In net/core/dev.c (0)
Location: include/linux/spinlock.h:442
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81f710d6)
Location: include/linux/spinlock.h:442
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In net/core/dev.c (0)
Location: include/linux/spinlock.h:429
Inline: True
```
```
In net/sched/sch_generic.c (ffff800010c3a2a8)
Location: include/linux/spinlock.h:429
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In net/core/dev.c (0)
Location: include/linux/spinlock.h:429
Inline: True
```
```
In net/sched/sch_generic.c (c0d4c454)
Location: include/linux/spinlock.h:429
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In net/core/dev.c (0)
Location: include/linux/spinlock.h:429
Inline: True
```
```
In net/sched/sch_generic.c (c000000000d3328c)
Location: include/linux/spinlock.h:429
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In net/core/dev.c (0)
Location: include/linux/spinlock.h:429
Inline: True
```
```
In net/sched/sch_generic.c (ffffffe0007ab476)
Location: include/linux/spinlock.h:429
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In net/core/dev.c (0)
Location: include/linux/spinlock.h:429
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff8192e719)
Location: include/linux/spinlock.h:429
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In net/core/dev.c (0)
Location: include/linux/spinlock.h:429
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff818e8219)
Location: include/linux/spinlock.h:429
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In net/core/dev.c (0)
Location: include/linux/spinlock.h:429
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff8197f8a9)
Location: include/linux/spinlock.h:429
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In net/core/dev.c (0)
Location: include/linux/spinlock.h:429
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff819a1e05)
Location: include/linux/spinlock.h:429
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
</details>
</li>
</ul>

## Differences
