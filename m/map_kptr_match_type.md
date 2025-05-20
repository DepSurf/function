# Function: <code>map_kptr_match_type</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int map_kptr_match_type(struct bpf_verifier_env *env, struct bpf_map_value_off_desc *off_desc, struct bpf_reg_state *reg, u32 regno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81285020)
Location: kernel/bpf/verifier.c:3653
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff81285020-ffffffff812852a5: map_kptr_match_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int map_kptr_match_type(struct bpf_verifier_env *env, struct btf_field *kptr_field, struct bpf_reg_state *reg, u32 regno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812d72b0)
Location: kernel/bpf/verifier.c:4095
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff812d72b0-ffffffff812d7474: map_kptr_match_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int map_kptr_match_type(struct bpf_verifier_env *env, struct btf_field *kptr_field, struct bpf_reg_state *reg, u32 regno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81300bd0)
Location: kernel/bpf/verifier.c:4980
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_reg_type
```
**Symbols:**

```
ffffffff81300bd0-ffffffff81300d83: map_kptr_match_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int map_kptr_match_type(struct bpf_verifier_env *env, struct btf_field *kptr_field, struct bpf_reg_state *reg, u32 regno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8131e6f0)
Location: kernel/bpf/verifier.c:5138
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_reg_type
```
**Symbols:**

```
ffffffff8131e6f0-ffffffff8131e8b7: map_kptr_match_type (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct btf_field *kptr_field</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bpf_map_value_off_desc *off_desc</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
