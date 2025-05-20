# Function: <code>adjust_ptr_min_max_vals</code>

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
int adjust_ptr_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn, const struct bpf_reg_state *ptr_reg, const struct bpf_reg_state *off_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811a2080)
Location: kernel/bpf/verifier.c:1892
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff811a2080-ffffffff811a26db: adjust_ptr_min_max_vals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int adjust_ptr_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn, const struct bpf_reg_state *ptr_reg, const struct bpf_reg_state *off_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811b8660)
Location: kernel/bpf/verifier.c:2659
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff811b8660-ffffffff811b8d0a: adjust_ptr_min_max_vals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int adjust_ptr_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn, const struct bpf_reg_state *ptr_reg, const struct bpf_reg_state *off_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811c7ef0)
Location: kernel/bpf/verifier.c:3200
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff811c7ef0-ffffffff811c8753: adjust_ptr_min_max_vals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int adjust_ptr_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn, const struct bpf_reg_state *ptr_reg, const struct bpf_reg_state *off_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811db660)
Location: kernel/bpf/verifier.c:4323
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff811db660-ffffffff811dbef5: adjust_ptr_min_max_vals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int adjust_ptr_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn, const struct bpf_reg_state *ptr_reg, const struct bpf_reg_state *off_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e7db0)
Location: kernel/bpf/verifier.c:4326
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff811e7db0-ffffffff811e864b: adjust_ptr_min_max_vals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int adjust_ptr_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn, const struct bpf_reg_state *ptr_reg, const struct bpf_reg_state *off_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120d880)
Location: kernel/bpf/verifier.c:5003
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff8120d880-ffffffff8120e14b: adjust_ptr_min_max_vals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int adjust_ptr_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn, const struct bpf_reg_state *ptr_reg, const struct bpf_reg_state *off_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120e050)
Location: kernel/bpf/verifier.c:5518
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff8120e050-ffffffff8120e946: adjust_ptr_min_max_vals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int adjust_ptr_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn, const struct bpf_reg_state *ptr_reg, const struct bpf_reg_state *off_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120aaa0)
Location: kernel/bpf/verifier.c:6708
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff8120aaa0-ffffffff8120b359: adjust_ptr_min_max_vals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int adjust_ptr_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn, const struct bpf_reg_state *ptr_reg, const struct bpf_reg_state *off_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:6997
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff8123e700-ffffffff8123f044: adjust_ptr_min_max_vals (STB_LOCAL)
ffffffff81cb8428-ffffffff81cb8444: adjust_ptr_min_max_vals.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int adjust_ptr_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn, const struct bpf_reg_state *ptr_reg, const struct bpf_reg_state *off_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:7996
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff812839b0-ffffffff81284258: adjust_ptr_min_max_vals (STB_LOCAL)
ffffffff81e69619-ffffffff81e69635: adjust_ptr_min_max_vals.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int adjust_ptr_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn, const struct bpf_reg_state *ptr_reg, const struct bpf_reg_state *off_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:9932
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff812db500-ffffffff812dbdf6: adjust_ptr_min_max_vals (STB_LOCAL)
ffffffff82060419-ffffffff8206043b: adjust_ptr_min_max_vals.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int adjust_ptr_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn, const struct bpf_reg_state *ptr_reg, const struct bpf_reg_state *off_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:11848
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff81309a00-ffffffff8130a2ac: adjust_ptr_min_max_vals (STB_LOCAL)
ffffffff820df7e9-ffffffff820df80b: adjust_ptr_min_max_vals.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int adjust_ptr_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn, const struct bpf_reg_state *ptr_reg, const struct bpf_reg_state *off_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:12782
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff8132dd70-ffffffff8132e62e: adjust_ptr_min_max_vals (STB_LOCAL)
ffffffff821bc25e-ffffffff821bc280: adjust_ptr_min_max_vals.cold (STB_LOCAL)
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
int adjust_ptr_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn, const struct bpf_reg_state *ptr_reg, const struct bpf_reg_state *off_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff80001026b878)
Location: kernel/bpf/verifier.c:4326
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffff80001026b878-ffff80001026bfec: adjust_ptr_min_max_vals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int adjust_ptr_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn, const struct bpf_reg_state *ptr_reg, const struct bpf_reg_state *off_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c049d8e4)
Location: kernel/bpf/verifier.c:4326
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:check_alu_op
```
**Symbols:**

```
c049d8e4-c049e344: adjust_ptr_min_max_vals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int adjust_ptr_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn, const struct bpf_reg_state *ptr_reg, const struct bpf_reg_state *off_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c000000000311920)
Location: kernel/bpf/verifier.c:4326
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
c000000000311920-c000000000312248: adjust_ptr_min_max_vals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int adjust_ptr_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn, const struct bpf_reg_state *ptr_reg, const struct bpf_reg_state *off_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a5d7c)
Location: kernel/bpf/verifier.c:4326
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffe0001a5d7c-ffffffe0001a63f6: adjust_ptr_min_max_vals (STB_LOCAL)
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
int adjust_ptr_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn, const struct bpf_reg_state *ptr_reg, const struct bpf_reg_state *off_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e03d0)
Location: kernel/bpf/verifier.c:4326
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff811e03d0-ffffffff811e0c6b: adjust_ptr_min_max_vals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int adjust_ptr_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn, const struct bpf_reg_state *ptr_reg, const struct bpf_reg_state *off_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d3190)
Location: kernel/bpf/verifier.c:4326
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff811d3190-ffffffff811d3a2b: adjust_ptr_min_max_vals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int adjust_ptr_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn, const struct bpf_reg_state *ptr_reg, const struct bpf_reg_state *off_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811de1a0)
Location: kernel/bpf/verifier.c:4326
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff811de1a0-ffffffff811dea3b: adjust_ptr_min_max_vals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int adjust_ptr_min_max_vals(struct bpf_verifier_env *env, struct bpf_insn *insn, const struct bpf_reg_state *ptr_reg, const struct bpf_reg_state *off_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ec5b0)
Location: kernel/bpf/verifier.c:4326
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff811ec5b0-ffffffff811ece4b: adjust_ptr_min_max_vals (STB_LOCAL)
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
