# Function: <code>emit</code>

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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/net/bpf_jit_comp.c (ffff8000100b3c30)
Location: arch/arm64/net/bpf_jit_comp.c:63
Inline: True
Inline callers:
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_epilogue
  - arch/arm64/net/bpf_jit_comp.c:build_epilogue
  - arch/arm64/net/bpf_jit_comp.c:build_epilogue
  - arch/arm64/net/bpf_jit_comp.c:build_epilogue
  - arch/arm64/net/bpf_jit_comp.c:build_epilogue
  - arch/arm64/net/bpf_jit_comp.c:build_epilogue
  - arch/arm64/net/bpf_jit_comp.c:build_epilogue
  - arch/arm64/net/bpf_jit_comp.c:emit_bpf_tail_call
  - arch/arm64/net/bpf_jit_comp.c:emit_bpf_tail_call
  - arch/arm64/net/bpf_jit_comp.c:emit_bpf_tail_call
  - arch/arm64/net/bpf_jit_comp.c:emit_bpf_tail_call
  - arch/arm64/net/bpf_jit_comp.c:emit_bpf_tail_call
  - arch/arm64/net/bpf_jit_comp.c:emit_bpf_tail_call
  - arch/arm64/net/bpf_jit_comp.c:emit_bpf_tail_call
  - arch/arm64/net/bpf_jit_comp.c:emit_bpf_tail_call
  - arch/arm64/net/bpf_jit_comp.c:emit_bpf_tail_call
  - arch/arm64/net/bpf_jit_comp.c:emit_bpf_tail_call
  - arch/arm64/net/bpf_jit_comp.c:emit_bpf_tail_call
  - arch/arm64/net/bpf_jit_comp.c:emit_bpf_tail_call
  - arch/arm64/net/bpf_jit_comp.c:emit_bpf_tail_call
  - arch/arm64/net/bpf_jit_comp.c:emit_bpf_tail_call
  - arch/arm64/net/bpf_jit_comp.c:emit_bpf_tail_call
  - arch/arm64/net/bpf_jit_comp.c:emit_bpf_tail_call
  - arch/arm64/net/bpf_jit_comp.c:emit_bpf_tail_call
  - arch/arm64/net/bpf_jit_comp.c:emit_bpf_tail_call
  - arch/arm64/net/bpf_jit_comp.c:emit_bpf_tail_call
  - arch/arm64/net/bpf_jit_comp.c:build_prologue
  - arch/arm64/net/bpf_jit_comp.c:build_prologue
  - arch/arm64/net/bpf_jit_comp.c:build_prologue
  - arch/arm64/net/bpf_jit_comp.c:build_prologue
  - arch/arm64/net/bpf_jit_comp.c:build_prologue
  - arch/arm64/net/bpf_jit_comp.c:build_prologue
  - arch/arm64/net/bpf_jit_comp.c:build_prologue
  - arch/arm64/net/bpf_jit_comp.c:build_prologue
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/net/bpf_jit_32.c (c032c5cc)
Location: arch/arm/net/bpf_jit_32.c:233
Inline: True
Inline callers:
  - arch/arm/net/bpf_jit_32.c:bpf_int_jit_compile
  - arch/arm/net/bpf_jit_32.c:bpf_int_jit_compile
  - arch/arm/net/bpf_jit_32.c:bpf_int_jit_compile
  - arch/arm/net/bpf_jit_32.c:bpf_int_jit_compile
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_insn
  - arch/arm/net/bpf_jit_32.c:build_prologue
  - arch/arm/net/bpf_jit_32.c:build_prologue
  - arch/arm/net/bpf_jit_32.c:build_prologue
  - arch/arm/net/bpf_jit_32.c:build_prologue
  - arch/arm/net/bpf_jit_32.c:build_prologue
  - arch/arm/net/bpf_jit_32.c:build_prologue
  - arch/arm/net/bpf_jit_32.c:build_prologue
  - arch/arm/net/bpf_jit_32.c:build_prologue
  - arch/arm/net/bpf_jit_32.c:build_prologue
  - arch/arm/net/bpf_jit_32.c:build_prologue
  - arch/arm/net/bpf_jit_32.c:build_prologue
  - arch/arm/net/bpf_jit_32.c:emit_bpf_tail_call
  - arch/arm/net/bpf_jit_32.c:emit_bpf_tail_call
  - arch/arm/net/bpf_jit_32.c:emit_bpf_tail_call
  - arch/arm/net/bpf_jit_32.c:emit_bpf_tail_call
  - arch/arm/net/bpf_jit_32.c:emit_bpf_tail_call
  - arch/arm/net/bpf_jit_32.c:emit_bpf_tail_call
  - arch/arm/net/bpf_jit_32.c:emit_bpf_tail_call
  - arch/arm/net/bpf_jit_32.c:emit_bpf_tail_call
  - arch/arm/net/bpf_jit_32.c:emit_bpf_tail_call
  - arch/arm/net/bpf_jit_32.c:emit_bpf_tail_call
  - arch/arm/net/bpf_jit_32.c:emit_bpf_tail_call
  - arch/arm/net/bpf_jit_32.c:emit_bpf_tail_call
  - arch/arm/net/bpf_jit_32.c:emit_str_r
  - arch/arm/net/bpf_jit_32.c:emit_str_r
  - arch/arm/net/bpf_jit_32.c:emit_str_r
  - arch/arm/net/bpf_jit_32.c:emit_str_r
  - arch/arm/net/bpf_jit_32.c:emit_str_r
  - arch/arm/net/bpf_jit_32.c:emit_str_r
  - arch/arm/net/bpf_jit_32.c:emit_str_r
  - arch/arm/net/bpf_jit_32.c:emit_str_r
  - arch/arm/net/bpf_jit_32.c:emit_str_r
  - arch/arm/net/bpf_jit_32.c:emit_a32_alu_r64
  - arch/arm/net/bpf_jit_32.c:emit_a32_alu_r64
  - arch/arm/net/bpf_jit_32.c:emit_a32_alu_r64
  - arch/arm/net/bpf_jit_32.c:emit_a32_alu_r64
  - arch/arm/net/bpf_jit_32.c:emit_a32_alu_r64
  - arch/arm/net/bpf_jit_32.c:emit_a32_alu_r64
  - arch/arm/net/bpf_jit_32.c:emit_a32_alu_r64
  - arch/arm/net/bpf_jit_32.c:emit_a32_alu_r64
  - arch/arm/net/bpf_jit_32.c:emit_a32_alu_r64
  - arch/arm/net/bpf_jit_32.c:emit_a32_alu_r64
  - arch/arm/net/bpf_jit_32.c:emit_a32_alu_r64
  - arch/arm/net/bpf_jit_32.c:emit_a32_alu_r64
  - arch/arm/net/bpf_jit_32.c:emit_a32_alu_r64
  - arch/arm/net/bpf_jit_32.c:emit_a32_alu_r64
  - arch/arm/net/bpf_jit_32.c:emit_a32_alu_r64
  - arch/arm/net/bpf_jit_32.c:emit_a32_alu_r64
  - arch/arm/net/bpf_jit_32.c:emit_a32_alu_r64
  - arch/arm/net/bpf_jit_32.c:emit_a32_alu_r64
  - arch/arm/net/bpf_jit_32.c:emit_a32_alu_r64
  - arch/arm/net/bpf_jit_32.c:emit_a32_alu_r64
  - arch/arm/net/bpf_jit_32.c:emit_a32_alu_r64
  - arch/arm/net/bpf_jit_32.c:emit_a32_alu_r64
  - arch/arm/net/bpf_jit_32.c:emit_a32_alu_r64
  - arch/arm/net/bpf_jit_32.c:emit_a32_alu_r64
  - arch/arm/net/bpf_jit_32.c:emit_a32_alu_r64
  - arch/arm/net/bpf_jit_32.c:emit_a32_alu_r64
  - arch/arm/net/bpf_jit_32.c:emit_a32_alu_r64
  - arch/arm/net/bpf_jit_32.c:emit_a32_alu_r64
  - arch/arm/net/bpf_jit_32.c:emit_a32_alu_r64
  - arch/arm/net/bpf_jit_32.c:emit_a32_mov_i64
  - arch/arm/net/bpf_jit_32.c:emit_a32_mov_i64
  - arch/arm/net/bpf_jit_32.c:emit_a32_mov_i64
  - arch/arm/net/bpf_jit_32.c:emit_a32_mov_i64
  - arch/arm/net/bpf_jit_32.c:emit_a32_mov_i64
  - arch/arm/net/bpf_jit_32.c:emit_a32_mov_i64
  - arch/arm/net/bpf_jit_32.c:arm_bpf_put_reg64
  - arch/arm/net/bpf_jit_32.c:arm_bpf_put_reg64
  - arch/arm/net/bpf_jit_32.c:arm_bpf_put_reg64
  - arch/arm/net/bpf_jit_32.c:arm_bpf_get_reg64
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/riscv/net/bpf_jit_comp.c (ffffffe0000bddea)
Location: arch/riscv/net/bpf_jit_comp.c:159
Inline: True
Inline callers:
  - arch/riscv/net/bpf_jit_comp.c:build_prologue
  - arch/riscv/net/bpf_jit_comp.c:build_prologue
  - arch/riscv/net/bpf_jit_comp.c:build_prologue
  - arch/riscv/net/bpf_jit_comp.c:build_prologue
  - arch/riscv/net/bpf_jit_comp.c:build_prologue
  - arch/riscv/net/bpf_jit_comp.c:build_prologue
  - arch/riscv/net/bpf_jit_comp.c:build_prologue
  - arch/riscv/net/bpf_jit_comp.c:build_prologue
  - arch/riscv/net/bpf_jit_comp.c:build_prologue
  - arch/riscv/net/bpf_jit_comp.c:build_prologue
  - arch/riscv/net/bpf_jit_comp.c:build_prologue
  - arch/riscv/net/bpf_jit_comp.c:build_prologue
  - arch/riscv/net/bpf_jit_comp.c:build_prologue
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_zext_32_rd_t1
  - arch/riscv/net/bpf_jit_comp.c:emit_zext_32_rd_t1
  - arch/riscv/net/bpf_jit_comp.c:emit_zext_32_rd_t1
  - arch/riscv/net/bpf_jit_comp.c:emit_zext_32_rd_t1
  - arch/riscv/net/bpf_jit_comp.c:emit_zext_32_rd_t1
  - arch/riscv/net/bpf_jit_comp.c:emit_sext_32_rd_rs
  - arch/riscv/net/bpf_jit_comp.c:emit_sext_32_rd_rs
  - arch/riscv/net/bpf_jit_comp.c:emit_zext_32_rd_rs
  - arch/riscv/net/bpf_jit_comp.c:emit_zext_32_rd_rs
  - arch/riscv/net/bpf_jit_comp.c:emit_zext_32_rd_rs
  - arch/riscv/net/bpf_jit_comp.c:emit_zext_32_rd_rs
  - arch/riscv/net/bpf_jit_comp.c:emit_zext_32_rd_rs
  - arch/riscv/net/bpf_jit_comp.c:emit_zext_32_rd_rs
  - arch/riscv/net/bpf_jit_comp.c:emit_bpf_tail_call
  - arch/riscv/net/bpf_jit_comp.c:emit_bpf_tail_call
  - arch/riscv/net/bpf_jit_comp.c:emit_bpf_tail_call
  - arch/riscv/net/bpf_jit_comp.c:emit_bpf_tail_call
  - arch/riscv/net/bpf_jit_comp.c:emit_bpf_tail_call
  - arch/riscv/net/bpf_jit_comp.c:emit_bpf_tail_call
  - arch/riscv/net/bpf_jit_comp.c:emit_bpf_tail_call
  - arch/riscv/net/bpf_jit_comp.c:emit_bpf_tail_call
  - arch/riscv/net/bpf_jit_comp.c:emit_bpf_tail_call
  - arch/riscv/net/bpf_jit_comp.c:emit_bpf_tail_call
  - arch/riscv/net/bpf_jit_comp.c:emit_bpf_tail_call
  - arch/riscv/net/bpf_jit_comp.c:emit_bpf_tail_call
  - arch/riscv/net/bpf_jit_comp.c:emit_bpf_tail_call
  - arch/riscv/net/bpf_jit_comp.c:__build_epilogue
  - arch/riscv/net/bpf_jit_comp.c:__build_epilogue
  - arch/riscv/net/bpf_jit_comp.c:__build_epilogue
  - arch/riscv/net/bpf_jit_comp.c:__build_epilogue
  - arch/riscv/net/bpf_jit_comp.c:__build_epilogue
  - arch/riscv/net/bpf_jit_comp.c:__build_epilogue
  - arch/riscv/net/bpf_jit_comp.c:__build_epilogue
  - arch/riscv/net/bpf_jit_comp.c:__build_epilogue
  - arch/riscv/net/bpf_jit_comp.c:__build_epilogue
  - arch/riscv/net/bpf_jit_comp.c:__build_epilogue
  - arch/riscv/net/bpf_jit_comp.c:__build_epilogue
  - arch/riscv/net/bpf_jit_comp.c:emit_imm
  - arch/riscv/net/bpf_jit_comp.c:emit_imm
  - arch/riscv/net/bpf_jit_comp.c:emit_imm
  - arch/riscv/net/bpf_jit_comp.c:emit_imm
  - arch/riscv/net/bpf_jit_comp.c:emit_imm
```
</details>
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
