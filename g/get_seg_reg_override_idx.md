# Function: <code>get_seg_reg_override_idx</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81983633)
Location: arch/x86/lib/insn-eval.c:69
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff819dfbe5)
Location: arch/x86/lib/insn-eval.c:69
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a1aaa5)
Location: arch/x86/lib/insn-eval.c:69
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a8a7fc)
Location: arch/x86/lib/insn-eval.c:69
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81ac1abc)
Location: arch/x86/lib/insn-eval.c:69
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff815fe055)
Location: arch/x86/lib/insn-eval.c:69
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_seg_reg_override_idx(struct insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81622660)
Location: arch/x86/lib/insn-eval.c:93
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff81622660-ffffffff81622761: get_seg_reg_override_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff816066d5)
Location: arch/x86/lib/insn-eval.c:93
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81675115)
Location: arch/x86/lib/insn-eval.c:93
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
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
In arch/x86/lib/insn-eval.c (ffffffff8178fb15)
Location: arch/x86/lib/insn-eval.c:91
Inline: True
Inline callers:
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
In arch/x86/lib/insn-eval.c (ffffffff8204d695)
Location: arch/x86/lib/insn-eval.c:91
Inline: True
Inline callers:
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
In arch/x86/lib/insn-eval.c (ffffffff820cbf65)
Location: arch/x86/lib/insn-eval.c:91
Inline: True
Inline callers:
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
In arch/x86/lib/insn-eval.c (ffffffff821a6795)
Location: arch/x86/lib/insn-eval.c:91
Inline: True
Inline callers:
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a6090c)
Location: arch/x86/lib/insn-eval.c:69
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a1d9fc)
Location: arch/x86/lib/insn-eval.c:69
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81acccfc)
Location: arch/x86/lib/insn-eval.c:69
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81ad920c)
Location: arch/x86/lib/insn-eval.c:69
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
