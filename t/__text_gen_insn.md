# Function: <code>__text_gen_insn</code>

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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff83451ee2)
Location: arch/x86/include/asm/text-patching.h:101
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/kernel/jump_label.c (ffffffff810493de)
Location: arch/x86/include/asm/text-patching.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/jump_label.c:__jump_label_patch
  - arch/x86/kernel/jump_label.c:__jump_label_patch
```
```
In arch/x86/kernel/static_call.c (ffffffff81f19606)
Location: arch/x86/include/asm/text-patching.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/static_call.c:__static_call_transform
  - arch/x86/kernel/static_call.c:__static_call_transform
  - arch/x86/kernel/static_call.c:__static_call_transform
```
```
In arch/x86/kernel/ftrace.c (ffffffff81094eb5)
Location: arch/x86/include/asm/text-patching.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/x86/kernel/ftrace.c:ftrace_make_call
  - arch/x86/kernel/ftrace.c:ftrace_make_nop
```
```
In arch/x86/kernel/paravirt.c (ffffffff810a0a74)
Location: arch/x86/include/asm/text-patching.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch
  - arch/x86/kernel/paravirt.c:paravirt_patch
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
In arch/x86/xen/enlighten_pv.c (ffffffff83e6ee01)
Location: arch/x86/include/asm/text-patching.h:102
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/kernel/jump_label.c (ffffffff8105440e)
Location: arch/x86/include/asm/text-patching.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/jump_label.c:__jump_label_patch
  - arch/x86/kernel/jump_label.c:__jump_label_patch
```
```
In arch/x86/kernel/alternative.c (ffffffff8105a799)
Location: arch/x86/include/asm/text-patching.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:apply_returns
  - arch/x86/kernel/alternative.c:patch_retpoline
  - arch/x86/kernel/alternative.c:patch_retpoline
```
```
In arch/x86/kernel/static_call.c (ffffffff820c1150)
Location: arch/x86/include/asm/text-patching.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/static_call.c:__static_call_transform
  - arch/x86/kernel/static_call.c:__static_call_transform
  - arch/x86/kernel/static_call.c:__static_call_transform
  - arch/x86/kernel/static_call.c:__static_call_transform
```
```
In arch/x86/kernel/ftrace.c (ffffffff810aa965)
Location: arch/x86/include/asm/text-patching.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/x86/kernel/ftrace.c:ftrace_make_call
  - arch/x86/kernel/ftrace.c:ftrace_make_nop
```
```
In arch/x86/kernel/paravirt.c (ffffffff810b8784)
Location: arch/x86/include/asm/text-patching.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch
  - arch/x86/kernel/paravirt.c:paravirt_patch
```
```
In arch/x86/kernel/callthunks.c (ffffffff810bef63)
Location: arch/x86/include/asm/text-patching.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/callthunks.c:patch_call
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
In arch/x86/xen/enlighten_pv.c (ffffffff8368fd41)
Location: arch/x86/include/asm/text-patching.h:102
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/kernel/jump_label.c (ffffffff8105546e)
Location: arch/x86/include/asm/text-patching.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/jump_label.c:__jump_label_patch
  - arch/x86/kernel/jump_label.c:__jump_label_patch
```
```
In arch/x86/kernel/alternative.c (ffffffff8105bc57)
Location: arch/x86/include/asm/text-patching.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:apply_returns
  - arch/x86/kernel/alternative.c:patch_retpoline
  - arch/x86/kernel/alternative.c:patch_retpoline
  - arch/x86/kernel/alternative.c:__optimize_nops
  - arch/x86/kernel/alternative.c:__optimize_nops
```
```
In arch/x86/kernel/static_call.c (ffffffff82144e28)
Location: arch/x86/include/asm/text-patching.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/static_call.c:__static_call_transform
  - arch/x86/kernel/static_call.c:__static_call_transform
  - arch/x86/kernel/static_call.c:__static_call_transform
  - arch/x86/kernel/static_call.c:__static_call_transform
```
```
In arch/x86/kernel/ftrace.c (ffffffff810add15)
Location: arch/x86/include/asm/text-patching.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/x86/kernel/ftrace.c:ftrace_make_call
  - arch/x86/kernel/ftrace.c:ftrace_make_nop
```
```
In arch/x86/kernel/paravirt.c (ffffffff810bb954)
Location: arch/x86/include/asm/text-patching.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch
  - arch/x86/kernel/paravirt.c:paravirt_patch
```
```
In arch/x86/kernel/callthunks.c (ffffffff810c2683)
Location: arch/x86/include/asm/text-patching.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/callthunks.c:patch_call
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
In arch/x86/xen/enlighten_pv.c (ffffffff838bf891)
Location: arch/x86/include/asm/text-patching.h:90
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/kernel/jump_label.c (ffffffff8105c6de)
Location: arch/x86/include/asm/text-patching.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/jump_label.c:__jump_label_patch
  - arch/x86/kernel/jump_label.c:__jump_label_patch
```
```
In arch/x86/kernel/alternative.c (ffffffff81062fbb)
Location: arch/x86/include/asm/text-patching.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:apply_returns
  - arch/x86/kernel/alternative.c:patch_retpoline
  - arch/x86/kernel/alternative.c:patch_retpoline
  - arch/x86/kernel/alternative.c:__optimize_nops
  - arch/x86/kernel/alternative.c:__optimize_nops
```
```
In arch/x86/kernel/static_call.c (ffffffff82227548)
Location: arch/x86/include/asm/text-patching.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/static_call.c:__static_call_transform
  - arch/x86/kernel/static_call.c:__static_call_transform
  - arch/x86/kernel/static_call.c:__static_call_transform
  - arch/x86/kernel/static_call.c:__static_call_transform
```
```
In arch/x86/kernel/ftrace.c (ffffffff810b4895)
Location: arch/x86/include/asm/text-patching.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/x86/kernel/ftrace.c:ftrace_make_call
  - arch/x86/kernel/ftrace.c:ftrace_make_nop
```
```
In arch/x86/kernel/callthunks.c (ffffffff810c9af3)
Location: arch/x86/include/asm/text-patching.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/callthunks.c:patch_call
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
