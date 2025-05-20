# Function: <code>bpf_map_area_alloc</code>

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
void *bpf_map_area_alloc(size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8118cd80)
Location: kernel/bpf/syscall.c:55
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
ffffffff8118cd80-ffffffff8118cdc2: bpf_map_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *bpf_map_area_alloc(size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81191cf0)
Location: kernel/bpf/syscall.c:67
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
ffffffff81191cf0-ffffffff81191d32: bpf_map_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *bpf_map_area_alloc(size_t size, int numa_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8119f3d0)
Location: kernel/bpf/syscall.c:113
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
ffffffff8119f3d0-ffffffff8119f41a: bpf_map_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *bpf_map_area_alloc(size_t size, int numa_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b4df0)
Location: kernel/bpf/syscall.c:137
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
ffffffff811b4df0-ffffffff811b4e3a: bpf_map_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *bpf_map_area_alloc(size_t size, int numa_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c3170)
Location: kernel/bpf/syscall.c:137
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
**Symbols:**

```
ffffffff811c3170-ffffffff811c31ba: bpf_map_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *bpf_map_area_alloc(size_t size, int numa_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d3da0)
Location: kernel/bpf/syscall.c:129
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
**Symbols:**

```
ffffffff811d3da0-ffffffff811d3ded: bpf_map_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *bpf_map_area_alloc(u64 size, int numa_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e0120)
Location: kernel/bpf/syscall.c:129
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
**Symbols:**

```
ffffffff811e0120-ffffffff811e0176: bpf_map_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *bpf_map_area_alloc(u64 size, int numa_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fe6b0)
Location: kernel/bpf/syscall.c:303
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_init
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/devmap.c:dev_map_init_map
  - kernel/bpf/devmap.c:dev_map_init_map
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
**Symbols:**

```
ffffffff811fe6b0-ffffffff811fe6c2: bpf_map_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *bpf_map_area_alloc(u64 size, int numa_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fd990)
Location: kernel/bpf/syscall.c:311
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_init
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/ringbuf.c:bpf_ringbuf_area_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
**Symbols:**

```
ffffffff811fd990-ffffffff811fd9a2: bpf_map_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *bpf_map_area_alloc(u64 size, int numa_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fe550)
Location: kernel/bpf/syscall.c:312
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_init
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
**Symbols:**

```
ffffffff811fe550-ffffffff811fe562: bpf_map_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *bpf_map_area_alloc(u64 size, int numa_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81230190)
Location: kernel/bpf/syscall.c:331
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_init
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
  - kernel/bpf/devmap.c:dev_map_init_map
  - kernel/bpf/devmap.c:dev_map_init_map
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
**Symbols:**

```
ffffffff81230190-ffffffff812301a2: bpf_map_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *bpf_map_area_alloc(u64 size, int numa_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81272ac0)
Location: kernel/bpf/syscall.c:337
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_init
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/bloom_filter.c:bloom_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
  - kernel/bpf/devmap.c:dev_map_init_map
  - kernel/bpf/devmap.c:dev_map_init_map
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
**Symbols:**

```
ffffffff81272ac0-ffffffff81272adc: bpf_map_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *bpf_map_area_alloc(u64 size, int numa_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812c8d80)
Location: kernel/bpf/syscall.c:337
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_init
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/bloom_filter.c:bloom_map_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
  - kernel/bpf/devmap.c:dev_map_init_map
  - kernel/bpf/devmap.c:dev_map_init_map
  - kernel/bpf/cpumap.c:cpu_map_alloc
  - kernel/bpf/cpumap.c:cpu_map_alloc
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
**Symbols:**

```
ffffffff812c8d80-ffffffff812c8d9c: bpf_map_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *bpf_map_area_alloc(u64 size, int numa_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812f0370)
Location: kernel/bpf/syscall.c:310
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_init
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/bloom_filter.c:bloom_map_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
  - kernel/bpf/devmap.c:dev_map_alloc
  - kernel/bpf/devmap.c:dev_map_init_map
  - kernel/bpf/devmap.c:dev_map_init_map
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_alloc
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_alloc
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_alloc
  - net/xdp/xskmap.c:xsk_map_alloc
```
**Symbols:**

```
ffffffff812f0370-ffffffff812f038c: bpf_map_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *bpf_map_area_alloc(u64 size, int numa_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8130f150)
Location: kernel/bpf/syscall.c:311
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_init
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/bloom_filter.c:bloom_map_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
  - kernel/bpf/devmap.c:dev_map_alloc
  - kernel/bpf/devmap.c:dev_map_init_map
  - kernel/bpf/devmap.c:dev_map_init_map
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_alloc
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_alloc
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_alloc
  - net/xdp/xskmap.c:xsk_map_alloc
```
**Symbols:**

```
ffffffff8130f150-ffffffff8130f16c: bpf_map_area_alloc (STB_GLOBAL)
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
void *bpf_map_area_alloc(u64 size, int numa_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffff800010262668)
Location: kernel/bpf/syscall.c:129
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/devmap.c:dev_map_init_map
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
**Symbols:**

```
ffff800010262668-ffff8000102626f0: bpf_map_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *bpf_map_area_alloc(u64 size, int numa_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c04951fc)
Location: kernel/bpf/syscall.c:129
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/devmap.c:dev_map_init_map
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
**Symbols:**

```
c04951fc-c0495274: bpf_map_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *bpf_map_area_alloc(u64 size, int numa_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c0000000003072b0)
Location: kernel/bpf/syscall.c:129
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
**Symbols:**

```
c0000000003072b0-c000000000307378: bpf_map_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *bpf_map_area_alloc(u64 size, int numa_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffe00019f068)
Location: kernel/bpf/syscall.c:129
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/devmap.c:dev_map_init_map
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
**Symbols:**

```
ffffffe00019f068-ffffffe00019f0da: bpf_map_area_alloc (STB_GLOBAL)
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
void *bpf_map_area_alloc(u64 size, int numa_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d8740)
Location: kernel/bpf/syscall.c:129
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
**Symbols:**

```
ffffffff811d8740-ffffffff811d8796: bpf_map_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *bpf_map_area_alloc(u64 size, int numa_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811cb500)
Location: kernel/bpf/syscall.c:129
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
**Symbols:**

```
ffffffff811cb500-ffffffff811cb556: bpf_map_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *bpf_map_area_alloc(u64 size, int numa_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d6510)
Location: kernel/bpf/syscall.c:129
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
**Symbols:**

```
ffffffff811d6510-ffffffff811d6566: bpf_map_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *bpf_map_area_alloc(u64 size, int numa_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e4880)
Location: kernel/bpf/syscall.c:129
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
**Symbols:**

```
ffffffff811e4880-ffffffff811e48d6: bpf_map_area_alloc (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int numa_node</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>size_t size</code> ➡️ <code>u64 size</code>
</li>
</ul>
</details>
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
