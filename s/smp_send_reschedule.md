# Function: <code>smp_send_reschedule</code>

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
In arch/x86/kernel/kvm.c (ffffffff81063bda)
Location: arch/x86/include/asm/smp.h:126
Inline: True
```
```
In kernel/sched/core.c (ffffffff810a49a4)
Location: arch/x86/include/asm/smp.h:126
Inline: True
Inline callers:
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:resched_curr
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
```
```
In kernel/sched/fair.c (ffffffff810be73b)
Location: arch/x86/include/asm/smp.h:126
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
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
In arch/x86/kernel/kvm.c (ffffffff810637f1)
Location: arch/x86/include/asm/smp.h:115
Inline: True
```
```
In kernel/sched/core.c (ffffffff810ae95c)
Location: arch/x86/include/asm/smp.h:115
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff810c1f1c)
Location: arch/x86/include/asm/smp.h:115
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
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
In arch/x86/kernel/kvm.c (ffffffff81066ca1)
Location: arch/x86/include/asm/smp.h:113
Inline: True
```
```
In kernel/sched/core.c (ffffffff810b4a38)
Location: arch/x86/include/asm/smp.h:113
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff810c7f2a)
Location: arch/x86/include/asm/smp.h:113
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
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
In arch/x86/kernel/kvm.c (ffffffff81065f66)
Location: arch/x86/include/asm/smp.h:113
Inline: True
```
```
In kernel/sched/core.c (ffffffff810b0b46)
Location: arch/x86/include/asm/smp.h:113
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff810c1bd3)
Location: arch/x86/include/asm/smp.h:113
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
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
In arch/x86/kernel/kvm.c (ffffffff81069e66)
Location: arch/x86/include/asm/smp.h:114
Inline: True
```
```
In kernel/sched/core.c (ffffffff810b7f92)
Location: arch/x86/include/asm/smp.h:114
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff810c9335)
Location: arch/x86/include/asm/smp.h:114
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
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
In arch/x86/kernel/kvm.c (ffffffff8106cae6)
Location: arch/x86/include/asm/smp.h:114
Inline: True
```
```
In kernel/sched/core.c (ffffffff810bfaf5)
Location: arch/x86/include/asm/smp.h:114
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff810c4c46)
Location: arch/x86/include/asm/smp.h:114
Inline: True
Inline callers:
  - kernel/sched/fair.c:kick_ilb
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
In arch/x86/kernel/kvm.c (ffffffff81072bf6)
Location: arch/x86/include/asm/smp.h:114
Inline: True
```
```
In kernel/sched/core.c (ffffffff810c8e62)
Location: arch/x86/include/asm/smp.h:114
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff810ce016)
Location: arch/x86/include/asm/smp.h:114
Inline: True
Inline callers:
  - kernel/sched/fair.c:kick_ilb
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
In arch/x86/kernel/kvm.c (ffffffff810764c6)
Location: arch/x86/include/asm/smp.h:115
Inline: True
```
```
In kernel/sched/core.c (ffffffff810d09b2)
Location: arch/x86/include/asm/smp.h:115
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff810d6429)
Location: arch/x86/include/asm/smp.h:115
Inline: True
Inline callers:
  - kernel/sched/fair.c:kick_ilb
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
In arch/x86/kernel/kvm.c (ffffffff810774d6)
Location: arch/x86/include/asm/smp.h:115
Inline: True
```
```
In kernel/sched/core.c (ffffffff810da961)
Location: arch/x86/include/asm/smp.h:115
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff810e0b29)
Location: arch/x86/include/asm/smp.h:115
Inline: True
Inline callers:
  - kernel/sched/fair.c:kick_ilb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e3fdf)
Location: arch/x86/include/asm/smp.h:115
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e1a16)
Location: arch/x86/include/asm/smp.h:105
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e3826)
Location: arch/x86/include/asm/smp.h:105
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810fa3f5)
Location: arch/x86/include/asm/smp.h:105
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811086fc)
Location: arch/x86/include/asm/smp.h:112
Inline: True
Inline callers:
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8112d69c)
Location: arch/x86/include/asm/smp.h:101
Inline: True
Inline callers:
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void smp_send_reschedule(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/smp.c (ffff80001009ce48)
Location: arch/arm64/kernel/smp.c:946
Inline: False
Direct callers:
  - virt/kvm/kvm_main.c:kvm_vcpu_kick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
  - kernel/sched/core.c:resched_curr
  - kernel/sched/fair.c:kick_ilb
```
**Symbols:**

```
ffff80001009ce48-ffff80001009cf34: smp_send_reschedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void smp_send_reschedule(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/smp.c (c031375c)
Location: arch/arm/kernel/smp.c:703
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
  - kernel/sched/fair.c:kick_ilb
```
**Symbols:**

```
c031375c-c0313898: smp_send_reschedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void smp_send_reschedule(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/smp.c (c000000000054d84)
Location: arch/powerpc/kernel/smp.c:330
Inline: True
Inline callers:
  - arch/powerpc/kernel/smp.c:smp_generic_kick_cpu
Direct callers:
  - arch/powerpc/platforms/powernv/subcore.c:cpu_update_split_mode
  - arch/powerpc/platforms/powernv/subcore.c:cpu_do_split
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
  - kernel/sched/fair.c:kick_ilb
```
**Symbols:**

```
c0000000000548d0-c00000000005498c: smp_send_reschedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void smp_send_reschedule(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/smp.c (ffffffe0000b7b64)
Location: arch/riscv/kernel/smp.c:207
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
  - kernel/sched/fair.c:kick_ilb
```
**Symbols:**

```
ffffffe0000b7b64-ffffffe0000b7bd2: smp_send_reschedule (STB_GLOBAL)
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
In arch/x86/kernel/kvm.c (ffffffff810764d6)
Location: arch/x86/include/asm/smp.h:115
Inline: True
```
```
In kernel/sched/core.c (ffffffff810d4e11)
Location: arch/x86/include/asm/smp.h:115
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff810dacd9)
Location: arch/x86/include/asm/smp.h:115
Inline: True
Inline callers:
  - kernel/sched/fair.c:kick_ilb
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
In arch/x86/kernel/kvm.c (ffffffff81066496)
Location: arch/x86/include/asm/smp.h:115
Inline: True
```
```
In kernel/sched/core.c (ffffffff810c3462)
Location: arch/x86/include/asm/smp.h:115
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff810c9ce9)
Location: arch/x86/include/asm/smp.h:115
Inline: True
Inline callers:
  - kernel/sched/fair.c:kick_ilb
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
In arch/x86/kernel/kvm.c (ffffffff81076486)
Location: arch/x86/include/asm/smp.h:115
Inline: True
```
```
In kernel/sched/core.c (ffffffff810d1c52)
Location: arch/x86/include/asm/smp.h:115
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff810d7059)
Location: arch/x86/include/asm/smp.h:115
Inline: True
Inline callers:
  - kernel/sched/fair.c:kick_ilb
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
In arch/x86/kernel/kvm.c (ffffffff810784d6)
Location: arch/x86/include/asm/smp.h:115
Inline: True
```
```
In kernel/sched/core.c (ffffffff810dc625)
Location: arch/x86/include/asm/smp.h:115
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff810e2a09)
Location: arch/x86/include/asm/smp.h:115
Inline: True
Inline callers:
  - kernel/sched/fair.c:kick_ilb
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
