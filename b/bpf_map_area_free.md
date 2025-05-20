# Function: <code>bpf_map_area_free</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bpf_map_area_free(void *area);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8118cdd0)
Location: kernel/bpf/syscall.c:74
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
ffffffff8118cdd0-ffffffff8118cde0: bpf_map_area_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bpf_map_area_free(void *area);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81191d40)
Location: kernel/bpf/syscall.c:85
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
ffffffff81191d40-ffffffff81191d50: bpf_map_area_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bpf_map_area_free(void *area);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8119f420)
Location: kernel/bpf/syscall.c:132
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/sockmap.c:sock_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
ffffffff8119f420-ffffffff8119f430: bpf_map_area_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bpf_map_area_free(void *area);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b4e40)
Location: kernel/bpf/syscall.c:156
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/xskmap.c:xsk_map_free
  - kernel/bpf/sockmap.c:__bpf_htab_free
  - kernel/bpf/sockmap.c:sock_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
ffffffff811b4e40-ffffffff811b4e50: bpf_map_area_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bpf_map_area_free(void *area);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c31c0)
Location: kernel/bpf/syscall.c:156
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/xskmap.c:xsk_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
```
**Symbols:**

```
ffffffff811c31c0-ffffffff811c31d0: bpf_map_area_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bpf_map_area_free(void *area);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d3df0)
Location: kernel/bpf/syscall.c:156
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/xskmap.c:xsk_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
```
**Symbols:**

```
ffffffff811d3df0-ffffffff811d3e00: bpf_map_area_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bpf_map_area_free(void *area);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e0180)
Location: kernel/bpf/syscall.c:159
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/xskmap.c:xsk_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
```
**Symbols:**

```
ffffffff811e0180-ffffffff811e0190: bpf_map_area_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bpf_map_area_free(void *area);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fe6f0)
Location: kernel/bpf/syscall.c:313
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
  - net/xdp/xskmap.c:xsk_map_free
```
**Symbols:**

```
ffffffff811fe6f0-ffffffff811fe700: bpf_map_area_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bpf_map_area_free(void *area);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fd9d0)
Location: kernel/bpf/syscall.c:321
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
  - kernel/bpf/arraymap.c:perf_event_fd_array_map_free
  - kernel/bpf/arraymap.c:prog_array_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
  - net/xdp/xskmap.c:xsk_map_free
```
**Symbols:**

```
ffffffff811fd9d0-ffffffff811fd9e0: bpf_map_area_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_map_area_free(void *area);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fe590)
Location: kernel/bpf/syscall.c:322
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
  - kernel/bpf/arraymap.c:perf_event_fd_array_map_free
  - kernel/bpf/arraymap.c:prog_array_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
  - net/xdp/xskmap.c:xsk_map_free
```
**Symbols:**

```
ffffffff811fe590-ffffffff811fe5a0: bpf_map_area_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_map_area_free(void *area);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812301d0)
Location: kernel/bpf/syscall.c:341
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
  - kernel/bpf/arraymap.c:perf_event_fd_array_map_free
  - kernel/bpf/arraymap.c:prog_array_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
  - net/xdp/xskmap.c:xsk_map_free
```
**Symbols:**

```
ffffffff812301d0-ffffffff812301e0: bpf_map_area_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_map_area_free(void *area);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81272b00)
Location: kernel/bpf/syscall.c:347
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
  - kernel/bpf/arraymap.c:perf_event_fd_array_map_free
  - kernel/bpf/arraymap.c:prog_array_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/bloom_filter.c:bloom_map_free
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
  - net/xdp/xskmap.c:xsk_map_free
```
**Symbols:**

```
ffffffff81272b00-ffffffff81272b16: bpf_map_area_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_map_area_free(void *area);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812c8de0)
Location: kernel/bpf/syscall.c:347
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
  - kernel/bpf/arraymap.c:perf_event_fd_array_map_free
  - kernel/bpf/arraymap.c:prog_array_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/lpm_trie.c:trie_free
  - kernel/bpf/bloom_filter.c:bloom_map_free
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_free
  - kernel/bpf/ringbuf.c:ringbuf_map_free
  - kernel/bpf/ringbuf.c:ringbuf_map_free
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_alloc
  - kernel/bpf/offload.c:bpf_map_offload_map_free
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
  - net/core/sock_map.c:sock_map_free
  - net/xdp/xskmap.c:xsk_map_free
```
**Symbols:**

```
ffffffff812c8de0-ffffffff812c8df6: bpf_map_area_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_map_area_free(void *area);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812f03d0)
Location: kernel/bpf/syscall.c:320
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
  - kernel/bpf/arraymap.c:perf_event_fd_array_map_free
  - kernel/bpf/arraymap.c:prog_array_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/lpm_trie.c:trie_free
  - kernel/bpf/bloom_filter.c:bloom_map_free
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_free
  - kernel/bpf/ringbuf.c:ringbuf_map_free
  - kernel/bpf/ringbuf.c:ringbuf_map_free
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_alloc
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/offload.c:bpf_map_offload_map_free
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_alloc
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_alloc
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_alloc
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_free
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_free
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
  - net/core/sock_map.c:sock_map_free
  - net/xdp/xskmap.c:xsk_map_free
```
**Symbols:**

```
ffffffff812f03d0-ffffffff812f03e6: bpf_map_area_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_map_area_free(void *area);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8130f1b0)
Location: kernel/bpf/syscall.c:321
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
  - kernel/bpf/arraymap.c:perf_event_fd_array_map_free
  - kernel/bpf/arraymap.c:prog_array_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/lpm_trie.c:trie_free
  - kernel/bpf/bloom_filter.c:bloom_map_free
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_free
  - kernel/bpf/ringbuf.c:ringbuf_map_free
  - kernel/bpf/ringbuf.c:ringbuf_map_free
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_alloc
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/offload.c:bpf_map_offload_map_free
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - kernel/bpf/bpf_struct_ops.c:__bpf_struct_ops_map_free
  - kernel/bpf/bpf_struct_ops.c:__bpf_struct_ops_map_free
  - kernel/bpf/bpf_struct_ops.c:__bpf_struct_ops_map_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
  - net/core/sock_map.c:sock_map_free
  - net/xdp/xskmap.c:xsk_map_free
```
**Symbols:**

```
ffffffff8130f1b0-ffffffff8130f1c6: bpf_map_area_free (STB_GLOBAL)
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
void bpf_map_area_free(void *area);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffff8000102626f0)
Location: kernel/bpf/syscall.c:159
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/xskmap.c:xsk_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
```
**Symbols:**

```
ffff8000102626f0-ffff80001026271c: bpf_map_area_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bpf_map_area_free(void *area);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c0495274)
Location: kernel/bpf/syscall.c:159
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/xskmap.c:xsk_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
```
**Symbols:**

```
c0495274-c0495290: bpf_map_area_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bpf_map_area_free(void *area);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c000000000307380)
Location: kernel/bpf/syscall.c:159
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:fd_array_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/xskmap.c:xsk_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
```
**Symbols:**

```
c000000000307380-c0000000003073b4: bpf_map_area_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bpf_map_area_free(void *area);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffe00019f0da)
Location: kernel/bpf/syscall.c:159
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/xskmap.c:xsk_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
```
**Symbols:**

```
ffffffe00019f0da-ffffffe00019f104: bpf_map_area_free (STB_GLOBAL)
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
void bpf_map_area_free(void *area);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d87a0)
Location: kernel/bpf/syscall.c:159
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/xskmap.c:xsk_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
```
**Symbols:**

```
ffffffff811d87a0-ffffffff811d87b0: bpf_map_area_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bpf_map_area_free(void *area);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811cb560)
Location: kernel/bpf/syscall.c:159
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/xskmap.c:xsk_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
```
**Symbols:**

```
ffffffff811cb560-ffffffff811cb570: bpf_map_area_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bpf_map_area_free(void *area);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d6570)
Location: kernel/bpf/syscall.c:159
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/xskmap.c:xsk_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
```
**Symbols:**

```
ffffffff811d6570-ffffffff811d6580: bpf_map_area_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bpf_map_area_free(void *area);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e48e0)
Location: kernel/bpf/syscall.c:159
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/xskmap.c:xsk_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
```
**Symbols:**

```
ffffffff811e48e0-ffffffff811e48f0: bpf_map_area_free (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
