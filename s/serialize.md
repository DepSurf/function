# Function: <code>serialize</code>

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
In arch/x86/kernel/alternative.c (ffffffff8103cf4a)
Location: arch/x86/include/asm/special_insns.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke_early
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105242f)
Location: arch/x86/include/asm/special_insns.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In kernel/sched/core.c (ffffffff810d6b0c)
Location: arch/x86/include/asm/special_insns.h:239
Inline: True
Inline callers:
  - kernel/sched/core.c:sync_core_before_usermode
```
```
In kernel/sched/membarrier.c (ffffffff81108ad7)
Location: arch/x86/include/asm/special_insns.h:239
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
In arch/x86/kernel/alternative.c (ffffffff8103e7ea)
Location: arch/x86/include/asm/special_insns.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke_early
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81053cdf)
Location: arch/x86/include/asm/special_insns.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In kernel/sched/core.c (ffffffff810d87e3)
Location: arch/x86/include/asm/special_insns.h:239
Inline: True
Inline callers:
  - kernel/sched/core.c:sync_core_before_usermode
```
```
In kernel/sched/membarrier.c (ffffffff8110a9be)
Location: arch/x86/include/asm/special_insns.h:239
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
In arch/x86/kernel/alternative.c (ffffffff8104455a)
Location: arch/x86/include/asm/special_insns.h:227
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke_early
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105c50f)
Location: arch/x86/include/asm/special_insns.h:227
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In kernel/sched/core.c (ffffffff810ec073)
Location: arch/x86/include/asm/special_insns.h:227
Inline: True
Inline callers:
  - kernel/sched/core.c:sync_core_before_usermode
```
```
In kernel/sched/membarrier.c (ffffffff8112914e)
Location: arch/x86/include/asm/special_insns.h:227
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
In arch/x86/kernel/alternative.c (ffffffff8104c90a)
Location: arch/x86/include/asm/special_insns.h:228
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke_early
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81068c09)
Location: arch/x86/include/asm/special_insns.h:228
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In kernel/sched/core.c (ffffffff81106521)
Location: arch/x86/include/asm/special_insns.h:228
Inline: True
Inline callers:
  - kernel/sched/core.c:sync_core_before_usermode
```
```
In kernel/sched/build_utility.c (ffffffff8113c09c)
Location: arch/x86/include/asm/special_insns.h:228
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
In arch/x86/kernel/alternative.c (ffffffff81058c6a)
Location: arch/x86/include/asm/special_insns.h:228
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke_early
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81076601)
Location: arch/x86/include/asm/special_insns.h:228
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In kernel/sched/core.c (ffffffff8112c1e1)
Location: arch/x86/include/asm/special_insns.h:228
Inline: True
Inline callers:
  - kernel/sched/core.c:sync_core_before_usermode
```
```
In kernel/sched/build_utility.c (ffffffff81166cbc)
Location: arch/x86/include/asm/special_insns.h:228
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
In arch/x86/kernel/alternative.c (ffffffff8105a53a)
Location: arch/x86/include/asm/special_insns.h:207
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke_early
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8107886c)
Location: arch/x86/include/asm/special_insns.h:207
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In kernel/sched/core.c (ffffffff811392e1)
Location: arch/x86/include/asm/special_insns.h:207
Inline: True
Inline callers:
  - kernel/sched/core.c:sync_core_before_usermode
```
```
In kernel/sched/build_utility.c (ffffffff8117712c)
Location: arch/x86/include/asm/special_insns.h:207
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
In arch/x86/kernel/alternative.c (ffffffff810616aa)
Location: arch/x86/include/asm/special_insns.h:220
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke_early
  - arch/x86/kernel/alternative.c:optimize_nops_inplace
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8107fd1c)
Location: arch/x86/include/asm/special_insns.h:220
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In kernel/sched/core.c (ffffffff811440e1)
Location: arch/x86/include/asm/special_insns.h:220
Inline: True
Inline callers:
  - kernel/sched/core.c:sync_core_before_usermode
```
```
In kernel/sched/build_utility.c (ffffffff8118509c)
Location: arch/x86/include/asm/special_insns.h:220
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
