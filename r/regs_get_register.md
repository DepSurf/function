# Function: <code>regs_get_register</code>

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
In arch/x86/kernel/perf_regs.c (ffffffff810661e4)
Location: arch/x86/include/asm/ptrace.h:172
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_reg_value
```
```
In arch/x86/mm/mpx.c (ffffffff81075a1e)
Location: arch/x86/include/asm/ptrace.h:172
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
```
```
In kernel/trace/trace_probe.c (ffffffff8116d471)
Location: arch/x86/include/asm/ptrace.h:172
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:fetch_reg_u8
  - kernel/trace/trace_probe.c:fetch_reg_u16
  - kernel/trace/trace_probe.c:fetch_reg_u32
  - kernel/trace/trace_probe.c:fetch_reg_u64
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
In arch/x86/kernel/perf_regs.c (ffffffff81065f74)
Location: arch/x86/include/asm/ptrace.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_reg_value
```
```
In arch/x86/mm/mpx.c (ffffffff81076f59)
Location: arch/x86/include/asm/ptrace.h:166
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
```
```
In kernel/trace/trace_probe.c (ffffffff8117aa31)
Location: arch/x86/include/asm/ptrace.h:166
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:fetch_reg_u64
  - kernel/trace/trace_probe.c:fetch_reg_u32
  - kernel/trace/trace_probe.c:fetch_reg_u16
  - kernel/trace/trace_probe.c:fetch_reg_u8
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
In arch/x86/kernel/perf_regs.c (ffffffff810694a4)
Location: arch/x86/include/asm/ptrace.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_reg_value
```
```
In arch/x86/mm/mpx.c (ffffffff8107ab05)
Location: arch/x86/include/asm/ptrace.h:166
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
```
```
In kernel/trace/trace_probe.c (ffffffff81186641)
Location: arch/x86/include/asm/ptrace.h:166
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:fetch_reg_u64
  - kernel/trace/trace_probe.c:fetch_reg_u32
  - kernel/trace/trace_probe.c:fetch_reg_u16
  - kernel/trace/trace_probe.c:fetch_reg_u8
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
In arch/x86/kernel/perf_regs.c (ffffffff81068748)
Location: arch/x86/include/asm/ptrace.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_reg_value
```
```
In arch/x86/mm/mpx.c (ffffffff8107933d)
Location: arch/x86/include/asm/ptrace.h:166
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
```
```
In kernel/trace/trace_probe.c (ffffffff811892a1)
Location: arch/x86/include/asm/ptrace.h:166
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:fetch_reg_u64
  - kernel/trace/trace_probe.c:fetch_reg_u32
  - kernel/trace/trace_probe.c:fetch_reg_u16
  - kernel/trace/trace_probe.c:fetch_reg_u8
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
In arch/x86/kernel/perf_regs.c (ffffffff8106ca24)
Location: arch/x86/include/asm/ptrace.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_reg_value
```
```
In kernel/trace/trace_probe.c (ffffffff81196f21)
Location: arch/x86/include/asm/ptrace.h:191
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:fetch_reg_u64
  - kernel/trace/trace_probe.c:fetch_reg_u32
  - kernel/trace/trace_probe.c:fetch_reg_u16
  - kernel/trace/trace_probe.c:fetch_reg_u8
```
```
In arch/x86/lib/insn-eval.c (ffffffff81983b27)
Location: arch/x86/include/asm/ptrace.h:191
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_eff_addr_sib
  - arch/x86/lib/insn-eval.c:get_eff_addr_sib
  - arch/x86/lib/insn-eval.c:get_eff_addr_modrm
  - arch/x86/lib/insn-eval.c:get_eff_addr_reg
  - arch/x86/lib/insn-eval.c:get_eff_addr_reg
  - arch/x86/lib/insn-eval.c:get_eff_addr_reg
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
In arch/x86/kernel/perf_regs.c (ffffffff8106f8c4)
Location: arch/x86/include/asm/ptrace.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_reg_value
```
```
In kernel/trace/trace_probe.c (ffffffff811abf20)
Location: arch/x86/include/asm/ptrace.h:196
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:fetch_reg_u64
  - kernel/trace/trace_probe.c:fetch_reg_u32
  - kernel/trace/trace_probe.c:fetch_reg_u16
  - kernel/trace/trace_probe.c:fetch_reg_u8
```
```
In arch/x86/lib/insn-eval.c (ffffffff819dffdd)
Location: arch/x86/include/asm/ptrace.h:196
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_eff_addr_sib
  - arch/x86/lib/insn-eval.c:get_eff_addr_sib
  - arch/x86/lib/insn-eval.c:get_eff_addr_modrm
  - arch/x86/lib/insn-eval.c:get_eff_addr_reg
  - arch/x86/lib/insn-eval.c:get_eff_addr_reg
  - arch/x86/lib/insn-eval.c:get_eff_addr_reg
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
In arch/x86/kernel/perf_regs.c (ffffffff81075924)
Location: arch/x86/include/asm/ptrace.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_reg_value
```
```
In kernel/trace/trace_kprobe.c (ffffffff811b5b53)
Location: arch/x86/include/asm/ptrace.h:198
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff811bc327)
Location: arch/x86/include/asm/ptrace.h:198
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
```
In arch/x86/lib/insn-eval.c (ffffffff81a1af6d)
Location: arch/x86/include/asm/ptrace.h:198
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_eff_addr_sib
  - arch/x86/lib/insn-eval.c:get_eff_addr_sib
  - arch/x86/lib/insn-eval.c:get_eff_addr_modrm
  - arch/x86/lib/insn-eval.c:get_eff_addr_reg
  - arch/x86/lib/insn-eval.c:get_eff_addr_reg
  - arch/x86/lib/insn-eval.c:get_eff_addr_reg
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
In arch/x86/kernel/perf_regs.c (ffffffff8107950b)
Location: arch/x86/include/asm/ptrace.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_reg_value
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c4e3f)
Location: arch/x86/include/asm/ptrace.h:213
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cd6e0)
Location: arch/x86/include/asm/ptrace.h:213
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
```
In arch/x86/lib/insn-eval.c (ffffffff81a8ad17)
Location: arch/x86/include/asm/ptrace.h:213
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_eff_addr_sib
  - arch/x86/lib/insn-eval.c:get_eff_addr_sib
  - arch/x86/lib/insn-eval.c:get_eff_addr_modrm
  - arch/x86/lib/insn-eval.c:get_eff_addr_reg
  - arch/x86/lib/insn-eval.c:get_eff_addr_reg
  - arch/x86/lib/insn-eval.c:get_eff_addr_reg
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
In arch/x86/kernel/perf_regs.c (ffffffff8107a55b)
Location: arch/x86/include/asm/ptrace.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_reg_value
```
```
In kernel/trace/trace_kprobe.c (ffffffff811d0943)
Location: arch/x86/include/asm/ptrace.h:213
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d9fb4)
Location: arch/x86/include/asm/ptrace.h:213
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
```
In arch/x86/lib/insn-eval.c (ffffffff81ac1fd7)
Location: arch/x86/include/asm/ptrace.h:213
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_eff_addr_sib
  - arch/x86/lib/insn-eval.c:get_eff_addr_sib
  - arch/x86/lib/insn-eval.c:get_eff_addr_modrm
  - arch/x86/lib/insn-eval.c:get_eff_addr_reg
  - arch/x86/lib/insn-eval.c:get_eff_addr_reg
  - arch/x86/lib/insn-eval.c:get_eff_addr_reg
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
In arch/x86/kernel/perf_regs.c (ffffffff810819aa)
Location: arch/x86/include/asm/ptrace.h:226
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_reg_value
```
```
In kernel/trace/trace_kprobe.c (ffffffff811ec413)
Location: arch/x86/include/asm/ptrace.h:226
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f6a5f)
Location: arch/x86/include/asm/ptrace.h:226
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
```
In arch/x86/lib/insn-eval.c (ffffffff815fe3c5)
Location: arch/x86/include/asm/ptrace.h:226
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_addr_ref_16
  - arch/x86/lib/insn-eval.c:get_addr_ref_16
  - arch/x86/lib/insn-eval.c:get_eff_addr_sib
  - arch/x86/lib/insn-eval.c:get_eff_addr_sib
  - arch/x86/lib/insn-eval.c:get_eff_addr_modrm
  - arch/x86/lib/insn-eval.c:get_eff_addr_reg
  - arch/x86/lib/insn-eval.c:get_eff_addr_reg
  - arch/x86/lib/insn-eval.c:get_eff_addr_reg
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
In arch/x86/kernel/perf_regs.c (ffffffff8108140a)
Location: arch/x86/include/asm/ptrace.h:246
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_reg_value
```
```
In kernel/trace/trace_kprobe.c (ffffffff811ea563)
Location: arch/x86/include/asm/ptrace.h:246
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f5546)
Location: arch/x86/include/asm/ptrace.h:246
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
```
In arch/x86/lib/insn-eval.c (ffffffff816231d5)
Location: arch/x86/include/asm/ptrace.h:246
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_addr_ref_16
  - arch/x86/lib/insn-eval.c:get_addr_ref_16
  - arch/x86/lib/insn-eval.c:get_eff_addr_sib
  - arch/x86/lib/insn-eval.c:get_eff_addr_sib
  - arch/x86/lib/insn-eval.c:get_eff_addr_modrm
  - arch/x86/lib/insn-eval.c:get_eff_addr_reg
  - arch/x86/lib/insn-eval.c:get_eff_addr_reg
  - arch/x86/lib/insn-eval.c:get_eff_addr_reg
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
In arch/x86/kernel/kprobes/core.c (ffffffff8107acc2)
Location: arch/x86/include/asm/ptrace.h:249
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_jmp_indirect
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_call_indirect
```
```
In arch/x86/kernel/perf_regs.c (ffffffff8108222a)
Location: arch/x86/include/asm/ptrace.h:249
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_reg_value
```
```
In kernel/trace/trace_kprobe.c (ffffffff811eb9ca)
Location: arch/x86/include/asm/ptrace.h:249
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f6430)
Location: arch/x86/include/asm/ptrace.h:249
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
```
In arch/x86/lib/insn-eval.c (ffffffff81606a85)
Location: arch/x86/include/asm/ptrace.h:249
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_addr_ref_16
  - arch/x86/lib/insn-eval.c:get_addr_ref_16
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
In arch/x86/kernel/kprobes/core.c (ffffffff81088e72)
Location: arch/x86/include/asm/ptrace.h:249
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_jmp_indirect
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_call_indirect
```
```
In arch/x86/kernel/perf_regs.c (ffffffff81091230)
Location: arch/x86/include/asm/ptrace.h:249
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_reg_value
```
```
In kernel/trace/trace_kprobe.c (ffffffff8121c8fc)
Location: arch/x86/include/asm/ptrace.h:249
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff8122669f)
Location: arch/x86/include/asm/ptrace.h:249
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
```
In arch/x86/lib/insn-eval.c (ffffffff816754e5)
Location: arch/x86/include/asm/ptrace.h:249
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_addr_ref_16
  - arch/x86/lib/insn-eval.c:get_addr_ref_16
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
In arch/x86/kernel/kprobes/core.c (ffffffff81099102)
Location: arch/x86/include/asm/ptrace.h:253
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_jmp_indirect
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_call_indirect
```
```
In arch/x86/kernel/perf_regs.c (ffffffff810a2340)
Location: arch/x86/include/asm/ptrace.h:253
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_reg_value
```
```
In kernel/trace/trace_kprobe.c (ffffffff8125b6e9)
Location: arch/x86/include/asm/ptrace.h:253
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff812662d8)
Location: arch/x86/include/asm/ptrace.h:253
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
```
In arch/x86/lib/insn-eval.c (ffffffff8178ffdd)
Location: arch/x86/include/asm/ptrace.h:253
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_addr_ref_16
  - arch/x86/lib/insn-eval.c:get_addr_ref_16
  - arch/x86/lib/insn-eval.c:get_eff_addr_sib
  - arch/x86/lib/insn-eval.c:get_eff_addr_sib
  - arch/x86/lib/insn-eval.c:get_eff_addr_modrm
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
In arch/x86/kernel/kprobes/core.c (ffffffff810af8d2)
Location: arch/x86/include/asm/ptrace.h:253
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_jmp_indirect
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_call_indirect
```
```
In arch/x86/kernel/perf_regs.c (ffffffff810ba4e0)
Location: arch/x86/include/asm/ptrace.h:253
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_reg_value
```
```
In kernel/trace/trace_kprobe.c (ffffffff812acfdb)
Location: arch/x86/include/asm/ptrace.h:253
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff812b7dcf)
Location: arch/x86/include/asm/ptrace.h:253
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
```
In arch/x86/lib/insn-eval.c (ffffffff8204db6d)
Location: arch/x86/include/asm/ptrace.h:253
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_addr_ref_16
  - arch/x86/lib/insn-eval.c:get_addr_ref_16
  - arch/x86/lib/insn-eval.c:get_eff_addr_sib
  - arch/x86/lib/insn-eval.c:get_eff_addr_sib
  - arch/x86/lib/insn-eval.c:get_eff_addr_modrm
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
In arch/x86/kernel/kprobes/core.c (ffffffff810b28f2)
Location: arch/x86/include/asm/ptrace.h:253
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_jmp_indirect
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_call_indirect
```
```
In arch/x86/kernel/perf_regs.c (ffffffff810bd6b0)
Location: arch/x86/include/asm/ptrace.h:253
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_reg_value
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ceb3a)
Location: arch/x86/include/asm/ptrace.h:253
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff812dac39)
Location: arch/x86/include/asm/ptrace.h:253
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_fprobe.c (ffffffff812e11ad)
Location: arch/x86/include/asm/ptrace.h:253
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:process_fetch_insn
```
```
In arch/x86/lib/insn-eval.c (ffffffff820cc410)
Location: arch/x86/include/asm/ptrace.h:253
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_addr_ref_16
  - arch/x86/lib/insn-eval.c:get_addr_ref_16
  - arch/x86/lib/insn-eval.c:get_eff_addr_sib
  - arch/x86/lib/insn-eval.c:get_eff_addr_sib
  - arch/x86/lib/insn-eval.c:get_eff_addr_modrm
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
In arch/x86/kernel/kprobes/core.c (ffffffff810b9d52)
Location: arch/x86/include/asm/ptrace.h:253
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_jmp_indirect
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_call_indirect
```
```
In arch/x86/kernel/perf_regs.c (ffffffff810c4830)
Location: arch/x86/include/asm/ptrace.h:253
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_reg_value
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ec53a)
Location: arch/x86/include/asm/ptrace.h:253
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff812f8e89)
Location: arch/x86/include/asm/ptrace.h:253
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_fprobe.c (ffffffff812ff1fd)
Location: arch/x86/include/asm/ptrace.h:253
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:process_fetch_insn
```
```
In arch/x86/lib/insn-eval.c (ffffffff821a6c40)
Location: arch/x86/include/asm/ptrace.h:253
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_addr_ref_16
  - arch/x86/lib/insn-eval.c:get_addr_ref_16
  - arch/x86/lib/insn-eval.c:get_eff_addr_sib
  - arch/x86/lib/insn-eval.c:get_eff_addr_sib
  - arch/x86/lib/insn-eval.c:get_eff_addr_modrm
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
In kernel/trace/trace_kprobe.c (ffff80001024f364)
Location: arch/arm64/include/asm/ptrace.h:247
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffff80001025a464)
Location: arch/arm64/include/asm/ptrace.h:247
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
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
In kernel/trace/trace_kprobe.c (c0482280)
Location: arch/arm/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (c048d660)
Location: arch/arm/include/asm/ptrace.h:144
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
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
In arch/powerpc/perf/perf_regs.c (c000000000125fbc)
Location: arch/powerpc/include/asm/ptrace.h:232
Inline: True
Inline callers:
  - arch/powerpc/perf/perf_regs.c:perf_reg_value
```
```
In kernel/trace/trace_kprobe.c (c0000000002eba84)
Location: arch/powerpc/include/asm/ptrace.h:232
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (c0000000002fde38)
Location: arch/powerpc/include/asm/ptrace.h:232
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
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
In arch/x86/kernel/perf_regs.c (ffffffff8107955b)
Location: arch/x86/include/asm/ptrace.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_reg_value
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c8f63)
Location: arch/x86/include/asm/ptrace.h:213
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d25d4)
Location: arch/x86/include/asm/ptrace.h:213
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
```
In arch/x86/lib/insn-eval.c (ffffffff81a60e27)
Location: arch/x86/include/asm/ptrace.h:213
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_eff_addr_sib
  - arch/x86/lib/insn-eval.c:get_eff_addr_sib
  - arch/x86/lib/insn-eval.c:get_eff_addr_modrm
  - arch/x86/lib/insn-eval.c:get_eff_addr_reg
  - arch/x86/lib/insn-eval.c:get_eff_addr_reg
  - arch/x86/lib/insn-eval.c:get_eff_addr_reg
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
In arch/x86/kernel/perf_regs.c (ffffffff81068cdb)
Location: arch/x86/include/asm/ptrace.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_reg_value
```
```
In kernel/trace/trace_kprobe.c (ffffffff811bbd43)
Location: arch/x86/include/asm/ptrace.h:213
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c53a4)
Location: arch/x86/include/asm/ptrace.h:213
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
```
In arch/x86/lib/insn-eval.c (ffffffff81a1dea7)
Location: arch/x86/include/asm/ptrace.h:213
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_eff_addr_sib
  - arch/x86/lib/insn-eval.c:get_eff_addr_sib
  - arch/x86/lib/insn-eval.c:get_eff_addr_modrm
  - arch/x86/lib/insn-eval.c:get_eff_addr_reg
  - arch/x86/lib/insn-eval.c:get_eff_addr_reg
  - arch/x86/lib/insn-eval.c:get_eff_addr_reg
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
In arch/x86/kernel/perf_regs.c (ffffffff8107950b)
Location: arch/x86/include/asm/ptrace.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_reg_value
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c6d33)
Location: arch/x86/include/asm/ptrace.h:213
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d03a4)
Location: arch/x86/include/asm/ptrace.h:213
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
```
In arch/x86/lib/insn-eval.c (ffffffff81acd217)
Location: arch/x86/include/asm/ptrace.h:213
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_eff_addr_sib
  - arch/x86/lib/insn-eval.c:get_eff_addr_sib
  - arch/x86/lib/insn-eval.c:get_eff_addr_modrm
  - arch/x86/lib/insn-eval.c:get_eff_addr_reg
  - arch/x86/lib/insn-eval.c:get_eff_addr_reg
  - arch/x86/lib/insn-eval.c:get_eff_addr_reg
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
In arch/x86/kernel/perf_regs.c (ffffffff8107b60b)
Location: arch/x86/include/asm/ptrace.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_reg_value
```
```
In kernel/trace/trace_kprobe.c (ffffffff811d4f93)
Location: arch/x86/include/asm/ptrace.h:213
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff811de644)
Location: arch/x86/include/asm/ptrace.h:213
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
```
In arch/x86/lib/insn-eval.c (ffffffff81ad9727)
Location: arch/x86/include/asm/ptrace.h:213
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_eff_addr_sib
  - arch/x86/lib/insn-eval.c:get_eff_addr_sib
  - arch/x86/lib/insn-eval.c:get_eff_addr_modrm
  - arch/x86/lib/insn-eval.c:get_eff_addr_reg
  - arch/x86/lib/insn-eval.c:get_eff_addr_reg
  - arch/x86/lib/insn-eval.c:get_eff_addr_reg
```
</details>
</li>
</ul>

## Differences
