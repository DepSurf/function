# Function: <code>patch_instruction</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int patch_instruction(unsigned int *addr, unsigned int instr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/powerpc/lib/code-patching.c (c0000000000a6ea0)
Location: arch/powerpc/lib/code-patching.c:186
Inline: True
Direct callers:
  - arch/powerpc/kernel/jump_label.c:arch_jump_label_transform
  - arch/powerpc/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/powerpc/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - arch/powerpc/kernel/kprobes.c:arch_disarm_kprobe
  - arch/powerpc/kernel/kprobes.c:arch_arm_kprobe
  - arch/powerpc/kernel/optprobes.c:arch_optimize_kprobes
  - arch/powerpc/kernel/optprobes.c:arch_prepare_optimized_kprobe
  - arch/powerpc/kernel/optprobes.c:arch_prepare_optimized_kprobe
  - arch/powerpc/kernel/optprobes.c:arch_prepare_optimized_kprobe
  - arch/powerpc/kernel/optprobes.c:patch_imm64_load_insns
  - arch/powerpc/kernel/optprobes.c:patch_imm64_load_insns
  - arch/powerpc/kernel/optprobes.c:patch_imm64_load_insns
  - arch/powerpc/kernel/optprobes.c:patch_imm64_load_insns
  - arch/powerpc/kernel/optprobes.c:patch_imm64_load_insns
  - arch/powerpc/kernel/optprobes.c:patch_imm32_load_insns
  - arch/powerpc/kernel/optprobes.c:patch_imm32_load_insns
  - arch/powerpc/kernel/trace/ftrace.c:ftrace_make_nop
  - arch/powerpc/kernel/trace/ftrace.c:ftrace_make_nop
  - arch/powerpc/kernel/trace/ftrace.c:ftrace_modify_code
  - arch/powerpc/kernel/epapr_paravirt.c:early_init_dt_scan_epapr
  - arch/powerpc/lib/code-patching.c:patch_branch
  - arch/powerpc/lib/feature-fixups.c:do_barrier_nospec_fixups_range
  - arch/powerpc/lib/feature-fixups.c:do_rfi_flush_fixups
  - arch/powerpc/lib/feature-fixups.c:do_rfi_flush_fixups
  - arch/powerpc/lib/feature-fixups.c:do_rfi_flush_fixups
  - arch/powerpc/lib/feature-fixups.c:do_stf_barrier_fixups
  - arch/powerpc/lib/feature-fixups.c:do_stf_barrier_fixups
  - arch/powerpc/lib/feature-fixups.c:do_stf_barrier_fixups
  - arch/powerpc/lib/feature-fixups.c:do_stf_barrier_fixups
  - arch/powerpc/lib/feature-fixups.c:do_stf_barrier_fixups
  - arch/powerpc/lib/feature-fixups.c:do_stf_barrier_fixups
  - arch/powerpc/lib/feature-fixups.c:do_stf_barrier_fixups
  - arch/powerpc/lib/feature-fixups.c:do_stf_barrier_fixups
  - arch/powerpc/lib/feature-fixups.c:do_stf_barrier_fixups
  - arch/powerpc/xmon/xmon.c:remove_bpts
  - arch/powerpc/xmon/xmon.c:xmon_core
```
**Symbols:**

```
c0000000000a6ea0-c0000000000a6f3c: patch_instruction (STB_GLOBAL)
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
<b>Arch</b>
<ul>
</ul>
