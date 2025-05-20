# Function: <code>arch_atomic_inc_not_zero</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007d7a)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/alternative.c (ffffffff81bbe075)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In kernel/cred.c (ffffffff810d7575)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
```
```
In kernel/module.c (ffffffff811636c5)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
```
```
In kernel/events/core.c (ffffffff81239fa3)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In kernel/events/uprobes.c (ffffffff81245827)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/rmap.c (ffffffff812a6623)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff812be3df)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/huge_memory.c (ffffffff812e86ec)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - mm/huge_memory.c:get_huge_zero_page
```
```
In fs/super.c (ffffffff81317a2e)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/userfaultfd.c (ffffffff81373520)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff8137bf92)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
```
```
In fs/io-wq.c (ffffffff8138a5d0)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - fs/io-wq.c:io_worker_handle_work
```
```
In fs/proc/task_mmu.c (ffffffff813b6753)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff813b9eb6)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff813bdb5a)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/kernfs/dir.c (ffffffff813cf1ae)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff817548a5)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/iommu/intel/svm.c (ffffffff817a974c)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/base/power/runtime.c (ffffffff817c75ad)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
```
```
In drivers/net/loopback.c (ffffffff8187eb47)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/vfio/vfio.c (ffffffff8189b7f5)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_add_container_user
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a2841)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
```
```
In net/core/sock.c (ffffffff819e3870)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819eb716)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff81a08615)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81a1621f)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff81a29bbe)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff81a4fec7)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
```
```
In net/netfilter/nf_queue.c (ffffffff81a8f908)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81a93f44)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_options.c (ffffffff81a9a750)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81a9c1e9)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a9feeb)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac5d55)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac9ae1)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81acda9b)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff81ad5795)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81ad9d17)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81adbf8e)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b022a3)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b15cf2)
Location: include/linux/atomic-arch-fallback.h:1127
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
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1ff71)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:skb_dst_pop
```
```
In net/ipv6/ip6_output.c (ffffffff81b30a94)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81b316a5)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b40e10)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67085)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b70c41)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81b747ed)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81b7a940)
Location: include/linux/atomic-arch-fallback.h:1127
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff81b80119)
Location: include/linux/atomic-arch-fallback.h:1127
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
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/alternative.c (ffffffff81c36915)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068071)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In kernel/cred.c (ffffffff810d2237)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
```
```
In kernel/module.c (ffffffff8115ddf2)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
```
```
In kernel/events/core.c (ffffffff81243631)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In kernel/events/uprobes.c (ffffffff8124fe47)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/rmap.c (ffffffff812b1ab8)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff812c9ff9)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/huge_memory.c (ffffffff812f39fc)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - mm/huge_memory.c:get_huge_zero_page
```
```
In fs/super.c (ffffffff81322c8e)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/userfaultfd.c (ffffffff813813d0)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff8138cf23)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
```
```
In fs/io-wq.c (ffffffff8139bd60)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - fs/io-wq.c:io_impersonate_work
```
```
In fs/proc/task_mmu.c (ffffffff813c86b3)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff813cb946)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff813cf8aa)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/kernfs/dir.c (ffffffff813e0dde)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8176fba5)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/iommu/intel/svm.c (ffffffff817b5b22)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/base/power/runtime.c (ffffffff817dc018)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
```
```
In drivers/net/loopback.c (ffffffff8188d0c7)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/vfio/vfio.c (ffffffff818aa405)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_add_container_user
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b2561)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
```
```
In net/core/sock.c (ffffffff819e33c5)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819eb436)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff81a09bc3)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81a16e80)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff81a2a51e)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff81a55f04)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
```
```
In net/sched/sch_frag.c (ffffffff81a6f3f1)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/netfilter/nf_queue.c (ffffffff81a998f8)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81a9de80)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_options.c (ffffffff81aa46a8)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81aa6049)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aaa776)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad1be5)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad5a31)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ad9adb)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff81ae1d33)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81ae6777)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81ae8aea)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b10644)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b24162)
Location: include/linux/atomic-arch-fallback.h:1197
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
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2e881)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:skb_dst_pop
```
```
In net/ipv6/ip6_output.c (ffffffff81b3f6c4)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81b40295)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b4f8c6)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b75660)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b7f651)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81b8355d)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81b89890)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff81b8f29c)
Location: include/linux/atomic-arch-fallback.h:1197
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
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/alternative.c (ffffffff81c28db8)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810685e1)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In kernel/cred.c (ffffffff810d3e17)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
```
```
In kernel/module.c (ffffffff811600b2)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
```
```
In kernel/events/core.c (ffffffff812485f5)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In kernel/events/uprobes.c (ffffffff81254727)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/rmap.c (ffffffff812b7188)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff812d0a70)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/huge_memory.c (ffffffff812fbdf8)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
```
```
In fs/super.c (ffffffff81328d4e)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/userfaultfd.c (ffffffff81387d78)
Location: include/linux/atomic-arch-fallback.h:1197
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
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - fs/io_uring.c:io_link_timeout_fn
```
```
In fs/proc/task_mmu.c (ffffffff813cf6f3)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff813d2936)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff813d6977)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/kernfs/dir.c (ffffffff813e790e)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81753555)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/iommu/intel/svm.c (ffffffff81798e40)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/base/power/runtime.c (ffffffff817c03d8)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
```
```
In drivers/net/loopback.c (ffffffff8186fa07)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/vfio/vfio.c (ffffffff8188d755)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_add_container_user
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff81895881)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
```
```
In net/core/sock.c (ffffffff819c9419)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819d1946)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff819f0554)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff819fdb28)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff81a116be)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff81a38f14)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
```
```
In net/sched/sch_frag.c (ffffffff81a57cc4)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/netfilter/nf_queue.c (ffffffff81a84c08)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81a88da4)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_options.c (ffffffff81a8f79d)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81a91209)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a95d25)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abcbf5)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac0a90)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ac4b29)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff81acba06)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81ad1a47)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81ad3da5)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81afe254)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b11d92)
Location: include/linux/atomic-arch-fallback.h:1197
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
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c5df)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d562)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81b2e8a5)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b3d5f6)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b64090)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b6e171)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81b721d0)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81b786e0)
Location: include/linux/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff81b7ec5c)
Location: include/linux/atomic-arch-fallback.h:1197
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
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/alternative.c (ffffffff81d46f48)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81072d77)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In kernel/cred.c (ffffffff810e6ee7)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - kernel/cred.c:get_task_cred
```
```
In kernel/sched/core.c (ffffffff810f24e5)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_core_get
```
```
In kernel/module.c (ffffffff81185262)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
```
```
In kernel/events/core.c (ffffffff81282c4b)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In kernel/events/uprobes.c (ffffffff81290157)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/oom_kill.c (ffffffff812a31ce)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
```
```
In mm/rmap.c (ffffffff812f95a8)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff8131614b)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/huge_memory.c (ffffffff81345c28)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
```
```
In fs/super.c (ffffffff8137637e)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/userfaultfd.c (ffffffff813d5085)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
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
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - fs/io_uring.c:io_link_timeout_fn
```
```
In fs/proc/task_mmu.c (ffffffff81420ad3)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff81423e86)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff814280a7)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/kernfs/dir.c (ffffffff8143961e)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
```
```
In fs/fuse/file.c (ffffffff814edea0)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff817d6985)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/iommu/iommu-sva-lib.c (ffffffff8182fb85)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva-lib.c:__mmget_not_zero
```
```
In drivers/base/power/runtime.c (ffffffff8184a745)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
```
```
In drivers/net/loopback.c (ffffffff818fffa7)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/vfio/vfio.c (ffffffff81920cb5)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_add_container_user
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff819297f1)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
```
```
In net/core/sock.c (ffffffff81a787b9)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81a81516)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff81aa1982)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81aaf0f5)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff81ac2b9e)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff81aeede4)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
```
```
In net/sched/sch_frag.c (ffffffff81b10c8c)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/netfilter/nf_queue.c (ffffffff81b3f132)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81b43514)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_options.c (ffffffff81b4a9dd)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81b4c59d)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b51185)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b79985)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7e454)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81b832d9)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff81b8a296)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81b90677)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81b92a65)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81bbf4e4)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd5910)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
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
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81be0f1d)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81bf3712)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81bf4c74)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
```
```
In net/ipv6/route.c (ffffffff81c05686)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2bb50)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81c3619a)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81c3c680)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81c43220)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff81c4a3c1)
Location: include/linux/atomic/atomic-arch-fallback.h:1197
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
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/alternative.c (ffffffff81f15508)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107e7cd)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81080fa5)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In kernel/cred.c (ffffffff81101191)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - kernel/cred.c:get_task_cred
```
```
In kernel/sched/core.c (ffffffff8110e325)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_core_get
```
```
In kernel/module/main.c (ffffffff8118be44)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - kernel/module/main.c:try_module_get
```
```
In kernel/events/core.c (ffffffff812ce84e)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In kernel/events/uprobes.c (ffffffff812e5217)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/rmap.c (ffffffff8135fe85)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff813812e0)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/huge_memory.c (ffffffff813bbd9d)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
```
```
In fs/super.c (ffffffff813f5544)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/userfaultfd.c (ffffffff8145d68b)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
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
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff8149c9dd)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff8149df5a)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/kernfs/dir.c (ffffffff814b469e)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
```
```
In fs/fuse/file.c (ffffffff8157d29e)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
```
```
In block/blk-mq-tag.c (ffffffff8168bffd)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_find_and_get_req
```
```
In io_uring/io_uring.c (ffffffff816ce685)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_link_timeout_fn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81914a65)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/iommu/iommu-sva-lib.c (ffffffff81970d85)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva-lib.c:__mmget_not_zero
```
```
In drivers/base/power/runtime.c (ffffffff8198fa49)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
```
```
In drivers/net/loopback.c (ffffffff81a51a6a)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81a7f891)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
```
```
In net/core/sock.c (ffffffff81bec17a)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81bf525a)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff81c19ab5)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81c27e70)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff81c3d85d)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff81c71d3e)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
```
```
In net/sched/sch_frag.c (ffffffff81c97e0e)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/netfilter/nf_queue.c (ffffffff81ccb879)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81ccffd3)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_options.c (ffffffff81cd7841)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81cd9bf1)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81cddf2d)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d09717)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0e442)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81d138e2)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff81d1db79)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81d21afb)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81d2407d)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81d5427e)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6c16a)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
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
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81d77c6c)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81d89e79)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81d8da9a)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
```
```
In net/ipv6/route.c (ffffffff81d9fc84)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dc90cf)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81dd3d9a)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81ddaa5d)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81de1f9e)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff81de9ab5)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
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
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/alternative.c (ffffffff820bc9d1)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810902ba)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81093a4a)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
```
```
In kernel/cred.c (ffffffff811262a1)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - kernel/cred.c:get_task_cred
```
```
In kernel/sched/core.c (ffffffff811350b5)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_core_get
```
```
In kernel/module/main.c (ffffffff811c8574)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - kernel/module/main.c:try_module_get
```
```
In kernel/events/core.c (ffffffff8133699a)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:get_pmu_ctx
```
```
In kernel/events/uprobes.c (ffffffff8134ebc4)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/vmscan.c (ffffffff813771ff)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - mm/vmscan.c:should_skip_mm
```
```
In mm/rmap.c (ffffffff813dad6e)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_get_anon_vma
```
```
In mm/swapfile.c (ffffffff813ffb23)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/huge_memory.c (ffffffff8143e2ed)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In fs/super.c (ffffffff8147e7b4)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/userfaultfd.c (ffffffff814ed1ab)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
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
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
```
```
In fs/proc/task_mmu.c (ffffffff8152cbc6)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff815313dd)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff81532c1a)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/kernfs/dir.c (ffffffff8154b59f)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
```
```
In fs/fuse/file.c (ffffffff81622efe)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
```
```
In block/blk-mq-tag.c (ffffffff8174a76d)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_find_and_get_req
```
```
In io_uring/timeout.c (ffffffff81798f21)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - io_uring/timeout.c:io_link_timeout_fn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81a6fc45)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/iommu/iommu-sva.c (ffffffff81adbe81)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
  - drivers/iommu/iommu-sva.c:__mmget_not_zero
```
```
In drivers/base/power/runtime.c (ffffffff81affbc9)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
```
```
In drivers/net/loopback.c (ffffffff81bdacaa)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff81d98b5a)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81da377a)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff81dcaa6a)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81ddaa50)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff81df3d3d)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff81e29e3e)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
```
```
In net/sched/sch_frag.c (ffffffff81e53dae)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/netfilter/nf_queue.c (ffffffff81e8b6c9)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81e901b7)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_options.c (ffffffff81e97ebf)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81e9a381)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81ea1823)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ece9e7)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed3ef2)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ed98a2)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff81ee4c38)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81ee8f3b)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81eeb70d)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f1e45e)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f374ca)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
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
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81f444ae)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81f57e23)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81f5bbca)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
```
```
In net/ipv6/route.c (ffffffff81f6ed24)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f99f0f)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81fa53aa)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81fac76c)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81fb44ce)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff81fbd1f5)
Location: include/linux/atomic/atomic-arch-fallback.h:1281
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
