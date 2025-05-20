# Function: <code>raw_atomic_add_return</code>

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
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006d2f)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81025b59)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8213eb6f)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8107bb20)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810d6e1e)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/panic.c (ffffffff810f5b32)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - kernel/panic.c:__warn_printk
  - kernel/panic.c:__warn_printk
```
```
In kernel/exit.c (ffffffff810fdf45)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - kernel/exit.c:make_task_dead
```
```
In kernel/sched/build_utility.c (ffffffff8118195b)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:build_overlap_sched_groups
```
```
In kernel/irq/spurious.c (ffffffff811abbfe)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff811b0f52)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_create
```
```
In kernel/rcu/tree.c (ffffffff811ccc65)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcu_momentary_dyntick_idle
```
```
In kernel/audit.c (ffffffff8123efc9)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_start
```
```
In kernel/watchdog.c (ffffffff8125e47a)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/trace/ftrace.c (ffffffff8126b310)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
```
```
In kernel/trace/trace.c (ffffffff81289a80)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff8128f89a)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/trace/trace_functions.c (ffffffff8129173d)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81292781)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8129c309)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff812a61a4)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812aed28)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
```
```
In kernel/events/callchain.c (ffffffff8137d548)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/context_tracking.c (ffffffff82141dbf)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - kernel/context_tracking.c:ct_kernel_exit_state
```
```
In kernel/watch_queue.c (ffffffff8138915e)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/vmscan.c (ffffffff813b5cd5)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_throttle
```
```
In mm/zswap.c (ffffffff8143533c)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/kfence/core.c (ffffffff8146590e)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - mm/kfence/core.c:__kfence_alloc
```
```
In fs/inode.c (ffffffff814d64b3)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
  - fs/inode.c:ihold
```
```
In fs/notify/notification.c (ffffffff815136b5)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/coredump.c (ffffffff8155072f)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/netlink.c (ffffffff815633e0)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffff8156970d)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/kernfs/inode.c (ffffffff81580d05)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/devpts/inode.c (ffffffff8158e375)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/mballoc.c (ffffffff815c963d)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/jbd2/transaction.c (ffffffff816136bf)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/ecryptfs/main.c (ffffffff81643e05)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffffffff816a4a5a)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffffffff81706c66)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_learning_profile
```
```
In block/blk-crypto-profile.c (ffffffff817c3979)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
```
```
In io_uring/cancel.c (ffffffff817dfa12)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - io_uring/cancel.c:io_sync_cancel
  - io_uring/cancel.c:io_sync_cancel
  - io_uring/cancel.c:io_async_cancel
```
```
In lib/percpu-refcount.c (ffffffff81818078)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81907de8)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
  - drivers/gpio/gpiolib-cdev.c:process_hw_ts
```
```
In drivers/pci/pci.c (ffffffff81926917)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a30345)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff81a8b6bf)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff81a91517)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_deassert
  - drivers/reset/core.c:reset_control_reset
```
```
In drivers/char/random.c (ffffffff81ae0202)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81b567f0)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_activate
```
```
In drivers/base/devcoredump.c (ffffffff81b79023)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd16cf)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff81bea486)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff81bf4157)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff81c036cd)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-sata.c (ffffffff81c16c31)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff81d067fd)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff81d0e31b)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/md/dm.c (ffffffff81d7a355)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In drivers/edac/edac_device.c (ffffffff81d8af25)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff81d8d725)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81d8e3d5)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de6434)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (ffffffff81dec29d)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_suspend_device
```
```
In drivers/devfreq/devfreq-event.c (ffffffff81df01e9)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
```
```
In net/core/skbuff.c (ffffffff81e1928f)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_realloc
```
```
In net/core/dev.c (ffffffff81e2e881)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
```
```
In net/core/neighbour.c (ffffffff81e4ca1f)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/netpoll.c (ffffffff81e867ec)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff81ea49c5)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_alloc_elem
```
```
In net/ipv4/route.c (ffffffff81eeb231)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/ip_fragment.c (ffffffff81ef57e1)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff81efc0e9)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81f3c629)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff81f4131c)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9798e)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81fb6a6a)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
```
```
In net/ipv6/route.c (ffffffff81fcc9cc)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_gc
```
```
In net/ipv6/raw.c (ffffffff81fee51d)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff82029cf9)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff8205618a)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
```
```
In lib/bug.c (ffffffff8209ec99)
Location: include/linux/atomic/atomic-arch-fallback.h:552
Inline: True
Inline callers:
  - lib/bug.c:report_bug
  - lib/bug.c:report_bug
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
In arch/x86/events/core.c (ffffffff8100c42f)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff8102bcb9)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff82220b8f)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810df67d)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/panic.c (ffffffff810feee2)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - kernel/panic.c:__warn_printk
  - kernel/panic.c:__warn_printk
```
```
In kernel/exit.c (ffffffff81106bf5)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - kernel/exit.c:make_task_dead
```
```
In kernel/sched/build_utility.c (ffffffff8119023a)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:build_overlap_sched_groups
```
```
In kernel/irq/spurious.c (ffffffff811bb7fe)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff811c0cd2)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_create
```
```
In kernel/rcu/tree.c (ffffffff811e1677)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_report_cpu_starting
  - kernel/rcu/tree.c:rcu_momentary_dyntick_idle
```
```
In kernel/audit.c (ffffffff81258e31)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_start
```
```
In kernel/watchdog.c (ffffffff812783ba)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/trace/ftrace.c (ffffffff812857c0)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
```
```
In kernel/trace/trace.c (ffffffff812a4e00)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff812aadfa)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/trace/trace_functions.c (ffffffff812acd4d)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812ade67)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
```
```
In kernel/trace/trace_functions_graph.c (ffffffff812b79e9)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff812c1cc4)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812cb248)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
```
```
In kernel/events/core.c (ffffffff81394c47)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
```
```
In kernel/events/callchain.c (ffffffff813a67a8)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/context_tracking.c (ffffffff8222413f)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - kernel/context_tracking.c:ct_kernel_exit_state
```
```
In kernel/watch_queue.c (ffffffff813b2bae)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/vmscan.c (ffffffff813deb95)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_throttle
```
```
In mm/zswap.c (ffffffff8146e42e)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/kfence/core.c (ffffffff81494bee)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - mm/kfence/core.c:__kfence_alloc
```
```
In fs/inode.c (ffffffff81508883)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
  - fs/inode.c:ihold
```
```
In fs/notify/notification.c (ffffffff81547b45)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/coredump.c (ffffffff815865bf)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/netlink.c (ffffffff81599ad0)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffff815a1d2d)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/kernfs/inode.c (ffffffff815b977a)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/devpts/inode.c (ffffffff815c70a5)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/mballoc.c (ffffffff81602411)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/jbd2/transaction.c (ffffffff8164c4bf)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/ecryptfs/main.c (ffffffff8167d395)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffffffff816e14ba)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffffffff81744706)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_learning_profile
```
```
In block/bdev.c (ffffffff817a8480)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - block/bdev.c:bdev_freeze
```
```
In block/blk-crypto-profile.c (ffffffff81808609)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
```
```
In io_uring/cancel.c (ffffffff81823ea2)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - io_uring/cancel.c:io_sync_cancel
  - io_uring/cancel.c:io_sync_cancel
  - io_uring/cancel.c:io_async_cancel
```
```
In lib/percpu-refcount.c (ffffffff8185d378)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8194f5fa)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
  - drivers/gpio/gpiolib-cdev.c:process_hw_ts
```
```
In drivers/pci/pci.c (ffffffff8196f0b7)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7b855)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff81adde45)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/regulator/event.c (ffffffff81ae254e)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - drivers/regulator/event.c:reg_generate_netlink_event
```
```
In drivers/reset/core.c (ffffffff81ae3e87)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_deassert
  - drivers/reset/core.c:reset_control_reset
```
```
In drivers/char/random.c (ffffffff81b33602)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81baede0)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_activate
```
```
In drivers/base/devcoredump.c (ffffffff81bccf0f)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c2633f)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff81c3faa6)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff81c49a97)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff81c58e8d)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-sata.c (ffffffff81c6b3fb)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_sas_port_alloc
```
```
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb5df7)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:drm_vblank_get
```
```
In drivers/input/serio/serio.c (ffffffff81dbc42d)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff81dc3f6a)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/md/dm.c (ffffffff81e314f5)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In drivers/edac/edac_device.c (ffffffff81e427a5)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff81e44fd5)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81e45cb5)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9c614)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (ffffffff81ea25ed)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_suspend_device
```
```
In drivers/devfreq/devfreq-event.c (ffffffff81ea67d8)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
```
```
In net/core/skbuff.c (ffffffff81ed671f)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_realloc
```
```
In net/core/dev.c (ffffffff81eece11)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
```
```
In net/core/neighbour.c (ffffffff81f0b72f)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/netpoll.c (ffffffff81f487f9)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff81f673e5)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_alloc_elem
```
```
In net/ipv4/route.c (ffffffff81faf251)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/ip_fragment.c (ffffffff81fb9791)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff81fc0049)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
```
```
In net/ipv4/raw.c (ffffffff82002758)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff82006f6c)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff82064cfe)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff82083ce8)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
```
```
In net/ipv6/route.c (ffffffff8209a1ac)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_gc
```
```
In net/ipv6/raw.c (ffffffff820bc0fd)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff820f97cd)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff82128a0a)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
```
```
In lib/bug.c (ffffffff82176c99)
Location: include/linux/atomic/atomic-arch-fallback.h:561
Inline: True
Inline callers:
  - lib/bug.c:report_bug
  - lib/bug.c:report_bug
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
