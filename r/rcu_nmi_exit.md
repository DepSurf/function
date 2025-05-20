# Function: <code>rcu_nmi_exit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void rcu_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810e7d10)
Location: kernel/rcu/tree.c:947
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_debug
```
**Symbols:**

```
ffffffff810e7d10-ffffffff810e7dc6: rcu_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void rcu_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810edf50)
Location: kernel/rcu/tree.c:1002
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_debug
```
**Symbols:**

```
ffffffff810edf50-ffffffff810ee006: rcu_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void rcu_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f5030)
Location: kernel/rcu/tree.c:1003
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_debug
```
**Symbols:**

```
ffffffff810f5030-ffffffff810f50e6: rcu_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rcu_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f5df0)
Location: kernel/rcu/tree.c:1086
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_debug
```
**Symbols:**

```
ffffffff810f5df0-ffffffff810f5e55: rcu_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rcu_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810ffc90)
Location: kernel/rcu/tree.c:1121
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_debug
```
**Symbols:**

```
ffffffff810ffc90-ffffffff810ffcf5: rcu_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rcu_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81107e20)
Location: kernel/rcu/tree.c:794
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_debug
  - kernel/extable.c:kernel_text_address
  - kernel/rcu/tree.c:rcu_irq_exit_irqson
```
**Symbols:**

```
ffffffff81107e20-ffffffff81107e8b: rcu_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rcu_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:709
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_debug
  - kernel/extable.c:kernel_text_address
```
**Symbols:**

```
ffffffff811133d0-ffffffff811133e0: rcu_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rcu_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111cf20)
Location: kernel/rcu/tree.c:670
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_debug
  - kernel/extable.c:kernel_text_address
```
**Symbols:**

```
ffffffff8111cf20-ffffffff8111cf9a: rcu_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rcu_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81129400)
Location: kernel/rcu/tree.c:678
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_debug
  - kernel/extable.c:kernel_text_address
```
**Symbols:**

```
ffffffff81129400-ffffffff81129486: rcu_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rcu_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81bbf990)
Location: kernel/rcu/tree.c:695
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
  - kernel/rcu/tree.c:rcu_irq_exit_preempt
  - kernel/rcu/tree.c:rcu_irq_exit
```
**Symbols:**

```
ffffffff81bbf990-ffffffff81bbf9fc: rcu_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rcu_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81c38770)
Location: kernel/rcu/tree.c:761
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_irq_exit_preempt
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/entry/common.c:irqentry_nmi_exit
```
**Symbols:**

```
ffffffff81c38770-ffffffff81c387dc: rcu_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rcu_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81c2ab70)
Location: kernel/rcu/tree.c:766
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_irq_exit_preempt
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/entry/common.c:irqentry_nmi_exit
```
**Symbols:**

```
ffffffff81c2ab70-ffffffff81c2abdc: rcu_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rcu_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81d49110)
Location: kernel/rcu/tree.c:741
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/entry/common.c:irqentry_nmi_exit
```
**Symbols:**

```
ffffffff81d49110-ffffffff81d4917d: rcu_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rcu_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81f18550)
Location: kernel/rcu/tree.c:751
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/entry/common.c:irqentry_nmi_exit
```
**Symbols:**

```
ffffffff81f18550-ffffffff81f185e9: rcu_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
void rcu_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:678
Inline: False
Direct callers:
  - arch/arm64/kernel/traps.c:do_serror
  - arch/arm64/kernel/acpi.c:apei_claim_sea
  - arch/arm64/kernel/sdei.c:__sdei_handler
  - arch/arm64/mm/fault.c:debug_exception_exit
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:kernel_text_address
  - drivers/irqchip/irq-gic-v3.c:gic_handle_irq
```
**Symbols:**

```
ffff800010190a90-ffff800010190aa8: rcu_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rcu_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:678
Inline: False
Direct callers:
  - arch/arm/kernel/traps.c:handle_fiq_as_nmi
  - kernel/extable.c:kernel_text_address
```
**Symbols:**

```
c03de67c-c03de69c: rcu_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rcu_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001ebd70)
Location: kernel/rcu/tree.c:678
Inline: False
Direct callers:
  - arch/powerpc/kernel/traps.c:machine_check_exception
  - arch/powerpc/kernel/traps.c:machine_check_exception
  - arch/powerpc/kernel/traps.c:system_reset_exception
  - arch/powerpc/kernel/watchdog.c:soft_nmi_interrupt
  - arch/powerpc/perf/core-book3s.c:perf_event_interrupt
  - kernel/extable.c:kernel_text_address
```
**Symbols:**

```
c0000000001ebd70-c0000000001ebe28: rcu_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rcu_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:678
Inline: False
Direct callers:
  - kernel/extable.c:kernel_text_address
```
**Symbols:**

```
ffffffe000124036-ffffffe000124056: rcu_nmi_exit (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void rcu_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811219e0)
Location: kernel/rcu/tree.c:678
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_debug
  - kernel/extable.c:kernel_text_address
```
**Symbols:**

```
ffffffff811219e0-ffffffff81121a66: rcu_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rcu_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81114050)
Location: kernel/rcu/tree.c:678
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_debug
  - kernel/extable.c:kernel_text_address
```
**Symbols:**

```
ffffffff81114050-ffffffff811140d6: rcu_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rcu_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111f8d0)
Location: kernel/rcu/tree.c:678
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_debug
  - kernel/extable.c:kernel_text_address
```
**Symbols:**

```
ffffffff8111f8d0-ffffffff8111f956: rcu_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rcu_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112ba40)
Location: kernel/rcu/tree.c:678
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_debug
  - kernel/extable.c:kernel_text_address
```
**Symbols:**

```
ffffffff8112ba40-ffffffff8112bac6: rcu_nmi_exit (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
