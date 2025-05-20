# Function: <code>sanitize_ptr_alu</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sanitize_ptr_alu(struct bpf_verifier_env *env, struct bpf_insn *insn, const struct bpf_reg_state *ptr_reg, struct bpf_reg_state *dst_reg, bool off_is_neg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811c7940)
Location: kernel/bpf/verifier.c:3143
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff811c7940-ffffffff811c7b7b: sanitize_ptr_alu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sanitize_ptr_alu(struct bpf_verifier_env *env, struct bpf_insn *insn, const struct bpf_reg_state *ptr_reg, struct bpf_reg_state *dst_reg, bool off_is_neg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811db030)
Location: kernel/bpf/verifier.c:4266
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff811db030-ffffffff811db29c: sanitize_ptr_alu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sanitize_ptr_alu(struct bpf_verifier_env *env, struct bpf_insn *insn, const struct bpf_reg_state *ptr_reg, struct bpf_reg_state *dst_reg, bool off_is_neg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e7780)
Location: kernel/bpf/verifier.c:4269
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff811e7780-ffffffff811e79ec: sanitize_ptr_alu (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff81207490)
Location: kernel/bpf/verifier.c:4946
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff81207490-ffffffff8120772b: sanitize_ptr_alu.constprop.0.isra.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff81207d50)
Location: kernel/bpf/verifier.c:5457
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff81207d50-ffffffff8120801c: sanitize_ptr_alu.constprop.0.isra.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff81209530)
Location: kernel/bpf/verifier.c:6489
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff81209530-ffffffff812098b5: sanitize_ptr_alu.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sanitize_ptr_alu(struct bpf_verifier_env *env, struct bpf_insn *insn, const struct bpf_reg_state *ptr_reg, const struct bpf_reg_state *off_reg, struct bpf_reg_state *dst_reg, struct bpf_sanitize_info *info, const bool commit_window);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:6778
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff8123d1f0-ffffffff8123d5e1: sanitize_ptr_alu (STB_LOCAL)
ffffffff81cb81dd-ffffffff81cb8301: sanitize_ptr_alu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sanitize_ptr_alu(struct bpf_verifier_env *env, struct bpf_insn *insn, const struct bpf_reg_state *ptr_reg, const struct bpf_reg_state *off_reg, struct bpf_reg_state *dst_reg, struct bpf_sanitize_info *info, const bool commit_window);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:7777
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff812825a0-ffffffff812829c3: sanitize_ptr_alu (STB_LOCAL)
ffffffff81e693fc-ffffffff81e694f7: sanitize_ptr_alu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int sanitize_ptr_alu(struct bpf_verifier_env *env, struct bpf_insn *insn, const struct bpf_reg_state *ptr_reg, const struct bpf_reg_state *off_reg, struct bpf_reg_state *dst_reg, struct bpf_sanitize_info *info, const bool commit_window);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:9713
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff812da0c0-ffffffff812da4e6: sanitize_ptr_alu (STB_LOCAL)
ffffffff820601fc-ffffffff820602f7: sanitize_ptr_alu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int sanitize_ptr_alu(struct bpf_verifier_env *env, struct bpf_insn *insn, const struct bpf_reg_state *ptr_reg, const struct bpf_reg_state *off_reg, struct bpf_reg_state *dst_reg, struct bpf_sanitize_info *info, const bool commit_window);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:11629
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff81302c10-ffffffff81303032: sanitize_ptr_alu (STB_LOCAL)
ffffffff820df239-ffffffff820df334: sanitize_ptr_alu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int sanitize_ptr_alu(struct bpf_verifier_env *env, struct bpf_insn *insn, const struct bpf_reg_state *ptr_reg, const struct bpf_reg_state *off_reg, struct bpf_reg_state *dst_reg, struct bpf_sanitize_info *info, const bool commit_window);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:12563
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff81320cb0-ffffffff813210d2: sanitize_ptr_alu (STB_LOCAL)
ffffffff821bb1da-ffffffff821bb2d5: sanitize_ptr_alu.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffff80001026b158)
Location: kernel/bpf/verifier.c:4269
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffff80001026b158-ffff80001026b3a0: sanitize_ptr_alu.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sanitize_ptr_alu(struct bpf_verifier_env *env, struct bpf_insn *insn, const struct bpf_reg_state *ptr_reg, struct bpf_reg_state *dst_reg, bool off_is_neg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c049d254)
Location: kernel/bpf/verifier.c:4269
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
c049d254-c049d424: sanitize_ptr_alu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (c0000000003110f0)
Location: kernel/bpf/verifier.c:4269
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
c0000000003110f0-c00000000031135c: sanitize_ptr_alu.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a57f0)
Location: kernel/bpf/verifier.c:4269
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffe0001a57f0-ffffffe0001a5992: sanitize_ptr_alu.isra.0 (STB_LOCAL)
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
int sanitize_ptr_alu(struct bpf_verifier_env *env, struct bpf_insn *insn, const struct bpf_reg_state *ptr_reg, struct bpf_reg_state *dst_reg, bool off_is_neg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dfda0)
Location: kernel/bpf/verifier.c:4269
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff811dfda0-ffffffff811e000c: sanitize_ptr_alu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sanitize_ptr_alu(struct bpf_verifier_env *env, struct bpf_insn *insn, const struct bpf_reg_state *ptr_reg, struct bpf_reg_state *dst_reg, bool off_is_neg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d2b60)
Location: kernel/bpf/verifier.c:4269
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff811d2b60-ffffffff811d2dcc: sanitize_ptr_alu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sanitize_ptr_alu(struct bpf_verifier_env *env, struct bpf_insn *insn, const struct bpf_reg_state *ptr_reg, struct bpf_reg_state *dst_reg, bool off_is_neg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ddb70)
Location: kernel/bpf/verifier.c:4269
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff811ddb70-ffffffff811ddddc: sanitize_ptr_alu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sanitize_ptr_alu(struct bpf_verifier_env *env, struct bpf_insn *insn, const struct bpf_reg_state *ptr_reg, struct bpf_reg_state *dst_reg, bool off_is_neg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ebf80)
Location: kernel/bpf/verifier.c:4269
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff811ebf80-ffffffff811ec1ec: sanitize_ptr_alu (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
