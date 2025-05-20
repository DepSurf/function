# Function: <code>push_stack</code>

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
In kernel/bpf/verifier.c (ffffffff811756f1)
Location: kernel/bpf/verifier.c:441
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
In kernel/bpf/verifier.c (ffffffff811839ca)
Location: kernel/bpf/verifier.c:447
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
In kernel/bpf/verifier.c (ffffffff811909d9)
Location: kernel/bpf/verifier.c:416
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
In kernel/bpf/verifier.c (ffffffff8119713d)
Location: kernel/bpf/verifier.c:435
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
In kernel/bpf/verifier.c (ffffffff811a4de1)
Location: kernel/bpf/verifier.c:394
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
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
In kernel/bpf/verifier.c (ffffffff811bb826)
Location: kernel/bpf/verifier.c:512
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct bpf_verifier_state *push_stack(struct bpf_verifier_env *env, int insn_idx, int prev_insn_idx, bool speculative);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811c7870)
Location: kernel/bpf/verifier.c:757
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:sanitize_ptr_alu
  - kernel/bpf/verifier.c:sanitize_ptr_alu
```
**Symbols:**

```
ffffffff811c7870-ffffffff811c793d: push_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct bpf_verifier_state *push_stack(struct bpf_verifier_env *env, int insn_idx, int prev_insn_idx, bool speculative);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811daf50)
Location: kernel/bpf/verifier.c:803
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:sanitize_ptr_alu
  - kernel/bpf/verifier.c:sanitize_ptr_alu
```
**Symbols:**

```
ffffffff811daf50-ffffffff811db030: push_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct bpf_verifier_state *push_stack(struct bpf_verifier_env *env, int insn_idx, int prev_insn_idx, bool speculative);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e76a0)
Location: kernel/bpf/verifier.c:803
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:sanitize_ptr_alu
  - kernel/bpf/verifier.c:sanitize_ptr_alu
```
**Symbols:**

```
ffffffff811e76a0-ffffffff811e7780: push_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct bpf_verifier_state *push_stack(struct bpf_verifier_env *env, int insn_idx, int prev_insn_idx, bool speculative);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81207360)
Location: kernel/bpf/verifier.c:932
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff81207360-ffffffff8120748d: push_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bpf_verifier_state *push_stack(struct bpf_verifier_env *env, int insn_idx, int prev_insn_idx, bool speculative);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81207c20)
Location: kernel/bpf/verifier.c:958
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff81207c20-ffffffff81207d4d: push_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bpf_verifier_state *push_stack(struct bpf_verifier_env *env, int insn_idx, int prev_insn_idx, bool speculative);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81209380)
Location: kernel/bpf/verifier.c:1007
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:sanitize_speculative_path
```
**Symbols:**

```
ffffffff81209380-ffffffff812094a7: push_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct bpf_verifier_state *push_stack(struct bpf_verifier_env *env, int insn_idx, int prev_insn_idx, bool speculative);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:1016
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:sanitize_speculative_path
```
**Symbols:**

```
ffffffff8123d030-ffffffff8123d138: push_stack (STB_LOCAL)
ffffffff81cb81c8-ffffffff81cb81dd: push_stack.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct bpf_verifier_state *push_stack(struct bpf_verifier_env *env, int insn_idx, int prev_insn_idx, bool speculative);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:1243
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:sanitize_speculative_path
```
**Symbols:**

```
ffffffff812823b0-ffffffff812824c4: push_stack (STB_LOCAL)
ffffffff81e693e7-ffffffff81e693fc: push_stack.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct bpf_verifier_state *push_stack(struct bpf_verifier_env *env, int insn_idx, int prev_insn_idx, bool speculative);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:1447
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:sanitize_speculative_path
```
**Symbols:**

```
ffffffff812d9eb0-ffffffff812d9fca: push_stack (STB_LOCAL)
ffffffff820601e7-ffffffff820601fc: push_stack.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct bpf_verifier_state *push_stack(struct bpf_verifier_env *env, int insn_idx, int prev_insn_idx, bool speculative);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:1824
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:sanitize_speculative_path
  - kernel/bpf/verifier.c:check_kfunc_call
```
**Symbols:**

```
ffffffff813029c0-ffffffff81302b15: push_stack (STB_LOCAL)
ffffffff820df224-ffffffff820df239: push_stack.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct bpf_verifier_state *push_stack(struct bpf_verifier_env *env, int insn_idx, int prev_insn_idx, bool speculative);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:1674
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:sanitize_speculative_path
  - kernel/bpf/verifier.c:push_callback_call
```
**Symbols:**

```
ffffffff81320a30-ffffffff81320bb4: push_stack (STB_LOCAL)
ffffffff821bb1c5-ffffffff821bb1da: push_stack.cold (STB_LOCAL)
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
struct bpf_verifier_state *push_stack(struct bpf_verifier_env *env, int insn_idx, int prev_insn_idx, bool speculative);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff80001026b048)
Location: kernel/bpf/verifier.c:803
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffff80001026b048-ffff80001026b158: push_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct bpf_verifier_state *push_stack(struct bpf_verifier_env *env, int insn_idx, int prev_insn_idx, bool speculative);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c049d15c)
Location: kernel/bpf/verifier.c:803
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:sanitize_ptr_alu
  - kernel/bpf/verifier.c:sanitize_ptr_alu
```
**Symbols:**

```
c049d15c-c049d254: push_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct bpf_verifier_state *push_stack(struct bpf_verifier_env *env, int insn_idx, int prev_insn_idx, bool speculative);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c000000000310f70)
Location: kernel/bpf/verifier.c:803
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
c000000000310f70-c0000000003110e8: push_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct bpf_verifier_state *push_stack(struct bpf_verifier_env *env, int insn_idx, int prev_insn_idx, bool speculative);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a571a)
Location: kernel/bpf/verifier.c:803
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffe0001a571a-ffffffe0001a57f0: push_stack (STB_LOCAL)
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
struct bpf_verifier_state *push_stack(struct bpf_verifier_env *env, int insn_idx, int prev_insn_idx, bool speculative);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dfcc0)
Location: kernel/bpf/verifier.c:803
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:sanitize_ptr_alu
  - kernel/bpf/verifier.c:sanitize_ptr_alu
```
**Symbols:**

```
ffffffff811dfcc0-ffffffff811dfda0: push_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct bpf_verifier_state *push_stack(struct bpf_verifier_env *env, int insn_idx, int prev_insn_idx, bool speculative);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d2a80)
Location: kernel/bpf/verifier.c:803
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:sanitize_ptr_alu
  - kernel/bpf/verifier.c:sanitize_ptr_alu
```
**Symbols:**

```
ffffffff811d2a80-ffffffff811d2b60: push_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct bpf_verifier_state *push_stack(struct bpf_verifier_env *env, int insn_idx, int prev_insn_idx, bool speculative);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dda90)
Location: kernel/bpf/verifier.c:803
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:sanitize_ptr_alu
  - kernel/bpf/verifier.c:sanitize_ptr_alu
```
**Symbols:**

```
ffffffff811dda90-ffffffff811ddb70: push_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct bpf_verifier_state *push_stack(struct bpf_verifier_env *env, int insn_idx, int prev_insn_idx, bool speculative);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ebea0)
Location: kernel/bpf/verifier.c:803
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:sanitize_ptr_alu
  - kernel/bpf/verifier.c:sanitize_ptr_alu
```
**Symbols:**

```
ffffffff811ebea0-ffffffff811ebf80: push_stack (STB_LOCAL)
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
