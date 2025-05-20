# Function: <code>get_segment_selector</code>

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
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81983945)
Location: arch/x86/lib/insn-eval.c:318
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_code_seg_params
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff81983010-ffffffff8198305c: get_segment_selector.isra.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff819dfe75)
Location: arch/x86/lib/insn-eval.c:318
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_code_seg_params
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff819df560-ffffffff819df5ac: get_segment_selector.isra.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a1ae05)
Location: arch/x86/lib/insn-eval.c:318
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_code_seg_params
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff81a1a490-ffffffff81a1a4e2: get_segment_selector.isra.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a8ab93)
Location: arch/x86/lib/insn-eval.c:320
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_code_seg_params
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff81a8a170-ffffffff81a8a1c8: get_segment_selector.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81ac1e53)
Location: arch/x86/lib/insn-eval.c:320
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_code_seg_params
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff81ac1430-ffffffff81ac1488: get_segment_selector.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
short int get_segment_selector(struct pt_regs *regs, int seg_reg_idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff815fe4a3)
Location: arch/x86/lib/insn-eval.c:320
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_code_seg_params
  - arch/x86/lib/insn-eval.c:insn_get_seg_base
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff815fd890-ffffffff815fd8f0: get_segment_selector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
short int get_segment_selector(struct pt_regs *regs, int seg_reg_idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff816232b3)
Location: arch/x86/lib/insn-eval.c:345
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_code_seg_params
  - arch/x86/lib/insn-eval.c:insn_get_seg_base
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff81622600-ffffffff81622660: get_segment_selector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
short int get_segment_selector(struct pt_regs *regs, int seg_reg_idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81606b63)
Location: arch/x86/lib/insn-eval.c:345
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_code_seg_params
  - arch/x86/lib/insn-eval.c:insn_get_seg_base
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff81605ee0-ffffffff81605f3e: get_segment_selector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
short int get_segment_selector(struct pt_regs *regs, int seg_reg_idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff816755c3)
Location: arch/x86/lib/insn-eval.c:345
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_code_seg_params
  - arch/x86/lib/insn-eval.c:insn_get_seg_base
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff816748d0-ffffffff8167492e: get_segment_selector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
short int get_segment_selector(struct pt_regs *regs, int seg_reg_idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff817900cb)
Location: arch/x86/lib/insn-eval.c:343
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_code_seg_params
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff8178f0e0-ffffffff8178f176: get_segment_selector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
short int get_segment_selector(struct pt_regs *regs, int seg_reg_idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff8204dc6b)
Location: arch/x86/lib/insn-eval.c:343
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_code_seg_params
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff8204cbd0-ffffffff8204cc66: get_segment_selector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
short int get_segment_selector(struct pt_regs *regs, int seg_reg_idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff820cc50b)
Location: arch/x86/lib/insn-eval.c:343
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_code_seg_params
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff820cb4a0-ffffffff820cb536: get_segment_selector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
short int get_segment_selector(struct pt_regs *regs, int seg_reg_idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff821a6d3b)
Location: arch/x86/lib/insn-eval.c:343
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_code_seg_params
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff821a5cd0-ffffffff821a5d66: get_segment_selector (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a60ca3)
Location: arch/x86/lib/insn-eval.c:320
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_code_seg_params
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff81a60280-ffffffff81a602d8: get_segment_selector.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a1dd23)
Location: arch/x86/lib/insn-eval.c:320
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_code_seg_params
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff81a1d350-ffffffff81a1d3a8: get_segment_selector.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81acd093)
Location: arch/x86/lib/insn-eval.c:320
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_code_seg_params
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff81acc670-ffffffff81acc6c8: get_segment_selector.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81ad95a3)
Location: arch/x86/lib/insn-eval.c:320
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_code_seg_params
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff81ad8b80-ffffffff81ad8bd8: get_segment_selector.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
