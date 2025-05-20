# Function: <code>__alloc_percpu_gfp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *__alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811b1650)
Location: mm/percpu.c:1067
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - lib/percpu-refcount.c:percpu_ref_init
  - lib/percpu_counter.c:__percpu_counter_init
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:tcf_hash_create
  - net/ipv6/route.c:ip6_dst_alloc
```
**Symbols:**

```
ffffffff811b1650-ffffffff811b1664: __alloc_percpu_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *__alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811ca7b0)
Location: mm/percpu.c:1060
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - lib/percpu-refcount.c:percpu_ref_init
  - lib/percpu_counter.c:__percpu_counter_init
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/dst_cache.c:dst_cache_init
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:tcf_hash_create
  - net/ipv6/route.c:ip6_dst_alloc
```
**Symbols:**

```
ffffffff811ca7b0-ffffffff811ca7c4: __alloc_percpu_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *__alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811da8d0)
Location: mm/percpu.c:1064
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - lib/percpu-refcount.c:percpu_ref_init
  - lib/percpu_counter.c:__percpu_counter_init
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/dst_cache.c:dst_cache_init
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:tcf_hash_create
  - net/ipv6/route.c:ip6_dst_alloc
```
**Symbols:**

```
ffffffff811da8d0-ffffffff811da8e4: __alloc_percpu_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *__alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811e3ff0)
Location: mm/percpu.c:1064
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - lib/percpu-refcount.c:percpu_ref_init
  - lib/percpu_counter.c:__percpu_counter_init
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/dst_cache.c:dst_cache_init
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:tcf_hash_create
  - net/ipv6/route.c:ip6_dst_alloc
```
**Symbols:**

```
ffffffff811e3ff0-ffffffff811e4004: __alloc_percpu_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *__alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811faa30)
Location: mm/percpu.c:1524
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - lib/percpu-refcount.c:percpu_ref_init
  - lib/percpu_counter.c:__percpu_counter_init
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/dst_cache.c:dst_cache_init
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv6/route.c:ip6_dst_alloc
```
**Symbols:**

```
ffffffff811faa30-ffffffff811faa44: __alloc_percpu_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *__alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8121b620)
Location: mm/percpu.c:1533
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - lib/percpu-refcount.c:percpu_ref_init
  - lib/percpu_counter.c:__percpu_counter_init
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/dst_cache.c:dst_cache_init
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv6/ip6_fib.c:fib6_info_alloc
```
**Symbols:**

```
ffffffff8121b620-ffffffff8121b634: __alloc_percpu_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *__alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8122e600)
Location: mm/percpu.c:1544
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - lib/percpu-refcount.c:percpu_ref_init
  - lib/percpu_counter.c:__percpu_counter_init
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/dst_cache.c:dst_cache_init
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv6/ip6_fib.c:fib6_info_alloc
```
**Symbols:**

```
ffffffff8122e600-ffffffff8122e614: __alloc_percpu_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *__alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8123ee70)
Location: mm/percpu.c:1781
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - lib/percpu-refcount.c:percpu_ref_init
  - lib/percpu_counter.c:__percpu_counter_init
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/dst_cache.c:dst_cache_init
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff8123ee70-ffffffff8123ee84: __alloc_percpu_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *__alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8124d2d0)
Location: mm/percpu.c:1781
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - lib/percpu-refcount.c:percpu_ref_init
  - lib/percpu_counter.c:__percpu_counter_init
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/dst_cache.c:dst_cache_init
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_traps_register
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff8124d2d0-ffffffff8124d2e4: __alloc_percpu_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *__alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8127b610)
Location: mm/percpu.c:1758
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_init
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - block/blk-cgroup.c:blkg_alloc
  - lib/percpu-refcount.c:percpu_ref_init
  - lib/percpu_counter.c:__percpu_counter_init
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/dst_cache.c:dst_cache_init
  - net/core/devlink.c:devlink_trap_group_register
  - net/core/devlink.c:devlink_trap_register
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff8127b610-ffffffff8127b624: __alloc_percpu_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *__alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81286140)
Location: mm/percpu.c:1891
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:alloc_mem_cgroup_per_node_info
  - mm/memcontrol.c:alloc_mem_cgroup_per_node_info
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-iocost.c:ioc_pd_alloc
  - lib/percpu-refcount.c:percpu_ref_init
  - lib/percpu_counter.c:__percpu_counter_init
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/dst_cache.c:dst_cache_init
  - net/core/devlink.c:devlink_trap_group_register
  - net/core/devlink.c:devlink_trap_register
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff81286140-ffffffff81286154: __alloc_percpu_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *__alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8128ad20)
Location: mm/percpu.c:1892
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-iocost.c:ioc_pd_alloc
  - lib/percpu-refcount.c:percpu_ref_init
  - lib/percpu_counter.c:__percpu_counter_init
  - lib/sbitmap.c:sbitmap_init_node
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/dst_cache.c:dst_cache_init
  - net/core/devlink.c:devlink_trap_groups_register
  - net/core/devlink.c:devlink_traps_register
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/seg6_local.c:parse_nla_counters
```
**Symbols:**

```
ffffffff8128ad20-ffffffff8128ad34: __alloc_percpu_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *__alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812cb0e0)
Location: mm/percpu.c:1935
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-iocost.c:ioc_pd_alloc
  - block/mq-deadline.c:dd_init_sched
  - lib/percpu-refcount.c:percpu_ref_init
  - lib/percpu_counter.c:__percpu_counter_init
  - lib/sbitmap.c:sbitmap_init_node
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/tun.c:tun_net_init
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/dst_cache.c:dst_cache_init
  - net/core/devlink.c:devlink_trap_groups_register
  - net/core/devlink.c:devlink_traps_register
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/seg6_local.c:parse_nla_counters
```
**Symbols:**

```
ffffffff812cb0e0-ffffffff812cb0f4: __alloc_percpu_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *__alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81328ab0)
Location: mm/percpu.c:1935
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-iocost.c:ioc_pd_alloc
  - lib/percpu-refcount.c:percpu_ref_init
  - lib/percpu_counter.c:__percpu_counter_init
  - lib/sbitmap.c:sbitmap_init_node
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/tun.c:tun_net_init
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - net/core/dev.c:netdev_core_stats_alloc
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/dst_cache.c:dst_cache_init
  - net/core/devlink.c:devlink_trap_groups_register
  - net/core/devlink.c:devlink_traps_register
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/fib_semantics.c:fib_nh_common_init
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/seg6_local.c:parse_nla_counters
```
**Symbols:**

```
ffffffff81328ab0-ffffffff81328ad0: __alloc_percpu_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *__alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8139dd00)
Location: mm/percpu.c:1928
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/memalloc.c:bpf_mem_alloc_init
  - kernel/bpf/memalloc.c:bpf_mem_alloc_init
  - kernel/bpf/memalloc.c:__alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - block/blk-cgroup.c:blkcg_css_alloc
  - block/blk-cgroup.c:blkcg_css_alloc
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-iocost.c:ioc_pd_alloc
  - lib/percpu-refcount.c:percpu_ref_init
  - lib/percpu_counter.c:__percpu_counter_init
  - lib/sbitmap.c:sbitmap_init_node
  - drivers/spi/spi.c:spi_alloc_device
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/tun.c:tun_net_init
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - net/core/dev.c:netdev_core_stats_alloc
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/dst_cache.c:dst_cache_init
  - net/core/devlink.c:devl_trap_groups_register
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/fib_semantics.c:fib_nh_common_init
  - net/ipv6/addrconf.c:snmp6_alloc_dev
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/seg6_local.c:parse_nla_counters
```
**Symbols:**

```
ffffffff8139dd00-ffffffff8139dd20: __alloc_percpu_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *__alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813d0e60)
Location: mm/percpu.c:1928
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/memalloc.c:bpf_mem_alloc_init
  - kernel/bpf/memalloc.c:bpf_mem_alloc_init
  - kernel/bpf/memalloc.c:__alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - block/blk-cgroup.c:blkcg_css_alloc
  - block/blk-cgroup.c:blkcg_css_alloc
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-iocost.c:ioc_pd_alloc
  - lib/percpu-refcount.c:percpu_ref_init
  - lib/percpu_counter.c:__percpu_counter_init
  - lib/sbitmap.c:sbitmap_init_node
  - drivers/spi/spi.c:spi_alloc_device
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/tun.c:tun_net_init
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - net/core/dev.c:netdev_core_stats_alloc
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/dst_cache.c:dst_cache_init
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/fib_semantics.c:fib_nh_common_init
  - net/ipv6/addrconf.c:snmp6_alloc_dev
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/seg6_local.c:parse_nla_counters
  - net/devlink/leftover.c:devl_trap_groups_register
```
**Symbols:**

```
ffffffff813d0e60-ffffffff813d0e80: __alloc_percpu_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *__alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813fb800)
Location: mm/percpu.c:1928
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/memalloc.c:bpf_mem_alloc_percpu_init
  - kernel/bpf/memalloc.c:bpf_mem_alloc_init
  - kernel/bpf/memalloc.c:bpf_mem_alloc_init
  - kernel/bpf/memalloc.c:__alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - block/blk-cgroup.c:blkcg_css_alloc
  - block/blk-cgroup.c:blkcg_css_alloc
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-iocost.c:ioc_pd_alloc
  - lib/percpu-refcount.c:percpu_ref_init
  - lib/percpu_counter.c:__percpu_counter_init_many
  - lib/sbitmap.c:sbitmap_init_node
  - drivers/spi/spi.c:spi_alloc_device
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/tun.c:tun_net_init
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - net/core/dev.c:netdev_core_stats_inc
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/dst_cache.c:dst_cache_init
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/fib_semantics.c:fib_nh_common_init
  - net/ipv6/addrconf.c:snmp6_alloc_dev
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/seg6_local.c:parse_nla_counters
  - net/devlink/trap.c:devl_trap_groups_register
```
**Symbols:**

```
ffffffff813fb800-ffffffff813fb820: __alloc_percpu_gfp (STB_GLOBAL)
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
void *__alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffff8000102e3b60)
Location: mm/percpu.c:1781
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - lib/percpu-refcount.c:percpu_ref_init
  - lib/percpu_counter.c:__percpu_counter_init
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/perf/arm_pmu.c:__armpmu_alloc
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/dst_cache.c:dst_cache_init
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_traps_register
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffff8000102e3b60-ffff8000102e3ba8: __alloc_percpu_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *__alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (c0507b90)
Location: mm/percpu.c:1781
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - lib/percpu-refcount.c:percpu_ref_init
  - lib/percpu_counter.c:__percpu_counter_init
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/perf/arm_pmu.c:__armpmu_alloc
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/dst_cache.c:dst_cache_init
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_traps_register
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
c0507b90-c0507bb4: __alloc_percpu_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *__alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (c0000000003a3520)
Location: mm/percpu.c:1781
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - lib/percpu-refcount.c:percpu_ref_init
  - lib/percpu_counter.c:__percpu_counter_init
  - drivers/net/loopback.c:loopback_dev_init
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/dst_cache.c:dst_cache_init
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_traps_register
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
c0000000003a3520-c0000000003a353c: __alloc_percpu_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *__alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffe0001f9c28)
Location: mm/percpu.c:1781
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - lib/percpu-refcount.c:percpu_ref_init
  - lib/percpu_counter.c:__percpu_counter_init
  - drivers/net/loopback.c:loopback_dev_init
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/dst_cache.c:dst_cache_init
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_traps_register
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffe0001f9c28-ffffffe0001f9c64: __alloc_percpu_gfp (STB_GLOBAL)
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
void *__alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81245920)
Location: mm/percpu.c:1781
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - lib/percpu-refcount.c:percpu_ref_init
  - lib/percpu_counter.c:__percpu_counter_init
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/dst_cache.c:dst_cache_init
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_traps_register
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff81245920-ffffffff81245934: __alloc_percpu_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *__alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812388d0)
Location: mm/percpu.c:1781
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - lib/percpu-refcount.c:percpu_ref_init
  - lib/percpu_counter.c:__percpu_counter_init
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/vxlan.c:vxlan_init
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/dst_cache.c:dst_cache_init
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_traps_register
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/ip_tunnel.c:ip_tunnel_init
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff812388d0-ffffffff812388e4: __alloc_percpu_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *__alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812436c0)
Location: mm/percpu.c:1781
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - lib/percpu-refcount.c:percpu_ref_init
  - lib/percpu_counter.c:__percpu_counter_init
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/dst_cache.c:dst_cache_init
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_traps_register
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff812436c0-ffffffff812436d4: __alloc_percpu_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *__alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81252e80)
Location: mm/percpu.c:1781
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - lib/percpu-refcount.c:percpu_ref_init
  - lib/percpu_counter.c:__percpu_counter_init
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/dst_cache.c:dst_cache_init
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_traps_register
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff81252e80-ffffffff81252e94: __alloc_percpu_gfp (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
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
