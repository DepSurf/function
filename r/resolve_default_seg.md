# Function: <code>resolve_default_seg</code>

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
In arch/x86/lib/insn-eval.c (ffffffff819837aa)
Location: arch/x86/lib/insn-eval.c:156
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff819834f0-ffffffff8198353a: resolve_default_seg.part.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int resolve_default_seg(struct insn *insn, struct pt_regs *regs, int off);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff819dfa10)
Location: arch/x86/lib/insn-eval.c:156
Inline: True
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff819dfa10-ffffffff819dfae4: resolve_default_seg (STB_LOCAL)
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
In arch/x86/lib/insn-eval.c (ffffffff81a1ac9a)
Location: arch/x86/lib/insn-eval.c:156
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff81a1a950-ffffffff81a1a9a2: resolve_default_seg.part.6 (STB_LOCAL)
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
In arch/x86/lib/insn-eval.c (ffffffff81a8aa15)
Location: arch/x86/lib/insn-eval.c:156
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff81a8a660-ffffffff81a8a6b2: resolve_default_seg.part.0 (STB_LOCAL)
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
In arch/x86/lib/insn-eval.c (ffffffff81ac1cd5)
Location: arch/x86/lib/insn-eval.c:156
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff81ac1920-ffffffff81ac1972: resolve_default_seg.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff815fdbe0)
Location: arch/x86/lib/insn-eval.c:156
Inline: True
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff815fdbe0-ffffffff815fdcb5: resolve_default_seg.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81622a80)
Location: arch/x86/lib/insn-eval.c:181
Inline: True
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff81622a80-ffffffff81622b55: resolve_default_seg.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81606310)
Location: arch/x86/lib/insn-eval.c:181
Inline: True
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff81606310-ffffffff816063e5: resolve_default_seg.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81674d40)
Location: arch/x86/lib/insn-eval.c:181
Inline: True
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff81674d40-ffffffff81674e15: resolve_default_seg.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff8178fdcc)
Location: arch/x86/lib/insn-eval.c:179
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff8204d94c)
Location: arch/x86/lib/insn-eval.c:179
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff820cc1bd)
Location: arch/x86/lib/insn-eval.c:179
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff821a69ed)
Location: arch/x86/lib/insn-eval.c:179
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
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
In arch/x86/lib/insn-eval.c (ffffffff81a60b25)
Location: arch/x86/lib/insn-eval.c:156
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff81a60770-ffffffff81a607c2: resolve_default_seg.part.0 (STB_LOCAL)
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
In arch/x86/lib/insn-eval.c (ffffffff81a1dbd4)
Location: arch/x86/lib/insn-eval.c:156
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff81a1d830-ffffffff81a1d882: resolve_default_seg.part.0 (STB_LOCAL)
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
In arch/x86/lib/insn-eval.c (ffffffff81accf15)
Location: arch/x86/lib/insn-eval.c:156
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff81accb60-ffffffff81accbb2: resolve_default_seg.part.0 (STB_LOCAL)
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
In arch/x86/lib/insn-eval.c (ffffffff81ad9425)
Location: arch/x86/lib/insn-eval.c:156
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff81ad9070-ffffffff81ad90c2: resolve_default_seg.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
