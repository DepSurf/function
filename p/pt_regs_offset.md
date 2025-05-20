# Function: <code>pt_regs_offset</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int pt_regs_offset(struct pt_regs *regs, int regno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff8178f691)
Location: arch/x86/lib/insn-eval.c:440
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_eff_addr_sib
  - arch/x86/lib/insn-eval.c:get_eff_addr_sib
  - arch/x86/lib/insn-eval.c:get_eff_addr_modrm
  - arch/x86/lib/insn-eval.c:insn_get_modrm_reg_ptr
Direct callers:
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:ex_handler_msr
```
**Symbols:**

```
ffffffff8178f890-ffffffff8178f8eb: pt_regs_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int pt_regs_offset(struct pt_regs *regs, int regno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff8204d1d1)
Location: arch/x86/lib/insn-eval.c:440
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_eff_addr_sib
  - arch/x86/lib/insn-eval.c:get_eff_addr_sib
  - arch/x86/lib/insn-eval.c:get_eff_addr_modrm
  - arch/x86/lib/insn-eval.c:insn_get_modrm_reg_ptr
Direct callers:
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:ex_handler_msr
```
**Symbols:**

```
ffffffff8204d3f0-ffffffff8204d44b: pt_regs_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int pt_regs_offset(struct pt_regs *regs, int regno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff820cba91)
Location: arch/x86/lib/insn-eval.c:440
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_eff_addr_sib
  - arch/x86/lib/insn-eval.c:get_eff_addr_sib
  - arch/x86/lib/insn-eval.c:get_eff_addr_modrm
  - arch/x86/lib/insn-eval.c:insn_get_modrm_reg_ptr
Direct callers:
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:ex_handler_msr
```
**Symbols:**

```
ffffffff820cbcb0-ffffffff820cbd0b: pt_regs_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int pt_regs_offset(struct pt_regs *regs, int regno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff821a62c1)
Location: arch/x86/lib/insn-eval.c:440
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_eff_addr_sib
  - arch/x86/lib/insn-eval.c:get_eff_addr_sib
  - arch/x86/lib/insn-eval.c:get_eff_addr_modrm
  - arch/x86/lib/insn-eval.c:insn_get_modrm_reg_ptr
Direct callers:
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:ex_handler_msr
```
**Symbols:**

```
ffffffff821a64e0-ffffffff821a653b: pt_regs_offset (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
