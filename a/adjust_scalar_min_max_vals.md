# Function: <code>adjust_scalar_min_max_vals</code>

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
In kernel/bpf/verifier.c (ffffffff811a3c73)
Location: kernel/bpf/verifier.c:2087
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
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
In kernel/bpf/verifier.c (ffffffff811b8f07)
Location: kernel/bpf/verifier.c:2856
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
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
In kernel/bpf/verifier.c (ffffffff811c8943)
Location: kernel/bpf/verifier.c:3436
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int adjust_scalar_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn, struct bpf_reg_state *dst_reg, struct bpf_reg_state src_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dbf00)
Location: kernel/bpf/verifier.c:4564
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff811dbf00-ffffffff811dc7ff: adjust_scalar_min_max_vals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int adjust_scalar_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn, struct bpf_reg_state *dst_reg, struct bpf_reg_state src_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e8650)
Location: kernel/bpf/verifier.c:4567
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff811e8650-ffffffff811e8fa0: adjust_scalar_min_max_vals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int adjust_scalar_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn, struct bpf_reg_state *dst_reg, struct bpf_reg_state src_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812078d0)
Location: kernel/bpf/verifier.c:5759
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff812078d0-ffffffff81208609: adjust_scalar_min_max_vals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int adjust_scalar_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn, struct bpf_reg_state *dst_reg, struct bpf_reg_state src_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81208410)
Location: kernel/bpf/verifier.c:6342
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff81208410-ffffffff81209190: adjust_scalar_min_max_vals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int adjust_scalar_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn, struct bpf_reg_state *dst_reg, struct bpf_reg_state src_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812099d0)
Location: kernel/bpf/verifier.c:7510
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff812099d0-ffffffff8120aa9a: adjust_scalar_min_max_vals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int adjust_scalar_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn, struct bpf_reg_state *dst_reg, struct bpf_reg_state src_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:7799
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff8123d700-ffffffff8123e6f7: adjust_scalar_min_max_vals (STB_LOCAL)
ffffffff81cb8301-ffffffff81cb8428: adjust_scalar_min_max_vals.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int adjust_scalar_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn, struct bpf_reg_state *dst_reg, struct bpf_reg_state src_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:8793
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff81282b50-ffffffff812839aa: adjust_scalar_min_max_vals (STB_LOCAL)
ffffffff81e694f7-ffffffff81e69619: adjust_scalar_min_max_vals.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int adjust_scalar_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn, struct bpf_reg_state *dst_reg, struct bpf_reg_state src_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:10729
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff812da690-ffffffff812db4e3: adjust_scalar_min_max_vals (STB_LOCAL)
ffffffff820602f7-ffffffff82060419: adjust_scalar_min_max_vals.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int adjust_scalar_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn, struct bpf_reg_state *dst_reg, struct bpf_reg_state src_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:12645
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff813100e0-ffffffff81310f14: adjust_scalar_min_max_vals (STB_LOCAL)
ffffffff820dffca-ffffffff820e00f0: adjust_scalar_min_max_vals.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int adjust_scalar_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn, struct bpf_reg_state *dst_reg, struct bpf_reg_state src_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:13583
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff81330c70-ffffffff81331aa4: adjust_scalar_min_max_vals (STB_LOCAL)
ffffffff821bc338-ffffffff821bc45e: adjust_scalar_min_max_vals.cold (STB_LOCAL)
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
int adjust_scalar_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn, struct bpf_reg_state *dst_reg, struct bpf_reg_state src_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff80001026bff0)
Location: kernel/bpf/verifier.c:4567
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffff80001026bff0-ffff80001026c690: adjust_scalar_min_max_vals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int adjust_scalar_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn, struct bpf_reg_state *dst_reg, struct bpf_reg_state src_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c049e344)
Location: kernel/bpf/verifier.c:4567
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_alu_op
```
**Symbols:**

```
c049e344-c049ee54: adjust_scalar_min_max_vals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int adjust_scalar_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn, struct bpf_reg_state *dst_reg, struct bpf_reg_state src_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c000000000312250)
Location: kernel/bpf/verifier.c:4567
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
c000000000312250-c000000000312c28: adjust_scalar_min_max_vals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int adjust_scalar_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn, struct bpf_reg_state *dst_reg, struct bpf_reg_state src_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a63f6)
Location: kernel/bpf/verifier.c:4567
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffe0001a63f6-ffffffe0001a6a5e: adjust_scalar_min_max_vals (STB_LOCAL)
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
int adjust_scalar_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn, struct bpf_reg_state *dst_reg, struct bpf_reg_state src_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e0c70)
Location: kernel/bpf/verifier.c:4567
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff811e0c70-ffffffff811e15c0: adjust_scalar_min_max_vals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int adjust_scalar_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn, struct bpf_reg_state *dst_reg, struct bpf_reg_state src_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d3a30)
Location: kernel/bpf/verifier.c:4567
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff811d3a30-ffffffff811d4380: adjust_scalar_min_max_vals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int adjust_scalar_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn, struct bpf_reg_state *dst_reg, struct bpf_reg_state src_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dea40)
Location: kernel/bpf/verifier.c:4567
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff811dea40-ffffffff811df390: adjust_scalar_min_max_vals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int adjust_scalar_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn, struct bpf_reg_state *dst_reg, struct bpf_reg_state src_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ece50)
Location: kernel/bpf/verifier.c:4567
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff811ece50-ffffffff811ed7a0: adjust_scalar_min_max_vals (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
