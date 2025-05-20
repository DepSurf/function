# Function: <code>aarch64_insn_gen_add_sub_imm</code>

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
u32 aarch64_insn_gen_add_sub_imm(enum aarch64_insn_register dst, enum aarch64_insn_register src, int imm, enum aarch64_insn_variant variant, enum aarch64_insn_adsb_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/insn.c (ffff800010096c68)
Location: arch/arm64/kernel/insn.c:836
Inline: False
Direct callers:
  - arch/arm64/kernel/module-plts.c:__get_adrp_add_pair
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_epilogue
  - arch/arm64/net/bpf_jit_comp.c:build_epilogue
  - arch/arm64/net/bpf_jit_comp.c:emit_bpf_tail_call
  - arch/arm64/net/bpf_jit_comp.c:emit_bpf_tail_call
  - arch/arm64/net/bpf_jit_comp.c:emit_bpf_tail_call
  - arch/arm64/net/bpf_jit_comp.c:emit_bpf_tail_call
  - arch/arm64/net/bpf_jit_comp.c:build_prologue
  - arch/arm64/net/bpf_jit_comp.c:build_prologue
  - arch/arm64/net/bpf_jit_comp.c:build_prologue
  - arch/arm64/kvm/va_layout.c:kvm_update_va_mask
  - arch/arm64/kvm/va_layout.c:kvm_update_va_mask
```
**Symbols:**

```
ffff800010096c68-ffff800010096d74: aarch64_insn_gen_add_sub_imm (STB_GLOBAL)
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
