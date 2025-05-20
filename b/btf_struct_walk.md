# Function: <code>btf_struct_walk</code>

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
int btf_struct_walk(struct bpf_verifier_log *log, const struct btf *btf, const struct btf_type *t, int off, int size, u32 *next_btf_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812281b0)
Location: kernel/bpf/btf.c:4759
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_access
```
**Symbols:**

```
ffffffff812281b0-ffffffff81228754: btf_struct_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int btf_struct_walk(struct bpf_verifier_log *log, const struct btf *btf, const struct btf_type *t, int off, int size, u32 *next_btf_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122ccb0)
Location: kernel/bpf/btf.c:4832
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_access
```
**Symbols:**

```
ffffffff8122ccb0-ffffffff8122d155: btf_struct_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int btf_struct_walk(struct bpf_verifier_log *log, const struct btf *btf, const struct btf_type *t, int off, int size, u32 *next_btf_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81265640)
Location: kernel/bpf/btf.c:4885
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_access
```
**Symbols:**

```
ffffffff81265640-ffffffff81265ae5: btf_struct_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int btf_struct_walk(struct bpf_verifier_log *log, const struct btf *btf, const struct btf_type *t, int off, int size, u32 *next_btf_id, enum bpf_type_flag *flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b1810)
Location: kernel/bpf/btf.c:5415
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_access
```
**Symbols:**

```
ffffffff812b1810-ffffffff812b1e0a: btf_struct_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int btf_struct_walk(struct bpf_verifier_log *log, const struct btf *btf, const struct btf_type *t, int off, int size, u32 *next_btf_id, enum bpf_type_flag *flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81311b80)
Location: kernel/bpf/btf.c:6051
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_access
```
**Symbols:**

```
ffffffff81311b80-ffffffff813121c4: btf_struct_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int btf_struct_walk(struct bpf_verifier_log *log, const struct btf *btf, const struct btf_type *t, int off, int size, u32 *next_btf_id, enum bpf_type_flag *flag, const char **field_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81341410)
Location: kernel/bpf/btf.c:6125
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_access
```
**Symbols:**

```
ffffffff81341410-ffffffff81341af1: btf_struct_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int btf_struct_walk(struct bpf_verifier_log *log, const struct btf *btf, const struct btf_type *t, int off, int size, u32 *next_btf_id, enum bpf_type_flag *flag, const char **field_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81367930)
Location: kernel/bpf/btf.c:6295
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_access
```
**Symbols:**

```
ffffffff81367930-ffffffff81368037: btf_struct_walk (STB_LOCAL)
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
<code>enum bpf_type_flag *flag</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char **field_name</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
