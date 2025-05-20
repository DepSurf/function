# Function: <code>preempt_count</code>

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
In init/main.c (ffffffff810020a5)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/x86/events/intel/cqm.c (ffffffff8100d7f4)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_event_count
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81031be1)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
```
In arch/x86/kernel/nmi.c (ffffffff810326b3)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81039956)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:irq_fpu_usable
```
```
In arch/x86/kernel/kvm.c (ffffffff81063a4d)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In arch/x86/kernel/paravirt.c (ffffffff81064d99)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In arch/x86/mm/fault.c (ffffffff8106a5c6)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:__do_page_fault
```
```
In kernel/exit.c (ffffffff8108391f)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff81084cd6)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/softirq.c:_local_bh_enable
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:cpu_callback
  - kernel/softirq.c:cpu_callback
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:raise_softirq
```
```
In kernel/workqueue.c (ffffffff81098a59)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/workqueue.c:process_one_work
```
```
In kernel/sched/core.c (ffffffff810a5b3e)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule_bug
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:preempt_schedule_irq
```
```
In kernel/sched/cputime.c (ffffffff810b1770)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_process_tick
```
```
In kernel/locking/rtmutex.c (ffffffff81822986)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff810cbdc6)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/process.c (ffffffff810cde53)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:freeze_kernel_threads
```
```
In kernel/irq/manage.c (ffffffff810db2c4)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_irq
```
```
In kernel/rcu/tree.c (ffffffff810e7ebb)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
```
```
In kernel/time/timer.c (ffffffff810ec32b)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:del_timer_sync
  - kernel/time/timer.c:update_process_times
```
```
In kernel/kexec_core.c (ffffffff8110c9f4)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cpuset.c (ffffffff8111d715)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/cpuset.c:__cpuset_node_allowed
```
```
In kernel/stop_machine.c (ffffffff811202b8)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/kprobes.c (ffffffff8112d085)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/debug/debug_core.c (ffffffff8112fd22)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8113391b)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
```
```
In kernel/debug/kdb/kdb_debugger.c (ffffffff81139d2d)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
```
In kernel/trace/trace_clock.c (ffffffff8113fe09)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ftrace.c (ffffffff8114010a)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_recurs_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/ring_buffer.c (ffffffff81147d02)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_write
```
```
In kernel/trace/trace.c (ffffffff8114a7c1)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace.c:get_trace_buf
  - kernel/trace/trace.c:tracing_snapshot
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_dump_stack
```
```
In kernel/trace/trace_functions.c (ffffffff811567a8)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811570d1)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_stack.c (ffffffff81158228)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff81158cc3)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
```
```
In kernel/trace/trace_functions_graph.c (ffffffff81159191)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_return
```
```
In kernel/trace/blktrace.c (ffffffff8115be67)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
```
```
In kernel/trace/trace_events.c (ffffffff8115da7b)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_syscalls.c (ffffffff81161e48)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_event_perf.c (ffffffff811623cd)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_prepare
```
```
In kernel/trace/bpf_trace.c (ffffffff81166fe0)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
```
```
In kernel/trace/trace_kprobe.c (ffffffff81168476)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/irq_work.c (ffffffff81170d58)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/events/core.c (ffffffff8117b063)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pending_event
  - kernel/events/core.c:__perf_sw_event
```
```
In kernel/events/callchain.c (ffffffff8118627e)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/events/callchain.c:perf_callchain
```
```
In mm/page_alloc.c (ffffffff81192f77)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc_failed
  - mm/page_alloc.c:gfp_pfmemalloc_allowed
  - mm/page_alloc.c:gfp_pfmemalloc_allowed
  - mm/page_alloc.c:gfp_pfmemalloc_allowed
  - mm/page_alloc.c:alloc_kmem_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:alloc_kmem_pages_node
```
```
In mm/memory.c (ffffffff811c1f4e)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
```
```
In mm/vmalloc.c (ffffffff811cd7fa)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/mempolicy.c (ffffffff811e07e3)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/slub.c (ffffffff811eade8)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
```
```
In mm/zsmalloc.c (ffffffff8120544a)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
```
```
In fs/file_table.c (ffffffff8120e35e)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
```
```
In fs/pstore/platform.c (ffffffff8132030b)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
  - fs/pstore/platform.c:pstore_dump
  - fs/pstore/platform.c:pstore_dump
```
```
In security/apparmor/net.c (ffffffff813909e6)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sock_perm
  - security/apparmor/net.c:aa_sock_create_perm
  - security/apparmor/net.c:aa_sock_bind_perm
  - security/apparmor/net.c:aa_sock_connect_perm
  - security/apparmor/net.c:aa_sock_listen_perm
  - security/apparmor/net.c:aa_sock_accept_perm
  - security/apparmor/net.c:aa_sock_msg_perm
  - security/apparmor/net.c:aa_sock_opt_perm
```
```
In crypto/ablkcipher.c (ffffffff8139fd95)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
```
```
In crypto/blkcipher.c (ffffffff813a17a4)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_first
```
```
In lib/idr.c (ffffffff813e9e01)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - lib/idr.c:idr_preload
```
```
In lib/radix-tree.c (ffffffff813eeb2f)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
```
```
In lib/vsprintf.c (ffffffff813f5038)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
```
```
In lib/dynamic_debug.c (ffffffff81413db6)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_emit_prefix
```
```
In drivers/pci/search.c (ffffffff8143a9c6)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_find_next_bus
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/search.c:pci_dev_present
```
```
In drivers/rapidio/rio.c (ffffffff81459052)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_get_asm
```
```
In drivers/acpi/utils.c (ffffffff8147ad49)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_handle_path
```
```
In drivers/acpi/ec.c (ffffffff814834c9)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/apei/erst.c (ffffffff814b3de3)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_stall
```
```
In drivers/acpi/apei/ghes.c (ffffffff814b5451)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff814ee985)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:reset_vc
```
```
In drivers/tty/vt/vt.c (ffffffff814f7b65)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_put_char
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:con_write
```
```
In drivers/tty/serial/serial_core.c (ffffffff81500ce5)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
```
In drivers/scsi/sr.c (ffffffff815bfec4)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/net/phy/mdio_bus.c (ffffffff815ecf75)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff8164fb08)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81656484)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/i2c/i2c-core.c (ffffffff81679d0f)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_transfer
```
```
In drivers/md/dm-table.c (ffffffff816a56c5)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
```
```
In net/core/sock.c (ffffffff817013c3)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff8170542b)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/scm.c (ffffffff8170ec58)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff81716f25)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_any
```
```
In net/core/filter.c (ffffffff817324eb)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/netlink/af_netlink.c (ffffffff8174e4de)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff81768026)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv6/route.c (ffffffff817d9206)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
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
In init/main.c (ffffffff81002166)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/x86/events/intel/cqm.c (ffffffff8100de51)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_event_count
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81030cf3)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
```
In arch/x86/kernel/nmi.c (ffffffff81031809)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81038945)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:irq_fpu_usable
```
```
In arch/x86/kernel/kvm.c (ffffffff81063686)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In arch/x86/kernel/paravirt.c (ffffffff81064b45)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In arch/x86/mm/fault.c (ffffffff8106b29f)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In kernel/exit.c (ffffffff81086a42)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff8108880c)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/softirq.c:cpu_callback
  - kernel/softirq.c:cpu_callback
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/workqueue.c (ffffffff8109d621)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/workqueue.c:process_one_work
```
```
In kernel/sched/core.c (ffffffff810ac1ba)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/sched/cputime.c (ffffffff810b45cc)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_process_tick
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
```
```
In kernel/locking/rtmutex.c (ffffffff8189ceb2)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff810d08dc)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/process.c (ffffffff810d2b16)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
```
In kernel/printk/nmi.c (ffffffff810df3c6)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/printk/nmi.c:printk_nmi_flush_on_panic
  - kernel/printk/nmi.c:printk_nmi_flush_line
```
```
In kernel/irq/manage.c (ffffffff810e0954)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_irq
```
```
In kernel/rcu/tree.c (ffffffff810ee0fb)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
```
```
In kernel/time/timer.c (ffffffff810f582f)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/time/timer.c:update_process_times
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:del_timer_sync
```
```
In kernel/kexec_core.c (ffffffff81114274)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cpuset.c (ffffffff811255b5)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/cpuset.c:__cpuset_node_allowed
```
```
In kernel/stop_machine.c (ffffffff81128235)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/kprobes.c (ffffffff81135245)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/debug/debug_core.c (ffffffff81138025)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8113bd52)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/debug/kdb/kdb_debugger.c (ffffffff8114222d)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
```
In kernel/trace/trace_clock.c (ffffffff81148479)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ftrace.c (ffffffff81149651)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/ring_buffer.c (ffffffff8114ffe8)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
```
In kernel/trace/trace.c (ffffffff811585e0)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_dump_stack
  - kernel/trace/trace.c:tracing_snapshot
```
```
In kernel/trace/trace_functions.c (ffffffff8116119d)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81161be2)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_stack.c (ffffffff81162ab8)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff81163642)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
```
```
In kernel/trace/trace_functions_graph.c (ffffffff81163a64)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff81166a22)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
```
```
In kernel/trace/trace_events.c (ffffffff8116839b)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_syscalls.c (ffffffff8116c739)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_event_perf.c (ffffffff8116cc1d)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/bpf_trace.c (ffffffff811743a0)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
```
In kernel/trace/trace_kprobe.c (ffffffff81175ac0)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/irq_work.c (ffffffff8117e44d)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/events/core.c (ffffffff81196449)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/ring_buffer.c (ffffffff811970a6)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
```
```
In kernel/events/callchain.c (ffffffff8119856e)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/page_alloc.c (ffffffff811aadba)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:warn_alloc_failed
```
```
In mm/memory.c (ffffffff811dda8e)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
```
```
In mm/vmalloc.c (ffffffff811ea8b5)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/mempolicy.c (ffffffff811feaa2)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/memcontrol.c (ffffffff812242dc)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
```
```
In mm/zsmalloc.c (ffffffff8122aa7e)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/file_table.c (ffffffff81234d7d)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
```
```
In fs/pstore/platform.c (ffffffff81355a1a)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
  - fs/pstore/platform.c:pstore_dump
```
```
In security/apparmor/net.c (ffffffff813cca04)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sock_opt_perm
  - security/apparmor/net.c:aa_sock_msg_perm
  - security/apparmor/net.c:aa_sock_accept_perm
  - security/apparmor/net.c:aa_sock_listen_perm
  - security/apparmor/net.c:aa_sock_connect_perm
  - security/apparmor/net.c:aa_sock_bind_perm
  - security/apparmor/net.c:aa_sock_create_perm
  - security/apparmor/net.c:aa_sock_perm
  - security/apparmor/net.c:aa_sk_perm
```
```
In crypto/ablkcipher.c (ffffffff813dcf75)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
```
```
In crypto/blkcipher.c (ffffffff813ddc54)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_first
```
```
In lib/idr.c (ffffffff814301e1)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - lib/idr.c:idr_preload
```
```
In lib/radix-tree.c (ffffffff81434315)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_node_alloc
```
```
In lib/vsprintf.c (ffffffff8143bcb5)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - lib/vsprintf.c:pointer
```
```
In lib/dynamic_debug.c (ffffffff8145ba06)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_emit_prefix
```
```
In drivers/pci/search.c (ffffffff81486cc6)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/search.c:pci_find_next_bus
```
```
In drivers/rapidio/rio.c (ffffffff814a6b0a)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_get_asm
```
```
In drivers/acpi/utils.c (ffffffff814c92f6)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_handle_path
```
```
In drivers/acpi/ec.c (ffffffff814d232b)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/apei/erst.c (ffffffff81503753)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_stall
```
```
In drivers/acpi/apei/ghes.c (ffffffff81504dd1)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff8153f5d5)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:reset_vc
```
```
In drivers/tty/vt/vt.c (ffffffff8154d93d)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_put_char
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:con_write
```
```
In drivers/tty/serial/serial_core.c (ffffffff8155177b)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
```
In drivers/scsi/sr.c (ffffffff81618664)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/net/phy/mdio_bus.c (ffffffff8164bbf5)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff816b0466)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816b6ecd)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/i2c/i2c-core.c (ffffffff816db49b)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_transfer
```
```
In drivers/md/dm-table.c (ffffffff81705845)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
```
```
In net/core/sock.c (ffffffff8176763f)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff8176c0a0)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/scm.c (ffffffff8177651f)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff81781666)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_any
```
```
In net/core/filter.c (ffffffff8179cccb)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/netlink/af_netlink.c (ffffffff817ba67e)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff817d48e8)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv6/route.c (ffffffff81847156)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
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
In init/main.c (ffffffff81002157)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/x86/events/intel/cqm.c (ffffffff8100df11)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_event_count
```
```
In arch/x86/kernel/dumpstack.c (ffffffff810308d3)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
```
In arch/x86/kernel/nmi.c (ffffffff81031459)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff810386a6)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
```
```
In arch/x86/kernel/hpet.c (ffffffff81065835)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81066b42)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In arch/x86/kernel/paravirt.c (ffffffff81068015)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In arch/x86/mm/fault.c (ffffffff8106eeb3)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In kernel/exit.c (ffffffff8108b9b2)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff8108d76a)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/workqueue.c (ffffffff810a2191)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/workqueue.c:process_one_work
```
```
In kernel/sched/core.c (ffffffff810b229a)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/sched/cputime.c (ffffffff810babb2)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_process_tick
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
```
```
In kernel/locking/rtmutex.c (ffffffff818d1d82)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff810d734c)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/process.c (ffffffff810d96a6)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
```
In kernel/printk/nmi.c (ffffffff810e59b6)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/printk/nmi.c:printk_nmi_flush_on_panic
  - kernel/printk/nmi.c:printk_nmi_flush_line
```
```
In kernel/irq/manage.c (ffffffff810e7374)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_irq
```
```
In kernel/rcu/tree.c (ffffffff810f51db)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
```
```
In kernel/time/timer.c (ffffffff810fc88f)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/time/timer.c:update_process_times
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:del_timer_sync
```
```
In kernel/kexec_core.c (ffffffff8111b994)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cpuset.c (ffffffff8112efa5)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/cpuset.c:__cpuset_node_allowed
```
```
In kernel/stop_machine.c (ffffffff81131e35)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/kprobes.c (ffffffff8113efc5)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/debug/debug_core.c (ffffffff81141db5)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81145b02)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/debug/kdb/kdb_debugger.c (ffffffff8114c00d)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
```
In kernel/trace/trace_clock.c (ffffffff81152329)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ftrace.c (ffffffff81153501)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/ring_buffer.c (ffffffff8115b11d)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
```
In kernel/trace/trace.c (ffffffff8115e742)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_dump_stack
  - kernel/trace/trace.c:tracing_snapshot
```
```
In kernel/trace/trace_functions.c (ffffffff8116bbfd)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8116c742)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_hwlat.c (ffffffff8116d6ef)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/trace/trace_stack.c (ffffffff8116dde8)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff8116e972)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8116ed94)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff811722cc)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
```
```
In kernel/trace/trace_events.c (ffffffff811737db)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_syscalls.c (ffffffff811779fe)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_event_perf.c (ffffffff81177eed)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/bpf_trace.c (ffffffff8117f648)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
```
In kernel/trace/trace_kprobe.c (ffffffff811814b0)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/irq_work.c (ffffffff8118a05d)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/events/core.c (ffffffff811a5ec9)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/ring_buffer.c (ffffffff811a6aa6)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
```
```
In kernel/events/callchain.c (ffffffff811a7f4e)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/page_alloc.c (ffffffff811bb491)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:warn_alloc
  - mm/page_alloc.c:warn_alloc
```
```
In mm/memory.c (ffffffff811ed8de)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
```
```
In mm/vmalloc.c (ffffffff811fd425)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/mempolicy.c (ffffffff812102e2)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/memcontrol.c (ffffffff812368ac)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
```
```
In mm/zsmalloc.c (ffffffff8123cfce)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/file_table.c (ffffffff8124792d)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
```
```
In fs/pstore/platform.c (ffffffff8136be4a)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
  - fs/pstore/platform.c:pstore_dump
```
```
In security/apparmor/net.c (ffffffff813e4084)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sock_opt_perm
  - security/apparmor/net.c:aa_sock_msg_perm
  - security/apparmor/net.c:aa_sock_accept_perm
  - security/apparmor/net.c:aa_sock_listen_perm
  - security/apparmor/net.c:aa_sock_connect_perm
  - security/apparmor/net.c:aa_sock_bind_perm
  - security/apparmor/net.c:aa_sock_create_perm
  - security/apparmor/net.c:aa_sock_perm
  - security/apparmor/net.c:aa_sk_perm
```
```
In crypto/ablkcipher.c (ffffffff813f4845)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
```
```
In crypto/blkcipher.c (ffffffff813f5504)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_first
```
```
In crypto/skcipher.c (ffffffff813f68db)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_first
```
```
In lib/idr.c (ffffffff8144c411)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - lib/idr.c:idr_preload
```
```
In lib/radix-tree.c (ffffffff81451798)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
```
```
In lib/vsprintf.c (ffffffff81458c95)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - lib/vsprintf.c:pointer
```
```
In lib/dynamic_debug.c (ffffffff8147a4e6)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_emit_prefix
```
```
In drivers/pci/search.c (ffffffff814a8476)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/search.c:pci_find_next_bus
```
```
In drivers/rapidio/rio.c (ffffffff814c8c1a)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_get_asm
```
```
In drivers/acpi/utils.c (ffffffff814eb23a)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_handle_path
```
```
In drivers/acpi/ec.c (ffffffff814f4807)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/apei/erst.c (ffffffff81527943)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_stall
```
```
In drivers/acpi/apei/ghes.c (ffffffff81528fc1)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff8156bc15)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:reset_vc
```
```
In drivers/tty/vt/vt.c (ffffffff8157a1bd)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_put_char
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:con_write
```
```
In drivers/tty/serial/serial_core.c (ffffffff8157e06b)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
```
In drivers/scsi/sr.c (ffffffff816492e4)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/net/phy/mdio_bus.c (ffffffff8167d3f5)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff816de606)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816e5198)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/i2c/i2c-core.c (ffffffff8170b7db)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_transfer
```
```
In drivers/md/dm-table.c (ffffffff817376f5)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
```
```
In net/core/sock.c (ffffffff81794647)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff81799280)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/scm.c (ffffffff817a379f)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff817aef76)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_any
```
```
In net/core/filter.c (ffffffff817ca35b)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/netlink/af_netlink.c (ffffffff817ea01e)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff81804628)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv6/route.c (ffffffff81878f96)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
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
In init/main.c (ffffffff81002166)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/x86/kernel/dumpstack.c (ffffffff8102eb99)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
```
In arch/x86/kernel/nmi.c (ffffffff8102f676)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103680f)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
```
```
In arch/x86/kernel/hpet.c (ffffffff81064c25)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81065e54)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In arch/x86/kernel/paravirt.c (ffffffff81067345)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In arch/x86/mm/fault.c (ffffffff8106e624)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In kernel/exit.c (ffffffff81088b33)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff8108a799)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/workqueue.c (ffffffff8109f68c)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/workqueue.c:process_one_work
```
```
In kernel/sched/core.c (ffffffff810aea7c)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/sched/cputime.c (ffffffff810b53e7)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_process_tick
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
```
```
In kernel/locking/rtmutex.c (ffffffff81908f86)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff810d638c)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/process.c (ffffffff810d8686)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
```
In kernel/printk/printk_safe.c (ffffffff810e4f06)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/irq/manage.c (ffffffff810e6974)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_irq
```
```
In kernel/rcu/tree.c (ffffffff810f5f5b)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
```
```
In kernel/time/timer.c (ffffffff810fecdf)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/time/timer.c:update_process_times
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:del_timer_sync
```
```
In kernel/kexec_core.c (ffffffff8111d714)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cpuset.c (ffffffff81130635)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
```
```
In kernel/stop_machine.c (ffffffff811333f1)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/kprobes.c (ffffffff81140545)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/debug/debug_core.c (ffffffff811435f8)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81147892)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/debug/kdb/kdb_debugger.c (ffffffff8114df88)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
```
In kernel/trace/trace_clock.c (ffffffff81154909)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ftrace.c (ffffffff81154f21)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/ring_buffer.c (ffffffff8115e6c0)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
```
In kernel/trace/trace.c (ffffffff81161972)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_dump_stack
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:tracing_snapshot_instance
```
```
In kernel/trace/trace_functions.c (ffffffff8116ed1e)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8116fae6)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_hwlat.c (ffffffff8117087e)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/trace/trace_stack.c (ffffffff811710e1)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff81171b92)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
```
```
In kernel/trace/trace_functions_graph.c (ffffffff81171fb4)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff811756c2)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
```
```
In kernel/trace/trace_events.c (ffffffff811764a9)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_syscalls.c (ffffffff8117a65f)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_event_perf.c (ffffffff8117abfd)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/bpf_trace.c (ffffffff81182348)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
```
In kernel/trace/trace_kprobe.c (ffffffff81184244)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/irq_work.c (ffffffff8118cbb0)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/events/core.c (ffffffff811ad649)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/ring_buffer.c (ffffffff811ae276)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
```
```
In kernel/events/callchain.c (ffffffff811af69e)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/page_alloc.c (ffffffff811c3899)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:warn_alloc
  - mm/page_alloc.c:warn_alloc
```
```
In mm/memory.c (ffffffff811f888e)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
```
```
In mm/vmalloc.c (ffffffff812080f5)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/mempolicy.c (ffffffff8121ae66)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/memcontrol.c (ffffffff8124234c)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
```
```
In mm/zsmalloc.c (ffffffff812495fb)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/file_table.c (ffffffff8125315d)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
```
```
In fs/pstore/platform.c (ffffffff81380729)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
  - fs/pstore/platform.c:pstore_dump
```
```
In crypto/ablkcipher.c (ffffffff81400b92)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
```
```
In crypto/blkcipher.c (ffffffff814017c5)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_first
```
```
In crypto/skcipher.c (ffffffff81402cd5)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_first
```
```
In block/blk-core.c (ffffffff814223f6)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - block/blk-core.c:blk_start_queue
```
```
In lib/dynamic_debug.c (ffffffff814836b5)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_emit_prefix
```
```
In drivers/pci/search.c (ffffffff814b23e6)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/search.c:pci_find_next_bus
```
```
In drivers/rapidio/rio.c (ffffffff814d49f2)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_get_asm
```
```
In drivers/acpi/utils.c (ffffffff814f728c)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_handle_path
```
```
In drivers/acpi/ec.c (ffffffff815027a9)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/apei/erst.c (ffffffff8153a893)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_stall
```
```
In drivers/acpi/apei/ghes.c (ffffffff8153c569)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff815802d7)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:reset_vc
```
```
In drivers/tty/vt/vt.c (ffffffff8158dfcd)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_put_char
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:con_write
```
```
In drivers/tty/serial/serial_core.c (ffffffff8159228b)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
```
In drivers/scsi/sr.c (ffffffff8165dc11)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/net/phy/mdio_bus.c (ffffffff816924f5)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff816f3f8c)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816f90d7)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8172083b)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/md/dm-table.c (ffffffff81750c15)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
```
```
In net/core/sock.c (ffffffff817b489a)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff817bb433)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/scm.c (ffffffff817c182d)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff817cd8b6)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_any
```
```
In net/core/filter.c (ffffffff817e92fb)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/netlink/af_netlink.c (ffffffff81809cee)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff81824c28)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv6/route.c (ffffffff8189e1d5)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
```
```
In lib/radix-tree.c (ffffffff818f15fc)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
```
```
In lib/vsprintf.c (ffffffff818fa508)
Location: arch/x86/include/asm/preempt.h:20
Inline: True
Inline callers:
  - lib/vsprintf.c:pointer
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
In init/main.c (ffffffff81002186)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81030a69)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
```
In arch/x86/kernel/nmi.c (ffffffff81031676)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81038bd6)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
```
```
In arch/x86/kernel/hpet.c (ffffffff81068db6)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8106a1ea)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106b589)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In arch/x86/mm/fault.c (ffffffff810736bf)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In kernel/exit.c (ffffffff8108f863)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff81091349)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/workqueue.c (ffffffff810a830f)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (ffffffff810af9a6)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
```
```
In kernel/sched/core.c (ffffffff810b5ccd)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/sched/cputime.c (ffffffff810bc597)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_process_tick
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
```
```
In kernel/locking/rtmutex.c (ffffffff81993096)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff810de33c)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/process.c (ffffffff810e0776)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
```
In kernel/printk/printk_safe.c (ffffffff810ed166)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/irq/manage.c (ffffffff810eeba4)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_irq
```
```
In kernel/rcu/tree.c (ffffffff810ffdfb)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
```
```
In kernel/time/timer.c (ffffffff811099cf)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/time/timer.c:update_process_times
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:del_timer_sync
```
```
In kernel/kexec_core.c (ffffffff81128f06)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cpuset.c (ffffffff8113d575)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
```
```
In kernel/stop_machine.c (ffffffff811400a3)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/kprobes.c (ffffffff8114d3e6)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/debug/debug_core.c (ffffffff811502bb)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81154142)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/debug/kdb/kdb_debugger.c (ffffffff8115a828)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
```
In kernel/trace/trace_clock.c (ffffffff81161129)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ftrace.c (ffffffff811617de)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/ring_buffer.c (ffffffff8116b60a)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
```
In kernel/trace/trace.c (ffffffff8116e1f2)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_dump_stack
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:tracing_snapshot_instance
```
```
In kernel/trace/trace_functions.c (ffffffff8117be0e)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8117cbfc)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_hwlat.c (ffffffff8117da4e)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/trace/trace_stack.c (ffffffff8117e29c)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff8117ed22)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8117f144)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff81182beb)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
```
```
In kernel/trace/trace_events.c (ffffffff81183c79)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_syscalls.c (ffffffff81187ecc)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_event_perf.c (ffffffff8118845d)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/bpf_trace.c (ffffffff8118fd08)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
```
In kernel/trace/trace_kprobe.c (ffffffff81191fa4)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/irq_work.c (ffffffff8119a7d5)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/events/core.c (ffffffff811c11b9)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/ring_buffer.c (ffffffff811c1ee6)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
```
```
In kernel/events/callchain.c (ffffffff811c322e)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/page_alloc.c (ffffffff811d86a5)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:warn_alloc
  - mm/page_alloc.c:warn_alloc
```
```
In mm/vmalloc.c (ffffffff812211d6)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/mempolicy.c (ffffffff81236086)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/memcontrol.c (ffffffff8126214c)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
```
```
In mm/zsmalloc.c (ffffffff812694a5)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/file_table.c (ffffffff81275264)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
```
```
In fs/pstore/platform.c (ffffffff813a5739)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
  - fs/pstore/platform.c:pstore_dump
```
```
In crypto/ablkcipher.c (ffffffff81429192)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
```
```
In crypto/blkcipher.c (ffffffff81429dd6)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_first
```
```
In crypto/skcipher.c (ffffffff8142b346)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_first
```
```
In block/blk-core.c (ffffffff8144d4d6)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - block/blk-core.c:blk_start_queue
```
```
In block/blk-mq.c (ffffffff8145b0e7)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In lib/dynamic_debug.c (ffffffff814bf6f5)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_emit_prefix
```
```
In drivers/pci/search.c (ffffffff814f1ad6)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/search.c:pci_find_next_bus
```
```
In drivers/rapidio/rio.c (ffffffff81514ea2)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_get_asm
```
```
In drivers/acpi/utils.c (ffffffff815380fc)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_handle_path
```
```
In drivers/acpi/ec.c (ffffffff81544bea)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/apei/erst.c (ffffffff8159d3f3)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_stall
```
```
In drivers/acpi/apei/ghes.c (ffffffff8159f0b9)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
```
```
In drivers/tty/sysrq.c (ffffffff815e3c96)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff815e4e57)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:reset_vc
```
```
In drivers/tty/vt/vt.c (ffffffff815f2a8d)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_put_char
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:con_write
```
```
In drivers/tty/serial/serial_core.c (ffffffff815f6cbb)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
```
In drivers/scsi/sr.c (ffffffff816c71f9)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/net/phy/mdio_bus.c (ffffffff816fc316)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff8176023c)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81765be7)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81791b6b)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/md/dm-table.c (ffffffff817c2de6)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff817d29c5)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
```
In net/core/sock.c (ffffffff8182cafa)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff81833646)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/scm.c (ffffffff8183b22c)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff81847266)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_any
```
```
In net/core/filter.c (ffffffff818646fb)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/netlink/af_netlink.c (ffffffff81888c4e)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff818a6a60)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv6/route.c (ffffffff819207b5)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
```
```
In lib/radix-tree.c (ffffffff81977aac)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
```
```
In lib/vsprintf.c (ffffffff8197fece)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - lib/vsprintf.c:restricted_pointer
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
In init/main.c (ffffffff81002786)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81031c80)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
```
In arch/x86/kernel/nmi.c (ffffffff810328f6)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103a39a)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
```
```
In arch/x86/kernel/hpet.c (ffffffff8106b565)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8106cd55)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106e259)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In arch/x86/mm/fault.c (ffffffff8107600f)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In kernel/exit.c (ffffffff810933d3)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff81094dda)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
  - kernel/softirq.c:_local_bh_enable
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/workqueue.c (ffffffff810aae47)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (ffffffff810b6805)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
```
```
In kernel/sched/core.c (ffffffff810bd972)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/sched/cputime.c (ffffffff810c3c6a)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_process_tick
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
```
```
In kernel/locking/rtmutex.c (ffffffff819ef675)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff810e6905)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/process.c (ffffffff810e8dea)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
```
In kernel/irq/manage.c (ffffffff810f6f94)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_irq
```
```
In kernel/rcu/tree.c (ffffffff8110811a)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
```
```
In kernel/time/timer.c (ffffffff81114fef)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/time/timer.c:update_process_times
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:del_timer_sync
```
```
In kernel/kexec_core.c (ffffffff81136e60)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cpuset.c (ffffffff8114be85)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
```
```
In kernel/stop_machine.c (ffffffff8114ea9e)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/kprobes.c (ffffffff8115bdf5)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/debug/debug_core.c (ffffffff8115ee6c)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811639b6)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/debug/kdb/kdb_debugger.c (ffffffff81169458)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
```
In kernel/trace/trace_clock.c (ffffffff81170059)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ftrace.c (ffffffff8117071d)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/ring_buffer.c (ffffffff8117aaf2)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
```
In kernel/trace/trace.c (ffffffff8117d1ff)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_dump_stack
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:tracing_snapshot_instance
```
```
In kernel/trace/trace_functions.c (ffffffff8118af58)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8118bc53)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_hwlat.c (ffffffff8118cc3a)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/trace/trace_stack.c (ffffffff8118d358)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff8118de1b)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8118e244)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff81191d84)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
```
```
In kernel/trace/trace_events.c (ffffffff81192de1)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_syscalls.c (ffffffff811970ee)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_event_perf.c (ffffffff81197600)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/bpf_trace.c (ffffffff811a4cf0)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
```
In kernel/trace/trace_kprobe.c (ffffffff811a75fc)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/irq_work.c (ffffffff811b0215)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/bpf/stackmap.c (ffffffff811d0c45)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff811e1535)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
  - kernel/events/core.c:perf_pending_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/ring_buffer.c (ffffffff811e22a5)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
```
```
In kernel/events/callchain.c (ffffffff811e35ce)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/page_alloc.c (ffffffff811f9712)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:warn_alloc
  - mm/page_alloc.c:warn_alloc
```
```
In mm/vmalloc.c (ffffffff81243085)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/mempolicy.c (ffffffff81259065)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/memcontrol.c (ffffffff8128614c)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
```
```
In mm/zsmalloc.c (ffffffff8128d395)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/file_table.c (ffffffff8129bb04)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
```
```
In fs/pstore/platform.c (ffffffff813d4889)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
  - fs/pstore/platform.c:pstore_dump
```
```
In crypto/ablkcipher.c (ffffffff8145bf52)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
```
```
In crypto/blkcipher.c (ffffffff8145cb25)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_first
```
```
In crypto/skcipher.c (ffffffff8145e065)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_first
```
```
In block/blk-mq.c (ffffffff8148e085)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In lib/dynamic_debug.c (ffffffff814f0641)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_emit_prefix
```
```
In drivers/pci/search.c (ffffffff81521d65)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/search.c:pci_find_next_bus
```
```
In drivers/rapidio/rio.c (ffffffff8154c995)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_get_asm
```
```
In drivers/acpi/utils.c (ffffffff8156dd8c)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_handle_path
```
```
In drivers/acpi/ec.c (ffffffff8157ad4f)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/apei/erst.c (ffffffff815d5143)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_stall
```
```
In drivers/acpi/apei/ghes.c (ffffffff815d6da5)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
```
```
In drivers/tty/sysrq.c (ffffffff8161cf45)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff8161e13c)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:reset_vc
```
```
In drivers/tty/vt/vt.c (ffffffff8162bec5)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_put_char
  - drivers/tty/vt/vt.c:con_put_char
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:con_write
```
```
In drivers/tty/serial/serial_core.c (ffffffff8162fea3)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
```
In drivers/scsi/sr.c (ffffffff81703aee)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81739aa5)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff817a10d7)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817a618c)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817d4595)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/md/dm-table.c (ffffffff8180b745)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff8181b7a5)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
```
In net/core/sock.c (ffffffff81877619)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff8187dae5)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/scm.c (ffffffff81885a23)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff81890775)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_any
```
```
In net/core/filter.c (ffffffff818b1851)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/page_pool.c (ffffffff818bdc42)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/netlink/af_netlink.c (ffffffff818dc69e)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff818fbb5b)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv6/route.c (ffffffff81978b05)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
```
```
In lib/radix-tree.c (ffffffff819d416c)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
```
```
In lib/vsprintf.c (ffffffff819dc052)
Location: arch/x86/include/asm/preempt.h:21
Inline: True
Inline callers:
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
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
In init/main.c (ffffffff81002786)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/x86/xen/spinlock.c (ffffffff8102ae88)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/hyperv/hv_spinlock.c (ffffffff8102d165)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81032f80)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
```
In arch/x86/kernel/nmi.c (ffffffff81033bb6)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/kernel/process.c (ffffffff81a2ca66)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103ba23)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/hpet.c (ffffffff810715e5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81072f25)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff81074229)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In arch/x86/mm/fault.c (ffffffff8107c29c)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/tlb.c (ffffffff81083eb7)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In kernel/exit.c (ffffffff8109b693)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff8109d2ba)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
  - kernel/softirq.c:_local_bh_enable
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/workqueue.c (ffffffff810b3ec7)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (ffffffff810bfc55)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
```
```
In kernel/sched/core.c (ffffffff810c6a69)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/sched/cputime.c (ffffffff810ccf2a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_process_tick
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
```
```
In kernel/sched/idle.c (ffffffff81a2cce3)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/locking/rtmutex.c (ffffffff81a2a9b5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff810f1f05)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/process.c (ffffffff810f43e9)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
```
In kernel/printk/printk.c (ffffffff810fe3e9)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
```
```
In kernel/irq/manage.c (ffffffff81102704)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_irq
```
```
In kernel/rcu/tree.c (ffffffff81112cfe)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_gp_kthread_wake
  - kernel/rcu/tree.c:rcu_gp_kthread_wake
```
```
In kernel/time/timer.c (ffffffff8112062f)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/time/timer.c:update_process_times
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:del_timer_sync
```
```
In kernel/kexec_core.c (ffffffff811425e0)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cpuset.c (ffffffff81158ad5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
```
```
In kernel/stop_machine.c (ffffffff8115b67e)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/kprobes.c (ffffffff81168b85)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/debug/debug_core.c (ffffffff8116bb8e)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8116fbd2)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/debug/kdb/kdb_debugger.c (ffffffff811762b8)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
```
In kernel/trace/trace_clock.c (ffffffff8117dc09)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ftrace.c (ffffffff8117e1b5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/ring_buffer.c (ffffffff81186ff2)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
```
In kernel/trace/trace.c (ffffffff8118aa6f)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:tracing_snapshot_instance
```
```
In kernel/trace/trace_functions.c (ffffffff81198881)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81199673)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_hwlat.c (ffffffff8119a742)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/trace/trace_stack.c (ffffffff8119accc)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff8119b7a2)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8119bbd4)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff8119f597)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
```
```
In kernel/trace/trace_events.c (ffffffff811a0f42)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_syscalls.c (ffffffff811a5243)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_event_perf.c (ffffffff811a5770)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/bpf_trace.c (ffffffff811b2dc0)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
```
In kernel/trace/trace_kprobe.c (ffffffff811b633d)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/irq_work.c (ffffffff811be829)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/bpf/stackmap.c (ffffffff811e0725)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff811f198d)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
  - kernel/events/core.c:perf_pending_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/ring_buffer.c (ffffffff811f2715)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In kernel/events/callchain.c (ffffffff811f3a8e)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/page_alloc.c (ffffffff8120be81)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:warn_alloc
```
```
In mm/vmalloc.c (ffffffff81257795)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/mempolicy.c (ffffffff8126d465)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/memcontrol.c (ffffffff8129b09e)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
```
```
In mm/zsmalloc.c (ffffffff812a25d5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/file_table.c (ffffffff812b0e2d)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In fs/pstore/platform.c (ffffffff813eeebd)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
  - fs/pstore/platform.c:pstore_dump
```
```
In crypto/ablkcipher.c (ffffffff81479852)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
```
```
In crypto/blkcipher.c (ffffffff8147a3b5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_first
```
```
In crypto/skcipher.c (ffffffff8147b905)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_first
```
```
In block/blk-mq.c (ffffffff814a7925)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In lib/dynamic_debug.c (ffffffff81504561)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_emit_prefix
```
```
In drivers/pci/search.c (ffffffff81537b95)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/search.c:pci_find_next_bus
```
```
In drivers/rapidio/rio.c (ffffffff81563a05)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_get_asm
```
```
In drivers/acpi/utils.c (ffffffff8158594c)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_handle_path
```
```
In drivers/acpi/ec.c (ffffffff81592a4d)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/apei/erst.c (ffffffff815ee8f3)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_stall
```
```
In drivers/clk/clk.c (ffffffff815f9cba)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
```
```
In drivers/tty/sysrq.c (ffffffff8163a1a5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff8163b39c)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:reset_vc
```
```
In drivers/tty/vt/vt.c (ffffffff81649fe5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_put_char
  - drivers/tty/vt/vt.c:con_put_char
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:con_write
```
```
In drivers/tty/serial/serial_core.c (ffffffff8164e04b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
```
In drivers/iommu/intel-pasid.c (ffffffff81693e9b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_id
```
```
In drivers/base/power/runtime.c (ffffffff816b0315)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:pm_suspend_timer_fn
  - drivers/base/power/runtime.c:pm_runtime_work
  - drivers/base/power/runtime.c:pm_runtime_work
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/scsi/sr.c (ffffffff817261d3)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/net/phy/mdio_bus.c (ffffffff8175d1c5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff817c7397)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817cc2ee)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff817dfdf7)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817fb715)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/md/dm-table.c (ffffffff81837745)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff81846fd5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81859598)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In net/core/sock.c (ffffffff81897a69)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff8189e6b5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/scm.c (ffffffff818a6153)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff818b10c5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_any
```
```
In net/core/filter.c (ffffffff818d6281)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/page_pool.c (ffffffff818e5022)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/netlink/af_netlink.c (ffffffff8190907e)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff81929ae4)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv6/route.c (ffffffff819ae785)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
```
```
In lib/radix-tree.c (ffffffff81a0d1ac)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In lib/vsprintf.c (ffffffff81a14356)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
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
In init/main.c (ffffffff81002856)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/x86/events/amd/core.c (ffffffff81008c77)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
  - arch/x86/events/amd/core.c:amd_pmu_disable_all
```
```
In arch/x86/xen/spinlock.c (ffffffff8102cc7a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/hyperv/hv_spinlock.c (ffffffff8102ef45)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81034dab)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
```
In arch/x86/kernel/nmi.c (ffffffff81035a26)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/kernel/process.c (ffffffff81a9cbcf)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103dd29)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/hpet.c (ffffffff81075465)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81076ab5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077d75)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In arch/x86/mm/fault.c (ffffffff8107f86b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/mm/tlb.c (ffffffff81087b75)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In kernel/exit.c (ffffffff8109fd02)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff810a189a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
  - kernel/softirq.c:_local_bh_enable
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/workqueue.c (ffffffff810b9968)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (ffffffff810c5d85)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
```
```
In kernel/sched/core.c (ffffffff810ccfbb)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/sched/cputime.c (ffffffff810d539c)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_process_tick
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
```
```
In kernel/sched/idle.c (ffffffff81a9ce46)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/locking/rtmutex.c (ffffffff81a9b6b5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff810fa475)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/process.c (ffffffff810fc953)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
```
In kernel/printk/printk.c (ffffffff81106b0a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_store
```
```
In kernel/irq/manage.c (ffffffff8110aef4)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_irq
```
```
In kernel/rcu/tree.c (ffffffff8111c65e)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
```
```
In kernel/time/timer.c (ffffffff8112af20)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/time/timer.c:update_process_times
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:del_timer_sync
```
```
In kernel/smp.c (ffffffff81143208)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/module.c (ffffffff81147e05)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/module.c:module_memfree
```
```
In kernel/kexec_core.c (ffffffff8114da04)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cpuset.c (ffffffff811651c5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
```
```
In kernel/stop_machine.c (ffffffff81167dcc)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/kprobes.c (ffffffff81175815)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/debug/debug_core.c (ffffffff811789a7)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8117c9d4)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/debug/kdb/kdb_debugger.c (ffffffff81183077)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
```
In kernel/trace/trace_clock.c (ffffffff8118ab09)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ftrace.c (ffffffff8118b264)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/ring_buffer.c (ffffffff81194ac4)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
```
In kernel/trace/trace.c (ffffffff811986c9)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
```
In kernel/trace/trace_functions.c (ffffffff811a6448)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a7293)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_hwlat.c (ffffffff811a8329)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/trace/trace_stack.c (ffffffff811a88ab)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811a935b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811a97e4)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff811ad2bd)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
```
```
In kernel/trace/trace_events.c (ffffffff811aeea4)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b33ba)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_event_perf.c (ffffffff811b36a0)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/bpf_trace.c (ffffffff811c23c8)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c53b4)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/irq_work.c (ffffffff811ce429)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/bpf/stackmap.c (ffffffff811f6315)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff81209555)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
  - kernel/events/core.c:perf_pending_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/ring_buffer.c (ffffffff8120a3e5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In kernel/events/callchain.c (ffffffff8120b783)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/vmalloc.c (ffffffff81269775)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/page_alloc.c (ffffffff81272008)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:warn_alloc
```
```
In mm/mempolicy.c (ffffffff812888c5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/memcontrol.c (ffffffff812b636e)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
```
```
In mm/zsmalloc.c (ffffffff812bd86b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/file_table.c (ffffffff812cd857)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In fs/pstore/platform.c (ffffffff8141b172)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
  - fs/pstore/platform.c:pstore_dump
```
```
In crypto/ablkcipher.c (ffffffff814a76a3)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
```
```
In crypto/blkcipher.c (ffffffff814a83d5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_first
```
```
In crypto/skcipher.c (ffffffff814a9ca5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_first
```
```
In block/blk-mq.c (ffffffff814d596b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In lib/dynamic_debug.c (ffffffff81532676)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_emit_prefix
```
```
In drivers/pci/search.c (ffffffff81567535)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/search.c:pci_find_next_bus
```
```
In drivers/rapidio/rio.c (ffffffff81593da5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_get_asm
```
```
In drivers/acpi/utils.c (ffffffff815b65bc)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_handle_path
```
```
In drivers/acpi/ec.c (ffffffff815c38a7)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/apei/erst.c (ffffffff81620693)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_stall
```
```
In drivers/clk/clk.c (ffffffff8162c06a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
```
```
In drivers/tty/sysrq.c (ffffffff8166e4d5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff8166f6e2)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:reset_vc
```
```
In drivers/tty/vt/vt.c (ffffffff8167e9c5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_put_char
  - drivers/tty/vt/vt.c:con_put_char
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:con_write
```
```
In drivers/tty/serial/serial_core.c (ffffffff81682bd3)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
```
In drivers/iommu/intel-pasid.c (ffffffff816cc7aa)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_id
```
```
In drivers/base/power/runtime.c (ffffffff816e90e1)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/scsi/sr.c (ffffffff81761906)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/net/phy/mdio_bus.c (ffffffff8179a755)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff818066db)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8180c4e3)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff8182086a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In drivers/md/dm-table.c (ffffffff8187a365)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff81889d95)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8189ce2d)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In net/core/sock.c (ffffffff818e1f8a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff818e8f25)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/scm.c (ffffffff818f15dc)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff818fe0d5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_any
```
```
In net/core/filter.c (ffffffff81923a51)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/page_pool.c (ffffffff81934934)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/netlink/af_netlink.c (ffffffff8196a3d1)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff8198cce7)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/nexthop.c (ffffffff819d3bb4)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv6/route.c (ffffffff81a1d019)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
```
```
In lib/radix-tree.c (ffffffff81a7cb12)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In lib/vsprintf.c (ffffffff81a83d1d)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
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
In init/main.c (ffffffff81002856)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/x86/events/amd/core.c (ffffffff81008fd9)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
  - arch/x86/events/amd/core.c:amd_pmu_disable_all
```
```
In arch/x86/xen/spinlock.c (ffffffff8102d54a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/hyperv/hv_spinlock.c (ffffffff8102f8a5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In arch/x86/kernel/dumpstack.c (ffffffff810355db)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
```
In arch/x86/kernel/nmi.c (ffffffff81036226)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/kernel/process.c (ffffffff81ad441f)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103e4e9)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/hpet.c (ffffffff81076435)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81077b05)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff81078de5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In arch/x86/mm/fault.c (ffffffff810808fb)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/mm/tlb.c (ffffffff81088835)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In kernel/exit.c (ffffffff810a6303)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff810a7e5a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
  - kernel/softirq.c:_local_bh_enable
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/workqueue.c (ffffffff810bfde8)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (ffffffff810cee65)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
```
```
In kernel/sched/core.c (ffffffff810d68a5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/sched/cputime.c (ffffffff810df95c)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_process_tick
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
```
```
In kernel/sched/idle.c (ffffffff81ad4696)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/locking/rtmutex.c (ffffffff81ad3005)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff81106255)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/process.c (ffffffff81108d48)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
```
In kernel/printk/printk.c (ffffffff81112e9a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_store
```
```
In kernel/irq/manage.c (ffffffff81117454)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_irq
```
```
In kernel/rcu/tree.c (ffffffff81128dc2)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
```
```
In kernel/time/timer.c (ffffffff81136ebc)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/time/timer.c:update_process_times
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:del_timer_sync
```
```
In kernel/smp.c (ffffffff8114ed48)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/module.c (ffffffff81153c45)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/module.c:module_memfree
```
```
In kernel/kexec_core.c (ffffffff81159714)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cgroup.c (ffffffff81166e28)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/cgroup/cpuset.c (ffffffff811710a5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
```
```
In kernel/stop_machine.c (ffffffff81173c8c)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/kprobes.c (ffffffff81181685)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/debug/debug_core.c (ffffffff811847f4)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81188854)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/debug/kdb/kdb_debugger.c (ffffffff8118eee7)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
```
In kernel/trace/trace_clock.c (ffffffff811969f9)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ftrace.c (ffffffff81197164)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/ring_buffer.c (ffffffff811a0584)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
```
In kernel/trace/trace.c (ffffffff811a3fb9)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
```
In kernel/trace/trace_functions.c (ffffffff811b1c38)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b2a83)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_hwlat.c (ffffffff811b3b29)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/trace/trace_stack.c (ffffffff811b40cb)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811b4b8b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811b4fd4)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff811b8b0d)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
```
```
In kernel/trace/trace_events.c (ffffffff811ba504)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_syscalls.c (ffffffff811be9aa)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_event_perf.c (ffffffff811bec90)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/bpf_trace.c (ffffffff811cdb38)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
```
In kernel/trace/trace_kprobe.c (ffffffff811d104f)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/irq_work.c (ffffffff811daa49)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/events/core.c (ffffffff812168c5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
  - kernel/events/core.c:perf_pending_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/ring_buffer.c (ffffffff812176c5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In kernel/events/callchain.c (ffffffff81218a63)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/vmalloc.c (ffffffff812786b5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/page_alloc.c (ffffffff81280e69)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:warn_alloc
```
```
In mm/hugetlb.c (ffffffff81292ee5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In mm/mempolicy.c (ffffffff81298435)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/memcontrol.c (ffffffff812c823e)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
```
```
In mm/zsmalloc.c (ffffffff812cf75b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/file_table.c (ffffffff812df277)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In fs/pstore/platform.c (ffffffff81434fc2)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
  - fs/pstore/platform.c:pstore_dump
```
```
In crypto/ablkcipher.c (ffffffff814c2323)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
```
```
In crypto/blkcipher.c (ffffffff814c3045)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_first
```
```
In crypto/skcipher.c (ffffffff814c4995)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_first
```
```
In block/blk-mq.c (ffffffff814eec9b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In lib/dynamic_debug.c (ffffffff815534b6)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_emit_prefix
```
```
In drivers/pci/search.c (ffffffff81588885)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/search.c:pci_find_next_bus
```
```
In drivers/rapidio/rio.c (ffffffff815b4ef5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_get_asm
```
```
In drivers/acpi/utils.c (ffffffff815d77ec)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_handle_path
```
```
In drivers/acpi/ec.c (ffffffff815e4ae7)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/apei/erst.c (ffffffff81642173)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_stall
```
```
In drivers/clk/clk.c (ffffffff8164d61a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
```
```
In drivers/tty/sysrq.c (ffffffff81690b15)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81691ce2)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:reset_vc
```
```
In drivers/tty/vt/vt.c (ffffffff816a11d5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_put_char
  - drivers/tty/vt/vt.c:con_put_char
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:con_write
```
```
In drivers/tty/serial/serial_core.c (ffffffff816a5263)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
```
In drivers/iommu/intel-pasid.c (ffffffff816efff7)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_id
```
```
In drivers/base/power/runtime.c (ffffffff8170d141)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/scsi/sr.c (ffffffff817858f6)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/net/phy/mdio_bus.c (ffffffff817be215)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff8183758b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8183d4d5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff81851cda)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In drivers/md/dm-table.c (ffffffff818ac145)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff818bbd35)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818cf20b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In net/core/sock.c (ffffffff8191415a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff8191b085)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/scm.c (ffffffff8192352c)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff81930405)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_any
```
```
In net/core/filter.c (ffffffff81955c81)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/page_pool.c (ffffffff81967235)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/netlink/af_netlink.c (ffffffff819a0e41)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff819c3686)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/nexthop.c (ffffffff81a0a724)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv6/route.c (ffffffff81a53ce9)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
```
```
In lib/radix-tree.c (ffffffff81ab3e42)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In lib/vsprintf.c (ffffffff81abaf8d)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
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
In init/main.c (ffffffff81003876)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/x86/entry/common.c (ffffffff81bbc968)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
```
```
In arch/x86/events/amd/core.c (ffffffff8100a692)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
  - arch/x86/events/amd/core.c:amd_pmu_disable_all
```
```
In arch/x86/xen/spinlock.c (ffffffff8102f67a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/hyperv/hv_spinlock.c (ffffffff81032025)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In arch/x86/kernel/traps.c (ffffffff81bbd704)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/traps.c:exc_double_fault
```
```
In arch/x86/kernel/dumpstack.c (ffffffff8103744d)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
```
In arch/x86/kernel/nmi.c (ffffffff81bbde8e)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/kernel/process.c (ffffffff81bcc514)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/kernel/fpu/core.c (ffffffff810418dc)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81bbea26)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
```
```
In arch/x86/kernel/hpet.c (ffffffff8107d505)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107f185)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff810800d5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In arch/x86/mm/fault.c (ffffffff810878f6)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/mm/tlb.c (ffffffff8108af34)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In kernel/exit.c (ffffffff810ae0ba)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff810af23a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit_rcu
  - kernel/softirq.c:irq_exit_rcu
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
  - kernel/softirq.c:_local_bh_enable
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/workqueue.c (ffffffff810c7138)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (ffffffff810d8b65)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
```
```
In kernel/sched/core.c (ffffffff810e0fa6)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/sched/cputime.c (ffffffff810e7c20)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_process_tick
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
```
```
In kernel/sched/idle.c (ffffffff81bcc701)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In kernel/locking/rtmutex.c (ffffffff81bcb195)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff81111175)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/process.c (ffffffff8111393a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
```
In kernel/printk/printk.c (ffffffff81120082)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
```
```
In kernel/irq/irqdesc.c (ffffffff8112140f)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_irq
```
```
In kernel/irq/manage.c (ffffffff811229f4)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_irq
```
```
In kernel/rcu/tree.c (ffffffff81136d2c)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_nmi_enter
  - kernel/rcu/tree.c:rcu_nmi_enter
  - kernel/rcu/tree.c:rcu_nmi_exit
  - kernel/rcu/tree.c:rcu_nmi_exit
```
```
In kernel/time/timer.c (ffffffff81145b12)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/time/timer.c:update_process_times
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:del_timer_sync
```
```
In kernel/smp.c (ffffffff8115f674)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/module.c (ffffffff81165675)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/module.c:module_memfree
```
```
In kernel/kexec_core.c (ffffffff8116aac4)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cgroup.c (ffffffff81178512)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/cgroup/cpuset.c (ffffffff81182db5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
```
```
In kernel/stop_machine.c (ffffffff81185a8c)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/kprobes.c (ffffffff811950c5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/debug/debug_core.c (ffffffff81198830)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8119dfb4)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/debug/kdb/kdb_debugger.c (ffffffff811a39b7)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
```
In kernel/trace/trace_clock.c (ffffffff811abd29)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ftrace.c (ffffffff811ac473)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/ring_buffer.c (ffffffff811b5854)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
```
In kernel/trace/trace.c (ffffffff811bd3e9)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:ftrace_trace_userstack
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
```
In kernel/trace/trace_functions.c (ffffffff811ca2f8)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811caf83)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_hwlat.c (ffffffff811cbccf)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
```
```
In kernel/trace/trace_stack.c (ffffffff811cc8d7)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811cd39b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811cdd04)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff811d15be)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
```
```
In kernel/trace/trace_events.c (ffffffff811d532e)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d81d5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_event_perf.c (ffffffff811d8670)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/trace_events_inject.c (ffffffff811dd6ff)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:parse_entry
```
```
In kernel/trace/bpf_trace.c (ffffffff811e8d50)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
  - kernel/trace/bpf_trace.c:trace_call_bpf
```
```
In kernel/trace/trace_kprobe.c (ffffffff811ecbf2)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/irq_work.c (ffffffff811f7453)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/bpf/syscall.c (ffffffff81200b22)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_release
```
```
In kernel/bpf/ringbuf.c (ffffffff8121e0ac)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:__bpf_ringbuf_reserve
```
```
In kernel/events/core.c (ffffffff812427c5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
  - kernel/events/core.c:perf_pending_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/ring_buffer.c (ffffffff81242f25)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:__rb_free_aux
```
```
In kernel/events/callchain.c (ffffffff81244458)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_entry
  - kernel/events/callchain.c:get_callchain_entry
  - kernel/events/callchain.c:get_callchain_entry
```
```
In mm/vmalloc.c (ffffffff812ac42f)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/page_alloc.c (ffffffff812b4a21)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
```
```
In mm/hugetlb.c (ffffffff812c6795)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/hugetlb.c:free_huge_page
```
```
In mm/mempolicy.c (ffffffff812ccc05)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/memcontrol.c (ffffffff812fda9e)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
```
```
In mm/zsmalloc.c (ffffffff81306a2b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/file_table.c (ffffffff813160d7)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In fs/io_uring.c (ffffffff81387926)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_cqring_ev_posted
```
```
In fs/pstore/platform.c (ffffffff81484e9f)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
  - fs/pstore/platform.c:pstore_dump
```
```
In crypto/skcipher.c (ffffffff81523925)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_first
```
```
In block/blk-mq.c (ffffffff8154ff2b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In lib/dynamic_debug.c (ffffffff815dc8a6)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_emit_prefix
```
```
In lib/radix-tree.c (ffffffff815edc52)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In lib/vsprintf.c (ffffffff815f75c4)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
```
```
In drivers/pci/search.c (ffffffff8162f3c5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/search.c:pci_find_next_bus
```
```
In drivers/rapidio/rio.c (ffffffff8165ded5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_get_asm
```
```
In drivers/acpi/utils.c (ffffffff81681a1e)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/acpi/utils.c:__acpi_handle_debug
  - drivers/acpi/utils.c:acpi_handle_printk
```
```
In drivers/acpi/ec.c (ffffffff8168fff0)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/apei/erst.c (ffffffff816ef5f3)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_stall
```
```
In drivers/clk/clk.c (ffffffff816ffe4a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
```
```
In drivers/tty/sysrq.c (ffffffff81743305)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81745f7c)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:change_console
  - drivers/tty/vt/vt_ioctl.c:complete_change_console
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
```
```
In drivers/tty/vt/vt.c (ffffffff81753a05)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_put_char
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:do_con_write
```
```
In drivers/tty/serial/serial_core.c (ffffffff81757893)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
```
In drivers/base/power/runtime.c (ffffffff817c9227)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/scsi/sr.c (ffffffff81849b93)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81887255)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_modify
  - drivers/net/phy/mdio_bus.c:mdiobus_write
  - drivers/net/phy/mdio_bus.c:mdiobus_write_nested
  - drivers/net/phy/mdio_bus.c:mdiobus_read
  - drivers/net/phy/mdio_bus.c:mdiobus_read_nested
```
```
In drivers/usb/host/xhci.c (ffffffff81909d31)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8190ff6a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff81923cae)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In drivers/md/dm-table.c (ffffffff8197c355)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff8198c5e5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
```
In drivers/cpuidle/cpuidle.c (ffffffff819a18fa)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In net/core/sock.c (ffffffff819e856b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff819edd95)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/scm.c (ffffffff819f6ac0)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/scm.c:__scm_install_fd
  - net/core/scm.c:__scm_install_fd
```
```
In net/core/dev.c (ffffffff81a04975)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_any
```
```
In net/core/filter.c (ffffffff81a297b1)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/page_pool.c (ffffffff81a3b08c)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page
  - net/core/page_pool.c:page_pool_put_page
```
```
In net/netlink/af_netlink.c (ffffffff81a7a651)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff81aaed8a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/nexthop.c (ffffffff81afb9d4)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv6/route.c (ffffffff81b4b379)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:__ip6_del_rt_siblings
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
In init/main.c (ffffffff81003934)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/x86/events/amd/core.c (ffffffff81009512)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
  - arch/x86/events/amd/core.c:amd_pmu_disable_all
```
```
In arch/x86/xen/spinlock.c (ffffffff810303ea)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/hyperv/hv_spinlock.c (ffffffff81032c85)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81038514)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/dumpstack.c:oops_end
```
```
In arch/x86/kernel/nmi.c (ffffffff81038c64)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff810413b5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:irq_fpu_usable
  - arch/x86/kernel/fpu/core.c:irq_fpu_usable
  - arch/x86/kernel/fpu/core.c:irq_fpu_usable
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8107b13c)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In arch/x86/kernel/hpet.c (ffffffff8107d475)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107edb5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107fcf5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In arch/x86/kernel/perf_regs.c (ffffffff810814db)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/mm/fault.c (ffffffff81088052)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:no_context
```
```
In kernel/exit.c (ffffffff810a976a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff810aaa08)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit_rcu
  - kernel/softirq.c:irq_exit_rcu
  - kernel/softirq.c:irq_exit_rcu
  - kernel/softirq.c:irq_exit_rcu
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
  - kernel/softirq.c:_local_bh_enable
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/workqueue.c (ffffffff810c24f8)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (ffffffff810d3d05)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
  - kernel/async.c:current_is_async
  - kernel/async.c:current_is_async
```
```
In kernel/sched/core.c (ffffffff810de3d3)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
```
```
In kernel/sched/cputime.c (ffffffff810e5910)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_process_tick
  - kernel/sched/cputime.c:account_process_tick
  - kernel/sched/cputime.c:account_process_tick
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
```
```
In kernel/locking/rtmutex.c (ffffffff81c44035)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff8110e2f5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/process.c (ffffffff81bdec6d)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
```
In kernel/printk/printk.c (ffffffff8111ad2d)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
```
```
In kernel/irq/irqdesc.c (ffffffff8111d3ef)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_irq
```
```
In kernel/irq/manage.c (ffffffff8111e824)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
```
```
In kernel/rcu/tree.c (ffffffff81132391)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_nmi_enter
  - kernel/rcu/tree.c:rcu_nmi_enter
  - kernel/rcu/tree.c:rcu_nmi_exit
  - kernel/rcu/tree.c:rcu_nmi_exit
```
```
In kernel/livepatch/patch.c (ffffffff81135cf7)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/entry/common.c (ffffffff8113bbd5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_exit_cond_resched
  - kernel/entry/common.c:irqentry_nmi_exit
  - kernel/entry/common.c:irqentry_nmi_enter
```
```
In kernel/time/timer.c (ffffffff81142144)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/time/timer.c:update_process_times
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:del_timer_sync
```
```
In kernel/smp.c (ffffffff8115b614)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/module.c (ffffffff81161de5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/module.c:module_memfree
  - kernel/module.c:module_memfree
  - kernel/module.c:module_memfree
```
```
In kernel/kexec_core.c (ffffffff81167204)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
  - kernel/kexec_core.c:kexec_should_crash
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cgroup.c (ffffffff8117524e)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/cgroup/cpuset.c (ffffffff8117fd15)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
```
```
In kernel/stop_machine.c (ffffffff81182bac)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/debug/debug_core.c (ffffffff81195990)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_debugger.c (ffffffff811a0b27)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
```
In kernel/trace/trace_clock.c (ffffffff811a95e9)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ftrace.c (ffffffff811a9d71)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/ring_buffer.c (ffffffff811b3134)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
```
In kernel/trace/trace.c (ffffffff811baff9)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
```
In kernel/trace/trace_functions.c (ffffffff811c7968)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c8663)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_hwlat.c (ffffffff811c931f)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
```
```
In kernel/trace/trace_stack.c (ffffffff811c9e17)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811ca88b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811cb1e4)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff811ce9be)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
```
```
In kernel/trace/trace_events.c (ffffffff811d24be)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d5295)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_event_perf.c (ffffffff811d56e0)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/trace_events_inject.c (ffffffff811da7ff)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:parse_entry
```
```
In kernel/trace/bpf_trace.c (ffffffff811e6130)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
```
In kernel/trace/trace_kprobe.c (ffffffff811ead42)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/irq_work.c (ffffffff811f5fc3)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/bpf/syscall.c (ffffffff811fffe2)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_release
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
```
```
In kernel/bpf/percpu_freelist.c (ffffffff8121e0ab)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
```
```
In kernel/bpf/ringbuf.c (ffffffff81220e4c)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:__bpf_ringbuf_reserve
```
```
In kernel/events/core.c (ffffffff8124cf1c)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/ring_buffer.c (ffffffff8124d5c5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:__rb_free_aux
```
```
In kernel/events/callchain.c (ffffffff8124ed4b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_entry
```
```
In mm/vmalloc.c (ffffffff812b7525)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/page_alloc.c (ffffffff812bf106)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:warn_alloc
  - mm/page_alloc.c:warn_alloc
  - mm/page_alloc.c:warn_alloc
```
```
In mm/hugetlb.c (ffffffff812d2395)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/mempolicy.c (ffffffff812dade5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/memcontrol.c (ffffffff81309eee)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:get_obj_cgroup_from_current
  - mm/memcontrol.c:get_obj_cgroup_from_current
  - mm/memcontrol.c:get_obj_cgroup_from_current
  - mm/memcontrol.c:get_obj_cgroup_from_current
  - mm/memcontrol.c:get_obj_cgroup_from_current
  - mm/memcontrol.c:get_obj_cgroup_from_current
  - mm/memcontrol.c:get_obj_cgroup_from_current
  - mm/memcontrol.c:get_obj_cgroup_from_current
  - mm/memcontrol.c:get_obj_cgroup_from_current
  - mm/memcontrol.c:get_obj_cgroup_from_current
  - mm/memcontrol.c:get_obj_cgroup_from_current
  - mm/memcontrol.c:get_obj_cgroup_from_current
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
```
```
In mm/zsmalloc.c (ffffffff813128ab)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/file_table.c (ffffffff8132126e)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In fs/buffer.c (ffffffff81367a5c)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81376083)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81377bf1)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/io_uring.c (ffffffff813982b4)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_openat2
  - fs/io_uring.c:io_openat2
  - fs/io_uring.c:io_openat2
  - fs/io_uring.c:io_iopoll_queue
  - fs/io_uring.c:io_iopoll_queue
  - fs/io_uring.c:io_iopoll_queue
  - fs/io_uring.c:io_cqring_ev_posted_iopoll
  - fs/io_uring.c:io_cqring_ev_posted_iopoll
  - fs/io_uring.c:io_cqring_ev_posted_iopoll
  - fs/io_uring.c:io_cqring_ev_posted
  - fs/io_uring.c:io_cqring_ev_posted
  - fs/io_uring.c:io_cqring_ev_posted
```
```
In fs/pstore/platform.c (ffffffff814a25e6)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
  - fs/pstore/platform.c:pstore_dump
```
```
In crypto/skcipher.c (ffffffff81540875)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_first
```
```
In block/blk-mq.c (ffffffff8156b9c5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In lib/dynamic_debug.c (ffffffff815fa826)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_emit_prefix
  - lib/dynamic_debug.c:dynamic_emit_prefix
  - lib/dynamic_debug.c:dynamic_emit_prefix
```
```
In lib/radix-tree.c (ffffffff81612382)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In lib/vsprintf.c (ffffffff8161bc84)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
```
```
In drivers/pci/search.c (ffffffff81654a55)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/search.c:pci_find_next_bus
  - drivers/pci/search.c:pci_find_next_bus
  - drivers/pci/search.c:pci_find_next_bus
```
```
In drivers/acpi/utils.c (ffffffff8169fecc)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_handle_path
  - drivers/acpi/utils.c:acpi_handle_path
  - drivers/acpi/utils.c:acpi_handle_path
```
```
In drivers/acpi/apei/erst.c (ffffffff8170c9d3)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_stall
```
```
In drivers/clk/clk.c (ffffffff8171d194)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
```
```
In drivers/tty/sysrq.c (ffffffff8175f185)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81760e72)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:reset_vc
  - drivers/tty/vt/vt_ioctl.c:reset_vc
  - drivers/tty/vt/vt_ioctl.c:reset_vc
```
```
In drivers/tty/vt/vt.c (ffffffff8176ef25)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_put_char
  - drivers/tty/vt/vt.c:con_put_char
  - drivers/tty/vt/vt.c:con_put_char
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_write
```
```
In drivers/tty/serial/serial_core.c (ffffffff81772953)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
```
In drivers/base/power/runtime.c (ffffffff817ddb54)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff8192b43e)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff81990045)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
```
In net/core/sock.c (ffffffff819e81ef)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff819eda35)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/dev.c (ffffffff81a08485)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/dev.c:netif_rx_any_context
  - net/core/dev.c:netif_rx_any_context
  - net/core/dev.c:netif_rx_any_context
  - net/core/dev.c:__dev_kfree_skb_any
```
```
In net/core/filter.c (ffffffff81a2a111)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/page_pool.c (ffffffff81a3d371)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page
  - net/core/page_pool.c:page_pool_put_page
```
```
In net/core/bpf_sk_storage.c (ffffffff81a69f75)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
```
```
In net/netlink/af_netlink.c (ffffffff81a834c1)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff81ab8fe8)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/nexthop.c (ffffffff81b090a4)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv6/route.c (ffffffff81b5a00a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:__ip6_del_rt_siblings
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
In init/main.c (ffffffff81003914)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/x86/events/amd/core.c (ffffffff81009edd)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
  - arch/x86/events/amd/core.c:amd_pmu_disable_all
```
```
In arch/x86/xen/spinlock.c (ffffffff81030eea)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/hyperv/hv_spinlock.c (ffffffff81034795)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In arch/x86/kernel/dumpstack.c (ffffffff8103a058)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/dumpstack.c:oops_end
```
```
In arch/x86/kernel/nmi.c (ffffffff8103a774)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81042db5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:irq_fpu_usable
  - arch/x86/kernel/fpu/core.c:irq_fpu_usable
  - arch/x86/kernel/fpu/core.c:irq_fpu_usable
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8107c349)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In arch/x86/kernel/hpet.c (ffffffff8107e835)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107feb5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff81080db5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In arch/x86/kernel/perf_regs.c (ffffffff810822fe)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/mm/fault.c (ffffffff81088b1d)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
```
```
In arch/x86/platform/efi/quirks.c (ffffffff810970d5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_crash_gracefully_on_page_fault
  - arch/x86/platform/efi/quirks.c:efi_crash_gracefully_on_page_fault
  - arch/x86/platform/efi/quirks.c:efi_crash_gracefully_on_page_fault
```
```
In kernel/exit.c (ffffffff810aa7aa)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff810abd58)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit_rcu
  - kernel/softirq.c:irq_exit_rcu
  - kernel/softirq.c:irq_exit_rcu
  - kernel/softirq.c:irq_exit_rcu
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
  - kernel/softirq.c:_local_bh_enable
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/workqueue.c (ffffffff810c4188)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (ffffffff810d5995)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
  - kernel/async.c:current_is_async
  - kernel/async.c:current_is_async
```
```
In kernel/sched/core.c (ffffffff810dfec7)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
```
```
In kernel/sched/cputime.c (ffffffff810e78e0)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_process_tick
  - kernel/sched/cputime.c:account_process_tick
  - kernel/sched/cputime.c:account_process_tick
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
```
```
In kernel/locking/qrwlock.c (ffffffff8110ee05)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/process.c (ffffffff81bd0de3)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
```
In kernel/printk/printk.c (ffffffff8111b2cd)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
```
```
In kernel/irq/irqdesc.c (ffffffff8111d76f)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_irq
```
```
In kernel/irq/manage.c (ffffffff8111ecb4)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
```
```
In kernel/rcu/tree.c (ffffffff811335d7)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_nmi_enter
  - kernel/rcu/tree.c:rcu_nmi_enter
  - kernel/rcu/tree.c:rcu_nmi_exit
  - kernel/rcu/tree.c:rcu_nmi_exit
```
```
In kernel/livepatch/patch.c (ffffffff81136b21)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/entry/common.c (ffffffff8113cec5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_exit_cond_resched
  - kernel/entry/common.c:irqentry_nmi_exit
  - kernel/entry/common.c:irqentry_nmi_enter
```
```
In kernel/time/timer.c (ffffffff81143334)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/time/timer.c:update_process_times
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:del_timer_sync
```
```
In kernel/smp.c (ffffffff8115c6ca)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/module.c (ffffffff81162875)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/module.c:module_memfree
  - kernel/module.c:module_memfree
  - kernel/module.c:module_memfree
```
```
In kernel/kexec_core.c (ffffffff81167f94)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
  - kernel/kexec_core.c:kexec_should_crash
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cgroup.c (ffffffff81175dae)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/cgroup/cpuset.c (ffffffff811807f5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
```
```
In kernel/stop_machine.c (ffffffff81183cfc)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/debug/debug_core.c (ffffffff81196930)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_debugger.c (ffffffff811a1756)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
```
In kernel/trace/trace_clock.c (ffffffff811aa1a5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ftrace.c (ffffffff811aa931)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/ring_buffer.c (ffffffff811b57d4)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
```
In kernel/trace/trace.c (ffffffff811bfb7d)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:tracing_gen_ctx_irq_test
  - kernel/trace/trace.c:tracing_gen_ctx_irq_test
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
```
In kernel/trace/trace_functions.c (ffffffff811c9464)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c9e2d)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_stack.c (ffffffff811cb1c7)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811cc504)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_event_perf.c (ffffffff811d6c00)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/bpf_trace.c (ffffffff811e77f0)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
```
In kernel/irq_work.c (ffffffff811f6eb3)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/bpf/syscall.c (ffffffff81200992)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_release
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
```
```
In kernel/bpf/percpu_freelist.c (ffffffff812219e5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop
```
```
In kernel/bpf/ringbuf.c (ffffffff812248eb)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:__bpf_ringbuf_reserve
```
```
In kernel/events/core.c (ffffffff8125161c)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/ring_buffer.c (ffffffff81251f05)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:__rb_free_aux
```
```
In kernel/events/callchain.c (ffffffff8125365b)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_entry
```
```
In mm/vmalloc.c (ffffffff812bcdf5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
```
```
In mm/page_alloc.c (ffffffff812c41a0)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:warn_alloc
  - mm/page_alloc.c:warn_alloc
  - mm/page_alloc.c:warn_alloc
```
```
In mm/mempolicy.c (ffffffff812e2645)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/memcontrol.c (ffffffff8131075e)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
```
```
In mm/zsmalloc.c (ffffffff813188e5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/file_table.c (ffffffff813276d7)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In fs/buffer.c (ffffffff8136e661)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff8137ca23)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8137e6ab)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/io_uring.c (ffffffff8139f33d)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_rw_should_reissue
  - fs/io_uring.c:io_rw_should_reissue
  - fs/io_uring.c:io_rw_should_reissue
  - fs/io_uring.c:io_rw_should_reissue
  - fs/io_uring.c:io_rw_should_reissue
  - fs/io_uring.c:io_rw_should_reissue
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_cqring_ev_posted
  - fs/io_uring.c:io_cqring_ev_posted
  - fs/io_uring.c:io_cqring_ev_posted
```
```
In fs/pstore/platform.c (ffffffff814a8690)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
  - fs/pstore/platform.c:pstore_dump
```
```
In crypto/skcipher.c (ffffffff81548ed5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_first
```
```
In block/blk-mq.c (ffffffff81573695)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In lib/dynamic_debug.c (ffffffff815dd403)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_emit_prefix
  - lib/dynamic_debug.c:__dynamic_emit_prefix
  - lib/dynamic_debug.c:__dynamic_emit_prefix
```
```
In lib/radix-tree.c (ffffffff815f5a62)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In lib/vsprintf.c (ffffffff815ff52c)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
```
```
In drivers/acpi/utils.c (ffffffff81682d4c)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_handle_path
  - drivers/acpi/utils.c:acpi_handle_path
  - drivers/acpi/utils.c:acpi_handle_path
```
```
In drivers/acpi/apei/erst.c (ffffffff816ee033)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_stall
```
```
In drivers/clk/clk.c (ffffffff816fdfc4)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
```
```
In drivers/tty/sysrq.c (ffffffff81742ff5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/vt.c (ffffffff81752a85)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_put_char
  - drivers/tty/vt/vt.c:con_put_char
  - drivers/tty/vt/vt.c:con_put_char
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_write
```
```
In drivers/base/power/runtime.c (ffffffff817c1ed4)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/clock_ops.c (ffffffff817cce25)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_op_lock
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff8190e95e)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff819745c5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
```
In net/core/sock.c (ffffffff819ce31f)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff819d5915)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_alloc
  - net/core/skbuff.c:msg_zerocopy_alloc
  - net/core/skbuff.c:msg_zerocopy_alloc
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_frag_align
```
```
In net/core/dev.c (ffffffff819eebe5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/core/dev.c:netif_rx_any_context
  - net/core/dev.c:netif_rx_any_context
  - net/core/dev.c:netif_rx_any_context
  - net/core/dev.c:validate_xmit_vlan
```
```
In net/core/filter.c (ffffffff81a1135b)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/page_pool.c (ffffffff81a24191)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page
  - net/core/page_pool.c:page_pool_put_page
```
```
In net/core/bpf_sk_storage.c (ffffffff81a52475)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
```
```
In net/netlink/af_netlink.c (ffffffff81a6c591)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff81aa429b)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/nexthop.c (ffffffff81af7234)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv6/route.c (ffffffff81b481ea)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:__ip6_del_rt_siblings
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
In init/main.c (ffffffff81003954)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/x86/events/amd/core.c (ffffffff8100afed)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
  - arch/x86/events/amd/core.c:amd_pmu_disable_all
```
```
In arch/x86/xen/spinlock.c (ffffffff8103608a)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/hyperv/hv_spinlock.c (ffffffff81039a35)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In arch/x86/kernel/dumpstack.c (ffffffff8103fa08)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/dumpstack.c:oops_end
```
```
In arch/x86/kernel/nmi.c (ffffffff8104013d)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81049125)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:irq_fpu_usable
  - arch/x86/kernel/fpu/core.c:irq_fpu_usable
  - arch/x86/kernel/fpu/core.c:irq_fpu_usable
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8108a48f)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In arch/x86/kernel/hpet.c (ffffffff8108d4b5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8108ecf5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff8108fd25)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In arch/x86/kernel/perf_regs.c (ffffffff8109130e)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/mm/fault.c (ffffffff81097f56)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
```
```
In arch/x86/platform/efi/quirks.c (ffffffff810a7045)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_crash_gracefully_on_page_fault
  - arch/x86/platform/efi/quirks.c:efi_crash_gracefully_on_page_fault
  - arch/x86/platform/efi/quirks.c:efi_crash_gracefully_on_page_fault
```
```
In kernel/exit.c (ffffffff810bc2d6)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff810bde33)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit_rcu
  - kernel/softirq.c:irq_exit_rcu
  - kernel/softirq.c:irq_exit_rcu
  - kernel/softirq.c:irq_exit_rcu
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
  - kernel/softirq.c:_local_bh_enable
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/workqueue.c (ffffffff810d6db8)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (ffffffff810e8bb5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
  - kernel/async.c:current_is_async
  - kernel/async.c:current_is_async
```
```
In kernel/sched/core.c (ffffffff810f503c)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
```
```
In kernel/sched/cputime.c (ffffffff810fef7d)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_process_tick
  - kernel/sched/cputime.c:account_process_tick
  - kernel/sched/cputime.c:account_process_tick
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
```
```
In kernel/sched/fair.c (ffffffff81104487)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
```
```
In kernel/locking/qrwlock.c (ffffffff8112e6a5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/process.c (ffffffff81ca9b31)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
```
In kernel/printk/printk.c (ffffffff8113b613)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
```
```
In kernel/printk/printk_safe.c (ffffffff8113c3b0)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:vprintk
```
```
In kernel/irq/irqdesc.c (ffffffff8113dafa)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:handle_irq_desc
```
```
In kernel/irq/manage.c (ffffffff8113f284)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
```
```
In kernel/rcu/tree.c (ffffffff811559c3)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_nmi_enter
  - kernel/rcu/tree.c:rcu_nmi_enter
  - kernel/rcu/tree.c:rcu_nmi_exit
  - kernel/rcu/tree.c:rcu_nmi_exit
```
```
In kernel/livepatch/patch.c (ffffffff81159767)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/entry/common.c (ffffffff8115ffe5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_exit_cond_resched
  - kernel/entry/common.c:irqentry_nmi_exit
  - kernel/entry/common.c:irqentry_nmi_enter
```
```
In kernel/time/timer.c (ffffffff811668b4)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/time/timer.c:update_process_times
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:del_timer_sync
```
```
In kernel/smp.c (ffffffff811817fc)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/module.c (ffffffff81187de5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/module.c:module_memfree
  - kernel/module.c:module_memfree
  - kernel/module.c:module_memfree
```
```
In kernel/kexec_core.c (ffffffff8118d979)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
  - kernel/kexec_core.c:kexec_should_crash
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cgroup.c (ffffffff8119d383)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/cgroup/cpuset.c (ffffffff811a85e5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
```
```
In kernel/stop_machine.c (ffffffff811abe89)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/debug/debug_core.c (ffffffff811bfc9e)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_debugger.c (ffffffff811caef6)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
```
In kernel/trace/trace_clock.c (ffffffff811d3d15)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ftrace.c (ffffffff811d45a3)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/ring_buffer.c (ffffffff811dfe64)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
```
In kernel/trace/trace.c (ffffffff811ea4cd)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:tracing_gen_ctx_irq_test
  - kernel/trace/trace.c:tracing_gen_ctx_irq_test
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
```
In kernel/trace/trace_functions.c (ffffffff811f4eba)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811f59bd)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_stack.c (ffffffff811f74d8)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811f8b0c)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_event_perf.c (ffffffff81203b15)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/bpf_trace.c (ffffffff81218470)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
```
In kernel/irq_work.c (ffffffff81228483)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/bpf/syscall.c (ffffffff81232702)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_release
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
```
```
In kernel/bpf/helpers.c (ffffffff8124ffc5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_timer_cancel
  - kernel/bpf/helpers.c:bpf_timer_start
  - kernel/bpf/helpers.c:bpf_timer_set_callback
  - kernel/bpf/helpers.c:bpf_timer_init
```
```
In kernel/bpf/percpu_freelist.c (ffffffff81259485)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop
```
```
In kernel/bpf/ringbuf.c (ffffffff8125c82b)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:__bpf_ringbuf_reserve
```
```
In kernel/events/core.c (ffffffff8128c41c)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/ring_buffer.c (ffffffff8128d7a5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In kernel/events/callchain.c (ffffffff8128ef9b)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_entry
```
```
In mm/vmalloc.c (ffffffff812ff605)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - mm/vmalloc.c:vunmap
  - mm/vmalloc.c:vunmap
  - mm/vmalloc.c:vunmap
  - mm/vmalloc.c:vfree
  - mm/vmalloc.c:vfree
  - mm/vmalloc.c:vfree
  - mm/vmalloc.c:vfree
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
```
```
In mm/page_alloc.c (ffffffff8130804a)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:warn_alloc
  - mm/page_alloc.c:warn_alloc
  - mm/page_alloc.c:warn_alloc
```
```
In mm/mempolicy.c (ffffffff81329875)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/memcontrol.c (ffffffff8135b928)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:drain_local_stock
  - mm/memcontrol.c:drain_local_stock
  - mm/memcontrol.c:drain_local_stock
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In mm/zsmalloc.c (ffffffff81364c25)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/file_table.c (ffffffff81374cd7)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In fs/buffer.c (ffffffff813bd8f4)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff813c9923)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff813cb78b)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/io_uring.c (ffffffff813ed112)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_try_cancel_userdata
  - fs/io_uring.c:io_try_cancel_userdata
  - fs/io_uring.c:io_try_cancel_userdata
  - fs/io_uring.c:io_rw_should_reissue
  - fs/io_uring.c:io_rw_should_reissue
  - fs/io_uring.c:io_rw_should_reissue
  - fs/io_uring.c:io_rw_should_reissue
  - fs/io_uring.c:io_rw_should_reissue
  - fs/io_uring.c:io_rw_should_reissue
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_cqring_ev_posted
  - fs/io_uring.c:io_cqring_ev_posted
  - fs/io_uring.c:io_cqring_ev_posted
```
```
In fs/pstore/platform.c (ffffffff815009c0)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
  - fs/pstore/platform.c:pstore_dump
```
```
In crypto/skcipher.c (ffffffff815a96b5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_first
```
```
In block/blk-mq.c (ffffffff815d8075)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In lib/dynamic_debug.c (ffffffff81648db3)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_emit_prefix
  - lib/dynamic_debug.c:__dynamic_emit_prefix
  - lib/dynamic_debug.c:__dynamic_emit_prefix
```
```
In lib/radix-tree.c (ffffffff81662ed2)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In lib/vsprintf.c (ffffffff8166d29c)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
```
```
In drivers/acpi/utils.c (ffffffff816f7e9c)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_handle_path
  - drivers/acpi/utils.c:acpi_handle_path
  - drivers/acpi/utils.c:acpi_handle_path
```
```
In drivers/acpi/apei/erst.c (ffffffff81768113)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_stall
```
```
In drivers/clk/clk.c (ffffffff817778f1)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
```
```
In drivers/xen/grant-table.c (ffffffff81790dc5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/tty/sysrq.c (ffffffff817c3a25)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/vt.c (ffffffff817d587f)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_write
```
```
In drivers/base/power/runtime.c (ffffffff8184bd81)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/clock_ops.c (ffffffff81857405)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_op_lock
```
```
In drivers/block/loop.c (ffffffff81870022)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff819af6fe)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff81a1d2c5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
```
In net/core/sock.c (ffffffff81a7dbff)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff81a85545)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_alloc
  - net/core/skbuff.c:msg_zerocopy_alloc
  - net/core/skbuff.c:msg_zerocopy_alloc
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_frag_align
```
```
In net/core/dev.c (ffffffff81a9ff35)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/core/dev.c:netif_rx_any_context
  - net/core/dev.c:netif_rx_any_context
  - net/core/dev.c:netif_rx_any_context
  - net/core/dev.c:validate_xmit_vlan
```
```
In net/core/filter.c (ffffffff81acc775)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/page_pool.c (ffffffff81ad8780)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page
  - net/core/page_pool.c:page_pool_put_page
```
```
In net/core/bpf_sk_storage.c (ffffffff81b0b575)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
```
```
In net/netlink/af_netlink.c (ffffffff81b25be1)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff81b5ff51)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81b7526d)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/nexthop.c (ffffffff81bb6bd4)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv6/route.c (ffffffff81c0f4ba)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:__ip6_del_rt_siblings
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
In init/main.c (ffffffff81001572)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/x86/events/amd/core.c (ffffffff8100a783)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_check_overflow
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83452802)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
```
```
In arch/x86/xen/multicalls.c (ffffffff81035d0b)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:xen_mc_flush
```
```
In arch/x86/xen/spinlock.c (ffffffff8103be8a)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/hyperv/ivm.c (ffffffff8103edc3)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_read
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
  - arch/x86/hyperv/ivm.c:hv_ghcb_hypercall
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8103f9ce)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In arch/x86/hyperv/hv_spinlock.c (ffffffff81040935)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In arch/x86/kernel/traps.c (ffffffff81042604)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:gp_try_fixup_and_notify
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81047177)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/dumpstack.c:oops_end
```
```
In arch/x86/kernel/nmi.c (ffffffff81047acd)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/kernel/ldt.c (ffffffff81048a03)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:switch_ldt
```
```
In arch/x86/kernel/process.c (ffffffff8105134c)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81052c85)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107e825)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81082025)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_update_lepubkeyhash
```
```
In arch/x86/kernel/ftrace.c (ffffffff8109508b)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8109a9ee)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In arch/x86/kernel/hpet.c (ffffffff8109d655)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:read_hpet
```
```
In arch/x86/kernel/kvm.c (ffffffff8109ed45)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff810a0c65)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In arch/x86/kernel/perf_regs.c (ffffffff810a243e)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/mm/fault.c (ffffffff810aab33)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
```
```
In arch/x86/mm/tlb.c (ffffffff810af3c5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
```
```
In arch/x86/platform/efi/quirks.c (ffffffff810bc385)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_crash_gracefully_on_page_fault
  - arch/x86/platform/efi/quirks.c:efi_crash_gracefully_on_page_fault
  - arch/x86/platform/efi/quirks.c:efi_crash_gracefully_on_page_fault
```
```
In kernel/exit.c (ffffffff810d341c)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/exit.c:make_task_dead
  - kernel/exit.c:make_task_dead
  - kernel/exit.c:make_task_dead
  - kernel/exit.c:make_task_dead
  - kernel/exit.c:make_task_dead
```
```
In kernel/softirq.c (ffffffff810d4e41)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:__irq_exit_rcu
  - kernel/softirq.c:__irq_exit_rcu
  - kernel/softirq.c:__irq_exit_rcu
  - kernel/softirq.c:__irq_exit_rcu
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/workqueue.c (ffffffff810f0997)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (ffffffff81103685)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
  - kernel/async.c:current_is_async
  - kernel/async.c:current_is_async
```
```
In kernel/sched/core.c (ffffffff81111ab0)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_notrace
  - kernel/sched/core.c:preempt_schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
```
```
In kernel/sched/fair.c (ffffffff8112190a)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
```
```
In kernel/sched/build_policy.c (ffffffff8113987a)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:account_process_tick
  - kernel/sched/build_policy.c:account_process_tick
  - kernel/sched/build_policy.c:account_process_tick
  - kernel/sched/build_policy.c:account_system_time
  - kernel/sched/build_policy.c:account_system_time
  - kernel/sched/build_policy.c:account_system_time
  - kernel/sched/build_policy.c:account_system_time
  - kernel/sched/build_policy.c:account_system_time
```
```
In kernel/locking/qrwlock.c (ffffffff8114f8c5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/process.c (ffffffff81e59a51)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
```
In kernel/printk/printk.c (ffffffff8115e772)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:printk_sprint
```
```
In kernel/printk/printk_safe.c (ffffffff8115f52f)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:vprintk
```
```
In kernel/irq/irqdesc.c (ffffffff81161b35)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_domain_nmi
  - kernel/irq/irqdesc.c:handle_irq_desc
```
```
In kernel/irq/manage.c (ffffffff81165455)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
```
```
In kernel/rcu/tree.c (ffffffff8117dbae)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_flavor_sched_clock_irq
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/livepatch/patch.c (ffffffff81182d27)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/entry/common.c (ffffffff81f18732)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_nmi_exit
  - kernel/entry/common.c:irqentry_nmi_enter
```
```
In kernel/module/main.c (ffffffff8118df25)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/module/main.c:module_memfree
  - kernel/module/main.c:module_memfree
  - kernel/module/main.c:module_memfree
```
```
In kernel/time/timer.c (ffffffff81199f96)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/time/timer.c:update_process_times
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:del_timer_sync
```
```
In kernel/smp.c (ffffffff811b7e0a)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/kexec_core.c (ffffffff811bce69)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
  - kernel/kexec_core.c:kexec_should_crash
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cgroup.c (ffffffff811cd6d6)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/cgroup/cpuset.c (ffffffff811d9765)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
```
```
In kernel/stop_machine.c (ffffffff811dd948)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/debug/debug_core.c (ffffffff811f31a3)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_debugger.c (ffffffff811febfb)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
```
In kernel/trace/trace_clock.c (ffffffff81208880)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ftrace.c (ffffffff812098c8)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:arch_ftrace_ops_list_func
```
```
In kernel/trace/ring_buffer.c (ffffffff81213d12)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
```
In kernel/trace/trace.c (ffffffff812223bb)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:tracing_gen_ctx_irq_test
  - kernel/trace/trace.c:tracing_gen_ctx_irq_test
  - kernel/trace/trace.c:tracing_gen_ctx_irq_test
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
```
In kernel/trace/trace_functions.c (ffffffff8122e069)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8122f81a)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_stack.c (ffffffff81231040)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8123252c)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_event_perf.c (ffffffff8123eeef)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/bpf_trace.c (ffffffff81256730)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
```
In kernel/trace/fprobe.c (ffffffff81268584)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In kernel/irq_work.c (ffffffff812694d8)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/bpf/syscall.c (ffffffff81275ab2)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_release
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
```
```
In kernel/bpf/helpers.c (ffffffff812978f5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_timer_cancel
  - kernel/bpf/helpers.c:bpf_timer_start
  - kernel/bpf/helpers.c:bpf_timer_set_callback
  - kernel/bpf/helpers.c:bpf_timer_init
```
```
In kernel/bpf/percpu_freelist.c (ffffffff812a23f5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop
```
```
In kernel/bpf/ringbuf.c (ffffffff812a659b)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:__bpf_ringbuf_reserve
```
```
In kernel/events/core.c (ffffffff812e0fc2)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/ring_buffer.c (ffffffff812e2555)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In kernel/events/callchain.c (ffffffff812e3ee1)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_entry
```
```
In mm/vmalloc.c (ffffffff81366705)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - mm/vmalloc.c:vfree
  - mm/vmalloc.c:vfree
  - mm/vmalloc.c:vfree
  - mm/vmalloc.c:vfree
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/page_alloc.c (ffffffff8137027e)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:warn_alloc
  - mm/page_alloc.c:warn_alloc
  - mm/page_alloc.c:warn_alloc
```
```
In mm/mempolicy.c (ffffffff81399345)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/memcontrol.c (ffffffff813d51d6)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:get_obj_cgroup_from_page
  - mm/memcontrol.c:get_obj_cgroup_from_page
  - mm/memcontrol.c:get_obj_cgroup_from_page
  - mm/memcontrol.c:get_obj_cgroup_from_page
  - mm/memcontrol.c:get_obj_cgroup_from_page
  - mm/memcontrol.c:get_obj_cgroup_from_page
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In mm/zsmalloc.c (ffffffff813e1638)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/file_table.c (ffffffff813f3664)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In fs/buffer.c (ffffffff814444f4)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff814513a4)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81453e19)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/pstore/platform.c (ffffffff81591b8e)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
  - fs/pstore/platform.c:pstore_dump
```
```
In crypto/skcipher.c (ffffffff81650af5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_first
```
```
In block/blk-mq.c (ffffffff816833e5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In io_uring/io_uring.c (ffffffff816d314d)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_try_cancel
  - io_uring/io_uring.c:io_try_cancel
  - io_uring/io_uring.c:io_try_cancel
  - io_uring/io_uring.c:io_rw_should_reissue
  - io_uring/io_uring.c:io_rw_should_reissue
  - io_uring/io_uring.c:io_rw_should_reissue
  - io_uring/io_uring.c:io_rw_should_reissue
  - io_uring/io_uring.c:io_rw_should_reissue
  - io_uring/io_uring.c:io_rw_should_reissue
  - io_uring/io_uring.c:__io_commit_cqring_flush
  - io_uring/io_uring.c:__io_commit_cqring_flush
  - io_uring/io_uring.c:__io_commit_cqring_flush
```
```
In lib/dynamic_debug.c (ffffffff8175f293)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_emit_prefix
  - lib/dynamic_debug.c:__dynamic_emit_prefix
  - lib/dynamic_debug.c:__dynamic_emit_prefix
```
```
In lib/radix-tree.c (ffffffff8177d0ea)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In lib/vsprintf.c (ffffffff817875da)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
```
```
In drivers/acpi/utils.c (ffffffff81824e8c)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_handle_path
  - drivers/acpi/utils.c:acpi_handle_path
  - drivers/acpi/utils.c:acpi_handle_path
```
```
In drivers/acpi/apei/erst.c (ffffffff8189c82b)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_stall
```
```
In drivers/clk/clk.c (ffffffff818ade6c)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
```
```
In drivers/xen/grant-table.c (ffffffff818c9415)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/time.c (ffffffff818cb255)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_get_runstate_snapshot_cpu_delta
```
```
In drivers/tty/sysrq.c (ffffffff81900645)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/vt.c (ffffffff819137ff)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_write
```
```
In drivers/char/random.c (ffffffff8193491a)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_timer_randomness
```
```
In drivers/base/power/runtime.c (ffffffff819916d2)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/clock_ops.c (ffffffff8199d8d5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_op_lock
```
```
In drivers/block/loop.c (ffffffff819b7615)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff81b0de8e)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff81b8658e)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
```
In net/core/sock.c (ffffffff81bf24ef)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff81bf8337)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_frag_align
```
```
In net/core/gen_stats.c (ffffffff81c02a13)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In net/core/dev.c (ffffffff81c0f425)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_any
```
```
In net/core/filter.c (ffffffff81c49605)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/page_pool.c (ffffffff81c595fc)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_defragged_page
  - net/core/page_pool.c:page_pool_put_defragged_page
```
```
In net/core/bpf_sk_storage.c (ffffffff81c91b75)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
```
```
In net/netlink/af_netlink.c (ffffffff81cae799)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff81ceed9e)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81d04a8e)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/nexthop.c (ffffffff81d4a834)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv6/route.c (ffffffff81daa60a)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:__ip6_del_rt_siblings
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
In init/main.c (ffffffff81001bb2)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/x86/events/amd/core.c (ffffffff8100c443)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_check_overflow
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83e6f885)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
```
```
In arch/x86/xen/multicalls.c (ffffffff8103dabb)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:xen_mc_flush
```
```
In arch/x86/xen/spinlock.c (ffffffff8104471a)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/hyperv/ivm.c (ffffffff81047e8c)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_read
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
  - arch/x86/hyperv/ivm.c:hv_ghcb_hypercall
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81048aa7)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In arch/x86/hyperv/hv_spinlock.c (ffffffff81049c35)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In arch/x86/kernel/traps.c (ffffffff8104bf84)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:gp_try_fixup_and_notify
```
```
In arch/x86/kernel/dumpstack.c (ffffffff8105137a)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/dumpstack.c:oops_end
```
```
In arch/x86/kernel/nmi.c (ffffffff8105258d)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/kernel/ldt.c (ffffffff81053753)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:switch_ldt
```
```
In arch/x86/kernel/process.c (ffffffff8105e942)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81060335)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8108fe65)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81094a35)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_update_lepubkeyhash
```
```
In arch/x86/kernel/ftrace.c (ffffffff810aab6b)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810b142e)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In arch/x86/kernel/hpet.c (ffffffff810b4765)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:read_hpet
```
```
In arch/x86/kernel/kvm.c (ffffffff810b6425)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff810b89e5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In arch/x86/kernel/perf_regs.c (ffffffff810ba60e)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/mm/fault.c (ffffffff810c4823)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
```
```
In arch/x86/mm/tlb.c (ffffffff810c9805)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
```
```
In arch/x86/platform/efi/quirks.c (ffffffff810d77d5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_crash_gracefully_on_page_fault
  - arch/x86/platform/efi/quirks.c:efi_crash_gracefully_on_page_fault
  - arch/x86/platform/efi/quirks.c:efi_crash_gracefully_on_page_fault
```
```
In kernel/exit.c (ffffffff810f1f85)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/exit.c:make_task_dead
  - kernel/exit.c:make_task_dead
  - kernel/exit.c:make_task_dead
  - kernel/exit.c:make_task_dead
  - kernel/exit.c:make_task_dead
```
```
In kernel/softirq.c (ffffffff810f3e91)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:__irq_exit_rcu
  - kernel/softirq.c:__irq_exit_rcu
  - kernel/softirq.c:__irq_exit_rcu
  - kernel/softirq.c:__irq_exit_rcu
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/workqueue.c (ffffffff811126d7)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (ffffffff81128d65)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
  - kernel/async.c:current_is_async
  - kernel/async.c:current_is_async
```
```
In kernel/sched/core.c (ffffffff811424f9)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/sched/core.c:dump_cpu_task
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_notrace
  - kernel/sched/core.c:preempt_schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
```
```
In kernel/sched/fair.c (ffffffff8114d465)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
```
```
In kernel/sched/build_policy.c (ffffffff8116404a)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:account_process_tick
  - kernel/sched/build_policy.c:account_process_tick
  - kernel/sched/build_policy.c:account_process_tick
  - kernel/sched/build_policy.c:account_system_time
  - kernel/sched/build_policy.c:account_system_time
  - kernel/sched/build_policy.c:account_system_time
  - kernel/sched/build_policy.c:account_system_time
  - kernel/sched/build_policy.c:account_system_time
```
```
In kernel/locking/qrwlock.c (ffffffff820d6c15)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/process.c (ffffffff811815ba)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
```
In kernel/printk/printk.c (ffffffff811916b2)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:printk_sprint
```
```
In kernel/printk/printk_safe.c (ffffffff8119283f)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:vprintk
```
```
In kernel/irq/irqdesc.c (ffffffff811952f5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_domain_nmi
  - kernel/irq/irqdesc.c:handle_irq_desc
```
```
In kernel/irq/manage.c (ffffffff81199348)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
```
```
In kernel/rcu/tree.c (ffffffff811b69b7)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/livepatch/patch.c (ffffffff811bdd77)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/entry/common.c (ffffffff820bfce2)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_nmi_exit
  - kernel/entry/common.c:irqentry_nmi_enter
```
```
In kernel/module/main.c (ffffffff811caaf5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/module/main.c:module_memfree
  - kernel/module/main.c:module_memfree
  - kernel/module/main.c:module_memfree
```
```
In kernel/time/timer.c (ffffffff811d8686)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/time/timer.c:update_process_times
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:__timer_delete_sync
```
```
In kernel/smp.c (ffffffff811f90ba)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/kexec_core.c (ffffffff811fee19)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
  - kernel/kexec_core.c:kexec_should_crash
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cgroup.c (ffffffff81210d66)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/cgroup/cpuset.c (ffffffff8121eb85)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
```
```
In kernel/stop_machine.c (ffffffff812233b8)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/debug/debug_core.c (ffffffff81239f2e)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_debugger.c (ffffffff812464e7)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
```
In kernel/trace/trace_clock.c (ffffffff81250d90)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ftrace.c (ffffffff81252078)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:arch_ftrace_ops_list_func
```
```
In kernel/trace/ring_buffer.c (ffffffff8125e23a)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
```
In kernel/trace/trace.c (ffffffff8126d3bb)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:tracing_gen_ctx_irq_test
  - kernel/trace/trace.c:tracing_gen_ctx_irq_test
  - kernel/trace/trace.c:tracing_gen_ctx_irq_test
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
```
In kernel/trace/trace_functions.c (ffffffff81279f29)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8127b99a)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_stack.c (ffffffff8127d4b0)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8127ec1c)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_event_perf.c (ffffffff8128c95f)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/bpf_trace.c (ffffffff812a5b00)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
```
In kernel/trace/fprobe.c (ffffffff812ba7c4)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In kernel/irq_work.c (ffffffff812be35c)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/bpf/syscall.c (ffffffff812c7402)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_release
  - kernel/bpf/syscall.c:__bpf_prog_put
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
```
```
In kernel/bpf/helpers.c (ffffffff812f27c5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_timer_cancel
  - kernel/bpf/helpers.c:bpf_timer_start
  - kernel/bpf/helpers.c:bpf_timer_set_callback
  - kernel/bpf/helpers.c:bpf_timer_init
```
```
In kernel/bpf/percpu_freelist.c (ffffffff8130006c)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
```
```
In kernel/bpf/ringbuf.c (ffffffff813047e7)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:__bpf_ringbuf_reserve
```
```
In kernel/bpf/memalloc.c (ffffffff8131bd53)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:alloc_bulk
  - kernel/bpf/memalloc.c:alloc_bulk
  - kernel/bpf/memalloc.c:alloc_bulk
  - kernel/bpf/memalloc.c:alloc_bulk
  - kernel/bpf/memalloc.c:alloc_bulk
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In kernel/events/core.c (ffffffff813494c2)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_task
  - kernel/events/core.c:perf_pending_irq
```
```
In kernel/events/ring_buffer.c (ffffffff8134ab25)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In kernel/events/callchain.c (ffffffff8134c611)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_entry
```
```
In kernel/context_tracking.c (0)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In mm/vmalloc.c (ffffffff813e2345)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - mm/vmalloc.c:vfree
  - mm/vmalloc.c:vfree
  - mm/vmalloc.c:vfree
  - mm/vmalloc.c:vfree
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/page_alloc.c (ffffffff813ec91e)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:warn_alloc
  - mm/page_alloc.c:warn_alloc
  - mm/page_alloc.c:warn_alloc
```
```
In mm/mempolicy.c (ffffffff814191c5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/memcontrol.c (ffffffff8145ac56)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In mm/zsmalloc.c (ffffffff81468b55)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/file_table.c (ffffffff8147c424)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In fs/buffer.c (ffffffff814d3764)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff814dfe94)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff814e2cc9)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/pstore/platform.c (ffffffff816394be)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
  - fs/pstore/platform.c:pstore_dump
```
```
In crypto/skcipher.c (ffffffff8170a2c5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_first
```
```
In block/bio.c (ffffffff8172df18)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - block/bio.c:bio_put_percpu_cache
  - block/bio.c:bio_put_percpu_cache
  - block/bio.c:bio_put_percpu_cache
```
```
In block/blk-mq.c (ffffffff817405a5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In io_uring/io_uring.c (ffffffff817888ff)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_eventfd_signal
  - io_uring/io_uring.c:io_eventfd_signal
  - io_uring/io_uring.c:io_eventfd_signal
```
```
In io_uring/cancel.c (ffffffff8179e33b)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - io_uring/cancel.c:io_try_cancel
  - io_uring/cancel.c:io_try_cancel
  - io_uring/cancel.c:io_try_cancel
```
```
In io_uring/rw.c (ffffffff817a306a)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - io_uring/rw.c:io_rw_should_reissue
  - io_uring/rw.c:io_rw_should_reissue
  - io_uring/rw.c:io_rw_should_reissue
  - io_uring/rw.c:io_rw_should_reissue
  - io_uring/rw.c:io_rw_should_reissue
  - io_uring/rw.c:io_rw_should_reissue
```
```
In lib/dynamic_debug.c (ffffffff8188c98c)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_emit_prefix
  - lib/dynamic_debug.c:__dynamic_emit_prefix
  - lib/dynamic_debug.c:__dynamic_emit_prefix
```
```
In drivers/acpi/utils.c (ffffffff8195600c)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_handle_path
  - drivers/acpi/utils.c:acpi_handle_path
  - drivers/acpi/utils.c:acpi_handle_path
```
```
In drivers/acpi/apei/erst.c (ffffffff819e555b)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_stall
```
```
In drivers/clk/clk.c (ffffffff819f96dc)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
```
```
In drivers/xen/grant-table.c (ffffffff81a1a285)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/time.c (ffffffff81a1c515)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_get_runstate_snapshot_cpu_delta
```
```
In drivers/tty/sysrq.c (ffffffff81a5a1f5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/vt.c (ffffffff81a6e7af)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_write
```
```
In drivers/char/random.c (ffffffff81a944aa)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_timer_randomness
```
```
In drivers/base/power/runtime.c (ffffffff81b01aa2)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/clock_ops.c (ffffffff81b0f025)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_op_lock
```
```
In drivers/block/loop.c (ffffffff81b2c915)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff81c9df7e)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff81d25e2c)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
```
In net/core/sock.c (ffffffff81d9e67f)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff81da7189)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_frag_align
```
```
In net/core/gen_stats.c (ffffffff81db1ed3)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In net/core/dev.c (ffffffff81dbf1c5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_any
```
```
In net/core/filter.c (ffffffff81dfe605)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/page_pool.c (ffffffff81e0f5dc)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_defragged_page
  - net/core/page_pool.c:page_pool_put_defragged_page
```
```
In net/core/bpf_sk_storage.c (ffffffff81e4d145)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
```
```
In net/netlink/af_netlink.c (ffffffff81e6bdd9)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff81eb2028)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81ec9ab6)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/nexthop.c (ffffffff81f13ef4)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv6/route.c (ffffffff81f79dfa)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
```
In lib/radix-tree.c (ffffffff8203997a)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In lib/vsprintf.c (ffffffff8204487a)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
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
In init/main.c (ffffffff81001972)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/x86/events/amd/core.c (ffffffff8100bc03)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_check_overflow
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83690a15)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
```
```
In arch/x86/xen/multicalls.c (ffffffff8103d96b)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:xen_mc_flush
```
```
In arch/x86/xen/spinlock.c (ffffffff8104485a)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/hyperv/ivm.c (ffffffff8104823c)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_read
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
  - arch/x86/hyperv/ivm.c:hv_ghcb_hypercall
```
```
In arch/x86/hyperv/hv_spinlock.c (ffffffff81049e65)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In arch/x86/kernel/traps.c (ffffffff8104c7f5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:gp_try_fixup_and_notify
```
```
In arch/x86/kernel/dumpstack.c (ffffffff810520da)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/dumpstack.c:oops_end
```
```
In arch/x86/kernel/nmi.c (ffffffff8105315d)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/kernel/ldt.c (ffffffff81054733)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:switch_ldt
```
```
In arch/x86/kernel/process.c (ffffffff81060032)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
```
```
In arch/x86/kernel/fpu/core.c (ffffffff810621c6)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81092d7b)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810979d5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_update_lepubkeyhash
```
```
In arch/x86/kernel/ftrace.c (ffffffff810adf20)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810b43dc)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In arch/x86/kernel/hpet.c (ffffffff810b783d)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:read_hpet
```
```
In arch/x86/kernel/kvm.c (ffffffff810b9525)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff810bbbb5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In arch/x86/kernel/perf_regs.c (ffffffff810bd7de)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/mm/fault.c (ffffffff810c8023)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
```
```
In arch/x86/mm/tlb.c (ffffffff810cce85)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
```
```
In arch/x86/platform/efi/quirks.c (ffffffff810e2d65)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_crash_gracefully_on_page_fault
  - arch/x86/platform/efi/quirks.c:efi_crash_gracefully_on_page_fault
  - arch/x86/platform/efi/quirks.c:efi_crash_gracefully_on_page_fault
```
```
In kernel/exit.c (ffffffff810fdf05)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/exit.c:make_task_dead
  - kernel/exit.c:make_task_dead
  - kernel/exit.c:make_task_dead
  - kernel/exit.c:make_task_dead
  - kernel/exit.c:make_task_dead
```
```
In kernel/softirq.c (ffffffff811002c1)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:__irq_exit_rcu
  - kernel/softirq.c:__irq_exit_rcu
  - kernel/softirq.c:__irq_exit_rcu
  - kernel/softirq.c:__irq_exit_rcu
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/workqueue.c (ffffffff8111ecd7)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (ffffffff81136215)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
  - kernel/async.c:current_is_async
  - kernel/async.c:current_is_async
```
```
In kernel/sched/core.c (ffffffff8114e209)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/sched/core.c:dump_cpu_task
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_notrace
  - kernel/sched/core.c:preempt_schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
```
```
In kernel/sched/fair.c (ffffffff8115b4f0)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
```
```
In kernel/sched/build_policy.c (ffffffff8117482a)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:account_process_tick
  - kernel/sched/build_policy.c:account_process_tick
  - kernel/sched/build_policy.c:account_process_tick
  - kernel/sched/build_policy.c:account_system_time
  - kernel/sched/build_policy.c:account_system_time
  - kernel/sched/build_policy.c:account_system_time
  - kernel/sched/build_policy.c:account_system_time
  - kernel/sched/build_policy.c:account_system_time
```
```
In kernel/locking/qrwlock.c (ffffffff82159fa5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/process.c (ffffffff811924ba)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
```
In kernel/printk/printk.c (ffffffff811a2f62)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
```
```
In kernel/printk/printk_safe.c (ffffffff811a40df)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:vprintk
```
```
In kernel/irq/irqdesc.c (ffffffff811a6c85)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_domain_nmi
  - kernel/irq/irqdesc.c:handle_irq_desc
```
```
In kernel/irq/manage.c (ffffffff811ab028)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
```
```
In kernel/rcu/tree.c (ffffffff811c73e7)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/livepatch/patch.c (ffffffff811d0767)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/entry/common.c (ffffffff82141aeb)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_nmi_exit
  - kernel/entry/common.c:irqentry_nmi_enter
```
```
In kernel/module/main.c (ffffffff811dddb5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/module/main.c:module_memfree
  - kernel/module/main.c:module_memfree
  - kernel/module/main.c:module_memfree
```
```
In kernel/time/timer.c (ffffffff811ecab6)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/time/timer.c:update_process_times
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:__timer_delete_sync
```
```
In kernel/smp.c (ffffffff8120dd6a)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/kexec_core.c (ffffffff81214219)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
  - kernel/kexec_core.c:kexec_should_crash
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cgroup.c (ffffffff81226756)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/cgroup/cpuset.c (ffffffff81234c75)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_node_allowed
  - kernel/cgroup/cpuset.c:cpuset_node_allowed
  - kernel/cgroup/cpuset.c:cpuset_node_allowed
```
```
In kernel/stop_machine.c (ffffffff81239be8)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/debug/debug_core.c (ffffffff81250f3e)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_debugger.c (ffffffff8125d557)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
```
In kernel/trace/trace_clock.c (ffffffff81268110)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ftrace.c (ffffffff81269b1b)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:arch_ftrace_ops_list_func
```
```
In kernel/trace/ring_buffer.c (ffffffff8127528a)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
```
In kernel/trace/trace.c (ffffffff81282900)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_gen_ctx_irq_test
  - kernel/trace/trace.c:tracing_gen_ctx_irq_test
  - kernel/trace/trace.c:tracing_gen_ctx_irq_test
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
```
In kernel/trace/trace_functions.c (ffffffff81291967)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812934ba)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_stack.c (ffffffff81299f50)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8129b7ac)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_event_perf.c (ffffffff812a9896)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/bpf_trace.c (ffffffff812c7fb0)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
```
In kernel/trace/fprobe.c (ffffffff812ddd13)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In kernel/irq_work.c (ffffffff812e4f9c)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/bpf/syscall.c (ffffffff812edaaf)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_put
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_kvcalloc
  - kernel/bpf/syscall.c:bpf_map_kvcalloc
  - kernel/bpf/syscall.c:bpf_map_kvcalloc
  - kernel/bpf/syscall.c:bpf_map_kvcalloc
  - kernel/bpf/syscall.c:bpf_map_kvcalloc
  - kernel/bpf/syscall.c:bpf_map_kvcalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
```
```
In kernel/bpf/helpers.c (ffffffff8131f3e5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_timer_cancel
  - kernel/bpf/helpers.c:bpf_timer_start
  - kernel/bpf/helpers.c:bpf_timer_set_callback
  - kernel/bpf/helpers.c:bpf_timer_init
```
```
In kernel/bpf/percpu_freelist.c (ffffffff8132ebcc)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
```
```
In kernel/bpf/ringbuf.c (ffffffff81333187)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:__bpf_ringbuf_reserve
```
```
In kernel/bpf/memalloc.c (ffffffff8134c447)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags
  - kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags
  - kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags
  - kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags
  - kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags
  - kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags
  - kernel/bpf/memalloc.c:alloc_bulk
  - kernel/bpf/memalloc.c:alloc_bulk
  - kernel/bpf/memalloc.c:alloc_bulk
  - kernel/bpf/memalloc.c:alloc_bulk
  - kernel/bpf/memalloc.c:alloc_bulk
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In kernel/events/core.c (ffffffff8137a4d2)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_task
  - kernel/events/core.c:perf_pending_irq
```
```
In kernel/events/ring_buffer.c (ffffffff8137bb65)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In kernel/events/callchain.c (ffffffff8137d661)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_entry
```
```
In kernel/context_tracking.c (0)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In mm/vmalloc.c (ffffffff81416f45)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - mm/vmalloc.c:vfree
  - mm/vmalloc.c:vfree
  - mm/vmalloc.c:vfree
  - mm/vmalloc.c:vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/page_alloc.c (ffffffff81421890)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:warn_alloc
  - mm/page_alloc.c:warn_alloc
  - mm/page_alloc.c:warn_alloc
```
```
In mm/mempolicy.c (ffffffff8144c6a5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/memcontrol.c (ffffffff814908b6)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In mm/zsmalloc.c (ffffffff8149db58)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/file_table.c (ffffffff814b0fa4)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In fs/buffer.c (ffffffff81509d30)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - fs/buffer.c:folio_alloc_buffers
  - fs/buffer.c:folio_alloc_buffers
  - fs/buffer.c:folio_alloc_buffers
  - fs/buffer.c:folio_alloc_buffers
  - fs/buffer.c:folio_alloc_buffers
  - fs/buffer.c:folio_alloc_buffers
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff8151671e)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81519577)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/pstore/platform.c (ffffffff816719a2)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
  - fs/pstore/platform.c:pstore_dump
```
```
In crypto/skcipher.c (ffffffff81743b15)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_first
```
```
In block/bio.c (ffffffff8176a158)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - block/bio.c:bio_put_percpu_cache
  - block/bio.c:bio_put_percpu_cache
  - block/bio.c:bio_put_percpu_cache
```
```
In block/blk-mq.c (ffffffff8177e06d)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_run_hw_queue
```
```
In io_uring/io_uring.c (ffffffff817c8fdf)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_eventfd_signal
  - io_uring/io_uring.c:io_eventfd_signal
  - io_uring/io_uring.c:io_eventfd_signal
```
```
In io_uring/cancel.c (ffffffff817df52b)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - io_uring/cancel.c:io_try_cancel
  - io_uring/cancel.c:io_try_cancel
  - io_uring/cancel.c:io_try_cancel
```
```
In io_uring/rw.c (ffffffff817e401d)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - io_uring/rw.c:io_rw_should_reissue
  - io_uring/rw.c:io_rw_should_reissue
  - io_uring/rw.c:io_rw_should_reissue
  - io_uring/rw.c:io_rw_should_reissue
  - io_uring/rw.c:io_rw_should_reissue
  - io_uring/rw.c:io_rw_should_reissue
```
```
In io_uring/io-wq.c (ffffffff817e7a46)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_worker_stopped
  - io_uring/io-wq.c:io_wq_worker_stopped
  - io_uring/io-wq.c:io_wq_worker_stopped
```
```
In lib/dynamic_debug.c (ffffffff818cedec)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_emit_prefix
  - lib/dynamic_debug.c:__dynamic_emit_prefix
  - lib/dynamic_debug.c:__dynamic_emit_prefix
```
```
In drivers/acpi/utils.c (ffffffff8199c40c)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_handle_path
  - drivers/acpi/utils.c:acpi_handle_path
  - drivers/acpi/utils.c:acpi_handle_path
```
```
In drivers/acpi/apei/erst.c (ffffffff81a2db7b)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_stall
```
```
In drivers/xen/grant-table.c (ffffffff81a63665)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/time.c (ffffffff81a656b5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_get_runstate_snapshot_cpu_delta
```
```
In drivers/tty/sysrq.c (ffffffff81aa4825)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/vt.c (ffffffff81ab8eef)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_write
```
```
In drivers/char/random.c (ffffffff81adfcca)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_timer_randomness
```
```
In drivers/base/power/clock_ops.c (ffffffff81b5d0d5)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_op_lock
```
```
In drivers/block/loop.c (ffffffff81b7cb3c)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff81d052ee)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff81d8f05c)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
```
In net/core/sock.c (ffffffff81e0ce8f)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff81e19239)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_frag_align
```
```
In net/core/gen_stats.c (ffffffff81e224a3)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In net/core/dev.c (ffffffff81e2ee95)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/core/dev.c:dev_kfree_skb_any_reason
```
```
In net/core/filter.c (ffffffff81e6f7c1)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/page_pool.c (ffffffff81e82db0)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_defragged_page
  - net/core/page_pool.c:page_pool_put_defragged_page
```
```
In net/core/bpf_sk_storage.c (ffffffff81ea8865)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
```
```
In net/netlink/af_netlink.c (ffffffff81ec7e39)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff81f106d8)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81f28606)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/nexthop.c (ffffffff81f73bc4)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv6/route.c (ffffffff81fda00a)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
```
In lib/radix-tree.c (ffffffff820b7c9a)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
```
```
In lib/vsprintf.c (ffffffff820c2e5a)
Location: arch/x86/include/asm/preempt.h:25
Inline: True
Inline callers:
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
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
In init/main.c (ffffffff81001982)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/x86/events/amd/core.c (ffffffff810113e3)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_check_overflow
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8103e005)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
  - arch/x86/xen/enlighten_pv.c:xen_end_context_switch
  - arch/x86/xen/enlighten_pv.c:xen_start_context_switch
  - arch/x86/xen/enlighten_pv.c:xen_mc_batch
```
```
In arch/x86/xen/mmu_pv.c (ffffffff838c04e5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
```
```
In arch/x86/xen/multicalls.c (ffffffff81043e2b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:xen_mc_flush
```
```
In arch/x86/xen/spinlock.c (ffffffff8104ad8a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/hyperv/ivm.c (ffffffff8104ec1c)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_read
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
  - arch/x86/hyperv/ivm.c:hv_ghcb_hypercall
```
```
In arch/x86/hyperv/hv_spinlock.c (ffffffff810510c5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In arch/x86/kernel/traps.c (ffffffff81053a75)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:gp_try_fixup_and_notify
```
```
In arch/x86/kernel/dumpstack.c (ffffffff810592fa)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
```
In arch/x86/kernel/nmi.c (ffffffff8105a37d)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/kernel/ldt.c (ffffffff8105b973)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:switch_ldt
```
```
In arch/x86/kernel/process.c (ffffffff810670fa)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81069e45)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_lock_and_load
  - arch/x86/kernel/fpu/core.c:fpregs_lock_and_load
  - arch/x86/kernel/fpu/core.c:fpregs_lock_and_load
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109a1bb)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109ef45)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_update_lepubkeyhash
```
```
In arch/x86/kernel/ftrace.c (ffffffff810b4aa0)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810bb83c)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In arch/x86/kernel/hpet.c (ffffffff810bec7d)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:read_hpet
```
```
In arch/x86/kernel/kvm.c (ffffffff810c0945)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In arch/x86/kernel/perf_regs.c (ffffffff810c495e)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/mm/fault.c (ffffffff810d04f7)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
```
```
In arch/x86/mm/tlb.c (ffffffff810d5555)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
```
```
In arch/x86/platform/efi/quirks.c (ffffffff810eb5e5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_crash_gracefully_on_page_fault
```
```
In kernel/exit.c (ffffffff81106bb5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/exit.c:make_task_dead
  - kernel/exit.c:make_task_dead
  - kernel/exit.c:make_task_dead
```
```
In kernel/softirq.c (ffffffff811099e1)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:__irq_exit_rcu
  - kernel/softirq.c:__irq_exit_rcu
  - kernel/softirq.c:irq_enter_rcu
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/workqueue.c (ffffffff811280f7)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:delayed_work_timer_fn
```
```
In kernel/async.c (ffffffff811413c5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
```
```
In kernel/sched/core.c (ffffffff8115a049)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/sched/core.c:dump_cpu_task
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_notrace
  - kernel/sched/core.c:preempt_schedule
  - kernel/sched/core.c:__schedule_bug
```
```
In kernel/sched/fair.c (ffffffff81166efb)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_sibling
```
```
In kernel/sched/build_policy.c (ffffffff8118277f)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:vtime_task_switch_generic
  - kernel/sched/build_policy.c:vtime_guest_enter
  - kernel/sched/build_policy.c:vtime_user_enter
  - kernel/sched/build_policy.c:vtime_account_kernel
  - kernel/sched/build_policy.c:account_process_tick
  - kernel/sched/build_policy.c:account_system_time
  - kernel/sched/build_policy.c:account_system_time
  - kernel/sched/build_policy.c:account_system_time
```
```
In kernel/locking/qrwlock.c (ffffffff8223d825)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/process.c (ffffffff811a0eaa)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
```
In kernel/printk/printk.c (ffffffff811b3158)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
```
```
In kernel/printk/printk_safe.c (ffffffff811b372e)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:vprintk
```
```
In kernel/irq/irqdesc.c (ffffffff811b67a5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_domain_nmi
  - kernel/irq/irqdesc.c:handle_irq_desc
```
```
In kernel/irq/manage.c (ffffffff811bac68)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_irq
```
```
In kernel/rcu/tree.c (ffffffff811d7907)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:__rcu_irq_enter_check_tick
```
```
In kernel/livepatch/patch.c (ffffffff811e53b7)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/entry/common.c (ffffffff82223a1b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_nmi_exit
  - kernel/entry/common.c:irqentry_nmi_enter
```
```
In kernel/module/main.c (ffffffff811f3ab5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/module/main.c:module_memfree
```
```
In kernel/time/timer.c (ffffffff81202c16)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/time/timer.c:update_process_times
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:__timer_delete_sync
```
```
In kernel/time/tick-sched.c (ffffffff8121c657)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_dep_set_cpu
```
```
In kernel/smp.c (ffffffff812254fa)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/kexec_core.c (ffffffff8122c169)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cgroup.c (ffffffff8123e3e6)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/cgroup/cpuset.c (ffffffff8124e895)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_node_allowed
```
```
In kernel/stop_machine.c (ffffffff812538b8)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/debug/debug_core.c (ffffffff8126ad8e)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_debugger.c (ffffffff81277497)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
```
In kernel/trace/trace_clock.c (ffffffff81282380)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ftrace.c (ffffffff81283c8b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:arch_ftrace_ops_list_func
```
```
In kernel/trace/ring_buffer.c (ffffffff8128f65a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
```
In kernel/trace/trace.c (ffffffff8129d9f0)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_gen_ctx_irq_test
  - kernel/trace/trace.c:tracing_gen_ctx_irq_test
  - kernel/trace/trace.c:tracing_gen_ctx_irq_test
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
```
In kernel/trace/trace_functions.c (ffffffff812acf77)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812ae49a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_stack.c (ffffffff812b55d0)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/trace/trace_functions_graph.c (ffffffff812b6e5c)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_event_perf.c (ffffffff812c55a6)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/bpf_trace.c (ffffffff812e4a40)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
```
In kernel/trace/fprobe.c (ffffffff812fbe03)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In kernel/irq_work.c (ffffffff8130304c)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/bpf/syscall.c (ffffffff8130c65f)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_put
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_kvcalloc
  - kernel/bpf/syscall.c:bpf_map_kvcalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
```
```
In kernel/bpf/helpers.c (ffffffff81341b05)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_timer_cancel
  - kernel/bpf/helpers.c:bpf_timer_start
  - kernel/bpf/helpers.c:bpf_timer_set_callback
  - kernel/bpf/helpers.c:bpf_timer_init
```
```
In kernel/bpf/percpu_freelist.c (ffffffff813530ec)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
```
```
In kernel/bpf/queue_stack_maps.c (ffffffff813571c3)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_push_elem
  - kernel/bpf/queue_stack_maps.c:__stack_map_get
  - kernel/bpf/queue_stack_maps.c:__queue_map_get
```
```
In kernel/bpf/ringbuf.c (ffffffff81357877)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:__bpf_ringbuf_reserve
```
```
In kernel/bpf/memalloc.c (ffffffff813739cd)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags
  - kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags
  - kernel/bpf/memalloc.c:alloc_bulk
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In kernel/events/core.c (ffffffff813a36d2)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_task
  - kernel/events/core.c:perf_pending_irq
```
```
In kernel/events/ring_buffer.c (ffffffff813a4da5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In kernel/events/callchain.c (ffffffff813a68c1)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_entry
```
```
In kernel/context_tracking.c (ffffffff813b0c30)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/context_tracking.c:user_exit_callable
  - kernel/context_tracking.c:user_enter_callable
  - kernel/context_tracking.c:ct_nmi_enter
  - kernel/context_tracking.c:ct_nmi_enter
  - kernel/context_tracking.c:ct_nmi_exit
```
```
In mm/vmalloc.c (ffffffff8144430c)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:delayed_vfree_work
  - mm/vmalloc.c:delayed_vfree_work
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/page_alloc.c (ffffffff8144e6c0)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:warn_alloc
```
```
In mm/mempolicy.c (ffffffff8148601d)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:folio_alloc
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/memcontrol.c (ffffffff814c0226)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In mm/zsmalloc.c (ffffffff814cd828)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/file_table.c (ffffffff814e2766)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In fs/buffer.c (ffffffff8153eb51)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - fs/buffer.c:folio_alloc_buffers
  - fs/buffer.c:folio_alloc_buffers
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff8154ab0e)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8154d957)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/pstore/platform.c (ffffffff816ad872)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
  - fs/pstore/platform.c:pstore_dump
```
```
In crypto/skcipher.c (ffffffff81785e45)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_first
```
```
In block/bio.c (ffffffff817ac408)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - block/bio.c:bio_put_percpu_cache
```
```
In block/blk-mq.c (ffffffff817c06dd)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
```
```
In io_uring/io_uring.c (ffffffff8180dc17)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_eventfd_signal
```
```
In io_uring/cancel.c (ffffffff8182397b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - io_uring/cancel.c:io_try_cancel
```
```
In io_uring/rw.c (ffffffff818280cd)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - io_uring/rw.c:io_rw_should_reissue
  - io_uring/rw.c:io_rw_should_reissue
```
```
In io_uring/io-wq.c (ffffffff8182d856)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_worker_stopped
```
```
In lib/dynamic_debug.c (ffffffff81920bcc)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_emit_prefix
```
```
In drivers/acpi/utils.c (ffffffff819e4a56)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/acpi/utils.c:__acpi_handle_debug
  - drivers/acpi/utils.c:acpi_handle_printk
```
```
In drivers/acpi/apei/erst.c (ffffffff81a78dbb)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_stall
```
```
In drivers/xen/grant-table.c (ffffffff81ab5e85)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/time.c (ffffffff81ab7f15)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_get_runstate_snapshot_cpu_delta
```
```
In drivers/tty/sysrq.c (ffffffff81af7225)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/vt.c (ffffffff81b0c236)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:do_con_write
```
```
In drivers/char/random.c (ffffffff81b330ea)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_timer_randomness
```
```
In drivers/base/power/clock_ops.c (ffffffff81bb0985)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_op_lock
```
```
In drivers/block/loop.c (ffffffff81bd0a74)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
```
```
In drivers/gpu/drm/drm_cache.c (ffffffff81c811b5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_cache.c:drm_memcpy_from_wc
```
```
In drivers/gpu/drm/drm_flip_work.c (ffffffff81cc8850)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_flip_work.c:drm_can_sleep
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff81dbaeae)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81de306e)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81de69cc)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff81e4696c)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
```
In net/core/sock.c (ffffffff81ec981f)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff81ed66c9)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:napi_pp_put_page
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_frag_align
```
```
In net/core/gen_stats.c (ffffffff81ee03e3)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In net/core/dev.c (ffffffff81eedb15)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/dev.c:dev_kfree_skb_any_reason
```
```
In net/core/filter.c (ffffffff81f2ef91)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/page_pool.c (ffffffff81f43ba0)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_unrefed_page
  - net/core/page_pool.c:page_pool_put_unrefed_page
```
```
In net/core/bpf_sk_storage.c (ffffffff81f6b325)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
```
```
In net/netlink/af_netlink.c (ffffffff81f8b249)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff81fd48c4)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81fed096)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/nexthop.c (ffffffff8203a3b4)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv6/route.c (ffffffff820a7a1a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
```
In lib/radix-tree.c (ffffffff821925aa)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In lib/vsprintf.c (ffffffff8219d7da)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
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
In init/main.c (ffff800010084e78)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/arm64/kernel/irq.c (ffff800010086e04)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
```
```
In arch/arm64/kernel/fpsimd.c (ffff80001008869c)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - arch/arm64/kernel/fpsimd.c:__efi_fpsimd_begin
  - arch/arm64/kernel/fpsimd.c:__efi_fpsimd_begin
  - arch/arm64/kernel/fpsimd.c:fpsimd_bind_state_to_cpu
```
```
In arch/arm64/kernel/process.c (ffff800010088eb8)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - arch/arm64/kernel/process.c:arch_cpu_idle
  - arch/arm64/kernel/process.c:arch_cpu_idle
```
```
In arch/arm64/kernel/stacktrace.c (ffff800010093a68)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - arch/arm64/kernel/stacktrace.c:unwind_frame
```
```
In arch/arm64/kernel/traps.c (ffff800010095758)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - arch/arm64/kernel/traps.c:do_serror
  - arch/arm64/kernel/traps.c:do_serror
  - arch/arm64/kernel/traps.c:do_serror
  - arch/arm64/kernel/traps.c:die
```
```
In arch/arm64/kernel/cpufeature.c (ffff8000100994b8)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - arch/arm64/kernel/cpufeature.c:cpu_enable_pan
```
```
In arch/arm64/kernel/smp.c (ffff80001009cc08)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:handle_IPI
  - arch/arm64/kernel/smp.c:handle_IPI
```
```
In arch/arm64/kernel/acpi.c (ffff8000100a9480)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - arch/arm64/kernel/acpi.c:apei_claim_sea
  - arch/arm64/kernel/acpi.c:apei_claim_sea
```
```
In arch/arm64/kernel/sdei.c (ffff800010da7cd8)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - arch/arm64/kernel/sdei.c:__sdei_handler
  - arch/arm64/kernel/sdei.c:__sdei_handler
  - arch/arm64/kernel/sdei.c:__sdei_handler
```
```
In arch/arm64/mm/fault.c (ffff800010da9028)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - arch/arm64/mm/fault.c:do_page_fault
```
```
In kernel/exit.c (ffff8000100fd2b0)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffff8000100ff734)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
  - kernel/softirq.c:_local_bh_enable
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/workqueue.c (ffff80001011c860)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (ffff80001012e430)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
```
```
In kernel/sched/core.c (ffff80001013700c)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/sched/cputime.c (ffff80001013f39c)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_process_tick
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
```
```
In kernel/sched/idle.c (ffff800010da7244)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/locking/rtmutex.c (ffff800010da5a40)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
```
```
In kernel/locking/qrwlock.c (ffff80001016c730)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/process.c (ffff8000101702dc)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
```
In kernel/printk/printk.c (ffff800010174308)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_store
```
```
In kernel/irq/irqdesc.c (ffff800010177cd0)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:handle_domain_nmi
```
```
In kernel/irq/manage.c (ffff80001017a1f4)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_irq
```
```
In kernel/rcu/tree.c (ffff800010190184)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
```
```
In kernel/time/timer.c (ffff8000101a013c)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/time/timer.c:update_process_times
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:del_timer_sync
```
```
In kernel/smp.c (ffff8000101bd290)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/module.c (ffff8000101c3030)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/module.c:module_memfree
```
```
In kernel/kexec_core.c (ffff8000101c8d2c)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cgroup.c (ffff8000101d8cb4)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/cgroup/cpuset.c (ffff8000101e4680)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
```
```
In kernel/stop_machine.c (ffff8000101e8098)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/kprobes.c (ffff8000101f842c)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/debug/debug_core.c (ffff8000101fa1e4)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffff800010200534)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/debug/kdb/kdb_debugger.c (ffff8000102064f0)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
```
In kernel/trace/trace_clock.c (ffff80001020efbc)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ftrace.c (ffff80001020f598)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_no_ops
  - kernel/trace/ftrace.c:ftrace_ops_no_ops
  - kernel/trace/ftrace.c:ftrace_ops_no_ops
```
```
In kernel/trace/ring_buffer.c (ffff8000102183f0)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
```
In kernel/trace/trace.c (ffff800010221df0)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
```
In kernel/trace/trace_functions.c (ffff800010230008)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffff8000102306d8)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_hwlat.c (ffff800010231e08)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/trace/trace_stack.c (ffff8000102324cc)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/trace/trace_functions_graph.c (ffff800010232e38)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffff800010237288)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
```
```
In kernel/trace/trace_events.c (ffff800010238e50)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_syscalls.c (ffff80001023df98)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_event_perf.c (ffff80001023e1d0)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/bpf_trace.c (ffff80001024c760)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
```
In kernel/trace/trace_kprobe.c (ffff800010251504)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/irq_work.c (ffff80001025b230)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/events/core.c (ffff800010294ee4)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_get_recursion_context
  - kernel/events/core.c:perf_swevent_get_recursion_context
  - kernel/events/core.c:perf_swevent_get_recursion_context
```
```
In kernel/events/ring_buffer.c (ffff8000102a1f60)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
```
```
In kernel/events/callchain.c (ffff8000102a384c)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/vmalloc.c (ffff80001030f000)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/page_alloc.c (ffff800010318b60)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:warn_alloc
```
```
In mm/hugetlb.c (ffff800010330a58)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
```
```
In mm/mempolicy.c (ffff800010338430)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/memcontrol.c (ffff80001036b140)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
```
```
In mm/zsmalloc.c (ffff800010375328)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/file_table.c (ffff800010385b10)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
```
```
In fs/pstore/platform.c (ffff80001051b018)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
  - fs/pstore/platform.c:pstore_dump
```
```
In crypto/ablkcipher.c (ffff8000105bca48)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
```
```
In crypto/blkcipher.c (ffff8000105bd75c)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_first
```
```
In crypto/skcipher.c (ffff8000105bf3f0)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_first
```
```
In block/blk-mq.c (ffff8000105ee370)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In lib/dynamic_debug.c (ffff80001065f7ec)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_emit_prefix
```
```
In drivers/irqchip/irq-gic-v3.c (ffff800010081a3c)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_handle_irq
  - drivers/irqchip/irq-gic-v3.c:gic_handle_irq
```
```
In drivers/bus/fsl-mc/mc-sys.c (ffff80001068130c)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - drivers/bus/fsl-mc/mc-sys.c:mc_send_command
```
```
In drivers/pci/search.c (ffff8000106ece48)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/search.c:pci_find_next_bus
```
```
In drivers/rapidio/rio.c (ffff80001073d09c)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_get_asm
```
```
In drivers/video/fbdev/amba-clcd.c (ffff80001075c2d0)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - drivers/video/fbdev/amba-clcd.c:clcdfb_enable
  - drivers/video/fbdev/amba-clcd.c:clcdfb_disable
```
```
In drivers/acpi/utils.c (ffff800010765180)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_handle_path
```
```
In drivers/acpi/ec.c (ffff8000107717a0)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/apei/erst.c (ffff8000107ada50)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_stall
```
```
In drivers/clk/clk.c (ffff8000107c10f8)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
```
```
In drivers/tty/sysrq.c (ffff800010864078)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
```
```
In drivers/tty/vt/vt_ioctl.c (ffff800010865b94)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:reset_vc
```
```
In drivers/tty/vt/vt.c (ffff800010878da4)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_put_char
  - drivers/tty/vt/vt.c:con_put_char
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:con_write
```
```
In drivers/tty/serial/serial_core.c (ffff80001087db94)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
```
In drivers/base/power/runtime.c (ffff8000108fc4e8)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/scsi/sr.c (ffff80001098c1ac)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/net/phy/mdio_bus.c (ffff8000109d7954)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
```
```
In drivers/usb/host/xhci.c (ffff800010a755b0)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffff800010a7b470)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/md/dm-table.c (ffff800010b02b40)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffff800010b1471c)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
```
In drivers/cpuidle/cpuidle.c (ffff800010b26f94)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In drivers/firmware/arm_sdei.c (ffff800010b4cb14)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - drivers/firmware/arm_sdei.c:sdei_event_register
  - drivers/firmware/arm_sdei.c:sdei_event_unregister
```
```
In net/core/sock.c (ffff800010bab148)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffff800010bb54d4)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/scm.c (ffff800010bbe5c4)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffff800010bce12c)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_any
```
```
In net/core/filter.c (ffff800010bf7a4c)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/page_pool.c (ffff800010c0d0b8)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/netlink/af_netlink.c (ffff800010c4f554)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffff800010c76224)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/nexthop.c (ffff800010cc3cf8)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv6/route.c (ffff800010d17e10)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
```
```
In lib/radix-tree.c (ffff800010d8e188)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
```
```
In lib/vsprintf.c (ffff800010d95ca4)
Location: arch/arm64/include/asm/preempt.h:10
Inline: True
Inline callers:
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
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
In init/main.c (c030363c)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/arm/vfp/vfpmodule.c (c0304864)
Location: include/asm-generic/preempt.h:9
Inline: True
```
```
In arch/arm/kernel/traps.c (c0302220)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - arch/arm/kernel/traps.c:handle_fiq_as_nmi
  - arch/arm/kernel/traps.c:handle_fiq_as_nmi
  - arch/arm/kernel/traps.c:die
  - arch/arm/kernel/traps.c:die
```
```
In arch/arm/kernel/smp.c (c0313a00)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - arch/arm/kernel/smp.c:smp_send_stop
  - arch/arm/kernel/smp.c:smp_send_reschedule
  - arch/arm/kernel/smp.c:handle_IPI
  - arch/arm/kernel/smp.c:handle_IPI
  - arch/arm/kernel/smp.c:tick_broadcast
  - arch/arm/kernel/smp.c:arch_irq_work_raise
  - arch/arm/kernel/smp.c:arch_send_call_function_single_ipi
  - arch/arm/kernel/smp.c:arch_send_wakeup_ipi_mask
  - arch/arm/kernel/smp.c:arch_send_call_function_ipi_mask
```
```
In arch/arm/mm/fault.c (c0e9f8b4)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - arch/arm/mm/fault.c:do_page_fault
```
```
In arch/arm/mm/highmem.c (c0321b08)
Location: include/asm-generic/preempt.h:9
Inline: True
```
```
In arch/arm/mach-omap2/pm34xx.c (c033d744)
Location: include/asm-generic/preempt.h:9
Inline: True
```
```
In arch/arm/mach-omap2/powerdomain.c (c0345244)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - arch/arm/mach-omap2/powerdomain.c:pwrdm_set_next_pwrst
  - arch/arm/mach-omap2/powerdomain.c:_pwrdm_state_switch
```
```
In kernel/exit.c (c035a384)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (c035c32c)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
  - kernel/softirq.c:_local_bh_enable
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/workqueue.c (c0371d38)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (c037e954)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
```
```
In kernel/sched/core.c (c0e9a064)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/sched/core.c:_cond_resched
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/sched/cputime.c (c038f388)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_process_tick
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
```
```
In kernel/sched/idle.c (c0e9ee88)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/locking/rtmutex.c (c0e9d89c)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
```
```
In kernel/power/process.c (c03baecc)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
```
In kernel/printk/printk.c (c03c65b0)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_store
```
```
In kernel/irq/irqdesc.c (c03c96a0)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:handle_domain_nmi
```
```
In kernel/irq/manage.c (c03cacc8)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_irq
```
```
In kernel/rcu/tree.c (c03dda60)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
```
```
In kernel/time/timer.c (c03e9dec)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/time/timer.c:update_process_times
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:del_timer_sync
```
```
In kernel/smp.c (c0405400)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/module.c (c040a218)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/module.c:module_memfree
```
```
In kernel/kexec_core.c (c040fb90)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cgroup.c (c041b9f0)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/cgroup/cpuset.c (c0425540)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
```
```
In kernel/stop_machine.c (c04283ac)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/kprobes.c (c0436cb8)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/debug/debug_core.c (c043a270)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (c043e9e8)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/debug/kdb/kdb_debugger.c (c04451dc)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
```
In kernel/trace/trace_clock.c (c044da48)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ftrace.c (c044e978)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/ring_buffer.c (c04582f8)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
```
In kernel/trace/trace.c (c045f890)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
```
In kernel/trace/trace_functions.c (c046b664)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (c046c6fc)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_hwlat.c (c046db98)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/trace/trace_stack.c (c046e168)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/trace/trace_functions_graph.c (c046ea78)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (c0472c00)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
```
```
In kernel/trace/trace_events.c (c0474ab4)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_syscalls.c (c04795d4)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_event_perf.c (c04799ac)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/bpf_trace.c (c0480688)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
```
In kernel/trace/trace_kprobe.c (c0483158)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/irq_work.c (c048e344)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/events/core.c (c04d0ee4)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
  - kernel/events/core.c:perf_pending_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/ring_buffer.c (c04d1af4)
Location: include/asm-generic/preempt.h:9
Inline: True
```
```
In kernel/events/callchain.c (c04d3040)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/vmalloc.c (c052a84c)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/page_alloc.c (c0533464)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:warn_alloc
```
```
In mm/memcontrol.c (c055c880)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
```
```
In mm/zsmalloc.c (c0562314)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/file_table.c (c056e9b8)
Location: include/asm-generic/preempt.h:9
Inline: True
```
```
In fs/pstore/platform.c (c06d5480)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
  - fs/pstore/platform.c:pstore_dump
```
```
In crypto/ablkcipher.c (c076a90c)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
```
```
In crypto/blkcipher.c (c076b5e0)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_first
```
```
In crypto/skcipher.c (c076d128)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_first
```
```
In block/blk-mq.c (c079a0f0)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In lib/genalloc.c (c07eabb0)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In lib/dynamic_debug.c (c08088c8)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_emit_prefix
```
```
In drivers/irqchip/irq-gic-v3.c (0)
Location: include/asm-generic/preempt.h:9
Inline: True
```
```
In drivers/pci/search.c (c08880dc)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/search.c:pci_find_next_bus
```
```
In drivers/rapidio/rio.c (c08c0a20)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_get_asm
```
```
In drivers/video/fbdev/amba-clcd.c (c08df508)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - drivers/video/fbdev/amba-clcd.c:clcdfb_enable
  - drivers/video/fbdev/amba-clcd.c:clcdfb_disable
```
```
In drivers/clk/clk.c (c08eaee8)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
```
```
In drivers/tty/sysrq.c (c0969644)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/vt_ioctl.c (c096ad84)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:reset_vc
```
```
In drivers/tty/vt/vt.c (c097b588)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_put_char
  - drivers/tty/vt/vt.c:con_put_char
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:con_write
```
```
In drivers/tty/serial/serial_core.c (c097f190)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
```
In drivers/base/power/runtime.c (c09e6b24)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/scsi/sr.c (c0a5e534)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/mtd/nand/raw/nand_legacy.c (c0aa3234)
Location: include/asm-generic/preempt.h:9
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (c0abf040)
Location: include/asm-generic/preempt.h:9
Inline: True
```
```
In drivers/usb/host/xhci.c (c0b49048)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (c0b4ec88)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/md/dm-table.c (c0be1e44)
Location: include/asm-generic/preempt.h:9
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (c0c01e88)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In net/core/sock.c (c0cc9bf0)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (c0cd2580)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/scm.c (c0cda0fc)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (c0ce46b4)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_any
```
```
In net/core/filter.c (c0d11274)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/page_pool.c (c0d24f44)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/netlink/af_netlink.c (c0d5f6b0)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (c0d84964)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/nexthop.c (c0dcf1d4)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv6/route.c (c0e1d9d0)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
```
```
In lib/radix-tree.c (c0e889c4)
Location: include/asm-generic/preempt.h:9
Inline: True
```
```
In lib/vsprintf.c (c0e92ebc)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
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
In init/main.c (c00000000001011c)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/powerpc/kernel/time.c (c00000000002bbfc)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - arch/powerpc/kernel/time.c:arch_irq_work_raise
```
```
In arch/powerpc/kernel/traps.c (c00000000002e468)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - arch/powerpc/kernel/traps.c:machine_check_exception
  - arch/powerpc/kernel/traps.c:machine_check_exception
  - arch/powerpc/kernel/traps.c:machine_check_exception
  - arch/powerpc/kernel/traps.c:machine_check_exception
  - arch/powerpc/kernel/traps.c:system_reset_exception
  - arch/powerpc/kernel/traps.c:system_reset_exception
  - arch/powerpc/kernel/traps.c:system_reset_exception
  - arch/powerpc/kernel/traps.c:die_will_crash
```
```
In arch/powerpc/kernel/watchdog.c (c000000000037ac0)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - arch/powerpc/kernel/watchdog.c:soft_nmi_interrupt
  - arch/powerpc/kernel/watchdog.c:soft_nmi_interrupt
```
```
In arch/powerpc/kernel/rtas-rtc.c (c00000000003fab0)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - arch/powerpc/kernel/rtas-rtc.c:rtas_set_rtc_time
  - arch/powerpc/kernel/rtas-rtc.c:rtas_get_rtc_time
```
```
In arch/powerpc/mm/fault.c (c000000000086ea0)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - arch/powerpc/mm/fault.c:__do_page_fault
  - arch/powerpc/mm/fault.c:__do_page_fault
```
```
In arch/powerpc/lib/vmx-helper.c (c0000000000b41f0)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - arch/powerpc/lib/vmx-helper.c:enter_vmx_ops
  - arch/powerpc/lib/vmx-helper.c:enter_vmx_usercopy
```
```
In arch/powerpc/platforms/powernv/opal-nvram.c (c0000000000c8de0)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-nvram.c:opal_nvram_write
  - arch/powerpc/platforms/powernv/opal-nvram.c:opal_nvram_write
```
```
In arch/powerpc/platforms/powernv/opal-irqchip.c (c0000000000cd1d4)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-irqchip.c:opal_event_shutdown
```
```
In arch/powerpc/perf/core-book3s.c (c000000000129318)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - arch/powerpc/perf/core-book3s.c:perf_event_interrupt
  - arch/powerpc/perf/core-book3s.c:perf_event_interrupt
```
```
In kernel/exit.c (c0000000001440c8)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (c000000000146ae8)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
  - kernel/softirq.c:_local_bh_enable
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/workqueue.c (c000000000166924)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (c000000000177a60)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
```
```
In kernel/sched/core.c (c000000000ee32fc)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/sched/core.c:_cond_resched
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/sched/cputime.c (c00000000018e450)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_process_tick
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
```
```
In kernel/sched/idle.c (c000000000ee9af4)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/locking/rtmutex.c (c000000000ee80cc)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
```
```
In kernel/power/process.c (c0000000001c844c)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
```
In kernel/printk/printk.c (c0000000001cd0fc)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_store
```
```
In kernel/irq/manage.c (c0000000001d3874)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_irq
```
```
In kernel/rcu/tree.c (c0000000001eb114)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
```
```
In kernel/time/timer.c (c0000000002010cc)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/time/timer.c:update_process_times
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:del_timer_sync
```
```
In kernel/smp.c (c0000000002235ac)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/module.c (c0000000002295dc)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/module.c:module_memfree
```
```
In kernel/kexec_core.c (c000000000231478)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cgroup.c (c000000000246078)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/cgroup/cpuset.c (c000000000254e08)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
```
```
In kernel/stop_machine.c (c000000000258cc4)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/kprobes.c (c00000000026ccdc)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/debug/debug_core.c (c000000000271b70)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (c000000000277f50)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/debug/kdb/kdb_debugger.c (c000000000282374)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
```
In kernel/trace/trace_clock.c (c00000000028d5a0)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ftrace.c (c00000000028e428)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/ring_buffer.c (c00000000029b260)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
```
In kernel/trace/trace.c (c0000000002a7288)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
```
In kernel/trace/trace_functions.c (c0000000002b949c)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (c0000000002bada4)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_hwlat.c (c0000000002bc5f0)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/trace/trace_stack.c (c0000000002bcd90)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/trace/trace_functions_graph.c (c0000000002bdbbc)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (c0000000002c2f4c)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
```
```
In kernel/trace/trace_events.c (c0000000002c5500)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_syscalls.c (c0000000002cd8c8)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_event_perf.c (c0000000002cdf04)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/bpf_trace.c (c0000000002e8888)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
```
In kernel/trace/trace_kprobe.c (c0000000002eea14)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/irq_work.c (c0000000002feed0)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/events/core.c (c000000000352ad8)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
  - kernel/events/core.c:perf_pending_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/ring_buffer.c (c000000000353e60)
Location: include/asm-generic/preempt.h:9
Inline: True
```
```
In kernel/events/callchain.c (c000000000355c80)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/vmalloc.c (c0000000003e0140)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - mm/vmalloc.c:vunmap
  - mm/vmalloc.c:vfree
  - mm/vmalloc.c:vfree
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/page_alloc.c (c0000000003eb520)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:warn_alloc
```
```
In mm/hugetlb.c (c000000000409870)
Location: include/asm-generic/preempt.h:9
Inline: True
```
```
In mm/mempolicy.c (c000000000411968)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/memcontrol.c (c00000000045a9a8)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
```
```
In mm/zsmalloc.c (c000000000466c2c)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/file_table.c (c00000000047bcec)
Location: include/asm-generic/preempt.h:9
Inline: True
```
```
In fs/pstore/platform.c (c000000000664fa4)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
  - fs/pstore/platform.c:pstore_dump
```
```
In crypto/ablkcipher.c (c000000000743874)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
```
```
In crypto/blkcipher.c (c000000000744b20)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_first
```
```
In crypto/skcipher.c (c0000000007470b0)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_first
```
```
In block/blk-mq.c (c000000000783a84)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In lib/dynamic_debug.c (c0000000008124cc)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_emit_prefix
```
```
In drivers/pci/search.c (c000000000868d60)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/search.c:pci_find_next_bus
```
```
In drivers/rapidio/rio.c (c000000000893d2c)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_get_asm
```
```
In drivers/tty/sysrq.c (c00000000090293c)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/vt_ioctl.c (c0000000009049bc)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:reset_vc
```
```
In drivers/tty/vt/vt.c (c00000000091b624)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_put_char
  - drivers/tty/vt/vt.c:con_put_char
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:con_write
```
```
In drivers/tty/serial/serial_core.c (c000000000924448)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
```
In drivers/base/power/runtime.c (c000000000998de4)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/scsi/sr.c (c000000000a4ce44)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/net/phy/mdio_bus.c (c000000000a993d4)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_write
  - drivers/net/phy/mdio_bus.c:mdiobus_write_nested
  - drivers/net/phy/mdio_bus.c:mdiobus_read
  - drivers/net/phy/mdio_bus.c:mdiobus_read_nested
```
```
In drivers/usb/host/xhci.c (c000000000b4b8b0)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (c000000000b5310c)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/md/dm-table.c (c000000000bf17b4)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_event
```
```
In drivers/cpuidle/cpuidle.c (c000000000c1e134)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In net/core/sock.c (c000000000c81940)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (c000000000c8c60c)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/scm.c (c000000000c979b0)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (c000000000ca4e40)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_any
```
```
In net/core/filter.c (c000000000cdd9b0)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/page_pool.c (c000000000cf8018)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/netlink/af_netlink.c (c000000000d4ddc4)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (c000000000d7dd1c)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/nexthop.c (c000000000ddfaa0)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv6/route.c (c000000000e45a6c)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
```
```
In lib/radix-tree.c (c000000000ed0ccc)
Location: include/asm-generic/preempt.h:9
Inline: True
```
```
In lib/vsprintf.c (c000000000edb184)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
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
In init/main.c (ffffffe0000b4316)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/riscv/kernel/traps.c (ffffffe0000b6c84)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - arch/riscv/kernel/traps.c:die
```
```
In arch/riscv/mm/fault.c (ffffffe0000b9bd0)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - arch/riscv/mm/fault.c:do_page_fault
```
```
In kernel/exit.c (ffffffe0000c5b58)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffe0000c6cf2)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
  - kernel/softirq.c:_local_bh_enable
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/workqueue.c (ffffffe0000d6f4a)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (ffffffe0000e29c6)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
```
```
In kernel/sched/core.c (ffffffe0008c566a)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/sched/core.c:_cond_resched
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/sched/cputime.c (ffffffe0000ed9c8)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_process_tick
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
```
```
In kernel/sched/idle.c (ffffffe0008c9294)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/locking/rtmutex.c (ffffffe0008c80dc)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
```
```
In kernel/power/process.c (ffffffe00010de3c)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
```
In kernel/printk/printk.c (ffffffe00010f75c)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_store
```
```
In kernel/irq/manage.c (ffffffe000113c56)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_irq
```
```
In kernel/rcu/tree.c (ffffffe000122bb6)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
```
```
In kernel/time/timer.c (ffffffe00012de42)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/time/timer.c:update_process_times
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:del_timer_sync
```
```
In kernel/smp.c (ffffffe0001408ac)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/module.c (ffffffe000143fea)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/module.c:module_memfree
```
```
In kernel/cgroup/cgroup.c (ffffffe000151c1c)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/cgroup/cpuset.c (ffffffe00015a92c)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
```
```
In kernel/stop_machine.c (ffffffe00015d3a4)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/trace/trace_clock.c (ffffffe00016fb50)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ftrace.c (ffffffe0001702d8)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/ring_buffer.c (ffffffe00017804a)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
```
In kernel/trace/trace.c (ffffffe00017d61c)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
```
In kernel/trace/trace_functions.c (ffffffe000187a12)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffe000189060)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_hwlat.c (ffffffe000189574)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/trace/trace_stack.c (ffffffe000189c1a)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/trace/trace_functions_graph.c (ffffffe00018a3de)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffe00018e132)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
```
```
In kernel/trace/trace_events.c (ffffffe00018fb7c)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_syscalls.c (ffffffe0001939c8)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_event_perf.c (ffffffe0001940e2)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/irq_work.c (ffffffe00019a2a6)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/events/core.c (ffffffe0001cfefa)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
  - kernel/events/core.c:perf_pending_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/ring_buffer.c (ffffffe0001d0c1a)
Location: include/asm-generic/preempt.h:9
Inline: True
```
```
In kernel/events/callchain.c (ffffffe0001d1e58)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/vmalloc.c (ffffffe0002177c8)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
```
```
In mm/page_alloc.c (ffffffe00021e988)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:warn_alloc
```
```
In mm/hugetlb.c (ffffffe00022dc7c)
Location: include/asm-generic/preempt.h:9
Inline: True
```
```
In mm/memcontrol.c (ffffffe0002488ca)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
```
```
In mm/zsmalloc.c (ffffffe00024ce34)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/file_table.c (ffffffe000258790)
Location: include/asm-generic/preempt.h:9
Inline: True
```
```
In fs/pstore/platform.c (ffffffe00038405c)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
  - fs/pstore/platform.c:pstore_dump
```
```
In crypto/ablkcipher.c (ffffffe000402248)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
```
```
In crypto/blkcipher.c (ffffffe000402d8e)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_first
```
```
In crypto/skcipher.c (ffffffe0004045c0)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_first
```
```
In block/blk-mq.c (ffffffe00042d27e)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In lib/genalloc.c (ffffffe000470b88)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In lib/dynamic_debug.c (ffffffe00048c76c)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_emit_prefix
```
```
In drivers/pci/search.c (ffffffe0004c1c66)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/search.c:pci_find_next_bus
```
```
In drivers/rapidio/rio.c (ffffffe0004ecfba)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_get_asm
```
```
In drivers/clk/clk.c (ffffffe00050b586)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
```
```
In drivers/tty/sysrq.c (ffffffe00053a38a)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffe00053b93a)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:reset_vc
```
```
In drivers/tty/vt/vt.c (ffffffe00054975e)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_put_char
  - drivers/tty/vt/vt.c:con_put_char
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:con_write
```
```
In drivers/tty/serial/serial_core.c (ffffffe00054c04a)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
```
In drivers/base/power/runtime.c (ffffffe00058b71e)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/scsi/sr.c (ffffffe0005f0670)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/net/phy/mdio_bus.c (ffffffe000623620)
Location: include/asm-generic/preempt.h:9
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffe00068d664)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffe000692a00)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/md/dm-table.c (ffffffe0006f2298)
Location: include/asm-generic/preempt.h:9
Inline: True
```
```
In net/core/sock.c (ffffffe00073eb34)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffe000745534)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/scm.c (ffffffe00074c532)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffe000754ff6)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_any
```
```
In net/core/filter.c (ffffffe00077944a)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/page_pool.c (ffffffe000789fb4)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/netlink/af_netlink.c (ffffffe0007bb1b2)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffe0007d93ec)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/nexthop.c (ffffffe000818ea0)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv6/route.c (ffffffe00085cda2)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
```
```
In lib/radix-tree.c (ffffffe0008b6dda)
Location: include/asm-generic/preempt.h:9
Inline: True
```
```
In lib/vsprintf.c (ffffffe0008bf7f4)
Location: include/asm-generic/preempt.h:9
Inline: True
Inline callers:
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
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
In init/main.c (ffffffff81002856)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/x86/events/amd/core.c (ffffffff81008fd9)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
  - arch/x86/events/amd/core.c:amd_pmu_disable_all
```
```
In arch/x86/xen/spinlock.c (ffffffff8102d6aa)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/hyperv/hv_spinlock.c (ffffffff8102fa05)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In arch/x86/kernel/dumpstack.c (ffffffff8103573b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
```
In arch/x86/kernel/nmi.c (ffffffff81036386)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/kernel/process.c (ffffffff81a7328f)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103e669)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/hpet.c (ffffffff81075435)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81076b05)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077de5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In arch/x86/mm/fault.c (ffffffff8107f8fb)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/mm/tlb.c (ffffffff81087835)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In kernel/exit.c (ffffffff8109fc23)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff810a177a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
  - kernel/softirq.c:_local_bh_enable
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/workqueue.c (ffffffff810ba158)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (ffffffff810c91e5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
```
```
In kernel/sched/core.c (ffffffff810d0e6a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/sched/cputime.c (ffffffff810d9b4c)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_process_tick
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
```
```
In kernel/sched/idle.c (ffffffff81a73506)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/locking/rtmutex.c (ffffffff81a71e75)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff810ff565)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/process.c (ffffffff81101e88)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
```
In kernel/printk/printk.c (ffffffff8110b47a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_store
```
```
In kernel/irq/manage.c (ffffffff8110fa34)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_irq
```
```
In kernel/rcu/tree.c (ffffffff811213a2)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
```
```
In kernel/time/timer.c (ffffffff8112f66c)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/time/timer.c:update_process_times
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:del_timer_sync
```
```
In kernel/smp.c (ffffffff81147368)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/module.c (ffffffff8114c265)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/module.c:module_memfree
```
```
In kernel/kexec_core.c (ffffffff81151d34)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cgroup.c (ffffffff8115f448)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/cgroup/cpuset.c (ffffffff811696c5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
```
```
In kernel/stop_machine.c (ffffffff8116c2ac)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/kprobes.c (ffffffff81179ca5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/debug/debug_core.c (ffffffff8117ce14)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81180e74)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/debug/kdb/kdb_debugger.c (ffffffff81187507)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
```
In kernel/trace/trace_clock.c (ffffffff8118f019)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ftrace.c (ffffffff8118f784)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/ring_buffer.c (ffffffff81198ba4)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
```
In kernel/trace/trace.c (ffffffff8119c5d9)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
```
In kernel/trace/trace_functions.c (ffffffff811aa258)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811ab0a3)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_hwlat.c (ffffffff811ac149)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/trace/trace_stack.c (ffffffff811ac6eb)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811ad1ab)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811ad5f4)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff811b112d)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
```
```
In kernel/trace/trace_events.c (ffffffff811b2b24)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b6fca)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_event_perf.c (ffffffff811b72b0)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/bpf_trace.c (ffffffff811c6158)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c966f)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/irq_work.c (ffffffff811d3069)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/events/core.c (ffffffff8120ef15)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
  - kernel/events/core.c:perf_pending_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/ring_buffer.c (ffffffff8120fd15)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In kernel/events/callchain.c (ffffffff812110b3)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/vmalloc.c (ffffffff81270d05)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/page_alloc.c (ffffffff812794b9)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:warn_alloc
```
```
In mm/hugetlb.c (ffffffff8128b4c5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In mm/mempolicy.c (ffffffff81290a15)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/memcontrol.c (ffffffff812c081e)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
```
```
In mm/zsmalloc.c (ffffffff812c7d3b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/file_table.c (ffffffff812d7857)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In fs/pstore/platform.c (ffffffff8142d5a2)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
  - fs/pstore/platform.c:pstore_dump
```
```
In crypto/ablkcipher.c (ffffffff814ba903)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
```
```
In crypto/blkcipher.c (ffffffff814bb625)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_first
```
```
In crypto/skcipher.c (ffffffff814bcf75)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_first
```
```
In block/blk-mq.c (ffffffff814e727b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In lib/dynamic_debug.c (ffffffff8154ba96)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_emit_prefix
```
```
In drivers/pci/search.c (ffffffff8157c715)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/search.c:pci_find_next_bus
```
```
In drivers/rapidio/rio.c (ffffffff815a9165)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_get_asm
```
```
In drivers/acpi/utils.c (ffffffff815caf7c)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_handle_path
```
```
In drivers/acpi/ec.c (ffffffff815d69d7)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/clk/clk.c (ffffffff8161367a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
```
```
In drivers/tty/sysrq.c (ffffffff81656595)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81657762)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:reset_vc
```
```
In drivers/tty/vt/vt.c (ffffffff81666c35)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_put_char
  - drivers/tty/vt/vt.c:con_put_char
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:con_write
```
```
In drivers/tty/serial/serial_core.c (ffffffff8166acc3)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
```
In drivers/iommu/intel-pasid.c (ffffffff816b57e7)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_id
```
```
In drivers/base/power/runtime.c (ffffffff816d2891)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/scsi/sr.c (ffffffff81739fe6)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81782ce5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff817ef93b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817f5885)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/md/dm-table.c (ffffffff81851fc5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81872cb6)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In net/core/sock.c (ffffffff818b415a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff818bb085)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/scm.c (ffffffff818c352c)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff818d0405)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_any
```
```
In net/core/filter.c (ffffffff818f5c51)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/page_pool.c (ffffffff81907205)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/netlink/af_netlink.c (ffffffff81940cb1)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff819634f6)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/nexthop.c (ffffffff819aa4c4)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv6/route.c (ffffffff819f3379)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
```
```
In lib/radix-tree.c (ffffffff81a52c92)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In lib/vsprintf.c (ffffffff81a59ddd)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
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
In init/main.c (ffffffff81000d46)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/x86/events/amd/core.c (ffffffff81007d4b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
  - arch/x86/events/amd/core.c:amd_pmu_disable_all
```
```
In arch/x86/hyperv/hv_spinlock.c (ffffffff8101f3d5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81025093)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
```
In arch/x86/kernel/nmi.c (ffffffff81025cd6)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/kernel/process.c (ffffffff81a2f64f)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8102de69)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/hpet.c (ffffffff81065265)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81066415)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff810678f9)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In arch/x86/mm/fault.c (ffffffff8106e96b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/mm/tlb.c (ffffffff810764a4)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In kernel/exit.c (ffffffff8108e653)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff81090154)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
  - kernel/softirq.c:_local_bh_enable
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/workqueue.c (ffffffff810a8a98)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (ffffffff810b7a05)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
```
```
In kernel/sched/core.c (ffffffff810bf069)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/sched/cputime.c (ffffffff810c8445)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/sched/cputime.c:__vtime_account_system
  - kernel/sched/cputime.c:account_process_tick
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
```
```
In kernel/sched/idle.c (ffffffff81a2f890)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/locking/rtmutex.c (ffffffff81a2e245)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff810ef755)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/process.c (ffffffff810f2248)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
```
In kernel/printk/printk.c (ffffffff810fc2d8)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_store
```
```
In kernel/irq/manage.c (ffffffff81100774)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_irq
```
```
In kernel/rcu/tree.c (ffffffff81112b3b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/timer.c (ffffffff811220ec)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/time/timer.c:update_process_times
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:del_timer_sync
```
```
In kernel/time/tick-sched.c (ffffffff8113480e)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_dep_set_cpu
```
```
In kernel/smp.c (ffffffff8113a643)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/module.c (ffffffff8113f515)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/module.c:module_memfree
```
```
In kernel/kexec_core.c (ffffffff81145014)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cgroup.c (ffffffff811526d8)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/cgroup/cpuset.c (ffffffff8115c8c5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
```
```
In kernel/stop_machine.c (ffffffff8115f4ac)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/kprobes.c (ffffffff8116ce45)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/debug/debug_core.c (ffffffff8116ff87)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81173fb4)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/debug/kdb/kdb_debugger.c (ffffffff8117a647)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
```
In kernel/trace/trace_clock.c (ffffffff8118218b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ftrace.c (ffffffff811828c4)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/ring_buffer.c (ffffffff8118b030)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
```
In kernel/trace/trace.c (ffffffff8118f653)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
```
In kernel/trace/trace_functions.c (ffffffff8119d1b9)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8119e3b3)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_hwlat.c (ffffffff8119f033)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/trace/trace_stack.c (ffffffff8119f43b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811a003b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811a048b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff811a40cf)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
```
```
In kernel/trace/trace_events.c (ffffffff811a592a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_syscalls.c (ffffffff811a9db3)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_event_perf.c (ffffffff811aa0a0)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/bpf_trace.c (ffffffff811b8f38)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
```
In kernel/trace/trace_kprobe.c (ffffffff811bc448)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/irq_work.c (ffffffff811c5e29)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/events/core.c (ffffffff81201cc5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
  - kernel/events/core.c:perf_pending_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/ring_buffer.c (ffffffff81202aa5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In kernel/events/callchain.c (ffffffff81203e43)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In kernel/context_tracking.c (ffffffff8120aa5b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/context_tracking.c:context_tracking_user_exit
  - kernel/context_tracking.c:context_tracking_user_enter
```
```
In mm/vmalloc.c (ffffffff81262c75)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/page_alloc.c (ffffffff8126b3a9)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:warn_alloc
```
```
In mm/hugetlb.c (ffffffff8127d2f5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In mm/mempolicy.c (ffffffff81282695)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/memcontrol.c (ffffffff812b18de)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
```
```
In mm/zsmalloc.c (ffffffff812b8d7b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/file_table.c (ffffffff812c84d7)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In fs/pstore/platform.c (ffffffff8141e022)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
  - fs/pstore/platform.c:pstore_dump
```
```
In crypto/ablkcipher.c (ffffffff814ab323)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
```
```
In crypto/blkcipher.c (ffffffff814ac045)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_first
```
```
In crypto/skcipher.c (ffffffff814ad995)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_first
```
```
In block/blk-mq.c (ffffffff814d77eb)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In lib/dynamic_debug.c (ffffffff8153bd76)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_emit_prefix
```
```
In drivers/pci/search.c (ffffffff8156b4e5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/search.c:pci_find_next_bus
```
```
In drivers/rapidio/rio.c (ffffffff81598305)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_get_asm
```
```
In drivers/acpi/utils.c (ffffffff815b3fcc)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_handle_path
```
```
In drivers/acpi/ec.c (ffffffff815c0597)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/apei/erst.c (ffffffff815fe583)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_stall
```
```
In drivers/clk/clk.c (ffffffff81607baa)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
```
```
In drivers/tty/sysrq.c (ffffffff81636925)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81637af2)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:reset_vc
```
```
In drivers/tty/vt/vt.c (ffffffff81646fb5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_put_char
  - drivers/tty/vt/vt.c:con_put_char
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:con_write
```
```
In drivers/tty/serial/serial_core.c (ffffffff81649e33)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
```
In drivers/iommu/intel-pasid.c (ffffffff81693427)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_id
```
```
In drivers/base/power/runtime.c (ffffffff816adb85)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/scsi/sr.c (ffffffff8171bc86)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81762a75)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff817b4a4b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817baa25)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/md/dm-table.c (ffffffff818195d5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8183caa0)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In net/core/sock.c (ffffffff8186e0aa)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff81874fc5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/scm.c (ffffffff8187d46c)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff81886285)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_any
```
```
In net/core/filter.c (ffffffff818afa81)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/page_pool.c (ffffffff818c1015)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/netlink/af_netlink.c (ffffffff818fa7a1)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff8191cfe6)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/nexthop.c (ffffffff81963f84)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv6/route.c (ffffffff819b0139)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
```
```
In lib/radix-tree.c (ffffffff81a0fd92)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In lib/vsprintf.c (ffffffff81a16ebd)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
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
In init/main.c (ffffffff81002856)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/x86/events/amd/core.c (ffffffff81008f99)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
  - arch/x86/events/amd/core.c:amd_pmu_disable_all
```
```
In arch/x86/xen/spinlock.c (ffffffff8102d50a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/hyperv/hv_spinlock.c (ffffffff8102f865)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In arch/x86/kernel/dumpstack.c (ffffffff8103559b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
```
In arch/x86/kernel/nmi.c (ffffffff810361e6)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/kernel/process.c (ffffffff81adf69f)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103e4a9)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/hpet.c (ffffffff810753e5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81076ab5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077d95)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In arch/x86/mm/fault.c (ffffffff8107f8ab)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/mm/tlb.c (ffffffff810877e5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In kernel/exit.c (ffffffff8109fbd3)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff810a172a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
  - kernel/softirq.c:_local_bh_enable
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/workqueue.c (ffffffff810b96b8)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (ffffffff810c8715)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
```
```
In kernel/sched/core.c (ffffffff810cefdc)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/sched/cputime.c (ffffffff810d5e8c)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_process_tick
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
```
```
In kernel/sched/idle.c (ffffffff81adf916)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/locking/rtmutex.c (ffffffff81ade285)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff810fc725)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/process.c (ffffffff810ff218)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
```
In kernel/printk/printk.c (ffffffff8110936a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_store
```
```
In kernel/irq/manage.c (ffffffff8110d924)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_irq
```
```
In kernel/rcu/tree.c (ffffffff8111f292)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
```
```
In kernel/time/timer.c (ffffffff8112d38c)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/time/timer.c:update_process_times
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:del_timer_sync
```
```
In kernel/smp.c (ffffffff81145218)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/module.c (ffffffff8114a115)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/module.c:module_memfree
```
```
In kernel/kexec_core.c (ffffffff8114fbe4)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cgroup.c (ffffffff8115d218)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/cgroup/cpuset.c (ffffffff81167495)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
```
```
In kernel/stop_machine.c (ffffffff8116a07c)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/kprobes.c (ffffffff81177a75)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/debug/debug_core.c (ffffffff8117abe4)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8117ec44)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/debug/kdb/kdb_debugger.c (ffffffff811852d7)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
```
In kernel/trace/trace_clock.c (ffffffff8118cde9)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ftrace.c (ffffffff8118d554)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/ring_buffer.c (ffffffff81196974)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
```
In kernel/trace/trace.c (ffffffff8119a3a9)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
```
In kernel/trace/trace_functions.c (ffffffff811a8028)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a8e73)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_hwlat.c (ffffffff811a9f19)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/trace/trace_stack.c (ffffffff811aa4bb)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811aaf7b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811ab3c4)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff811aeefd)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
```
```
In kernel/trace/trace_events.c (ffffffff811b08f4)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b4d9a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_event_perf.c (ffffffff811b5080)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/bpf_trace.c (ffffffff811c3f28)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c743f)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/irq_work.c (ffffffff811d0e39)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/events/core.c (ffffffff8120ccb5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
  - kernel/events/core.c:perf_pending_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/ring_buffer.c (ffffffff8120dab5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In kernel/events/callchain.c (ffffffff8120ee53)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/vmalloc.c (ffffffff8126eaa5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/page_alloc.c (ffffffff81277259)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:warn_alloc
```
```
In mm/hugetlb.c (ffffffff812892d5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In mm/mempolicy.c (ffffffff8128e825)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/memcontrol.c (ffffffff812be62e)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
```
```
In mm/zsmalloc.c (ffffffff812c5b4b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/file_table.c (ffffffff812d5667)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In fs/pstore/platform.c (ffffffff81429742)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
  - fs/pstore/platform.c:pstore_dump
```
```
In crypto/ablkcipher.c (ffffffff814b6993)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
```
```
In crypto/blkcipher.c (ffffffff814b76b5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_first
```
```
In crypto/skcipher.c (ffffffff814b9005)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_first
```
```
In block/blk-mq.c (ffffffff814e330b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In lib/dynamic_debug.c (ffffffff815477d6)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_emit_prefix
```
```
In drivers/pci/search.c (ffffffff8157c5d5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/search.c:pci_find_next_bus
```
```
In drivers/rapidio/rio.c (ffffffff815a96f5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_get_asm
```
```
In drivers/acpi/utils.c (ffffffff815cbacc)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_handle_path
```
```
In drivers/acpi/ec.c (ffffffff815d8dc7)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/apei/erst.c (ffffffff81635fb3)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_stall
```
```
In drivers/clk/clk.c (ffffffff8164145a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
```
```
In drivers/tty/sysrq.c (ffffffff81684955)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81685b22)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:reset_vc
```
```
In drivers/tty/vt/vt.c (ffffffff81695015)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_put_char
  - drivers/tty/vt/vt.c:con_put_char
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:con_write
```
```
In drivers/tty/serial/serial_core.c (ffffffff816990a3)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
```
In drivers/iommu/intel-pasid.c (ffffffff816e3cb7)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_id
```
```
In drivers/base/power/runtime.c (ffffffff81700e01)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/scsi/sr.c (ffffffff8177a776)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/net/phy/mdio_bus.c (ffffffff817b3095)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff8182c40b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81832355)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/md/dm-table.c (ffffffff818a15f5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff818b11e5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818c46bb)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In net/core/sock.c (ffffffff8190515a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff8190c085)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/scm.c (ffffffff8191452c)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff81921405)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_any
```
```
In net/core/filter.c (ffffffff81946c81)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/page_pool.c (ffffffff81958235)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/netlink/af_netlink.c (ffffffff81991e41)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff819cdcc6)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/nexthop.c (ffffffff81a14d64)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv6/route.c (ffffffff81a5ddf9)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
```
```
In lib/radix-tree.c (ffffffff81abf082)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In lib/vsprintf.c (ffffffff81ac61cd)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
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
In init/main.c (ffffffff81002856)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/x86/events/amd/core.c (ffffffff810090f9)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
  - arch/x86/events/amd/core.c:amd_pmu_disable_all
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a7250)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
```
```
In arch/x86/xen/multicalls.c (ffffffff810297f7)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:xen_mc_flush
```
```
In arch/x86/xen/spinlock.c (ffffffff8102e2fa)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/hyperv/hv_spinlock.c (ffffffff810306b5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In arch/x86/kernel/traps.c (ffffffff81032e0a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_general_protection
```
```
In arch/x86/kernel/ioport.c (ffffffff81036307)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/dumpstack.c (ffffffff8103657b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
```
In arch/x86/kernel/nmi.c (ffffffff810371e6)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/kernel/process.c (ffffffff81aebe2f)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103f640)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106e985)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:x2apic_get_apic_id
```
```
In arch/x86/kernel/hpet.c (ffffffff81077445)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81078d1e)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In arch/x86/kernel/paravirt.c (ffffffff81079f05)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/fault.c (ffffffff81081967)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/mm/tlb.c (ffffffff8108994a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c625d)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In kernel/exit.c (ffffffff810a7b43)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff810a96ea)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
  - kernel/softirq.c:_local_bh_enable
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/workqueue.c (ffffffff810c26f8)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (ffffffff810d0c55)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
```
```
In kernel/sched/core.c (ffffffff810d83eb)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_notrace
  - kernel/sched/core.c:preempt_schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/sched/cputime.c (ffffffff810e179c)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_process_tick
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
```
```
In kernel/sched/idle.c (ffffffff81aec0e6)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/locking/rtmutex.c (ffffffff81aea735)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff81107955)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/process.c (ffffffff8110a51c)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
```
In kernel/printk/printk.c (ffffffff81115edd)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
```
```
In kernel/irq/manage.c (ffffffff8111b44e)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_irq
```
```
In kernel/rcu/tree.c (ffffffff8112a5c1)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__rcu_read_unlock
  - kernel/rcu/tree.c:__rcu_read_unlock
  - kernel/rcu/tree.c:__rcu_read_unlock
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/time/timer.c (ffffffff81139c9c)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/time/timer.c:update_process_times
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:del_timer_sync
```
```
In kernel/smp.c (ffffffff81151df8)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/module.c (ffffffff81156df5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/module.c:module_memfree
```
```
In kernel/kexec_core.c (ffffffff8115ca44)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cgroup.c (ffffffff8116a370)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/cgroup/cpuset.c (ffffffff81174b05)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
```
```
In kernel/stop_machine.c (ffffffff811777d2)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/kprobes.c (ffffffff81185335)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/debug/debug_core.c (ffffffff81188514)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8118c564)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/debug/kdb/kdb_debugger.c (ffffffff81192c27)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
```
In kernel/trace/trace_clock.c (ffffffff8119a929)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ftrace.c (ffffffff8119b0d2)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/ring_buffer.c (ffffffff811a4582)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
```
In kernel/trace/trace.c (ffffffff811a8049)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
```
In kernel/trace/trace_functions.c (ffffffff811b5dd8)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b6cb3)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_hwlat.c (ffffffff811b7d59)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/trace/trace_stack.c (ffffffff811b8313)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811b8de2)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811b9234)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff811bce01)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
```
```
In kernel/trace/trace_events.c (ffffffff811be984)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_syscalls.c (ffffffff811c2e3a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_event_perf.c (ffffffff811c3120)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/bpf_trace.c (ffffffff811d1808)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
```
In kernel/trace/trace_kprobe.c (ffffffff811d569f)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/irq_work.c (ffffffff811df120)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/events/core.c (ffffffff8121bb3c)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
  - kernel/events/core.c:perf_pending_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/ring_buffer.c (ffffffff8121c965)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In kernel/events/callchain.c (ffffffff8121dd63)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/vmalloc.c (ffffffff8127e4a5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/page_alloc.c (ffffffff81286e46)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:warn_alloc
```
```
In mm/hugetlb.c (ffffffff812990b5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In mm/mempolicy.c (ffffffff8129e725)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/memcontrol.c (ffffffff812cf08e)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
```
```
In mm/zsmalloc.c (ffffffff812d6d2b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/file_table.c (ffffffff812e64b7)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In fs/pstore/platform.c (ffffffff81440602)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
  - fs/pstore/platform.c:pstore_dump
```
```
In crypto/ablkcipher.c (ffffffff814cf423)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
```
```
In crypto/blkcipher.c (ffffffff814d0195)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_first
```
```
In crypto/skcipher.c (ffffffff814d1ac5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_first
```
```
In block/blk-mq.c (ffffffff814fc238)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In lib/scatterlist.c (ffffffff815309b3)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In lib/dynamic_debug.c (ffffffff81561626)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_emit_prefix
```
```
In drivers/pci/search.c (ffffffff81596a85)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/search.c:pci_find_next_bus
```
```
In drivers/rapidio/rio.c (ffffffff815c1a65)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_get_asm
```
```
In drivers/acpi/utils.c (ffffffff815e596c)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_handle_path
```
```
In drivers/acpi/ec.c (ffffffff815f2c87)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/apei/erst.c (ffffffff816502c3)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_stall
```
```
In drivers/clk/clk.c (ffffffff8165b80a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
```
```
In drivers/xen/time.c (ffffffff8167411c)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_get_runstate_snapshot_cpu_delta
```
```
In drivers/tty/sysrq.c (ffffffff8169ef65)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff816a0122)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:reset_vc
```
```
In drivers/tty/vt/vt.c (ffffffff816af5e5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_put_char
  - drivers/tty/vt/vt.c:con_put_char
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:con_write
```
```
In drivers/tty/serial/serial_core.c (ffffffff816b3763)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
```
In drivers/iommu/intel-pasid.c (ffffffff816fe367)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_id
```
```
In drivers/base/power/runtime.c (ffffffff8171ac97)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/scsi/sr.c (ffffffff817945a6)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/net/phy/mdio_bus.c (ffffffff817cd045)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff818463f4)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8184c535)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff818610da)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In drivers/md/dm-table.c (ffffffff818bd835)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff818cd475)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818e0a3b)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In net/core/sock.c (ffffffff8192622a)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff8192d1b5)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/scm.c (ffffffff8193566c)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff81943275)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_any
```
```
In net/core/filter.c (ffffffff81968591)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/page_pool.c (ffffffff8197a345)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/netlink/af_netlink.c (ffffffff819b4931)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff819d7856)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/nexthop.c (ffffffff81a1f774)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv6/route.c (ffffffff81a6a209)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
```
```
In lib/radix-tree.c (ffffffff81acb552)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
```
```
In lib/vsprintf.c (ffffffff81ad26ad)
Location: arch/x86/include/asm/preempt.h:24
Inline: True
Inline callers:
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:restricted_pointer
```
</details>
</li>
</ul>

## Differences
