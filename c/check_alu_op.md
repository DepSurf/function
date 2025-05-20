# Function: <code>check_alu_op</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81174a0a)
Location: kernel/bpf/verifier.c:1004
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81183075)
Location: kernel/bpf/verifier.c:1437
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8118fb8b)
Location: kernel/bpf/verifier.c:1630
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
In kernel/bpf/verifier.c (ffffffff81196225)
Location: kernel/bpf/verifier.c:1965
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811a686f)
Location: kernel/bpf/verifier.c:2396
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
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
In kernel/bpf/verifier.c (ffffffff811bca16)
Location: kernel/bpf/verifier.c:3183
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
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
In kernel/bpf/verifier.c (ffffffff811cdfd0)
Location: kernel/bpf/verifier.c:3783
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int check_alu_op(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dd7e0)
Location: kernel/bpf/verifier.c:4918
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811dd7e0-ffffffff811ddd7f: check_alu_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int check_alu_op(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e9fa0)
Location: kernel/bpf/verifier.c:4928
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811e9fa0-ffffffff811ea53f: check_alu_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int check_alu_op(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120e400)
Location: kernel/bpf/verifier.c:5999
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff8120e400-ffffffff8120ea2d: check_alu_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int check_alu_op(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120ec10)
Location: kernel/bpf/verifier.c:6592
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff8120ec10-ffffffff8120f274: check_alu_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int check_alu_op(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120b780)
Location: kernel/bpf/verifier.c:7755
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff8120b780-ffffffff8120be00: check_alu_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int check_alu_op(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:8044
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff8123f4f0-ffffffff8123fc7b: check_alu_op (STB_LOCAL)
ffffffff81cb8465-ffffffff81cb84bc: check_alu_op.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int check_alu_op(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:9035
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff81284680-ffffffff81284d43: check_alu_op (STB_LOCAL)
ffffffff81e69656-ffffffff81e696ab: check_alu_op.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int check_alu_op(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:10976
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff812e1200-ffffffff812e18df: check_alu_op (STB_LOCAL)
ffffffff820608fb-ffffffff82060950: check_alu_op.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int check_alu_op(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:12892
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff81311200-ffffffff813119cd: check_alu_op (STB_LOCAL)
ffffffff820e0132-ffffffff820e0192: check_alu_op.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int check_alu_op(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:13830
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff81337990-ffffffff813387f2: check_alu_op (STB_LOCAL)
ffffffff821bc7a6-ffffffff821bc92e: check_alu_op.cold (STB_LOCAL)
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
int check_alu_op(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff80001026d7a0)
Location: kernel/bpf/verifier.c:4928
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffff80001026d7a0-ffff80001026dc9c: check_alu_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int check_alu_op(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c049fd8c)
Location: kernel/bpf/verifier.c:4928
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
c049fd8c-c04a0428: check_alu_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int check_alu_op(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c0000000003141c0)
Location: kernel/bpf/verifier.c:4928
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
c0000000003141c0-c000000000314730: check_alu_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int check_alu_op(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a77d6)
Location: kernel/bpf/verifier.c:4928
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffe0001a77d6-ffffffe0001a7c3e: check_alu_op (STB_LOCAL)
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
int check_alu_op(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e25c0)
Location: kernel/bpf/verifier.c:4928
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811e25c0-ffffffff811e2b5f: check_alu_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int check_alu_op(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d5380)
Location: kernel/bpf/verifier.c:4928
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811d5380-ffffffff811d591f: check_alu_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int check_alu_op(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e0390)
Location: kernel/bpf/verifier.c:4928
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811e0390-ffffffff811e092f: check_alu_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int check_alu_op(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ee7a0)
Location: kernel/bpf/verifier.c:4928
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811ee7a0-ffffffff811eed3f: check_alu_op (STB_LOCAL)
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
