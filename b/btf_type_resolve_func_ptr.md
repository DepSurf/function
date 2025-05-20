# Function: <code>btf_type_resolve_func_ptr</code>

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
const struct btf_type *btf_type_resolve_func_ptr(const struct btf *btf, u32 id, u32 *res_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81222ef0)
Location: kernel/bpf/btf.c:432
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_struct_ops_btf_id
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init_member
```
**Symbols:**

```
ffffffff81222ef0-ffffffff81222f6b: btf_type_resolve_func_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const struct btf_type *btf_type_resolve_func_ptr(const struct btf *btf, u32 id, u32 *res_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81229140)
Location: kernel/bpf/btf.c:521
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_struct_ops_btf_id
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init_member
```
**Symbols:**

```
ffffffff81229140-ffffffff812291fa: btf_type_resolve_func_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const struct btf_type *btf_type_resolve_func_ptr(const struct btf *btf, u32 id, u32 *res_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122d9e0)
Location: kernel/bpf/btf.c:522
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_struct_ops_btf_id
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init_member
```
**Symbols:**

```
ffffffff8122d9e0-ffffffff8122da9a: btf_type_resolve_func_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const struct btf_type *btf_type_resolve_func_ptr(const struct btf *btf, u32 id, u32 *res_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81266410)
Location: kernel/bpf/btf.c:522
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_struct_ops_btf_id
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init_member
```
**Symbols:**

```
ffffffff81266410-ffffffff812664ca: btf_type_resolve_func_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const struct btf_type *btf_type_resolve_func_ptr(const struct btf *btf, u32 id, u32 *res_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b2fc0)
Location: kernel/bpf/btf.c:609
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_struct_ops_btf_id
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init_member
```
**Symbols:**

```
ffffffff812b2fc0-ffffffff812b3015: btf_type_resolve_func_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const struct btf_type *btf_type_resolve_func_ptr(const struct btf *btf, u32 id, u32 *res_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81313410)
Location: kernel/bpf/btf.c:604
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_struct_ops_btf_id
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
```
**Symbols:**

```
ffffffff81313410-ffffffff81313465: btf_type_resolve_func_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const struct btf_type *btf_type_resolve_func_ptr(const struct btf *btf, u32 id, u32 *res_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff813430e0)
Location: kernel/bpf/btf.c:627
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_struct_ops_btf_id
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
```
**Symbols:**

```
ffffffff813430e0-ffffffff8134313f: btf_type_resolve_func_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const struct btf_type *btf_type_resolve_func_ptr(const struct btf *btf, u32 id, u32 *res_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81369010)
Location: kernel/bpf/btf.c:628
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_struct_ops_btf_id
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
```
**Symbols:**

```
ffffffff81369010-ffffffff8136906f: btf_type_resolve_func_ptr (STB_GLOBAL)
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
