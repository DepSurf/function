# Function: <code>get_eff_addr_reg</code>

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
int get_eff_addr_reg(struct insn *insn, struct pt_regs *regs, int *regoff, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81983210)
Location: arch/x86/lib/insn-eval.c:876
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff81983210-ffffffff819832b9: get_eff_addr_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int get_eff_addr_reg(struct insn *insn, struct pt_regs *regs, int *regoff, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff819df760)
Location: arch/x86/lib/insn-eval.c:876
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff819df760-ffffffff819df7f7: get_eff_addr_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int get_eff_addr_reg(struct insn *insn, struct pt_regs *regs, int *regoff, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a1a6a0)
Location: arch/x86/lib/insn-eval.c:876
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff81a1a6a0-ffffffff81a1a737: get_eff_addr_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int get_eff_addr_reg(struct insn *insn, struct pt_regs *regs, int *regoff, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a8a3b0)
Location: arch/x86/lib/insn-eval.c:879
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff81a8a3b0-ffffffff81a8a448: get_eff_addr_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int get_eff_addr_reg(struct insn *insn, struct pt_regs *regs, int *regoff, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81ac1670)
Location: arch/x86/lib/insn-eval.c:879
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff81ac1670-ffffffff81ac1708: get_eff_addr_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int get_eff_addr_reg(struct insn *insn, struct pt_regs *regs, int *regoff, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff815fddb0)
Location: arch/x86/lib/insn-eval.c:883
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_addr_ref_16
```
**Symbols:**

```
ffffffff815fddb0-ffffffff815fde93: get_eff_addr_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_eff_addr_reg(struct insn *insn, struct pt_regs *regs, int *regoff, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81622c50)
Location: arch/x86/lib/insn-eval.c:928
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_addr_ref_16
```
**Symbols:**

```
ffffffff81622c50-ffffffff81622d33: get_eff_addr_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int get_eff_addr_reg(struct insn *insn, struct pt_regs *regs, int *regoff, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81606110)
Location: arch/x86/lib/insn-eval.c:924
Inline: True
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_addr_ref_16
```
**Symbols:**

```
ffffffff81606110-ffffffff816061b7: get_eff_addr_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int get_eff_addr_reg(struct insn *insn, struct pt_regs *regs, int *regoff, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81674b40)
Location: arch/x86/lib/insn-eval.c:924
Inline: True
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_addr_ref_16
```
**Symbols:**

```
ffffffff81674b40-ffffffff81674be7: get_eff_addr_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int get_eff_addr_reg(struct insn *insn, struct pt_regs *regs, int *regoff, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff8178f3b0)
Location: arch/x86/lib/insn-eval.c:966
Inline: True
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_addr_ref_16
```
**Symbols:**

```
ffffffff8178f3b0-ffffffff8178f4b6: get_eff_addr_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int get_eff_addr_reg(struct insn *insn, struct pt_regs *regs, int *regoff, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff8204ced0)
Location: arch/x86/lib/insn-eval.c:966
Inline: True
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_addr_ref_16
```
**Symbols:**

```
ffffffff8204ced0-ffffffff8204cfd6: get_eff_addr_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int get_eff_addr_reg(struct insn *insn, struct pt_regs *regs, int *regoff, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff820cb790)
Location: arch/x86/lib/insn-eval.c:966
Inline: True
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_addr_ref_16
```
**Symbols:**

```
ffffffff820cb790-ffffffff820cb896: get_eff_addr_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int get_eff_addr_reg(struct insn *insn, struct pt_regs *regs, int *regoff, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff821a5fc0)
Location: arch/x86/lib/insn-eval.c:966
Inline: True
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_addr_ref_16
```
**Symbols:**

```
ffffffff821a5fc0-ffffffff821a60c6: get_eff_addr_reg (STB_LOCAL)
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
int get_eff_addr_reg(struct insn *insn, struct pt_regs *regs, int *regoff, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a604c0)
Location: arch/x86/lib/insn-eval.c:879
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff81a604c0-ffffffff81a60558: get_eff_addr_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int get_eff_addr_reg(struct insn *insn, struct pt_regs *regs, int *regoff, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a1d590)
Location: arch/x86/lib/insn-eval.c:879
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff81a1d590-ffffffff81a1d628: get_eff_addr_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int get_eff_addr_reg(struct insn *insn, struct pt_regs *regs, int *regoff, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81acc8b0)
Location: arch/x86/lib/insn-eval.c:879
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff81acc8b0-ffffffff81acc948: get_eff_addr_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int get_eff_addr_reg(struct insn *insn, struct pt_regs *regs, int *regoff, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81ad8dc0)
Location: arch/x86/lib/insn-eval.c:879
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff81ad8dc0-ffffffff81ad8e58: get_eff_addr_reg (STB_LOCAL)
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
