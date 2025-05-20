# Function: <code>btf_type_seq_show</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void btf_type_seq_show(const struct btf *btf, u32 type_id, void *obj, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811c87b0)
Location: kernel/bpf/btf.c:2229
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
```
**Symbols:**

```
ffffffff811c87b0-ffffffff811c87f5: btf_type_seq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void btf_type_seq_show(const struct btf *btf, u32 type_id, void *obj, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811dc600)
Location: kernel/bpf/btf.c:2881
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
```
**Symbols:**

```
ffffffff811dc600-ffffffff811dc645: btf_type_seq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void btf_type_seq_show(const struct btf *btf, u32 type_id, void *obj, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f1d60)
Location: kernel/bpf/btf.c:3371
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
```
**Symbols:**

```
ffffffff811f1d60-ffffffff811f1da8: btf_type_seq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void btf_type_seq_show(const struct btf *btf, u32 type_id, void *obj, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811fe470)
Location: kernel/bpf/btf.c:3370
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
```
**Symbols:**

```
ffffffff811fe470-ffffffff811fe4b8: btf_type_seq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void btf_type_seq_show(const struct btf *btf, u32 type_id, void *obj, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81225d60)
Location: kernel/bpf/btf.c:4562
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_seq_show_elem
```
**Symbols:**

```
ffffffff81225d60-ffffffff81225da8: btf_type_seq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void btf_type_seq_show(const struct btf *btf, u32 type_id, void *obj, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122c7c0)
Location: kernel/bpf/btf.c:5518
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_seq_show_elem
```
**Symbols:**

```
ffffffff8122c7c0-ffffffff8122c7d6: btf_type_seq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void btf_type_seq_show(const struct btf *btf, u32 type_id, void *obj, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81231580)
Location: kernel/bpf/btf.c:5711
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_seq_show_elem
```
**Symbols:**

```
ffffffff81231580-ffffffff81231596: btf_type_seq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void btf_type_seq_show(const struct btf *btf, u32 type_id, void *obj, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8126a510)
Location: kernel/bpf/btf.c:5764
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_seq_show_elem
```
**Symbols:**

```
ffffffff8126a510-ffffffff8126a526: btf_type_seq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void btf_type_seq_show(const struct btf *btf, u32 type_id, void *obj, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b7300)
Location: kernel/bpf/btf.c:6497
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_seq_show_elem
```
**Symbols:**

```
ffffffff812b7300-ffffffff812b7327: btf_type_seq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void btf_type_seq_show(const struct btf *btf, u32 type_id, void *obj, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81318920)
Location: kernel/bpf/btf.c:6988
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_seq_show_elem
```
**Symbols:**

```
ffffffff81318920-ffffffff81318947: btf_type_seq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void btf_type_seq_show(const struct btf *btf, u32 type_id, void *obj, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81348810)
Location: kernel/bpf/btf.c:7090
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_seq_show_elem
```
**Symbols:**

```
ffffffff81348810-ffffffff81348837: btf_type_seq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void btf_type_seq_show(const struct btf *btf, u32 type_id, void *obj, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8136ef40)
Location: kernel/bpf/btf.c:7154
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_seq_show_elem
```
**Symbols:**

```
ffffffff8136ef40-ffffffff8136ef67: btf_type_seq_show (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void btf_type_seq_show(const struct btf *btf, u32 type_id, void *obj, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffff800010285478)
Location: kernel/bpf/btf.c:3370
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
```
**Symbols:**

```
ffff800010285478-ffff8000102854fc: btf_type_seq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void btf_type_seq_show(const struct btf *btf, u32 type_id, void *obj, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c04b5a7c)
Location: kernel/bpf/btf.c:3370
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
```
**Symbols:**

```
c04b5a7c-c04b5ae8: btf_type_seq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void btf_type_seq_show(const struct btf *btf, u32 type_id, void *obj, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c0000000003301f0)
Location: kernel/bpf/btf.c:3370
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
```
**Symbols:**

```
c0000000003301f0-c0000000003302b4: btf_type_seq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void btf_type_seq_show(const struct btf *btf, u32 type_id, void *obj, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffe0001ba898)
Location: kernel/bpf/btf.c:3370
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
```
**Symbols:**

```
ffffffe0001ba898-ffffffe0001ba904: btf_type_seq_show (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void btf_type_seq_show(const struct btf *btf, u32 type_id, void *obj, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f6a90)
Location: kernel/bpf/btf.c:3370
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
```
**Symbols:**

```
ffffffff811f6a90-ffffffff811f6ad8: btf_type_seq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void btf_type_seq_show(const struct btf *btf, u32 type_id, void *obj, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811e97e0)
Location: kernel/bpf/btf.c:3370
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
```
**Symbols:**

```
ffffffff811e97e0-ffffffff811e9828: btf_type_seq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void btf_type_seq_show(const struct btf *btf, u32 type_id, void *obj, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f4860)
Location: kernel/bpf/btf.c:3370
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
```
**Symbols:**

```
ffffffff811f4860-ffffffff811f48a8: btf_type_seq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void btf_type_seq_show(const struct btf *btf, u32 type_id, void *obj, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81202d70)
Location: kernel/bpf/btf.c:3370
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
```
**Symbols:**

```
ffffffff81202d70-ffffffff81202db8: btf_type_seq_show (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
