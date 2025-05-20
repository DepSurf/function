# Function: <code>nmi_cpu_backtrace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool nmi_cpu_backtrace(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nmi_backtrace.c (ffffffff813edaf0)
Location: lib/nmi_backtrace.c:148
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:arch_trigger_all_cpu_backtrace_handler
```
**Symbols:**

```
ffffffff813edaf0-ffffffff813edb68: nmi_cpu_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool nmi_cpu_backtrace(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nmi_backtrace.c (ffffffff81433d30)
Location: lib/nmi_backtrace.c:75
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:arch_trigger_all_cpu_backtrace_handler
```
**Symbols:**

```
ffffffff81433d30-ffffffff81433d88: nmi_cpu_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool nmi_cpu_backtrace(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nmi_backtrace.c (ffffffff8144ff80)
Location: lib/nmi_backtrace.c:86
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:nmi_cpu_backtrace_handler
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff8144ff80-ffffffff81450016: nmi_cpu_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool nmi_cpu_backtrace(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nmi_backtrace.c (ffffffff818efcf0)
Location: lib/nmi_backtrace.c:87
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:nmi_cpu_backtrace_handler
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff818efcf0-ffffffff818efdbc: nmi_cpu_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool nmi_cpu_backtrace(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nmi_backtrace.c (ffffffff81976130)
Location: lib/nmi_backtrace.c:88
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:nmi_cpu_backtrace_handler
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff81976130-ffffffff819761fc: nmi_cpu_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
bool nmi_cpu_backtrace(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nmi_backtrace.c (0)
Location: lib/nmi_backtrace.c:88
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:nmi_cpu_backtrace_handler
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff819d2a63-ffffffff819d2ab5: nmi_cpu_backtrace.cold.4 (STB_LOCAL)
ffffffff819d2910-ffffffff819d2961: nmi_cpu_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
bool nmi_cpu_backtrace(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nmi_backtrace.c (0)
Location: lib/nmi_backtrace.c:88
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:nmi_cpu_backtrace_handler
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff81a0c0e3-ffffffff81a0c135: nmi_cpu_backtrace.cold.5 (STB_LOCAL)
ffffffff81a0bf90-ffffffff81a0bfe1: nmi_cpu_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool nmi_cpu_backtrace(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nmi_backtrace.c (0)
Location: lib/nmi_backtrace.c:88
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:nmi_cpu_backtrace_handler
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff81a7ba3a-ffffffff81a7ba8d: nmi_cpu_backtrace.cold (STB_LOCAL)
ffffffff81a7b8f0-ffffffff81a7b947: nmi_cpu_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
bool nmi_cpu_backtrace(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nmi_backtrace.c (0)
Location: lib/nmi_backtrace.c:88
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:nmi_cpu_backtrace_handler
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff81ab2d9a-ffffffff81ab2ded: nmi_cpu_backtrace.cold (STB_LOCAL)
ffffffff81ab2c50-ffffffff81ab2ca7: nmi_cpu_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool nmi_cpu_backtrace(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nmi_backtrace.c (0)
Location: lib/nmi_backtrace.c:88
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:nmi_cpu_backtrace_handler
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff815ed63b-ffffffff815ed68e: nmi_cpu_backtrace.cold (STB_LOCAL)
ffffffff815ed4f0-ffffffff815ed547: nmi_cpu_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool nmi_cpu_backtrace(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nmi_backtrace.c (0)
Location: lib/nmi_backtrace.c:92
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:nmi_cpu_backtrace_handler
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff81bf4c11-ffffffff81bf4c7a: nmi_cpu_backtrace.cold (STB_LOCAL)
ffffffff81611ca0-ffffffff81611d06: nmi_cpu_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool nmi_cpu_backtrace(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nmi_backtrace.c (0)
Location: lib/nmi_backtrace.c:92
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:nmi_cpu_backtrace_handler
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff81be6b34-ffffffff81be6b9d: nmi_cpu_backtrace.cold (STB_LOCAL)
ffffffff815f5380-ffffffff815f53e6: nmi_cpu_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool nmi_cpu_backtrace(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nmi_backtrace.c (0)
Location: lib/nmi_backtrace.c:92
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:nmi_cpu_backtrace_handler
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff81cdf421-ffffffff81cdf4b4: nmi_cpu_backtrace.cold (STB_LOCAL)
ffffffff816627b0-ffffffff81662858: nmi_cpu_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool nmi_cpu_backtrace(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nmi_backtrace.c (0)
Location: lib/nmi_backtrace.c:92
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:nmi_cpu_backtrace_handler
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff81ea5bd9-ffffffff81ea5c6e: nmi_cpu_backtrace.cold (STB_LOCAL)
ffffffff8177c5f0-ffffffff8177c69d: nmi_cpu_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool nmi_cpu_backtrace(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nmi_backtrace.c (0)
Location: lib/nmi_backtrace.c:92
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:nmi_cpu_backtrace_handler
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff820b75fb-ffffffff820b7616: nmi_cpu_backtrace.cold (STB_LOCAL)
ffffffff82039040-ffffffff82039158: nmi_cpu_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool nmi_cpu_backtrace(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nmi_backtrace.c (0)
Location: lib/nmi_backtrace.c:94
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:nmi_cpu_backtrace_handler
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff82138b02-ffffffff82138b1d: nmi_cpu_backtrace.cold (STB_LOCAL)
ffffffff820b7350-ffffffff820b7468: nmi_cpu_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool nmi_cpu_backtrace(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nmi_backtrace.c (0)
Location: lib/nmi_backtrace.c:94
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:nmi_cpu_backtrace_handler
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff8221a882-ffffffff8221a89d: nmi_cpu_backtrace.cold (STB_LOCAL)
ffffffff82191500-ffffffff82191618: nmi_cpu_backtrace (STB_GLOBAL)
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
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool nmi_cpu_backtrace(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nmi_backtrace.c (c0e873c0)
Location: lib/nmi_backtrace.c:88
Inline: False
Direct callers:
  - arch/arm/kernel/smp.c:handle_IPI
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
c0e873c0-c0e8748c: nmi_cpu_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool nmi_cpu_backtrace(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nmi_backtrace.c (c000000000ecefa0)
Location: lib/nmi_backtrace.c:88
Inline: False
Direct callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
c000000000ecefa0-c000000000ecf0b0: nmi_cpu_backtrace (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
bool nmi_cpu_backtrace(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nmi_backtrace.c (0)
Location: lib/nmi_backtrace.c:88
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:nmi_cpu_backtrace_handler
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff81a51bea-ffffffff81a51c3d: nmi_cpu_backtrace.cold (STB_LOCAL)
ffffffff81a51aa0-ffffffff81a51af7: nmi_cpu_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
bool nmi_cpu_backtrace(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nmi_backtrace.c (0)
Location: lib/nmi_backtrace.c:88
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:nmi_cpu_backtrace_handler
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff81a0ecea-ffffffff81a0ed3d: nmi_cpu_backtrace.cold (STB_LOCAL)
ffffffff81a0eba0-ffffffff81a0ebf7: nmi_cpu_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
bool nmi_cpu_backtrace(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nmi_backtrace.c (0)
Location: lib/nmi_backtrace.c:88
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:nmi_cpu_backtrace_handler
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff81abdfda-ffffffff81abe02d: nmi_cpu_backtrace.cold (STB_LOCAL)
ffffffff81abde90-ffffffff81abdee7: nmi_cpu_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
bool nmi_cpu_backtrace(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nmi_backtrace.c (0)
Location: lib/nmi_backtrace.c:88
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:nmi_cpu_backtrace_handler
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff81aca478-ffffffff81aca4cb: nmi_cpu_backtrace.cold (STB_LOCAL)
ffffffff81aca310-ffffffff81aca367: nmi_cpu_backtrace (STB_GLOBAL)
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
