# Function: <code>btf_types_are_same</code>

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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122bbf9)
Location: kernel/bpf/btf.c:5031
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812305f9)
Location: kernel/bpf/btf.c:5104
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81269379)
Location: kernel/bpf/btf.c:5157
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b6867)
Location: kernel/bpf/btf.c:5704
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool btf_types_are_same(const struct btf *btf1, u32 id1, const struct btf *btf2, u32 id2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81317a87)
Location: kernel/bpf/btf.c:6373
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
```
**Symbols:**

```
ffffffff813178a0-ffffffff8131792c: btf_types_are_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool btf_types_are_same(const struct btf *btf1, u32 id1, const struct btf *btf2, u32 id2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8134798a)
Location: kernel/bpf/btf.c:6461
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
```
**Symbols:**

```
ffffffff813477a0-ffffffff8134782c: btf_types_are_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool btf_types_are_same(const struct btf *btf1, u32 id1, const struct btf *btf2, u32 id2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8136ddfa)
Location: kernel/bpf/btf.c:6633
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
```
**Symbols:**

```
ffffffff8136dc10-ffffffff8136dc9c: btf_types_are_same (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
