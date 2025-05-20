# Function: <code>report_bug</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff813e8df0)
Location: lib/bug.c:141
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die
```
**Symbols:**

```
ffffffff813e8df0-ffffffff813e8f44: report_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff8142f060)
Location: lib/bug.c:141
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die
```
**Symbols:**

```
ffffffff8142f060-ffffffff8142f14e: report_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff8144b1d0)
Location: lib/bug.c:141
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die
```
**Symbols:**

```
ffffffff8144b1d0-ffffffff8144b2be: report_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff818eb440)
Location: lib/bug.c:142
Inline: False
```
**Symbols:**

```
ffffffff818eb440-ffffffff818eb556: report_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff81971380)
Location: lib/bug.c:143
Inline: False
```
**Symbols:**

```
ffffffff81971380-ffffffff81971492: report_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/bug.c (0)
Location: lib/bug.c:143
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_error_trap
```
**Symbols:**

```
ffffffff819cd89a-ffffffff819cd8e6: report_bug.cold.3 (STB_LOCAL)
ffffffff819cd740-ffffffff819cd812: report_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/bug.c (0)
Location: lib/bug.c:143
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_error_trap
```
**Symbols:**

```
ffffffff81a06bfa-ffffffff81a06c46: report_bug.cold.3 (STB_LOCAL)
ffffffff81a06aa0-ffffffff81a06b72: report_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/bug.c (0)
Location: lib/bug.c:143
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_error_trap
```
**Symbols:**

```
ffffffff81a76565-ffffffff81a765b3: report_bug.cold (STB_LOCAL)
ffffffff81a76400-ffffffff81a764ec: report_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/bug.c (0)
Location: lib/bug.c:143
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_error_trap
```
**Symbols:**

```
ffffffff81aad975-ffffffff81aad9c6: report_bug.cold (STB_LOCAL)
ffffffff81aad800-ffffffff81aad8fb: report_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/bug.c (0)
Location: lib/bug.c:144
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:handle_bug
  - arch/x86/mm/extable.c:early_fixup_exception
```
**Symbols:**

```
ffffffff815e79e5-ffffffff815e7a36: report_bug.cold (STB_LOCAL)
ffffffff815e78b0-ffffffff815e796a: report_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/bug.c (0)
Location: lib/bug.c:144
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:handle_bug
  - arch/x86/mm/extable.c:early_fixup_exception
```
**Symbols:**

```
ffffffff81bf494a-ffffffff81bf499b: report_bug.cold (STB_LOCAL)
ffffffff8160ca70-ffffffff8160cb2a: report_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/bug.c (0)
Location: lib/bug.c:157
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:handle_bug
  - arch/x86/mm/extable.c:early_fixup_exception
```
**Symbols:**

```
ffffffff81be6842-ffffffff81be6893: report_bug.cold (STB_LOCAL)
ffffffff815efd40-ffffffff815efdfa: report_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/bug.c (0)
Location: lib/bug.c:157
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:handle_bug
  - arch/x86/mm/extable.c:early_fixup_exception
```
**Symbols:**

```
ffffffff81cdf0dd-ffffffff81cdf12e: report_bug.cold (STB_LOCAL)
ffffffff8165ce50-ffffffff8165cf0a: report_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/bug.c (0)
Location: lib/bug.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:handle_bug
  - arch/x86/mm/extable.c:early_fixup_exception
```
**Symbols:**

```
ffffffff81ea58c0-ffffffff81ea5909: report_bug.cold (STB_LOCAL)
ffffffff81776240-ffffffff81776320: report_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff8201eb90)
Location: lib/bug.c:213
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:handle_bug
  - arch/x86/mm/extable.c:early_fixup_exception
```
**Symbols:**

```
ffffffff8201eb90-ffffffff8201ed36: report_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff8209eba0)
Location: lib/bug.c:213
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:handle_bug
  - arch/x86/mm/extable.c:early_fixup_exception
```
**Symbols:**

```
ffffffff8209eba0-ffffffff8209ed46: report_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff82176ba0)
Location: lib/bug.c:213
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:handle_bug
  - arch/x86/mm/extable.c:early_fixup_exception
```
**Symbols:**

```
ffffffff82176ba0-ffffffff82176d46: report_bug (STB_GLOBAL)
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
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffff800010d83ab8)
Location: lib/bug.c:143
Inline: False
```
**Symbols:**

```
ffff800010d83ab8-ffff800010d83c14: report_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bug.c (c0e7ed8c)
Location: lib/bug.c:143
Inline: False
Direct callers:
  - arch/arm/kernel/traps.c:die
```
**Symbols:**

```
c0e7ed8c-c0e7eecc: report_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bug.c (c000000000ec2840)
Location: lib/bug.c:143
Inline: False
Direct callers:
  - arch/powerpc/kernel/traps.c:program_check_exception
```
**Symbols:**

```
c000000000ec2840-c000000000ec2a24: report_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffe0008ae0ca)
Location: lib/bug.c:143
Inline: False
Direct callers:
  - arch/riscv/kernel/traps.c:do_trap_break
```
**Symbols:**

```
ffffffe0008ae0ca-ffffffe0008ae1fe: report_bug (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/bug.c (0)
Location: lib/bug.c:143
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_error_trap
```
**Symbols:**

```
ffffffff81a4c7c5-ffffffff81a4c816: report_bug.cold (STB_LOCAL)
ffffffff81a4c650-ffffffff81a4c74b: report_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/bug.c (0)
Location: lib/bug.c:143
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_error_trap
```
**Symbols:**

```
ffffffff81a098f5-ffffffff81a09946: report_bug.cold (STB_LOCAL)
ffffffff81a09780-ffffffff81a0987b: report_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/bug.c (0)
Location: lib/bug.c:143
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_error_trap
```
**Symbols:**

```
ffffffff81ab8bb5-ffffffff81ab8c06: report_bug.cold (STB_LOCAL)
ffffffff81ab8a40-ffffffff81ab8b3b: report_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/bug.c (0)
Location: lib/bug.c:143
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_error_trap
```
**Symbols:**

```
ffffffff81ac5001-ffffffff81ac5052: report_bug.cold (STB_LOCAL)
ffffffff81ac4e70-ffffffff81ac4f6b: report_bug (STB_GLOBAL)
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
