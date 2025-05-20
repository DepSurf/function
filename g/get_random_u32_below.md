# Function: <code>get_random_u32_below</code>

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
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 get_random_u32_below(u32 ceil);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004dfa)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
```
```
In arch/x86/kernel/process.c (ffffffff8105f6eb)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_align_stack
```
```
In arch/x86/kernel/module.c (ffffffff810b194f)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - arch/x86/kernel/module.c:module_alloc
```
```
In arch/x86/mm/cpu_entry_area.c (0)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:init_cea_offsets
```
```
In kernel/time/clocksource.c (ffffffff811e0ab7)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/cgroup/cpuset.c (ffffffff81217972)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:node_random
```
```
In kernel/bpf/core.c (ffffffff812c4342)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In mm/swapfile.c (ffffffff813fcc93)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:set_cluster_next
```
```
In mm/slub.c (ffffffff81426dea)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - mm/slub.c:shuffle_freelist
```
```
In mm/kfence/core.c (ffffffff8142f015)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In mm/memory-tiers.c (ffffffff81437977)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - mm/memory-tiers.c:next_demotion_node
```
```
In fs/ext4/ialloc.c (ffffffff8156dcbe)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/mmp.c (ffffffff81598a8b)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
```
```
In fs/ext4/super.c (0)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_register_li_request
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In lib/sbitmap.c (ffffffff818a437e)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_queue_get_batch
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get
  - lib/sbitmap.c:sbitmap_init_node
```
```
In drivers/pci/p2pdma.c (ffffffff8191d028)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pmem_find_many
```
```
In net/core/stream.c (ffffffff81db11e1)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/core/neighbour.c (ffffffff81dd8dd2)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_base_reachable_time
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_periodic_work
```
```
In net/netlink/af_netlink.c (ffffffff81e6a3e1)
Location: include/linux/random.h:60
Inline: True
```
```
In net/ipv4/route.c (ffffffff81e8ea98)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea547e)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea7eba)
Location: include/linux/random.h:60
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81eb57d9)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_send_challenge_ack
```
```
In net/ipv4/tcp_plb.c (ffffffff81edb718)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/ipv4/tcp_plb.c:tcp_plb_update_state_upon_rto
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_global_allow
```
```
In net/ipv4/igmp.c (ffffffff81ef913e)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3dd47)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
```
```
In net/ipv6/addrconf.c (ffffffff81f6a372)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
```
```
In net/ipv6/route.c (ffffffff81f6f881)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/mcast.c (ffffffff81f952f9)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
Direct callers:
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_select_ident
```
```
In net/packet/af_packet.c (ffffffff81fc69aa)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff81f91d70-ffffffff81f91d81: get_random_u32_below (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 get_random_u32_below(u32 ceil);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004602)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
```
```
In arch/x86/kernel/process.c (ffffffff81060e4b)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_align_stack
```
```
In arch/x86/kernel/module.c (ffffffff810b498f)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - arch/x86/kernel/module.c:module_alloc
```
```
In arch/x86/mm/cpu_entry_area.c (0)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:init_cea_offsets
```
```
In kernel/sched/fair.c (ffffffff81163944)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_cfs_bandwidth
```
```
In kernel/time/clocksource.c (ffffffff811f5017)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/cgroup/cpuset.c (ffffffff81234e3b)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
```
```
In kernel/bpf/core.c (ffffffff812eb2f2)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In mm/vmscan.c (ffffffff813b7eef)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_many
  - mm/vmscan.c:lru_gen_online_memcg
  - mm/vmscan.c:lru_gen_rotate_memcg
```
```
In mm/slab_common.c (ffffffff813d5d36)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/swapfile.c (ffffffff8142ff6f)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:set_cluster_next
```
```
In mm/slub.c (ffffffff8145cb9a)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - mm/slub.c:shuffle_freelist
```
```
In mm/kfence/core.c (ffffffff81464d25)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In mm/memory-tiers.c (ffffffff8146d637)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - mm/memory-tiers.c:next_demotion_node
```
```
In fs/ext4/ialloc.c (ffffffff815a5ba0)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/mmp.c (ffffffff815cf6da)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
```
```
In fs/ext4/super.c (0)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_register_li_request
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In lib/sbitmap.c (ffffffff818e680e)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_queue_get_batch
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get
  - lib/sbitmap.c:sbitmap_init_node
```
```
In drivers/pci/p2pdma.c (ffffffff819605e8)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pmem_find_many
```
```
In net/core/stream.c (ffffffff81e216ea)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/core/neighbour.c (ffffffff81e499e2)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_base_reachable_time
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_periodic_work
```
```
In net/netlink/af_netlink.c (ffffffff81ec63b0)
Location: include/linux/random.h:60
Inline: True
```
```
In net/ipv4/route.c (ffffffff81eed189)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f03c06)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f06701)
Location: include/linux/random.h:60
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81f13c09)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_send_challenge_ack
```
```
In net/ipv4/tcp_plb.c (ffffffff81f3a7d8)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/ipv4/tcp_plb.c:tcp_plb_update_state_upon_rto
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_global_allow
```
```
In net/ipv4/igmp.c (ffffffff81f58cee)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9d69d)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
```
```
In net/ipv6/addrconf.c (ffffffff81fca3b2)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
```
```
In net/ipv6/route.c (ffffffff81fcf964)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/mcast.c (ffffffff81ff5ca0)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
Direct callers:
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_select_ident
```
```
In net/packet/af_packet.c (ffffffff820276b9)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff81ff2690-ffffffff81ff26a1: get_random_u32_below (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 get_random_u32_below(u32 ceil);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81006f12)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
```
```
In arch/x86/kernel/process.c (ffffffff81067efb)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_align_stack
```
```
In arch/x86/kernel/module.c (ffffffff810bbdef)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - arch/x86/kernel/module.c:module_alloc
```
```
In arch/x86/mm/cpu_entry_area.c (0)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:init_cea_offsets
```
```
In kernel/sched/fair.c (ffffffff81170697)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_cfs_bandwidth
```
```
In kernel/time/clocksource.c (ffffffff8120b1b7)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/cgroup/cpuset.c (ffffffff8124ea5b)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
```
```
In kernel/bpf/core.c (ffffffff81309815)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In mm/vmscan.c (ffffffff813e0e4b)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_many
  - mm/vmscan.c:lru_gen_online_memcg
  - mm/vmscan.c:lru_gen_rotate_memcg
```
```
In mm/slab_common.c (ffffffff813ffa06)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/slub.c (ffffffff814572aa)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - mm/slub.c:shuffle_freelist
```
```
In mm/swapfile.c (ffffffff81469a10)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:set_cluster_next
```
```
In mm/kfence/core.c (ffffffff81493975)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In mm/memory-tiers.c (ffffffff8149c7a7)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - mm/memory-tiers.c:next_demotion_node
```
```
In fs/ext4/ialloc.c (ffffffff815dea10)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/mmp.c (ffffffff81607f6a)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
```
```
In fs/ext4/super.c (0)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_register_li_request
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In lib/sbitmap.c (ffffffff8192d82e)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_queue_get_batch
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get
  - lib/sbitmap.c:sbitmap_init_node
```
```
In drivers/pci/p2pdma.c (ffffffff819a9d07)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pmem_find_many
```
```
In net/core/stream.c (ffffffff81edf47b)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/core/neighbour.c (ffffffff81f08702)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_base_reachable_time
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_periodic_work
```
```
In net/netlink/af_netlink.c (ffffffff81f89621)
Location: include/linux/random.h:60
Inline: True
```
```
In net/ipv4/route.c (ffffffff81fb1219)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc7eb3)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fca9e6)
Location: include/linux/random.h:60
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81fd80ea)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_send_challenge_ack
```
```
In net/ipv4/tcp_plb.c (ffffffff82000798)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/ipv4/tcp_plb.c:tcp_plb_update_state_upon_rto
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_global_allow
```
```
In net/ipv4/igmp.c (ffffffff8201f1bc)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_start_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff8206a9fd)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
```
```
In net/ipv6/addrconf.c (ffffffff82097b52)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
```
```
In net/ipv6/route.c (ffffffff8209d1f3)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/mcast.c (ffffffff820c38b0)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
Direct callers:
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_select_ident
```
```
In net/packet/af_packet.c (ffffffff820f6f19)
Location: include/linux/random.h:60
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff820c02f0-ffffffff820c0301: get_random_u32_below (STB_LOCAL)
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
