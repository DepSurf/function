# Function: <code>bpf_map_init_from_attr</code>

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
void bpf_map_init_from_attr(struct bpf_map *map, union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b4e50)
Location: kernel/bpf/syscall.c:161
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
ffffffff811b4e50-ffffffff811b4e89: bpf_map_init_from_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bpf_map_init_from_attr(struct bpf_map *map, union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c31d0)
Location: kernel/bpf/syscall.c:161
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
**Symbols:**

```
ffffffff811c31d0-ffffffff811c320b: bpf_map_init_from_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bpf_map_init_from_attr(struct bpf_map *map, union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d3e00)
Location: kernel/bpf/syscall.c:173
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
**Symbols:**

```
ffffffff811d3e00-ffffffff811d3e3e: bpf_map_init_from_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bpf_map_init_from_attr(struct bpf_map *map, union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e0190)
Location: kernel/bpf/syscall.c:176
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
**Symbols:**

```
ffffffff811e0190-ffffffff811e01ce: bpf_map_init_from_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bpf_map_init_from_attr(struct bpf_map *map, union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fe700)
Location: kernel/bpf/syscall.c:330
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/devmap.c:dev_map_init_map
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
**Symbols:**

```
ffffffff811fe700-ffffffff811fe73e: bpf_map_init_from_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bpf_map_init_from_attr(struct bpf_map *map, union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fd9e0)
Location: kernel/bpf/syscall.c:338
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
**Symbols:**

```
ffffffff811fd9e0-ffffffff811fda1e: bpf_map_init_from_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_map_init_from_attr(struct bpf_map *map, union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fe5a0)
Location: kernel/bpf/syscall.c:339
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
**Symbols:**

```
ffffffff811fe5a0-ffffffff811fe5de: bpf_map_init_from_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_map_init_from_attr(struct bpf_map *map, union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812301e0)
Location: kernel/bpf/syscall.c:358
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
  - kernel/bpf/devmap.c:dev_map_init_map
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
**Symbols:**

```
ffffffff812301e0-ffffffff8123021e: bpf_map_init_from_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_map_init_from_attr(struct bpf_map *map, union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81272b20)
Location: kernel/bpf/syscall.c:364
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/bloom_filter.c:bloom_map_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
  - kernel/bpf/devmap.c:dev_map_init_map
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
**Symbols:**

```
ffffffff81272b20-ffffffff81272b70: bpf_map_init_from_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_map_init_from_attr(struct bpf_map *map, union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812c8e10)
Location: kernel/bpf/syscall.c:364
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/bloom_filter.c:bloom_map_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
  - kernel/bpf/devmap.c:dev_map_init_map
  - kernel/bpf/cpumap.c:cpu_map_alloc
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
**Symbols:**

```
ffffffff812c8e10-ffffffff812c8e60: bpf_map_init_from_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_map_init_from_attr(struct bpf_map *map, union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812f0400)
Location: kernel/bpf/syscall.c:337
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/bloom_filter.c:bloom_map_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
  - kernel/bpf/devmap.c:dev_map_init_map
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_alloc
  - net/xdp/xskmap.c:xsk_map_alloc
```
**Symbols:**

```
ffffffff812f0400-ffffffff812f0450: bpf_map_init_from_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_map_init_from_attr(struct bpf_map *map, union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8130f1e0)
Location: kernel/bpf/syscall.c:338
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/bloom_filter.c:bloom_map_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
  - kernel/bpf/devmap.c:dev_map_init_map
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_alloc
  - net/xdp/xskmap.c:xsk_map_alloc
```
**Symbols:**

```
ffffffff8130f1e0-ffffffff8130f230: bpf_map_init_from_attr (STB_GLOBAL)
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
void bpf_map_init_from_attr(struct bpf_map *map, union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffff800010262720)
Location: kernel/bpf/syscall.c:176
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/devmap.c:dev_map_init_map
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
**Symbols:**

```
ffff800010262720-ffff80001026278c: bpf_map_init_from_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bpf_map_init_from_attr(struct bpf_map *map, union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c0495290)
Location: kernel/bpf/syscall.c:176
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/devmap.c:dev_map_init_map
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
**Symbols:**

```
c0495290-c04952e8: bpf_map_init_from_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bpf_map_init_from_attr(struct bpf_map *map, union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c0000000003073c0)
Location: kernel/bpf/syscall.c:176
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
**Symbols:**

```
c0000000003073c0-c000000000307418: bpf_map_init_from_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bpf_map_init_from_attr(struct bpf_map *map, union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffe00019f104)
Location: kernel/bpf/syscall.c:176
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/devmap.c:dev_map_init_map
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
**Symbols:**

```
ffffffe00019f104-ffffffe00019f15a: bpf_map_init_from_attr (STB_GLOBAL)
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
void bpf_map_init_from_attr(struct bpf_map *map, union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d87b0)
Location: kernel/bpf/syscall.c:176
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
**Symbols:**

```
ffffffff811d87b0-ffffffff811d87ee: bpf_map_init_from_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bpf_map_init_from_attr(struct bpf_map *map, union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811cb570)
Location: kernel/bpf/syscall.c:176
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
**Symbols:**

```
ffffffff811cb570-ffffffff811cb5ae: bpf_map_init_from_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bpf_map_init_from_attr(struct bpf_map *map, union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d6580)
Location: kernel/bpf/syscall.c:176
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
**Symbols:**

```
ffffffff811d6580-ffffffff811d65be: bpf_map_init_from_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bpf_map_init_from_attr(struct bpf_map *map, union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e48f0)
Location: kernel/bpf/syscall.c:176
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
**Symbols:**

```
ffffffff811e48f0-ffffffff811e492e: bpf_map_init_from_attr (STB_GLOBAL)
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
