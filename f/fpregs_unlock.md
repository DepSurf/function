# Function: <code>fpregs_unlock</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103e465)
Location: arch/x86/include/asm/fpu/api.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f364)
Location: arch/x86/include/asm/fpu/api.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103fe7c)
Location: arch/x86/include/asm/fpu/api.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8108dc0a)
Location: arch/x86/include/asm/fpu/api.h:39
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
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
In arch/x86/kernel/fpu/core.c (ffffffff8103ec25)
Location: arch/x86/include/asm/fpu/api.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f8e8)
Location: arch/x86/include/asm/fpu/api.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104059c)
Location: arch/x86/include/asm/fpu/api.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8108e86a)
Location: arch/x86/include/asm/fpu/api.h:39
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
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
In arch/x86/kernel/fpu/core.c (ffffffff81041a0d)
Location: arch/x86/include/asm/fpu/api.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81042b4e)
Location: arch/x86/include/asm/fpu/api.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81043940)
Location: arch/x86/include/asm/fpu/api.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff810949ed)
Location: arch/x86/include/asm/fpu/api.h:39
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
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
In arch/x86/kernel/fpu/core.c (ffffffff81041999)
Location: arch/x86/include/asm/fpu/api.h:63
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81042a99)
Location: arch/x86/include/asm/fpu/api.h:63
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810439f0)
Location: arch/x86/include/asm/fpu/api.h:63
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff81093ddd)
Location: arch/x86/include/asm/fpu/api.h:63
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
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
In arch/x86/kernel/fpu/core.c (ffffffff81043399)
Location: arch/x86/include/asm/fpu/api.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81044487)
Location: arch/x86/include/asm/fpu/api.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81045234)
Location: arch/x86/include/asm/fpu/api.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8109479d)
Location: arch/x86/include/asm/fpu/api.h:75
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
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
In arch/x86/kernel/fpu/core.c (ffffffff81049b0c)
Location: arch/x86/include/asm/fpu/api.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_flush_thread
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104a997)
Location: arch/x86/include/asm/fpu/api.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
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
In arch/x86/kernel/fpu/core.c (ffffffff810538df)
Location: arch/x86/include/asm/fpu/api.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_flush_thread
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_update_guest_xfd
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81054e73)
Location: arch/x86/include/asm/fpu/api.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81055fde)
Location: arch/x86/include/asm/fpu/api.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpstate_realloc
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
In arch/x86/kernel/fpu/core.c (ffffffff81061680)
Location: arch/x86/include/asm/fpu/api.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:fpu_reset_fpregs
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_update_guest_xfd
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810629c9)
Location: arch/x86/include/asm/fpu/api.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810638aa)
Location: arch/x86/include/asm/fpu/api.h:77
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
In arch/x86/kernel/fpu/core.c (ffffffff81062f54)
Location: arch/x86/include/asm/fpu/api.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:fpu_reset_fpregs
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_update_guest_xfd
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810643df)
Location: arch/x86/include/asm/fpu/api.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81065216)
Location: arch/x86/include/asm/fpu/api.h:77
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
In arch/x86/kernel/fpu/core.c (ffffffff8106a240)
Location: arch/x86/include/asm/fpu/api.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:fpu_reset_fpregs
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_update_guest_xfd
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106b8c4)
Location: arch/x86/include/asm/fpu/api.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106c7ea)
Location: arch/x86/include/asm/fpu/api.h:77
Inline: True
```
```
In arch/x86/kernel/shstk.c (ffffffff810cadae)
Location: arch/x86/include/asm/fpu/api.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/shstk.c:shstk_prctl
  - arch/x86/kernel/shstk.c:wrss_control
  - arch/x86/kernel/shstk.c:restore_signal_shadow_stack
  - arch/x86/kernel/shstk.c:restore_signal_shadow_stack
  - arch/x86/kernel/shstk.c:setup_signal_shadow_stack
  - arch/x86/kernel/shstk.c:setup_signal_shadow_stack
  - arch/x86/kernel/shstk.c:shstk_setup
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
In arch/x86/kernel/fpu/core.c (ffffffff8103eda5)
Location: arch/x86/include/asm/fpu/api.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103fa68)
Location: arch/x86/include/asm/fpu/api.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104071c)
Location: arch/x86/include/asm/fpu/api.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8108d82a)
Location: arch/x86/include/asm/fpu/api.h:39
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
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
In arch/x86/kernel/fpu/core.c (ffffffff8102e5a5)
Location: arch/x86/include/asm/fpu/api.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8102f268)
Location: arch/x86/include/asm/fpu/api.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8102fefc)
Location: arch/x86/include/asm/fpu/api.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8107c35a)
Location: arch/x86/include/asm/fpu/api.h:39
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
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
In arch/x86/kernel/fpu/core.c (ffffffff8103ebe5)
Location: arch/x86/include/asm/fpu/api.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f8a8)
Location: arch/x86/include/asm/fpu/api.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104055c)
Location: arch/x86/include/asm/fpu/api.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8108d7da)
Location: arch/x86/include/asm/fpu/api.h:39
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
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
In arch/x86/kernel/fpu/core.c (ffffffff8103fe90)
Location: arch/x86/include/asm/fpu/api.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81040f18)
Location: arch/x86/include/asm/fpu/api.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81041932)
Location: arch/x86/include/asm/fpu/api.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8108fba1)
Location: arch/x86/include/asm/fpu/api.h:39
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
</details>
</li>
</ul>

## Differences
