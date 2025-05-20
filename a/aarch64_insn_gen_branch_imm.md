# Function: <code>aarch64_insn_gen_branch_imm</code>

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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
u32 aarch64_insn_gen_branch_imm(long unsigned int pc, long unsigned int addr, enum aarch64_insn_branch_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/insn.c (ffff800010da7ba8)
Location: arch/arm64/kernel/insn.c:471
Inline: False
Direct callers:
  - arch/arm64/kernel/ftrace.c:ftrace_disable_ftrace_graph_caller
  - arch/arm64/kernel/ftrace.c:ftrace_enable_ftrace_graph_caller
  - arch/arm64/kernel/ftrace.c:ftrace_make_nop
  - arch/arm64/kernel/ftrace.c:ftrace_make_call
  - arch/arm64/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/arm64/kernel/module.c:apply_relocate_add
  - arch/arm64/kernel/module-plts.c:module_emit_veneer_for_adrp
  - arch/arm64/kernel/jump_label.c:arch_jump_label_transform
  - arch/arm64/net/bpf_jit_comp.c:build_insn
```
**Symbols:**

```
ffff800010da7ba8-ffff800010da7c68: aarch64_insn_gen_branch_imm (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
