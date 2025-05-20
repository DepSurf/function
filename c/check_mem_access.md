# Function: <code>check_mem_access</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int check_mem_access(struct verifier_env *env, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81173fd0)
Location: kernel/bpf/verifier.c:681
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff81173fd0-ffffffff811744d0: check_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int check_mem_access(struct verifier_env *env, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81182350)
Location: kernel/bpf/verifier.c:758
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff81182350-ffffffff81182ad3: check_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int check_mem_access(struct bpf_verifier_env *env, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8118ebf0)
Location: kernel/bpf/verifier.c:751
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff8118ebf0-ffffffff8118f4fa: check_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int check_mem_access(struct bpf_verifier_env *env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81194e50)
Location: kernel/bpf/verifier.c:878
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff81194e50-ffffffff811956a0: check_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int check_mem_access(struct bpf_verifier_env *env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811a5800)
Location: kernel/bpf/verifier.c:1118
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811a5800-ffffffff811a61a5: check_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int check_mem_access(struct bpf_verifier_env *env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811b9a40)
Location: kernel/bpf/verifier.c:1673
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff811b9a40-ffffffff811ba6c2: check_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int check_mem_access(struct bpf_verifier_env *env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811c93f0)
Location: kernel/bpf/verifier.c:1932
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff811c93f0-ffffffff811ca212: check_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int check_mem_access(struct bpf_verifier_env *env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e0ba0)
Location: kernel/bpf/verifier.c:2748
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff811e0ba0-ffffffff811e1b5a: check_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int check_mem_access(struct bpf_verifier_env *env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ed3a0)
Location: kernel/bpf/verifier.c:2749
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff811ed3a0-ffffffff811ee35a: check_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int check_mem_access(struct bpf_verifier_env *env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81210260)
Location: kernel/bpf/verifier.c:3203
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_xadd
  - kernel/bpf/verifier.c:check_xadd
```
**Symbols:**

```
ffffffff81210260-ffffffff81210d65: check_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int check_mem_access(struct bpf_verifier_env *env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81210f10)
Location: kernel/bpf/verifier.c:3410
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_xadd
  - kernel/bpf/verifier.c:check_xadd
```
**Symbols:**

```
ffffffff81210f10-ffffffff81211a88: check_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int check_mem_access(struct bpf_verifier_env *env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81212b60)
Location: kernel/bpf/verifier.c:4038
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_atomic
  - kernel/bpf/verifier.c:check_atomic
```
**Symbols:**

```
ffffffff81212b60-ffffffff8121394e: check_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int check_mem_access(struct bpf_verifier_env *env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:4139
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_atomic
  - kernel/bpf/verifier.c:check_atomic
  - kernel/bpf/verifier.c:check_atomic
```
**Symbols:**

```
ffffffff81248460-ffffffff8124972d: check_mem_access (STB_LOCAL)
ffffffff81cb8c24-ffffffff81cb8d79: check_mem_access.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int check_mem_access(struct bpf_verifier_env *env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:4688
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_atomic
  - kernel/bpf/verifier.c:check_atomic
  - kernel/bpf/verifier.c:check_atomic
```
**Symbols:**

```
ffffffff8128e610-ffffffff8128faea: check_mem_access (STB_LOCAL)
ffffffff81e69f35-ffffffff81e6a06f: check_mem_access.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int check_mem_access(struct bpf_verifier_env *env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:5194
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_atomic
  - kernel/bpf/verifier.c:check_atomic
  - kernel/bpf/verifier.c:check_atomic
```
**Symbols:**

```
ffffffff812e6e20-ffffffff812e82f5: check_mem_access (STB_LOCAL)
ffffffff82060d7f-ffffffff82060eb9: check_mem_access.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int check_mem_access(struct bpf_verifier_env *env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:6274
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:process_dynptr_func
  - kernel/bpf/verifier.c:process_dynptr_func
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_atomic
  - kernel/bpf/verifier.c:check_atomic
  - kernel/bpf/verifier.c:check_atomic
```
**Symbols:**

```
ffffffff81312180-ffffffff813136a9: check_mem_access (STB_LOCAL)
ffffffff820e0192-ffffffff820e02da: check_mem_access.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int check_mem_access(struct bpf_verifier_env *env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once, bool is_ldsx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:6648
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:process_dynptr_func
  - kernel/bpf/verifier.c:process_dynptr_func
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_atomic
  - kernel/bpf/verifier.c:check_atomic
  - kernel/bpf/verifier.c:check_atomic
```
**Symbols:**

```
ffffffff81332090-ffffffff8133353e: check_mem_access (STB_LOCAL)
ffffffff821bc4a0-ffffffff821bc5e8: check_mem_access.cold (STB_LOCAL)
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
int check_mem_access(struct bpf_verifier_env *env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff800010271248)
Location: kernel/bpf/verifier.c:2749
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffff800010271248-ffff800010271d30: check_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int check_mem_access(struct bpf_verifier_env *env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c04a3514)
Location: kernel/bpf/verifier.c:2749
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
c04a3514-c04a4090: check_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int check_mem_access(struct bpf_verifier_env *env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c0000000003185f0)
Location: kernel/bpf/verifier.c:2749
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
c0000000003185f0-c00000000031922c: check_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int check_mem_access(struct bpf_verifier_env *env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001aa68a)
Location: kernel/bpf/verifier.c:2749
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffe0001aa68a-ffffffe0001aaf4c: check_mem_access (STB_LOCAL)
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
int check_mem_access(struct bpf_verifier_env *env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e59c0)
Location: kernel/bpf/verifier.c:2749
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff811e59c0-ffffffff811e697a: check_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int check_mem_access(struct bpf_verifier_env *env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d8780)
Location: kernel/bpf/verifier.c:2749
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff811d8780-ffffffff811d973a: check_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int check_mem_access(struct bpf_verifier_env *env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e3790)
Location: kernel/bpf/verifier.c:2749
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff811e3790-ffffffff811e474a: check_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int check_mem_access(struct bpf_verifier_env *env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811f1b60)
Location: kernel/bpf/verifier.c:2749
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff811f1b60-ffffffff811f2b1a: check_mem_access (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int insn_idx</code>
</li>
<li>
<b>Param reordered. </b>
<code>env, regno, off, bpf_size, t, value_regno</code> ➡️ <code>env, insn_idx, regno, off, bpf_size, t, value_regno</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool strict_alignment_once</code>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool is_ldsx</code>
</li>
</ul>
</details>
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
