# Function: <code>check_and_init_map_lock</code>

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
In kernel/bpf/syscall.c (ffffffff811d4ad8)
Location: include/linux/bpf.h:110
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/hashtab.c (ffffffff811e75d3)
Location: include/linux/bpf.h:110
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/local_storage.c (ffffffff811ed157)
Location: include/linux/bpf.h:110
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
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
In kernel/bpf/syscall.c (ffffffff811e11d8)
Location: include/linux/bpf.h:113
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/hashtab.c (ffffffff811f3d33)
Location: include/linux/bpf.h:113
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/local_storage.c (ffffffff811f98a7)
Location: include/linux/bpf.h:113
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
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
In kernel/bpf/syscall.c (ffffffff811ff1a2)
Location: include/linux/bpf.h:144
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
```
In kernel/bpf/hashtab.c (ffffffff812189fb)
Location: include/linux/bpf.h:144
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/local_storage.c (ffffffff8121d725)
Location: include/linux/bpf.h:144
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
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
In kernel/bpf/syscall.c (ffffffff811fe4eb)
Location: include/linux/bpf.h:186
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
```
In kernel/bpf/hashtab.c (ffffffff8121ad16)
Location: include/linux/bpf.h:186
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/local_storage.c (ffffffff81220559)
Location: include/linux/bpf.h:186
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
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
In kernel/bpf/syscall.c (ffffffff811fef7b)
Location: include/linux/bpf.h:197
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
```
In kernel/bpf/hashtab.c (ffffffff8121e9ae)
Location: include/linux/bpf.h:197
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/local_storage.c (ffffffff81223fe9)
Location: include/linux/bpf.h:197
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
In kernel/bpf/syscall.c (ffff800010263f04)
Location: include/linux/bpf.h:113
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/hashtab.c (ffff800010278428)
Location: include/linux/bpf.h:113
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/local_storage.c (ffff80001027f270)
Location: include/linux/bpf.h:113
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
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
In kernel/bpf/syscall.c (c0496584)
Location: include/linux/bpf.h:113
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/hashtab.c (c04aa4c0)
Location: include/linux/bpf.h:113
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/local_storage.c (c04b0684)
Location: include/linux/bpf.h:113
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
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
In kernel/bpf/syscall.c (c000000000308cc8)
Location: include/linux/bpf.h:113
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/hashtab.c (c0000000003206a4)
Location: include/linux/bpf.h:113
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/local_storage.c (c0000000003293d8)
Location: include/linux/bpf.h:113
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
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
In kernel/bpf/syscall.c (ffffffe0001a0078)
Location: include/linux/bpf.h:113
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/hashtab.c (ffffffe0001afbe6)
Location: include/linux/bpf.h:113
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/local_storage.c (ffffffe0001b5f8c)
Location: include/linux/bpf.h:113
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
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
In kernel/bpf/syscall.c (ffffffff811d97f8)
Location: include/linux/bpf.h:113
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/hashtab.c (ffffffff811ec353)
Location: include/linux/bpf.h:113
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/local_storage.c (ffffffff811f1ec7)
Location: include/linux/bpf.h:113
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
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
In kernel/bpf/syscall.c (ffffffff811cc5b8)
Location: include/linux/bpf.h:113
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/hashtab.c (ffffffff811df0e3)
Location: include/linux/bpf.h:113
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/local_storage.c (ffffffff811e4c17)
Location: include/linux/bpf.h:113
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
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
In kernel/bpf/syscall.c (ffffffff811d75c8)
Location: include/linux/bpf.h:113
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/hashtab.c (ffffffff811ea123)
Location: include/linux/bpf.h:113
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/local_storage.c (ffffffff811efc97)
Location: include/linux/bpf.h:113
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
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
In kernel/bpf/syscall.c (ffffffff811e5b89)
Location: include/linux/bpf.h:113
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/hashtab.c (ffffffff811f8503)
Location: include/linux/bpf.h:113
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/local_storage.c (ffffffff811fe1a7)
Location: include/linux/bpf.h:113
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
```
</details>
</li>
</ul>

## Differences
