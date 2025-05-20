# Function: <code>map_value_has_spin_lock</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (0)
Location: include/linux/bpf.h:105
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/bpf.h:105
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/bpf.h:105
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/bpf.h:105
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/bpf.h:105
Inline: True
```
```
In kernel/bpf/map_in_map.c (0)
Location: include/linux/bpf.h:105
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/bpf.h:105
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/bpf.h:105
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/map_in_map.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811ff92b)
Location: include/linux/bpf.h:139
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_mmap
  - kernel/bpf/syscall.c:bpf_map_copy_value
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
```
In kernel/bpf/verifier.c (ffffffff81205421)
Location: include/linux/bpf.h:139
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_map_prog_compatibility
  - kernel/bpf/verifier.c:check_ld_imm
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:process_spin_lock
  - kernel/bpf/verifier.c:check_map_access
```
```
In kernel/bpf/helpers.c (ffffffff81214ec6)
Location: include/linux/bpf.h:139
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
```
```
In kernel/bpf/hashtab.c (ffffffff812189fb)
Location: include/linux/bpf.h:139
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/arraymap.c (ffffffff81219d47)
Location: include/linux/bpf.h:139
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_update_elem
  - kernel/bpf/arraymap.c:array_map_update_elem
```
```
In kernel/bpf/map_in_map.c (ffffffff8121ca96)
Location: include/linux/bpf.h:139
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/local_storage.c (ffffffff8121d725)
Location: include/linux/bpf.h:139
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
```
```
In net/core/bpf_sk_storage.c (ffffffff81a612e1)
Location: include/linux/bpf.h:139
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fecdb)
Location: include/linux/bpf.h:181
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_mmap
  - kernel/bpf/syscall.c:bpf_map_copy_value
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
```
In kernel/bpf/verifier.c (ffffffff8120604c)
Location: include/linux/bpf.h:181
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_map_prog_compatibility
  - kernel/bpf/verifier.c:check_ld_imm
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:process_spin_lock
  - kernel/bpf/verifier.c:check_map_access
```
```
In kernel/bpf/helpers.c (ffffffff81216ab6)
Location: include/linux/bpf.h:181
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
```
```
In kernel/bpf/hashtab.c (ffffffff8121ad16)
Location: include/linux/bpf.h:181
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/arraymap.c (ffffffff8121c988)
Location: include/linux/bpf.h:181
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_update_elem
  - kernel/bpf/arraymap.c:array_map_update_elem
```
```
In kernel/bpf/map_in_map.c (ffffffff8121f992)
Location: include/linux/bpf.h:181
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/local_storage.c (ffffffff81220559)
Location: include/linux/bpf.h:181
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff812300ce)
Location: include/linux/bpf.h:181
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
```
```
In net/core/bpf_sk_storage.c (ffffffff81a69bd1)
Location: include/linux/bpf.h:181
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811ff76b)
Location: include/linux/bpf.h:192
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_mmap
  - kernel/bpf/syscall.c:bpf_map_copy_value
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
```
In kernel/bpf/verifier.c (ffffffff81207f83)
Location: include/linux/bpf.h:192
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_map_prog_compatibility
  - kernel/bpf/verifier.c:check_ld_imm
  - kernel/bpf/verifier.c:process_spin_lock
  - kernel/bpf/verifier.c:check_map_access
```
```
In kernel/bpf/helpers.c (ffffffff812197f6)
Location: include/linux/bpf.h:192
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
```
```
In kernel/bpf/hashtab.c (ffffffff8121e9ae)
Location: include/linux/bpf.h:192
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/arraymap.c (ffffffff812204a8)
Location: include/linux/bpf.h:192
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_update_elem
  - kernel/bpf/arraymap.c:array_map_update_elem
```
```
In kernel/bpf/map_in_map.c (ffffffff81223412)
Location: include/linux/bpf.h:192
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/local_storage.c (ffffffff81223fe9)
Location: include/linux/bpf.h:192
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8122568f)
Location: include/linux/bpf.h:192
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
```
```
In net/core/bpf_sk_storage.c (ffffffff81a52641)
Location: include/linux/bpf.h:192
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8122eda9)
Location: include/linux/bpf.h:196
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_mmap
  - kernel/bpf/syscall.c:bpf_map_copy_value
  - kernel/bpf/syscall.c:copy_map_value
```
```
In kernel/bpf/verifier.c (ffffffff8123b845)
Location: include/linux/bpf.h:196
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_map_prog_compatibility
  - kernel/bpf/verifier.c:check_ld_imm
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:process_spin_lock
  - kernel/bpf/verifier.c:check_map_access
```
```
In kernel/bpf/helpers.c (ffffffff8124faf3)
Location: include/linux/bpf.h:196
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value
```
```
In kernel/bpf/hashtab.c (ffffffff81254f9e)
Location: include/linux/bpf.h:196
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:prealloc_lru_pop
  - kernel/bpf/hashtab.c:copy_map_value
```
```
In kernel/bpf/arraymap.c (ffffffff81257c78)
Location: include/linux/bpf.h:196
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_update_elem
  - kernel/bpf/arraymap.c:copy_map_value
```
```
In kernel/bpf/map_in_map.c (ffffffff8125b1c6)
Location: include/linux/bpf.h:196
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/local_storage.c (ffffffff8125becb)
Location: include/linux/bpf.h:196
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8125d67f)
Location: include/linux/bpf.h:196
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
```
```
In net/core/bpf_sk_storage.c (ffffffff81b0b0b1)
Location: include/linux/bpf.h:196
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:copy_map_value
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81271671)
Location: include/linux/bpf.h:246
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_mmap
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
```
In kernel/bpf/verifier.c (ffffffff81281378)
Location: include/linux/bpf.h:246
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_map_prog_compatibility
  - kernel/bpf/verifier.c:check_ld_imm
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:process_spin_lock
  - kernel/bpf/verifier.c:check_map_access
```
```
In kernel/bpf/hashtab.c (ffffffff8129e392)
Location: include/linux/bpf.h:246
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/arraymap.c (ffffffff812a0907)
Location: include/linux/bpf.h:246
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_update_elem
```
```
In kernel/bpf/map_in_map.c (ffffffff812a43be)
Location: include/linux/bpf.h:246
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/local_storage.c (ffffffff812a5a03)
Location: include/linux/bpf.h:246
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff812a7953)
Location: include/linux/bpf.h:246
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
```
```
In net/core/bpf_sk_storage.c (ffffffff81c91782)
Location: include/linux/bpf.h:246
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/map_in_map.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c0493c24)
Location: include/linux/bpf.h:108
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/verifier.c (c049b2a8)
Location: include/linux/bpf.h:108
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:process_spin_lock
  - kernel/bpf/verifier.c:check_map_access
```
```
In kernel/bpf/helpers.c (c04a9010)
Location: include/linux/bpf.h:108
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
```
```
In kernel/bpf/hashtab.c (c04ac39c)
Location: include/linux/bpf.h:108
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/arraymap.c (c04acf60)
Location: include/linux/bpf.h:108
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_update_elem
  - kernel/bpf/arraymap.c:array_map_update_elem
```
```
In kernel/bpf/map_in_map.c (c04af8e4)
Location: include/linux/bpf.h:108
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/local_storage.c (c04b0684)
Location: include/linux/bpf.h:108
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
```
```
In net/core/bpf_sk_storage.c (c0d48d7c)
Location: include/linux/bpf.h:108
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/map_in_map.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/map_in_map.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/map_in_map.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/map_in_map.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/map_in_map.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/map_in_map.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/bpf.h:108
Inline: True
```
</details>
</li>
</ul>

## Differences
