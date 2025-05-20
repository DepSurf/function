# Function: <code>notify_die</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int notify_die(enum die_val val, const char *str, struct pt_regs *regs, long int err, int trap, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a1590)
Location: kernel/notifier.c:536
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_debug
  - arch/x86/kernel/traps.c:do_error_trap
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_double_fault
  - arch/x86/kernel/traps.c:do_bounds
```
**Symbols:**

```
ffffffff810a1590-ffffffff810a15eb: notify_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int notify_die(enum die_val val, const char *str, struct pt_regs *regs, long int err, int trap, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a4cb0)
Location: kernel/notifier.c:536
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_debug
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_double_fault
  - arch/x86/kernel/traps.c:do_error_trap
```
**Symbols:**

```
ffffffff810a4cb0-ffffffff810a4d0b: notify_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int notify_die(enum die_val val, const char *str, struct pt_regs *regs, long int err, int trap, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810aa910)
Location: kernel/notifier.c:536
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_debug
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_double_fault
  - arch/x86/kernel/traps.c:do_error_trap
```
**Symbols:**

```
ffffffff810aa910-ffffffff810aa96b: notify_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int notify_die(enum die_val val, const char *str, struct pt_regs *regs, long int err, int trap, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a7490)
Location: kernel/notifier.c:536
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_debug
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_double_fault
  - arch/x86/kernel/traps.c:do_error_trap
```
**Symbols:**

```
ffffffff810a7490-ffffffff810a74eb: notify_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int notify_die(enum die_val val, const char *str, struct pt_regs *regs, long int err, int trap, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810adc10)
Location: kernel/notifier.c:536
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_debug
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_double_fault
  - arch/x86/kernel/traps.c:do_error_trap
```
**Symbols:**

```
ffffffff810adc10-ffffffff810adc6b: notify_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int notify_die(enum die_val val, const char *str, struct pt_regs *regs, long int err, int trap, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810b4a80)
Location: kernel/notifier.c:536
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_debug
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_double_fault
  - arch/x86/kernel/traps.c:do_error_trap
  - arch/x86/kernel/dumpstack.c:__die
```
**Symbols:**

```
ffffffff810b4a80-ffffffff810b4adb: notify_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int notify_die(enum die_val val, const char *str, struct pt_regs *regs, long int err, int trap, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810bdbd0)
Location: kernel/notifier.c:536
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_debug
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_double_fault
  - arch/x86/kernel/traps.c:do_error_trap
  - arch/x86/kernel/dumpstack.c:__die
```
**Symbols:**

```
ffffffff810bdbd0-ffffffff810bdc2b: notify_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int notify_die(enum die_val val, const char *str, struct pt_regs *regs, long int err, int trap, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c3b90)
Location: kernel/notifier.c:538
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_debug
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_double_fault
  - arch/x86/kernel/traps.c:do_error_trap
  - arch/x86/kernel/dumpstack.c:__die
```
**Symbols:**

```
ffffffff810c3b90-ffffffff810c3beb: notify_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int notify_die(enum die_val val, const char *str, struct pt_regs *regs, long int err, int trap, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810ccca0)
Location: kernel/notifier.c:538
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_debug
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_double_fault
  - arch/x86/kernel/traps.c:do_error_trap
  - arch/x86/kernel/dumpstack.c:__die
```
**Symbols:**

```
ffffffff810ccca0-ffffffff810cccfb: notify_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int notify_die(enum die_val val, const char *str, struct pt_regs *regs, long int err, int trap, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d6e60)
Location: kernel/notifier.c:503
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:handle_debug
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:exc_bounds
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/traps.c:exc_alignment_check
  - arch/x86/kernel/traps.c:do_error_trap
  - arch/x86/kernel/dumpstack.c:__die_body
```
**Symbols:**

```
ffffffff810d6e60-ffffffff810d6ef3: notify_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int notify_die(enum die_val val, const char *str, struct pt_regs *regs, long int err, int trap, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d1900)
Location: kernel/notifier.c:535
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:noist_exc_debug
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:exc_bounds
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/traps.c:exc_alignment_check
  - arch/x86/kernel/traps.c:do_error_trap
  - arch/x86/kernel/dumpstack.c:__die_body
```
**Symbols:**

```
ffffffff810d1900-ffffffff810d199e: notify_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int notify_die(enum die_val val, const char *str, struct pt_regs *regs, long int err, int trap, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d34e0)
Location: kernel/notifier.c:535
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:noist_exc_debug
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:exc_bounds
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/traps.c:exc_alignment_check
  - arch/x86/kernel/traps.c:do_error_trap
  - arch/x86/kernel/dumpstack.c:__die_body
```
**Symbols:**

```
ffffffff810d34e0-ffffffff810d357e: notify_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int notify_die(enum die_val val, const char *str, struct pt_regs *regs, long int err, int trap, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810e6670)
Location: kernel/notifier.c:516
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:noist_exc_debug
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:exc_bounds
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/traps.c:exc_alignment_check
  - arch/x86/kernel/traps.c:do_error_trap
  - arch/x86/kernel/dumpstack.c:__die_body
```
**Symbols:**

```
ffffffff810e6670-ffffffff810e670e: notify_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int notify_die(enum die_val val, const char *str, struct pt_regs *regs, long int err, int trap, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff81100700)
Location: kernel/notifier.c:580
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:noist_exc_debug
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:gp_try_fixup_and_notify
  - arch/x86/kernel/traps.c:exc_bounds
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/traps.c:exc_alignment_check
  - arch/x86/kernel/traps.c:do_error_trap
  - arch/x86/kernel/dumpstack.c:__die_body
```
**Symbols:**

```
ffffffff81100700-ffffffff811007b5: notify_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int notify_die(enum die_val val, const char *str, struct pt_regs *regs, long int err, int trap, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff81125640)
Location: kernel/notifier.c:580
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:noist_exc_debug
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:gp_try_fixup_and_notify
  - arch/x86/kernel/traps.c:exc_bounds
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/traps.c:exc_alignment_check
  - arch/x86/kernel/traps.c:do_error_trap
  - arch/x86/kernel/dumpstack.c:die_addr
  - arch/x86/kernel/dumpstack.c:die
```
**Symbols:**

```
ffffffff81125640-ffffffff811256f5: notify_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int notify_die(enum die_val val, const char *str, struct pt_regs *regs, long int err, int trap, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff81132ab0)
Location: kernel/notifier.c:583
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:noist_exc_debug
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:gp_try_fixup_and_notify
  - arch/x86/kernel/traps.c:exc_bounds
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/traps.c:exc_alignment_check
  - arch/x86/kernel/traps.c:do_error_trap
  - arch/x86/kernel/dumpstack.c:die_addr
  - arch/x86/kernel/dumpstack.c:die
```
**Symbols:**

```
ffffffff81132ab0-ffffffff81132b32: notify_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int notify_die(enum die_val val, const char *str, struct pt_regs *regs, long int err, int trap, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff8113d9c0)
Location: kernel/notifier.c:583
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:noist_exc_debug
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:gp_try_fixup_and_notify
  - arch/x86/kernel/traps.c:exc_bounds
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/traps.c:exc_alignment_check
  - arch/x86/kernel/traps.c:do_error_trap
  - arch/x86/kernel/dumpstack.c:die_addr
  - arch/x86/kernel/dumpstack.c:die
```
**Symbols:**

```
ffffffff8113d9c0-ffffffff8113da42: notify_die (STB_GLOBAL)
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
int notify_die(enum die_val val, const char *str, struct pt_regs *regs, long int err, int trap, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffff80001012bb10)
Location: kernel/notifier.c:538
Inline: False
Direct callers:
  - arch/arm64/kernel/traps.c:die
```
**Symbols:**

```
ffff80001012bb10-ffff80001012bb7c: notify_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int notify_die(enum die_val val, const char *str, struct pt_regs *regs, long int err, int trap, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (c037bf3c)
Location: kernel/notifier.c:538
Inline: False
Direct callers:
  - arch/arm/kernel/traps.c:die
```
**Symbols:**

```
c037bf3c-c037bfc0: notify_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int notify_die(enum die_val val, const char *str, struct pt_regs *regs, long int err, int trap, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (c000000000174650)
Location: kernel/notifier.c:538
Inline: False
Direct callers:
  - arch/powerpc/kernel/process.c:do_break
  - arch/powerpc/kernel/traps.c:program_check_exception
  - arch/powerpc/kernel/traps.c:instruction_breakpoint_exception
  - arch/powerpc/kernel/traps.c:__die
```
**Symbols:**

```
c000000000174650-c0000000001746cc: notify_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int notify_die(enum die_val val, const char *str, struct pt_regs *regs, long int err, int trap, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffe0000e0e52)
Location: kernel/notifier.c:538
Inline: False
Direct callers:
  - arch/riscv/kernel/traps.c:die
```
**Symbols:**

```
ffffffe0000e0e52-ffffffe0000e0e94: notify_die (STB_GLOBAL)
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
int notify_die(enum die_val val, const char *str, struct pt_regs *regs, long int err, int trap, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c7020)
Location: kernel/notifier.c:538
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_debug
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_double_fault
  - arch/x86/kernel/traps.c:do_error_trap
  - arch/x86/kernel/dumpstack.c:__die
```
**Symbols:**

```
ffffffff810c7020-ffffffff810c707b: notify_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int notify_die(enum die_val val, const char *str, struct pt_regs *regs, long int err, int trap, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810b5840)
Location: kernel/notifier.c:538
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_debug
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_double_fault
  - arch/x86/kernel/traps.c:do_error_trap
  - arch/x86/kernel/dumpstack.c:__die
```
**Symbols:**

```
ffffffff810b5840-ffffffff810b589b: notify_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int notify_die(enum die_val val, const char *str, struct pt_regs *regs, long int err, int trap, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c6570)
Location: kernel/notifier.c:538
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_debug
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_double_fault
  - arch/x86/kernel/traps.c:do_error_trap
  - arch/x86/kernel/dumpstack.c:__die
```
**Symbols:**

```
ffffffff810c6570-ffffffff810c65cb: notify_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int notify_die(enum die_val val, const char *str, struct pt_regs *regs, long int err, int trap, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810cebb0)
Location: kernel/notifier.c:538
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_debug
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_double_fault
  - arch/x86/kernel/traps.c:do_error_trap
  - arch/x86/kernel/dumpstack.c:__die
```
**Symbols:**

```
ffffffff810cebb0-ffffffff810cec03: notify_die (STB_GLOBAL)
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
