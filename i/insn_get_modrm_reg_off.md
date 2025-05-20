# Function: <code>insn_get_modrm_reg_off</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int insn_get_modrm_reg_off(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff816233a0)
Location: arch/x86/lib/insn-eval.c:852
Inline: False
Direct callers:
  - arch/x86/kernel/sev-es.c:vc_handle_mmio
  - arch/x86/kernel/sev-es.c:vc_handle_mmio
  - arch/x86/kernel/sev-es.c:vc_handle_mmio_twobyte_ops
  - arch/x86/kernel/sev-es.c:vc_handle_mmio_twobyte_ops
```
**Symbols:**

```
ffffffff816233a0-ffffffff81623404: insn_get_modrm_reg_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int insn_get_modrm_reg_off(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81606c50)
Location: arch/x86/lib/insn-eval.c:848
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_mmio_twobyte_ops
  - arch/x86/kernel/sev.c:vc_handle_mmio_twobyte_ops
```
**Symbols:**

```
ffffffff81606c50-ffffffff81606cb4: insn_get_modrm_reg_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int insn_get_modrm_reg_off(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/lib/insn-eval.c (0)
Location: arch/x86/lib/insn-eval.c:848
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_mmio_twobyte_ops
  - arch/x86/kernel/sev.c:vc_handle_mmio_twobyte_ops
```
**Symbols:**

```
ffffffff81ce0129-ffffffff81ce013d: insn_get_modrm_reg_off.cold (STB_LOCAL)
ffffffff816756e0-ffffffff81675774: insn_get_modrm_reg_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int insn_get_modrm_reg_off(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff817902a9)
Location: arch/x86/lib/insn-eval.c:870
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_modrm_reg_ptr
```
**Symbols:**

```
ffffffff81ea6868-ffffffff81ea687c: insn_get_modrm_reg_off.cold (STB_LOCAL)
ffffffff81790200-ffffffff8179029f: insn_get_modrm_reg_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int insn_get_modrm_reg_off(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff8204de79)
Location: arch/x86/lib/insn-eval.c:870
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_modrm_reg_ptr
```
**Symbols:**

```
ffffffff820b8100-ffffffff820b8114: insn_get_modrm_reg_off.cold (STB_LOCAL)
ffffffff8204ddc0-ffffffff8204de5f: insn_get_modrm_reg_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int insn_get_modrm_reg_off(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff820cc719)
Location: arch/x86/lib/insn-eval.c:870
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_modrm_reg_ptr
```
**Symbols:**

```
ffffffff821394e1-ffffffff821394f5: insn_get_modrm_reg_off.cold (STB_LOCAL)
ffffffff820cc660-ffffffff820cc6ff: insn_get_modrm_reg_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int insn_get_modrm_reg_off(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff821a6f49)
Location: arch/x86/lib/insn-eval.c:870
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_modrm_reg_ptr
```
**Symbols:**

```
ffffffff8221b286-ffffffff8221b29a: insn_get_modrm_reg_off.cold (STB_LOCAL)
ffffffff821a6e90-ffffffff821a6f2f: insn_get_modrm_reg_off (STB_GLOBAL)
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
