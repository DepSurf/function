# Function: <code>get_eff_addr_modrm</code>

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
int get_eff_addr_modrm(struct insn *insn, struct pt_regs *regs, int *regoff, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff819832c0)
Location: arch/x86/lib/insn-eval.c:924
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff819832c0-ffffffff819833a4: get_eff_addr_modrm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int get_eff_addr_modrm(struct insn *insn, struct pt_regs *regs, int *regoff, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff819df800)
Location: arch/x86/lib/insn-eval.c:924
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff819df800-ffffffff819df8da: get_eff_addr_modrm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int get_eff_addr_modrm(struct insn *insn, struct pt_regs *regs, int *regoff, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a1a740)
Location: arch/x86/lib/insn-eval.c:924
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff81a1a740-ffffffff81a1a81a: get_eff_addr_modrm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int get_eff_addr_modrm(struct insn *insn, struct pt_regs *regs, int *regoff, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a8a450)
Location: arch/x86/lib/insn-eval.c:927
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff81a8a450-ffffffff81a8a52a: get_eff_addr_modrm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int get_eff_addr_modrm(struct insn *insn, struct pt_regs *regs, int *regoff, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81ac1710)
Location: arch/x86/lib/insn-eval.c:927
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff81ac1710-ffffffff81ac17ea: get_eff_addr_modrm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int get_eff_addr_modrm(struct insn *insn, struct pt_regs *regs, int *regoff, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff815fdcc0)
Location: arch/x86/lib/insn-eval.c:931
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff815fdcc0-ffffffff815fdda8: get_eff_addr_modrm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_eff_addr_modrm(struct insn *insn, struct pt_regs *regs, int *regoff, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81622b60)
Location: arch/x86/lib/insn-eval.c:976
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff81622b60-ffffffff81622c48: get_eff_addr_modrm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int get_eff_addr_modrm(struct insn *insn, struct pt_regs *regs, int *regoff, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff816063f0)
Location: arch/x86/lib/insn-eval.c:973
Inline: True
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff816063f0-ffffffff816064cd: get_eff_addr_modrm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int get_eff_addr_modrm(struct insn *insn, struct pt_regs *regs, int *regoff, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81674e20)
Location: arch/x86/lib/insn-eval.c:973
Inline: True
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff81674e20-ffffffff81674efd: get_eff_addr_modrm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int get_eff_addr_modrm(struct insn *insn, struct pt_regs *regs, int *regoff, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff8178f4c0)
Location: arch/x86/lib/insn-eval.c:1015
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff8178f4c0-ffffffff8178f5f3: get_eff_addr_modrm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_eff_addr_modrm(struct insn *insn, struct pt_regs *regs, int *regoff, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff8204cff0)
Location: arch/x86/lib/insn-eval.c:1015
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff8204cff0-ffffffff8204d123: get_eff_addr_modrm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int get_eff_addr_modrm(struct insn *insn, struct pt_regs *regs, int *regoff, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff820cb8b0)
Location: arch/x86/lib/insn-eval.c:1015
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff820cb8b0-ffffffff820cb9e7: get_eff_addr_modrm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int get_eff_addr_modrm(struct insn *insn, struct pt_regs *regs, int *regoff, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff821a60e0)
Location: arch/x86/lib/insn-eval.c:1015
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff821a60e0-ffffffff821a6217: get_eff_addr_modrm (STB_LOCAL)
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
int get_eff_addr_modrm(struct insn *insn, struct pt_regs *regs, int *regoff, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a60560)
Location: arch/x86/lib/insn-eval.c:927
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff81a60560-ffffffff81a6063a: get_eff_addr_modrm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int get_eff_addr_modrm(struct insn *insn, struct pt_regs *regs, int *regoff, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a1d630)
Location: arch/x86/lib/insn-eval.c:927
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff81a1d630-ffffffff81a1d6f9: get_eff_addr_modrm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int get_eff_addr_modrm(struct insn *insn, struct pt_regs *regs, int *regoff, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81acc950)
Location: arch/x86/lib/insn-eval.c:927
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff81acc950-ffffffff81acca2a: get_eff_addr_modrm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int get_eff_addr_modrm(struct insn *insn, struct pt_regs *regs, int *regoff, long int *eff_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81ad8e60)
Location: arch/x86/lib/insn-eval.c:927
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff81ad8e60-ffffffff81ad8f3a: get_eff_addr_modrm (STB_LOCAL)
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
