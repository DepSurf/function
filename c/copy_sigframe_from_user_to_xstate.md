# Function: <code>copy_sigframe_from_user_to_xstate</code>

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
<summary>In <code>5.15</code>: ✅</summary>

```c
int copy_sigframe_from_user_to_xstate(struct xregs_state *xsave, const void *ubuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104c330)
Location: arch/x86/kernel/fpu/xstate.c:1172
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
```
**Symbols:**

```
ffffffff8104c330-ffffffff8104c345: copy_sigframe_from_user_to_xstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int copy_sigframe_from_user_to_xstate(struct fpstate *fpstate, const void *ubuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81056f00)
Location: arch/x86/kernel/fpu/xstate.c:1277
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
```
**Symbols:**

```
ffffffff81056f00-ffffffff81056f1f: copy_sigframe_from_user_to_xstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int copy_sigframe_from_user_to_xstate(struct task_struct *tsk, const void *ubuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff810645c0)
Location: arch/x86/kernel/fpu/xstate.c:1323
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
```
**Symbols:**

```
ffffffff810645c0-ffffffff810645ef: copy_sigframe_from_user_to_xstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int copy_sigframe_from_user_to_xstate(struct task_struct *tsk, const void *ubuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81065ed0)
Location: arch/x86/kernel/fpu/xstate.c:1328
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
```
**Symbols:**

```
ffffffff81065ed0-ffffffff81065eff: copy_sigframe_from_user_to_xstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int copy_sigframe_from_user_to_xstate(struct task_struct *tsk, const void *ubuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106d350)
Location: arch/x86/kernel/fpu/xstate.c:1327
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
```
**Symbols:**

```
ffffffff8106d350-ffffffff8106d37f: copy_sigframe_from_user_to_xstate (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fpstate *fpstate</code>
</li>
<li>
<b>Param removed. </b>
<code>struct xregs_state *xsave</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct *tsk</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fpstate *fpstate</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
