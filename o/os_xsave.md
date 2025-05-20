# Function: <code>os_xsave</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff810491a2)
Location: arch/x86/include/asm/fpu/internal.h:292
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:save_fpregs_to_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104aabd)
Location: arch/x86/include/asm/fpu/internal.h:292
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate ⚠️</summary>

```c
void os_xsave(struct fpstate *fpstate);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81052880)
Location: arch/x86/kernel/fpu/xstate.h:177
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:save_fpregs_to_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81054690)
Location: arch/x86/kernel/fpu/xstate.h:177
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
```
**Symbols:**

```
ffffffff81052880-ffffffff810528ee: os_xsave (STB_LOCAL)
ffffffff81054690-ffffffff810546fe: os_xsave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate ⚠️</summary>

```c
void os_xsave(struct fpstate *fpstate);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8105fee0)
Location: arch/x86/kernel/fpu/xstate.h:177
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:save_fpregs_to_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810622b0)
Location: arch/x86/kernel/fpu/xstate.h:177
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
```
**Symbols:**

```
ffffffff8105fee0-ffffffff8105ff4e: os_xsave (STB_LOCAL)
ffffffff810622b0-ffffffff8106231e: os_xsave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate ⚠️</summary>

```c
void os_xsave(struct fpstate *fpstate);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81061650)
Location: arch/x86/kernel/fpu/xstate.h:177
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:save_fpregs_to_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81063c50)
Location: arch/x86/kernel/fpu/xstate.h:177
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
```
**Symbols:**

```
ffffffff81061650-ffffffff810616be: os_xsave (STB_LOCAL)
ffffffff81063c50-ffffffff81063cbe: os_xsave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate ⚠️</summary>

```c
void os_xsave(struct fpstate *fpstate);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81068760)
Location: arch/x86/kernel/fpu/xstate.h:178
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:save_fpregs_to_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106b170)
Location: arch/x86/kernel/fpu/xstate.h:178
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
```
**Symbols:**

```
ffffffff81068760-ffffffff810687ce: os_xsave (STB_LOCAL)
ffffffff8106b170-ffffffff8106b1de: os_xsave (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
