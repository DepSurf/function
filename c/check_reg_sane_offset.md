# Function: <code>check_reg_sane_offset</code>

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
bool check_reg_sane_offset(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, enum bpf_reg_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811a15b0)
Location: kernel/bpf/verifier.c:1852
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff811a15b0-ffffffff811a1678: check_reg_sane_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool check_reg_sane_offset(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, enum bpf_reg_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811b8590)
Location: kernel/bpf/verifier.c:2619
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff811b8590-ffffffff811b8658: check_reg_sane_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool check_reg_sane_offset(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, enum bpf_reg_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811c7b80)
Location: kernel/bpf/verifier.c:3041
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff811c7b80-ffffffff811c7c48: check_reg_sane_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool check_reg_sane_offset(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, enum bpf_reg_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811db2a0)
Location: kernel/bpf/verifier.c:4161
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff811db2a0-ffffffff811db368: check_reg_sane_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool check_reg_sane_offset(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, enum bpf_reg_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e79f0)
Location: kernel/bpf/verifier.c:4164
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff811e79f0-ffffffff811e7ab8: check_reg_sane_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool check_reg_sane_offset(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, enum bpf_reg_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81207730)
Location: kernel/bpf/verifier.c:4841
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff81207730-ffffffff812077f8: check_reg_sane_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool check_reg_sane_offset(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, enum bpf_reg_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81208020)
Location: kernel/bpf/verifier.c:5347
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff81208020-ffffffff812080e8: check_reg_sane_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool check_reg_sane_offset(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, enum bpf_reg_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81209180)
Location: kernel/bpf/verifier.c:6345
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff81209180-ffffffff81209248: check_reg_sane_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool check_reg_sane_offset(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, enum bpf_reg_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8123cd60)
Location: kernel/bpf/verifier.c:6634
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff8123cd60-ffffffff8123cee0: check_reg_sane_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool check_reg_sane_offset(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, enum bpf_reg_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81282130)
Location: kernel/bpf/verifier.c:7633
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff81282130-ffffffff81282247: check_reg_sane_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool check_reg_sane_offset(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, enum bpf_reg_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812d9c10)
Location: kernel/bpf/verifier.c:9574
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff812d9c10-ffffffff812d9d27: check_reg_sane_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool check_reg_sane_offset(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, enum bpf_reg_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812f7410)
Location: kernel/bpf/verifier.c:11490
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff812f7410-ffffffff812f7527: check_reg_sane_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool check_reg_sane_offset(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, enum bpf_reg_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81316930)
Location: kernel/bpf/verifier.c:12424
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff81316930-ffffffff81316a47: check_reg_sane_offset (STB_LOCAL)
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
bool check_reg_sane_offset(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, enum bpf_reg_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff80001026b3a0)
Location: kernel/bpf/verifier.c:4164
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffff80001026b3a0-ffff80001026b4e8: check_reg_sane_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool check_reg_sane_offset(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, enum bpf_reg_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c049d424)
Location: kernel/bpf/verifier.c:4164
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
c049d424-c049d560: check_reg_sane_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool check_reg_sane_offset(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, enum bpf_reg_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c000000000311360)
Location: kernel/bpf/verifier.c:4164
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
c000000000311360-c0000000003114f8: check_reg_sane_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool check_reg_sane_offset(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, enum bpf_reg_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a5992)
Location: kernel/bpf/verifier.c:4164
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffe0001a5992-ffffffe0001a5ace: check_reg_sane_offset (STB_LOCAL)
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
bool check_reg_sane_offset(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, enum bpf_reg_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e0010)
Location: kernel/bpf/verifier.c:4164
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff811e0010-ffffffff811e00d8: check_reg_sane_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool check_reg_sane_offset(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, enum bpf_reg_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d2dd0)
Location: kernel/bpf/verifier.c:4164
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff811d2dd0-ffffffff811d2e98: check_reg_sane_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool check_reg_sane_offset(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, enum bpf_reg_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ddde0)
Location: kernel/bpf/verifier.c:4164
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff811ddde0-ffffffff811ddea8: check_reg_sane_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool check_reg_sane_offset(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, enum bpf_reg_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ec1f0)
Location: kernel/bpf/verifier.c:4164
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff811ec1f0-ffffffff811ec2b8: check_reg_sane_offset (STB_LOCAL)
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
