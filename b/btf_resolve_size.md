# Function: <code>btf_resolve_size</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const struct btf_type *btf_resolve_size(const struct btf *btf, const struct btf_type *type, u32 *type_size, const struct btf_type **elem_type, u32 *total_nelems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81223050)
Location: kernel/bpf/btf.c:1091
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
```
**Symbols:**

```
ffffffff81223050-ffffffff81223123: btf_resolve_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_resolve_size(const struct btf *btf, const struct btf_type *type, u32 *type_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81225c6d)
Location: kernel/bpf/btf.c:1759
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_show_obj_safe
Direct callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
```
**Symbols:**

```
ffffffff812295c0-ffffffff812295da: btf_resolve_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_resolve_size(const struct btf *btf, const struct btf_type *type, u32 *type_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812312ee)
Location: kernel/bpf/btf.c:1761
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
Direct callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
```
**Symbols:**

```
ffffffff8122de60-ffffffff8122de7a: btf_resolve_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_resolve_size(const struct btf *btf, const struct btf_type *type, u32 *type_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8126a232)
Location: kernel/bpf/btf.c:1761
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
Direct callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
```
**Symbols:**

```
ffffffff81266a60-ffffffff81266a7a: btf_resolve_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_resolve_size(const struct btf *btf, const struct btf_type *type, u32 *type_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b7022)
Location: kernel/bpf/btf.c:1890
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
Direct callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
```
**Symbols:**

```
ffffffff812b3c10-ffffffff812b3c3c: btf_resolve_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_resolve_size(const struct btf *btf, const struct btf_type *type, u32 *type_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8131857f)
Location: kernel/bpf/btf.c:1914
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
Direct callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
  - tools/lib/bpf/relo_core.c:bpf_core_calc_type_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
```
**Symbols:**

```
ffffffff81314100-ffffffff8131412c: btf_resolve_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_resolve_size(const struct btf *btf, const struct btf_type *type, u32 *type_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81348519)
Location: kernel/bpf/btf.c:1944
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
Direct callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
  - tools/lib/bpf/relo_core.c:bpf_core_calc_type_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
```
**Symbols:**

```
ffffffff81343f70-ffffffff81343f9c: btf_resolve_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_resolve_size(const struct btf *btf, const struct btf_type *type, u32 *type_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8136e9ed)
Location: kernel/bpf/btf.c:1945
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
Direct callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
  - tools/lib/bpf/relo_core.c:bpf_core_calc_type_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
```
**Symbols:**

```
ffffffff81369f00-ffffffff81369f2c: btf_resolve_size (STB_GLOBAL)
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
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>const struct btf_type **elem_type</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 *total_nelems</code>
</li>
</ul>
</details>
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
