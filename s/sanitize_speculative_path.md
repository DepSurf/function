# Function: <code>sanitize_speculative_path</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bpf_verifier_state *sanitize_speculative_path(struct bpf_verifier_env *env, const struct bpf_insn *insn, u32 next_idx, u32 curr_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812094b0)
Location: kernel/bpf/verifier.c:6469
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff812094b0-ffffffff81209527: sanitize_speculative_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct bpf_verifier_state *sanitize_speculative_path(struct bpf_verifier_env *env, const struct bpf_insn *insn, u32 next_idx, u32 curr_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8123d140)
Location: kernel/bpf/verifier.c:6758
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:sanitize_ptr_alu
  - kernel/bpf/verifier.c:sanitize_ptr_alu
```
**Symbols:**

```
ffffffff8123d140-ffffffff8123d1e2: sanitize_speculative_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct bpf_verifier_state *sanitize_speculative_path(struct bpf_verifier_env *env, const struct bpf_insn *insn, u32 next_idx, u32 curr_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812824d0)
Location: kernel/bpf/verifier.c:7757
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:sanitize_ptr_alu
  - kernel/bpf/verifier.c:sanitize_ptr_alu
```
**Symbols:**

```
ffffffff812824d0-ffffffff81282591: sanitize_speculative_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bpf_verifier_state *sanitize_speculative_path(struct bpf_verifier_env *env, const struct bpf_insn *insn, u32 next_idx, u32 curr_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812d9fe0)
Location: kernel/bpf/verifier.c:9693
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:sanitize_ptr_alu
  - kernel/bpf/verifier.c:sanitize_ptr_alu
```
**Symbols:**

```
ffffffff812d9fe0-ffffffff812da0a1: sanitize_speculative_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bpf_verifier_state *sanitize_speculative_path(struct bpf_verifier_env *env, const struct bpf_insn *insn, u32 next_idx, u32 curr_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81302b30)
Location: kernel/bpf/verifier.c:11609
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:sanitize_ptr_alu
  - kernel/bpf/verifier.c:sanitize_ptr_alu
```
**Symbols:**

```
ffffffff81302b30-ffffffff81302bf1: sanitize_speculative_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bpf_verifier_state *sanitize_speculative_path(struct bpf_verifier_env *env, const struct bpf_insn *insn, u32 next_idx, u32 curr_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81320bd0)
Location: kernel/bpf/verifier.c:12543
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:sanitize_ptr_alu
  - kernel/bpf/verifier.c:sanitize_ptr_alu
```
**Symbols:**

```
ffffffff81320bd0-ffffffff81320c91: sanitize_speculative_path (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
