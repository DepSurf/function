# Function: <code>aarch64_insn_encode_immediate</code>

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
u32 aarch64_insn_encode_immediate(enum aarch64_insn_imm_type type, u32 insn, u64 imm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/insn.c (ffff800010da7af8)
Location: arch/arm64/kernel/insn.c:317
Inline: False
Direct callers:
  - arch/arm64/kernel/insn.c:aarch64_insn_gen_extr
  - arch/arm64/kernel/insn.c:aarch64_insn_gen_extr
  - arch/arm64/kernel/insn.c:aarch64_encode_immediate
  - arch/arm64/kernel/insn.c:aarch64_encode_immediate
  - arch/arm64/kernel/insn.c:aarch64_encode_immediate
  - arch/arm64/kernel/insn.c:aarch64_insn_adrp_set_offset
  - arch/arm64/kernel/insn.c:aarch64_set_branch_offset
  - arch/arm64/kernel/insn.c:aarch64_set_branch_offset
  - arch/arm64/kernel/insn.c:aarch64_set_branch_offset
  - arch/arm64/kernel/insn.c:aarch64_insn_gen_adr
  - arch/arm64/kernel/insn.c:aarch64_insn_gen_logical_shifted_reg
  - arch/arm64/kernel/insn.c:aarch64_insn_gen_add_sub_shifted_reg
  - arch/arm64/kernel/insn.c:aarch64_insn_gen_movewide
  - arch/arm64/kernel/insn.c:aarch64_insn_gen_bitfield
  - arch/arm64/kernel/insn.c:aarch64_insn_gen_bitfield
  - arch/arm64/kernel/insn.c:aarch64_insn_gen_add_sub_imm
  - arch/arm64/kernel/insn.c:aarch64_insn_gen_prefetch
  - arch/arm64/kernel/insn.c:aarch64_insn_gen_load_store_pair
  - arch/arm64/kernel/insn.c:aarch64_insn_gen_cond_branch_imm
  - arch/arm64/kernel/insn.c:aarch64_insn_gen_comp_branch_imm
  - arch/arm64/kernel/insn.c:aarch64_insn_gen_branch_imm
  - arch/arm64/kernel/module.c:reloc_insn_imm
  - arch/arm64/kernel/module.c:reloc_insn_movw
```
**Symbols:**

```
ffff800010da7af8-ffff800010da7ba8: aarch64_insn_encode_immediate (STB_GLOBAL)
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
