# Function: <code>fixup_exception</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fixup_exception(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff8106bfa0)
Location: arch/x86/mm/extable.c:17
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/mm/fault.c:no_context
```
**Symbols:**

```
ffffffff8106bfa0-ffffffff8106c001: fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fixup_exception(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff8106bfd0)
Location: arch/x86/mm/extable.c:99
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/extable.c:early_fixup_exception
```
**Symbols:**

```
ffffffff8106bfd0-ffffffff8106c011: fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fixup_exception(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff8106fbf0)
Location: arch/x86/mm/extable.c:99
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/extable.c:early_fixup_exception
```
**Symbols:**

```
ffffffff8106fbf0-ffffffff8106fc31: fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fixup_exception(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff8106f310)
Location: arch/x86/mm/extable.c:101
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/extable.c:early_fixup_exception
```
**Symbols:**

```
ffffffff8106f310-ffffffff8106f353: fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fixup_exception(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff810746b0)
Location: arch/x86/mm/extable.c:173
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/extable.c:early_fixup_exception
```
**Symbols:**

```
ffffffff810746b0-ffffffff810746f6: fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fixup_exception(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff810770c0)
Location: arch/x86/mm/extable.c:173
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/extable.c:early_fixup_exception
```
**Symbols:**

```
ffffffff810770c0-ffffffff81077109: fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fixup_exception(struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff8107d770)
Location: arch/x86/mm/extable.c:200
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/extable.c:early_fixup_exception
```
**Symbols:**

```
ffffffff8107d770-ffffffff8107d7d1: fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fixup_exception(struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff81081070)
Location: arch/x86/mm/extable.c:202
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/extable.c:early_fixup_exception
```
**Symbols:**

```
ffffffff81081070-ffffffff810810d1: fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fixup_exception(struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff81082130)
Location: arch/x86/mm/extable.c:202
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/extable.c:early_fixup_exception
```
**Symbols:**

```
ffffffff81082130-ffffffff81082191: fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fixup_exception(struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff81089140)
Location: arch/x86/mm/extable.c:141
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/extable.c:early_fixup_exception
```
**Symbols:**

```
ffffffff81089140-ffffffff810891a1: fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fixup_exception(struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff81089380)
Location: arch/x86/mm/extable.c:158
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/extable.c:early_fixup_exception
```
**Symbols:**

```
ffffffff81089380-ffffffff810893e1: fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fixup_exception(struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff8108a020)
Location: arch/x86/mm/extable.c:158
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
  - arch/x86/mm/extable.c:early_fixup_exception
```
**Symbols:**

```
ffffffff8108a020-ffffffff8108a081: fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fixup_exception(struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff81099540)
Location: arch/x86/mm/extable.c:158
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
  - arch/x86/mm/extable.c:early_fixup_exception
```
**Symbols:**

```
ffffffff81099540-ffffffff810995a1: fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fixup_exception(struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/extable.c (0)
Location: arch/x86/mm/extable.c:152
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:gp_try_fixup_and_notify
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
  - arch/x86/mm/extable.c:early_fixup_exception
```
**Symbols:**

```
ffffffff81e505c3-ffffffff81e505ec: fixup_exception.cold (STB_LOCAL)
ffffffff810ac1f0-ffffffff810ac52f: fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fixup_exception(struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/extable.c (0)
Location: arch/x86/mm/extable.c:205
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:gp_try_fixup_and_notify
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
  - arch/x86/mm/extable.c:early_fixup_exception
```
**Symbols:**

```
ffffffff82054aa4-ffffffff82054acd: fixup_exception.cold (STB_LOCAL)
ffffffff810c61e0-ffffffff810c654d: fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fixup_exception(struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/extable.c (0)
Location: arch/x86/mm/extable.c:233
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:gp_try_fixup_and_notify
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
  - arch/x86/mm/extable.c:early_fixup_exception
```
**Symbols:**

```
ffffffff820d30ae-ffffffff820d30d7: fixup_exception.cold (STB_LOCAL)
ffffffff810c9950-ffffffff810c9cd3: fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fixup_exception(struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/extable.c (0)
Location: arch/x86/mm/extable.c:233
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:gp_try_fixup_and_notify
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
  - arch/x86/mm/extable.c:early_fixup_exception
```
**Symbols:**

```
ffffffff821adf1c-ffffffff821adf45: fixup_exception.cold (STB_LOCAL)
ffffffff810d1db0-ffffffff810d2133: fixup_exception (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int fixup_exception(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/extable.c (ffff8000100acc80)
Location: arch/arm64/mm/extable.c:9
Inline: False
Direct callers:
  - arch/arm64/kernel/probes/kprobes.c:kprobe_fault_handler
  - arch/arm64/mm/fault.c:__do_kernel_fault
```
**Symbols:**

```
ffff8000100acc80-ffff8000100accc8: fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fixup_exception(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/mm/extable.c (c031a25c)
Location: arch/arm/mm/extable.c:8
Inline: False
Direct callers:
  - arch/arm/mm/fault.c:do_page_fault
```
**Symbols:**

```
c031a25c-c031a294: fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fixup_exception(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/mm/extable.c (ffffffe0000b9ef2)
Location: arch/riscv/mm/extable.c:14
Inline: False
Direct callers:
  - arch/riscv/mm/fault.c:do_page_fault
  - arch/riscv/mm/fault.c:do_page_fault
```
**Symbols:**

```
ffffffe0000b9ef2-ffffffe0000b9f30: fixup_exception (STB_GLOBAL)
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
int fixup_exception(struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff81081130)
Location: arch/x86/mm/extable.c:202
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/extable.c:early_fixup_exception
```
**Symbols:**

```
ffffffff81081130-ffffffff81081191: fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fixup_exception(struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff81070080)
Location: arch/x86/mm/extable.c:202
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/extable.c:early_fixup_exception
```
**Symbols:**

```
ffffffff81070080-ffffffff810700e1: fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fixup_exception(struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff810810e0)
Location: arch/x86/mm/extable.c:202
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/extable.c:early_fixup_exception
```
**Symbols:**

```
ffffffff810810e0-ffffffff81081141: fixup_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fixup_exception(struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff81083200)
Location: arch/x86/mm/extable.c:202
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/extable.c:early_fixup_exception
```
**Symbols:**

```
ffffffff81083200-ffffffff81083261: fixup_exception (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int trapnr</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int error_code</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int fault_addr</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int trapnr</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int error_code</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int fault_addr</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>armhf</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int trapnr</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int error_code</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int fault_addr</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int trapnr</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int error_code</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int fault_addr</code>
</li>
</ul>
</details>
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
