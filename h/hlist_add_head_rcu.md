# Function: <code>hlist_add_head_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff8109e503)
Location: include/linux/rculist.h:392
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:change_pid
```
```
In kernel/time/posix-timers.c (ffffffff810f1599)
Location: include/linux/rculist.h:392
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:SyS_timer_create
```
```
In kernel/kprobes.c (ffffffff8112ee42)
Location: include/linux/rculist.h:392
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff81142984)
Location: include/linux/rculist.h:392
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:profile_graph_entry
  - kernel/trace/ftrace.c:register_ftrace_function_probe
```
```
In kernel/trace/trace_event_perf.c (ffffffff81162948)
Location: include/linux/rculist.h:392
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_add
```
```
In kernel/bpf/hashtab.c (ffffffff8117797c)
Location: include/linux/rculist.h:392
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
```
In kernel/events/core.c (ffffffff81180434)
Location: include/linux/rculist.h:392
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
```
```
In fs/namespace.c (ffffffff8122cccc)
Location: include/linux/rculist.h:392
Inline: True
Inline callers:
  - fs/namespace.c:attach_mnt
```
```
In fs/notify/mark.c (ffffffff812507dc)
Location: include/linux/rculist.h:392
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In security/selinux/avc.c (ffffffff8134094e)
Location: include/linux/rculist.h:392
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_compute_av
```
```
In security/smack/smack_access.c (ffffffff813628ec)
Location: include/linux/rculist.h:392
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/integrity/ima/ima_queue.c (ffffffff813971f9)
Location: include/linux/rculist.h:392
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
```
In block/blk-cgroup.c (ffffffff813d7d9b)
Location: include/linux/rculist.h:392
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/net/tun.c (ffffffff815ef4e1)
Location: include/linux/rculist.h:392
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/dev.c (ffffffff81716b06)
Location: include/linux/rculist.h:392
Inline: True
Inline callers:
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:dev_change_name
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177c006)
Location: include/linux/rculist.h:392
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff817912bb)
Location: include/linux/rculist.h:392
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/fib_frontend.c (ffffffff8179a69c)
Location: include/linux/rculist.h:392
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_new_table
```
```
In net/ipv4/fib_trie.c (ffffffff817a03b5)
Location: include/linux/rculist.h:392
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrconf.c (ffffffff817ca74a)
Location: include/linux/rculist.h:392
Inline: True
```
```
In net/ipv6/addrlabel.c (ffffffff817d2b31)
Location: include/linux/rculist.h:392
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/ip6_fib.c (ffffffff817da83f)
Location: include/linux/rculist.h:392
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_init
  - net/ipv6/ip6_fib.c:fib6_net_init
  - net/ipv6/ip6_fib.c:fib6_new_table
```
```
In net/packet/af_packet.c (ffffffff81804096)
Location: include/linux/rculist.h:392
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a1d23)
Location: include/linux/rculist.h:478
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
  - kernel/pid.c:alloc_pid
```
```
In kernel/time/posix-timers.c (ffffffff810f85cc)
Location: include/linux/rculist.h:478
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:SyS_timer_create
```
```
In kernel/kprobes.c (ffffffff81137281)
Location: include/linux/rculist.h:478
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff8114dc1e)
Location: include/linux/rculist.h:478
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:profile_graph_entry
```
```
In kernel/trace/trace_event_perf.c (ffffffff8116d118)
Location: include/linux/rculist.h:478
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_add
```
```
In kernel/bpf/hashtab.c (ffffffff81186995)
Location: include/linux/rculist.h:478
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
```
In kernel/events/core.c (ffffffff81192183)
Location: include/linux/rculist.h:478
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
```
```
In fs/namespace.c (ffffffff8125655c)
Location: include/linux/rculist.h:478
Inline: True
Inline callers:
  - fs/namespace.c:attach_mnt
```
```
In fs/notify/mark.c (ffffffff81278e66)
Location: include/linux/rculist.h:478
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In security/selinux/avc.c (ffffffff81375ff8)
Location: include/linux/rculist.h:478
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_compute_av
```
```
In security/smack/smack_access.c (ffffffff81398abe)
Location: include/linux/rculist.h:478
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/integrity/ima/ima_queue.c (ffffffff813d3256)
Location: include/linux/rculist.h:478
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
```
In block/blk-cgroup.c (ffffffff8141da62)
Location: include/linux/rculist.h:478
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/net/tun.c (ffffffff8164e042)
Location: include/linux/rculist.h:478
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/dev.c (ffffffff81785e27)
Location: include/linux/rculist.h:478
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:list_netdevice
```
```
In net/ipv4/inet_hashtables.c (ffffffff817cf149)
Location: include/linux/rculist.h:478
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817e984b)
Location: include/linux/rculist.h:478
Inline: True
```
```
In net/ipv4/udp.c (ffffffff817f3f91)
Location: include/linux/rculist.h:478
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/devinet.c (ffffffff817fe5fb)
Location: include/linux/rculist.h:478
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/fib_frontend.c (ffffffff818075ff)
Location: include/linux/rculist.h:478
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_new_table
```
```
In net/ipv4/fib_trie.c (ffffffff8180df95)
Location: include/linux/rculist.h:478
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrconf.c (ffffffff8183794e)
Location: include/linux/rculist.h:478
Inline: True
```
```
In net/ipv6/addrlabel.c (ffffffff8184052b)
Location: include/linux/rculist.h:478
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/ip6_fib.c (ffffffff81848cd8)
Location: include/linux/rculist.h:478
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_init
  - net/ipv6/ip6_fib.c:fib6_net_init
  - net/ipv6/ip6_fib.c:fib6_new_table
```
```
In net/packet/af_packet.c (ffffffff8187507f)
Location: include/linux/rculist.h:478
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_create
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a6de3)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
  - kernel/pid.c:alloc_pid
```
```
In kernel/time/posix-timers.c (ffffffff81105f5c)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:SyS_timer_create
```
```
In kernel/kprobes.c (ffffffff81141001)
Location: include/linux/rculist.h:476
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff81157b6e)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:profile_graph_entry
```
```
In kernel/trace/trace_event_perf.c (ffffffff811783e8)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_add
```
```
In kernel/bpf/hashtab.c (ffffffff81194e1f)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
```
In kernel/events/core.c (ffffffff811a1933)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
```
```
In fs/namespace.c (ffffffff8126700f)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - fs/namespace.c:__attach_mnt
```
```
In fs/notify/mark.c (ffffffff8128ca96)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In security/selinux/avc.c (ffffffff8138c928)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_compute_av
```
```
In security/smack/smack_access.c (ffffffff813af69e)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/integrity/ima/ima_queue.c (ffffffff813ea8ed)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In block/blk-cgroup.c (ffffffff81439022)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/net/tun.c (ffffffff8167fd6e)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/dev.c (ffffffff817ab7e7)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:list_netdevice
```
```
In net/sched/sch_api.c (ffffffff817df707)
Location: include/linux/rculist.h:476
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff817fef63)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81819afb)
Location: include/linux/rculist.h:476
Inline: True
```
```
In net/ipv4/udp.c (ffffffff818251a1)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/devinet.c (ffffffff8182f55b)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/fib_frontend.c (ffffffff8183868f)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_new_table
```
```
In net/ipv4/fib_trie.c (ffffffff8183f3ed)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffffffff81850ad0)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81859161)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/ipv6/addrconf.c (ffffffff81869441)
Location: include/linux/rculist.h:476
Inline: True
```
```
In net/ipv6/addrlabel.c (ffffffff818721ab)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/ip6_fib.c (ffffffff8187ab28)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_init
  - net/ipv6/ip6_fib.c:fib6_net_init
  - net/ipv6/ip6_fib.c:fib6_new_table
```
```
In net/packet/af_packet.c (ffffffff818a9545)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_create
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a3d23)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
  - kernel/pid.c:alloc_pid
```
```
In kernel/time/posix-timers.c (ffffffff81107f6f)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/kprobes.c (ffffffff8114265c)
Location: include/linux/rculist.h:476
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff81156859)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:profile_graph_entry
```
```
In kernel/trace/trace_event_perf.c (ffffffff8117b0f4)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_add
```
```
In kernel/events/core.c (ffffffff811a91cf)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
```
```
In fs/namespace.c (ffffffff8127485f)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - fs/namespace.c:__attach_mnt
```
```
In fs/notify/mark.c (ffffffff81299d18)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
```
In fs/proc/proc_sysctl.c (ffffffff812d3d2f)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
```
```
In security/selinux/avc.c (ffffffff813a2660)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_compute_av
```
```
In security/smack/smack_access.c (ffffffff813c624e)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/integrity/ima/ima_queue.c (ffffffff813f6c41)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In block/blk-cgroup.c (ffffffff81446846)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/net/tun.c (ffffffff81695145)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/dev.c (ffffffff817c9e26)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:list_netdevice
```
```
In net/sched/sch_api.c (ffffffff817fec48)
Location: include/linux/rculist.h:476
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff8181f224)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81839d50)
Location: include/linux/rculist.h:476
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81845f2b)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/devinet.c (ffffffff81850a45)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/fib_frontend.c (ffffffff81859ac7)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_new_table
```
```
In net/ipv4/fib_trie.c (ffffffff81860aee)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffffffff818746cb)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff8187c11c)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/ipv6/addrconf.c (ffffffff818901b3)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81896f1e)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/ip6_fib.c (ffffffff818a0249)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_init
  - net/ipv6/ip6_fib.c:fib6_net_init
  - net/ipv6/ip6_fib.c:fib6_new_table
```
```
In net/packet/af_packet.c (ffffffff818d0299)
Location: include/linux/rculist.h:476
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_create
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810aa313)
Location: include/linux/rculist.h:477
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
```
```
In kernel/livepatch/shadow.c (ffffffff81102f4a)
Location: include/linux/rculist.h:477
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
```
In kernel/time/posix-timers.c (ffffffff8111311f)
Location: include/linux/rculist.h:477
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/kprobes.c (ffffffff8114f41c)
Location: include/linux/rculist.h:477
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff81163379)
Location: include/linux/rculist.h:477
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:profile_graph_entry
```
```
In kernel/trace/trace_event_perf.c (ffffffff8118897f)
Location: include/linux/rculist.h:477
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_add
```
```
In kernel/events/core.c (ffffffff811bca0f)
Location: include/linux/rculist.h:477
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
```
```
In fs/namespace.c (ffffffff8129718f)
Location: include/linux/rculist.h:477
Inline: True
Inline callers:
  - fs/namespace.c:__attach_mnt
```
```
In fs/notify/mark.c (ffffffff812bd0c8)
Location: include/linux/rculist.h:477
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
```
In fs/proc/proc_sysctl.c (ffffffff812f855f)
Location: include/linux/rculist.h:477
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
```
```
In security/selinux/avc.c (ffffffff813c8460)
Location: include/linux/rculist.h:477
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_compute_av
```
```
In security/smack/smack_access.c (ffffffff813ec53e)
Location: include/linux/rculist.h:477
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/integrity/ima/ima_queue.c (ffffffff8141ed61)
Location: include/linux/rculist.h:477
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In block/blk-cgroup.c (ffffffff81473419)
Location: include/linux/rculist.h:477
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/net/tun.c (ffffffff816ffb6a)
Location: include/linux/rculist.h:477
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/dev.c (ffffffff81843746)
Location: include/linux/rculist.h:477
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:list_netdevice
```
```
In net/sched/sch_api.c (ffffffff8187c8d8)
Location: include/linux/rculist.h:477
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff8189e194)
Location: include/linux/rculist.h:477
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818b9460)
Location: include/linux/rculist.h:477
Inline: True
```
```
In net/ipv4/udp.c (ffffffff818c595b)
Location: include/linux/rculist.h:477
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/devinet.c (ffffffff818d067c)
Location: include/linux/rculist.h:477
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/fib_frontend.c (ffffffff818d99c7)
Location: include/linux/rculist.h:477
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_new_table
```
```
In net/ipv4/fib_trie.c (ffffffff818e0b6e)
Location: include/linux/rculist.h:477
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f4c35)
Location: include/linux/rculist.h:477
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff818fc9d2)
Location: include/linux/rculist.h:477
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/ipv6/addrconf.c (ffffffff81911949)
Location: include/linux/rculist.h:477
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81918435)
Location: include/linux/rculist.h:477
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff8191c1e0)
Location: include/linux/rculist.h:477
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/ip6_fib.c (ffffffff819220b4)
Location: include/linux/rculist.h:477
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_new_table
```
```
In net/packet/af_packet.c (ffffffff819551b3)
Location: include/linux/rculist.h:477
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_create
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
In kernel/pid.c (ffffffff810b0f1c)
Location: include/linux/rculist.h:490
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
```
```
In kernel/livepatch/shadow.c (ffffffff8110b59b)
Location: include/linux/rculist.h:490
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
```
In kernel/time/posix-timers.c (ffffffff8111f9fc)
Location: include/linux/rculist.h:490
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/kprobes.c (ffffffff8115e079)
Location: include/linux/rculist.h:490
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff8117222c)
Location: include/linux/rculist.h:490
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:profile_graph_entry
```
```
In kernel/trace/trace_event_perf.c (ffffffff81197df6)
Location: include/linux/rculist.h:490
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_add
```
```
In kernel/bpf/sockmap.c (ffffffff811cdcbd)
Location: include/linux/rculist.h:490
Inline: True
```
```
In kernel/events/core.c (ffffffff811dcbcf)
Location: include/linux/rculist.h:490
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
```
```
In fs/namespace.c (ffffffff812bd3cf)
Location: include/linux/rculist.h:490
Inline: True
Inline callers:
  - fs/namespace.c:__attach_mnt
```
```
In fs/notify/mark.c (ffffffff812e5d6b)
Location: include/linux/rculist.h:490
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
```
In fs/proc/proc_sysctl.c (ffffffff813261f6)
Location: include/linux/rculist.h:490
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
```
```
In security/security.c (ffffffff82715f9e)
Location: include/linux/rculist.h:490
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In security/selinux/avc.c (ffffffff813f7b0b)
Location: include/linux/rculist.h:490
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_compute_av
```
```
In security/smack/smack_access.c (ffffffff8141d37e)
Location: include/linux/rculist.h:490
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/integrity/ima/ima_queue.c (ffffffff81450fc3)
Location: include/linux/rculist.h:490
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In block/blk-cgroup.c (ffffffff814a7c15)
Location: include/linux/rculist.h:490
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/net/tun.c (ffffffff8173f600)
Location: include/linux/rculist.h:490
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/dev.c (ffffffff8189189b)
Location: include/linux/rculist.h:490
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:list_netdevice
```
```
In net/sched/sch_api.c (ffffffff818cf0f6)
Location: include/linux/rculist.h:490
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f2b48)
Location: include/linux/rculist.h:490
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8190e796)
Location: include/linux/rculist.h:490
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8191d9cd)
Location: include/linux/rculist.h:490
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/devinet.c (ffffffff81926c21)
Location: include/linux/rculist.h:490
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/fib_frontend.c (ffffffff8193044b)
Location: include/linux/rculist.h:490
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_new_table
```
```
In net/ipv4/fib_trie.c (ffffffff8193716b)
Location: include/linux/rculist.h:490
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194b33c)
Location: include/linux/rculist.h:490
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81953909)
Location: include/linux/rculist.h:490
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/ipv6/addrconf.c (ffffffff81968d6a)
Location: include/linux/rculist.h:490
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff8196fc7f)
Location: include/linux/rculist.h:490
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81973b5e)
Location: include/linux/rculist.h:490
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/ip6_fib.c (ffffffff8197a31e)
Location: include/linux/rculist.h:490
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_new_table
```
```
In net/packet/af_packet.c (ffffffff819aee3d)
Location: include/linux/rculist.h:490
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_create
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
In kernel/pid.c (ffffffff810ba054)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
```
```
In kernel/livepatch/shadow.c (ffffffff81116d8b)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
```
In kernel/time/posix-timers.c (ffffffff8112b1d3)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/kprobes.c (ffffffff8116ac50)
Location: include/linux/rculist.h:505
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff8117f928)
Location: include/linux/rculist.h:505
Inline: True
```
```
In kernel/trace/trace_event_perf.c (ffffffff811a5f46)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_add
```
```
In kernel/events/core.c (ffffffff811ecfcf)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
```
```
In fs/namespace.c (ffffffff812d26df)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - fs/namespace.c:__attach_mnt
```
```
In fs/notify/mark.c (ffffffff812fa957)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
```
In fs/proc/proc_sysctl.c (ffffffff8133db2d)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
```
```
In security/security.c (ffffffff828cda61)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In security/selinux/avc.c (ffffffff814135bb)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_compute_av
```
```
In security/smack/smack_access.c (ffffffff8143996e)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/integrity/ima/ima_queue.c (ffffffff8146dfa3)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In block/blk-cgroup.c (ffffffff814c26ec)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/net/tun.c (ffffffff8175f417)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/core/dev.c (ffffffff818b2421)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:list_netdevice
```
```
In net/core/sock_map.c (ffffffff818f28fc)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/sched/sch_api.c (ffffffff818fa646)
Location: include/linux/rculist.h:505
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff819205b8)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193cb86)
Location: include/linux/rculist.h:505
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8194c27d)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/devinet.c (ffffffff81955cd1)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/fib_frontend.c (ffffffff8195f92b)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_new_table
```
```
In net/ipv4/fib_trie.c (ffffffff81966b5b)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197c19d)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_list
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81987b11)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/ipv6/anycast.c (ffffffff8199402e)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff8199e679)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff819a589f)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff819a9754)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/ip6_fib.c (ffffffff819b01ce)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_new_table
```
```
In net/packet/af_packet.c (ffffffff819e57fb)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
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
In kernel/pid.c (ffffffff810bff6a)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
```
```
In kernel/livepatch/shadow.c (ffffffff81121029)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
```
In kernel/time/posix-timers.c (ffffffff8113629f)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/kprobes.c (ffffffff811779a8)
Location: include/linux/rculist.h:505
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff8118ca1b)
Location: include/linux/rculist.h:505
Inline: True
```
```
In kernel/trace/trace_event_perf.c (ffffffff811b3e46)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_add
```
```
In kernel/events/core.c (ffffffff812049c5)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
```
```
In mm/mmu_notifier.c (ffffffff8128e037)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - mm/mmu_notifier.c:do_mmu_notifier_register
```
```
In fs/namespace.c (ffffffff812ef7bf)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - fs/namespace.c:__attach_mnt
```
```
In fs/notify/mark.c (ffffffff8131aaf5)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In fs/proc/proc_sysctl.c (ffffffff81365a0f)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
```
```
In security/security.c (ffffffff828e748d)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In security/selinux/avc.c (ffffffff8144105e)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_compute_av
```
```
In security/smack/smack_access.c (ffffffff8146756f)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/integrity/ima/ima_queue.c (ffffffff8149b667)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In block/blk-cgroup.c (ffffffff814f0ced)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/net/tun.c (ffffffff8179cc54)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/core/dev.c (ffffffff818fee38)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:list_netdevice
```
```
In net/core/sock_map.c (ffffffff81944a4c)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (ffffffff819529d0)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
```
```
In net/sched/sch_api.c (ffffffff81959ef6)
Location: include/linux/rculist.h:505
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81982ee8)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a0fde)
Location: include/linux/rculist.h:505
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819b0cad)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/devinet.c (ffffffff819ba6b2)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/fib_frontend.c (ffffffff819c47a4)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_new_table
```
```
In net/ipv4/fib_trie.c (ffffffff819ccd8c)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e5acb)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_list
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff819f18b3)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/ipv6/anycast.c (ffffffff819ffb16)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81a0a770)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81a11e02)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81a16d1c)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/ip6_fib.c (ffffffff81a1e30f)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_new_table
```
```
In net/packet/af_packet.c (ffffffff81a55223)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff81a7474e)
Location: include/linux/rculist.h:505
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_create
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
In kernel/pid.c (ffffffff810c633b)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
```
```
In kernel/livepatch/shadow.c (ffffffff8112d649)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
```
In kernel/time/posix-timers.c (ffffffff8114233f)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/kprobes.c (ffffffff811838e6)
Location: include/linux/rculist.h:525
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff8119861b)
Location: include/linux/rculist.h:525
Inline: True
```
```
In kernel/trace/trace_event_perf.c (ffffffff811bf476)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_add
```
```
In kernel/bpf/devmap.c (ffffffff811ff645)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
```
```
In kernel/events/core.c (ffffffff812115b5)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
```
```
In mm/mmu_notifier.c (ffffffff8129db90)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In fs/namespace.c (ffffffff8130128f)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - fs/namespace.c:__attach_mnt
```
```
In fs/notify/mark.c (ffffffff8132e001)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
```
In fs/proc/proc_sysctl.c (ffffffff8137dc9f)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
```
```
In security/security.c (ffffffff828f0001)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In security/selinux/avc.c (ffffffff8145a995)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_compute_av
```
```
In security/smack/smack_access.c (ffffffff8148134f)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/integrity/ima/ima_queue.c (ffffffff814b58a7)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In block/blk-cgroup.c (ffffffff8150a2c1)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/net/tun.c (ffffffff817c06e6)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/core/dev.c (ffffffff819311a7)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:list_netdevice
```
```
In net/core/sock_map.c (ffffffff81979a4c)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (ffffffff81988d20)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
```
```
In net/sched/sch_api.c (ffffffff81990396)
Location: include/linux/rculist.h:525
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81994cd2)
Location: include/linux/rculist.h:525
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b97a1)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d7c8e)
Location: include/linux/rculist.h:525
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819e7c00)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/devinet.c (ffffffff819f1245)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/fib_frontend.c (ffffffff819fb344)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_new_table
```
```
In net/ipv4/fib_trie.c (ffffffff81a0377a)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1cadb)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_list
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81a28783)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/ipv6/anycast.c (ffffffff81a366f9)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81a41423)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81a48a22)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81a4d95c)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/ip6_fib.c (ffffffff81a54f6f)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_new_table
```
```
In net/packet/af_packet.c (ffffffff81a8be13)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff81aab0fd)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_create
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
In kernel/pid.c (ffffffff810ce1a0)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
```
```
In kernel/livepatch/shadow.c (ffffffff8113bdc9)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
```
In kernel/time/posix-timers.c (ffffffff81150990)
Location: include/linux/rculist.h:556
Inline: True
```
```
In kernel/kprobes.c (ffffffff8119773e)
Location: include/linux/rculist.h:556
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff811ad5f9)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_profile_alloc
```
```
In kernel/trace/trace_event_perf.c (ffffffff811d8d86)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_add
```
```
In kernel/bpf/devmap.c (ffffffff8122747a)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
```
```
In kernel/events/core.c (ffffffff8123d620)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
```
```
In mm/mmu_notifier.c (ffffffff812d224f)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In fs/inode.c (ffffffff8133756a)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/namespace.c (ffffffff8133a4ff)
Location: include/linux/rculist.h:556
Inline: True
```
```
In fs/notify/mark.c (ffffffff81367733)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In fs/proc/base.c (ffffffff813bea62)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_make_inode
```
```
In fs/proc/proc_sysctl.c (ffffffff813c7c1f)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
```
```
In security/security.c (ffffffff82d0526a)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In security/selinux/avc.c (ffffffff814adc94)
Location: include/linux/rculist.h:556
Inline: True
```
```
In security/selinux/ss/sidtab.c (ffffffff814c0bed)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/smack/smack_access.c (ffffffff814d72bf)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/integrity/ima/ima_queue.c (ffffffff81514f5f)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In block/blk-cgroup.c (ffffffff8156b4d3)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/net/tun.c (ffffffff8188c240)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/core/dev.c (ffffffff81a05388)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/core/dev.c:napi_hash_add
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:netdev_name_node_alt_create
```
```
In net/core/sock_map.c (ffffffff81a4f845)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (ffffffff81a609e0)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
```
```
In net/sched/sch_api.c (ffffffff81a67ed7)
Location: include/linux/rculist.h:556
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81a6c3a7)
Location: include/linux/rculist.h:556
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa43f3)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac3d2f)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_add
```
```
In net/ipv4/udp.c (ffffffff81ad4b83)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/devinet.c (ffffffff81adf1b5)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/fib_frontend.c (ffffffff81aea7b2)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_new_table
```
```
In net/ipv4/fib_trie.c (ffffffff81af3016)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b10064)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_list
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_inexact_list
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1adfa)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/anycast.c (ffffffff81b2b7ff)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81b3529f)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr_hash
```
```
In net/ipv6/addrlabel.c (ffffffff81b3ed49)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81b43c91)
Location: include/linux/rculist.h:556
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4cebf)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_new_table
```
```
In net/packet/af_packet.c (ffffffff81b892a1)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff81ba70bb)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_create
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
In kernel/pid.c (ffffffff810c8c72)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
```
```
In kernel/livepatch/shadow.c (ffffffff811364d9)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
```
In kernel/time/posix-timers.c (ffffffff8114cc10)
Location: include/linux/rculist.h:585
Inline: True
```
```
In kernel/kprobes.c (ffffffff8119484e)
Location: include/linux/rculist.h:585
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff811aaf09)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_profile_alloc
```
```
In kernel/trace/trace_event_perf.c (ffffffff811d5ea6)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_add
```
```
In kernel/bpf/devmap.c (ffffffff8122dfdb)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8122ffc9)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_selem_link_map
```
```
In kernel/events/core.c (ffffffff812479c0)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
```
```
In mm/mmu_notifier.c (ffffffff812ddc6f)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In fs/inode.c (ffffffff81342eaa)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/namespace.c (ffffffff813468bf)
Location: include/linux/rculist.h:585
Inline: True
```
```
In fs/notify/mark.c (ffffffff81374a93)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In fs/eventpoll.c (ffffffff8137b21d)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/proc/base.c (ffffffff813d0832)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_make_inode
```
```
In fs/proc/proc_sysctl.c (ffffffff813d9c0f)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
```
```
In security/security.c (ffffffff82ff2637)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In security/selinux/avc.c (ffffffff814cb714)
Location: include/linux/rculist.h:585
Inline: True
```
```
In security/selinux/ss/sidtab.c (ffffffff814de66d)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/smack/smack_access.c (ffffffff814f476f)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/integrity/ima/ima_queue.c (ffffffff81531fcf)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In block/blk-cgroup.c (ffffffff81585fdc)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/net/tun.c (ffffffff8189a320)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/core/dev.c (ffffffff81a06a74)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:netdev_name_node_alt_create
```
```
In net/core/sock_map.c (ffffffff81a556da)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/sched/sch_api.c (ffffffff81a70603)
Location: include/linux/rculist.h:585
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81a74d5f)
Location: include/linux/rculist.h:585
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aaea35)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81acf7bf)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_add
```
```
In net/ipv4/udp.c (ffffffff81ae10c3)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/devinet.c (ffffffff81aebfb5)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/fib_frontend.c (ffffffff81af7642)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_new_table
```
```
In net/ipv4/fib_trie.c (ffffffff81afff26)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1e354)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_list
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_inexact_list
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/xfrm/xfrm_state.c (ffffffff81b29505)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/anycast.c (ffffffff81b3a22f)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81b439af)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr_hash
```
```
In net/ipv6/addrlabel.c (ffffffff81b4d759)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81b52372)
Location: include/linux/rculist.h:585
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81b5bb3f)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_new_table
```
```
In net/packet/af_packet.c (ffffffff81b98da1)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff81bb63fa)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_create
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
In kernel/pid.c (ffffffff810ca711)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
```
```
In kernel/livepatch/shadow.c (ffffffff811372d6)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
```
In kernel/time/posix-timers.c (ffffffff8114f2bc)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/kprobes.c (ffffffff8119583e)
Location: include/linux/rculist.h:585
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff811acc57)
Location: include/linux/rculist.h:585
Inline: True
```
```
In kernel/trace/trace_event_perf.c (ffffffff811d74e6)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_add
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8122559e)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_selem_link_map
```
```
In kernel/bpf/devmap.c (ffffffff812323d1)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
```
```
In kernel/events/core.c (ffffffff8124b86a)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
```
```
In mm/mmu_notifier.c (ffffffff812e521f)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In fs/inode.c (ffffffff81349160)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/namespace.c (ffffffff8134c52f)
Location: include/linux/rculist.h:585
Inline: True
```
```
In fs/notify/mark.c (ffffffff8137b44a)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In fs/eventpoll.c (ffffffff81382fd9)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/proc/base.c (ffffffff813d7732)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_make_inode
```
```
In fs/proc/proc_sysctl.c (ffffffff813e09ff)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
```
```
In security/security.c (ffffffff831fd013)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In security/selinux/avc.c (ffffffff814d1d37)
Location: include/linux/rculist.h:585
Inline: True
```
```
In security/selinux/ss/sidtab.c (ffffffff814e4fed)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/smack/smack_access.c (ffffffff814fb6de)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/integrity/ima/ima_queue.c (ffffffff8153a39f)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In block/blk-cgroup.c (ffffffff8158c9cc)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/net/tun.c (ffffffff8187c0f0)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/core/dev.c (ffffffff819edd58)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:netdev_name_node_alt_create
```
```
In net/core/sock_map.c (ffffffff81a50ed7)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/sched/sch_api.c (ffffffff81a58f03)
Location: include/linux/rculist.h:585
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81a5d90f)
Location: include/linux/rculist.h:585
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a99c85)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81aba90f)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_add
```
```
In net/ipv4/udp.c (ffffffff81acd023)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/devinet.c (ffffffff81ad7625)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae2d72)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_new_table
```
```
In net/ipv4/fib_trie.c (ffffffff81aeb41d)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0bcb5)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_list
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_inexact_list
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/xfrm/xfrm_state.c (ffffffff81b17140)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/ipv6/anycast.c (ffffffff81b27f17)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81b3398b)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81b3be23)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81b3fd20)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/ip6_fib.c (ffffffff81b48eef)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_new_table
```
```
In net/packet/af_packet.c (ffffffff81b87c94)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff81ba6766)
Location: include/linux/rculist.h:585
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_create
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
In kernel/pid.c (ffffffff810dd5d7)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
```
```
In kernel/livepatch/shadow.c (ffffffff81159f80)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
```
In kernel/time/posix-timers.c (ffffffff81173482)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/kprobes.c (ffffffff811be792)
Location: include/linux/rculist.h:584
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff811d68b7)
Location: include/linux/rculist.h:584
Inline: True
```
```
In kernel/trace/trace_event_perf.c (ffffffff812044a6)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_add
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8125d58e)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_selem_link_map
```
```
In kernel/bpf/devmap.c (ffffffff8126b621)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
```
```
In kernel/events/core.c (ffffffff81284d9a)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
```
```
In mm/mmu_notifier.c (ffffffff8132ce7f)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In fs/inode.c (ffffffff81396eaa)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/namespace.c (ffffffff8139a594)
Location: include/linux/rculist.h:584
Inline: True
```
```
In fs/notify/mark.c (ffffffff813c8190)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In fs/eventpoll.c (ffffffff813d026b)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/proc/base.c (ffffffff81428e72)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_make_inode
```
```
In fs/proc/proc_sysctl.c (ffffffff8143247f)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
```
```
In security/security.c (ffffffff832e4214)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In security/selinux/avc.c (ffffffff8152aaf7)
Location: include/linux/rculist.h:584
Inline: True
```
```
In security/selinux/ss/sidtab.c (ffffffff8153e663)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/smack/smack_access.c (ffffffff8155634e)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/integrity/ima/ima_queue.c (ffffffff81598d21)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In block/blk-cgroup.c (ffffffff815f2118)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/net/tun.c (ffffffff8190d638)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/core/dev.c (ffffffff81a9efbd)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:netdev_name_node_alt_create
```
```
In net/core/sock_map.c (ffffffff81b09f84)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/sched/sch_api.c (ffffffff81b12380)
Location: include/linux/rculist.h:584
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81b16819)
Location: include/linux/rculist.h:584
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b550ed)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b77c07)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_add
```
```
In net/ipv4/udp.c (ffffffff81b8b9a3)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/devinet.c (ffffffff81b960d5)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba27d6)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_new_table
```
```
In net/ipv4/fib_trie.c (ffffffff81bab76d)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcec75)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_list
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_inexact_list
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/xfrm/xfrm_state.c (ffffffff81bdb4f0)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/anycast.c (ffffffff81bede57)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81bf9ffb)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81c026a3)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81c05f2d)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/ip6_fib.c (ffffffff81c101ff)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_new_table
```
```
In net/packet/af_packet.c (ffffffff81c541c1)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff81c742b6)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_create
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
In kernel/pid.c (ffffffff810f6ed7)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
```
```
In kernel/livepatch/shadow.c (ffffffff81183842)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
```
In kernel/time/posix-timers.c (ffffffff811a6691)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/kprobes.c (ffffffff811f1c99)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kprobe
```
```
In kernel/trace/ftrace.c (ffffffff8120ba41)
Location: include/linux/rculist.h:584
Inline: True
```
```
In kernel/trace/trace_event_perf.c (ffffffff8123f956)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_add
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff812a7776)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_selem_link_map
```
```
In kernel/bpf/devmap.c (ffffffff812ba2a6)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
```
```
In kernel/events/core.c (ffffffff812d92e7)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
```
```
In kernel/watch_queue.c (ffffffff812ed5d4)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/mmu_notifier.c (ffffffff8139d07f)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In fs/inode.c (ffffffff81418a85)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/namespace.c (ffffffff8141d144)
Location: include/linux/rculist.h:584
Inline: True
```
```
In fs/notify/mark.c (ffffffff8144f978)
Location: include/linux/rculist.h:584
Inline: True
```
```
In fs/eventpoll.c (ffffffff814589a6)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/proc/base.c (ffffffff814a26cf)
Location: include/linux/rculist.h:584
Inline: True
```
```
In fs/proc/proc_sysctl.c (ffffffff814aaf56)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
```
```
In security/security.c (ffffffff8349ad75)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In security/selinux/avc.c (ffffffff815c0836)
Location: include/linux/rculist.h:584
Inline: True
```
```
In security/selinux/ss/sidtab.c (ffffffff815d6057)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/smack/smack_access.c (ffffffff815f06fe)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/integrity/ima/ima_queue.c (ffffffff8163d74e)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In block/blk-cgroup.c (ffffffff816a393d)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/net/tun.c (ffffffff81a60734)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81b3ee33)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_register
```
```
In net/core/dev.c (ffffffff81c11db1)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add_weight
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:netdev_name_node_alt_create
```
```
In net/core/sock_map.c (ffffffff81c901d1)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/sched/sch_api.c (ffffffff81c996b2)
Location: include/linux/rculist.h:584
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81c9df19)
Location: include/linux/rculist.h:584
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d076c4)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_add
```
```
In net/ipv4/udp.c (ffffffff81d18d40)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/devinet.c (ffffffff81d27e1c)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/fib_frontend.c (ffffffff81d34ed4)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_new_table
```
```
In net/ipv4/fib_trie.c (ffffffff81d3e614)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d65bf2)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_list
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_inexact_list
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/xfrm/xfrm_state.c (ffffffff81d72334)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/anycast.c (ffffffff81d863b5)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81d93249)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81d9bbeb)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81da05e9)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/ip6_fib.c (ffffffff81dac0d2)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_new_table
```
```
In net/packet/af_packet.c (ffffffff81df3568)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff81e17b58)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_create
```
```
In net/mctp/af_mctp.c (ffffffff81e37bb6)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_hash
  - net/mctp/af_mctp.c:mctp_sk_hash
```
```
In net/mctp/route.c (ffffffff81e3a7d3)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_alloc_local_tag
  - net/mctp/route.c:mctp_alloc_local_tag
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
In kernel/pid.c (ffffffff811195f7)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
```
```
In kernel/printk/printk.c (ffffffff8118d988)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_force_preferred_locked
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:register_console
```
```
In kernel/livepatch/shadow.c (ffffffff811be9f2)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
```
In kernel/time/posix-timers.c (ffffffff811e6231)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/kprobes.c (ffffffff81238944)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kprobe
```
```
In kernel/trace/ftrace.c (ffffffff81254490)
Location: include/linux/rculist.h:584
Inline: True
```
```
In kernel/trace/trace_event_perf.c (ffffffff8128d436)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_add
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff81305e96)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_selem_link_map
```
```
In kernel/bpf/devmap.c (ffffffff8131d626)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
```
```
In kernel/events/core.c (ffffffff813417b7)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
```
```
In kernel/watch_queue.c (ffffffff813579a4)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/mmu_notifier.c (ffffffff8141c4cf)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In fs/inode.c (ffffffff814a43a5)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/namespace.c (ffffffff814a9464)
Location: include/linux/rculist.h:584
Inline: True
```
```
In fs/notify/mark.c (ffffffff814de218)
Location: include/linux/rculist.h:584
Inline: True
```
```
In fs/eventpoll.c (ffffffff814e74d6)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/crypto/keyring.c (ffffffff814fe8b7)
Location: include/linux/rculist.h:584
Inline: True
```
```
In fs/proc/base.c (ffffffff8153785f)
Location: include/linux/rculist.h:584
Inline: True
```
```
In fs/proc/proc_sysctl.c (ffffffff81540dd6)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
```
```
In security/security.c (0)
Location: include/linux/rculist.h:584
Inline: True
```
```
In security/selinux/avc.c (ffffffff8166cda6)
Location: include/linux/rculist.h:584
Inline: True
```
```
In security/selinux/ss/sidtab.c (ffffffff81684276)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/smack/smack_access.c (ffffffff816a0afe)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/integrity/ima/ima_queue.c (ffffffff816f527e)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In block/blk-cgroup.c (ffffffff81762622)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/net/tun.c (ffffffff81bebe20)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81cd51e0)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_register
```
```
In net/core/dev.c (ffffffff81dc39a7)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add_weight
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:netdev_name_node_alt_create
```
```
In net/core/sock_map.c (ffffffff81e4b604)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/sched/sch_api.c (ffffffff81e559c2)
Location: include/linux/rculist.h:584
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81e5a619)
Location: include/linux/rculist.h:584
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecd080)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_add
```
```
In net/ipv4/udp.c (ffffffff81edf44b)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/devinet.c (ffffffff81eef7dc)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/fib_frontend.c (ffffffff81efd404)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_new_table
```
```
In net/ipv4/fib_trie.c (ffffffff81f071f4)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f30b8b)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_list
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_inexact_list
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3e005)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/anycast.c (ffffffff81f53f05)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81f619d9)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81f6a86b)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81f6f858)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/ip6_fib.c (ffffffff81f7b962)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_new_table
```
```
In net/packet/af_packet.c (ffffffff81fc8328)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff81feeb08)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_create
```
```
In net/mctp/af_mctp.c (ffffffff82010e26)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_hash
  - net/mctp/af_mctp.c:mctp_sk_hash
```
```
In net/mctp/route.c (ffffffff82013d80)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_alloc_local_tag
  - net/mctp/route.c:mctp_alloc_local_tag
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
In kernel/workqueue.c (ffffffff8111e27d)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_cpu_intensive_report
```
```
In kernel/pid.c (ffffffff81126ad1)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
```
```
In kernel/printk/printk.c (ffffffff8119f136)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_force_preferred_locked
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:register_console
```
```
In kernel/livepatch/shadow.c (ffffffff811d1419)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
```
In kernel/time/posix-timers.c (ffffffff811fa873)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/kprobes.c (ffffffff8124faa4)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kprobe
```
```
In kernel/trace/ftrace.c (ffffffff8126b380)
Location: include/linux/rculist.h:584
Inline: True
```
```
In kernel/trace/trace_event_perf.c (ffffffff812aa3b6)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_add
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff81334bd6)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_selem_link_map
```
```
In kernel/bpf/devmap.c (ffffffff8134d42e)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
```
```
In kernel/events/core.c (ffffffff81372797)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
```
```
In kernel/watch_queue.c (ffffffff81389206)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/mmu_notifier.c (ffffffff8144fa81)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In fs/inode.c (ffffffff814d951e)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/namespace.c (ffffffff814de3a4)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - fs/namespace.c:__attach_mnt
```
```
In fs/notify/mark.c (ffffffff81514a4b)
Location: include/linux/rculist.h:584
Inline: True
```
```
In fs/eventpoll.c (ffffffff8151f2fe)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/crypto/keyring.c (ffffffff81535d87)
Location: include/linux/rculist.h:584
Inline: True
```
```
In fs/proc/base.c (ffffffff8156fa5f)
Location: include/linux/rculist.h:584
Inline: True
```
```
In fs/proc/proc_sysctl.c (ffffffff81579186)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
```
```
In security/security.c (0)
Location: include/linux/rculist.h:584
Inline: True
```
```
In security/selinux/avc.c (ffffffff816a4fe6)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_compute_av
```
```
In security/selinux/ss/sidtab.c (ffffffff816bc5e0)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/smack/smack_access.c (ffffffff816d943e)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/integrity/ima/ima_queue.c (ffffffff8172f37c)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In block/blk-cgroup.c (ffffffff817a12b8)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/net/tun.c (ffffffff81c442d1)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81d3ce63)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_register
```
```
In net/core/dev.c (ffffffff81e32e47)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add_weight
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:netdev_name_node_alt_create
```
```
In net/core/sock_map.c (ffffffff81ea6d24)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/sched/sch_api.c (ffffffff81eb1262)
Location: include/linux/rculist.h:584
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81eb5ec9)
Location: include/linux/rculist.h:584
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2bd60)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_add
```
```
In net/ipv4/raw.c (ffffffff81f3bcd8)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff81f3e917)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/devinet.c (ffffffff81f4f19c)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5ce4a)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_new_table
```
```
In net/ipv4/fib_trie.c (ffffffff81f66df6)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv4/ping.c (ffffffff81f6c6a8)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f90bfb)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_list
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_inexact_list
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9d90c)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/anycast.c (ffffffff81fb38f5)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81fc1805)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81fca897)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81fcf93b)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/ip6_fib.c (ffffffff81fdb6d2)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_new_table
```
```
In net/packet/af_packet.c (ffffffff8202844a)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff8206ac47)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_create
```
```
In net/mctp/af_mctp.c (ffffffff8208d67c)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_hash
  - net/mctp/af_mctp.c:mctp_sk_hash
```
```
In net/mctp/route.c (ffffffff82090c2c)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_alloc_local_tag
  - net/mctp/route.c:mctp_alloc_local_tag
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
In kernel/workqueue.c (ffffffff81127fad)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_cpu_intensive_report
```
```
In kernel/pid.c (ffffffff811310b7)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
```
```
In kernel/printk/printk.c (ffffffff811ae226)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_force_preferred_locked
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:register_console
```
```
In kernel/livepatch/shadow.c (ffffffff811e6099)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
```
In kernel/time/posix-timers.c (ffffffff81210a63)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/kprobes.c (ffffffff812699d4)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kprobe
```
```
In kernel/trace/ftrace.c (ffffffff81285830)
Location: include/linux/rculist.h:584
Inline: True
```
```
In kernel/trace/trace_event_perf.c (ffffffff812c60c6)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_add
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff813592b2)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_selem_link_map
```
```
In kernel/bpf/devmap.c (ffffffff8137494e)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
```
```
In kernel/events/core.c (ffffffff8139bb07)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
```
```
In kernel/watch_queue.c (ffffffff813b2c58)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/mmu_notifier.c (ffffffff8148979f)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In fs/inode.c (ffffffff8150bcce)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/namespace.c (ffffffff81510e14)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - fs/namespace.c:__attach_mnt
```
```
In fs/notify/mark.c (ffffffff81548e61)
Location: include/linux/rculist.h:584
Inline: True
```
```
In fs/eventpoll.c (ffffffff8155390e)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/crypto/keyring.c (ffffffff8156ad8f)
Location: include/linux/rculist.h:584
Inline: True
```
```
In fs/proc/base.c (ffffffff815a83ef)
Location: include/linux/rculist.h:584
Inline: True
```
```
In fs/proc/proc_sysctl.c (ffffffff815b19d4)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
```
```
In security/security.c (0)
Location: include/linux/rculist.h:584
Inline: True
```
```
In security/selinux/avc.c (ffffffff816e1a3a)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_compute_av
```
```
In security/selinux/ss/sidtab.c (ffffffff816f9110)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/smack/smack_access.c (ffffffff81715e9e)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/integrity/ima/ima_queue.c (ffffffff8176fd0a)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In block/blk-cgroup.c (ffffffff817e4e05)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/net/tun.c (ffffffff81cf9bc0)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81df37d2)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_register
```
```
In net/core/dev.c (ffffffff81ef1dcb)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add_weight
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:netdev_name_node_alt_create
```
```
In net/core/sock_map.c (ffffffff81f69843)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/sched/sch_api.c (ffffffff81f73d02)
Location: include/linux/rculist.h:584
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81f78bd9)
Location: include/linux/rculist.h:584
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff0b11)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_add
```
```
In net/ipv4/raw.c (ffffffff82001df8)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff82004c67)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/devinet.c (ffffffff820152fc)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/fib_frontend.c (ffffffff820233da)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_new_table
```
```
In net/ipv4/fib_trie.c (ffffffff8202d3d9)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv4/ping.c (ffffffff82032df8)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv4/tcp_ao.c (ffffffff82055128)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_ao_del_cmd
  - net/ipv4/tcp_ao.c:tcp_ao_add_cmd
  - net/ipv4/tcp_ao.c:tcp_ao_copy_all_matching
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205e96b)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_list
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_inexact_list
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/xfrm/xfrm_state.c (ffffffff8206ac6c)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/anycast.c (ffffffff8208119a)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff8208ed3d)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff82098037)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff8209d1ca)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/ip6_fib.c (ffffffff820a9201)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_new_table
```
```
In net/packet/af_packet.c (ffffffff820f7caa)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff8213e357)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_create
```
```
In net/mctp/af_mctp.c (ffffffff82163b3c)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_hash
  - net/mctp/af_mctp.c:mctp_sk_hash
```
```
In net/mctp/route.c (ffffffff8216716c)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_alloc_local_tag
  - net/mctp/route.c:mctp_alloc_local_tag
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
In virt/kvm/eventfd.c (ffff8000100c0f18)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - virt/kvm/eventfd.c:kvm_register_irq_ack_notifier
```
```
In kernel/pid.c (ffff800010124b78)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
```
```
In kernel/time/posix-timers.c (ffff8000101ac400)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/kprobes.c (ffff8000101f9008)
Location: include/linux/rculist.h:525
Inline: True
```
```
In kernel/trace/ftrace.c (ffff800010210f98)
Location: include/linux/rculist.h:525
Inline: True
```
```
In kernel/trace/trace_event_perf.c (ffff80001023eadc)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_add
```
```
In kernel/bpf/devmap.c (ffff800010287458)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
```
```
In kernel/events/core.c (ffff8000102a0980)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
```
```
In mm/mmu_notifier.c (ffff80001033d064)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In fs/namespace.c (ffff8000103b3b40)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - fs/namespace.c:__attach_mnt
```
```
In fs/notify/mark.c (ffff8000103e9a7c)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In fs/proc/proc_sysctl.c (ffff80001044a620)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
```
```
In security/security.c (ffff800011469ef8)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In security/selinux/avc.c (ffff800010546ffc)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_compute_av
```
```
In security/smack/smack_access.c (ffff800010572c5c)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/integrity/ima/ima_queue.c (ffff8000105add28)
Location: include/linux/rculist.h:525
Inline: True
```
```
In block/blk-cgroup.c (ffff80001060d998)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/net/tun.c (ffff8000109de160)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/core/dev.c (ffff800010bce990)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:list_netdevice
```
```
In net/core/sock_map.c (ffff800010c20ef8)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (ffff800010c31228)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
```
```
In net/sched/sch_api.c (ffff800010c3c2b0)
Location: include/linux/rculist.h:525
Inline: True
```
```
In net/sched/cls_api.c (ffff800010c41408)
Location: include/linux/rculist.h:525
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffff800010c6af28)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8ab50)
Location: include/linux/rculist.h:525
Inline: True
```
```
In net/ipv4/udp.c (ffff800010c9bb94)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/devinet.c (ffff800010ca74c0)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/fib_frontend.c (ffff800010cb31f4)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_new_table
```
```
In net/ipv4/fib_trie.c (ffff800010cbc230)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffff800010cd8e98)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_list
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffff800010ce7ee0)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/ipv6/anycast.c (ffff800010cf72fc)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffff800010d02dd4)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffff800010d0be48)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffff800010d121e8)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/ip6_fib.c (ffff800010d18b7c)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_new_table
```
```
In net/packet/af_packet.c (ffff800010d586ec)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffff800010d7e704)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_create
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
In kernel/pid.c (c0377b54)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
```
```
In kernel/time/posix-timers.c (c03f6740)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/kprobes.c (c0439174)
Location: include/linux/rculist.h:525
Inline: True
```
```
In kernel/trace/ftrace.c (c044f63c)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:profile_graph_entry
```
```
In kernel/trace/trace_event_perf.c (c047a110)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_add
```
```
In kernel/bpf/devmap.c (c04b6c50)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
```
```
In kernel/events/core.c (c04d0c78)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
```
```
In mm/mmu_notifier.c (c0543464)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In fs/namespace.c (c05926f8)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - fs/namespace.c:__attach_mnt
```
```
In fs/notify/mark.c (c05c1244)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In fs/proc/proc_sysctl.c (c060ece0)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
```
```
In security/security.c (c1542ad4)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In security/selinux/avc.c (c06fcd48)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_compute_av
```
```
In security/smack/smack_access.c (c0725e78)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/integrity/ima/ima_queue.c (c075d428)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In block/blk-cgroup.c (c07b8528)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/net/tun.c (c0ac1b3c)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/core/dev.c (c0ce5640)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:list_netdevice
```
```
In net/core/sock_map.c (c0d387a0)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (c0d47de8)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
```
```
In net/sched/sch_api.c (c0d4e218)
Location: include/linux/rculist.h:525
Inline: True
```
```
In net/sched/cls_api.c (c0d536ac)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_signal_destroying
```
```
In net/ipv4/inet_hashtables.c (c0d79fd0)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/tcp_ipv4.c (c0d9ab30)
Location: include/linux/rculist.h:525
Inline: True
```
```
In net/ipv4/udp.c (c0da7a1c)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/devinet.c (c0db3be4)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/fib_frontend.c (c0dbe99c)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_new_table
```
```
In net/ipv4/fib_trie.c (c0dc7a68)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (c0de2acc)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_list
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (c0def160)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/ipv6/anycast.c (c0dfd9c4)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (c0e09b78)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (c0e11c08)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (c0e17f18)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/ip6_fib.c (c0e1e44c)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_new_table
```
```
In net/packet/af_packet.c (c0e58188)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (c0e791a4)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_create
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
In kernel/pid.c (c00000000016e910)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
```
```
In kernel/livepatch/shadow.c (c0000000001f21e0)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
```
In kernel/time/posix-timers.c (c000000000210130)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/kprobes.c (c00000000027044c)
Location: include/linux/rculist.h:525
Inline: True
```
```
In kernel/trace/ftrace.c (c00000000028f9b8)
Location: include/linux/rculist.h:525
Inline: True
```
```
In kernel/trace/trace_event_perf.c (c0000000002ce9bc)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_add
```
```
In kernel/bpf/devmap.c (c000000000331d0c)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
```
```
In kernel/events/core.c (c000000000352808)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
```
```
In mm/mmu_notifier.c (c000000000417fec)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In fs/namespace.c (c0000000004af7b4)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - fs/namespace.c:__attach_mnt
```
```
In fs/notify/mark.c (c0000000004f0d60)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In fs/proc/proc_sysctl.c (c00000000056060c)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
```
```
In security/security.c (c000000001398324)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In security/selinux/avc.c (c00000000069de84)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_compute_av
```
```
In security/smack/smack_access.c (c0000000006dab38)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/integrity/ima/ima_queue.c (c00000000072c8d8)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In block/blk-cgroup.c (c0000000007aab50)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/net/tun.c (c000000000a9d164)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/core/dev.c (c000000000ca5f60)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:list_netdevice
```
```
In net/core/sock_map.c (c000000000d13050)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (c000000000d29eec)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
```
```
In net/sched/sch_api.c (c000000000d35f24)
Location: include/linux/rculist.h:525
Inline: True
```
```
In net/sched/cls_api.c (c000000000d3c6d4)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_signal_destroying
```
```
In net/ipv4/inet_hashtables.c (c000000000d702c8)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/tcp_ipv4.c (c000000000d993ec)
Location: include/linux/rculist.h:525
Inline: True
```
```
In net/ipv4/udp.c (c000000000dab780)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/devinet.c (c000000000dbbcd8)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/fib_frontend.c (c000000000dca134)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_new_table
```
```
In net/ipv4/fib_trie.c (c000000000dd5d98)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (c000000000df9678)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_list
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_bydst_resize
```
```
In net/xfrm/xfrm_state.c (c000000000e09fe0)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/ipv6/anycast.c (c000000000e1db48)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (c000000000e2a984)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (c000000000e366f8)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (c000000000e3e3c4)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/ip6_fib.c (c000000000e487f0)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_new_table
```
```
In net/packet/af_packet.c (c000000000e90d60)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (c000000000ebe7f0)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_create
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
In kernel/pid.c (ffffffe0000dcb04)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
```
```
In kernel/time/posix-timers.c (ffffffe00013620e)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/trace/ftrace.c (ffffffe0001710a6)
Location: include/linux/rculist.h:525
Inline: True
```
```
In kernel/trace/trace_event_perf.c (ffffffe00019407c)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_add
```
```
In kernel/bpf/devmap.c (ffffffe0001bb93c)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
```
```
In kernel/events/core.c (ffffffe0001cfd3e)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
```
```
In mm/mmu_notifier.c (ffffffe00023261e)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In fs/namespace.c (ffffffe0002771fe)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - fs/namespace.c:__attach_mnt
```
```
In fs/notify/mark.c (ffffffe00029e35c)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In fs/proc/proc_sysctl.c (ffffffe0002e0568)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
```
```
In security/security.c (ffffffe000025058)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In security/selinux/avc.c (ffffffe0003a28c4)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_compute_av
```
```
In security/smack/smack_access.c (ffffffe0003c6222)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/integrity/ima/ima_queue.c (ffffffe0003f6088)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In block/blk-cgroup.c (ffffffe0004461aa)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/net/tun.c (ffffffe000625b8e)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/core/dev.c (ffffffe000758c9c)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:list_netdevice
```
```
In net/core/sock_map.c (ffffffe000799c88)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (ffffffe0007a6e56)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
```
```
In net/sched/sch_api.c (ffffffe0007acc00)
Location: include/linux/rculist.h:525
Inline: True
```
```
In net/sched/cls_api.c (ffffffe0007b0ab8)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_signal_destroying
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007d0bf2)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ebcf2)
Location: include/linux/rculist.h:525
Inline: True
```
```
In net/ipv4/udp.c (ffffffe0007f9e12)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/devinet.c (ffffffe000802614)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/fib_frontend.c (ffffffe00080b2be)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_new_table
```
```
In net/ipv4/fib_trie.c (ffffffe000812708)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffffffe000829386)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_list
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffe000835730)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/ipv6/anycast.c (ffffffe000842700)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffe00084c206)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffe000852da6)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffe00085866c)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/ip6_fib.c (ffffffe00085d588)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_new_table
```
```
In net/packet/af_packet.c (ffffffe0008906a2)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffe0008ac1a4)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_create
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
In kernel/pid.c (ffffffff810c06ba)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
```
```
In kernel/livepatch/shadow.c (ffffffff81125c29)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
```
In kernel/time/posix-timers.c (ffffffff8113aaef)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/kprobes.c (ffffffff8117bf06)
Location: include/linux/rculist.h:525
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff81190c3b)
Location: include/linux/rculist.h:525
Inline: True
```
```
In kernel/trace/trace_event_perf.c (ffffffff811b7a96)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_add
```
```
In kernel/bpf/devmap.c (ffffffff811f7c65)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
```
```
In kernel/events/core.c (ffffffff81209c05)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
```
```
In mm/mmu_notifier.c (ffffffff81296170)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In fs/namespace.c (ffffffff812f986f)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - fs/namespace.c:__attach_mnt
```
```
In fs/notify/mark.c (ffffffff813265e1)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
```
In fs/proc/proc_sysctl.c (ffffffff8137627f)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
```
```
In security/security.c (ffffffff828d8eb5)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In security/selinux/avc.c (ffffffff81452f75)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_compute_av
```
```
In security/smack/smack_access.c (ffffffff8147992f)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/integrity/ima/ima_queue.c (ffffffff814ade87)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In block/blk-cgroup.c (ffffffff815028a1)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/net/tun.c (ffffffff817851b6)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/core/dev.c (ffffffff818d11a7)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:list_netdevice
```
```
In net/core/sock_map.c (ffffffff819198bc)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (ffffffff81928b90)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
```
```
In net/sched/sch_api.c (ffffffff81930206)
Location: include/linux/rculist.h:525
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81934b42)
Location: include/linux/rculist.h:525
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81959611)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81977afe)
Location: include/linux/rculist.h:525
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81987a70)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/devinet.c (ffffffff81990fe5)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/fib_frontend.c (ffffffff8199b0e4)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_new_table
```
```
In net/ipv4/fib_trie.c (ffffffff819a351a)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bc16b)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_list
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff819c7e13)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/ipv6/anycast.c (ffffffff819d5d89)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff819e0ab3)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff819e80b2)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff819ecfec)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/ip6_fib.c (ffffffff819f45ff)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_new_table
```
```
In net/packet/af_packet.c (ffffffff81a2b4a3)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff81a4a48d)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_create
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
In kernel/pid.c (ffffffff810aeebb)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
```
```
In kernel/livepatch/shadow.c (ffffffff81118689)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
```
In kernel/time/posix-timers.c (ffffffff8112d53f)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/kprobes.c (ffffffff8116f0a6)
Location: include/linux/rculist.h:525
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff811837a3)
Location: include/linux/rculist.h:525
Inline: True
```
```
In kernel/trace/trace_event_perf.c (ffffffff811aa876)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_add
```
```
In kernel/bpf/devmap.c (ffffffff811ea9b5)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
```
```
In kernel/events/core.c (ffffffff811fc9b5)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
```
```
In mm/mmu_notifier.c (ffffffff81287d80)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In fs/namespace.c (ffffffff812ea48f)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - fs/namespace.c:__attach_mnt
```
```
In fs/notify/mark.c (ffffffff81317181)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
```
In fs/proc/proc_sysctl.c (ffffffff81366d4f)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
```
```
In security/security.c (ffffffff828d15d1)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In security/selinux/avc.c (ffffffff814439b5)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_compute_av
```
```
In security/smack/smack_access.c (ffffffff8146a34f)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/integrity/ima/ima_queue.c (ffffffff8149e8a7)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In block/blk-cgroup.c (ffffffff814f3051)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/net/tun.c (ffffffff81764b06)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In drivers/net/vxlan.c (ffffffff81770e9c)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - drivers/net/vxlan.c:__vxlan_sock_add
  - drivers/net/vxlan.c:__vxlan_sock_add
  - drivers/net/vxlan.c:vxlan_fdb_insert
```
```
In net/core/dev.c (ffffffff8188b057)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:list_netdevice
```
```
In net/core/sock_map.c (ffffffff818d366c)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (ffffffff818e2940)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
```
```
In net/sched/sch_api.c (ffffffff818e9d06)
Location: include/linux/rculist.h:525
Inline: True
```
```
In net/sched/cls_api.c (ffffffff818ee642)
Location: include/linux/rculist.h:525
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81913101)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819315be)
Location: include/linux/rculist.h:525
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81941530)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/devinet.c (ffffffff8194aaa5)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/fib_frontend.c (ffffffff81954ba4)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_new_table
```
```
In net/ipv4/fib_trie.c (ffffffff8195cfda)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv4/ip_tunnel.c (ffffffff819667b5)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81978f5b)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_list
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81984c03)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/ipv6/anycast.c (ffffffff81992b49)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff8199d873)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff819a4e72)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff819a9dac)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/ip6_fib.c (ffffffff819b13bf)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_new_table
```
```
In net/packet/af_packet.c (ffffffff819e8693)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff81a0707d)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_create
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
In kernel/pid.c (ffffffff810bfc0b)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
```
```
In kernel/livepatch/shadow.c (ffffffff81123b19)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
```
In kernel/time/posix-timers.c (ffffffff8113880f)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/kprobes.c (ffffffff81179cd6)
Location: include/linux/rculist.h:525
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff8118ea0b)
Location: include/linux/rculist.h:525
Inline: True
```
```
In kernel/trace/trace_event_perf.c (ffffffff811b5866)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_add
```
```
In kernel/bpf/devmap.c (ffffffff811f5a35)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
```
```
In kernel/events/core.c (ffffffff812079a5)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
```
```
In mm/mmu_notifier.c (ffffffff81293f80)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In fs/namespace.c (ffffffff812f765f)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - fs/namespace.c:__attach_mnt
```
```
In fs/notify/mark.c (ffffffff813240b1)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
```
In fs/proc/proc_sysctl.c (ffffffff81373d4f)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
```
```
In security/security.c (ffffffff828ebc35)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In security/selinux/avc.c (ffffffff8144f015)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_compute_av
```
```
In security/smack/smack_access.c (ffffffff814759cf)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/integrity/ima/ima_queue.c (ffffffff814a9f27)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In block/blk-cgroup.c (ffffffff814fe931)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/net/tun.c (ffffffff817b5566)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/core/dev.c (ffffffff819221a7)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:list_netdevice
```
```
In net/core/sock_map.c (ffffffff8196aa4c)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (ffffffff81979d20)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
```
```
In net/sched/sch_api.c (ffffffff81981396)
Location: include/linux/rculist.h:525
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81985cd2)
Location: include/linux/rculist.h:525
Inline: True
```
```
In net/netfilter/nfnetlink_queue.c (ffffffff8199b148)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_config
```
```
In net/netfilter/nfnetlink_log.c (ffffffff8199bc3a)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_log.c:nfulnl_recv_config
```
```
In net/netfilter/nf_conntrack_expect.c (ffffffff819a2947)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expect_related_report
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expect_related_report
```
```
In net/netfilter/nf_conntrack_helper.c (ffffffff819a38c0)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_helper.c:nf_conntrack_helper_register
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c3de1)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e22ce)
Location: include/linux/rculist.h:525
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819f2240)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/devinet.c (ffffffff819fb885)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/fib_frontend.c (ffffffff81a05984)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_new_table
```
```
In net/ipv4/fib_trie.c (ffffffff81a0ddba)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a26beb)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_list
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81a32893)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/ipv6/anycast.c (ffffffff81a40809)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81a4b533)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81a52b32)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81a57a6c)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/ip6_fib.c (ffffffff81a5f07f)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_new_table
```
```
In net/packet/af_packet.c (ffffffff81a97053)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff81ab633d)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_create
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
In kernel/pid.c (ffffffff810c801a)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
```
```
In kernel/livepatch/shadow.c (ffffffff81130159)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
```
In kernel/time/posix-timers.c (ffffffff8114526a)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/kprobes.c (ffffffff811875b0)
Location: include/linux/rculist.h:525
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff8119c59b)
Location: include/linux/rculist.h:525
Inline: True
```
```
In kernel/trace/trace_event_perf.c (ffffffff811c3906)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_add
```
```
In kernel/bpf/devmap.c (ffffffff81203f95)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
```
```
In kernel/events/core.c (ffffffff81216705)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
```
```
In mm/mmu_notifier.c (ffffffff812a3da1)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In fs/namespace.c (ffffffff8130889f)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - fs/namespace.c:__attach_mnt
```
```
In fs/notify/mark.c (ffffffff81335df0)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
```
In fs/proc/proc_sysctl.c (ffffffff81386908)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
```
```
In security/security.c (ffffffff828f104b)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In security/selinux/avc.c (ffffffff81466420)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_compute_av
```
```
In security/smack/smack_access.c (ffffffff8148d41f)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/integrity/ima/ima_queue.c (ffffffff814c2977)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In block/blk-cgroup.c (ffffffff81517d09)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/net/tun.c (ffffffff817cf752)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/core/dev.c (ffffffff819400c7)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:list_netdevice
```
```
In net/core/sock_map.c (ffffffff8198cebc)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (ffffffff8199c250)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
```
```
In net/sched/sch_api.c (ffffffff819a3916)
Location: include/linux/rculist.h:525
Inline: True
```
```
In net/sched/cls_api.c (ffffffff819a8cd2)
Location: include/linux/rculist.h:525
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff819cd839)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ec01e)
Location: include/linux/rculist.h:525
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819f962e)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/devinet.c (ffffffff81a05bb5)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/fib_frontend.c (ffffffff81a0ff54)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_new_table
```
```
In net/ipv4/fib_trie.c (ffffffff81a185ca)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a3208b)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_list
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3e1c9)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/ipv6/anycast.c (ffffffff81a4c409)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81a5742f)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81a5eac8)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81a63b50)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/ip6_fib.c (ffffffff81a6b52f)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_new_table
```
```
In net/packet/af_packet.c (ffffffff81aa20f6)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff81ac245d)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_create
```
</details>
</li>
</ul>

## Differences
