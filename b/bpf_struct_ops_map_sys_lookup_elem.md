# Function: <code>bpf_struct_ops_map_sys_lookup_elem</code>

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
int bpf_struct_ops_map_sys_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff81230050)
Location: kernel/bpf/bpf_struct_ops.c:241
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_seq_show_elem
```
**Symbols:**

```
ffffffff81230050-ffffffff812300ad: bpf_struct_ops_map_sys_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_struct_ops_map_sys_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff81238500)
Location: kernel/bpf/bpf_struct_ops.c:241
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_seq_show_elem
```
**Symbols:**

```
ffffffff81238500-ffffffff8123855d: bpf_struct_ops_map_sys_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_struct_ops_map_sys_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff8123ccf0)
Location: kernel/bpf/bpf_struct_ops.c:241
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_seq_show_elem
```
**Symbols:**

```
ffffffff8123ccf0-ffffffff8123cd4d: bpf_struct_ops_map_sys_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_struct_ops_map_sys_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff81277770)
Location: kernel/bpf/bpf_struct_ops.c:242
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_seq_show_elem
```
**Symbols:**

```
ffffffff81277770-ffffffff812777cd: bpf_struct_ops_map_sys_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_struct_ops_map_sys_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff812c7380)
Location: kernel/bpf/bpf_struct_ops.c:246
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_seq_show_elem
```
**Symbols:**

```
ffffffff812c7380-ffffffff812c73fb: bpf_struct_ops_map_sys_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_struct_ops_map_sys_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff8132cd20)
Location: kernel/bpf/bpf_struct_ops.c:246
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_seq_show_elem
```
**Symbols:**

```
ffffffff8132cd20-ffffffff8132cd9b: bpf_struct_ops_map_sys_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_struct_ops_map_sys_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff8135d160)
Location: kernel/bpf/bpf_struct_ops.c:255
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_seq_show_elem
```
**Symbols:**

```
ffffffff8135d160-ffffffff8135d1ef: bpf_struct_ops_map_sys_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_struct_ops_map_sys_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff81385870)
Location: kernel/bpf/bpf_struct_ops.c:255
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_seq_show_elem
```
**Symbols:**

```
ffffffff81385870-ffffffff813858ff: bpf_struct_ops_map_sys_lookup_elem (STB_GLOBAL)
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
