# Function: <code>copy_uabi_to_xstate</code>

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
int copy_uabi_to_xstate(struct xregs_state *xsave, const void *kbuf, const void *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104b1c0)
Location: arch/x86/kernel/fpu/xstate.c:1094
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:copy_sigframe_from_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_uabi_from_kernel_to_xstate
```
**Symbols:**

```
ffffffff8104b1c0-ffffffff8104b400: copy_uabi_to_xstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int copy_uabi_to_xstate(struct fpstate *fpstate, const void *kbuf, const void *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81055930)
Location: arch/x86/kernel/fpu/xstate.c:1199
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:copy_sigframe_from_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_uabi_from_kernel_to_xstate
```
**Symbols:**

```
ffffffff81055930-ffffffff81055b6d: copy_uabi_to_xstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int copy_uabi_to_xstate(struct fpstate *fpstate, const void *kbuf, const void *ubuf, u32 *pkru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81063440)
Location: arch/x86/kernel/fpu/xstate.c:1231
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:copy_sigframe_from_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_uabi_from_kernel_to_xstate
```
**Symbols:**

```
ffffffff81063440-ffffffff810636cb: copy_uabi_to_xstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int copy_uabi_to_xstate(struct fpstate *fpstate, const void *kbuf, const void *ubuf, u32 *pkru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81064d90)
Location: arch/x86/kernel/fpu/xstate.c:1236
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:copy_sigframe_from_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_uabi_from_kernel_to_xstate
```
**Symbols:**

```
ffffffff81064d90-ffffffff8106501b: copy_uabi_to_xstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int copy_uabi_to_xstate(struct fpstate *fpstate, const void *kbuf, const void *ubuf, u32 *pkru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106c440)
Location: arch/x86/kernel/fpu/xstate.c:1235
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:copy_sigframe_from_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_uabi_from_kernel_to_xstate
```
**Symbols:**

```
ffffffff8106c440-ffffffff8106c6cb: copy_uabi_to_xstate (STB_LOCAL)
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
<code>u32 *pkru</code>
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
