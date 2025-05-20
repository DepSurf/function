# Function: <code>get_seg_base_limit</code>

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
int get_seg_base_limit(struct insn *insn, struct pt_regs *regs, int regoff, long unsigned int *base, long unsigned int *limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff819835f0)
Location: arch/x86/lib/insn-eval.c:826
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff819835f0-ffffffff81983935: get_seg_base_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int get_seg_base_limit(struct insn *insn, struct pt_regs *regs, int regoff, long unsigned int *base, long unsigned int *limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff819dfba0)
Location: arch/x86/lib/insn-eval.c:826
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff819dfba0-ffffffff819dfe62: get_seg_base_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int get_seg_base_limit(struct insn *insn, struct pt_regs *regs, int regoff, long unsigned int *base, long unsigned int *limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a1aa60)
Location: arch/x86/lib/insn-eval.c:826
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff81a1aa60-ffffffff81a1adfa: get_seg_base_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int get_seg_base_limit(struct insn *insn, struct pt_regs *regs, int regoff, long unsigned int *base, long unsigned int *limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a8a7a0)
Location: arch/x86/lib/insn-eval.c:829
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff81a8a7a0-ffffffff81a8ab62: get_seg_base_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int get_seg_base_limit(struct insn *insn, struct pt_regs *regs, int regoff, long unsigned int *base, long unsigned int *limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81ac1a60)
Location: arch/x86/lib/insn-eval.c:829
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff81ac1a60-ffffffff81ac1e22: get_seg_base_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int get_seg_base_limit(struct insn *insn, struct pt_regs *regs, int regoff, long unsigned int *base, long unsigned int *limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff815fe000)
Location: arch/x86/lib/insn-eval.c:833
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_addr_ref_16
```
**Symbols:**

```
ffffffff815fe000-ffffffff815fe317: get_seg_base_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_seg_base_limit(struct insn *insn, struct pt_regs *regs, int regoff, long unsigned int *base, long unsigned int *limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81622ef0)
Location: arch/x86/lib/insn-eval.c:878
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_addr_ref_16
```
**Symbols:**

```
ffffffff81622ef0-ffffffff81623126: get_seg_base_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int get_seg_base_limit(struct insn *insn, struct pt_regs *regs, int regoff, long unsigned int *base, long unsigned int *limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81606680)
Location: arch/x86/lib/insn-eval.c:874
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_addr_ref_16
```
**Symbols:**

```
ffffffff81606680-ffffffff816069dd: get_seg_base_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int get_seg_base_limit(struct insn *insn, struct pt_regs *regs, int regoff, long unsigned int *base, long unsigned int *limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff816750c0)
Location: arch/x86/lib/insn-eval.c:874
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_addr_ref_16
```
**Symbols:**

```
ffffffff816750c0-ffffffff81675432: get_seg_base_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int get_seg_base_limit(struct insn *insn, struct pt_regs *regs, int regoff, long unsigned int *base, long unsigned int *limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff8178fac0)
Location: arch/x86/lib/insn-eval.c:916
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_addr_ref_16
```
**Symbols:**

```
ffffffff8178fac0-ffffffff8178ff16: get_seg_base_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_seg_base_limit(struct insn *insn, struct pt_regs *regs, int regoff, long unsigned int *base, long unsigned int *limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff8204d640)
Location: arch/x86/lib/insn-eval.c:916
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_addr_ref_16
```
**Symbols:**

```
ffffffff8204d640-ffffffff8204da96: get_seg_base_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int get_seg_base_limit(struct insn *insn, struct pt_regs *regs, int regoff, long unsigned int *base, long unsigned int *limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff820cbf10)
Location: arch/x86/lib/insn-eval.c:916
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_addr_ref_16
```
**Symbols:**

```
ffffffff820cbf10-ffffffff820cc331: get_seg_base_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int get_seg_base_limit(struct insn *insn, struct pt_regs *regs, int regoff, long unsigned int *base, long unsigned int *limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff821a6740)
Location: arch/x86/lib/insn-eval.c:916
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_addr_ref_16
```
**Symbols:**

```
ffffffff821a6740-ffffffff821a6b61: get_seg_base_limit (STB_LOCAL)
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
int get_seg_base_limit(struct insn *insn, struct pt_regs *regs, int regoff, long unsigned int *base, long unsigned int *limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a608b0)
Location: arch/x86/lib/insn-eval.c:829
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff81a608b0-ffffffff81a60c72: get_seg_base_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int get_seg_base_limit(struct insn *insn, struct pt_regs *regs, int regoff, long unsigned int *base, long unsigned int *limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a1d9a0)
Location: arch/x86/lib/insn-eval.c:829
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff81a1d9a0-ffffffff81a1dcfd: get_seg_base_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int get_seg_base_limit(struct insn *insn, struct pt_regs *regs, int regoff, long unsigned int *base, long unsigned int *limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81accca0)
Location: arch/x86/lib/insn-eval.c:829
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff81accca0-ffffffff81acd062: get_seg_base_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int get_seg_base_limit(struct insn *insn, struct pt_regs *regs, int regoff, long unsigned int *base, long unsigned int *limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81ad91b0)
Location: arch/x86/lib/insn-eval.c:829
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff81ad91b0-ffffffff81ad9572: get_seg_base_limit (STB_LOCAL)
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
