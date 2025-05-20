# Function: <code>irqentry_nmi_enter</code>

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
irqentry_state_t irqentry_nmi_enter(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff81c38870)
Location: kernel/entry/common.c:436
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
  - arch/x86/kernel/sev-es.c:safe_stack_exc_vmm_communication
```
**Symbols:**

```
ffffffff81c38870-ffffffff81c388b9: irqentry_nmi_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
irqentry_state_t irqentry_nmi_enter(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff81c2ac70)
Location: kernel/entry/common.c:445
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
  - arch/x86/kernel/sev.c:kernel_exc_vmm_communication
```
**Symbols:**

```
ffffffff81c2ac70-ffffffff81c2acb9: irqentry_nmi_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
irqentry_state_t irqentry_nmi_enter(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff81d49210)
Location: kernel/entry/common.c:443
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
  - arch/x86/kernel/sev.c:kernel_exc_vmm_communication
```
**Symbols:**

```
ffffffff81d49210-ffffffff81d49254: irqentry_nmi_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
irqentry_state_t irqentry_nmi_enter(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff81f186d0)
Location: kernel/entry/common.c:443
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
  - arch/x86/kernel/sev.c:kernel_exc_vmm_communication
```
**Symbols:**

```
ffffffff81f186d0-ffffffff81f18720: irqentry_nmi_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
irqentry_state_t irqentry_nmi_enter(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff820bfc70)
Location: kernel/entry/common.c:447
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
  - arch/x86/kernel/sev.c:kernel_exc_vmm_communication
```
**Symbols:**

```
ffffffff820bfc70-ffffffff820bfcc0: irqentry_nmi_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
irqentry_state_t irqentry_nmi_enter(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff82141a50)
Location: kernel/entry/common.c:448
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
  - arch/x86/kernel/sev.c:kernel_exc_vmm_communication
```
**Symbols:**

```
ffffffff82141a50-ffffffff82141ab9: irqentry_nmi_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
irqentry_state_t irqentry_nmi_enter(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff82223980)
Location: kernel/entry/common.c:363
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
  - arch/x86/kernel/sev.c:kernel_exc_vmm_communication
```
**Symbols:**

```
ffffffff82223980-ffffffff822239e9: irqentry_nmi_enter (STB_GLOBAL)
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
