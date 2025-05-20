# Function: <code>sanitize_err</code>

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
int sanitize_err(struct bpf_verifier_env *env, const struct bpf_insn *insn, int reason, const struct bpf_reg_state *off_reg, const struct bpf_reg_state *dst_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812098c0)
Location: kernel/bpf/verifier.c:6598
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff812098c0-ffffffff812099c4: sanitize_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sanitize_err(struct bpf_verifier_env *env, const struct bpf_insn *insn, int reason, const struct bpf_reg_state *off_reg, const struct bpf_reg_state *dst_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8123d5f0)
Location: kernel/bpf/verifier.c:6887
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff8123d5f0-ffffffff8123d6f4: sanitize_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sanitize_err(struct bpf_verifier_env *env, const struct bpf_insn *insn, int reason, const struct bpf_reg_state *off_reg, const struct bpf_reg_state *dst_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812829d0)
Location: kernel/bpf/verifier.c:7886
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff812829d0-ffffffff81282b46: sanitize_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sanitize_err(struct bpf_verifier_env *env, const struct bpf_insn *insn, int reason, const struct bpf_reg_state *off_reg, const struct bpf_reg_state *dst_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812da500)
Location: kernel/bpf/verifier.c:9822
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff812da500-ffffffff812da676: sanitize_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sanitize_err(struct bpf_verifier_env *env, const struct bpf_insn *insn, int reason, const struct bpf_reg_state *off_reg, const struct bpf_reg_state *dst_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812f6810)
Location: kernel/bpf/verifier.c:11738
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff812f6810-ffffffff812f697a: sanitize_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sanitize_err(struct bpf_verifier_env *env, const struct bpf_insn *insn, int reason, const struct bpf_reg_state *off_reg, const struct bpf_reg_state *dst_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff813155d0)
Location: kernel/bpf/verifier.c:12672
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff813155d0-ffffffff8131573a: sanitize_err (STB_LOCAL)
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
