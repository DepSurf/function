# Function: <code>btf_nr_types</code>

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
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
u32 btf_nr_types(const struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122ca65)
Location: kernel/bpf/btf.c:462
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_find_by_name_kind
Direct callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
```
**Symbols:**

```
ffffffff8122ca40-ffffffff8122ca5e: btf_nr_types (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
u32 btf_nr_types(const struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812653c5)
Location: kernel/bpf/btf.c:462
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_find_by_name_kind
Direct callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
```
**Symbols:**

```
ffffffff812653a0-ffffffff812653be: btf_nr_types (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
u32 btf_nr_types(const struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b8f55)
Location: kernel/bpf/btf.c:505
Inline: True
Inline callers:
  - kernel/bpf/btf.c:bpf_core_add_cands
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_check_type_tags
  - kernel/bpf/btf.c:btf_find_by_name_kind
Direct callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
```
**Symbols:**

```
ffffffff812b13e0-ffffffff812b1407: btf_nr_types (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
u32 btf_nr_types(const struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8131af65)
Location: kernel/bpf/btf.c:500
Inline: True
Inline callers:
  - kernel/bpf/btf.c:bpf_core_add_cands
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_check_type_tags
  - kernel/bpf/btf.c:btf_find_by_name_kind
Direct callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
```
**Symbols:**

```
ffffffff813115e0-ffffffff81311607: btf_nr_types (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u32 btf_nr_types(const struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8134a555)
Location: kernel/bpf/btf.c:523
Inline: True
Inline callers:
  - kernel/bpf/btf.c:bpf_core_add_cands
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_check_type_tags
  - kernel/bpf/btf.c:btf_find_by_name_kind
Direct callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
```
**Symbols:**

```
ffffffff81340fc0-ffffffff81340fe7: btf_nr_types (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
u32 btf_nr_types(const struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81370d05)
Location: kernel/bpf/btf.c:524
Inline: True
Inline callers:
  - kernel/bpf/btf.c:bpf_core_add_cands
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_check_type_tags
  - kernel/bpf/btf.c:btf_find_decl_tag_value
  - kernel/bpf/btf.c:btf_find_by_name_kind
Direct callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
```
**Symbols:**

```
ffffffff813675d0-ffffffff813675f7: btf_nr_types (STB_GLOBAL)
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
