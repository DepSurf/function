# Function: <code>bpf_obj_free_fields</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_obj_free_fields(const struct btf_record *rec, void *obj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812c99c0)
Location: kernel/bpf/syscall.c:638
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_obj_drop_impl
  - kernel/bpf/helpers.c:bpf_list_head_free
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:array_map_update_elem
```
**Symbols:**

```
ffffffff812c99c0-ffffffff812c9ab0: bpf_obj_free_fields (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_obj_free_fields(const struct btf_record *rec, void *obj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812f1150)
Location: kernel/bpf/syscall.c:627
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:__bpf_obj_drop_impl
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:check_and_free_fields
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:array_map_update_elem
```
**Symbols:**

```
ffffffff812f1150-ffffffff812f1310: bpf_obj_free_fields (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_obj_free_fields(const struct btf_record *rec, void *obj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8130ff70)
Location: kernel/bpf/syscall.c:628
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_obj_drop_impl
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:check_and_free_fields
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:array_map_update_elem
```
**Symbols:**

```
ffffffff8130ff70-ffffffff8131013f: bpf_obj_free_fields (STB_GLOBAL)
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
