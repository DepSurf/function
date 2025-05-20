# Function: <code>insn_get_modrm_reg_ptr</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long unsigned int *insn_get_modrm_reg_ptr(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/lib/insn-eval.c (0)
Location: arch/x86/lib/insn-eval.c:885
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_mmio
```
**Symbols:**

```
ffffffff81ea687c-ffffffff81ea6890: insn_get_modrm_reg_ptr.cold (STB_LOCAL)
ffffffff817902a0-ffffffff81790352: insn_get_modrm_reg_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long unsigned int *insn_get_modrm_reg_ptr(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/lib/insn-eval.c (0)
Location: arch/x86/lib/insn-eval.c:885
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/mm/extable.c:ex_handler_zeropad
```
**Symbols:**

```
ffffffff820b8114-ffffffff820b8128: insn_get_modrm_reg_ptr.cold (STB_LOCAL)
ffffffff8204de70-ffffffff8204df22: insn_get_modrm_reg_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long unsigned int *insn_get_modrm_reg_ptr(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/lib/insn-eval.c (0)
Location: arch/x86/lib/insn-eval.c:885
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/mm/extable.c:ex_handler_zeropad
```
**Symbols:**

```
ffffffff821394f5-ffffffff82139509: insn_get_modrm_reg_ptr.cold (STB_LOCAL)
ffffffff820cc710-ffffffff820cc7c2: insn_get_modrm_reg_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long unsigned int *insn_get_modrm_reg_ptr(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/lib/insn-eval.c (0)
Location: arch/x86/lib/insn-eval.c:885
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/mm/extable.c:ex_handler_zeropad
```
**Symbols:**

```
ffffffff8221b29a-ffffffff8221b2ae: insn_get_modrm_reg_ptr.cold (STB_LOCAL)
ffffffff821a6f40-ffffffff821a6ff2: insn_get_modrm_reg_ptr (STB_GLOBAL)
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
