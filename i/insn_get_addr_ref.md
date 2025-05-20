# Function: <code>insn_get_addr_ref</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *insn_get_addr_ref(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff819839d0)
Location: arch/x86/lib/insn-eval.c:1349
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
```
**Symbols:**

```
ffffffff819839d0-ffffffff81983c5f: insn_get_addr_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *insn_get_addr_ref(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff819dfef0)
Location: arch/x86/lib/insn-eval.c:1349
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
```
**Symbols:**

```
ffffffff819dfef0-ffffffff819e0186: insn_get_addr_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *insn_get_addr_ref(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a1ae80)
Location: arch/x86/lib/insn-eval.c:1349
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/mpx.c:mpx_fault_info
```
**Symbols:**

```
ffffffff81a1ae80-ffffffff81a1b116: insn_get_addr_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *insn_get_addr_ref(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a8ac20)
Location: arch/x86/lib/insn-eval.c:1352
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/mpx.c:mpx_fault_info
```
**Symbols:**

```
ffffffff81a8ac20-ffffffff81a8aec0: insn_get_addr_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *insn_get_addr_ref(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81ac1ee0)
Location: arch/x86/lib/insn-eval.c:1352
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/mpx.c:mpx_fault_info
```
**Symbols:**

```
ffffffff81ac1ee0-ffffffff81ac2180: insn_get_addr_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *insn_get_addr_ref(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff815fe590)
Location: arch/x86/lib/insn-eval.c:1356
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:get_kernel_gp_address
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff815fe590-ffffffff815fe757: insn_get_addr_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *insn_get_addr_ref(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81623410)
Location: arch/x86/lib/insn-eval.c:1401
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:get_kernel_gp_address
  - arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/sev-es.c:vc_do_mmio
```
**Symbols:**

```
ffffffff81623410-ffffffff816235d7: insn_get_addr_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *insn_get_addr_ref(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81606cc0)
Location: arch/x86/lib/insn-eval.c:1403
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:get_kernel_gp_address
  - arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/sev.c:vc_do_mmio
```
**Symbols:**

```
ffffffff81606cc0-ffffffff81606e87: insn_get_addr_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *insn_get_addr_ref(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81675780)
Location: arch/x86/lib/insn-eval.c:1403
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:get_kernel_gp_address
  - arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/sev.c:vc_do_mmio
```
**Symbols:**

```
ffffffff81675780-ffffffff81675947: insn_get_addr_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *insn_get_addr_ref(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81790360)
Location: arch/x86/lib/insn-eval.c:1445
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:handle_mmio
  - arch/x86/kernel/traps.c:get_kernel_gp_address
  - arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/sev.c:vc_do_mmio
```
**Symbols:**

```
ffffffff81790360-ffffffff81790552: insn_get_addr_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *insn_get_addr_ref(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff8204df40)
Location: arch/x86/lib/insn-eval.c:1445
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:handle_mmio
  - arch/x86/kernel/traps.c:get_kernel_gp_address
  - arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/sev.c:vc_do_mmio
  - arch/x86/mm/extable.c:ex_handler_zeropad
```
**Symbols:**

```
ffffffff8204df40-ffffffff8204e132: insn_get_addr_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *insn_get_addr_ref(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff820cc7e0)
Location: arch/x86/lib/insn-eval.c:1445
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:handle_mmio
  - arch/x86/kernel/traps.c:get_kernel_gp_address
  - arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/sev.c:vc_do_mmio
  - arch/x86/mm/extable.c:ex_handler_zeropad
```
**Symbols:**

```
ffffffff820cc7e0-ffffffff820cc9c6: insn_get_addr_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *insn_get_addr_ref(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff821a7010)
Location: arch/x86/lib/insn-eval.c:1445
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:handle_mmio
  - arch/x86/kernel/traps.c:get_kernel_gp_address
  - arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/sev.c:vc_do_mmio
  - arch/x86/mm/extable.c:ex_handler_zeropad
```
**Symbols:**

```
ffffffff821a7010-ffffffff821a71f6: insn_get_addr_ref (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void *insn_get_addr_ref(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a60d30)
Location: arch/x86/lib/insn-eval.c:1352
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/mpx.c:mpx_fault_info
```
**Symbols:**

```
ffffffff81a60d30-ffffffff81a60fd0: insn_get_addr_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *insn_get_addr_ref(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a1ddb0)
Location: arch/x86/lib/insn-eval.c:1352
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/mpx.c:mpx_fault_info
```
**Symbols:**

```
ffffffff81a1ddb0-ffffffff81a1e041: insn_get_addr_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *insn_get_addr_ref(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81acd120)
Location: arch/x86/lib/insn-eval.c:1352
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/mpx.c:mpx_fault_info
```
**Symbols:**

```
ffffffff81acd120-ffffffff81acd3c0: insn_get_addr_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *insn_get_addr_ref(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81ad9630)
Location: arch/x86/lib/insn-eval.c:1352
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/mpx.c:mpx_fault_info
```
**Symbols:**

```
ffffffff81ad9630-ffffffff81ad98d0: insn_get_addr_ref (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
