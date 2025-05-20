# Function: <code>irqentry_nmi_exit</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
void irqentry_nmi_exit(struct pt_regs *regs, irqentry_state_t irq_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff81c388c0)
Location: kernel/entry/common.c:455
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
  - arch/x86/kernel/sev-es.c:safe_stack_exc_vmm_communication
```
**Symbols:**

```
ffffffff81c388c0-ffffffff81c38902: irqentry_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void irqentry_nmi_exit(struct pt_regs *regs, irqentry_state_t irq_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff81c2acc0)
Location: kernel/entry/common.c:464
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
  - arch/x86/kernel/sev.c:kernel_exc_vmm_communication
```
**Symbols:**

```
ffffffff81c2acc0-ffffffff81c2ad02: irqentry_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void irqentry_nmi_exit(struct pt_regs *regs, irqentry_state_t irq_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff81d49260)
Location: kernel/entry/common.c:462
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
  - arch/x86/kernel/sev.c:kernel_exc_vmm_communication
```
**Symbols:**

```
ffffffff81d49260-ffffffff81d4929d: irqentry_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void irqentry_nmi_exit(struct pt_regs *regs, irqentry_state_t irq_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff81f18720)
Location: kernel/entry/common.c:462
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
  - arch/x86/kernel/sev.c:kernel_exc_vmm_communication
```
**Symbols:**

```
ffffffff81f18720-ffffffff81f18760: irqentry_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void irqentry_nmi_exit(struct pt_regs *regs, irqentry_state_t irq_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff820bfcd0)
Location: kernel/entry/common.c:467
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
  - arch/x86/kernel/sev.c:kernel_exc_vmm_communication
```
**Symbols:**

```
ffffffff820bfcd0-ffffffff820bfd10: irqentry_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void irqentry_nmi_exit(struct pt_regs *regs, irqentry_state_t irq_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff82141ad0)
Location: kernel/entry/common.c:468
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
  - arch/x86/kernel/sev.c:kernel_exc_vmm_communication
```
**Symbols:**

```
ffffffff82141ad0-ffffffff82141b29: irqentry_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void irqentry_nmi_exit(struct pt_regs *regs, irqentry_state_t irq_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff82223a00)
Location: kernel/entry/common.c:383
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
  - arch/x86/kernel/sev.c:kernel_exc_vmm_communication
```
**Symbols:**

```
ffffffff82223a00-ffffffff82223a59: irqentry_nmi_exit (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
