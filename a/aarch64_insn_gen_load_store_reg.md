# Function: <code>aarch64_insn_gen_load_store_reg</code>

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
u32 aarch64_insn_gen_load_store_reg(enum aarch64_insn_register reg, enum aarch64_insn_register base, enum aarch64_insn_register offset, enum aarch64_insn_size_type size, enum aarch64_insn_ldst_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/insn.c (ffff8000100967d8)
Location: arch/arm64/kernel/insn.c:596
Inline: False
Direct callers:
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:emit_bpf_tail_call
  - arch/arm64/net/bpf_jit_comp.c:emit_bpf_tail_call
  - arch/arm64/net/bpf_jit_comp.c:emit_bpf_tail_call
```
**Symbols:**

```
ffff8000100967d8-ffff8000100968ac: aarch64_insn_gen_load_store_reg (STB_GLOBAL)
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
