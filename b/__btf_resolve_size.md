# Function: <code>__btf_resolve_size</code>

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
const struct btf_type *__btf_resolve_size(const struct btf *btf, const struct btf_type *type, u32 *type_size, const struct btf_type **elem_type, u32 *elem_id, u32 *total_nelems, u32 *type_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81225ac0)
Location: kernel/bpf/btf.c:1692
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_show_obj_safe
```
**Symbols:**

```
ffffffff81225ac0-ffffffff81225c1e: __btf_resolve_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const struct btf_type *__btf_resolve_size(const struct btf *btf, const struct btf_type *type, u32 *type_size, const struct btf_type **elem_type, u32 *elem_id, u32 *total_nelems, u32 *type_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122a5b0)
Location: kernel/bpf/btf.c:1693
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_struct_walk
```
**Symbols:**

```
ffffffff8122a5b0-ffffffff8122a726: __btf_resolve_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const struct btf_type *__btf_resolve_size(const struct btf *btf, const struct btf_type *type, u32 *type_size, const struct btf_type **elem_type, u32 *elem_id, u32 *total_nelems, u32 *type_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81262d30)
Location: kernel/bpf/btf.c:1693
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_struct_walk
```
**Symbols:**

```
ffffffff81262d30-ffffffff81262ea6: __btf_resolve_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const struct btf_type *__btf_resolve_size(const struct btf *btf, const struct btf_type *type, u32 *type_size, const struct btf_type **elem_type, u32 *elem_id, u32 *total_nelems, u32 *type_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812ae870)
Location: kernel/bpf/btf.c:1821
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_struct_walk
```
**Symbols:**

```
ffffffff812ae870-ffffffff812aea2d: __btf_resolve_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const struct btf_type *__btf_resolve_size(const struct btf *btf, const struct btf_type *type, u32 *type_size, const struct btf_type **elem_type, u32 *elem_id, u32 *total_nelems, u32 *type_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8130db70)
Location: kernel/bpf/btf.c:1844
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_struct_walk
```
**Symbols:**

```
ffffffff8130db70-ffffffff8130dd17: __btf_resolve_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const struct btf_type *__btf_resolve_size(const struct btf *btf, const struct btf_type *type, u32 *type_size, const struct btf_type **elem_type, u32 *elem_id, u32 *total_nelems, u32 *type_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8133d3e0)
Location: kernel/bpf/btf.c:1874
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_struct_walk
```
**Symbols:**

```
ffffffff8133d3e0-ffffffff8133d593: __btf_resolve_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const struct btf_type *__btf_resolve_size(const struct btf *btf, const struct btf_type *type, u32 *type_size, const struct btf_type **elem_type, u32 *elem_id, u32 *total_nelems, u32 *type_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff813633f0)
Location: kernel/bpf/btf.c:1875
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_struct_walk
```
**Symbols:**

```
ffffffff813633f0-ffffffff813635a3: __btf_resolve_size (STB_LOCAL)
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
