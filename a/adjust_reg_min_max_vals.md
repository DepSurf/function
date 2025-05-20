# Function: <code>adjust_reg_min_max_vals</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8118fc80)
Location: kernel/bpf/verifier.c:1516
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81196eed)
Location: kernel/bpf/verifier.c:1803
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int adjust_reg_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811a3af0)
Location: kernel/bpf/verifier.c:2329
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811a3af0-ffffffff811a44b2: adjust_reg_min_max_vals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int adjust_reg_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811b8d10)
Location: kernel/bpf/verifier.c:3114
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811b8d10-ffffffff811b9719: adjust_reg_min_max_vals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int adjust_reg_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811c8760)
Location: kernel/bpf/verifier.c:3714
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811c8760-ffffffff811c9270: adjust_reg_min_max_vals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int adjust_reg_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:4842
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_alu_op
```
**Symbols:**

```
ffffffff811dc800-ffffffff811dca48: adjust_reg_min_max_vals (STB_LOCAL)
ffffffff811e552b-ffffffff811e555d: adjust_reg_min_max_vals.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int adjust_reg_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e8fa0)
Location: kernel/bpf/verifier.c:4852
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_alu_op
```
**Symbols:**

```
ffffffff811e8fa0-ffffffff811e91e6: adjust_reg_min_max_vals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int adjust_reg_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120e150)
Location: kernel/bpf/verifier.c:5923
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_alu_op
```
**Symbols:**

```
ffffffff8120e150-ffffffff8120e3fc: adjust_reg_min_max_vals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int adjust_reg_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120e950)
Location: kernel/bpf/verifier.c:6511
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_alu_op
```
**Symbols:**

```
ffffffff8120e950-ffffffff8120ec0f: adjust_reg_min_max_vals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int adjust_reg_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120b360)
Location: kernel/bpf/verifier.c:7674
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_alu_op
```
**Symbols:**

```
ffffffff8120b360-ffffffff8120b61f: adjust_reg_min_max_vals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int adjust_reg_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:7963
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_alu_op
```
**Symbols:**

```
ffffffff8123f050-ffffffff8123f367: adjust_reg_min_max_vals (STB_LOCAL)
ffffffff81cb8444-ffffffff81cb8465: adjust_reg_min_max_vals.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int adjust_reg_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:8954
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_alu_op
```
**Symbols:**

```
ffffffff81284260-ffffffff812844fa: adjust_reg_min_max_vals (STB_LOCAL)
ffffffff81e69635-ffffffff81e69656: adjust_reg_min_max_vals.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int adjust_reg_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:10890
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_alu_op
```
**Symbols:**

```
ffffffff812e0eb0-ffffffff812e11e8: adjust_reg_min_max_vals (STB_LOCAL)
ffffffff820608c3-ffffffff820608fb: adjust_reg_min_max_vals.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int adjust_reg_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:12806
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_alu_op
```
**Symbols:**

```
ffffffff81310f30-ffffffff813111f0: adjust_reg_min_max_vals (STB_LOCAL)
ffffffff820e00f0-ffffffff820e0132: adjust_reg_min_max_vals.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int adjust_reg_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:13744
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_alu_op
```
**Symbols:**

```
ffffffff81331ac0-ffffffff81331d80: adjust_reg_min_max_vals (STB_LOCAL)
ffffffff821bc45e-ffffffff821bc4a0: adjust_reg_min_max_vals.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int adjust_reg_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff80001026c690)
Location: kernel/bpf/verifier.c:4852
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_alu_op
```
**Symbols:**

```
ffff80001026c690-ffff80001026c8fc: adjust_reg_min_max_vals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c049ffec)
Location: kernel/bpf/verifier.c:4852
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_alu_op
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int adjust_reg_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c000000000312c30)
Location: kernel/bpf/verifier.c:4852
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_alu_op
```
**Symbols:**

```
c000000000312c30-c000000000312f10: adjust_reg_min_max_vals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int adjust_reg_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a6a5e)
Location: kernel/bpf/verifier.c:4852
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_alu_op
```
**Symbols:**

```
ffffffe0001a6a5e-ffffffe0001a6c7c: adjust_reg_min_max_vals (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int adjust_reg_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e15c0)
Location: kernel/bpf/verifier.c:4852
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_alu_op
```
**Symbols:**

```
ffffffff811e15c0-ffffffff811e1806: adjust_reg_min_max_vals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int adjust_reg_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d4380)
Location: kernel/bpf/verifier.c:4852
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_alu_op
```
**Symbols:**

```
ffffffff811d4380-ffffffff811d45c6: adjust_reg_min_max_vals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int adjust_reg_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811df390)
Location: kernel/bpf/verifier.c:4852
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_alu_op
```
**Symbols:**

```
ffffffff811df390-ffffffff811df5d6: adjust_reg_min_max_vals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int adjust_reg_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ed7a0)
Location: kernel/bpf/verifier.c:4852
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_alu_op
```
**Symbols:**

```
ffffffff811ed7a0-ffffffff811ed9e6: adjust_reg_min_max_vals (STB_LOCAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
