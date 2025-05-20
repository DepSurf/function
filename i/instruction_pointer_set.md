# Function: <code>instruction_pointer_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81188e0c)
Location: include/asm-generic/ptrace.h:26
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8119b4da)
Location: include/asm-generic/ptrace.h:26
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811aaece)
Location: include/asm-generic/ptrace.h:26
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811b23ae)
Location: include/asm-generic/ptrace.h:26
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811c5fc1)
Location: include/asm-generic/ptrace.h:26
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
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
In kernel/events/uprobes.c (ffffffff811e645c)
Location: include/asm-generic/ptrace.h:26
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
```
```
In kernel/rseq.c (ffffffff811ea4bf)
Location: include/asm-generic/ptrace.h:26
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
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
In kernel/events/uprobes.c (ffffffff811f6fac)
Location: include/asm-generic/ptrace.h:26
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
```
```
In kernel/rseq.c (ffffffff811fb02f)
Location: include/asm-generic/ptrace.h:26
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
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
In kernel/events/uprobes.c (ffffffff8120efca)
Location: arch/x86/include/asm/ptrace.h:177
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_swbp
```
```
In kernel/rseq.c (ffffffff81212747)
Location: arch/x86/include/asm/ptrace.h:177
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
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
In kernel/events/uprobes.c (ffffffff8121c27a)
Location: arch/x86/include/asm/ptrace.h:177
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_swbp
```
```
In kernel/rseq.c (ffffffff8121ff27)
Location: arch/x86/include/asm/ptrace.h:177
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
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
In kernel/events/uprobes.c (ffffffff81248db5)
Location: arch/x86/include/asm/ptrace.h:190
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_trampoline
```
```
In kernel/rseq.c (ffffffff8124c1f3)
Location: arch/x86/include/asm/ptrace.h:190
Inline: True
Inline callers:
  - kernel/rseq.c:rseq_ip_fixup
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
In kernel/events/uprobes.c (ffffffff812534c5)
Location: arch/x86/include/asm/ptrace.h:205
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_trampoline
```
```
In kernel/rseq.c (ffffffff8125666f)
Location: arch/x86/include/asm/ptrace.h:205
Inline: True
Inline callers:
  - kernel/rseq.c:rseq_ip_fixup
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
In kernel/events/uprobes.c (ffffffff81257888)
Location: arch/x86/include/asm/ptrace.h:208
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_swbp
```
```
In kernel/rseq.c (ffffffff8125ab49)
Location: arch/x86/include/asm/ptrace.h:208
Inline: True
Inline callers:
  - kernel/rseq.c:rseq_ip_fixup
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
In kernel/events/uprobes.c (ffffffff81293604)
Location: arch/x86/include/asm/ptrace.h:208
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
```
```
In kernel/rseq.c (ffffffff8129693a)
Location: arch/x86/include/asm/ptrace.h:208
Inline: True
Inline callers:
  - kernel/rseq.c:rseq_ip_fixup
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
In kernel/trace/rethook.c (ffffffff81269223)
Location: arch/x86/include/asm/ptrace.h:212
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_trampoline_handler
```
```
In kernel/events/uprobes.c (ffffffff812e90de)
Location: arch/x86/include/asm/ptrace.h:212
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
```
```
In kernel/rseq.c (ffffffff812ec9b0)
Location: arch/x86/include/asm/ptrace.h:212
Inline: True
Inline callers:
  - kernel/rseq.c:rseq_ip_fixup
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
In kernel/trace/rethook.c (ffffffff812bb583)
Location: arch/x86/include/asm/ptrace.h:212
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_trampoline_handler
```
```
In kernel/events/uprobes.c (ffffffff81352ca6)
Location: arch/x86/include/asm/ptrace.h:212
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
```
```
In kernel/rseq.c (ffffffff81356d1c)
Location: arch/x86/include/asm/ptrace.h:212
Inline: True
Inline callers:
  - kernel/rseq.c:rseq_ip_fixup
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
In kernel/trace/rethook.c (ffffffff812df1a3)
Location: arch/x86/include/asm/ptrace.h:212
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_trampoline_handler
```
```
In kernel/events/uprobes.c (ffffffff81383eb6)
Location: arch/x86/include/asm/ptrace.h:212
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
```
```
In kernel/rseq.c (ffffffff813887e8)
Location: arch/x86/include/asm/ptrace.h:212
Inline: True
Inline callers:
  - kernel/rseq.c:rseq_ip_fixup
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
In kernel/trace/rethook.c (ffffffff812fd0e3)
Location: arch/x86/include/asm/ptrace.h:212
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_trampoline_handler
```
```
In kernel/events/uprobes.c (ffffffff813ad306)
Location: arch/x86/include/asm/ptrace.h:212
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
```
```
In kernel/rseq.c (ffffffff813b2248)
Location: arch/x86/include/asm/ptrace.h:212
Inline: True
Inline callers:
  - kernel/rseq.c:rseq_ip_fixup
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/probes/kprobes.c (ffff800010da8104)
Location: arch/arm64/include/asm/ptrace.h:340
Inline: True
Inline callers:
  - arch/arm64/kernel/probes/kprobes.c:kprobe_breakpoint_handler
  - arch/arm64/kernel/probes/kprobes.c:kprobe_fault_handler
  - arch/arm64/kernel/probes/kprobes.c:post_kprobe_handler
```
```
In arch/arm64/kernel/probes/simulate-insn.c (ffff800010da8fa4)
Location: arch/arm64/include/asm/ptrace.h:340
Inline: True
Inline callers:
  - arch/arm64/kernel/probes/simulate-insn.c:simulate_ldrsw_literal
  - arch/arm64/kernel/probes/simulate-insn.c:simulate_ldr_literal
  - arch/arm64/kernel/probes/simulate-insn.c:simulate_tbz_tbnz
  - arch/arm64/kernel/probes/simulate-insn.c:simulate_cbz_cbnz
  - arch/arm64/kernel/probes/simulate-insn.c:simulate_br_blr_ret
  - arch/arm64/kernel/probes/simulate-insn.c:simulate_b_cond
  - arch/arm64/kernel/probes/simulate-insn.c:simulate_b_bl
  - arch/arm64/kernel/probes/simulate-insn.c:simulate_adr_adrp
```
```
In arch/arm64/kernel/probes/uprobes.c (ffff8000100ac9bc)
Location: arch/arm64/include/asm/ptrace.h:340
Inline: True
Inline callers:
  - arch/arm64/kernel/probes/uprobes.c:arch_uprobe_abort_xol
  - arch/arm64/kernel/probes/uprobes.c:arch_uprobe_post_xol
  - arch/arm64/kernel/probes/uprobes.c:arch_uprobe_pre_xol
```
```
In kernel/events/uprobes.c (ffff8000102a8204)
Location: arch/arm64/include/asm/ptrace.h:340
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
```
```
In kernel/rseq.c (ffff8000102ad190)
Location: arch/arm64/include/asm/ptrace.h:340
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
```
In arch/arm64/lib/error-inject.c (ffff800010628fd8)
Location: arch/arm64/include/asm/ptrace.h:340
Inline: True
Inline callers:
  - arch/arm64/lib/error-inject.c:override_function_with_return
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/probes/uprobes/core.c (c0327d40)
Location: arch/arm/include/asm/ptrace.h:100
Inline: True
Inline callers:
  - arch/arm/probes/uprobes/core.c:arch_uprobe_abort_xol
```
```
In kernel/events/uprobes.c (c04d6d48)
Location: arch/arm/include/asm/ptrace.h:100
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_swbp
```
```
In kernel/rseq.c (c04d98b0)
Location: arch/arm/include/asm/ptrace.h:100
Inline: True
Inline callers:
  - kernel/rseq.c:rseq_ip_fixup
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/uprobes.c (c000000000068570)
Location: arch/powerpc/include/asm/ptrace.h:119
Inline: True
Inline callers:
  - arch/powerpc/kernel/uprobes.c:arch_uprobe_abort_xol
```
```
In kernel/events/uprobes.c (c00000000035b328)
Location: arch/powerpc/include/asm/ptrace.h:119
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_swbp
```
```
In kernel/rseq.c (c000000000360ab4)
Location: arch/powerpc/include/asm/ptrace.h:119
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
</details>
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
In kernel/events/uprobes.c (ffffffff812148ca)
Location: arch/x86/include/asm/ptrace.h:177
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_swbp
```
```
In kernel/rseq.c (ffffffff81218577)
Location: arch/x86/include/asm/ptrace.h:177
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
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
In kernel/events/uprobes.c (ffffffff8120763a)
Location: arch/x86/include/asm/ptrace.h:177
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_swbp
```
```
In kernel/rseq.c (ffffffff8120b787)
Location: arch/x86/include/asm/ptrace.h:177
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
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
In kernel/events/uprobes.c (ffffffff8121266a)
Location: arch/x86/include/asm/ptrace.h:177
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_swbp
```
```
In kernel/rseq.c (ffffffff81216317)
Location: arch/x86/include/asm/ptrace.h:177
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
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
In kernel/events/uprobes.c (ffffffff812215ea)
Location: arch/x86/include/asm/ptrace.h:177
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_swbp
```
```
In kernel/rseq.c (ffffffff81224fc1)
Location: arch/x86/include/asm/ptrace.h:177
Inline: True
Inline callers:
  - kernel/rseq.c:rseq_ip_fixup
```
</details>
</li>
</ul>

## Differences
