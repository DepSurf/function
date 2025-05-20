# Function: <code>get_eff_addr_sib</code>

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
int get_eff_addr_sib(struct insn *insn, struct pt_regs *regs, int *base_offset, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff819833b0)
Location: arch/x86/lib/insn-eval.c:1059
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff819833b0-ffffffff819834ee: get_eff_addr_sib (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int get_eff_addr_sib(struct insn *insn, struct pt_regs *regs, int *base_offset, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff819df8e0)
Location: arch/x86/lib/insn-eval.c:1059
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff819df8e0-ffffffff819dfa01: get_eff_addr_sib (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int get_eff_addr_sib(struct insn *insn, struct pt_regs *regs, int *base_offset, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a1a820)
Location: arch/x86/lib/insn-eval.c:1059
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff81a1a820-ffffffff81a1a941: get_eff_addr_sib (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int get_eff_addr_sib(struct insn *insn, struct pt_regs *regs, int *base_offset, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a8a530)
Location: arch/x86/lib/insn-eval.c:1062
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff81a8a530-ffffffff81a8a651: get_eff_addr_sib (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int get_eff_addr_sib(struct insn *insn, struct pt_regs *regs, int *base_offset, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81ac17f0)
Location: arch/x86/lib/insn-eval.c:1062
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff81ac17f0-ffffffff81ac1911: get_eff_addr_sib (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int get_eff_addr_sib(struct insn *insn, struct pt_regs *regs, int *base_offset, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff815fdaa0)
Location: arch/x86/lib/insn-eval.c:1066
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff815fdaa0-ffffffff815fdbd7: get_eff_addr_sib (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_eff_addr_sib(struct insn *insn, struct pt_regs *regs, int *base_offset, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81622940)
Location: arch/x86/lib/insn-eval.c:1111
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff81622940-ffffffff81622a77: get_eff_addr_sib (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int get_eff_addr_sib(struct insn *insn, struct pt_regs *regs, int *base_offset, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff816061c0)
Location: arch/x86/lib/insn-eval.c:1108
Inline: True
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff816061c0-ffffffff8160630b: get_eff_addr_sib (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int get_eff_addr_sib(struct insn *insn, struct pt_regs *regs, int *base_offset, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81674bf0)
Location: arch/x86/lib/insn-eval.c:1108
Inline: True
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff81674bf0-ffffffff81674d3b: get_eff_addr_sib (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int get_eff_addr_sib(struct insn *insn, struct pt_regs *regs, int *base_offset, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff8178f600)
Location: arch/x86/lib/insn-eval.c:1150
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff8178f600-ffffffff8178f817: get_eff_addr_sib (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_eff_addr_sib(struct insn *insn, struct pt_regs *regs, int *base_offset, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff8204d140)
Location: arch/x86/lib/insn-eval.c:1150
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff8204d140-ffffffff8204d357: get_eff_addr_sib (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int get_eff_addr_sib(struct insn *insn, struct pt_regs *regs, int *base_offset, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff820cba00)
Location: arch/x86/lib/insn-eval.c:1150
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff820cba00-ffffffff820cbc1a: get_eff_addr_sib (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int get_eff_addr_sib(struct insn *insn, struct pt_regs *regs, int *base_offset, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff821a6230)
Location: arch/x86/lib/insn-eval.c:1150
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff821a6230-ffffffff821a644a: get_eff_addr_sib (STB_LOCAL)
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
int get_eff_addr_sib(struct insn *insn, struct pt_regs *regs, int *base_offset, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a60640)
Location: arch/x86/lib/insn-eval.c:1062
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff81a60640-ffffffff81a60761: get_eff_addr_sib (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int get_eff_addr_sib(struct insn *insn, struct pt_regs *regs, int *base_offset, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a1d700)
Location: arch/x86/lib/insn-eval.c:1062
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff81a1d700-ffffffff81a1d821: get_eff_addr_sib (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int get_eff_addr_sib(struct insn *insn, struct pt_regs *regs, int *base_offset, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81acca30)
Location: arch/x86/lib/insn-eval.c:1062
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff81acca30-ffffffff81accb51: get_eff_addr_sib (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int get_eff_addr_sib(struct insn *insn, struct pt_regs *regs, int *base_offset, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81ad8f40)
Location: arch/x86/lib/insn-eval.c:1062
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff81ad8f40-ffffffff81ad9061: get_eff_addr_sib (STB_LOCAL)
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
