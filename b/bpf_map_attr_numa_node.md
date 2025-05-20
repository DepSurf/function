# Function: <code>bpf_map_attr_numa_node</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8119fe0f)
Location: include/linux/bpf.h:426
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/bpf/hashtab.c (ffffffff811ab953)
Location: include/linux/bpf.h:426
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff811ac95f)
Location: include/linux/bpf.h:426
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/lpm_trie.c (ffffffff811ae816)
Location: include/linux/bpf.h:426
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffff811af466)
Location: include/linux/bpf.h:426
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff811afa9a)
Location: include/linux/bpf.h:426
Inline: True
```
```
In kernel/bpf/sockmap.c (ffffffff811b0f56)
Location: include/linux/bpf.h:426
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff811b1d04)
Location: include/linux/bpf.h:426
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b5165)
Location: include/linux/bpf.h:508
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_init_from_attr
```
```
In kernel/bpf/hashtab.c (ffffffff811c126e)
Location: include/linux/bpf.h:508
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/arraymap.c (ffffffff811c3f3e)
Location: include/linux/bpf.h:508
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc_check
```
```
In kernel/bpf/stackmap.c (ffffffff811d0ad5)
Location: include/linux/bpf.h:508
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c40d9)
Location: include/linux/bpf.h:581
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_map_init_from_attr
```
```
In kernel/bpf/hashtab.c (ffffffff811d2a6c)
Location: include/linux/bpf.h:581
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/arraymap.c (ffffffff811d5b3e)
Location: include/linux/bpf.h:581
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc_check
```
```
In kernel/bpf/local_storage.c (ffffffff811d7e88)
Location: include/linux/bpf.h:581
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
```
```
In kernel/bpf/queue_stack_maps.c (ffffffff811d8c25)
Location: include/linux/bpf.h:581
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
```
```
In kernel/bpf/stackmap.c (ffffffff811e05b5)
Location: include/linux/bpf.h:581
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In kernel/bpf/reuseport_array.c (ffffffff811e2795)
Location: include/linux/bpf.h:581
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d42f8)
Location: include/linux/bpf.h:730
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_init_from_attr
```
```
In kernel/bpf/hashtab.c (ffffffff811e71ac)
Location: include/linux/bpf.h:730
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/arraymap.c (ffffffff811ea4fd)
Location: include/linux/bpf.h:730
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc_check
```
```
In kernel/bpf/local_storage.c (ffffffff811ec847)
Location: include/linux/bpf.h:730
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
```
```
In kernel/bpf/queue_stack_maps.c (ffffffff811ed786)
Location: include/linux/bpf.h:730
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
```
```
In kernel/bpf/stackmap.c (ffffffff811f61bd)
Location: include/linux/bpf.h:730
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In kernel/bpf/reuseport_array.c (ffffffff811f9925)
Location: include/linux/bpf.h:730
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
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
In kernel/bpf/syscall.c (ffffffff811e09f8)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_init_from_attr
```
```
In kernel/bpf/hashtab.c (ffffffff811f390c)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/arraymap.c (ffffffff811f6c5d)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc_check
```
```
In kernel/bpf/local_storage.c (ffffffff811f8f97)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
```
```
In kernel/bpf/queue_stack_maps.c (ffffffff811f9e96)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
```
```
In kernel/bpf/stackmap.c (ffffffff8120317d)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In kernel/bpf/reuseport_array.c (ffffffff812069f5)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
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
In kernel/bpf/syscall.c (ffffffff811fec05)
Location: include/linux/bpf.h:1261
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_init_from_attr
```
```
In kernel/bpf/hashtab.c (ffffffff8121710c)
Location: include/linux/bpf.h:1261
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/arraymap.c (ffffffff8121ab03)
Location: include/linux/bpf.h:1261
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:fd_array_map_alloc_check
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/local_storage.c (ffffffff8121cd97)
Location: include/linux/bpf.h:1261
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
```
```
In kernel/bpf/queue_stack_maps.c (ffffffff8121dd06)
Location: include/linux/bpf.h:1261
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
```
```
In kernel/bpf/stackmap.c (ffffffff8122afd6)
Location: include/linux/bpf.h:1261
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In kernel/bpf/reuseport_array.c (ffffffff8122efa7)
Location: include/linux/bpf.h:1261
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
```
In net/xdp/xskmap.c (ffffffff81ba8fa3)
Location: include/linux/bpf.h:1261
Inline: True
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
In kernel/bpf/syscall.c (ffffffff811fdf25)
Location: include/linux/bpf.h:1450
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_init_from_attr
```
```
In kernel/bpf/hashtab.c (ffffffff812193dc)
Location: include/linux/bpf.h:1450
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/arraymap.c (ffffffff8121d34c)
Location: include/linux/bpf.h:1450
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc_check
```
```
In kernel/bpf/local_storage.c (ffffffff8121fbb5)
Location: include/linux/bpf.h:1450
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
```
```
In kernel/bpf/queue_stack_maps.c (ffffffff81220af5)
Location: include/linux/bpf.h:1450
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
```
```
In kernel/bpf/stackmap.c (ffffffff81232eff)
Location: include/linux/bpf.h:1450
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In kernel/bpf/reuseport_array.c (ffffffff81237505)
Location: include/linux/bpf.h:1450
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
```
In net/xdp/xskmap.c (ffffffff81bb8808)
Location: include/linux/bpf.h:1450
Inline: True
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
In kernel/bpf/syscall.c (ffffffff811fe9b5)
Location: include/linux/bpf.h:1513
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_init_from_attr
```
```
In kernel/bpf/hashtab.c (ffffffff8121cddc)
Location: include/linux/bpf.h:1513
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/arraymap.c (ffffffff81220e5c)
Location: include/linux/bpf.h:1513
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc_check
```
```
In kernel/bpf/local_storage.c (ffffffff81223635)
Location: include/linux/bpf.h:1513
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
```
```
In kernel/bpf/queue_stack_maps.c (ffffffff81224585)
Location: include/linux/bpf.h:1513
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
```
```
In kernel/bpf/stackmap.c (ffffffff8123709f)
Location: include/linux/bpf.h:1513
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In kernel/bpf/reuseport_array.c (ffffffff8123bd25)
Location: include/linux/bpf.h:1513
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
```
In net/xdp/xskmap.c (ffffffff81ba7a38)
Location: include/linux/bpf.h:1513
Inline: True
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
In kernel/bpf/syscall.c (ffffffff812305f5)
Location: include/linux/bpf.h:1606
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_init_from_attr
```
```
In kernel/bpf/hashtab.c (ffffffff81253dac)
Location: include/linux/bpf.h:1606
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/arraymap.c (ffffffff8125881c)
Location: include/linux/bpf.h:1606
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc_check
```
```
In kernel/bpf/local_storage.c (ffffffff8125b455)
Location: include/linux/bpf.h:1606
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
```
```
In kernel/bpf/queue_stack_maps.c (ffffffff8125c4c5)
Location: include/linux/bpf.h:1606
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
```
```
In kernel/bpf/stackmap.c (ffffffff8127168c)
Location: include/linux/bpf.h:1606
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In kernel/bpf/reuseport_array.c (ffffffff812766b5)
Location: include/linux/bpf.h:1606
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
```
In net/xdp/xskmap.c (ffffffff81c756c8)
Location: include/linux/bpf.h:1606
Inline: True
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
In kernel/bpf/syscall.c (ffffffff81273565)
Location: include/linux/bpf.h:1728
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_init_from_attr
```
```
In kernel/bpf/hashtab.c (ffffffff8129c29c)
Location: include/linux/bpf.h:1728
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/arraymap.c (ffffffff812a162c)
Location: include/linux/bpf.h:1728
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc_check
```
```
In kernel/bpf/bloom_filter.c (ffffffff812a48a5)
Location: include/linux/bpf.h:1728
Inline: True
Inline callers:
  - kernel/bpf/bloom_filter.c:bloom_map_alloc
```
```
In kernel/bpf/local_storage.c (ffffffff812a4ef5)
Location: include/linux/bpf.h:1728
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
```
```
In kernel/bpf/queue_stack_maps.c (ffffffff812a6185)
Location: include/linux/bpf.h:1728
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
```
```
In kernel/bpf/stackmap.c (ffffffff812c07f0)
Location: include/linux/bpf.h:1728
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In kernel/bpf/reuseport_array.c (ffffffff812c6125)
Location: include/linux/bpf.h:1728
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
```
In net/xdp/xskmap.c (ffffffff81e198fd)
Location: include/linux/bpf.h:1728
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812c9cc5)
Location: include/linux/bpf.h:2105
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_init_from_attr
```
```
In kernel/bpf/hashtab.c (ffffffff812f84dc)
Location: include/linux/bpf.h:2105
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/arraymap.c (ffffffff812fe88c)
Location: include/linux/bpf.h:2105
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc_check
```
```
In kernel/bpf/bloom_filter.c (ffffffff813025e5)
Location: include/linux/bpf.h:2105
Inline: True
Inline callers:
  - kernel/bpf/bloom_filter.c:bloom_map_alloc
```
```
In kernel/bpf/local_storage.c (ffffffff81302c75)
Location: include/linux/bpf.h:2105
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
```
```
In kernel/bpf/queue_stack_maps.c (ffffffff81303f75)
Location: include/linux/bpf.h:2105
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
```
```
In kernel/bpf/stackmap.c (ffffffff81324080)
Location: include/linux/bpf.h:2105
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In kernel/bpf/reuseport_array.c (ffffffff8132b875)
Location: include/linux/bpf.h:2105
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
```
In net/xdp/xskmap.c (ffffffff81ff0c8d)
Location: include/linux/bpf.h:2105
Inline: True
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
In kernel/bpf/syscall.c (ffffffff812f14c5)
Location: include/linux/bpf.h:2241
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_init_from_attr
```
```
In kernel/bpf/hashtab.c (ffffffff8132652c)
Location: include/linux/bpf.h:2241
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/arraymap.c (ffffffff8132d47c)
Location: include/linux/bpf.h:2241
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc_check
```
```
In kernel/bpf/bloom_filter.c (ffffffff813313a5)
Location: include/linux/bpf.h:2241
Inline: True
Inline callers:
  - kernel/bpf/bloom_filter.c:bloom_map_alloc
```
```
In kernel/bpf/local_storage.c (ffffffff81331715)
Location: include/linux/bpf.h:2241
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
```
```
In kernel/bpf/queue_stack_maps.c (ffffffff813329a5)
Location: include/linux/bpf.h:2241
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
```
```
In kernel/bpf/stackmap.c (ffffffff813542f6)
Location: include/linux/bpf.h:2241
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In kernel/bpf/reuseport_array.c (ffffffff8135ba25)
Location: include/linux/bpf.h:2241
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
```
In net/xdp/xskmap.c (ffffffff8206ce78)
Location: include/linux/bpf.h:2241
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_alloc
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
In kernel/bpf/syscall.c (ffffffff813102f5)
Location: include/linux/bpf.h:2400
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_init_from_attr
```
```
In kernel/bpf/hashtab.c (ffffffff8134ab6c)
Location: include/linux/bpf.h:2400
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/arraymap.c (ffffffff8135181c)
Location: include/linux/bpf.h:2400
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc_check
```
```
In kernel/bpf/bloom_filter.c (ffffffff81355945)
Location: include/linux/bpf.h:2400
Inline: True
Inline callers:
  - kernel/bpf/bloom_filter.c:bloom_map_alloc
```
```
In kernel/bpf/local_storage.c (ffffffff81355cb5)
Location: include/linux/bpf.h:2400
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
```
```
In kernel/bpf/queue_stack_maps.c (ffffffff81356f75)
Location: include/linux/bpf.h:2400
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
```
```
In kernel/bpf/stackmap.c (ffffffff8137cc66)
Location: include/linux/bpf.h:2400
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In kernel/bpf/reuseport_array.c (ffffffff813846b5)
Location: include/linux/bpf.h:2400
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
```
In net/xdp/xskmap.c (ffffffff82140d18)
Location: include/linux/bpf.h:2400
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_alloc
```
</details>
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
In kernel/bpf/syscall.c (ffff800010263010)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_init_from_attr
```
```
In kernel/bpf/hashtab.c (ffff800010277ca8)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/arraymap.c (ffff80001027b384)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc_check
```
```
In kernel/bpf/local_storage.c (ffff80001027e5e8)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
```
```
In kernel/bpf/queue_stack_maps.c (ffff80001027f740)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
```
```
In kernel/bpf/stackmap.c (ffff80001028b888)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In kernel/bpf/reuseport_array.c (ffff8000102901a0)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
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
In kernel/bpf/syscall.c (c0495bf4)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_init_from_attr
```
```
In kernel/bpf/hashtab.c (c04aa0c0)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/arraymap.c (c04ad3bc)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc_check
```
```
In kernel/bpf/local_storage.c (c04b0044)
Location: include/linux/bpf.h:734
Inline: True
```
```
In kernel/bpf/queue_stack_maps.c (c04b0c3c)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
```
```
In kernel/bpf/stackmap.c (c04baf6c)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In kernel/bpf/reuseport_array.c (c04bf7d8)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
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
In kernel/bpf/syscall.c (c0000000003081c4)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_init_from_attr
```
```
In kernel/bpf/hashtab.c (c000000000320040)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/arraymap.c (c000000000324bb0)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc_check
```
```
In kernel/bpf/local_storage.c (c000000000328494)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
```
```
In kernel/bpf/queue_stack_maps.c (c000000000329c9c)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
```
```
In kernel/bpf/stackmap.c (c00000000033782c)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In kernel/bpf/reuseport_array.c (c00000000033cf94)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
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
In kernel/bpf/syscall.c (ffffffe00019f97e)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_init_from_attr
```
```
In kernel/bpf/hashtab.c (ffffffe0001af87a)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/arraymap.c (ffffffe0001b312c)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc_check
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/bpf.h:734
Inline: True
```
```
In kernel/bpf/queue_stack_maps.c (ffffffe0001b64de)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
```
```
In kernel/bpf/stackmap.c (ffffffe0001bf4ac)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In kernel/bpf/reuseport_array.c (ffffffe0001c2d64)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
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
In kernel/bpf/syscall.c (ffffffff811d9018)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_init_from_attr
```
```
In kernel/bpf/hashtab.c (ffffffff811ebf2c)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/arraymap.c (ffffffff811ef27d)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc_check
```
```
In kernel/bpf/local_storage.c (ffffffff811f15b7)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
```
```
In kernel/bpf/queue_stack_maps.c (ffffffff811f24b6)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
```
```
In kernel/bpf/stackmap.c (ffffffff811fb79d)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In kernel/bpf/reuseport_array.c (ffffffff811ff015)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
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
In kernel/bpf/syscall.c (ffffffff811cbdd8)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_init_from_attr
```
```
In kernel/bpf/hashtab.c (ffffffff811decbc)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/arraymap.c (ffffffff811e200d)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc_check
```
```
In kernel/bpf/local_storage.c (ffffffff811e4307)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
```
```
In kernel/bpf/queue_stack_maps.c (ffffffff811e5206)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
```
```
In kernel/bpf/stackmap.c (ffffffff811ee4ed)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In kernel/bpf/reuseport_array.c (ffffffff811f1d65)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
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
In kernel/bpf/syscall.c (ffffffff811d6de8)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_init_from_attr
```
```
In kernel/bpf/hashtab.c (ffffffff811e9cfc)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/arraymap.c (ffffffff811ed04d)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc_check
```
```
In kernel/bpf/local_storage.c (ffffffff811ef387)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
```
```
In kernel/bpf/queue_stack_maps.c (ffffffff811f0286)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
```
```
In kernel/bpf/stackmap.c (ffffffff811f956d)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In kernel/bpf/reuseport_array.c (ffffffff811fcde5)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
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
In kernel/bpf/syscall.c (ffffffff811e5158)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_init_from_attr
```
```
In kernel/bpf/hashtab.c (ffffffff811f80cc)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/arraymap.c (ffffffff811fb4fd)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc_check
```
```
In kernel/bpf/local_storage.c (ffffffff811fd857)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
```
```
In kernel/bpf/queue_stack_maps.c (ffffffff811fe796)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
```
```
In kernel/bpf/stackmap.c (ffffffff8120800d)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In kernel/bpf/reuseport_array.c (ffffffff8120ba95)
Location: include/linux/bpf.h:734
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
</details>
</li>
</ul>

## Differences
