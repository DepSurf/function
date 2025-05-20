# Function: <code>btf_record_has_field</code>

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
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812c7885)
Location: include/linux/bpf.h:332
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_obj_free_timer
```
```
In kernel/bpf/verifier.c (ffffffff812d90e5)
Location: include/linux/bpf.h:332
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_map_prog_compatibility
  - kernel/bpf/verifier.c:check_map_prog_compatibility
  - kernel/bpf/verifier.c:check_map_prog_compatibility
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:process_spin_lock
```
```
In kernel/bpf/hashtab.c (ffffffff812fc2cd)
Location: include/linux/bpf.h:332
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
```
In kernel/bpf/arraymap.c (ffffffff812fda8c)
Location: include/linux/bpf.h:332
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_update_elem
```
```
In kernel/bpf/local_storage.c (ffffffff813033eb)
Location: include/linux/bpf.h:332
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff81305fc7)
Location: include/linux/bpf.h:332
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
```
```
In kernel/bpf/btf.c (ffffffff813193fa)
Location: include/linux/bpf.h:332
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_fields
```
```
In net/core/bpf_sk_storage.c (ffffffff81e4cd26)
Location: include/linux/bpf.h:332
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812eed57)
Location: include/linux/bpf.h:386
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_obj_free_timer
```
```
In kernel/bpf/verifier.c (ffffffff81303085)
Location: include/linux/bpf.h:386
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_map_prog_compatibility
  - kernel/bpf/verifier.c:check_map_prog_compatibility
  - kernel/bpf/verifier.c:check_map_prog_compatibility
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:process_spin_lock
```
```
In kernel/bpf/hashtab.c (ffffffff8132acec)
Location: include/linux/bpf.h:386
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
```
In kernel/bpf/arraymap.c (ffffffff8132c692)
Location: include/linux/bpf.h:386
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_update_elem
```
```
In kernel/bpf/local_storage.c (ffffffff81331e95)
Location: include/linux/bpf.h:386
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff81334d0c)
Location: include/linux/bpf.h:386
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
```
```
In kernel/bpf/btf.c (ffffffff813495ab)
Location: include/linux/bpf.h:386
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_fields
```
```
In net/core/bpf_sk_storage.c (ffffffff81ea844a)
Location: include/linux/bpf.h:386
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8130db17)
Location: include/linux/bpf.h:417
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_obj_free_timer
```
```
In kernel/bpf/verifier.c (ffffffff81322b90)
Location: include/linux/bpf.h:417
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_map_prog_compatibility
  - kernel/bpf/verifier.c:check_map_prog_compatibility
  - kernel/bpf/verifier.c:check_map_prog_compatibility
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:process_spin_lock
```
```
In kernel/bpf/hashtab.c (ffffffff8134f1c3)
Location: include/linux/bpf.h:417
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
```
In kernel/bpf/arraymap.c (ffffffff81350bd2)
Location: include/linux/bpf.h:417
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_update_elem
```
```
In kernel/bpf/local_storage.c (ffffffff81356449)
Location: include/linux/bpf.h:417
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8135945d)
Location: include/linux/bpf.h:417
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
```
```
In kernel/bpf/btf.c (ffffffff8136fcfe)
Location: include/linux/bpf.h:417
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_fields
```
```
In net/core/bpf_sk_storage.c (ffffffff81f6af0a)
Location: include/linux/bpf.h:417
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
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
