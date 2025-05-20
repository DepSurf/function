# Function: <code>insn_get_modrm_rm_off</code>

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
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int insn_get_modrm_rm_off(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff819839b0)
Location: arch/x86/lib/insn-eval.c:800
Inline: True
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff819839b0-ffffffff819839d0: insn_get_modrm_rm_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int insn_get_modrm_rm_off(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff819dfed0)
Location: arch/x86/lib/insn-eval.c:800
Inline: True
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff819dfed0-ffffffff819dfee2: insn_get_modrm_rm_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int insn_get_modrm_rm_off(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a1ae60)
Location: arch/x86/lib/insn-eval.c:800
Inline: True
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff81a1ae60-ffffffff81a1ae72: insn_get_modrm_rm_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int insn_get_modrm_rm_off(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a8ac00)
Location: arch/x86/lib/insn-eval.c:803
Inline: True
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff81a8ac00-ffffffff81a8ac12: insn_get_modrm_rm_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int insn_get_modrm_rm_off(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81ac1ec0)
Location: arch/x86/lib/insn-eval.c:803
Inline: True
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff81ac1ec0-ffffffff81ac1ed2: insn_get_modrm_rm_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int insn_get_modrm_rm_off(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff815fe510)
Location: arch/x86/lib/insn-eval.c:807
Inline: True
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff815fe510-ffffffff815fe589: insn_get_modrm_rm_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int insn_get_modrm_rm_off(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81623320)
Location: arch/x86/lib/insn-eval.c:837
Inline: True
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/sev-es.c:vc_handle_exitcode
  - arch/x86/kernel/sev-es.c:vc_handle_dr7_write
```
**Symbols:**

```
ffffffff81623320-ffffffff81623399: insn_get_modrm_rm_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int insn_get_modrm_rm_off(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81606bd0)
Location: arch/x86/lib/insn-eval.c:833
Inline: True
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
```
**Symbols:**

```
ffffffff81606bd0-ffffffff81606c49: insn_get_modrm_rm_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int insn_get_modrm_rm_off(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/lib/insn-eval.c (0)
Location: arch/x86/lib/insn-eval.c:833
Inline: True
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
```
**Symbols:**

```
ffffffff81ce0115-ffffffff81ce0129: insn_get_modrm_rm_off.cold (STB_LOCAL)
ffffffff81675630-ffffffff816756d9: insn_get_modrm_rm_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int insn_get_modrm_rm_off(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/lib/insn-eval.c (0)
Location: arch/x86/lib/insn-eval.c:855
Inline: True
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
```
**Symbols:**

```
ffffffff81ea6854-ffffffff81ea6868: insn_get_modrm_rm_off.cold (STB_LOCAL)
ffffffff81790140-ffffffff817901fd: insn_get_modrm_rm_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int insn_get_modrm_rm_off(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/lib/insn-eval.c (0)
Location: arch/x86/lib/insn-eval.c:855
Inline: True
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
```
**Symbols:**

```
ffffffff820b80ec-ffffffff820b8100: insn_get_modrm_rm_off.cold (STB_LOCAL)
ffffffff8204dcf0-ffffffff8204ddad: insn_get_modrm_rm_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int insn_get_modrm_rm_off(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/lib/insn-eval.c (0)
Location: arch/x86/lib/insn-eval.c:855
Inline: True
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
```
**Symbols:**

```
ffffffff821394cd-ffffffff821394e1: insn_get_modrm_rm_off.cold (STB_LOCAL)
ffffffff820cc590-ffffffff820cc64d: insn_get_modrm_rm_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int insn_get_modrm_rm_off(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/lib/insn-eval.c (0)
Location: arch/x86/lib/insn-eval.c:855
Inline: True
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
```
**Symbols:**

```
ffffffff8221b272-ffffffff8221b286: insn_get_modrm_rm_off.cold (STB_LOCAL)
ffffffff821a6dc0-ffffffff821a6e7d: insn_get_modrm_rm_off (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int insn_get_modrm_rm_off(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a60d10)
Location: arch/x86/lib/insn-eval.c:803
Inline: True
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff81a60d10-ffffffff81a60d22: insn_get_modrm_rm_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int insn_get_modrm_rm_off(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a1dd90)
Location: arch/x86/lib/insn-eval.c:803
Inline: True
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff81a1dd90-ffffffff81a1dda2: insn_get_modrm_rm_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int insn_get_modrm_rm_off(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81acd100)
Location: arch/x86/lib/insn-eval.c:803
Inline: True
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff81acd100-ffffffff81acd112: insn_get_modrm_rm_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int insn_get_modrm_rm_off(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81ad9610)
Location: arch/x86/lib/insn-eval.c:803
Inline: True
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff81ad9610-ffffffff81ad9622: insn_get_modrm_rm_off (STB_GLOBAL)
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
