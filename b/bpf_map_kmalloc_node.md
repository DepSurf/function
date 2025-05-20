# Function: <code>bpf_map_kmalloc_node</code>

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
void *bpf_map_kmalloc_node(const struct bpf_map *map, size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fda90)
Location: kernel/bpf/syscall.c:403
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - net/core/sock_map.c:sock_hash_alloc_elem
```
**Symbols:**

```
ffffffff811fda90-ffffffff811fdb2a: bpf_map_kmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *bpf_map_kmalloc_node(const struct bpf_map *map, size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fe650)
Location: kernel/bpf/syscall.c:404
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - net/core/sock_map.c:sock_hash_update_common
```
**Symbols:**

```
ffffffff811fe650-ffffffff811fe6e6: bpf_map_kmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *bpf_map_kmalloc_node(const struct bpf_map *map, size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81230290)
Location: kernel/bpf/syscall.c:423
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_timer_init
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - net/core/sock_map.c:sock_hash_update_common
```
**Symbols:**

```
ffffffff81230290-ffffffff81230326: bpf_map_kmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *bpf_map_kmalloc_node(const struct bpf_map *map, size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81272c00)
Location: kernel/bpf/syscall.c:430
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_timer_init
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - net/core/sock_map.c:sock_hash_update_common
```
**Symbols:**

```
ffffffff81272c00-ffffffff81272cae: bpf_map_kmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *bpf_map_kmalloc_node(const struct bpf_map *map, size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812c8f10)
Location: kernel/bpf/syscall.c:444
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_timer_init
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - net/core/sock_map.c:sock_hash_alloc_elem
```
**Symbols:**

```
ffffffff812c8f10-ffffffff812c902f: bpf_map_kmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *bpf_map_kmalloc_node(const struct bpf_map *map, size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812f04e0)
Location: kernel/bpf/syscall.c:412
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_timer_init
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - net/core/sock_map.c:sock_hash_alloc_elem
```
**Symbols:**

```
ffffffff812f04e0-ffffffff812f05ff: bpf_map_kmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *bpf_map_kmalloc_node(const struct bpf_map *map, size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8130f2c0)
Location: kernel/bpf/syscall.c:413
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_timer_init
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - net/core/sock_map.c:sock_hash_alloc_elem
```
**Symbols:**

```
ffffffff8130f2c0-ffffffff8130f3df: bpf_map_kmalloc_node (STB_GLOBAL)
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
