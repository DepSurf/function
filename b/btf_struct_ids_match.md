# Function: <code>btf_struct_ids_match</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool btf_struct_ids_match(struct bpf_verifier_log *log, const struct btf *btf, u32 id, int off, const struct btf *need_btf, u32 need_type_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122bae0)
Location: kernel/bpf/btf.c:5041
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_reg_type
```
**Symbols:**

```
ffffffff8122bae0-ffffffff8122bc9c: btf_struct_ids_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool btf_struct_ids_match(struct bpf_verifier_log *log, const struct btf *btf, u32 id, int off, const struct btf *need_btf, u32 need_type_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812304e0)
Location: kernel/bpf/btf.c:5114
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/btf.c:btf_check_func_arg_match
```
**Symbols:**

```
ffffffff812304e0-ffffffff8123069c: btf_struct_ids_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool btf_struct_ids_match(struct bpf_verifier_log *log, const struct btf *btf, u32 id, int off, const struct btf *need_btf, u32 need_type_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81269260)
Location: kernel/bpf/btf.c:5167
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/btf.c:btf_check_func_arg_match
```
**Symbols:**

```
ffffffff81269260-ffffffff8126941c: btf_struct_ids_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool btf_struct_ids_match(struct bpf_verifier_log *log, const struct btf *btf, u32 id, int off, const struct btf *need_btf, u32 need_type_id, bool strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b6720)
Location: kernel/bpf/btf.c:5714
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
```
**Symbols:**

```
ffffffff812b6720-ffffffff812b6956: btf_struct_ids_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool btf_struct_ids_match(struct bpf_verifier_log *log, const struct btf *btf, u32 id, int off, const struct btf *need_btf, u32 need_type_id, bool strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81317940)
Location: kernel/bpf/btf.c:6383
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:process_kf_arg_ptr_to_list_node
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:map_kptr_match_type
```
**Symbols:**

```
ffffffff81317940-ffffffff81317b76: btf_struct_ids_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool btf_struct_ids_match(struct bpf_verifier_log *log, const struct btf *btf, u32 id, int off, const struct btf *need_btf, u32 need_type_id, bool strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81347840)
Location: kernel/bpf/btf.c:6471
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:__process_kf_arg_ptr_to_graph_node
  - kernel/bpf/verifier.c:process_kf_arg_ptr_to_btf_id
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:map_kptr_match_type
```
**Symbols:**

```
ffffffff81347840-ffffffff81347a79: btf_struct_ids_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool btf_struct_ids_match(struct bpf_verifier_log *log, const struct btf *btf, u32 id, int off, const struct btf *need_btf, u32 need_type_id, bool strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8136dcb0)
Location: kernel/bpf/btf.c:6643
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:__process_kf_arg_ptr_to_graph_node
  - kernel/bpf/verifier.c:process_kf_arg_ptr_to_btf_id
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:map_kptr_match_type
```
**Symbols:**

```
ffffffff8136dcb0-ffffffff8136dee9: btf_struct_ids_match (STB_GLOBAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool strict</code>
</li>
</ul>
</details>
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
