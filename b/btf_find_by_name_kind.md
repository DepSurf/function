# Function: <code>btf_find_by_name_kind</code>

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
s32 btf_find_by_name_kind(const struct btf *btf, const char *name, u8 kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81222d90)
Location: kernel/bpf/btf.c:385
Inline: False
Direct callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init
```
**Symbols:**

```
ffffffff81222d90-ffffffff81222e1f: btf_find_by_name_kind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
s32 btf_find_by_name_kind(const struct btf *btf, const char *name, u8 kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81227f50)
Location: kernel/bpf/btf.c:473
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init
```
**Symbols:**

```
ffffffff81227f50-ffffffff81228033: btf_find_by_name_kind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
s32 btf_find_by_name_kind(const struct btf *btf, const char *name, u8 kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122ca60)
Location: kernel/bpf/btf.c:474
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init
```
**Symbols:**

```
ffffffff8122ca60-ffffffff8122cb40: btf_find_by_name_kind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
s32 btf_find_by_name_kind(const struct btf *btf, const char *name, u8 kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812653c0)
Location: kernel/bpf/btf.c:474
Inline: False
Direct callers:
  - kernel/bpf/btf.c:bpf_btf_find_by_name_kind
  - kernel/bpf/btf.c:bpf_btf_find_by_name_kind
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init
```
**Symbols:**

```
ffffffff812653c0-ffffffff812654a0: btf_find_by_name_kind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
s32 btf_find_by_name_kind(const struct btf *btf, const char *name, u8 kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b1410)
Location: kernel/bpf/btf.c:517
Inline: False
Direct callers:
  - kernel/bpf/btf.c:bpf_find_btf_id
  - kernel/bpf/btf.c:bpf_find_btf_id
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_btf_struct_access
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init
```
**Symbols:**

```
ffffffff812b1410-ffffffff812b1524: btf_find_by_name_kind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
s32 btf_find_by_name_kind(const struct btf *btf, const char *name, u8 kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81311620)
Location: kernel/bpf/btf.c:512
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/btf.c:bpf_find_btf_id
  - kernel/bpf/btf.c:bpf_find_btf_id
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_btf_struct_access
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init
```
**Symbols:**

```
ffffffff81311620-ffffffff81311734: btf_find_by_name_kind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
s32 btf_find_by_name_kind(const struct btf *btf, const char *name, u8 kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81341000)
Location: kernel/bpf/btf.c:535
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:find_btf_func_proto
  - kernel/bpf/btf.c:btf_nested_type_is_trusted
  - kernel/bpf/btf.c:bpf_find_btf_id
  - kernel/bpf/btf.c:bpf_find_btf_id
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_btf_struct_access
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init
```
**Symbols:**

```
ffffffff81341000-ffffffff81341114: btf_find_by_name_kind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
s32 btf_find_by_name_kind(const struct btf *btf, const char *name, u8 kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81367610)
Location: kernel/bpf/btf.c:536
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_find_exception_callback_insn_off
  - kernel/bpf/btf.c:btf_nested_type_is_trusted
  - kernel/bpf/btf.c:bpf_find_btf_id
  - kernel/bpf/btf.c:bpf_find_btf_id
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_btf_struct_access
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init
```
**Symbols:**

```
ffffffff81367610-ffffffff81367724: btf_find_by_name_kind (STB_GLOBAL)
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
