# Function: <code>pop_stack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pop_stack(struct verifier_env *env, int *prev_insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81173990)
Location: kernel/bpf/verifier.c:422
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff81173990-ffffffff81173a2a: pop_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pop_stack(struct verifier_env *env, int *prev_insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81181bd0)
Location: kernel/bpf/verifier.c:428
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff81181bd0-ffffffff81181c66: pop_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pop_stack(struct bpf_verifier_env *env, int *prev_insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8118e020)
Location: kernel/bpf/verifier.c:397
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_analyzer
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff8118e020-ffffffff8118e0b6: pop_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pop_stack(struct bpf_verifier_env *env, int *prev_insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81194200)
Location: kernel/bpf/verifier.c:416
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_analyzer
  - kernel/bpf/verifier.c:bpf_analyzer
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff81194200-ffffffff81194296: pop_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pop_stack(struct bpf_verifier_env *env, int *prev_insn_idx, int *insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811a4ca0)
Location: kernel/bpf/verifier.c:367
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff811a4ca0-ffffffff811a4d32: pop_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pop_stack(struct bpf_verifier_env *env, int *prev_insn_idx, int *insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811b7840)
Location: kernel/bpf/verifier.c:485
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff811b7840-ffffffff811b78c6: pop_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pop_stack(struct bpf_verifier_env *env, int *prev_insn_idx, int *insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811c6e10)
Location: kernel/bpf/verifier.c:730
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811c6e10-ffffffff811c6e96: pop_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pop_stack(struct bpf_verifier_env *env, int *prev_insn_idx, int *insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d90b0)
Location: kernel/bpf/verifier.c:776
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:push_stack
```
**Symbols:**

```
ffffffff811d90b0-ffffffff811d9136: pop_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pop_stack(struct bpf_verifier_env *env, int *prev_insn_idx, int *insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e57a0)
Location: kernel/bpf/verifier.c:776
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:push_stack
```
**Symbols:**

```
ffffffff811e57a0-ffffffff811e5826: pop_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int pop_stack(struct bpf_verifier_env *env, int *prev_insn_idx, int *insn_idx, bool pop_log);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120742d)
Location: kernel/bpf/verifier.c:903
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:push_stack
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff81204d80-ffffffff81204e7e: pop_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int pop_stack(struct bpf_verifier_env *env, int *prev_insn_idx, int *insn_idx, bool pop_log);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81207ced)
Location: kernel/bpf/verifier.c:929
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:push_stack
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff81204d40-ffffffff81204e4a: pop_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int pop_stack(struct bpf_verifier_env *env, int *prev_insn_idx, int *insn_idx, bool pop_log);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120944d)
Location: kernel/bpf/verifier.c:978
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:push_stack
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff81204c40-ffffffff81204d4a: pop_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pop_stack(struct bpf_verifier_env *env, int *prev_insn_idx, int *insn_idx, bool pop_log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81236ce0)
Location: kernel/bpf/verifier.c:987
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:push_stack
```
**Symbols:**

```
ffffffff81236ce0-ffffffff81236dea: pop_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pop_stack(struct bpf_verifier_env *env, int *prev_insn_idx, int *insn_idx, bool pop_log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8127afc0)
Location: kernel/bpf/verifier.c:1214
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:push_stack
```
**Symbols:**

```
ffffffff8127afc0-ffffffff8127b0d6: pop_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pop_stack(struct bpf_verifier_env *env, int *prev_insn_idx, int *insn_idx, bool pop_log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812d1ac0)
Location: kernel/bpf/verifier.c:1418
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:push_stack
```
**Symbols:**

```
ffffffff812d1ac0-ffffffff812d1bd3: pop_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int pop_stack(struct bpf_verifier_env *env, int *prev_insn_idx, int *insn_idx, bool pop_log);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81302ac8)
Location: kernel/bpf/verifier.c:1795
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:push_stack
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:__check_func_call
```
**Symbols:**

```
ffffffff812feed0-ffffffff812fef8e: pop_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int pop_stack(struct bpf_verifier_env *env, int *prev_insn_idx, int *insn_idx, bool pop_log);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81320b67)
Location: kernel/bpf/verifier.c:1645
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:push_stack
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:push_callback_call
```
**Symbols:**

```
ffffffff8131e620-ffffffff8131e6de: pop_stack (STB_LOCAL)
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
int pop_stack(struct bpf_verifier_env *env, int *prev_insn_idx, int *insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff800010268928)
Location: kernel/bpf/verifier.c:776
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:push_stack
```
**Symbols:**

```
ffff800010268928-ffff8000102689c4: pop_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pop_stack(struct bpf_verifier_env *env, int *prev_insn_idx, int *insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c049ad88)
Location: kernel/bpf/verifier.c:776
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:push_stack
```
**Symbols:**

```
c049ad88-c049ae20: pop_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pop_stack(struct bpf_verifier_env *env, int *prev_insn_idx, int *insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c00000000030e670)
Location: kernel/bpf/verifier.c:776
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:push_stack
```
**Symbols:**

```
c00000000030e670-c00000000030e748: pop_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pop_stack(struct bpf_verifier_env *env, int *prev_insn_idx, int *insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a3aea)
Location: kernel/bpf/verifier.c:776
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:push_stack
```
**Symbols:**

```
ffffffe0001a3aea-ffffffe0001a3b74: pop_stack (STB_LOCAL)
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
int pop_stack(struct bpf_verifier_env *env, int *prev_insn_idx, int *insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dddc0)
Location: kernel/bpf/verifier.c:776
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:push_stack
```
**Symbols:**

```
ffffffff811dddc0-ffffffff811dde46: pop_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pop_stack(struct bpf_verifier_env *env, int *prev_insn_idx, int *insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d0b80)
Location: kernel/bpf/verifier.c:776
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:push_stack
```
**Symbols:**

```
ffffffff811d0b80-ffffffff811d0c06: pop_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pop_stack(struct bpf_verifier_env *env, int *prev_insn_idx, int *insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dbb90)
Location: kernel/bpf/verifier.c:776
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:push_stack
```
**Symbols:**

```
ffffffff811dbb90-ffffffff811dbc16: pop_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pop_stack(struct bpf_verifier_env *env, int *prev_insn_idx, int *insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e9fa0)
Location: kernel/bpf/verifier.c:776
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:push_stack
```
**Symbols:**

```
ffffffff811e9fa0-ffffffff811ea026: pop_stack (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct verifier_env *env</code> ➡️ <code>struct bpf_verifier_env *env</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int *insn_idx</code>
</li>
</ul>
</details>
</li>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool pop_log</code>
</li>
</ul>
</details>
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
