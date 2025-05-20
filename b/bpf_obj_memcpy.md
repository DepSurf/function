# Function: <code>bpf_obj_memcpy</code>

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
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void bpf_obj_memcpy(struct btf_field_offs *foffs, void *dst, void *src, u32 size, bool long_memcpy);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812c5950)
Location: include/linux/bpf.h:378
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
```
In kernel/bpf/helpers.c (ffffffff812f28a0)
Location: include/linux/bpf.h:378
Inline: True
Direct callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
```
```
In kernel/bpf/hashtab.c (ffffffff812f88b0)
Location: include/linux/bpf.h:378
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/arraymap.c (ffffffff812fd860)
Location: include/linux/bpf.h:378
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:__bpf_array_map_seq_show
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:array_map_update_elem
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff81305690)
Location: include/linux/bpf.h:378
Inline: True
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_alloc
```
```
In net/core/bpf_sk_storage.c (ffffffff81e4c710)
Location: include/linux/bpf.h:378
Inline: True
Direct callers:
  - net/core/bpf_sk_storage.c:diag_get
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff812c5950-ffffffff812c5a10: bpf_obj_memcpy.constprop.0 (STB_LOCAL)
ffffffff812f28a0-ffffffff812f2960: bpf_obj_memcpy.constprop.0 (STB_LOCAL)
ffffffff812f88b0-ffffffff812f8970: bpf_obj_memcpy.constprop.0 (STB_LOCAL)
ffffffff812fd860-ffffffff812fd99c: bpf_obj_memcpy (STB_LOCAL)
ffffffff81305690-ffffffff81305750: bpf_obj_memcpy.constprop.0 (STB_LOCAL)
ffffffff81e4c710-ffffffff81e4c7d0: bpf_obj_memcpy.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void bpf_obj_memcpy(struct btf_record *rec, void *dst, void *src, u32 size, bool long_memcpy);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812eca70)
Location: include/linux/bpf.h:432
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
```
In kernel/bpf/helpers.c (ffffffff8131f4c0)
Location: include/linux/bpf.h:432
Inline: True
Direct callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
```
```
In kernel/bpf/hashtab.c (ffffffff81326670)
Location: include/linux/bpf.h:432
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:__bpf_hash_map_seq_show
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/arraymap.c (ffffffff8132c4b0)
Location: include/linux/bpf.h:432
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:__bpf_array_map_seq_show
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:array_map_update_elem
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff81334000)
Location: include/linux/bpf.h:432
Inline: True
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_alloc
```
```
In net/core/bpf_sk_storage.c (ffffffff81ea7e30)
Location: include/linux/bpf.h:432
Inline: True
Direct callers:
  - net/core/bpf_sk_storage.c:diag_get
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff812eca70-ffffffff812ecb15: bpf_obj_memcpy.constprop.0 (STB_LOCAL)
ffffffff8131f4c0-ffffffff8131f565: bpf_obj_memcpy.constprop.0 (STB_LOCAL)
ffffffff81326670-ffffffff81326755: bpf_obj_memcpy (STB_LOCAL)
ffffffff8132c4b0-ffffffff8132c595: bpf_obj_memcpy (STB_LOCAL)
ffffffff81334000-ffffffff813340a5: bpf_obj_memcpy.constprop.0 (STB_LOCAL)
ffffffff81ea7e30-ffffffff81ea7ed5: bpf_obj_memcpy.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void bpf_obj_memcpy(struct btf_record *rec, void *dst, void *src, u32 size, bool long_memcpy);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8130b220)
Location: include/linux/bpf.h:463
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
```
In kernel/bpf/helpers.c (ffffffff813418f0)
Location: include/linux/bpf.h:463
Inline: True
Direct callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
```
```
In kernel/bpf/hashtab.c (ffffffff8134acb0)
Location: include/linux/bpf.h:463
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:__bpf_hash_map_seq_show
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/arraymap.c (ffffffff813509f0)
Location: include/linux/bpf.h:463
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:__bpf_array_map_seq_show
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:array_map_update_elem
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff813586f0)
Location: include/linux/bpf.h:463
Inline: True
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_alloc
```
```
In net/core/bpf_sk_storage.c (ffffffff81f6a8e0)
Location: include/linux/bpf.h:463
Inline: True
Direct callers:
  - net/core/bpf_sk_storage.c:diag_get
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff8130b220-ffffffff8130b2c5: bpf_obj_memcpy.constprop.0 (STB_LOCAL)
ffffffff813418f0-ffffffff81341995: bpf_obj_memcpy.constprop.0 (STB_LOCAL)
ffffffff8134acb0-ffffffff8134ad95: bpf_obj_memcpy (STB_LOCAL)
ffffffff813509f0-ffffffff81350ad5: bpf_obj_memcpy (STB_LOCAL)
ffffffff813586f0-ffffffff81358795: bpf_obj_memcpy.constprop.0 (STB_LOCAL)
ffffffff81f6a8e0-ffffffff81f6a985: bpf_obj_memcpy.constprop.0 (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct btf_record *rec</code>
</li>
<li>
<b>Param removed. </b>
<code>struct btf_field_offs *foffs</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
