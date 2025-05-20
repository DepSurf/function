# Function: <code>atomic_inc_not_zero</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006c8c)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In kernel/cred.c (ffffffff810c4865)
Location: include/linux/atomic-fallback.h:1125
Inline: True
```
```
In kernel/futex.c (ffffffff8113ebc8)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/module.c (ffffffff81145f35)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
```
```
In kernel/events/core.c (ffffffff81202cec)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In kernel/events/uprobes.c (ffffffff8120d87d)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/rmap.c (ffffffff812668eb)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff8127b729)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/huge_memory.c (ffffffff812a3bfb)
Location: include/linux/atomic-fallback.h:1125
Inline: True
```
```
In mm/hmm.c (ffffffff812c2e7d)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_register
```
```
In fs/super.c (ffffffff812ce6ea)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/userfaultfd.c (ffffffff81326d6e)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff81330cec)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/proc/task_mmu.c (ffffffff81356a4b)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff8135d46a)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/proc_sysctl.c (ffffffff81365703)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/kernfs/dir.c (ffffffff8136c530)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81680415)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/iommu/intel-svm.c (ffffffff816cd61d)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/base/power/runtime.c (ffffffff816e7e6b)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_if_in_use
```
```
In drivers/net/loopback.c (ffffffff81793ed7)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff818e1c20)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff818e68a6)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff81901640)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff8191353e)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff81925c7e)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff819459eb)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/netfilter/nf_queue.c (ffffffff8196fbf4)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff819756b7)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_options.c (ffffffff81979f60)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff8197b035)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff8197f3f8)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a39d7)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819a5c42)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819a97a9)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff819aecc9)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff819b527a)
Location: include/linux/atomic-fallback.h:1125
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff819b74ca)
Location: include/linux/atomic-fallback.h:1125
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819d9a0a)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff819eccc2)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (ffffffff819f5647)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819f66d3)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a048e4)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81a15103)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a36965)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a3fd6d)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81a42fe8)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81a48f40)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff81a4e133)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
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
In arch/x86/events/core.c (ffffffff81006d1a)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In kernel/cred.c (ffffffff810cd915)
Location: include/linux/atomic-fallback.h:1125
Inline: True
```
```
In kernel/module.c (ffffffff81151ac5)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
```
```
In kernel/events/core.c (ffffffff8120fbcc)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In kernel/events/uprobes.c (ffffffff8121aead)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/rmap.c (ffffffff8127520b)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff8128b209)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/huge_memory.c (ffffffff812b50fb)
Location: include/linux/atomic-fallback.h:1125
Inline: True
```
```
In mm/hmm.c (ffffffff812d4d14)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_register
```
```
In fs/super.c (ffffffff812e019a)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/userfaultfd.c (ffffffff81339afe)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff813446ed)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/proc/task_mmu.c (ffffffff8136f083)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff81374eaa)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/proc_sysctl.c (ffffffff8137d993)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/kernfs/dir.c (ffffffff813846e0)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816a2ac5)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/iommu/intel-svm.c (ffffffff816f145d)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/base/power/runtime.c (ffffffff8170becb)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_if_in_use
```
```
In drivers/net/loopback.c (ffffffff817b7a07)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/vfio/vfio.c (ffffffff817d069a)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_add_container_user
```
```
In net/core/sock.c (ffffffff81913de0)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819189ee)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff8193396e)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81945b9e)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff819582ce)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff8197aa0b)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/netfilter/nf_queue.c (ffffffff819a6573)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff819ac0d3)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_options.c (ffffffff819b08c0)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff819b19a5)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff819b5938)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819da6d9)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819dca02)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819e0469)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff819e59e6)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff819ebfa8)
Location: include/linux/atomic-fallback.h:1125
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff819ee1ca)
Location: include/linux/atomic-fallback.h:1125
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a1086a)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a23cd2)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2c2f7)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2d353)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a3b4d5)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81a4bcde)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6d485)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a769dd)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81a79b48)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81a7fb30)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff81a84d84)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
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
In arch/x86/events/core.c (ffffffff81007d7a)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In kernel/cred.c (ffffffff810d7575)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
```
```
In kernel/module.c (ffffffff811636c5)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
```
```
In kernel/events/core.c (ffffffff81239fa3)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In kernel/events/uprobes.c (ffffffff81245827)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/rmap.c (ffffffff812a6623)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff812be3df)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/huge_memory.c (ffffffff812e86ec)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - mm/huge_memory.c:get_huge_zero_page
```
```
In fs/super.c (ffffffff81317a2e)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/userfaultfd.c (ffffffff81373520)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff8137bf92)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
```
```
In fs/io-wq.c (ffffffff8138a5d0)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - fs/io-wq.c:io_worker_handle_work
```
```
In fs/proc/task_mmu.c (ffffffff813b6753)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff813b9eb6)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff813bdb5a)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/kernfs/dir.c (ffffffff813cf1ae)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff817548a5)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/iommu/intel/svm.c (ffffffff817a974c)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/base/power/runtime.c (ffffffff817c75ad)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
```
```
In drivers/net/loopback.c (ffffffff8187eb47)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/vfio/vfio.c (ffffffff8189b7f5)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_add_container_user
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a2841)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
```
```
In net/core/sock.c (ffffffff819e3870)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819eb716)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff81a08615)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81a1621f)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff81a29bbe)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff81a4fec7)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
```
```
In net/netfilter/nf_queue.c (ffffffff81a8f908)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81a93f44)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_options.c (ffffffff81a9a750)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81a9c1e9)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a9feeb)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac5d55)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac9ae1)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81acda9b)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff81ad5795)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81ad9d17)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81adbf8e)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b022a3)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b15cf2)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1e76f)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1ff71)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:skb_dst_pop
```
```
In net/ipv6/ip6_output.c (ffffffff81b30a94)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81b316a5)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b40e10)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67085)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b70c41)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81b747ed)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81b7a940)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff81b80119)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
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
In arch/x86/events/core.c (ffffffff81006e2a)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068071)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In kernel/cred.c (ffffffff810d2237)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
```
```
In kernel/module.c (ffffffff8115ddf2)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
```
```
In kernel/events/core.c (ffffffff81243631)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In kernel/events/uprobes.c (ffffffff8124fe47)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/rmap.c (ffffffff812b1ab8)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff812c9ff9)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/huge_memory.c (ffffffff812f39fc)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - mm/huge_memory.c:get_huge_zero_page
```
```
In fs/super.c (ffffffff81322c8e)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/userfaultfd.c (ffffffff813813d0)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff8138cf23)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
```
```
In fs/io-wq.c (ffffffff8139bd60)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - fs/io-wq.c:io_impersonate_work
```
```
In fs/proc/task_mmu.c (ffffffff813c86b3)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff813cb946)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff813cf8aa)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/kernfs/dir.c (ffffffff813e0dde)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8176fba5)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/iommu/intel/svm.c (ffffffff817b5b22)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/base/power/runtime.c (ffffffff817dc018)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
```
```
In drivers/net/loopback.c (ffffffff8188d0c7)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/vfio/vfio.c (ffffffff818aa405)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_add_container_user
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b2561)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
```
```
In net/core/sock.c (ffffffff819e33c5)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819eb436)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff81a09bc3)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81a16e80)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff81a2a51e)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff81a55f04)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
```
```
In net/sched/sch_frag.c (ffffffff81a6f3f1)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/netfilter/nf_queue.c (ffffffff81a998f8)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81a9de80)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_options.c (ffffffff81aa46a8)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81aa6049)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aaa776)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad1be5)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad5a31)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ad9adb)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff81ae1d33)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81ae6777)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81ae8aea)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b10644)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b24162)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2d0b1)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2e881)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:skb_dst_pop
```
```
In net/ipv6/ip6_output.c (ffffffff81b3f6c4)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81b40295)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b4f8c6)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b75660)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b7f651)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81b8355d)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81b89890)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff81b8f29c)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
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
In arch/x86/events/core.c (ffffffff8100754a)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810685e1)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In kernel/cred.c (ffffffff810d3e17)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
```
```
In kernel/module.c (ffffffff811600b2)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
```
```
In kernel/events/core.c (ffffffff812485f5)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In kernel/events/uprobes.c (ffffffff81254727)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/rmap.c (ffffffff812b7188)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff812d0a70)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/huge_memory.c (ffffffff812fbdf8)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
```
```
In fs/super.c (ffffffff81328d4e)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/userfaultfd.c (ffffffff81387d78)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff8139774b)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - fs/io_uring.c:io_link_timeout_fn
```
```
In fs/proc/task_mmu.c (ffffffff813cf6f3)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff813d2936)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff813d6977)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/kernfs/dir.c (ffffffff813e790e)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81753555)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/iommu/intel/svm.c (ffffffff81798e40)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/base/power/runtime.c (ffffffff817c03d8)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
```
```
In drivers/net/loopback.c (ffffffff8186fa07)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/vfio/vfio.c (ffffffff8188d755)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_add_container_user
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff81895881)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
```
```
In net/core/sock.c (ffffffff819c940e)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819d1946)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff819f0554)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff819fdb28)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff81a116be)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff81a38f14)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
```
```
In net/sched/sch_frag.c (ffffffff81a57cc4)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/netfilter/nf_queue.c (ffffffff81a84c08)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81a88da4)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_options.c (ffffffff81a8f79d)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81a91209)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a95d25)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abcbf5)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac0a90)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ac4b29)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff81acba06)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81ad1a47)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81ad3da5)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81afe254)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b11d92)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1acf6)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c5df)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d562)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81b2e8a5)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b3d5f6)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b64090)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b6e171)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81b721d0)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81b786e0)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff81b7ec5c)
Location: include/asm-generic/atomic-instrumented.h:796
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
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
In arch/x86/events/core.c (ffffffff81007db6)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81072d77)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In kernel/cred.c (ffffffff810e6ee7)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - kernel/cred.c:get_task_cred
```
```
In kernel/sched/core.c (ffffffff810f24e5)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_core_get
```
```
In kernel/module.c (ffffffff81185262)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
```
```
In kernel/events/core.c (ffffffff81282c4b)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In kernel/events/uprobes.c (ffffffff81290157)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/oom_kill.c (ffffffff812a31ce)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
```
```
In mm/rmap.c (ffffffff812f95a8)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff8131614b)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/huge_memory.c (ffffffff81345c28)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
```
```
In fs/super.c (ffffffff8137637e)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/userfaultfd.c (ffffffff813d5085)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff813df075)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - fs/io_uring.c:io_link_timeout_fn
```
```
In fs/proc/task_mmu.c (ffffffff81420ad3)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff81423e86)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff814280a7)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/kernfs/dir.c (ffffffff8143961e)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
```
```
In fs/fuse/file.c (ffffffff814edea0)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff817d6985)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/iommu/iommu-sva-lib.c (ffffffff8182fb85)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva-lib.c:__mmget_not_zero
```
```
In drivers/base/power/runtime.c (ffffffff8184a745)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
```
```
In drivers/net/loopback.c (ffffffff818fffa7)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/vfio/vfio.c (ffffffff81920cb5)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_add_container_user
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff819297f1)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
```
```
In net/core/sock.c (ffffffff81a787ae)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81a81516)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff81aa1982)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81aaf0f5)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff81ac2b9e)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff81aeede4)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
```
```
In net/sched/sch_frag.c (ffffffff81b10c8c)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/netfilter/nf_queue.c (ffffffff81b3f132)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81b43514)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_options.c (ffffffff81b4a9dd)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81b4c59d)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b51185)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b79985)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7e454)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81b832d9)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff81b8a296)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81b90677)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81b92a65)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81bbf4e4)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd5910)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (ffffffff81bdf263)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81be0f1d)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81bf3712)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81bf4c74)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
```
```
In net/ipv6/route.c (ffffffff81c05686)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2bb50)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81c3619a)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81c3c680)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81c43220)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff81c4a3c1)
Location: include/linux/atomic/atomic-instrumented.h:575
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
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
In arch/x86/events/core.c (ffffffff810072f9)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107e7cd)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81080fa5)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In kernel/cred.c (ffffffff81101191)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/cred.c:get_task_cred
```
```
In kernel/sched/core.c (ffffffff8110e325)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_core_get
```
```
In kernel/module/main.c (ffffffff8118be44)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/module/main.c:try_module_get
```
```
In kernel/events/core.c (ffffffff812ce84e)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In kernel/events/uprobes.c (ffffffff812e5217)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/rmap.c (ffffffff8135fe85)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff813812e0)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/huge_memory.c (ffffffff813bbd9d)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
```
```
In fs/super.c (ffffffff813f5544)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/userfaultfd.c (ffffffff8145d68b)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/proc/task_mmu.c (ffffffff81498908)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff8149c9dd)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff8149df5a)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/kernfs/dir.c (ffffffff814b469e)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
```
```
In fs/fuse/file.c (ffffffff8157d29e)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
```
```
In block/blk-mq-tag.c (ffffffff8168bffd)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_find_and_get_req
```
```
In io_uring/io_uring.c (ffffffff816ce685)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_link_timeout_fn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81914a65)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/iommu/iommu-sva-lib.c (ffffffff81970d85)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva-lib.c:__mmget_not_zero
```
```
In drivers/base/power/runtime.c (ffffffff8198fa49)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
```
```
In drivers/net/loopback.c (ffffffff81a51a6a)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81a7f891)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
```
```
In net/core/sock.c (ffffffff81bec17a)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81bf525a)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff81c19ab5)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81c27e70)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff81c3d85d)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff81c71d3e)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
```
```
In net/sched/sch_frag.c (ffffffff81c97e0e)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/netfilter/nf_queue.c (ffffffff81ccb879)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81ccffd3)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_options.c (ffffffff81cd7841)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81cd9bf1)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81cddf2d)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d09717)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0e442)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81d138e2)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff81d1db79)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81d21afb)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81d2407d)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81d5427e)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6c16a)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (ffffffff81d75fcd)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81d77c6c)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81d89e79)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81d8da9a)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
```
```
In net/ipv6/route.c (ffffffff81d9fc84)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dc90cf)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81dd3d9a)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81ddaa5d)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81de1f9e)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff81de9ab5)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
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
In arch/x86/events/core.c (ffffffff81008b69)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810902ba)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81093a4a)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
```
```
In kernel/cred.c (ffffffff811262a1)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/cred.c:get_task_cred
```
```
In kernel/sched/core.c (ffffffff811350b5)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_core_get
```
```
In kernel/module/main.c (ffffffff811c8574)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/module/main.c:try_module_get
```
```
In kernel/events/core.c (ffffffff8133699a)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:get_pmu_ctx
```
```
In kernel/events/uprobes.c (ffffffff8134ebc4)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/vmscan.c (ffffffff813771ff)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - mm/vmscan.c:should_skip_mm
```
```
In mm/rmap.c (ffffffff813dad6e)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_get_anon_vma
```
```
In mm/swapfile.c (ffffffff813ffb23)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/huge_memory.c (ffffffff8143e2ed)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In fs/super.c (ffffffff8147e7b4)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/userfaultfd.c (ffffffff814ed1ab)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/mbcache.c (ffffffff81514f8f)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
```
```
In fs/proc/task_mmu.c (ffffffff8152cbc6)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff815313dd)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff81532c1a)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/kernfs/dir.c (ffffffff8154b59f)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
```
```
In fs/fuse/file.c (ffffffff81622efe)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
```
```
In block/blk-mq-tag.c (ffffffff8174a76d)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_find_and_get_req
```
```
In io_uring/timeout.c (ffffffff81798f21)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - io_uring/timeout.c:io_link_timeout_fn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81a6fc45)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/iommu/iommu-sva.c (ffffffff81adbe81)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
  - drivers/iommu/iommu-sva.c:__mmget_not_zero
```
```
In drivers/base/power/runtime.c (ffffffff81affbc9)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
```
```
In drivers/net/loopback.c (ffffffff81bdacaa)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff81d98b5a)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81da377a)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff81dcaa6a)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81ddaa50)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff81df3d3d)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff81e29e3e)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
```
```
In net/sched/sch_frag.c (ffffffff81e53dae)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/netfilter/nf_queue.c (ffffffff81e8b6c9)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81e901b7)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_options.c (ffffffff81e97ebf)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81e9a381)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81ea1823)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ece9e7)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed3ef2)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ed98a2)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff81ee4c38)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81ee8f3b)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81eeb70d)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f1e45e)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f374ca)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (ffffffff81f4270d)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81f444ae)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81f57e23)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81f5bbca)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
```
```
In net/ipv6/route.c (ffffffff81f6ed24)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f99f0f)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81fa53aa)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81fac76c)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81fb44ce)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff81fbd1f5)
Location: include/linux/atomic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
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
In arch/x86/events/core.c (ffffffff81008399)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810931ce)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810969ca)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
```
```
In kernel/cred.c (ffffffff81133751)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - kernel/cred.c:get_task_cred
```
```
In kernel/sched/core.c (ffffffff811442c5)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_core_get
```
```
In kernel/module/main.c (ffffffff811db4d7)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - kernel/module/main.c:try_module_get
```
```
In kernel/events/core.c (ffffffff8136775a)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:get_pmu_ctx
```
```
In kernel/events/uprobes.c (ffffffff8137fd57)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/vmscan.c (ffffffff813a9271)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - mm/vmscan.c:should_skip_mm
```
```
In mm/rmap.c (ffffffff8140f4ae)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_get_anon_vma
```
```
In mm/swapfile.c (ffffffff814329b3)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/huge_memory.c (ffffffff81473aed)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In fs/super.c (ffffffff814b34e4)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/userfaultfd.c (ffffffff815262ef)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/mbcache.c (ffffffff8154c98f)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
```
```
In fs/proc/task_mmu.c (ffffffff81564ffc)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff81569591)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff8156ae0a)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/kernfs/dir.c (ffffffff815831ef)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
```
```
In fs/fuse/file.c (ffffffff8165b37e)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
```
```
In block/blk-mq-tag.c (ffffffff81786e4d)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_find_and_get_req
```
```
In io_uring/timeout.c (ffffffff817d9dd1)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - io_uring/timeout.c:io_link_timeout_fn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81aba3f5)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/iommu/iommu-sva.c (ffffffff81b2a0a4)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
```
```
In drivers/base/power/runtime.c (ffffffff81b4df31)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff82005d43)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
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
In arch/x86/events/core.c (ffffffff8100dab9)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109a63e)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109df3a)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
```
```
In kernel/sched/core.c (ffffffff8114f7e5)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_core_get
```
```
In kernel/module/main.c (ffffffff811f1187)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - kernel/module/main.c:try_module_get
```
```
In kernel/events/core.c (ffffffff81394b09)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:get_pmu_ctx
```
```
In kernel/events/uprobes.c (ffffffff813a8fa2)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/vmscan.c (ffffffff813dd0bc)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
```
```
In mm/rmap.c (ffffffff8143be78)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_get_anon_vma
```
```
In mm/swapfile.c (ffffffff8146bdd3)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/huge_memory.c (ffffffff814a2ffd)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In fs/super.c (ffffffff814e478c)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - fs/super.c:get_bdev_super
  - fs/super.c:grab_super
```
```
In fs/userfaultfd.c (ffffffff8155953a)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_move
  - fs/userfaultfd.c:userfaultfd_poison
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/mbcache.c (ffffffff815827bf)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
```
```
In fs/proc/task_mmu.c (ffffffff8159c3fc)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff815a1bb1)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff815a37ea)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/kernfs/dir.c (ffffffff815bbe3f)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
```
```
In fs/fuse/file.c (ffffffff8169504e)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
```
```
In block/blk-mq-tag.c (ffffffff817c952d)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_find_and_get_req
```
```
In io_uring/timeout.c (ffffffff8181dfe1)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - io_uring/timeout.c:io_link_timeout_fn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81b0d135)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/iommu/iommu-sva.c (ffffffff81b81274)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
```
```
In drivers/base/power/runtime.c (ffffffff81ba64b1)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff820d4b95)
Location: include/linux/atomic/atomic-instrumented.h:1522
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
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
In kernel/cred.c (ffff80001012cbb0)
Location: include/linux/atomic-fallback.h:1125
Inline: True
```
```
In kernel/module.c (ffff8000101c27b4)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
```
```
In kernel/events/core.c (ffff8000102979c8)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In kernel/events/uprobes.c (ffff8000102a6504)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/rmap.c (ffff80001030b004)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffff8000103265dc)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/huge_memory.c (ffff80001035644c)
Location: include/linux/atomic-fallback.h:1125
Inline: True
```
```
In mm/hmm.c (ffff80001037b0e4)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_register
```
```
In fs/super.c (ffff800010386f4c)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/userfaultfd.c (ffff8000103f8904)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffff80001040630c)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/proc/task_mmu.c (ffff80001043a5e8)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffff800010440550)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/proc_sysctl.c (ffff80001044aa38)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/kernfs/dir.c (ffff8000104534a8)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
```
```
In drivers/tty/hvc/hvc_console.c (ffff800010879c58)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/base/power/runtime.c (ffff8000108fb188)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_if_in_use
```
```
In drivers/net/loopback.c (ffff8000109d0264)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/perf/arm-cci.c (ffff800010b91b98)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:cci_pmu_event_init
```
```
In net/core/sock.c (ffff800010bac178)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffff800010bb4798)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffff800010bd1ac4)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffff800010be7610)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffff800010c010f8)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffff800010c2214c)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/netfilter/nf_queue.c (ffff800010c55df4)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffff800010c5bf8c)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_options.c (ffff800010c60ee4)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffff800010c62360)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffff800010c66860)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8bb24)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c8f96c)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffff800010c940e0)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffff800010c9e30c)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffff800010ca1a88)
Location: include/linux/atomic-fallback.h:1125
Inline: True
```
```
In net/ipv4/icmp.c (ffff800010ca3d38)
Location: include/linux/atomic-fallback.h:1125
Inline: True
```
```
In net/ipv4/ipmr.c (ffff800010ccb494)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffff800010ce0f54)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (ffff800010ceb0d4)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffff800010cec07c)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffff800010cfc5dc)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffff800010d111f8)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d371ac)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffff800010d3fc80)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffff800010d43e2c)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffff800010d4b188)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffff800010d50e14)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
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
In kernel/cred.c (c037cf40)
Location: include/linux/atomic-fallback.h:1125
Inline: True
```
```
In kernel/module.c (c0408ae0)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
```
```
In kernel/acct.c (c040f29c)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (c041bbd4)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (c041ece8)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (c04202f4)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (c0421528)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (c04258f8)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (c04c6fe8)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/events/uprobes.c (c04d5678)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/page-writeback.c (c04e8ddc)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (c05036ac)
Location: include/linux/atomic-fallback.h:1125
Inline: True
```
```
In mm/rmap.c (c0527478)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (c053dfb8)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/slub.c (c0549938)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (c055c764)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hmm.c (c0565c8c)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_register
```
```
In fs/super.c (c056f744)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/fs-writeback.c (c05a70d8)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/userfaultfd.c (c05cc998)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/aio.c (c05cedb0)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (c05d7568)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_get_req
```
```
In fs/proc/task_mmu.c (c0600514)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (c0603bb8)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:mem_rw
```
```
In fs/proc/proc_sysctl.c (c060f8fc)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/kernfs/dir.c (c061605c)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
```
```
In block/bio.c (c0788394)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - block/bio.c:__bio_associate_blkg
```
```
In block/blk-core.c (c0791654)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (c079af88)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (c07a060c)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (c07b9254)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/tty/hvc/hvc_console.c (c097ce74)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/base/power/runtime.c (c09e6698)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_if_in_use
```
```
In drivers/net/loopback.c (c0ab8484)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/perf/arm-cci.c (c0c7b524)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:cci_pmu_event_init
```
```
In net/core/sock.c (c0ccab50)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (c0cd0550)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (c0cec6a8)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (c0cfd740)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (c0d14984)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (c0d3941c)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
```
```
In net/netfilter/nf_queue.c (c0d657f8)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (c0d6b870)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_options.c (c0d70890)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (c0d71b54)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (c0d76370)
Location: include/linux/atomic-fallback.h:1125
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (c0d9c25c)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (c0d9ea30)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (c0da28fc)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (c0da911c)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (c0dae8d0)
Location: include/linux/atomic-fallback.h:1125
Inline: True
```
```
In net/ipv4/icmp.c (c0db09d4)
Location: include/linux/atomic-fallback.h:1125
Inline: True
```
```
In net/ipv4/ipmr.c (c0dd598c)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (c0dea2a0)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (c0df2ea0)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (c0df41e0)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (c0e039f8)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (c0e15580)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/tcp_ipv6.c (c0e39de4)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (c0e429e4)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (c0e45be4)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (c0e4c4f0)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (c0e51994)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
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
In arch/powerpc/perf/core-book3s.c (c0000000001275b4)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - arch/powerpc/perf/core-book3s.c:power_pmu_event_init
```
```
In kernel/cred.c (c000000000175a6c)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - kernel/cred.c:get_task_cred
```
```
In kernel/module.c (c000000000226d5c)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
```
```
In kernel/events/core.c (c00000000034db5c)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In kernel/events/uprobes.c (c0000000003594a0)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/rmap.c (c0000000003dafe8)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (c0000000003fcc90)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/huge_memory.c (c00000000043d6c0)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
```
```
In mm/hmm.c (c00000000046e65c)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_register
```
```
In fs/super.c (c00000000047d05c)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/userfaultfd.c (c0000000004ffd44)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (c00000000050f1b0)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/proc/task_mmu.c (c00000000054b5c4)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (c0000000005555d4)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:mem_rw
```
```
In fs/proc/proc_sysctl.c (c0000000005611d4)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/kernfs/dir.c (c00000000056c818)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
```
```
In drivers/tty/hvc/hvc_console.c (c000000000922278)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/base/power/runtime.c (c00000000099769c)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_if_in_use
```
```
In drivers/net/loopback.c (c000000000a8f1f0)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/vfio/vfio.c (c000000000aaeca8)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_add_container_user
```
```
In net/core/sock.c (c000000000c7e724)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (c000000000c86764)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (c000000000caff70)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (c000000000cc5b84)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (c000000000ce0c98)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (c000000000d14470)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/netfilter/nf_queue.c (c000000000d56554)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (c000000000d5e308)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_options.c (c000000000d641b8)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (c000000000d65620)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (c000000000d6aff4)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_ipv4.c (c000000000d97314)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9e994)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (c000000000da4814)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (c000000000db047c)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (c000000000db4d18)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
```
```
In net/ipv4/icmp.c (c000000000db7744)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
```
```
In net/ipv4/ipmr.c (c000000000de811c)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (c000000000e03398)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (c000000000e0ec80)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (c000000000e103d8)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (c000000000e240e0)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (c000000000e38530)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/tcp_ipv6.c (c000000000e67ea4)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (c000000000e74408)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (c000000000e78988)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (c000000000e81520)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (c000000000e88cdc)
Location: arch/powerpc/include/asm/atomic.h:244
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
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
In kernel/cred.c (ffffffe0000e1750)
Location: include/linux/atomic-fallback.h:1125
Inline: True
```
```
In kernel/module.c (ffffffe000142e58)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
```
```
In kernel/events/core.c (ffffffe0001ce172)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In mm/rmap.c (ffffffe000214a94)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffe00022680c)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hmm.c (ffffffe000251438)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_register
```
```
In fs/super.c (ffffffe000259742)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/userfaultfd.c (ffffffe0002a77c4)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffe0002afcde)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/proc/task_mmu.c (ffffffe0002d2adc)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffe0002d7a8e)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:mem_rw
```
```
In fs/proc/proc_sysctl.c (ffffffe0002dfd50)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/kernfs/dir.c (ffffffe0002e5b16)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
```
```
In drivers/tty/hvc/hvc_console.c (ffffffe00054ad30)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/base/power/runtime.c (ffffffe00058a1c6)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_if_in_use
```
```
In drivers/net/loopback.c (ffffffe00061ccf0)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffe00073ca24)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffe000742506)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffe00075bec2)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffe0007698ba)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffe00077f20e)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffe00079abae)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/netfilter/nf_queue.c (ffffffe0007c0130)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffe0007c5210)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_options.c (ffffffe0007c909e)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffe0007c9f20)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007cd968)
Location: include/linux/atomic-fallback.h:1125
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ee07a)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007efcac)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffe0007f3614)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffe0007f81c4)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffe0007fe29e)
Location: include/linux/atomic-fallback.h:1125
Inline: True
```
```
In net/ipv4/icmp.c (ffffffe0007ffbbe)
Location: include/linux/atomic-fallback.h:1125
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffe00081e7b8)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082fb04)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (ffffffe00083890a)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffe000839ad0)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffe000846e9c)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffe000854ef8)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffe00087323c)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffe00087b9ca)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffe00087e9bc)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffe00088420a)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffe000889120)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
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
In arch/x86/events/core.c (ffffffff81006d1a)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In kernel/cred.c (ffffffff810c7c95)
Location: include/linux/atomic-fallback.h:1125
Inline: True
```
```
In kernel/module.c (ffffffff8114a0e5)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
```
```
In kernel/events/core.c (ffffffff812081ec)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In kernel/events/uprobes.c (ffffffff812134fd)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/rmap.c (ffffffff8126d85b)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff812837e9)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/huge_memory.c (ffffffff812ad6db)
Location: include/linux/atomic-fallback.h:1125
Inline: True
```
```
In mm/hmm.c (ffffffff812cd2f4)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_register
```
```
In fs/super.c (ffffffff812d877a)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/userfaultfd.c (ffffffff813320de)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff8133cccd)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/proc/task_mmu.c (ffffffff81367663)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff8136d48a)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/proc_sysctl.c (ffffffff81375f73)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/kernfs/dir.c (ffffffff8137ccc0)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81668525)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/iommu/intel-svm.c (ffffffff816b6c4d)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/base/power/runtime.c (ffffffff816d161b)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_if_in_use
```
```
In drivers/net/loopback.c (ffffffff8177c4df)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff818b3de0)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff818b89ee)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff818d396e)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff818e5b6e)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff818f829e)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff8191a87b)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/netfilter/nf_queue.c (ffffffff819463e3)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff8194bf43)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_options.c (ffffffff81950730)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81951815)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff819557a8)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197a549)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8197c872)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819802d9)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff81985856)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff8198bdd8)
Location: include/linux/atomic-fallback.h:1125
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff8198df6a)
Location: include/linux/atomic-fallback.h:1125
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819b027a)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c3362)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (ffffffff819cb987)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819cc9e3)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff819dab65)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff819eb36e)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0cb15)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a1606d)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81a191d8)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81a1f1c0)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff81a24414)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
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
In arch/x86/events/core.c (ffffffff8100543a)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In kernel/cred.c (ffffffff810b64b5)
Location: include/linux/atomic-fallback.h:1125
Inline: True
```
```
In kernel/module.c (ffffffff8113d395)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
```
```
In kernel/events/core.c (ffffffff811fb324)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In kernel/events/uprobes.c (ffffffff8120626d)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/rmap.c (ffffffff8125f88b)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff812756a1)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/huge_memory.c (ffffffff8129ed5b)
Location: include/linux/atomic-fallback.h:1125
Inline: True
```
```
In mm/hmm.c (ffffffff812be164)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_register
```
```
In fs/super.c (ffffffff812c93fa)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/userfaultfd.c (ffffffff81322c9e)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff8132d99d)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/proc/task_mmu.c (ffffffff81358303)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff8135df1a)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/proc_sysctl.c (ffffffff81366a43)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/kernfs/dir.c (ffffffff8136d790)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816488a5)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/iommu/intel-svm.c (ffffffff8169488d)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/base/power/runtime.c (ffffffff816ac93b)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_if_in_use
```
```
In drivers/net/loopback.c (ffffffff8175c28f)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/vfio/vfio.c (ffffffff8177a74a)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_add_container_user
```
```
In net/core/sock.c (ffffffff8186dd30)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8187293e)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff8188d7fe)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff8189f9ae)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff818b20ce)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff818d462b)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/netfilter/nf_queue.c (ffffffff818ffed3)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff81905a33)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_options.c (ffffffff8190a220)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff8190b305)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff8190f298)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81934009)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81936332)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81939d99)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff8193f316)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81945898)
Location: include/linux/atomic-fallback.h:1125
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81947a2a)
Location: include/linux/atomic-fallback.h:1125
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8196c8aa)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff81980152)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (ffffffff81988777)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819897d3)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81997925)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff819a812e)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c98d5)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819d2e2d)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff819d5f98)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff819dbf80)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff819e11d4)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
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
In arch/x86/events/core.c (ffffffff81006cda)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In kernel/cred.c (ffffffff810c71e5)
Location: include/linux/atomic-fallback.h:1125
Inline: True
```
```
In kernel/module.c (ffffffff81147f95)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
```
```
In kernel/events/core.c (ffffffff81205fbc)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In kernel/events/uprobes.c (ffffffff8121129d)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/rmap.c (ffffffff8126b5fb)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff812815f9)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/huge_memory.c (ffffffff812ab4eb)
Location: include/linux/atomic-fallback.h:1125
Inline: True
```
```
In mm/hmm.c (ffffffff812cb104)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_register
```
```
In fs/super.c (ffffffff812d658a)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/userfaultfd.c (ffffffff8132fbae)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff8133a79d)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/proc/task_mmu.c (ffffffff81365133)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff8136af5a)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/proc_sysctl.c (ffffffff81373a43)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/kernfs/dir.c (ffffffff8137a790)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81696905)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/iommu/intel-svm.c (ffffffff816e511d)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/base/power/runtime.c (ffffffff816ffb8b)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_if_in_use
```
```
In drivers/net/loopback.c (ffffffff817ac887)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/vfio/vfio.c (ffffffff817c551a)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_add_container_user
```
```
In net/core/sock.c (ffffffff81904de0)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819099ee)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff8192496e)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81936b9e)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff819492ce)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff8196ba0b)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/netfilter/nf_queue.c (ffffffff81997573)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff8199e4d1)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:gc_worker
  - net/netfilter/nf_conntrack_core.c:early_drop
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_find_get
```
```
In net/netfilter/nf_conntrack_standalone.c (ffffffff819a17ae)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_standalone.c:ct_seq_show
```
```
In net/netfilter/nf_conntrack_expect.c (ffffffff819a2e26)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_expect.c:nf_ct_find_expectation
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819b0c15)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_list
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_table
```
```
In net/ipv4/route.c (ffffffff819b6713)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_options.c (ffffffff819baf00)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff819bbfe5)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff819bff78)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e4d19)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819e7042)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819eaaa9)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff819f0026)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff819f65e8)
Location: include/linux/atomic-fallback.h:1125
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff819f880a)
Location: include/linux/atomic-fallback.h:1125
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a1ab1a)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2dde2)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (ffffffff81a36407)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a37463)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a455e5)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81a55dee)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a77595)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a80aed)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81a83c58)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81a89c40)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff81a8ee94)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
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
In arch/x86/events/core.c (ffffffff81006e3a)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In kernel/cred.c (ffffffff810cf720)
Location: include/linux/atomic-fallback.h:1125
Inline: True
```
```
In kernel/module.c (ffffffff81154bae)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
```
```
In kernel/events/core.c (ffffffff81214e73)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In kernel/events/uprobes.c (ffffffff812201ed)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/rmap.c (ffffffff8127af79)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff81291336)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/huge_memory.c (ffffffff812bb83b)
Location: include/linux/atomic-fallback.h:1125
Inline: True
```
```
In mm/hmm.c (ffffffff812dbe64)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_register
```
```
In fs/super.c (ffffffff812e70c8)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/userfaultfd.c (ffffffff8134252e)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff8134d2f8)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/proc/task_mmu.c (ffffffff81378813)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff8137c5fa)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/proc_sysctl.c (ffffffff81386fd5)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/kernfs/dir.c (ffffffff8138e28a)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816b0eb5)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/iommu/intel-svm.c (ffffffff816ff7eb)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/base/power/runtime.c (ffffffff8171a4bb)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_if_in_use
```
```
In drivers/net/loopback.c (ffffffff817c6817)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/vfio/vfio.c (ffffffff817df7ba)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_add_container_user
```
```
In net/core/sock.c (ffffffff81925eaf)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8192aaee)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff81945e0a)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81958354)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff8196abde)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff8198de89)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/netfilter/nf_queue.c (ffffffff819ba253)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff819bff45)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_options.c (ffffffff819c480d)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff819c58f5)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c9951)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ee079)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819f0d10)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819f4980)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff819fa8ad)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81a007f8)
Location: include/linux/atomic-fallback.h:1125
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81a02b78)
Location: include/linux/atomic-fallback.h:1125
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a2597a)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a395c2)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (ffffffff81a41d58)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a42df3)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a512b5)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81a61e1a)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a83de1)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a8d3ad)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81a90578)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81a968a0)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff81a9bc18)
Location: include/linux/atomic-fallback.h:1125
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
</details>
</li>
</ul>

## Differences
