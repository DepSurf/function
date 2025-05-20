# Function: <code>btf_type_resolve_ptr</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_type_resolve_ptr(const struct btf *btf, u32 id, u32 *res_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81222ef5)
Location: kernel/bpf/btf.c:420
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
Direct callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
**Symbols:**

```
ffffffff81222e80-ffffffff81222eec: btf_type_resolve_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_type_resolve_ptr(const struct btf *btf, u32 id, u32 *res_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122914c)
Location: kernel/bpf/btf.c:509
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
Direct callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
**Symbols:**

```
ffffffff81229090-ffffffff81229138: btf_type_resolve_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_type_resolve_ptr(const struct btf *btf, u32 id, u32 *res_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122d9ec)
Location: kernel/bpf/btf.c:510
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
Direct callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
**Symbols:**

```
ffffffff8122d940-ffffffff8122d9e0: btf_type_resolve_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_type_resolve_ptr(const struct btf *btf, u32 id, u32 *res_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8126641c)
Location: kernel/bpf/btf.c:510
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
Direct callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
**Symbols:**

```
ffffffff81266370-ffffffff81266410: btf_type_resolve_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_type_resolve_ptr(const struct btf *btf, u32 id, u32 *res_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b2fd4)
Location: kernel/bpf/btf.c:597
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
Direct callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
**Symbols:**

```
ffffffff812b2f70-ffffffff812b2fbc: btf_type_resolve_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_type_resolve_ptr(const struct btf *btf, u32 id, u32 *res_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81313424)
Location: kernel/bpf/btf.c:592
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
Direct callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
**Symbols:**

```
ffffffff813133b0-ffffffff813133fc: btf_type_resolve_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_type_resolve_ptr(const struct btf *btf, u32 id, u32 *res_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff813430f4)
Location: kernel/bpf/btf.c:615
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
Direct callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
**Symbols:**

```
ffffffff81343070-ffffffff813430c1: btf_type_resolve_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_type_resolve_ptr(const struct btf *btf, u32 id, u32 *res_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81369024)
Location: kernel/bpf/btf.c:616
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
Direct callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
**Symbols:**

```
ffffffff81368fa0-ffffffff81368ff1: btf_type_resolve_ptr (STB_GLOBAL)
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
