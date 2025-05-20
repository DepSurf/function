# Function: <code>do_trap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void do_trap(int trapnr, int signr, char *str, struct pt_regs *regs, long int error_code, siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102f010)
Location: arch/x86/kernel/traps.c:245
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_error_trap
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_bounds
```
**Symbols:**

```
ffffffff8102f010-ffffffff8102f14b: do_trap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void do_trap(int trapnr, int signr, char *str, struct pt_regs *regs, long int error_code, siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102e0d0)
Location: arch/x86/kernel/traps.c:232
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_error_trap
```
**Symbols:**

```
ffffffff8102e0d0-ffffffff8102e20a: do_trap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void do_trap(int trapnr, int signr, char *str, struct pt_regs *regs, long int error_code, siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102dfc0)
Location: arch/x86/kernel/traps.c:232
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_error_trap
```
**Symbols:**

```
ffffffff8102dfc0-ffffffff8102e0fa: do_trap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void do_trap(int trapnr, int signr, char *str, struct pt_regs *regs, long int error_code, siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102c920)
Location: arch/x86/kernel/traps.c:267
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_error_trap
```
**Symbols:**

```
ffffffff8102c920-ffffffff8102ca6b: do_trap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void do_trap(int trapnr, int signr, char *str, struct pt_regs *regs, long int error_code, siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102cfa0)
Location: arch/x86/kernel/traps.c:252
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_error_trap
```
**Symbols:**

```
ffffffff8102cfa0-ffffffff8102d0d7: do_trap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void do_trap(int trapnr, int signr, char *str, struct pt_regs *regs, long int error_code, siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/traps.c (0)
Location: arch/x86/kernel/traps.c:252
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_error_trap
```
**Symbols:**

```
ffffffff8102e000-ffffffff8102e0ce: do_trap (STB_LOCAL)
ffffffff8102eebc-ffffffff8102ef0f: do_trap.cold.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void do_trap(int trapnr, int signr, char *str, struct pt_regs *regs, long int error_code, int sicode, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102f380)
Location: arch/x86/kernel/traps.c:244
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_error_trap
```
**Symbols:**

```
ffffffff8102f380-ffffffff8102f45f: do_trap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void do_trap(int trapnr, int signr, char *str, struct pt_regs *regs, long int error_code, int sicode, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81031170)
Location: arch/x86/kernel/traps.c:245
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_error_trap
```
**Symbols:**

```
ffffffff81031170-ffffffff81031253: do_trap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void do_trap(int trapnr, int signr, char *str, struct pt_regs *regs, long int error_code, int sicode, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81031a30)
Location: arch/x86/kernel/traps.c:245
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_error_trap
```
**Symbols:**

```
ffffffff81031a30-ffffffff81031b13: do_trap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void do_trap(int trapnr, int signr, char *str, struct pt_regs *regs, long int error_code, int sicode, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/traps.c (0)
Location: arch/x86/kernel/traps.c:152
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/traps.c:exc_bounds
  - arch/x86/kernel/traps.c:exc_alignment_check
  - arch/x86/kernel/traps.c:do_error_trap
```
**Symbols:**

```
ffffffff81034230-ffffffff81034318: do_trap (STB_LOCAL)
ffffffff81034761-ffffffff8103477f: do_trap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void do_trap(int trapnr, int signr, char *str, struct pt_regs *regs, long int error_code, int sicode, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/traps.c (0)
Location: arch/x86/kernel/traps.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/traps.c:exc_bounds
  - arch/x86/kernel/traps.c:exc_alignment_check
  - arch/x86/kernel/traps.c:do_error_trap
```
**Symbols:**

```
ffffffff81034c30-ffffffff81034d26: do_trap (STB_LOCAL)
ffffffff81bd330d-ffffffff81bd332b: do_trap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void do_trap(int trapnr, int signr, char *str, struct pt_regs *regs, long int error_code, int sicode, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/traps.c (0)
Location: arch/x86/kernel/traps.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/traps.c:exc_bounds
  - arch/x86/kernel/traps.c:exc_alignment_check
  - arch/x86/kernel/traps.c:do_error_trap
```
**Symbols:**

```
ffffffff81036690-ffffffff81036786: do_trap (STB_LOCAL)
ffffffff81bc5725-ffffffff81bc5743: do_trap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void do_trap(int trapnr, int signr, char *str, struct pt_regs *regs, long int error_code, int sicode, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/traps.c (0)
Location: arch/x86/kernel/traps.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/traps.c:exc_bounds
  - arch/x86/kernel/traps.c:exc_alignment_check
  - arch/x86/kernel/traps.c:do_error_trap
```
**Symbols:**

```
ffffffff8103b9b0-ffffffff8103baa6: do_trap (STB_LOCAL)
ffffffff81c9833c-ffffffff81c9835a: do_trap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void do_trap(int trapnr, int signr, char *str, struct pt_regs *regs, long int error_code, int sicode, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/traps.c (0)
Location: arch/x86/kernel/traps.c:158
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/traps.c:exc_bounds
  - arch/x86/kernel/traps.c:exc_alignment_check
  - arch/x86/kernel/traps.c:do_error_trap
```
**Symbols:**

```
ffffffff810427d0-ffffffff810428cc: do_trap (STB_LOCAL)
ffffffff81e47813-ffffffff81e47831: do_trap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void do_trap(int trapnr, int signr, char *str, struct pt_regs *regs, long int error_code, int sicode, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8104c260)
Location: arch/x86/kernel/traps.c:160
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/traps.c:exc_bounds
  - arch/x86/kernel/traps.c:exc_alignment_check
  - arch/x86/kernel/traps.c:do_error_trap
```
**Symbols:**

```
ffffffff8104c260-ffffffff8104c34a: do_trap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void do_trap(int trapnr, int signr, char *str, struct pt_regs *regs, long int error_code, int sicode, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8104cad0)
Location: arch/x86/kernel/traps.c:160
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/traps.c:exc_bounds
  - arch/x86/kernel/traps.c:exc_alignment_check
  - arch/x86/kernel/traps.c:do_error_trap
```
**Symbols:**

```
ffffffff8104cad0-ffffffff8104cbba: do_trap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void do_trap(int trapnr, int signr, char *str, struct pt_regs *regs, long int error_code, int sicode, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81053d50)
Location: arch/x86/kernel/traps.c:149
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/traps.c:exc_bounds
  - arch/x86/kernel/traps.c:exc_alignment_check
  - arch/x86/kernel/traps.c:do_error_trap
```
**Symbols:**

```
ffffffff81053d50-ffffffff81053e3a: do_trap (STB_LOCAL)
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
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void do_trap(struct pt_regs *regs, int signo, int code, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/traps.c (ffffffe0000b6ce8)
Location: arch/riscv/kernel/traps.c:59
Inline: False
Direct callers:
  - arch/riscv/mm/fault.c:do_page_fault
  - arch/riscv/mm/fault.c:do_page_fault
  - arch/riscv/mm/fault.c:do_page_fault
```
**Symbols:**

```
ffffffe0000b6ce8-ffffffe0000b6da6: do_trap (STB_GLOBAL)
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
void do_trap(int trapnr, int signr, char *str, struct pt_regs *regs, long int error_code, int sicode, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81031b90)
Location: arch/x86/kernel/traps.c:245
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_error_trap
```
**Symbols:**

```
ffffffff81031b90-ffffffff81031c73: do_trap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void do_trap(int trapnr, int signr, char *str, struct pt_regs *regs, long int error_code, int sicode, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81021660)
Location: arch/x86/kernel/traps.c:245
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_error_trap
```
**Symbols:**

```
ffffffff81021660-ffffffff81021743: do_trap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void do_trap(int trapnr, int signr, char *str, struct pt_regs *regs, long int error_code, int sicode, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff810319f0)
Location: arch/x86/kernel/traps.c:245
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_error_trap
```
**Symbols:**

```
ffffffff810319f0-ffffffff81031ad3: do_trap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void do_trap(int trapnr, int signr, char *str, struct pt_regs *regs, long int error_code, int sicode, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff810328b0)
Location: arch/x86/kernel/traps.c:245
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_error_trap
```
**Symbols:**

```
ffffffff810328b0-ffffffff81032993: do_trap (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int sicode</code>
</li>
<li>
<b>Param added. </b>
<code>void *addr</code>
</li>
<li>
<b>Param removed. </b>
<code>siginfo_t *info</code>
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
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int signo</code>
</li>
<li>
<b>Param added. </b>
<code>int code</code>
</li>
<li>
<b>Param removed. </b>
<code>int trapnr</code>
</li>
<li>
<b>Param removed. </b>
<code>int signr</code>
</li>
<li>
<b>Param removed. </b>
<code>char *str</code>
</li>
<li>
<b>Param removed. </b>
<code>long int error_code</code>
</li>
<li>
<b>Param removed. </b>
<code>int sicode</code>
</li>
<li>
<b>Param reordered. </b>
<code>trapnr, signr, str, regs, error_code, sicode, addr</code> ➡️ <code>regs, signo, code, addr</code>
</li>
<li>
<b>Param type changed. </b>
<code>void *addr</code> ➡️ <code>long unsigned int addr</code>
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
