# Function: <code>iret_to_self</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103cf4e)
Location: arch/x86/include/asm/sync_core.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke_early
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81052456)
Location: arch/x86/include/asm/sync_core.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In kernel/sched/core.c (ffffffff810d6b10)
Location: arch/x86/include/asm/sync_core.h:22
Inline: True
Inline callers:
  - kernel/sched/core.c:sync_core_before_usermode
```
```
In kernel/sched/membarrier.c (ffffffff81108adb)
Location: arch/x86/include/asm/sync_core.h:22
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:ipi_sync_core
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
In arch/x86/kernel/alternative.c (ffffffff8103e7ee)
Location: arch/x86/include/asm/sync_core.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke_early
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81053d06)
Location: arch/x86/include/asm/sync_core.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In kernel/sched/core.c (ffffffff810d87e7)
Location: arch/x86/include/asm/sync_core.h:22
Inline: True
Inline callers:
  - kernel/sched/core.c:sync_core_before_usermode
```
```
In kernel/sched/membarrier.c (ffffffff8110a9c2)
Location: arch/x86/include/asm/sync_core.h:22
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:ipi_sync_core
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
In arch/x86/kernel/alternative.c (ffffffff8104455e)
Location: arch/x86/include/asm/sync_core.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke_early
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105c536)
Location: arch/x86/include/asm/sync_core.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In kernel/sched/core.c (ffffffff810ec077)
Location: arch/x86/include/asm/sync_core.h:22
Inline: True
Inline callers:
  - kernel/sched/core.c:sync_core_before_usermode
```
```
In kernel/sched/membarrier.c (ffffffff81129152)
Location: arch/x86/include/asm/sync_core.h:22
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:ipi_sync_core
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
In arch/x86/kernel/alternative.c (ffffffff8104c914)
Location: arch/x86/include/asm/sync_core.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke_early
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81068c40)
Location: arch/x86/include/asm/sync_core.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In kernel/sched/core.c (ffffffff8110652b)
Location: arch/x86/include/asm/sync_core.h:22
Inline: True
Inline callers:
  - kernel/sched/core.c:sync_core_before_usermode
```
```
In kernel/sched/build_utility.c (ffffffff8113c0a6)
Location: arch/x86/include/asm/sync_core.h:22
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:ipi_sync_core
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
In arch/x86/kernel/alternative.c (ffffffff81058c74)
Location: arch/x86/include/asm/sync_core.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke_early
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81076614)
Location: arch/x86/include/asm/sync_core.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In kernel/sched/core.c (ffffffff8112c1f2)
Location: arch/x86/include/asm/sync_core.h:22
Inline: True
Inline callers:
  - kernel/sched/core.c:sync_core_before_usermode
```
```
In kernel/sched/build_utility.c (ffffffff81166ccd)
Location: arch/x86/include/asm/sync_core.h:22
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:ipi_sync_core
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
In arch/x86/kernel/alternative.c (ffffffff8105a544)
Location: arch/x86/include/asm/sync_core.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke_early
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81078888)
Location: arch/x86/include/asm/sync_core.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In kernel/sched/core.c (ffffffff811392f2)
Location: arch/x86/include/asm/sync_core.h:22
Inline: True
Inline callers:
  - kernel/sched/core.c:sync_core_before_usermode
```
```
In kernel/sched/build_utility.c (ffffffff8117713d)
Location: arch/x86/include/asm/sync_core.h:22
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:ipi_sync_core
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
In arch/x86/kernel/alternative.c (ffffffff810616b4)
Location: arch/x86/include/asm/sync_core.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke_early
  - arch/x86/kernel/alternative.c:optimize_nops_inplace
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8107fd38)
Location: arch/x86/include/asm/sync_core.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In kernel/sched/core.c (ffffffff811440f2)
Location: arch/x86/include/asm/sync_core.h:22
Inline: True
Inline callers:
  - kernel/sched/core.c:sync_core_before_usermode
```
```
In kernel/sched/build_utility.c (ffffffff811850ad)
Location: arch/x86/include/asm/sync_core.h:22
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:ipi_sync_core
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
