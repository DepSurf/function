# Function: <code>__get_random_u32_below</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 __get_random_u32_below(u32 ceil);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81a93b50)
Location: drivers/char/random.c:535
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/cgroup/cpuset.c:node_random
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:set_cluster_next
  - mm/slub.c:shuffle_freelist
  - mm/memory-tiers.c:next_demotion_node
  - fs/ext4/ialloc.c:find_group_orlov
  - lib/sbitmap.c:__sbitmap_queue_get_batch
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get
  - lib/sbitmap.c:sbitmap_init_node
  - drivers/pci/p2pdma.c:pci_p2pmem_find_many
  - net/core/neighbour.c:neigh_proc_base_reachable_time
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_periodic_work
  - net/ipv4/route.c:__ip_select_ident
  - net/ipv4/tcp_input.c:tcp_send_challenge_ack
  - net/ipv4/tcp_plb.c:tcp_plb_update_state_upon_rto
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff81a93b50-ffffffff81a93bbb: __get_random_u32_below (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 __get_random_u32_below(u32 ceil);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81adf640)
Location: drivers/char/random.c:535
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - mm/slab_common.c:cache_random_seq_create
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:set_cluster_next
  - mm/slub.c:shuffle_freelist
  - mm/memory-tiers.c:next_demotion_node
  - fs/ext4/ialloc.c:find_group_orlov
  - lib/sbitmap.c:__sbitmap_queue_get_batch
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get
  - lib/sbitmap.c:sbitmap_init_node
  - drivers/pci/p2pdma.c:pci_p2pmem_find_many
  - net/core/neighbour.c:neigh_proc_base_reachable_time
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_periodic_work
  - net/ipv4/route.c:__ip_select_ident
  - net/ipv4/tcp_input.c:tcp_send_challenge_ack
  - net/ipv4/tcp_plb.c:tcp_plb_update_state_upon_rto
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff81adf640-ffffffff81adf6aa: __get_random_u32_below (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 __get_random_u32_below(u32 ceil);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81b32a60)
Location: drivers/char/random.c:535
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - mm/slab_common.c:cache_random_seq_create
  - mm/slub.c:shuffle_freelist
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:set_cluster_next
  - mm/memory-tiers.c:next_demotion_node
  - fs/ext4/ialloc.c:find_group_orlov
  - lib/sbitmap.c:__sbitmap_queue_get_batch
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get
  - lib/sbitmap.c:sbitmap_init_node
  - drivers/pci/p2pdma.c:pci_p2pmem_find_many
  - net/core/neighbour.c:neigh_proc_base_reachable_time
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_periodic_work
  - net/ipv4/route.c:__ip_select_ident
  - net/ipv4/tcp_input.c:tcp_send_challenge_ack
  - net/ipv4/tcp_plb.c:tcp_plb_update_state_upon_rto
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_start_timer
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff81b32a60-ffffffff81b32aca: __get_random_u32_below (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
