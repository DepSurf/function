# Function: <code>user_64bit_mode</code>

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
In arch/x86/events/core.c (ffffffff8100789f)
Location: arch/x86/include/asm/ptrace.h:125
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_instruction_pointer
```
```
In arch/x86/kernel/step.c (ffffffff8103dd37)
Location: arch/x86/include/asm/ptrace.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
```
```
In arch/x86/kernel/perf_regs.c (ffffffff81066371)
Location: arch/x86/include/asm/ptrace.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/mm/fault.c (ffffffff8106a4df)
Location: arch/x86/include/asm/ptrace.h:125
Inline: True
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
In arch/x86/events/core.c (ffffffff81007ae1)
Location: arch/x86/include/asm/ptrace.h:119
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_instruction_pointer
```
```
In arch/x86/kernel/signal.c (ffffffff8102d6e7)
Location: arch/x86/include/asm/ptrace.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/step.c (ffffffff8103db57)
Location: arch/x86/include/asm/ptrace.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
```
```
In arch/x86/kernel/perf_regs.c (ffffffff81066100)
Location: arch/x86/include/asm/ptrace.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/mm/fault.c (ffffffff8106a23b)
Location: arch/x86/include/asm/ptrace.h:119
Inline: True
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
In arch/x86/events/core.c (ffffffff81007af1)
Location: arch/x86/include/asm/ptrace.h:119
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_instruction_pointer
```
```
In arch/x86/kernel/signal.c (ffffffff8102d56e)
Location: arch/x86/include/asm/ptrace.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103c66d)
Location: arch/x86/include/asm/ptrace.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
```
In arch/x86/kernel/step.c (ffffffff8103d435)
Location: arch/x86/include/asm/ptrace.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
```
```
In arch/x86/kernel/perf_regs.c (ffffffff81069620)
Location: arch/x86/include/asm/ptrace.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/mm/fault.c (ffffffff8106dddb)
Location: arch/x86/include/asm/ptrace.h:119
Inline: True
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
In arch/x86/events/core.c (ffffffff81007866)
Location: arch/x86/include/asm/ptrace.h:119
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_instruction_pointer
```
```
In arch/x86/kernel/signal.c (ffffffff8102b7c1)
Location: arch/x86/include/asm/ptrace.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103a507)
Location: arch/x86/include/asm/ptrace.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
```
In arch/x86/kernel/step.c (ffffffff8103b485)
Location: arch/x86/include/asm/ptrace.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
```
```
In arch/x86/kernel/perf_regs.c (ffffffff81068890)
Location: arch/x86/include/asm/ptrace.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/mm/fault.c (ffffffff8106d30b)
Location: arch/x86/include/asm/ptrace.h:119
Inline: True
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
In arch/x86/events/core.c (ffffffff81007cd2)
Location: arch/x86/include/asm/ptrace.h:139
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_instruction_pointer
```
```
In arch/x86/kernel/signal.c (ffffffff8102c4e7)
Location: arch/x86/include/asm/ptrace.h:139
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103cf30)
Location: arch/x86/include/asm/ptrace.h:139
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
```
In arch/x86/kernel/step.c (ffffffff8103dea7)
Location: arch/x86/include/asm/ptrace.h:139
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
```
```
In arch/x86/kernel/perf_regs.c (ffffffff8106cb90)
Location: arch/x86/include/asm/ptrace.h:139
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/kernel/umip.c (ffffffff8106cfd7)
Location: arch/x86/include/asm/ptrace.h:139
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
```
In arch/x86/mm/fault.c (ffffffff8107206b)
Location: arch/x86/include/asm/ptrace.h:139
Inline: True
```
```
In arch/x86/lib/insn-eval.c (ffffffff81983a8e)
Location: arch/x86/include/asm/ptrace.h:139
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_eff_addr_modrm
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
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
In arch/x86/events/core.c (ffffffff810082e5)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_instruction_pointer
```
```
In arch/x86/kernel/signal.c (ffffffff8102d7c8)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103e678)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
```
In arch/x86/kernel/step.c (ffffffff8103f47c)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
```
```
In arch/x86/kernel/perf_regs.c (ffffffff8106fa2f)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/kernel/umip.c (ffffffff8106ff17)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
```
In arch/x86/mm/fault.c (ffffffff81074e7f)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
```
```
In arch/x86/lib/insn-eval.c (ffffffff819e00da)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_eff_addr_modrm
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
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
In arch/x86/events/core.c (ffffffff810081c5)
Location: arch/x86/include/asm/ptrace.h:146
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_instruction_pointer
```
```
In arch/x86/kernel/signal.c (ffffffff8102ea0c)
Location: arch/x86/include/asm/ptrace.h:146
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103fbe9)
Location: arch/x86/include/asm/ptrace.h:146
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
```
In arch/x86/kernel/step.c (ffffffff81040a7c)
Location: arch/x86/include/asm/ptrace.h:146
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
```
```
In arch/x86/kernel/perf_regs.c (ffffffff81075a8f)
Location: arch/x86/include/asm/ptrace.h:146
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/kernel/umip.c (ffffffff81075e77)
Location: arch/x86/include/asm/ptrace.h:146
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
```
In arch/x86/mm/fault.c (ffffffff8107ac7f)
Location: arch/x86/include/asm/ptrace.h:146
Inline: True
```
```
In arch/x86/lib/insn-eval.c (ffffffff81a1b06a)
Location: arch/x86/include/asm/ptrace.h:146
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_eff_addr_modrm
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
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
In arch/x86/events/core.c (ffffffff810083c5)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_instruction_pointer
```
```
In arch/x86/kernel/signal.c (ffffffff81030619)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/ptrace.c (ffffffff810422be)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
```
In arch/x86/kernel/step.c (ffffffff81043216)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
```
```
In arch/x86/kernel/uprobes.c (ffffffff81079301)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/kernel/uprobes.c:default_post_xol_op
  - arch/x86/kernel/uprobes.c:emulate_push_stack
  - arch/x86/kernel/uprobes.c:emulate_push_stack
```
```
In arch/x86/kernel/perf_regs.c (ffffffff8107968c)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/kernel/umip.c (ffffffff81079a77)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
```
In arch/x86/mm/fault.c (ffffffff8107ec98)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
```
```
In arch/x86/lib/insn-eval.c (ffffffff81a8ae13)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_eff_addr_modrm
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
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
In arch/x86/events/core.c (ffffffff810086c5)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_instruction_pointer
```
```
In arch/x86/kernel/signal.c (ffffffff81031113)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/ptrace.c (ffffffff81042a3e)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
```
In arch/x86/kernel/step.c (ffffffff81043976)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
```
```
In arch/x86/kernel/uprobes.c (ffffffff8107a351)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/kernel/uprobes.c:default_post_xol_op
  - arch/x86/kernel/uprobes.c:emulate_push_stack
  - arch/x86/kernel/uprobes.c:emulate_push_stack
```
```
In arch/x86/kernel/perf_regs.c (ffffffff8107a6dc)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/kernel/umip.c (ffffffff8107aac7)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
```
In arch/x86/mm/fault.c (ffffffff8107fd28)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
```
```
In arch/x86/lib/insn-eval.c (ffffffff81ac20d3)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_eff_addr_modrm
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
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
In arch/x86/events/core.c (ffffffff8100966e)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_instruction_pointer
```
```
In arch/x86/kernel/signal.c (ffffffff8103331c)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/ptrace.c (ffffffff8104592e)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
```
In arch/x86/kernel/step.c (ffffffff810470cf)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:is_setting_trap_flag
```
```
In arch/x86/kernel/uprobes.c (ffffffff8108103b)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/kernel/uprobes.c:default_post_xol_op
  - arch/x86/kernel/uprobes.c:emulate_push_stack
  - arch/x86/kernel/uprobes.c:emulate_push_stack
```
```
In arch/x86/kernel/perf_regs.c (ffffffff81081b28)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/kernel/umip.c (ffffffff81081ed7)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
```
In arch/x86/mm/fault.c (ffffffff81086a9d)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
```
```
In arch/x86/lib/insn-eval.c (ffffffff815fe692)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_eff_addr_modrm
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:insn_get_seg_base
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
In arch/x86/events/core.c (ffffffff8100880e)
Location: arch/x86/include/asm/ptrace.h:146
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_instruction_pointer
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/events/intel/ds.c (ffffffff81010f83)
Location: arch/x86/include/asm/ptrace.h:146
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
```
```
In arch/x86/events/intel/lbr.c (ffffffff810136af)
Location: arch/x86/include/asm/ptrace.h:146
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:branch_type
```
```
In arch/x86/kernel/signal.c (ffffffff81033d6c)
Location: arch/x86/include/asm/ptrace.h:146
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/ptrace.c (ffffffff810453da)
Location: arch/x86/include/asm/ptrace.h:146
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
```
In arch/x86/kernel/step.c (ffffffff8104691f)
Location: arch/x86/include/asm/ptrace.h:146
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:is_setting_trap_flag
```
```
In arch/x86/kernel/uprobes.c (ffffffff81080aeb)
Location: arch/x86/include/asm/ptrace.h:146
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/kernel/uprobes.c:default_post_xol_op
  - arch/x86/kernel/uprobes.c:emulate_push_stack
  - arch/x86/kernel/uprobes.c:emulate_push_stack
```
```
In arch/x86/kernel/perf_regs.c (ffffffff810815c9)
Location: arch/x86/include/asm/ptrace.h:146
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/kernel/umip.c (ffffffff81081d25)
Location: arch/x86/include/asm/ptrace.h:146
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
```
In arch/x86/mm/fault.c (ffffffff8108737d)
Location: arch/x86/include/asm/ptrace.h:146
Inline: True
```
```
In arch/x86/lib/insn-eval.c (ffffffff816236de)
Location: arch/x86/include/asm/ptrace.h:146
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_decode
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_eff_addr_modrm
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:insn_get_seg_base
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
In arch/x86/events/core.c (ffffffff8100919e)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_instruction_pointer
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/events/intel/ds.c (ffffffff81011f33)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
```
```
In arch/x86/events/intel/lbr.c (ffffffff8101482e)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:branch_type
```
```
In arch/x86/kernel/signal.c (ffffffff81035868)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/ptrace.c (ffffffff81047805)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:task_user_regset_view
```
```
In arch/x86/kernel/step.c (ffffffff81048484)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
```
```
In arch/x86/kernel/uprobes.c (ffffffff8108186b)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/kernel/uprobes.c:default_post_xol_op
  - arch/x86/kernel/uprobes.c:emulate_push_stack
```
```
In arch/x86/kernel/perf_regs.c (ffffffff810823ec)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/kernel/umip.c (ffffffff81082b45)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
```
In arch/x86/mm/fault.c (ffffffff81087fbe)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff813bad4c)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
```
In arch/x86/lib/insn-eval.c (ffffffff81606f8e)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_decode_from_regs
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:insn_get_seg_base
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
In arch/x86/events/core.c (ffffffff8100a0bf)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_instruction_pointer
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/events/intel/ds.c (ffffffff81012e23)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
```
```
In arch/x86/events/intel/lbr.c (ffffffff81015bde)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:branch_type
```
```
In arch/x86/kernel/signal.c (ffffffff8103ab48)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/ptrace.c (ffffffff8104e065)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:task_user_regset_view
```
```
In arch/x86/kernel/step.c (ffffffff8104ed94)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
```
```
In arch/x86/kernel/uprobes.c (ffffffff810905bf)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/kernel/uprobes.c:branch_post_xol_op
  - arch/x86/kernel/uprobes.c:default_post_xol_op
  - arch/x86/kernel/uprobes.c:emulate_push_stack
```
```
In arch/x86/kernel/perf_regs.c (ffffffff810913fc)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/kernel/umip.c (ffffffff81091c11)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
```
In arch/x86/mm/fault.c (ffffffff8109733e)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff8140aa4c)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
```
In arch/x86/lib/insn-eval.c (ffffffff81675a9e)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_decode_from_regs
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:insn_get_seg_base
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
In arch/x86/events/core.c (ffffffff810097df)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_instruction_pointer
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/events/intel/ds.c (ffffffff8101401b)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
```
```
In arch/x86/events/intel/lbr.c (ffffffff81017d3b)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:branch_type
```
```
In arch/x86/kernel/signal.c (ffffffff81041db2)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:__setup_rt_frame
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/ptrace.c (ffffffff810590e5)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:task_user_regset_view
```
```
In arch/x86/kernel/step.c (ffffffff81059fe4)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
```
```
In arch/x86/kernel/uprobes.c (ffffffff810a148f)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/kernel/uprobes.c:branch_post_xol_op
  - arch/x86/kernel/uprobes.c:default_post_xol_op
  - arch/x86/kernel/uprobes.c:emulate_push_stack
```
```
In arch/x86/kernel/perf_regs.c (ffffffff810a252c)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/kernel/umip.c (ffffffff810a2e37)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
```
In arch/x86/mm/fault.c (ffffffff810a9e74)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff8147f7fb)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
```
In arch/x86/lib/insn-eval.c (ffffffff8179073e)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_decode_from_regs
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_eff_addr_modrm
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
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
In arch/x86/events/core.c (ffffffff8100ac8f)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_instruction_pointer
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/events/utils.c (ffffffff8100b22f)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/events/utils.c:get_branch_type
```
```
In arch/x86/events/intel/ds.c (ffffffff8101806b)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
```
```
In arch/x86/kernel/signal_64.c (ffffffff8104bc36)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/signal_64.c:x64_setup_rt_frame
  - arch/x86/kernel/signal_64.c:restore_sigcontext
```
```
In arch/x86/kernel/ptrace.c (ffffffff810669e5)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:task_user_regset_view
```
```
In arch/x86/kernel/step.c (ffffffff810678cc)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_single_step
```
```
In arch/x86/kernel/uprobes.c (ffffffff810b95df)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/kernel/uprobes.c:branch_post_xol_op
  - arch/x86/kernel/uprobes.c:default_post_xol_op
  - arch/x86/kernel/uprobes.c:emulate_push_stack
```
```
In arch/x86/kernel/perf_regs.c (ffffffff810ba6fc)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/kernel/umip.c (ffffffff810bb107)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
```
In arch/x86/mm/fault.c (ffffffff810c3444)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff8151294b)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
```
In arch/x86/lib/insn-eval.c (ffffffff8204e35e)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_decode_from_regs
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_eff_addr_modrm
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
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
In arch/x86/events/core.c (ffffffff8100a47f)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_instruction_pointer
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/events/utils.c (ffffffff8100a9ff)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/events/utils.c:get_branch_type
```
```
In arch/x86/events/intel/ds.c (ffffffff8101794b)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
```
```
In arch/x86/kernel/signal_64.c (ffffffff8104c4ba)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/signal_64.c:x64_setup_rt_frame
  - arch/x86/kernel/signal_64.c:restore_sigcontext
```
```
In arch/x86/kernel/ptrace.c (ffffffff81068115)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:task_user_regset_view
```
```
In arch/x86/kernel/step.c (ffffffff8106913d)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_single_step
```
```
In arch/x86/kernel/uprobes.c (ffffffff810bc8bf)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/kernel/uprobes.c:branch_post_xol_op
  - arch/x86/kernel/uprobes.c:default_post_xol_op
  - arch/x86/kernel/uprobes.c:emulate_push_stack
```
```
In arch/x86/kernel/perf_regs.c (ffffffff810bd8cc)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/kernel/umip.c (ffffffff810be244)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
```
In arch/x86/mm/fault.c (ffffffff810c6b64)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff8154a38b)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
```
In arch/x86/lib/insn-eval.c (ffffffff820ccbee)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_decode_from_regs
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_eff_addr_modrm
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
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
In arch/x86/events/core.c (ffffffff8100fb9f)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_instruction_pointer
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/events/utils.c (ffffffff8101017b)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/events/utils.c:get_branch_type
```
```
In arch/x86/events/intel/ds.c (ffffffff8101d48b)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
```
```
In arch/x86/kernel/signal_64.c (ffffffff8105373a)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/signal_64.c:x64_setup_rt_frame
  - arch/x86/kernel/signal_64.c:restore_sigcontext
```
```
In arch/x86/kernel/ptrace.c (ffffffff8106f595)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:task_user_regset_view
```
```
In arch/x86/kernel/step.c (ffffffff810705ad)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_single_step
```
```
In arch/x86/kernel/uprobes.c (ffffffff810c3a3f)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/kernel/uprobes.c:branch_post_xol_op
  - arch/x86/kernel/uprobes.c:default_post_xol_op
  - arch/x86/kernel/uprobes.c:emulate_push_stack
```
```
In arch/x86/kernel/perf_regs.c (ffffffff810c4a4c)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/kernel/umip.c (ffffffff810c53c4)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
```
In arch/x86/mm/fault.c (ffffffff810cefe4)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff8157f3b4)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
```
In arch/x86/lib/insn-eval.c (ffffffff821a740e)
Location: arch/x86/include/asm/ptrace.h:149
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_decode_from_regs
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_eff_addr_modrm
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
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
In arch/x86/events/core.c (ffffffff810086c5)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_instruction_pointer
```
```
In arch/x86/kernel/signal.c (ffffffff81031273)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/ptrace.c (ffffffff81042bbe)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
```
In arch/x86/kernel/step.c (ffffffff81043af6)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
```
```
In arch/x86/kernel/uprobes.c (ffffffff81079351)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/kernel/uprobes.c:default_post_xol_op
  - arch/x86/kernel/uprobes.c:emulate_push_stack
  - arch/x86/kernel/uprobes.c:emulate_push_stack
```
```
In arch/x86/kernel/perf_regs.c (ffffffff810796dc)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/kernel/umip.c (ffffffff81079ac7)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
```
In arch/x86/mm/fault.c (ffffffff8107ed28)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
```
```
In arch/x86/lib/insn-eval.c (ffffffff81a60f23)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_eff_addr_modrm
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
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
In arch/x86/events/core.c (0)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
```
```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
```
```
In arch/x86/kernel/step.c (0)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
```
```
In arch/x86/kernel/uprobes.c (0)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
```
```
In arch/x86/kernel/perf_regs.c (0)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
```
```
In arch/x86/kernel/umip.c (ffffffff8106929a)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
```
In arch/x86/mm/fault.c (0)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
```
```
In arch/x86/lib/insn-eval.c (0)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
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
In arch/x86/events/core.c (ffffffff81008685)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_instruction_pointer
```
```
In arch/x86/kernel/signal.c (ffffffff810310d3)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/ptrace.c (ffffffff810429fe)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
```
In arch/x86/kernel/step.c (ffffffff81043936)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
```
```
In arch/x86/kernel/uprobes.c (ffffffff81079301)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/kernel/uprobes.c:default_post_xol_op
  - arch/x86/kernel/uprobes.c:emulate_push_stack
  - arch/x86/kernel/uprobes.c:emulate_push_stack
```
```
In arch/x86/kernel/perf_regs.c (ffffffff8107968c)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/kernel/umip.c (ffffffff81079a77)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
```
In arch/x86/mm/fault.c (ffffffff8107ecd8)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
```
```
In arch/x86/lib/insn-eval.c (ffffffff81acd313)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_eff_addr_modrm
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
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
In arch/x86/events/core.c (ffffffff810087e5)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_instruction_pointer
```
```
In arch/x86/kernel/signal.c (ffffffff81031f80)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/ptrace.c (ffffffff81043dde)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
```
In arch/x86/kernel/step.c (ffffffff81044d36)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
```
```
In arch/x86/kernel/uprobes.c (ffffffff8107b401)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/kernel/uprobes.c:default_post_xol_op
  - arch/x86/kernel/uprobes.c:emulate_push_stack
  - arch/x86/kernel/uprobes.c:emulate_push_stack
```
```
In arch/x86/kernel/perf_regs.c (ffffffff8107b78c)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/kernel/umip.c (ffffffff8107bb77)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
```
In arch/x86/mm/fault.c (ffffffff81080dc8)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
```
```
In arch/x86/lib/insn-eval.c (ffffffff81ad9823)
Location: arch/x86/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_eff_addr_modrm
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
</details>
</li>
</ul>

## Differences
