# Function: <code>xstate_init_xcomp_bv</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void xstate_init_xcomp_bv(struct xregs_state *xsave, u64 mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8105294c)
Location: arch/x86/kernel/fpu/xstate.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_alloc_guest_fpstate
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81055ec9)
Location: arch/x86/kernel/fpu/xstate.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpstate_realloc
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
**Symbols:**

```
ffffffff810553b0-ffffffff810553ca: xstate_init_xcomp_bv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8105ffbc)
Location: arch/x86/kernel/fpu/xstate.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_alloc_guest_fpstate
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810637a9)
Location: arch/x86/kernel/fpu/xstate.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpstate_realloc
  - arch/x86/kernel/fpu/xstate.c:setup_init_fpu_buf
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8106172c)
Location: arch/x86/kernel/fpu/xstate.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_alloc_guest_fpstate
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8369c61a)
Location: arch/x86/kernel/fpu/xstate.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:setup_init_fpu_buf
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8106883c)
Location: arch/x86/kernel/fpu/xstate.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_alloc_guest_fpstate
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff838cc314)
Location: arch/x86/kernel/fpu/xstate.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:setup_init_fpu_buf
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
</ul>
