# Function: <code>xfeatures_mask_supervisor</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (0)
Location: arch/x86/include/asm/fpu/xstate.h:56
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: arch/x86/include/asm/fpu/xstate.h:56
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: arch/x86/include/asm/fpu/xstate.h:56
Inline: True
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
In arch/x86/kernel/fpu/core.c (ffffffff8104197f)
Location: arch/x86/include/asm/fpu/xstate.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81042d1e)
Location: arch/x86/include/asm/fpu/xstate.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81043f34)
Location: arch/x86/include/asm/fpu/xstate.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_supervisor_to_kernel
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_cpu_xstate
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
In arch/x86/kernel/fpu/core.c (ffffffff8104337c)
Location: arch/x86/include/asm/fpu/xstate.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810446d9)
Location: arch/x86/include/asm/fpu/xstate.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81045c34)
Location: arch/x86/include/asm/fpu/xstate.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_supervisor_to_kernel
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_cpu_xstate
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
In arch/x86/kernel/fpu/core.c (ffffffff810499ec)
Location: arch/x86/include/asm/fpu/xstate.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104aa10)
Location: arch/x86/include/asm/fpu/xstate.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104b629)
Location: arch/x86/include/asm/fpu/xstate.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
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
In arch/x86/kernel/fpu/core.c (ffffffff81053b6c)
Location: arch/x86/kernel/fpu/xstate.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81054f34)
Location: arch/x86/kernel/fpu/xstate.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81055c84)
Location: arch/x86/kernel/fpu/xstate.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:__xstate_request_perm
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
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
In arch/x86/kernel/fpu/core.c (ffffffff8106160c)
Location: arch/x86/kernel/fpu/xstate.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81062a6e)
Location: arch/x86/kernel/fpu/xstate.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81063ad4)
Location: arch/x86/kernel/fpu/xstate.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:__xstate_request_perm
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
  - arch/x86/kernel/fpu/xstate.c:init_xstate_size
  - arch/x86/kernel/fpu/xstate.c:init_xstate_size
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
In arch/x86/kernel/fpu/core.c (ffffffff81062edc)
Location: arch/x86/kernel/fpu/xstate.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81064494)
Location: arch/x86/kernel/fpu/xstate.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81065424)
Location: arch/x86/kernel/fpu/xstate.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:__xstate_request_perm
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
  - arch/x86/kernel/fpu/xstate.c:init_xstate_size
  - arch/x86/kernel/fpu/xstate.c:init_xstate_size
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
In arch/x86/kernel/fpu/core.c (ffffffff8106a1cc)
Location: arch/x86/kernel/fpu/xstate.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106b95d)
Location: arch/x86/kernel/fpu/xstate.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106c29c)
Location: arch/x86/kernel/fpu/xstate.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:__xstate_request_perm
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
  - arch/x86/kernel/fpu/xstate.c:init_xstate_size
  - arch/x86/kernel/fpu/xstate.c:init_xstate_size
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
