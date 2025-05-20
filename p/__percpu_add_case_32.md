# Function: <code>__percpu_add_case_32</code>

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
In <code>6.2</code>: Absent ⚠️
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
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __percpu_add_case_32(void *ptr, long unsigned int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffff80001016a508)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
```
```
In kernel/printk/printk_safe.c (ffff800010176fa8)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_exit
  - kernel/printk/printk_safe.c:__printk_safe_enter
```
```
In kernel/trace/trace.c (ffff800010221430)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - kernel/trace/trace.c:put_trace_buf
  - kernel/trace/trace.c:trace_buffer_unlock_commit_nostack
  - kernel/trace/trace.c:disable_trace_buffered_event
  - kernel/trace/trace.c:enable_trace_buffered_event
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
```
```
In kernel/trace/trace_syscalls.c (ffff80001023e108)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/bpf_trace.c (ffff80001024dc10)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:put_bpf_raw_tp_regs
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
```
```
In kernel/trace/trace_kprobe.c (ffff8000102517ac)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (ffff80001025a78c)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
```
```
In kernel/bpf/syscall.c (ffff800010263ce4)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/devmap.c (ffff800010286f3c)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/bpf/offload.c (ffff80001028a928)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
```
In kernel/events/core.c (ffff80001029ac0c)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - kernel/events/core.c:perf_sched_cb_inc
  - kernel/events/core.c:perf_sched_cb_dec
```
```
In mm/page-writeback.c (ffff8000102be180)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/namespace.c (ffff8000103b86bc)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - fs/namespace.c:__arm64_sys_fsmount
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:__arm64_sys_open_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:mnt_set_mountpoint
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_clone_write
  - fs/namespace.c:__mnt_want_write
  - fs/namespace.c:__mnt_want_write
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/buffer.c (ffff8000103d8044)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
```
```
In fs/eventfd.c (ffff8000103f6190)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_signal
  - fs/eventfd.c:eventfd_signal
```
```
In security/selinux/avc.c (ffff800010546cc4)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_node_kill
  - security/selinux/avc.c:avc_node_free
```
```
In security/selinux/netif.c (ffff800010558090)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/lsm_audit.c (ffff8000105773bc)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
```
```
In block/blk-iocost.c (ffff8000106158a8)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
```
```
In lib/percpu_counter.c (ffff80001065ebb8)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_add_batch
```
```
In drivers/net/tun.c (ffff8000109dcd34)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_read_iter
  - drivers/net/tun.c:tun_chr_read_iter
  - drivers/net/tun.c:tun_chr_write_iter
  - drivers/net/tun.c:tun_chr_write_iter
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffff800010bab054)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
```
```
In net/core/dev.c (ffff800010bd7738)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_getfirstbyhwtype
  - net/core/dev.c:dev_get_by_index
  - net/core/dev.c:dev_get_by_name
```
```
In net/core/ethtool.c (ffff800010bdcb9c)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/dst.c (ffff800010be097c)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
  - net/core/dst.c:dst_dev_put
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (ffff800010be4cd8)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/utils.c (ffff800010bf33ec)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/link_watch.c (ffff800010bf3a34)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/net-sysfs.c (ffff800010c0c048)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:netdev_queue_release
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:rx_queue_release
```
```
In net/core/netpoll.c (ffff800010c10aac)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (ffff800010c1b910)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_metadata_free
```
```
In net/core/netprio_cgroup.c (ffff800010c1d2c4)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:write_priomap
```
```
In net/core/lwt_bpf.c (ffff800010c1f1a4)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/core/devlink.c (ffff800010c306b8)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/sch_generic.c (ffff800010c3a334)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/sch_api.c (ffff800010c3c9a4)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:qdisc_create
```
```
In net/netlink/af_netlink.c (ffff800010c4b6e0)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netfilter/nf_queue.c (ffff800010c55b50)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/route.c (ffff800010c5d0a0)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/ip_sockglue.c (ffff800010c68d98)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
```
```
In net/ipv4/devinet.c (ffff800010ca8f54)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:in_dev_finish_destroy
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/fib_semantics.c (ffff800010cb7de8)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v6_gw
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/fib_trie.c (ffff800010cbc5ec)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
```
```
In net/ipv4/ipmr.c (ffff800010ccd6cc)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv4/xfrm4_policy.c (ffff800010cd7588)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
```
In net/xfrm/xfrm_policy.c (ffff800010cda860)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_state.c (ffff800010ce3638)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (ffff800010ceabb0)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffff800010cee130)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffff800010d083ec)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffff800010d171a4)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ipv6_sockglue.c (ffff800010d1f6b4)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
```
```
In net/ipv6/ip6mr.c (ffff800010d46654)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffff800010d48bd4)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/addrconf_core.c (ffff800010d52f40)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
```
```
In net/packet/af_packet.c (ffff800010d5aef4)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_destruct_skb
```
```
In net/netlabel/netlabel_unlabeled.c (ffff800010d68f9c)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/switchdev/switchdev.c (ffff800010d7410c)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/ncsi/ncsi-netlink.c (ffff800010d7c35c)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ndp_from_ifindex
```
```
In net/xdp/xsk.c (ffff800010d7eb5c)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_unbind_dev
```
```
In net/xdp/xdp_umem.c (ffff800010d81078)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_clear_dev
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
```
**Symbols:**

```
ffff80001021df50-ffff80001021df64: __percpu_add_case_32 (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
