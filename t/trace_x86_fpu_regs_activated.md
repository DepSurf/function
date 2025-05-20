# Function: <code>trace_x86_fpu_regs_activated</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102c58a)
Location: arch/x86/include/asm/trace/fpu.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81039a6a)
Location: arch/x86/include/asm/trace/fpu.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__restore
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103a906)
Location: arch/x86/include/asm/trace/fpu.h:67
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
In arch/x86/kernel/process_64.c (ffffffff8102c6c2)
Location: arch/x86/include/asm/trace/fpu.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81039386)
Location: arch/x86/include/asm/trace/fpu.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__restore
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103a0fa)
Location: arch/x86/include/asm/trace/fpu.h:64
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
In arch/x86/kernel/process_64.c (ffffffff8102a887)
Location: arch/x86/include/asm/trace/fpu.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff810372a7)
Location: arch/x86/include/asm/trace/fpu.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__restore
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810380c1)
Location: arch/x86/include/asm/trace/fpu.h:64
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
In arch/x86/kernel/process_64.c (ffffffff8102b5c5)
Location: arch/x86/include/asm/trace/fpu.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103951f)
Location: arch/x86/include/asm/trace/fpu.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__restore
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103a1cc)
Location: arch/x86/include/asm/trace/fpu.h:57
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
In arch/x86/kernel/process_64.c (ffffffff8102c5e5)
Location: arch/x86/include/asm/trace/fpu.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103aa5f)
Location: arch/x86/include/asm/trace/fpu.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__restore
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103b5f7)
Location: arch/x86/include/asm/trace/fpu.h:57
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
In arch/x86/kernel/process_64.c (ffffffff8102d84e)
Location: arch/x86/include/asm/trace/fpu.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103bf5f)
Location: arch/x86/include/asm/trace/fpu.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__restore
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103cc11)
Location: arch/x86/include/asm/trace/fpu.h:57
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
In arch/x86/kernel/fpu/core.c (ffffffff8103de27)
Location: arch/x86/include/asm/trace/fpu.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f782)
Location: arch/x86/include/asm/trace/fpu.h:57
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
In arch/x86/kernel/fpu/core.c (ffffffff8103e5e7)
Location: arch/x86/include/asm/trace/fpu.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103feb9)
Location: arch/x86/include/asm/trace/fpu.h:57
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
In arch/x86/kernel/fpu/core.c (ffffffff81041767)
Location: arch/x86/include/asm/trace/fpu.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81043143)
Location: arch/x86/include/asm/trace/fpu.h:57
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
In arch/x86/kernel/fpu/core.c (ffffffff81041882)
Location: arch/x86/include/asm/trace/fpu.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104311d)
Location: arch/x86/include/asm/trace/fpu.h:57
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
In arch/x86/kernel/fpu/core.c (ffffffff81043282)
Location: arch/x86/include/asm/trace/fpu.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81044a2d)
Location: arch/x86/include/asm/trace/fpu.h:57
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
In arch/x86/kernel/fpu/core.c (ffffffff810495f2)
Location: arch/x86/include/asm/trace/fpu.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104acca)
Location: arch/x86/include/asm/trace/fpu.h:57
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
In arch/x86/kernel/fpu/core.c (ffffffff810539b2)
Location: arch/x86/include/asm/trace/fpu.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81054875)
Location: arch/x86/include/asm/trace/fpu.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpregs_restore_userregs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810555c5)
Location: arch/x86/include/asm/trace/fpu.h:57
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
In arch/x86/kernel/fpu/core.c (ffffffff81061422)
Location: arch/x86/include/asm/trace/fpu.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu_clone
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81062ce1)
Location: arch/x86/include/asm/trace/fpu.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81063909)
Location: arch/x86/include/asm/trace/fpu.h:57
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
In arch/x86/kernel/fpu/core.c (ffffffff81062cf2)
Location: arch/x86/include/asm/trace/fpu.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu_clone
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810646d9)
Location: arch/x86/include/asm/trace/fpu.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106526e)
Location: arch/x86/include/asm/trace/fpu.h:57
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
In arch/x86/kernel/fpu/core.c (ffffffff81069fe2)
Location: arch/x86/include/asm/trace/fpu.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:fpregs_lock_and_load
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu_clone
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106bb99)
Location: arch/x86/include/asm/trace/fpu.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106c8da)
Location: arch/x86/include/asm/trace/fpu.h:57
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
In arch/x86/kernel/fpu/core.c (ffffffff8103e767)
Location: arch/x86/include/asm/trace/fpu.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81040039)
Location: arch/x86/include/asm/trace/fpu.h:57
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
In arch/x86/kernel/fpu/core.c (ffffffff8102df67)
Location: arch/x86/include/asm/trace/fpu.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8102f839)
Location: arch/x86/include/asm/trace/fpu.h:57
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
In arch/x86/kernel/fpu/core.c (ffffffff8103e5a7)
Location: arch/x86/include/asm/trace/fpu.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103fe79)
Location: arch/x86/include/asm/trace/fpu.h:57
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
In arch/x86/kernel/fpu/core.c (ffffffff8103f737)
Location: arch/x86/include/asm/trace/fpu.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104121d)
Location: arch/x86/include/asm/trace/fpu.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
</details>
</li>
</ul>

## Differences
