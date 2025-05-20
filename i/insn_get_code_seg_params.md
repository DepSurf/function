# Function: <code>insn_get_code_seg_params</code>

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
int insn_get_code_seg_params(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81983940)
Location: arch/x86/lib/insn-eval.c:740
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff81983940-ffffffff819839a8: insn_get_code_seg_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int insn_get_code_seg_params(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff819dfe70)
Location: arch/x86/lib/insn-eval.c:740
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff819dfe70-ffffffff819dfece: insn_get_code_seg_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int insn_get_code_seg_params(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a1ae00)
Location: arch/x86/lib/insn-eval.c:740
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff81a1ae00-ffffffff81a1ae5e: insn_get_code_seg_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int insn_get_code_seg_params(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a8ab70)
Location: arch/x86/lib/insn-eval.c:744
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff81a8ab70-ffffffff81a8abf7: insn_get_code_seg_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int insn_get_code_seg_params(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81ac1e30)
Location: arch/x86/lib/insn-eval.c:744
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff81ac1e30-ffffffff81ac1eb7: insn_get_code_seg_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int insn_get_code_seg_params(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff815fe480)
Location: arch/x86/lib/insn-eval.c:748
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff815fe480-ffffffff815fe507: insn_get_code_seg_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int insn_get_code_seg_params(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81623290)
Location: arch/x86/lib/insn-eval.c:778
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_decode
```
**Symbols:**

```
ffffffff81623290-ffffffff81623317: insn_get_code_seg_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int insn_get_code_seg_params(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81606b40)
Location: arch/x86/lib/insn-eval.c:774
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_decode_from_regs
```
**Symbols:**

```
ffffffff81606b40-ffffffff81606bc7: insn_get_code_seg_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int insn_get_code_seg_params(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff816755a0)
Location: arch/x86/lib/insn-eval.c:774
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_decode_from_regs
```
**Symbols:**

```
ffffffff816755a0-ffffffff81675627: insn_get_code_seg_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int insn_get_code_seg_params(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff817900a0)
Location: arch/x86/lib/insn-eval.c:796
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_decode_from_regs
```
**Symbols:**

```
ffffffff817900a0-ffffffff81790137: insn_get_code_seg_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int insn_get_code_seg_params(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff8204dc40)
Location: arch/x86/lib/insn-eval.c:796
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_decode_from_regs
```
**Symbols:**

```
ffffffff8204dc40-ffffffff8204dcd7: insn_get_code_seg_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int insn_get_code_seg_params(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff820cc4e0)
Location: arch/x86/lib/insn-eval.c:796
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_decode_from_regs
```
**Symbols:**

```
ffffffff820cc4e0-ffffffff820cc577: insn_get_code_seg_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int insn_get_code_seg_params(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff821a6d10)
Location: arch/x86/lib/insn-eval.c:796
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_decode_from_regs
```
**Symbols:**

```
ffffffff821a6d10-ffffffff821a6da7: insn_get_code_seg_params (STB_GLOBAL)
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
int insn_get_code_seg_params(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a60c80)
Location: arch/x86/lib/insn-eval.c:744
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff81a60c80-ffffffff81a60d07: insn_get_code_seg_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int insn_get_code_seg_params(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a1dd00)
Location: arch/x86/lib/insn-eval.c:744
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff81a1dd00-ffffffff81a1dd87: insn_get_code_seg_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int insn_get_code_seg_params(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81acd070)
Location: arch/x86/lib/insn-eval.c:744
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff81acd070-ffffffff81acd0f7: insn_get_code_seg_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int insn_get_code_seg_params(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81ad9580)
Location: arch/x86/lib/insn-eval.c:744
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff81ad9580-ffffffff81ad9607: insn_get_code_seg_params (STB_GLOBAL)
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
