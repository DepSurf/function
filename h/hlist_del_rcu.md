# Function: <code>hlist_del_rcu</code>

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
In kernel/pid.c (ffffffff8109dfb2)
Location: include/linux/rculist.h:340
Inline: True
Inline callers:
  - kernel/pid.c:free_pid
  - kernel/pid.c:__change_pid
```
```
In kernel/time/posix-timers.c (ffffffff810f10d2)
Location: include/linux/rculist.h:340
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/kprobes.c (ffffffff8112df92)
Location: include/linux/rculist.h:340
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff81144606)
Location: include/linux/rculist.h:340
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:__unregister_ftrace_function_probe
```
```
In kernel/trace/trace_event_perf.c (ffffffff811629bb)
Location: include/linux/rculist.h:340
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/hashtab.c (ffffffff81177558)
Location: include/linux/rculist.h:340
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
```
```
In kernel/events/core.c (ffffffff811786b0)
Location: include/linux/rculist.h:340
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In security/selinux/avc.c (ffffffff81340216)
Location: include/linux/rculist.h:340
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_delete
```
```
In drivers/net/tun.c (ffffffff815edfca)
Location: include/linux/rculist.h:340
Inline: True
```
```
In net/core/dev.c (ffffffff81713942)
Location: include/linux/rculist.h:340
Inline: True
Inline callers:
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:dev_change_name
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177ab17)
Location: include/linux/rculist.h:340
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/fib_trie.c (ffffffff817a0c5e)
Location: include/linux/rculist.h:340
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_trie_unmerge
```
```
In net/ipv6/addrlabel.c (ffffffff817d2726)
Location: include/linux/rculist.h:340
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
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
In kernel/pid.c (ffffffff810a170f)
Location: include/linux/rculist.h:426
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
  - kernel/pid.c:free_pid
```
```
In kernel/time/posix-timers.c (ffffffff810f80e2)
Location: include/linux/rculist.h:426
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/kprobes.c (ffffffff81136365)
Location: include/linux/rculist.h:426
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff8114d1ba)
Location: include/linux/rculist.h:426
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:__unregister_ftrace_function_probe
```
```
In kernel/trace/trace_event_perf.c (ffffffff8116d18b)
Location: include/linux/rculist.h:426
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/hashtab.c (ffffffff81186ac8)
Location: include/linux/rculist.h:426
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
```
In kernel/events/core.c (ffffffff81188b50)
Location: include/linux/rculist.h:426
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In security/selinux/avc.c (ffffffff813758b6)
Location: include/linux/rculist.h:426
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_delete
```
```
In drivers/net/tun.c (ffffffff8164d0ba)
Location: include/linux/rculist.h:426
Inline: True
```
```
In net/core/dev.c (ffffffff8177b5a4)
Location: include/linux/rculist.h:426
Inline: True
Inline callers:
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ea372)
Location: include/linux/rculist.h:426
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/fib_trie.c (ffffffff8180ecbb)
Location: include/linux/rculist.h:426
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/ipv6/addrlabel.c (ffffffff818407a2)
Location: include/linux/rculist.h:426
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
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
In kernel/pid.c (ffffffff810a67cf)
Location: include/linux/rculist.h:424
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
  - kernel/pid.c:free_pid
```
```
In kernel/time/posix-timers.c (ffffffff81105a72)
Location: include/linux/rculist.h:424
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/kprobes.c (ffffffff811400e5)
Location: include/linux/rculist.h:424
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff811570fa)
Location: include/linux/rculist.h:424
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:__unregister_ftrace_function_probe
```
```
In kernel/trace/trace_event_perf.c (ffffffff8117845b)
Location: include/linux/rculist.h:424
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/hashtab.c (ffffffff81193862)
Location: include/linux/rculist.h:424
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
```
```
In kernel/events/core.c (ffffffff81197f30)
Location: include/linux/rculist.h:424
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In security/selinux/avc.c (ffffffff8138c1e6)
Location: include/linux/rculist.h:424
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_delete
```
```
In drivers/net/tun.c (ffffffff8167edfa)
Location: include/linux/rculist.h:424
Inline: True
```
```
In net/core/dev.c (ffffffff817a8c14)
Location: include/linux/rculist.h:424
Inline: True
Inline callers:
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81818b67)
Location: include/linux/rculist.h:424
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/fib_trie.c (ffffffff818400f3)
Location: include/linux/rculist.h:424
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff8184f5fc)
Location: include/linux/rculist.h:424
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff818583bb)
Location: include/linux/rculist.h:424
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/addrlabel.c (ffffffff81872422)
Location: include/linux/rculist.h:424
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
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
In kernel/pid.c (ffffffff810a373f)
Location: include/linux/rculist.h:424
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
  - kernel/pid.c:free_pid
```
```
In kernel/time/posix-timers.c (ffffffff81107c62)
Location: include/linux/rculist.h:424
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/kprobes.c (ffffffff8114147d)
Location: include/linux/rculist.h:424
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff8115a184)
Location: include/linux/rculist.h:424
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
```
```
In kernel/trace/trace_event_perf.c (ffffffff8117b14b)
Location: include/linux/rculist.h:424
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/events/core.c (ffffffff8119fa50)
Location: include/linux/rculist.h:424
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In security/selinux/avc.c (ffffffff813a1f36)
Location: include/linux/rculist.h:424
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_delete
```
```
In drivers/net/tun.c (ffffffff816940da)
Location: include/linux/rculist.h:424
Inline: True
```
```
In net/core/dev.c (ffffffff817c72b4)
Location: include/linux/rculist.h:424
Inline: True
Inline callers:
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183934a)
Location: include/linux/rculist.h:424
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/fib_trie.c (ffffffff81861696)
Location: include/linux/rculist.h:424
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff818730dc)
Location: include/linux/rculist.h:424
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff8187c227)
Location: include/linux/rculist.h:424
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/addrlabel.c (ffffffff81897192)
Location: include/linux/rculist.h:424
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
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
In kernel/pid.c (ffffffff810a9f2f)
Location: include/linux/rculist.h:425
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/time/posix-timers.c (ffffffff81112de2)
Location: include/linux/rculist.h:425
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/kprobes.c (ffffffff8114e31d)
Location: include/linux/rculist.h:425
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff81166c94)
Location: include/linux/rculist.h:425
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
```
```
In kernel/trace/trace_event_perf.c (ffffffff811889d8)
Location: include/linux/rculist.h:425
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/events/core.c (ffffffff811b33c0)
Location: include/linux/rculist.h:425
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In security/selinux/avc.c (ffffffff813c7d36)
Location: include/linux/rculist.h:425
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_delete
```
```
In drivers/net/tun.c (ffffffff816fe0da)
Location: include/linux/rculist.h:425
Inline: True
```
```
In net/core/dev.c (ffffffff81840e94)
Location: include/linux/rculist.h:425
Inline: True
Inline callers:
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818b8af3)
Location: include/linux/rculist.h:425
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/fib_trie.c (ffffffff818e17f5)
Location: include/linux/rculist.h:425
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f3aec)
Location: include/linux/rculist.h:425
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff818fcf57)
Location: include/linux/rculist.h:425
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/addrlabel.c (ffffffff819186c6)
Location: include/linux/rculist.h:425
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
```
```
In net/ipv6/route.c (ffffffff8191a9fe)
Location: include/linux/rculist.h:425
Inline: True
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
In kernel/pid.c (ffffffff810b0b5f)
Location: include/linux/rculist.h:438
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/time/posix-timers.c (ffffffff8111e8d2)
Location: include/linux/rculist.h:438
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/kprobes.c (ffffffff8115cc5f)
Location: include/linux/rculist.h:438
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff81175994)
Location: include/linux/rculist.h:438
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
```
```
In kernel/trace/trace_event_perf.c (ffffffff81197e48)
Location: include/linux/rculist.h:438
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/sockmap.c (ffffffff811d02de)
Location: include/linux/rculist.h:438
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:sock_hash_delete_elem
  - kernel/bpf/sockmap.c:sock_hash_free
  - kernel/bpf/sockmap.c:bpf_tcp_close
```
```
In kernel/events/core.c (ffffffff811d2b20)
Location: include/linux/rculist.h:438
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In security/selinux/avc.c (ffffffff813f7385)
Location: include/linux/rculist.h:438
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_delete
```
```
In drivers/net/tun.c (ffffffff8173c2d5)
Location: include/linux/rculist.h:438
Inline: True
```
```
In net/core/dev.c (ffffffff81890eb5)
Location: include/linux/rculist.h:438
Inline: True
Inline callers:
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8190dfbc)
Location: include/linux/rculist.h:438
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/fib_trie.c (ffffffff8193844e)
Location: include/linux/rculist.h:438
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194a3fc)
Location: include/linux/rculist.h:438
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff819539de)
Location: include/linux/rculist.h:438
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/addrlabel.c (ffffffff8196ff0b)
Location: include/linux/rculist.h:438
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
```
```
In net/ipv6/route.c (ffffffff81971896)
Location: include/linux/rculist.h:438
Inline: True
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
In kernel/pid.c (ffffffff810b9c38)
Location: include/linux/rculist.h:453
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/time/posix-timers.c (ffffffff8112a0a2)
Location: include/linux/rculist.h:453
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/kprobes.c (ffffffff81169914)
Location: include/linux/rculist.h:453
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff811835d4)
Location: include/linux/rculist.h:453
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
```
```
In kernel/trace/trace_event_perf.c (ffffffff811a5f98)
Location: include/linux/rculist.h:453
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/events/core.c (ffffffff811e2e20)
Location: include/linux/rculist.h:453
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In security/selinux/avc.c (ffffffff81412e35)
Location: include/linux/rculist.h:453
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_delete
```
```
In drivers/net/tun.c (ffffffff8175fc15)
Location: include/linux/rculist.h:453
Inline: True
```
```
In net/core/dev.c (ffffffff818b1495)
Location: include/linux/rculist.h:453
Inline: True
Inline callers:
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/sock_map.c (ffffffff818f3410)
Location: include/linux/rculist.h:453
Inline: True
Inline callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193c3ac)
Location: include/linux/rculist.h:453
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/fib_trie.c (ffffffff81967e55)
Location: include/linux/rculist.h:453
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197c380)
Location: include/linux/rculist.h:453
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff8198638e)
Location: include/linux/rculist.h:453
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/addrlabel.c (ffffffff819a5b2b)
Location: include/linux/rculist.h:453
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
```
```
In net/ipv6/route.c (ffffffff819a895f)
Location: include/linux/rculist.h:453
Inline: True
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
In kernel/pid.c (ffffffff810bfb47)
Location: include/linux/rculist.h:453
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/time/posix-timers.c (ffffffff811349d9)
Location: include/linux/rculist.h:453
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/kprobes.c (ffffffff811767d9)
Location: include/linux/rculist.h:453
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff81190353)
Location: include/linux/rculist.h:453
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
```
```
In kernel/trace/trace_event_perf.c (ffffffff811b3e98)
Location: include/linux/rculist.h:453
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/events/core.c (ffffffff811f9fd0)
Location: include/linux/rculist.h:453
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In security/selinux/avc.c (ffffffff814408c5)
Location: include/linux/rculist.h:453
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_delete
```
```
In drivers/net/tun.c (ffffffff8179d325)
Location: include/linux/rculist.h:453
Inline: True
```
```
In net/core/dev.c (ffffffff818fe246)
Location: include/linux/rculist.h:453
Inline: True
Inline callers:
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/sock_map.c (ffffffff819458e4)
Location: include/linux/rculist.h:453
Inline: True
Inline callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a07e0)
Location: include/linux/rculist.h:453
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/fib_trie.c (ffffffff819cdfe2)
Location: include/linux/rculist.h:453
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e56ac)
Location: include/linux/rculist.h:453
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff819f01b1)
Location: include/linux/rculist.h:453
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/addrlabel.c (ffffffff81a1209d)
Location: include/linux/rculist.h:453
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
```
```
In net/ipv6/route.c (ffffffff81a1645f)
Location: include/linux/rculist.h:453
Inline: True
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
In kernel/pid.c (ffffffff810c5f18)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/time/posix-timers.c (ffffffff811409ec)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/kprobes.c (ffffffff81182709)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff8119c32e)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
```
```
In kernel/trace/trace_event_perf.c (ffffffff811bf4c8)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/devmap.c (ffffffff811ff26b)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffff812070a0)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In security/selinux/avc.c (ffffffff8145a195)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_delete
```
```
In drivers/net/tun.c (ffffffff817c0dc5)
Location: include/linux/rculist.h:473
Inline: True
```
```
In net/core/dev.c (ffffffff81930576)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/sock_map.c (ffffffff8197a904)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d73b4)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/fib_trie.c (ffffffff81a04ba3)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1c6dc)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81a27081)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/addrlabel.c (ffffffff81a48cbd)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
```
```
In net/ipv6/route.c (ffffffff81a4d09f)
Location: include/linux/rculist.h:473
Inline: True
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
In kernel/pid.c (ffffffff810cdc9e)
Location: include/linux/rculist.h:483
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/time/posix-timers.c (ffffffff8114fbaf)
Location: include/linux/rculist.h:483
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/kprobes.c (ffffffff81195e4f)
Location: include/linux/rculist.h:483
Inline: True
Inline callers:
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:do_unoptimize_kprobes
```
```
In kernel/trace/ftrace.c (ffffffff811b1a06)
Location: include/linux/rculist.h:483
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:dup_hash
```
```
In kernel/trace/trace_event_perf.c (ffffffff811d8dd8)
Location: include/linux/rculist.h:483
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/devmap.c (ffffffff8122661c)
Location: include/linux/rculist.h:483
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_remove_netdev
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffff812305b0)
Location: include/linux/rculist.h:483
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In security/selinux/avc.c (ffffffff814adac6)
Location: include/linux/rculist.h:483
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_flush
```
```
In drivers/net/tun.c (ffffffff8188b188)
Location: include/linux/rculist.h:483
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_flush
```
```
In net/core/dev.c (ffffffff81a0d8c9)
Location: include/linux/rculist.h:483
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:netdev_name_node_alt_destroy
```
```
In net/core/sock_map.c (ffffffff81a4ea49)
Location: include/linux/rculist.h:483
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac5e2a)
Location: include/linux/rculist.h:483
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/fib_trie.c (ffffffff81af45d4)
Location: include/linux/rculist.h:483
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_free
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0da9c)
Location: include/linux/rculist.h:483
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/xfrm/xfrm_state.c (ffffffff81b18311)
Location: include/linux/rculist.h:483
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/addrlabel.c (ffffffff81b3f58d)
Location: include/linux/rculist.h:483
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_del
```
```
In net/ipv6/route.c (ffffffff81b42cba)
Location: include/linux/rculist.h:483
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
In kernel/pid.c (ffffffff810c8768)
Location: include/linux/rculist.h:512
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/time/posix-timers.c (ffffffff8114be2f)
Location: include/linux/rculist.h:512
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/kprobes.c (ffffffff81192b19)
Location: include/linux/rculist.h:512
Inline: True
Inline callers:
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:do_unoptimize_kprobes
```
```
In kernel/trace/ftrace.c (ffffffff811af476)
Location: include/linux/rculist.h:512
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:dup_hash
```
```
In kernel/trace/trace_event_perf.c (ffffffff811d5ef8)
Location: include/linux/rculist.h:512
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/devmap.c (ffffffff8122d20c)
Location: include/linux/rculist.h:512
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_remove_netdev
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffff8123a210)
Location: include/linux/rculist.h:512
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In fs/eventpoll.c (ffffffff8137adbe)
Location: include/linux/rculist.h:512
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In security/selinux/avc.c (ffffffff814cb546)
Location: include/linux/rculist.h:512
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_flush
```
```
In drivers/net/tun.c (ffffffff81899328)
Location: include/linux/rculist.h:512
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_flush
```
```
In net/core/dev.c (ffffffff81a05af2)
Location: include/linux/rculist.h:512
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:netdev_name_node_alt_destroy
```
```
In net/core/sock_map.c (ffffffff81a54a29)
Location: include/linux/rculist.h:512
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad1a5a)
Location: include/linux/rculist.h:512
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/fib_trie.c (ffffffff81b013d4)
Location: include/linux/rculist.h:512
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_free
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1bcac)
Location: include/linux/rculist.h:512
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/xfrm/xfrm_state.c (ffffffff81b26c91)
Location: include/linux/rculist.h:512
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/addrlabel.c (ffffffff81b4e02d)
Location: include/linux/rculist.h:512
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_init
  - net/ipv6/addrlabel.c:ip6addrlbl_del
```
```
In net/ipv6/route.c (ffffffff81b514ba)
Location: include/linux/rculist.h:512
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
In kernel/pid.c (ffffffff810ca211)
Location: include/linux/rculist.h:512
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/time/posix-timers.c (ffffffff8114d2df)
Location: include/linux/rculist.h:512
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/kprobes.c (ffffffff81193a57)
Location: include/linux/rculist.h:512
Inline: True
Inline callers:
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff811afcd6)
Location: include/linux/rculist.h:512
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:dup_hash
```
```
In kernel/trace/trace_event_perf.c (ffffffff811d7538)
Location: include/linux/rculist.h:512
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/devmap.c (ffffffff81232648)
Location: include/linux/rculist.h:512
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffff8123ea40)
Location: include/linux/rculist.h:512
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In fs/eventpoll.c (ffffffff8138192a)
Location: include/linux/rculist.h:512
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In security/selinux/avc.c (ffffffff814d1b76)
Location: include/linux/rculist.h:512
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_flush
```
```
In drivers/net/tun.c (ffffffff8187b708)
Location: include/linux/rculist.h:512
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_flush
```
```
In net/core/dev.c (ffffffff819ec43c)
Location: include/linux/rculist.h:512
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:netdev_name_node_alt_destroy
```
```
In net/core/sock_map.c (ffffffff81a50649)
Location: include/linux/rculist.h:512
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abca7a)
Location: include/linux/rculist.h:512
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/fib_trie.c (ffffffff81aeca9a)
Location: include/linux/rculist.h:512
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0999f)
Location: include/linux/rculist.h:512
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/xfrm/xfrm_state.c (ffffffff81b148b1)
Location: include/linux/rculist.h:512
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/addrlabel.c (ffffffff81b3c12f)
Location: include/linux/rculist.h:512
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_init
```
```
In net/ipv6/route.c (ffffffff81b3f3da)
Location: include/linux/rculist.h:512
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
In kernel/pid.c (ffffffff810dd02f)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/time/posix-timers.c (ffffffff811713df)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/kprobes.c (ffffffff811bc964)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff811d9b66)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:dup_hash
```
```
In kernel/trace/trace_event_perf.c (ffffffff812044f8)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/devmap.c (ffffffff8126b9d4)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffff81279500)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In fs/eventpoll.c (ffffffff813ceb6a)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In security/selinux/avc.c (ffffffff8152a907)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_flush
```
```
In drivers/net/tun.c (ffffffff8190cc29)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_flush
```
```
In net/core/dev.c (ffffffff81a9d32c)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:netdev_name_node_alt_destroy
```
```
In net/core/sock_map.c (ffffffff81b091d7)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7980a)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/fib_trie.c (ffffffff81bacd94)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcc928)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd88b1)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/addrlabel.c (ffffffff81c02a1f)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_init
```
```
In net/ipv6/route.c (ffffffff81c0599a)
Location: include/linux/rculist.h:511
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
In kernel/pid.c (ffffffff810f68ef)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/time/posix-timers.c (ffffffff811a5c5b)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/kprobes.c (ffffffff811ef9c0)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff81209155)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:remove_direct_functions_hash
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:dup_hash
```
```
In kernel/trace/trace_event_perf.c (ffffffff8123f9b8)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/devmap.c (ffffffff812ba89b)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffff812cc555)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In fs/eventpoll.c (ffffffff814576aa)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In security/selinux/avc.c (ffffffff815c02d0)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_flush
```
```
In drivers/net/tun.c (ffffffff81a611dd)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_flush
```
```
In net/core/dev.c (ffffffff81c16b23)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:netdev_name_node_alt_destroy
```
```
In net/core/sock_map.c (ffffffff81c8f267)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d09566)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/fib_trie.c (ffffffff81d3fcbe)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d62638)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6f3ed)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/addrlabel.c (ffffffff81d9c641)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_init
```
```
In net/ipv6/route.c (ffffffff81d9ffca)
Location: include/linux/rculist.h:511
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
In kernel/pid.c (ffffffff81118fbb)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/printk/printk.c (ffffffff8118d947)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_force_preferred_locked
```
```
In kernel/time/posix-timers.c (ffffffff811e573b)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/kprobes.c (ffffffff8123766b)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff81251785)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:remove_direct_functions_hash
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:dup_hash
```
```
In kernel/trace/trace_event_perf.c (ffffffff8128d4a8)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/devmap.c (ffffffff8131dd67)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffff81334335)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In fs/eventpoll.c (ffffffff814e695a)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In fs/crypto/keyring.c (ffffffff814fe672)
Location: include/linux/rculist.h:511
Inline: True
```
```
In security/selinux/avc.c (ffffffff8166c810)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_flush
```
```
In drivers/net/tun.c (ffffffff81bec4d8)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_flush
```
```
In net/core/dev.c (ffffffff81dd0e10)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:netdev_name_node_alt_destroy
```
```
In net/core/sock_map.c (ffffffff81e4a4c7)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ece80a)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/fib_trie.c (ffffffff81f088ee)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f2d138)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3ab5d)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/addrlabel.c (ffffffff81f6b331)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_init
```
```
In net/ipv6/route.c (ffffffff81f6f1da)
Location: include/linux/rculist.h:511
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
In kernel/pid.c (ffffffff81126477)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/printk/printk.c (ffffffff8119f0ed)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_force_preferred_locked
```
```
In kernel/time/posix-timers.c (ffffffff811fa4b9)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_timer_unhash_and_free
```
```
In kernel/kprobes.c (ffffffff8124e72b)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff81268c22)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:remove_direct_functions_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:dup_hash
```
```
In kernel/trace/trace_event_perf.c (ffffffff812aa428)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/devmap.c (ffffffff8134daa5)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffff813650b5)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In fs/eventpoll.c (ffffffff8151d570)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - fs/eventpoll.c:__ep_remove
```
```
In fs/crypto/keyring.c (ffffffff81535ef7)
Location: include/linux/rculist.h:511
Inline: True
```
```
In security/selinux/avc.c (ffffffff816a58a2)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_ss_reset
```
```
In drivers/net/tun.c (ffffffff81c44b58)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_flush
```
```
In net/core/dev.c (ffffffff81e41a3e)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:netdev_name_node_alt_destroy
```
```
In net/core/sock_map.c (ffffffff81ea5bd7)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2dbca)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/fib_trie.c (ffffffff81f683fe)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f8cc38)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9a57d)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/addrlabel.c (ffffffff81fcb4e7)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_init
```
```
In net/ipv6/route.c (ffffffff81fcf26d)
Location: include/linux/rculist.h:511
Inline: True
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
In kernel/pid.c (ffffffff81130a7f)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/printk/printk.c (ffffffff811ae1dd)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_force_preferred_locked
```
```
In kernel/time/posix-timers.c (ffffffff812106a9)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_timer_unhash_and_free
```
```
In kernel/kprobes.c (ffffffff8126865b)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff81288c96)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
```
```
In kernel/trace/trace_event_perf.c (ffffffff812c6138)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/devmap.c (ffffffff81374fc5)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffff8138e085)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In fs/eventpoll.c (ffffffff81551b50)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - fs/eventpoll.c:__ep_remove
```
```
In fs/crypto/keyring.c (ffffffff8156af07)
Location: include/linux/rculist.h:511
Inline: True
```
```
In security/selinux/avc.c (ffffffff816e22e2)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_ss_reset
```
```
In drivers/net/tun.c (ffffffff81cfa6b8)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_flush
```
```
In net/core/dev.c (ffffffff81ef71cd)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit_net
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:netdev_name_node_alt_destroy
```
```
In net/core/sock_map.c (ffffffff81f68697)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff73d4)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_clear_md5_list
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/fib_trie.c (ffffffff8202ea2e)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
```
```
In net/ipv4/tcp_ao.c (ffffffff82055045)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_ao_del_cmd
  - net/ipv4/tcp_ao.c:tcp_ao_connect_init
  - net/ipv4/tcp_ao.c:tcp_ao_destroy_sock
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205a5c8)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/xfrm/xfrm_state.c (ffffffff820678dd)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/addrlabel.c (ffffffff82098cc7)
Location: include/linux/rculist.h:511
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_init
```
```
In net/ipv6/route.c (ffffffff8209cacd)
Location: include/linux/rculist.h:511
Inline: True
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
In kernel/pid.c (ffff8000101245b0)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/time/posix-timers.c (ffff8000101ab880)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/kprobes.c (ffff8000101f72f0)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In kernel/trace/ftrace.c (ffff8000102151d0)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
```
```
In kernel/trace/trace_event_perf.c (ffff80001023eb44)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/devmap.c (ffff800010287270)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffff800010290c88)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In security/selinux/avc.c (ffff800010546924)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_delete
```
```
In drivers/net/tun.c (ffff8000109db224)
Location: include/linux/rculist.h:473
Inline: True
```
```
In net/core/dev.c (ffff800010bcc4e0)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/sock_map.c (ffff800010c21ce0)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8c1e4)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/fib_trie.c (ffff800010cbd760)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/xfrm/xfrm_policy.c (ffff800010cd8948)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffff800010ce5fb8)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/addrlabel.c (ffff800010d0c108)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
```
```
In net/ipv6/route.c (ffff800010d0ea28)
Location: include/linux/rculist.h:473
Inline: True
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
In kernel/pid.c (c03776f4)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/time/posix-timers.c (c03f63e8)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/kprobes.c (c0437d84)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (c0453f10)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
```
```
In kernel/trace/trace_event_perf.c (c047a1b0)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/devmap.c (c04b7378)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (c04c0370)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In security/selinux/avc.c (c06fc300)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_delete
```
```
In drivers/net/tun.c (c0ac17d8)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_delete
```
```
In net/core/dev.c (c0ce45d0)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/sock_map.c (c0d39298)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/ipv4/tcp_ipv4.c (c0d99d28)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/fib_trie.c (c0dc9110)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/xfrm/xfrm_policy.c (c0de2520)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (c0deced8)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/addrlabel.c (c0e11e84)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
```
```
In net/ipv6/route.c (c0e15f98)
Location: include/linux/rculist.h:473
Inline: True
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
In kernel/pid.c (c00000000016e238)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/time/posix-timers.c (c00000000020eba4)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/kprobes.c (c00000000026e778)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (c000000000296918)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
```
```
In kernel/trace/trace_event_perf.c (c0000000002cea68)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/devmap.c (c000000000331674)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (c00000000033db80)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In security/selinux/avc.c (c00000000069d130)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_delete
```
```
In drivers/net/tun.c (c000000000a9cc38)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_delete
```
```
In net/core/dev.c (c000000000cab68c)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/sock_map.c (c000000000d14380)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/ipv4/tcp_ipv4.c (c000000000d97e38)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/fib_trie.c (c000000000dd7964)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/xfrm/xfrm_policy.c (c000000000df915c)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_bydst_resize
  - net/xfrm/xfrm_policy.c:xfrm_bydst_resize
```
```
In net/xfrm/xfrm_state.c (c000000000e07718)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/addrlabel.c (c000000000e36a14)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
```
```
In net/ipv6/route.c (c000000000e3bed0)
Location: include/linux/rculist.h:473
Inline: True
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
In kernel/pid.c (ffffffe0000dc60a)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/time/posix-timers.c (ffffffe0001360b6)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/trace/ftrace.c (ffffffe000174f0c)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
```
```
In kernel/trace/trace_event_perf.c (ffffffe0001940c8)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/devmap.c (ffffffe0001bb4d6)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffe0001c367c)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In security/selinux/avc.c (ffffffe0003a2040)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_alloc_node
```
```
In drivers/net/tun.c (ffffffe00062592e)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_delete
```
```
In net/core/dev.c (ffffffe000757f4e)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/sock_map.c (ffffffe00079aad2)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eb350)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/fib_trie.c (ffffffe000813a46)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffe000828e6c)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffe000831e66)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/addrlabel.c (ffffffe000852fba)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
```
```
In net/ipv6/route.c (ffffffe00085500a)
Location: include/linux/rculist.h:473
Inline: True
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
In kernel/pid.c (ffffffff810c0297)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/time/posix-timers.c (ffffffff8113919c)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/kprobes.c (ffffffff8117ad29)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff8119494e)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
```
```
In kernel/trace/trace_event_perf.c (ffffffff811b7ae8)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/devmap.c (ffffffff811f788b)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffff811ff6c0)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In security/selinux/avc.c (ffffffff81452775)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_delete
```
```
In drivers/net/tun.c (ffffffff81785895)
Location: include/linux/rculist.h:473
Inline: True
```
```
In net/core/dev.c (ffffffff818d0576)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/sock_map.c (ffffffff8191a774)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81977224)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/fib_trie.c (ffffffff819a4943)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bbd6c)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff819c6711)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/addrlabel.c (ffffffff819e834d)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
```
```
In net/ipv6/route.c (ffffffff819ec72f)
Location: include/linux/rculist.h:473
Inline: True
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
In kernel/pid.c (ffffffff810aeaa8)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/time/posix-timers.c (ffffffff8112bbec)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/kprobes.c (ffffffff8116dec9)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff81187a5e)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
```
```
In kernel/trace/trace_event_perf.c (ffffffff811aa8c8)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/devmap.c (ffffffff811ea5db)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffff811f2410)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In security/selinux/avc.c (ffffffff814431c5)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_delete
```
```
In drivers/net/tun.c (ffffffff817651e5)
Location: include/linux/rculist.h:473
Inline: True
```
```
In drivers/net/vxlan.c (ffffffff8176d284)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_fdb_destroy
```
```
In net/core/dev.c (ffffffff8188a456)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/sock_map.c (ffffffff818d4524)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81930ce4)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/fib_trie.c (ffffffff8195e403)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff81978b5c)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81983501)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/addrlabel.c (ffffffff819a510d)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
```
```
In net/ipv6/route.c (ffffffff819a94ef)
Location: include/linux/rculist.h:473
Inline: True
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
In kernel/pid.c (ffffffff810bf7e8)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/time/posix-timers.c (ffffffff81136ebc)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/kprobes.c (ffffffff81178af9)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff8119271e)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
```
```
In kernel/trace/trace_event_perf.c (ffffffff811b58b8)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/devmap.c (ffffffff811f565b)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffff811fd490)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In security/selinux/avc.c (ffffffff8144e815)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_delete
```
```
In drivers/net/tun.c (ffffffff817b5c45)
Location: include/linux/rculist.h:473
Inline: True
```
```
In net/core/dev.c (ffffffff81921576)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/sock_map.c (ffffffff8196b904)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/netfilter/nfnetlink_queue.c (ffffffff8199b049)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_config
  - net/netfilter/nfnetlink_queue.c:nfqnl_rcv_nl_event
```
```
In net/netfilter/nfnetlink_log.c (ffffffff8199b6c5)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_log.c:__instance_destroy
```
```
In net/netfilter/nf_conntrack_expect.c (ffffffff819a21d4)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_expect.c:nf_ct_unlink_expect_report
  - net/netfilter/nf_conntrack_expect.c:nf_ct_unlink_expect_report
```
```
In net/netfilter/nf_conntrack_helper.c (ffffffff819a362a)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_helper.c:nf_conntrack_helper_unregister
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e19f4)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/fib_trie.c (ffffffff81a0f1e3)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a267ec)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81a31191)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/addrlabel.c (ffffffff81a52dcd)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
```
```
In net/ipv6/route.c (ffffffff81a571af)
Location: include/linux/rculist.h:473
Inline: True
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
In kernel/pid.c (ffffffff810c7bf7)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/time/posix-timers.c (ffffffff8114394c)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/kprobes.c (ffffffff811863c9)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff811a02ae)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
```
```
In kernel/trace/trace_event_perf.c (ffffffff811c3958)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/devmap.c (ffffffff81203bb5)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffff8120c1f0)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In security/selinux/avc.c (ffffffff81465be5)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_delete
```
```
In drivers/net/tun.c (ffffffff817cffe5)
Location: include/linux/rculist.h:473
Inline: True
```
```
In net/core/dev.c (ffffffff8193be58)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/sock_map.c (ffffffff8198dd74)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819eb724)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/fib_trie.c (ffffffff81a19a33)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a31c9c)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3ca91)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/addrlabel.c (ffffffff81a5ed48)
Location: include/linux/rculist.h:473
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
```
```
In net/ipv6/route.c (ffffffff81a6325f)
Location: include/linux/rculist.h:473
Inline: True
```
</details>
</li>
</ul>

## Differences
