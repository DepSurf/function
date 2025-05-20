# Function: <code>fpregs_activate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102d713)
Location: arch/x86/include/asm/fpu/internal.h:564
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81039bbc)
Location: arch/x86/include/asm/fpu/internal.h:564
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103aff5)
Location: arch/x86/include/asm/fpu/internal.h:564
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102c569)
Location: arch/x86/include/asm/fpu/internal.h:563
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81039a42)
Location: arch/x86/include/asm/fpu/internal.h:563
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__restore
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103a8d9)
Location: arch/x86/include/asm/fpu/internal.h:563
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102c6a6)
Location: arch/x86/include/asm/fpu/internal.h:526
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81039377)
Location: arch/x86/include/asm/fpu/internal.h:526
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__restore
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103a0eb)
Location: arch/x86/include/asm/fpu/internal.h:526
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102a86b)
Location: arch/x86/include/asm/fpu/internal.h:536
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81037298)
Location: arch/x86/include/asm/fpu/internal.h:536
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__restore
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810380b2)
Location: arch/x86/include/asm/fpu/internal.h:536
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102b5bd)
Location: arch/x86/include/asm/fpu/internal.h:511
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81039517)
Location: arch/x86/include/asm/fpu/internal.h:511
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__restore
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103a1c4)
Location: arch/x86/include/asm/fpu/internal.h:511
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102c5dd)
Location: arch/x86/include/asm/fpu/internal.h:511
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103aa57)
Location: arch/x86/include/asm/fpu/internal.h:511
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__restore
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103b5ef)
Location: arch/x86/include/asm/fpu/internal.h:511
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102d846)
Location: arch/x86/include/asm/fpu/internal.h:514
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103bf57)
Location: arch/x86/include/asm/fpu/internal.h:514
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__restore
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103cc09)
Location: arch/x86/include/asm/fpu/internal.h:514
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103de1f)
Location: arch/x86/include/asm/fpu/internal.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f776)
Location: arch/x86/include/asm/fpu/internal.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103e5df)
Location: arch/x86/include/asm/fpu/internal.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103fead)
Location: arch/x86/include/asm/fpu/internal.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8104175f)
Location: arch/x86/include/asm/fpu/internal.h:529
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81043137)
Location: arch/x86/include/asm/fpu/internal.h:529
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8104187a)
Location: arch/x86/include/asm/fpu/internal.h:496
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81043111)
Location: arch/x86/include/asm/fpu/internal.h:496
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8104327a)
Location: arch/x86/include/asm/fpu/internal.h:487
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81044a21)
Location: arch/x86/include/asm/fpu/internal.h:487
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff810495ea)
Location: arch/x86/include/asm/fpu/internal.h:449
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104acbe)
Location: arch/x86/include/asm/fpu/internal.h:449
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff810539aa)
Location: arch/x86/kernel/fpu/context.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8105486d)
Location: arch/x86/kernel/fpu/context.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpregs_restore_userregs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810555bd)
Location: arch/x86/kernel/fpu/context.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpregs_restore_userregs
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
In arch/x86/kernel/fpu/core.c (ffffffff8106141a)
Location: arch/x86/kernel/fpu/context.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu_clone
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81062cd9)
Location: arch/x86/kernel/fpu/context.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810638f9)
Location: arch/x86/kernel/fpu/context.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpstate_realloc
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
In arch/x86/kernel/fpu/core.c (ffffffff81062cea)
Location: arch/x86/kernel/fpu/context.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu_clone
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810646d1)
Location: arch/x86/kernel/fpu/context.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106525f)
Location: arch/x86/kernel/fpu/context.h:47
Inline: True
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
In arch/x86/kernel/fpu/core.c (ffffffff81069fda)
Location: arch/x86/kernel/fpu/context.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:fpregs_lock_and_load
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu_clone
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106bb91)
Location: arch/x86/kernel/fpu/context.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106c8ca)
Location: arch/x86/kernel/fpu/context.h:47
Inline: True
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103e75f)
Location: arch/x86/include/asm/fpu/internal.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104002d)
Location: arch/x86/include/asm/fpu/internal.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8102df5f)
Location: arch/x86/include/asm/fpu/internal.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8102f82d)
Location: arch/x86/include/asm/fpu/internal.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103e59f)
Location: arch/x86/include/asm/fpu/internal.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103fe6d)
Location: arch/x86/include/asm/fpu/internal.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103f72f)
Location: arch/x86/include/asm/fpu/internal.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81041211)
Location: arch/x86/include/asm/fpu/internal.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
</details>
</li>
</ul>

## Differences
