# Function: <code>sanitize_check_bounds</code>

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
int sanitize_check_bounds(struct bpf_verifier_env *env, const struct bpf_insn *insn, const struct bpf_reg_state *dst_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81209250)
Location: kernel/bpf/verifier.c:6671
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff81209250-ffffffff81209377: sanitize_check_bounds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sanitize_check_bounds(struct bpf_verifier_env *env, const struct bpf_insn *insn, const struct bpf_reg_state *dst_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:6960
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff8123cee0-ffffffff8123d024: sanitize_check_bounds (STB_LOCAL)
ffffffff81cb81aa-ffffffff81cb81c8: sanitize_check_bounds.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sanitize_check_bounds(struct bpf_verifier_env *env, const struct bpf_insn *insn, const struct bpf_reg_state *dst_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:7959
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff81282250-ffffffff812823a6: sanitize_check_bounds (STB_LOCAL)
ffffffff81e693c9-ffffffff81e693e7: sanitize_check_bounds.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int sanitize_check_bounds(struct bpf_verifier_env *env, const struct bpf_insn *insn, const struct bpf_reg_state *dst_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:9895
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff812d9d40-ffffffff812d9e96: sanitize_check_bounds (STB_LOCAL)
ffffffff820601c9-ffffffff820601e7: sanitize_check_bounds.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int sanitize_check_bounds(struct bpf_verifier_env *env, const struct bpf_insn *insn, const struct bpf_reg_state *dst_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:11811
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff81309890-ffffffff813099e3: sanitize_check_bounds (STB_LOCAL)
ffffffff820df7cb-ffffffff820df7e9: sanitize_check_bounds.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int sanitize_check_bounds(struct bpf_verifier_env *env, const struct bpf_insn *insn, const struct bpf_reg_state *dst_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:12745
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff8132dc00-ffffffff8132dd53: sanitize_check_bounds (STB_LOCAL)
ffffffff821bc240-ffffffff821bc25e: sanitize_check_bounds.cold (STB_LOCAL)
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
