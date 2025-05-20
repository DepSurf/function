# Function: <code>hlist_empty</code>

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
In arch/x86/entry/common.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In arch/x86/mm/init.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In kernel/pid.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In kernel/time/timer.c (ffffffff810ec742)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - kernel/time/timer.c:migrate_timer_list
  - kernel/time/timer.c:run_timer_softirq
```
```
In kernel/module.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In kernel/kprobes.c (ffffffff8112d0b9)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/trace/ftrace.c (ffffffff81140e67)
Location: include/linux/list.h:609
Inline: True
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In kernel/trace/trace_event_perf.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In kernel/trace/trace_kprobe.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In kernel/trace/power-traces.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In kernel/trace/rpm-traces.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In kernel/user-return-notifier.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In mm/mmu_notifier.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In mm/cma.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In fs/super.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In fs/dcache.c (ffffffff81222c6e)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - fs/dcache.c:d_find_any_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
```
```
In fs/namespace.c (ffffffff8122df86)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
```
```
In fs/seq_file.c (ffffffff812313dd)
Location: include/linux/list.h:609
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In fs/notify/fsnotify.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In fs/notify/mark.c (ffffffff81250664)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In fs/locks.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In fs/ext4/fsync.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In security/selinux/avc.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In block/blk-ioc.c (ffffffff813bed60)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff813d8a12)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_offline
```
```
In lib/swiotlb.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In drivers/iommu/iommu-traces.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In drivers/dma-buf/fence.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In drivers/usb/host/xhci-trace.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In drivers/i2c/i2c-core.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In drivers/thermal/power_allocator.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In drivers/clk/clk.c (ffffffff816e7210)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
```
```
In drivers/ras/ras.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In net/core/flow.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In net/core/net-traces.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81763039)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81784214)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b1fc1)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In net/unix/af_unix.c (ffffffff817be41e)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/list.h:609
Inline: True
```
```
In net/ipv6/raw.c (ffffffff817e69f5)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
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
In arch/x86/entry/common.c (ffffffff810030e0)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004621)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff810278ec)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_set_ldt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_gdt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_load_idt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_single
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_all
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_alloc_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pgd_clear
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pud_clear
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pgd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pmd_clear
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pte_clear
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pte_at
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_domain_pte
  - arch/x86/xen/trace.c:perf_trace_xen_mmu__set_pte
  - arch/x86/xen/trace.c:perf_trace_xen_mc_extend_args
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush_reason
  - arch/x86/xen/trace.c:perf_trace_xen_mc_callback
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry_alloc
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mc__batch
```
```
In arch/x86/kernel/irq.c (ffffffff8102efc1)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:perf_trace_x86_irq_vector
```
```
In arch/x86/kernel/nmi.c (ffffffff81031337)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81038ad9)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104395d)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:perf_trace_mce_record
```
```
In arch/x86/mm/init.c (ffffffff810685ec)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff81069d0e)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff81076641)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:perf_trace_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:perf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:perf_trace_bounds_exception_mpx
  - arch/x86/mm/mpx.c:perf_trace_mpx_bounds_register_exception
```
```
In kernel/fork.c (ffffffff8107f480)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff810831c3)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/exit.c (ffffffff81086520)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/softirq.c (ffffffff81087d11)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff8108fc65)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff8109a439)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/pid.c (ffffffff810a1750)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/sched/core.c (ffffffff810a9131)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_wake_idle_without_ipi
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:perf_trace_sched_process_hang
  - kernel/sched/core.c:perf_trace_sched_pi_setprio
  - kernel/sched/core.c:perf_trace_sched_stat_runtime
  - kernel/sched/core.c:perf_trace_sched_process_exec
  - kernel/sched/core.c:perf_trace_sched_process_fork
  - kernel/sched/core.c:perf_trace_sched_process_wait
  - kernel/sched/core.c:perf_trace_sched_process_template
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:perf_trace_sched_kthread_stop_ret
  - kernel/sched/core.c:perf_trace_sched_kthread_stop
```
```
In kernel/printk/printk.c (ffffffff810db752)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/rcu/update.c (ffffffff810e90f1)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/time/timer.c (ffffffff810f5916)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:perf_trace_tick_stop
  - kernel/time/timer.c:perf_trace_itimer_expire
  - kernel/time/timer.c:perf_trace_itimer_state
  - kernel/time/timer.c:perf_trace_hrtimer_class
  - kernel/time/timer.c:perf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:perf_trace_hrtimer_start
  - kernel/time/timer.c:perf_trace_hrtimer_init
  - kernel/time/timer.c:perf_trace_timer_expire_entry
  - kernel/time/timer.c:perf_trace_timer_start
  - kernel/time/timer.c:perf_trace_timer_class
```
```
In kernel/module.c (ffffffff8110c372)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/auditsc.c (ffffffff8112ff48)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/kprobes.c (ffffffff81135279)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/trace/ftrace.c (ffffffff81148712)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_trace_probe_call
  - kernel/trace/ftrace.c:profile_graph_return
  - kernel/trace/ftrace.c:profile_graph_entry
  - kernel/trace/ftrace.c:profile_graph_entry
```
```
In kernel/trace/trace_syscalls.c (ffffffff8116c5e3)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/trace_event_perf.c (ffffffff8116cc80)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/trace_kprobe.c (ffffffff81174da8)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/power-traces.c (ffffffff81177fa0)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:perf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:perf_trace_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_power_domain
  - kernel/trace/power-traces.c:perf_trace_clock
  - kernel/trace/power-traces.c:perf_trace_wakeup_source
  - kernel/trace/power-traces.c:perf_trace_suspend_resume
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:perf_trace_pstate_sample
  - kernel/trace/power-traces.c:perf_trace_powernv_throttle
  - kernel/trace/power-traces.c:perf_trace_cpu
```
```
In kernel/trace/rpm-traces.c (ffffffff81179b6d)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffffffff8117ca8a)
Location: include/linux/list.h:609
Inline: True
```
```
In kernel/events/core.c (ffffffff8118ba62)
Location: include/linux/list.h:609
Inline: True
```
```
In kernel/user-return-notifier.c (ffffffff8119be48)
Location: include/linux/list.h:609
Inline: True
```
```
In mm/filemap.c (ffffffff8119f593)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff811a46ca)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_oom_score_adj_update
```
```
In mm/swap.c (ffffffff811b17a6)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff811b608d)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_isolate_template
  - mm/vmscan.c:perf_trace_mm_shrink_slab_end
  - mm/vmscan.c:perf_trace_mm_shrink_slab_start
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_end_template
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:perf_trace_mm_vmscan_wakeup_kswapd
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_wake
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_sleep
```
```
In mm/slab_common.c (ffffffff811cbfe4)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:perf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:perf_trace_mm_page
  - mm/slab_common.c:perf_trace_mm_page_alloc
  - mm/slab_common.c:perf_trace_mm_page_free_batched
  - mm/slab_common.c:perf_trace_mm_page_free
  - mm/slab_common.c:perf_trace_kmem_free
  - mm/slab_common.c:perf_trace_kmem_alloc_node
  - mm/slab_common.c:perf_trace_kmem_alloc
```
```
In mm/compaction.c (ffffffff811ce7d7)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - mm/compaction.c:perf_trace_kcompactd_wake_template
  - mm/compaction.c:perf_trace_mm_compaction_kcompactd_sleep
  - mm/compaction.c:perf_trace_mm_compaction_defer_template
  - mm/compaction.c:perf_trace_mm_compaction_suitable_template
  - mm/compaction.c:perf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:perf_trace_mm_compaction_end
  - mm/compaction.c:perf_trace_mm_compaction_begin
  - mm/compaction.c:perf_trace_mm_compaction_migratepages
  - mm/compaction.c:perf_trace_mm_compaction_isolate_template
```
```
In mm/mmu_notifier.c (ffffffff81202c24)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_mm_destroy
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (ffffffff81203a8f)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - mm/ksm.c:remove_rmap_item_from_tree
```
```
In mm/migrate.c (ffffffff8120f9ae)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_numa_migrate_ratelimit
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff81218d33)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff812288d7)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffffffff8122c607)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffffffff8122f087)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/super.c (ffffffff81236dda)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - fs/super.c:do_remount_sb
```
```
In fs/dcache.c (ffffffff8124cf37)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_find_any_alias
  - fs/dcache.c:d_instantiate_no_diralias
  - fs/dcache.c:d_find_alias
```
```
In fs/namespace.c (ffffffff81256781)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:namespace_unlock
```
```
In fs/seq_file.c (ffffffff812596de)
Location: include/linux/list.h:609
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8125e496)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_writeback_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_congest_waited_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_pages_written
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_page
```
```
In fs/notify/fsnotify.c (ffffffff81277a54)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffff81278d96)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_destroy_marks
```
```
In fs/locks.c (ffffffff8128b16c)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/fsync.c (ffffffff812c020f)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/super.c (ffffffff812dd48e)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:perf_trace_ext4_insert_range
  - fs/ext4/super.c:perf_trace_ext4_collapse_range
  - fs/ext4/super.c:perf_trace_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:perf_trace_ext4__es_shrink_enter
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:perf_trace_ext4_es_find_delayed_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_delayed_extent_range_enter
  - fs/ext4/super.c:perf_trace_ext4_es_remove_extent
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_idx
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_show_extent
  - fs/ext4/super.c:perf_trace_ext4_get_reserved_cluster_alloc
  - fs/ext4/super.c:perf_trace_ext4_find_delalloc_range
  - fs/ext4/super.c:perf_trace_ext4_ext_in_cache
  - fs/ext4/super.c:perf_trace_ext4_ext_put_in_cache
  - fs/ext4/super.c:perf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:perf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:perf_trace_ext4__trim
  - fs/ext4/super.c:perf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:perf_trace_ext4_journal_start
  - fs/ext4/super.c:perf_trace_ext4_load_inode
  - fs/ext4/super.c:perf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_exit
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_enter
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:perf_trace_ext4__truncate
  - fs/ext4/super.c:perf_trace_ext4_unlink_exit
  - fs/ext4/super.c:perf_trace_ext4_unlink_enter
  - fs/ext4/super.c:perf_trace_ext4_fallocate_exit
  - fs/ext4/super.c:perf_trace_ext4__fallocate_mode
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_exit
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_enter
  - fs/ext4/super.c:perf_trace_ext4__bitmap_load
  - fs/ext4/super.c:perf_trace_ext4_da_release_space
  - fs/ext4/super.c:perf_trace_ext4_da_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_da_update_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_forget
  - fs/ext4/super.c:perf_trace_ext4__mballoc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_prealloc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_alloc
  - fs/ext4/super.c:perf_trace_ext4_alloc_da_blocks
  - fs/ext4/super.c:perf_trace_ext4_sync_fs
  - fs/ext4/super.c:perf_trace_ext4_sync_file_exit
  - fs/ext4/super.c:perf_trace_ext4_sync_file_enter
  - fs/ext4/super.c:perf_trace_ext4_free_blocks
  - fs/ext4/super.c:perf_trace_ext4_allocate_blocks
  - fs/ext4/super.c:perf_trace_ext4_request_blocks
  - fs/ext4/super.c:perf_trace_ext4_mb_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_mb_release_group_pa
  - fs/ext4/super.c:perf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:perf_trace_ext4__mb_new_pa
  - fs/ext4/super.c:perf_trace_ext4_discard_blocks
  - fs/ext4/super.c:perf_trace_ext4_invalidatepage_op
  - fs/ext4/super.c:perf_trace_ext4__page_op
  - fs/ext4/super.c:perf_trace_ext4_writepages_result
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages_extent
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages
  - fs/ext4/super.c:perf_trace_ext4_writepages
  - fs/ext4/super.c:perf_trace_ext4__write_end
  - fs/ext4/super.c:perf_trace_ext4__write_begin
  - fs/ext4/super.c:perf_trace_ext4_begin_ordered_truncate
  - fs/ext4/super.c:perf_trace_ext4_mark_inode_dirty
  - fs/ext4/super.c:perf_trace_ext4_drop_inode
  - fs/ext4/super.c:perf_trace_ext4_evict_inode
  - fs/ext4/super.c:perf_trace_ext4_allocate_inode
  - fs/ext4/super.c:perf_trace_ext4_request_inode
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
```
```
In fs/jbd2/journal.c (ffffffff8131c74c)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - fs/jbd2/journal.c:perf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:perf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:perf_trace_jbd2_update_log_tail
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_run_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_extend
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_start
  - fs/jbd2/journal.c:perf_trace_jbd2_submit_inode_data
  - fs/jbd2/journal.c:perf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint
```
```
In security/selinux/avc.c (ffffffff81376450)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_get_hash_stats
```
```
In block/blk-core.c (ffffffff813f9a5f)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_unplug
  - block/blk-core.c:perf_trace_block_plug
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_with_error
  - block/blk-core.c:perf_trace_block_buffer
```
```
In block/blk-ioc.c (ffffffff81402bd4)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - block/blk-ioc.c:put_io_context
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff8141e762)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_offline
```
```
In lib/swiotlb.c (ffffffff8145a881)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - lib/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In arch/x86/lib/msr.c (ffffffff81463df7)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff8146db07)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/regulator/core.c (ffffffff81528841)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff815649c7)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - drivers/char/random.c:perf_trace_urandom_read
  - drivers/char/random.c:perf_trace_random_read
  - drivers/char/random.c:perf_trace_random__extract_entropy
  - drivers/char/random.c:perf_trace_random__get_random_bytes
  - drivers/char/random.c:perf_trace_xfer_secondary_pool
  - drivers/char/random.c:perf_trace_add_disk_randomness
  - drivers/char/random.c:perf_trace_add_input_randomness
  - drivers/char/random.c:perf_trace_debit_entropy
  - drivers/char/random.c:perf_trace_push_to_pool
  - drivers/char/random.c:perf_trace_credit_entropy_bits
  - drivers/char/random.c:perf_trace_random__mix_pool_bytes
  - drivers/char/random.c:perf_trace_add_device_randomness
```
```
In drivers/iommu/iommu-traces.c (ffffffff8157fad2)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff815b7be1)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
```
```
In drivers/dma-buf/fence.c (ffffffff815fb9f9)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - drivers/dma-buf/fence.c:perf_trace_fence
  - drivers/dma-buf/fence.c:perf_trace_fence_annotate_wait_on
```
```
In drivers/scsi/scsi.c (ffffffff815fe027)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff81620497)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff81643006)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_master
```
```
In drivers/usb/host/xhci-trace.c (ffffffff816c185f)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_event
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
```
```
In drivers/i2c/i2c-core.c (ffffffff816d9488)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core.c:perf_trace_smbus_write
  - drivers/i2c/i2c-core.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core.c:perf_trace_i2c_write
```
```
In drivers/thermal/thermal_core.c (ffffffff816e43e9)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (ffffffff816ea744)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff8172109b)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/clk/clk.c (ffffffff8174b810)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/ras/ras.c (ffffffff817582e7)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_memory_failure_event
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_mc_event
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
```
```
In net/core/flow.c (ffffffff817a139c)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
```
```
In net/core/net-traces.c (ffffffff817a907f)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_fib6_table_lookup
  - net/core/net-traces.c:perf_trace_fib_validate_source
  - net/core/net-traces.c:perf_trace_fib_table_lookup_nh
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:perf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_rcvqueue_full
  - net/core/net-traces.c:perf_trace_napi_poll
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_template
  - net/core/net-traces.c:perf_trace_net_dev_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:perf_trace_consume_skb
  - net/core/net-traces.c:perf_trace_kfree_skb
```
```
In net/ipv4/inet_hashtables.c (ffffffff817cf6bc)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d013b)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817e9211)
Location: include/linux/list.h:609
Inline: True
```
```
In net/ipv4/raw.c (ffffffff817f17e7)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff817f462c)
Location: include/linux/list.h:609
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff8180ed08)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff81820c10)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff818283ae)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
```
```
In net/unix/af_unix.c (ffffffff8182b3b2)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/addrconf.c (ffffffff8183fe55)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
```
```
In net/ipv6/raw.c (ffffffff81854d81)
Location: include/linux/list.h:609
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
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
In arch/x86/entry/common.c (ffffffff810030de)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8100469f)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff8102803a)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_set_ldt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_gdt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_load_idt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_single
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_all
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_alloc_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pgd_clear
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pud_clear
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pgd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pmd_clear
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pte_clear
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pte_at
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_domain_pte
  - arch/x86/xen/trace.c:perf_trace_xen_mmu__set_pte
  - arch/x86/xen/trace.c:perf_trace_xen_mc_extend_args
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush_reason
  - arch/x86/xen/trace.c:perf_trace_xen_mc_callback
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry_alloc
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mc__batch
```
```
In arch/x86/kernel/irq.c (ffffffff8102ef7f)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:perf_trace_x86_irq_vector
```
```
In arch/x86/kernel/nmi.c (ffffffff81030f85)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff810384be)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810453bb)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:perf_trace_mce_record
```
```
In arch/x86/mm/init.c (ffffffff8106c26a)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff8106d8bc)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff8107a22f)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:perf_trace_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:perf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:perf_trace_bounds_exception_mpx
  - arch/x86/mm/mpx.c:perf_trace_mpx_bounds_register_exception
```
```
In kernel/fork.c (ffffffff81083b2e)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff81089572)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/exit.c (ffffffff8108b490)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/softirq.c (ffffffff8108cc6f)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff81094be3)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff8109f867)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/pid.c (ffffffff810a6810)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/sched/core.c (ffffffff810aefef)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_wake_idle_without_ipi
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:perf_trace_sched_process_hang
  - kernel/sched/core.c:perf_trace_sched_pi_setprio
  - kernel/sched/core.c:perf_trace_sched_stat_runtime
  - kernel/sched/core.c:perf_trace_sched_process_exec
  - kernel/sched/core.c:perf_trace_sched_process_fork
  - kernel/sched/core.c:perf_trace_sched_process_wait
  - kernel/sched/core.c:perf_trace_sched_process_template
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:perf_trace_sched_kthread_stop_ret
  - kernel/sched/core.c:perf_trace_sched_kthread_stop
```
```
In kernel/printk/printk.c (ffffffff810e2220)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/rcu/update.c (ffffffff810effbf)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/time/timer.c (ffffffff810fc956)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:perf_trace_tick_stop
  - kernel/time/timer.c:perf_trace_itimer_expire
  - kernel/time/timer.c:perf_trace_itimer_state
  - kernel/time/timer.c:perf_trace_hrtimer_class
  - kernel/time/timer.c:perf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:perf_trace_hrtimer_start
  - kernel/time/timer.c:perf_trace_hrtimer_init
  - kernel/time/timer.c:perf_trace_timer_expire_entry
  - kernel/time/timer.c:perf_trace_timer_start
  - kernel/time/timer.c:perf_trace_timer_class
```
```
In kernel/time/alarmtimer.c (ffffffff8110407c)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff81113dc0)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup.c (ffffffff81122ef1)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - kernel/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup.c:perf_trace_cgroup
  - kernel/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/auditsc.c (ffffffff81139cb8)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/kprobes.c (ffffffff8113eff9)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/trace/ftrace.c (ffffffff811525c2)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_trace_probe_call
  - kernel/trace/ftrace.c:profile_graph_return
  - kernel/trace/ftrace.c:profile_graph_entry
  - kernel/trace/ftrace.c:profile_graph_entry
```
```
In kernel/trace/trace_syscalls.c (ffffffff81177168)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/trace_event_perf.c (ffffffff81177f50)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/trace_kprobe.c (ffffffff81180828)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/power-traces.c (ffffffff81183a5e)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:perf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:perf_trace_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_power_domain
  - kernel/trace/power-traces.c:perf_trace_clock
  - kernel/trace/power-traces.c:perf_trace_wakeup_source
  - kernel/trace/power-traces.c:perf_trace_suspend_resume
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:perf_trace_pstate_sample
  - kernel/trace/power-traces.c:perf_trace_powernv_throttle
  - kernel/trace/power-traces.c:perf_trace_cpu
```
```
In kernel/trace/rpm-traces.c (ffffffff8118563b)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffffffff8118869a)
Location: include/linux/list.h:625
Inline: True
```
```
In kernel/events/core.c (ffffffff8119af32)
Location: include/linux/list.h:625
Inline: True
```
```
In kernel/user-return-notifier.c (ffffffff811ab828)
Location: include/linux/list.h:625
Inline: True
```
```
In mm/filemap.c (ffffffff811aefae)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff811b4a28)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_oom_score_adj_update
```
```
In mm/swap.c (ffffffff811c1dde)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff811c669b)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_isolate_template
  - mm/vmscan.c:perf_trace_mm_shrink_slab_end
  - mm/vmscan.c:perf_trace_mm_shrink_slab_start
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_end_template
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:perf_trace_mm_vmscan_wakeup_kswapd
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_wake
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_sleep
```
```
In mm/slab_common.c (ffffffff811dc0ef)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:perf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:perf_trace_mm_page
  - mm/slab_common.c:perf_trace_mm_page_alloc
  - mm/slab_common.c:perf_trace_mm_page_free_batched
  - mm/slab_common.c:perf_trace_mm_page_free
  - mm/slab_common.c:perf_trace_kmem_free
  - mm/slab_common.c:perf_trace_kmem_alloc_node
  - mm/slab_common.c:perf_trace_kmem_alloc
```
```
In mm/compaction.c (ffffffff811de905)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - mm/compaction.c:perf_trace_kcompactd_wake_template
  - mm/compaction.c:perf_trace_mm_compaction_kcompactd_sleep
  - mm/compaction.c:perf_trace_mm_compaction_defer_template
  - mm/compaction.c:perf_trace_mm_compaction_suitable_template
  - mm/compaction.c:perf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:perf_trace_mm_compaction_end
  - mm/compaction.c:perf_trace_mm_compaction_begin
  - mm/compaction.c:perf_trace_mm_compaction_migratepages
  - mm/compaction.c:perf_trace_mm_compaction_isolate_template
```
```
In mm/mmu_notifier.c (ffffffff81214a64)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_mm_destroy
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (ffffffff81215aaf)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - mm/ksm.c:remove_rmap_item_from_tree
```
```
In mm/migrate.c (ffffffff81221aec)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_numa_migrate_ratelimit
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff8122b2c1)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff8123ae85)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffffffff8123eb35)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffffffff812415e5)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/super.c (ffffffff81249a8a)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - fs/super.c:do_remount_sb
```
```
In fs/dcache.c (ffffffff8125fff7)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_find_any_alias
  - fs/dcache.c:d_instantiate_no_diralias
  - fs/dcache.c:d_find_alias
```
```
In fs/namespace.c (ffffffff8126a3a6)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:namespace_unlock
```
```
In fs/seq_file.c (ffffffff8126cc88)
Location: include/linux/list.h:625
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812719b4)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_writeback_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_congest_waited_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_pages_written
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_page
```
```
In fs/notify/fsnotify.c (ffffffff8128b734)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffff8128c9c6)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_destroy_marks
```
```
In fs/locks.c (ffffffff8129feca)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffff812f2fdc)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:perf_trace_ext4_insert_range
  - fs/ext4/super.c:perf_trace_ext4_collapse_range
  - fs/ext4/super.c:perf_trace_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:perf_trace_ext4__es_shrink_enter
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:perf_trace_ext4_es_find_delayed_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_delayed_extent_range_enter
  - fs/ext4/super.c:perf_trace_ext4_es_remove_extent
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_idx
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_show_extent
  - fs/ext4/super.c:perf_trace_ext4_get_reserved_cluster_alloc
  - fs/ext4/super.c:perf_trace_ext4_find_delalloc_range
  - fs/ext4/super.c:perf_trace_ext4_ext_in_cache
  - fs/ext4/super.c:perf_trace_ext4_ext_put_in_cache
  - fs/ext4/super.c:perf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:perf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:perf_trace_ext4__trim
  - fs/ext4/super.c:perf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:perf_trace_ext4_journal_start
  - fs/ext4/super.c:perf_trace_ext4_load_inode
  - fs/ext4/super.c:perf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_exit
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_enter
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:perf_trace_ext4__truncate
  - fs/ext4/super.c:perf_trace_ext4_unlink_exit
  - fs/ext4/super.c:perf_trace_ext4_unlink_enter
  - fs/ext4/super.c:perf_trace_ext4_fallocate_exit
  - fs/ext4/super.c:perf_trace_ext4__fallocate_mode
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_exit
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_enter
  - fs/ext4/super.c:perf_trace_ext4__bitmap_load
  - fs/ext4/super.c:perf_trace_ext4_da_release_space
  - fs/ext4/super.c:perf_trace_ext4_da_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_da_update_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_forget
  - fs/ext4/super.c:perf_trace_ext4__mballoc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_prealloc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_alloc
  - fs/ext4/super.c:perf_trace_ext4_alloc_da_blocks
  - fs/ext4/super.c:perf_trace_ext4_sync_fs
  - fs/ext4/super.c:perf_trace_ext4_sync_file_exit
  - fs/ext4/super.c:perf_trace_ext4_sync_file_enter
  - fs/ext4/super.c:perf_trace_ext4_free_blocks
  - fs/ext4/super.c:perf_trace_ext4_allocate_blocks
  - fs/ext4/super.c:perf_trace_ext4_request_blocks
  - fs/ext4/super.c:perf_trace_ext4_mb_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_mb_release_group_pa
  - fs/ext4/super.c:perf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:perf_trace_ext4__mb_new_pa
  - fs/ext4/super.c:perf_trace_ext4_discard_blocks
  - fs/ext4/super.c:perf_trace_ext4_invalidatepage_op
  - fs/ext4/super.c:perf_trace_ext4__page_op
  - fs/ext4/super.c:perf_trace_ext4_writepages_result
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages_extent
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages
  - fs/ext4/super.c:perf_trace_ext4_writepages
  - fs/ext4/super.c:perf_trace_ext4__write_end
  - fs/ext4/super.c:perf_trace_ext4__write_begin
  - fs/ext4/super.c:perf_trace_ext4_begin_ordered_truncate
  - fs/ext4/super.c:perf_trace_ext4_mark_inode_dirty
  - fs/ext4/super.c:perf_trace_ext4_drop_inode
  - fs/ext4/super.c:perf_trace_ext4_evict_inode
  - fs/ext4/super.c:perf_trace_ext4_allocate_inode
  - fs/ext4/super.c:perf_trace_ext4_request_inode
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
```
```
In fs/jbd2/journal.c (ffffffff8133272a)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - fs/jbd2/journal.c:perf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:perf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:perf_trace_jbd2_update_log_tail
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_run_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_extend
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_start
  - fs/jbd2/journal.c:perf_trace_jbd2_submit_inode_data
  - fs/jbd2/journal.c:perf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint
```
```
In security/selinux/avc.c (ffffffff8138cd80)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_get_hash_stats
```
```
In block/blk-core.c (ffffffff81413406)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_unplug
  - block/blk-core.c:perf_trace_block_plug
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_with_error
  - block/blk-core.c:perf_trace_block_buffer
```
```
In block/blk-ioc.c (ffffffff8141c904)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - block/blk-ioc.c:put_io_context
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff81439d22)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_offline
```
```
In block/blk-wbt.c (ffffffff814498b9)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In lib/swiotlb.c (ffffffff8147943f)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - lib/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In arch/x86/lib/msr.c (ffffffff81483095)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff8148f9c5)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (ffffffff81534080)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff81554d9f)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff81591355)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - drivers/char/random.c:perf_trace_urandom_read
  - drivers/char/random.c:perf_trace_random_read
  - drivers/char/random.c:perf_trace_random__extract_entropy
  - drivers/char/random.c:perf_trace_random__get_random_bytes
  - drivers/char/random.c:perf_trace_xfer_secondary_pool
  - drivers/char/random.c:perf_trace_add_disk_randomness
  - drivers/char/random.c:perf_trace_add_input_randomness
  - drivers/char/random.c:perf_trace_debit_entropy
  - drivers/char/random.c:perf_trace_push_to_pool
  - drivers/char/random.c:perf_trace_credit_entropy_bits
  - drivers/char/random.c:perf_trace_random__mix_pool_bytes
  - drivers/char/random.c:perf_trace_add_device_randomness
```
```
In drivers/iommu/iommu-traces.c (ffffffff815ac660)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff815e6f1f)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81629ad7)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence_annotate_wait_on
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8162c0ed)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff8162d625)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff81651005)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff816740d4)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_master
```
```
In drivers/net/phy/mdio_bus.c (ffffffff8167ceeb)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff816ef7cd)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_event
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
```
```
In drivers/i2c/i2c-core.c (ffffffff81709576)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core.c:perf_trace_smbus_write
  - drivers/i2c/i2c-core.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core.c:perf_trace_i2c_write
```
```
In drivers/thermal/thermal_core.c (ffffffff81714f97)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (ffffffff8171b662)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff81753929)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/ras/ras.c (ffffffff817848b5)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_memory_failure_event
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_mc_event
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
```
```
In net/core/flow.c (ffffffff817cfcbf)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
```
```
In net/core/net-traces.c (ffffffff817d7bbd)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_fib6_table_lookup
  - net/core/net-traces.c:perf_trace_fib_validate_source
  - net/core/net-traces.c:perf_trace_fib_table_lookup_nh
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:perf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_rcvqueue_full
  - net/core/net-traces.c:perf_trace_napi_poll
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_template
  - net/core/net-traces.c:perf_trace_net_dev_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:perf_trace_consume_skb
  - net/core/net-traces.c:perf_trace_kfree_skb
```
```
In net/ipv4/inet_hashtables.c (ffffffff817ff4ac)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817fff68)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81819413)
Location: include/linux/list.h:625
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81822564)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff818256fc)
Location: include/linux/list.h:625
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff8184023e)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff81852430)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81859d8e)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
```
```
In net/unix/af_unix.c (ffffffff8185cddf)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/addrconf.c (ffffffff81871ad5)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
```
```
In net/ipv6/raw.c (ffffffff81886af1)
Location: include/linux/list.h:625
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
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
In arch/x86/entry/common.c (ffffffff81002faf)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004539)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff81026614)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_set_ldt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_gdt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_load_idt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_single
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_all
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_alloc_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pgd_clear
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pud_clear
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pmd_clear
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pte_clear
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pte_at
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_domain_pte
  - arch/x86/xen/trace.c:perf_trace_xen_mmu__set_pte
  - arch/x86/xen/trace.c:perf_trace_xen_mc_extend_args
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush_reason
  - arch/x86/xen/trace.c:perf_trace_xen_mc_callback
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry_alloc
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mc__batch
```
```
In arch/x86/kernel/irq.c (ffffffff8102d409)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:perf_trace_x86_irq_vector
```
```
In arch/x86/kernel/nmi.c (ffffffff8102f276)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81036692)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81045509)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:perf_trace_mce_record
```
```
In arch/x86/mm/init.c (ffffffff8106b674)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff8106cfed)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff81078af9)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:perf_trace_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:perf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:perf_trace_bounds_exception_mpx
  - arch/x86/mm/mpx.c:perf_trace_mpx_bounds_register_exception
```
```
In kernel/fork.c (ffffffff810809e4)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff810865d6)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/exit.c (ffffffff81088209)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/softirq.c (ffffffff81089be9)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff81091b41)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff8109d038)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/pid.c (ffffffff810a3780)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/sched/core.c (ffffffff810aaf09)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_wake_idle_without_ipi
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:perf_trace_sched_process_hang
  - kernel/sched/core.c:perf_trace_sched_pi_setprio
  - kernel/sched/core.c:perf_trace_sched_stat_runtime
  - kernel/sched/core.c:perf_trace_sched_process_exec
  - kernel/sched/core.c:perf_trace_sched_process_fork
  - kernel/sched/core.c:perf_trace_sched_process_wait
  - kernel/sched/core.c:perf_trace_sched_process_template
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:perf_trace_sched_kthread_stop_ret
  - kernel/sched/core.c:perf_trace_sched_kthread_stop
```
```
In kernel/printk/printk.c (ffffffff810e14e9)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/rcu/update.c (ffffffff810eff79)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/time/timer.c (ffffffff810feda6)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:perf_trace_tick_stop
  - kernel/time/timer.c:perf_trace_itimer_expire
  - kernel/time/timer.c:perf_trace_itimer_state
  - kernel/time/timer.c:perf_trace_hrtimer_class
  - kernel/time/timer.c:perf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:perf_trace_hrtimer_start
  - kernel/time/timer.c:perf_trace_hrtimer_init
  - kernel/time/timer.c:perf_trace_timer_expire_entry
  - kernel/time/timer.c:perf_trace_timer_start
  - kernel/time/timer.c:perf_trace_timer_class
```
```
In kernel/time/alarmtimer.c (ffffffff811061aa)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff81116dda)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff811230fc)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/kprobes.c (ffffffff81140579)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/trace/ftrace.c (ffffffff8115670d)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:profile_graph_return
  - kernel/trace/ftrace.c:profile_graph_entry
  - kernel/trace/ftrace.c:profile_graph_entry
```
```
In kernel/trace/trace_syscalls.c (ffffffff81179ebe)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/trace_event_perf.c (ffffffff8117ac62)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/trace_kprobe.c (ffffffff81183672)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/power-traces.c (ffffffff81186d07)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:perf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:perf_trace_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_power_domain
  - kernel/trace/power-traces.c:perf_trace_clock
  - kernel/trace/power-traces.c:perf_trace_wakeup_source
  - kernel/trace/power-traces.c:perf_trace_suspend_resume
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:perf_trace_pstate_sample
  - kernel/trace/power-traces.c:perf_trace_powernv_throttle
  - kernel/trace/power-traces.c:perf_trace_cpu
```
```
In kernel/trace/rpm-traces.c (ffffffff81188458)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffffffff8118b237)
Location: include/linux/list.h:638
Inline: True
```
```
In kernel/bpf/core.c (ffffffff8118e37c)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_xdp_exception
  - kernel/bpf/core.c:perf_trace_bpf_map_next_key
  - kernel/bpf/core.c:perf_trace_bpf_map_delete_elem
  - kernel/bpf/core.c:perf_trace_bpf_map_keyval
  - kernel/bpf/core.c:perf_trace_bpf_obj_map
  - kernel/bpf/core.c:perf_trace_bpf_obj_prog
  - kernel/bpf/core.c:perf_trace_bpf_map_create
  - kernel/bpf/core.c:perf_trace_bpf_prog_load
  - kernel/bpf/core.c:perf_trace_bpf_prog_event
```
```
In kernel/events/core.c (ffffffff811a29d3)
Location: include/linux/list.h:638
Inline: True
```
```
In kernel/user-return-notifier.c (ffffffff811b2c94)
Location: include/linux/list.h:638
Inline: True
```
```
In mm/filemap.c (ffffffff811b5d0b)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff811bc44b)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:perf_trace_skip_task_reaping
  - mm/oom_kill.c:perf_trace_finish_task_reaping
  - mm/oom_kill.c:perf_trace_start_task_reaping
  - mm/oom_kill.c:perf_trace_wake_reaper
  - mm/oom_kill.c:perf_trace_mark_victim
  - mm/oom_kill.c:perf_trace_reclaim_retry_zone
  - mm/oom_kill.c:perf_trace_oom_score_adj_update
```
```
In mm/swap.c (ffffffff811ca08f)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff811cebe9)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - mm/vmscan.c:perf_trace_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_isolate
  - mm/vmscan.c:perf_trace_mm_shrink_slab_end
  - mm/vmscan.c:perf_trace_mm_shrink_slab_start
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_end_template
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:perf_trace_mm_vmscan_wakeup_kswapd
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_wake
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_sleep
```
```
In mm/percpu.c (ffffffff811e2649)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff811e5c15)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:perf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:perf_trace_mm_page
  - mm/slab_common.c:perf_trace_mm_page_alloc
  - mm/slab_common.c:perf_trace_mm_page_free_batched
  - mm/slab_common.c:perf_trace_mm_page_free
  - mm/slab_common.c:perf_trace_kmem_free
  - mm/slab_common.c:perf_trace_kmem_alloc_node
  - mm/slab_common.c:perf_trace_kmem_alloc
```
```
In mm/compaction.c (ffffffff811e8656)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - mm/compaction.c:perf_trace_kcompactd_wake_template
  - mm/compaction.c:perf_trace_mm_compaction_kcompactd_sleep
  - mm/compaction.c:perf_trace_mm_compaction_defer_template
  - mm/compaction.c:perf_trace_mm_compaction_suitable_template
  - mm/compaction.c:perf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:perf_trace_mm_compaction_end
  - mm/compaction.c:perf_trace_mm_compaction_begin
  - mm/compaction.c:perf_trace_mm_compaction_migratepages
  - mm/compaction.c:perf_trace_mm_compaction_isolate_template
```
```
In mm/mmu_notifier.c (ffffffff8121fe74)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_mm_destroy
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (ffffffff81222a9b)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
```
```
In mm/migrate.c (ffffffff8122d80e)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_numa_migrate_ratelimit
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff81236e42)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff81246916)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffffffff8124a3f6)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffffffff8124db9e)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/super.c (ffffffff8125535e)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - fs/super.c:do_remount_sb
```
```
In fs/dcache.c (ffffffff8126d927)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_find_any_alias
  - fs/dcache.c:d_instantiate_no_diralias
  - fs/dcache.c:d_find_alias
```
```
In fs/namespace.c (ffffffff81277b75)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:namespace_unlock
```
```
In fs/seq_file.c (ffffffff8127a847)
Location: include/linux/list.h:638
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8127e9fd)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_writeback_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_congest_waited_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_pages_written
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_page
```
```
In fs/notify/mark.c (ffffffff81299c54)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
```
In fs/dax.c (ffffffff812a8d34)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - fs/dax.c:perf_trace_dax_writeback_one
  - fs/dax.c:perf_trace_dax_writeback_range_class
  - fs/dax.c:perf_trace_dax_insert_mapping
  - fs/dax.c:perf_trace_dax_pte_fault_class
  - fs/dax.c:perf_trace_dax_pmd_insert_mapping_class
  - fs/dax.c:perf_trace_dax_pmd_load_hole_class
  - fs/dax.c:perf_trace_dax_pmd_fault_class
```
```
In fs/locks.c (ffffffff812aed1e)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffff81327d80)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:perf_trace_ext4_insert_range
  - fs/ext4/super.c:perf_trace_ext4_collapse_range
  - fs/ext4/super.c:perf_trace_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:perf_trace_ext4__es_shrink_enter
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:perf_trace_ext4_es_find_delayed_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_delayed_extent_range_enter
  - fs/ext4/super.c:perf_trace_ext4_es_remove_extent
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_idx
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_show_extent
  - fs/ext4/super.c:perf_trace_ext4_get_reserved_cluster_alloc
  - fs/ext4/super.c:perf_trace_ext4_find_delalloc_range
  - fs/ext4/super.c:perf_trace_ext4_ext_in_cache
  - fs/ext4/super.c:perf_trace_ext4_ext_put_in_cache
  - fs/ext4/super.c:perf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:perf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:perf_trace_ext4__trim
  - fs/ext4/super.c:perf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:perf_trace_ext4_journal_start
  - fs/ext4/super.c:perf_trace_ext4_load_inode
  - fs/ext4/super.c:perf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_exit
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_enter
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:perf_trace_ext4__truncate
  - fs/ext4/super.c:perf_trace_ext4_unlink_exit
  - fs/ext4/super.c:perf_trace_ext4_unlink_enter
  - fs/ext4/super.c:perf_trace_ext4_fallocate_exit
  - fs/ext4/super.c:perf_trace_ext4__fallocate_mode
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_exit
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_enter
  - fs/ext4/super.c:perf_trace_ext4__bitmap_load
  - fs/ext4/super.c:perf_trace_ext4_da_release_space
  - fs/ext4/super.c:perf_trace_ext4_da_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_da_update_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_forget
  - fs/ext4/super.c:perf_trace_ext4__mballoc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_prealloc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_alloc
  - fs/ext4/super.c:perf_trace_ext4_alloc_da_blocks
  - fs/ext4/super.c:perf_trace_ext4_sync_fs
  - fs/ext4/super.c:perf_trace_ext4_sync_file_exit
  - fs/ext4/super.c:perf_trace_ext4_sync_file_enter
  - fs/ext4/super.c:perf_trace_ext4_free_blocks
  - fs/ext4/super.c:perf_trace_ext4_allocate_blocks
  - fs/ext4/super.c:perf_trace_ext4_request_blocks
  - fs/ext4/super.c:perf_trace_ext4_mb_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_mb_release_group_pa
  - fs/ext4/super.c:perf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:perf_trace_ext4__mb_new_pa
  - fs/ext4/super.c:perf_trace_ext4_discard_blocks
  - fs/ext4/super.c:perf_trace_ext4_invalidatepage_op
  - fs/ext4/super.c:perf_trace_ext4__page_op
  - fs/ext4/super.c:perf_trace_ext4_writepages_result
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages_extent
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages
  - fs/ext4/super.c:perf_trace_ext4_writepages
  - fs/ext4/super.c:perf_trace_ext4__write_end
  - fs/ext4/super.c:perf_trace_ext4__write_begin
  - fs/ext4/super.c:perf_trace_ext4_begin_ordered_truncate
  - fs/ext4/super.c:perf_trace_ext4_mark_inode_dirty
  - fs/ext4/super.c:perf_trace_ext4_drop_inode
  - fs/ext4/super.c:perf_trace_ext4_evict_inode
  - fs/ext4/super.c:perf_trace_ext4_allocate_inode
  - fs/ext4/super.c:perf_trace_ext4_request_inode
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
```
```
In fs/jbd2/journal.c (ffffffff81347644)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - fs/jbd2/journal.c:perf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:perf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:perf_trace_jbd2_update_log_tail
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_run_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_extend
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_start
  - fs/jbd2/journal.c:perf_trace_jbd2_submit_inode_data
  - fs/jbd2/journal.c:perf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint
```
```
In security/selinux/avc.c (ffffffff813a2ab7)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_get_hash_stats
```
```
In block/blk-core.c (ffffffff81420a59)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_unplug
  - block/blk-core.c:perf_trace_block_plug
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_buffer
```
```
In block/blk-ioc.c (ffffffff8142a9d0)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff814475a2)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_offline
```
```
In block/blk-wbt.c (ffffffff81457dd5)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In lib/swiotlb.c (ffffffff81482802)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - lib/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In arch/x86/lib/msr.c (ffffffff8148c7f6)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff81499336)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (ffffffff815479b0)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff8156facd)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff815a52a6)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - drivers/char/random.c:perf_trace_urandom_read
  - drivers/char/random.c:perf_trace_random_read
  - drivers/char/random.c:perf_trace_random__extract_entropy
  - drivers/char/random.c:perf_trace_random__get_random_bytes
  - drivers/char/random.c:perf_trace_xfer_secondary_pool
  - drivers/char/random.c:perf_trace_add_disk_randomness
  - drivers/char/random.c:perf_trace_add_input_randomness
  - drivers/char/random.c:perf_trace_debit_entropy
  - drivers/char/random.c:perf_trace_push_to_pool
  - drivers/char/random.c:perf_trace_credit_entropy_bits
  - drivers/char/random.c:perf_trace_random__mix_pool_bytes
  - drivers/char/random.c:perf_trace_add_device_randomness
```
```
In drivers/iommu/iommu-traces.c (ffffffff815c25e9)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff815fb93d)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8163fa8c)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence_annotate_wait_on
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81641e55)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff816426af)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff816657fe)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff81688851)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81691ee4)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81704ee8)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_slot_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ep_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_trb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8171e77e)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff817220a0)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/thermal/thermal_core.c (ffffffff8172f268)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (ffffffff8173377c)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff8177365c)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/ras/ras.c (ffffffff817a34a6)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_memory_failure_event
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_non_standard_event
  - drivers/ras/ras.c:perf_trace_arm_event
  - drivers/ras/ras.c:perf_trace_mc_event
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
```
```
In net/core/flow.c (ffffffff817ef0bd)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
```
```
In net/core/net-traces.c (ffffffff817f6073)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_fib6_table_lookup
  - net/core/net-traces.c:perf_trace_fib_validate_source
  - net/core/net-traces.c:perf_trace_fib_table_lookup_nh
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:perf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_rcvqueue_full
  - net/core/net-traces.c:perf_trace_napi_poll
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_template
  - net/core/net-traces.c:perf_trace_net_dev_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:perf_trace_consume_skb
  - net/core/net-traces.c:perf_trace_kfree_skb
```
```
In net/ipv4/inet_hashtables.c (ffffffff8181f717)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818210d6)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183a5dd)
Location: include/linux/list.h:638
Inline: True
```
```
In net/ipv4/raw.c (ffffffff818431be)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81847733)
Location: include/linux/list.h:638
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff818617a5)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff818755c3)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff8187db7e)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
```
```
In net/unix/af_unix.c (ffffffff8188156b)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/addrconf.c (ffffffff8189685a)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
```
```
In net/ipv6/raw.c (ffffffff818ad01d)
Location: include/linux/list.h:638
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
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
In arch/x86/entry/common.c (ffffffff81002f3f)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8100471a)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff81026c9f)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_set_ldt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_gdt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_load_idt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_one_user
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_all
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_alloc_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pte_at
  - arch/x86/xen/trace.c:perf_trace_xen_mmu__set_pte
  - arch/x86/xen/trace.c:perf_trace_xen_mc_extend_args
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush_reason
  - arch/x86/xen/trace.c:perf_trace_xen_mc_callback
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry_alloc
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mc__batch
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102adf1)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/irq.c (ffffffff8102ea84)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:perf_trace_vector_free_moved
  - arch/x86/kernel/irq.c:perf_trace_vector_setup
  - arch/x86/kernel/irq.c:perf_trace_vector_teardown
  - arch/x86/kernel/irq.c:perf_trace_vector_activate
  - arch/x86/kernel/irq.c:perf_trace_vector_alloc_managed
  - arch/x86/kernel/irq.c:perf_trace_vector_alloc
  - arch/x86/kernel/irq.c:perf_trace_vector_reserve
  - arch/x86/kernel/irq.c:perf_trace_vector_mod
  - arch/x86/kernel/irq.c:perf_trace_vector_config
  - arch/x86/kernel/irq.c:perf_trace_x86_irq_vector
```
```
In arch/x86/kernel/nmi.c (ffffffff810311d4)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103899a)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81048cea)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:perf_trace_mce_record
```
```
In arch/x86/mm/init.c (ffffffff8106fe6f)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff81071cb4)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff8107edba)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:perf_trace_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:perf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:perf_trace_bounds_exception_mpx
  - arch/x86/mm/mpx.c:perf_trace_mpx_bounds_register_exception
```
```
In kernel/fork.c (ffffffff810871a0)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff8108d247)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/exit.c (ffffffff8108ef7d)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/softirq.c (ffffffff810908da)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff81098904)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810a37da)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/pid.c (ffffffff810a9f70)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/sched/core.c (ffffffff810b1c6a)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_wake_idle_without_ipi
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:perf_trace_sched_process_hang
  - kernel/sched/core.c:perf_trace_sched_pi_setprio
  - kernel/sched/core.c:perf_trace_sched_stat_runtime
  - kernel/sched/core.c:perf_trace_sched_process_exec
  - kernel/sched/core.c:perf_trace_sched_process_fork
  - kernel/sched/core.c:perf_trace_sched_process_wait
  - kernel/sched/core.c:perf_trace_sched_process_template
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:perf_trace_sched_kthread_stop_ret
  - kernel/sched/core.c:perf_trace_sched_kthread_stop
```
```
In kernel/printk/printk.c (ffffffff810e9531)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff810f8bd4)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff810f9baa)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/time/timer.c (ffffffff81109b25)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:perf_trace_tick_stop
  - kernel/time/timer.c:perf_trace_itimer_expire
  - kernel/time/timer.c:perf_trace_itimer_state
  - kernel/time/timer.c:perf_trace_hrtimer_class
  - kernel/time/timer.c:perf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:perf_trace_hrtimer_start
  - kernel/time/timer.c:perf_trace_hrtimer_init
  - kernel/time/timer.c:perf_trace_timer_expire_entry
  - kernel/time/timer.c:perf_trace_timer_start
  - kernel/time/timer.c:perf_trace_timer_class
```
```
In kernel/time/alarmtimer.c (ffffffff8111117f)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff81122315)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff8112ec5d)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/kprobes.c (ffffffff8114d422)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/trace/ftrace.c (ffffffff8116322d)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:profile_graph_return
  - kernel/trace/ftrace.c:profile_graph_entry
  - kernel/trace/ftrace.c:profile_graph_entry
```
```
In kernel/trace/trace_syscalls.c (ffffffff8118762b)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811912e9)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/power-traces.c (ffffffff81194674)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:perf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:perf_trace_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_power_domain
  - kernel/trace/power-traces.c:perf_trace_clock
  - kernel/trace/power-traces.c:perf_trace_wakeup_source
  - kernel/trace/power-traces.c:perf_trace_suspend_resume
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:perf_trace_pstate_sample
  - kernel/trace/power-traces.c:perf_trace_powernv_throttle
  - kernel/trace/power-traces.c:perf_trace_cpu
```
```
In kernel/trace/rpm-traces.c (ffffffff81196026)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffffffff81198cbd)
Location: include/linux/list.h:639
Inline: True
```
```
In kernel/bpf/core.c (ffffffff8119b474)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_exception
  - kernel/bpf/core.c:perf_trace_bpf_map_next_key
  - kernel/bpf/core.c:perf_trace_bpf_map_delete_elem
  - kernel/bpf/core.c:perf_trace_bpf_map_keyval
  - kernel/bpf/core.c:perf_trace_bpf_obj_map
  - kernel/bpf/core.c:perf_trace_bpf_obj_prog
  - kernel/bpf/core.c:perf_trace_bpf_map_create
  - kernel/bpf/core.c:perf_trace_bpf_prog_load
  - kernel/bpf/core.c:perf_trace_bpf_prog_event
```
```
In kernel/events/core.c (ffffffff811b6bb5)
Location: include/linux/list.h:639
Inline: True
```
```
In kernel/user-return-notifier.c (ffffffff811c68e4)
Location: include/linux/list.h:639
Inline: True
```
```
In mm/filemap.c (ffffffff811c9d5f)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff811d0f68)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:perf_trace_skip_task_reaping
  - mm/oom_kill.c:perf_trace_finish_task_reaping
  - mm/oom_kill.c:perf_trace_start_task_reaping
  - mm/oom_kill.c:perf_trace_wake_reaper
  - mm/oom_kill.c:perf_trace_mark_victim
  - mm/oom_kill.c:perf_trace_reclaim_retry_zone
  - mm/oom_kill.c:perf_trace_oom_score_adj_update
```
```
In mm/swap.c (ffffffff811deeba)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff811e3f24)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - mm/vmscan.c:perf_trace_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_isolate
  - mm/vmscan.c:perf_trace_mm_shrink_slab_end
  - mm/vmscan.c:perf_trace_mm_shrink_slab_start
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_end_template
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:perf_trace_mm_vmscan_wakeup_kswapd
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_wake
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_sleep
```
```
In mm/percpu.c (ffffffff811f873a)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff811fbd64)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:perf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:perf_trace_mm_page
  - mm/slab_common.c:perf_trace_mm_page_alloc
  - mm/slab_common.c:perf_trace_mm_page_free_batched
  - mm/slab_common.c:perf_trace_mm_page_free
  - mm/slab_common.c:perf_trace_kmem_free
  - mm/slab_common.c:perf_trace_kmem_alloc_node
  - mm/slab_common.c:perf_trace_kmem_alloc
```
```
In mm/compaction.c (ffffffff811fe8e4)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - mm/compaction.c:perf_trace_kcompactd_wake_template
  - mm/compaction.c:perf_trace_mm_compaction_kcompactd_sleep
  - mm/compaction.c:perf_trace_mm_compaction_defer_template
  - mm/compaction.c:perf_trace_mm_compaction_suitable_template
  - mm/compaction.c:perf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:perf_trace_mm_compaction_end
  - mm/compaction.c:perf_trace_mm_compaction_begin
  - mm/compaction.c:perf_trace_mm_compaction_migratepages
  - mm/compaction.c:perf_trace_mm_compaction_isolate_template
```
```
In mm/mmu_notifier.c (ffffffff8123b094)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_mm_destroy
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (ffffffff8123de88)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
```
```
In mm/migrate.c (ffffffff81249073)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_numa_migrate_ratelimit
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff81256134)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff812669e4)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffffffff8126a554)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffffffff8126fbfe)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/super.c (ffffffff812774ee)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - fs/super.c:do_remount_sb
```
```
In fs/dcache.c (ffffffff812903c7)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_find_any_alias
  - fs/dcache.c:d_instantiate_no_diralias
  - fs/dcache.c:d_find_alias
```
```
In fs/namespace.c (ffffffff8129a5b5)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:namespace_unlock
```
```
In fs/seq_file.c (ffffffff8129d28b)
Location: include/linux/list.h:639
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812a141a)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_writeback_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_congest_waited_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_pages_written
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_page
```
```
In fs/notify/mark.c (ffffffff812bd004)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/dax.c (ffffffff812cc164)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - fs/dax.c:perf_trace_dax_writeback_one
  - fs/dax.c:perf_trace_dax_writeback_range_class
  - fs/dax.c:perf_trace_dax_insert_mapping
  - fs/dax.c:perf_trace_dax_pte_fault_class
  - fs/dax.c:perf_trace_dax_pmd_insert_mapping_class
  - fs/dax.c:perf_trace_dax_pmd_load_hole_class
  - fs/dax.c:perf_trace_dax_pmd_fault_class
```
```
In fs/locks.c (ffffffff812d260f)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffff8134c14f)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:perf_trace_ext4_insert_range
  - fs/ext4/super.c:perf_trace_ext4_collapse_range
  - fs/ext4/super.c:perf_trace_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:perf_trace_ext4__es_shrink_enter
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:perf_trace_ext4_es_find_delayed_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_delayed_extent_range_enter
  - fs/ext4/super.c:perf_trace_ext4_es_remove_extent
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_idx
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_show_extent
  - fs/ext4/super.c:perf_trace_ext4_get_reserved_cluster_alloc
  - fs/ext4/super.c:perf_trace_ext4_find_delalloc_range
  - fs/ext4/super.c:perf_trace_ext4_ext_in_cache
  - fs/ext4/super.c:perf_trace_ext4_ext_put_in_cache
  - fs/ext4/super.c:perf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:perf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:perf_trace_ext4__trim
  - fs/ext4/super.c:perf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:perf_trace_ext4_journal_start
  - fs/ext4/super.c:perf_trace_ext4_load_inode
  - fs/ext4/super.c:perf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_exit
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_enter
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:perf_trace_ext4__truncate
  - fs/ext4/super.c:perf_trace_ext4_unlink_exit
  - fs/ext4/super.c:perf_trace_ext4_unlink_enter
  - fs/ext4/super.c:perf_trace_ext4_fallocate_exit
  - fs/ext4/super.c:perf_trace_ext4__fallocate_mode
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_exit
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_enter
  - fs/ext4/super.c:perf_trace_ext4__bitmap_load
  - fs/ext4/super.c:perf_trace_ext4_da_release_space
  - fs/ext4/super.c:perf_trace_ext4_da_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_da_update_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_forget
  - fs/ext4/super.c:perf_trace_ext4__mballoc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_prealloc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_alloc
  - fs/ext4/super.c:perf_trace_ext4_alloc_da_blocks
  - fs/ext4/super.c:perf_trace_ext4_sync_fs
  - fs/ext4/super.c:perf_trace_ext4_sync_file_exit
  - fs/ext4/super.c:perf_trace_ext4_sync_file_enter
  - fs/ext4/super.c:perf_trace_ext4_free_blocks
  - fs/ext4/super.c:perf_trace_ext4_allocate_blocks
  - fs/ext4/super.c:perf_trace_ext4_request_blocks
  - fs/ext4/super.c:perf_trace_ext4_mb_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_mb_release_group_pa
  - fs/ext4/super.c:perf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:perf_trace_ext4__mb_new_pa
  - fs/ext4/super.c:perf_trace_ext4_discard_blocks
  - fs/ext4/super.c:perf_trace_ext4_invalidatepage_op
  - fs/ext4/super.c:perf_trace_ext4__page_op
  - fs/ext4/super.c:perf_trace_ext4_writepages_result
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages_extent
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages
  - fs/ext4/super.c:perf_trace_ext4_writepages
  - fs/ext4/super.c:perf_trace_ext4__write_end
  - fs/ext4/super.c:perf_trace_ext4__write_begin
  - fs/ext4/super.c:perf_trace_ext4_begin_ordered_truncate
  - fs/ext4/super.c:perf_trace_ext4_mark_inode_dirty
  - fs/ext4/super.c:perf_trace_ext4_drop_inode
  - fs/ext4/super.c:perf_trace_ext4_evict_inode
  - fs/ext4/super.c:perf_trace_ext4_allocate_inode
  - fs/ext4/super.c:perf_trace_ext4_request_inode
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
```
```
In fs/jbd2/journal.c (ffffffff8136bbef)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - fs/jbd2/journal.c:perf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:perf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:perf_trace_jbd2_update_log_tail
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_run_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_extend
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_start
  - fs/jbd2/journal.c:perf_trace_jbd2_submit_inode_data
  - fs/jbd2/journal.c:perf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint
```
```
In security/selinux/avc.c (ffffffff813c88b7)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_get_hash_stats
```
```
In block/blk-core.c (ffffffff8144b4b1)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_unplug
  - block/blk-core.c:perf_trace_block_plug
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_buffer
```
```
In block/blk-ioc.c (ffffffff81455bc0)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff81474192)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_offline
```
```
In block/blk-wbt.c (ffffffff81483a54)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In lib/swiotlb.c (ffffffff814be719)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - lib/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In arch/x86/lib/msr.c (ffffffff814c8844)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff814d7594)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (ffffffff815ab201)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff815d3e81)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff8160bb04)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/char/random.c:perf_trace_urandom_read
  - drivers/char/random.c:perf_trace_random_read
  - drivers/char/random.c:perf_trace_random__extract_entropy
  - drivers/char/random.c:perf_trace_random__get_random_bytes
  - drivers/char/random.c:perf_trace_xfer_secondary_pool
  - drivers/char/random.c:perf_trace_add_disk_randomness
  - drivers/char/random.c:perf_trace_add_input_randomness
  - drivers/char/random.c:perf_trace_debit_entropy
  - drivers/char/random.c:perf_trace_push_to_pool
  - drivers/char/random.c:perf_trace_credit_entropy_bits
  - drivers/char/random.c:perf_trace_random__mix_pool_bytes
  - drivers/char/random.c:perf_trace_add_device_randomness
```
```
In drivers/iommu/iommu-traces.c (ffffffff81628cb8)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff816639ef)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
```
```
In drivers/dma-buf/dma-fence.c (ffffffff816a84fe)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816aa7b3)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff816ab62a)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff816ced8a)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff816f205f)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff816fbc04)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81770a9a)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_dbc_log_request
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_slot_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ep_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_trb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8178f964)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff817933f4)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/thermal/thermal_core.c (ffffffff817a07c8)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (ffffffff817a4874)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff817e9482)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/ras/ras.c (ffffffff8181a574)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_memory_failure_event
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_non_standard_event
  - drivers/ras/ras.c:perf_trace_arm_event
  - drivers/ras/ras.c:perf_trace_mc_event
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
```
```
In net/core/net-traces.c (ffffffff81873512)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_br_fdb_update
  - net/core/net-traces.c:perf_trace_fdb_delete
  - net/core/net-traces.c:perf_trace_br_fdb_external_learn_add
  - net/core/net-traces.c:perf_trace_br_fdb_add
  - net/core/net-traces.c:perf_trace_fib6_table_lookup
  - net/core/net-traces.c:perf_trace_qdisc_dequeue
  - net/core/net-traces.c:perf_trace_fib_validate_source
  - net/core/net-traces.c:perf_trace_fib_table_lookup_nh
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_set_state
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_rcvqueue_full
  - net/core/net-traces.c:perf_trace_napi_poll
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_template
  - net/core/net-traces.c:perf_trace_net_dev_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:perf_trace_consume_skb
  - net/core/net-traces.c:perf_trace_kfree_skb
```
```
In net/ipv4/inet_hashtables.c (ffffffff8189e67a)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8189fe96)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818ba0dd)
Location: include/linux/list.h:639
Inline: True
```
```
In net/ipv4/raw.c (ffffffff818c2b7e)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff818c7193)
Location: include/linux/list.h:639
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff818e18bc)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f5ce3)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff818fe94e)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
```
```
In net/unix/af_unix.c (ffffffff8190270b)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/addrconf.c (ffffffff81917c2a)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
```
```
In net/ipv6/raw.c (ffffffff8192fc2d)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffff81954a10)
Location: include/linux/list.h:639
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
In init/main.c (ffffffff8100217f)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/common.c (ffffffff810036ff)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004e8a)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff8102778f)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_set_ldt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_gdt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_load_idt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_one_user
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_alloc_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pte_at
  - arch/x86/xen/trace.c:perf_trace_xen_mmu__set_pte
  - arch/x86/xen/trace.c:perf_trace_xen_mc_extend_args
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush_reason
  - arch/x86/xen/trace.c:perf_trace_xen_mc_callback
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry_alloc
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mc__batch
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102b9d1)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/irq.c (ffffffff8102fac4)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:perf_trace_vector_free_moved
  - arch/x86/kernel/irq.c:perf_trace_vector_setup
  - arch/x86/kernel/irq.c:perf_trace_vector_teardown
  - arch/x86/kernel/irq.c:perf_trace_vector_activate
  - arch/x86/kernel/irq.c:perf_trace_vector_alloc_managed
  - arch/x86/kernel/irq.c:perf_trace_vector_alloc
  - arch/x86/kernel/irq.c:perf_trace_vector_reserve
  - arch/x86/kernel/irq.c:perf_trace_vector_mod
  - arch/x86/kernel/irq.c:perf_trace_vector_config
  - arch/x86/kernel/irq.c:perf_trace_x86_irq_vector
```
```
In arch/x86/kernel/nmi.c (ffffffff81032564)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81039f2a)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104b61a)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:perf_trace_mce_record
```
```
In arch/x86/mm/init.c (ffffffff81072cdf)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff81074aa4)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff81081f4a)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:perf_trace_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:perf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:perf_trace_bounds_exception_mpx
  - arch/x86/mm/mpx.c:perf_trace_mpx_bounds_register_exception
```
```
In kernel/fork.c (ffffffff8108a5f0)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff81090c0c)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/exit.c (ffffffff81092a8e)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/softirq.c (ffffffff810944ea)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff8109c0e4)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810aa2ba)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/pid.c (ffffffff810b0b92)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/sched/core.c (ffffffff810b8d0a)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_wake_idle_without_ipi
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:perf_trace_sched_process_hang
  - kernel/sched/core.c:perf_trace_sched_pi_setprio
  - kernel/sched/core.c:perf_trace_sched_stat_runtime
  - kernel/sched/core.c:perf_trace_sched_process_exec
  - kernel/sched/core.c:perf_trace_sched_process_fork
  - kernel/sched/core.c:perf_trace_sched_process_wait
  - kernel/sched/core.c:perf_trace_sched_process_template
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:perf_trace_sched_kthread_stop_ret
  - kernel/sched/core.c:perf_trace_sched_kthread_stop
```
```
In kernel/printk/printk.c (ffffffff810f1804)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff81101134)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff8110211a)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff8110d656)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/time/timer.c (ffffffff8111513b)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:perf_trace_tick_stop
  - kernel/time/timer.c:perf_trace_itimer_expire
  - kernel/time/timer.c:perf_trace_itimer_state
  - kernel/time/timer.c:perf_trace_hrtimer_class
  - kernel/time/timer.c:perf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:perf_trace_hrtimer_start
  - kernel/time/timer.c:perf_trace_hrtimer_init
  - kernel/time/timer.c:perf_trace_timer_expire_entry
  - kernel/time/timer.c:perf_trace_timer_start
  - kernel/time/timer.c:perf_trace_timer_class
```
```
In kernel/time/alarmtimer.c (ffffffff8111cb6f)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff8112fe24)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff8113cf63)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/kprobes.c (ffffffff8115be3a)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/trace/ftrace.c (ffffffff811720ae)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:profile_graph_return
  - kernel/trace/ftrace.c:profile_graph_entry
  - kernel/trace/ftrace.c:profile_graph_entry
```
```
In kernel/trace/trace_syscalls.c (ffffffff8119681d)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811a683c)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/power-traces.c (ffffffff811aa253)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:perf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:perf_trace_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_power_domain
  - kernel/trace/power-traces.c:perf_trace_clock
  - kernel/trace/power-traces.c:perf_trace_wakeup_source
  - kernel/trace/power-traces.c:perf_trace_suspend_resume
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:perf_trace_pstate_sample
  - kernel/trace/power-traces.c:perf_trace_powernv_throttle
  - kernel/trace/power-traces.c:perf_trace_cpu
```
```
In kernel/trace/rpm-traces.c (ffffffff811ab895)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ae39c)
Location: include/linux/list.h:639
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811b0aa8)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/events/core.c (ffffffff811d6515)
Location: include/linux/list.h:639
Inline: True
```
```
In kernel/user-return-notifier.c (ffffffff811e6e24)
Location: include/linux/list.h:639
Inline: True
```
```
In kernel/rseq.c (ffffffff811e9cc4)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff811eaebf)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff811f2198)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:perf_trace_skip_task_reaping
  - mm/oom_kill.c:perf_trace_finish_task_reaping
  - mm/oom_kill.c:perf_trace_start_task_reaping
  - mm/oom_kill.c:perf_trace_wake_reaper
  - mm/oom_kill.c:perf_trace_mark_victim
  - mm/oom_kill.c:perf_trace_reclaim_retry_zone
  - mm/oom_kill.c:perf_trace_oom_score_adj_update
```
```
In mm/swap.c (ffffffff8120076a)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff81205574)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - mm/vmscan.c:perf_trace_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_isolate
  - mm/vmscan.c:perf_trace_mm_shrink_slab_end
  - mm/vmscan.c:perf_trace_mm_shrink_slab_start
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_end_template
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:perf_trace_mm_vmscan_wakeup_kswapd
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_wake
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_sleep
```
```
In mm/percpu.c (ffffffff812199ca)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff8121cff4)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:perf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:perf_trace_mm_page
  - mm/slab_common.c:perf_trace_mm_page_alloc
  - mm/slab_common.c:perf_trace_mm_page_free_batched
  - mm/slab_common.c:perf_trace_mm_page_free
  - mm/slab_common.c:perf_trace_kmem_free
  - mm/slab_common.c:perf_trace_kmem_alloc_node
  - mm/slab_common.c:perf_trace_kmem_alloc
```
```
In mm/compaction.c (ffffffff8121fc44)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - mm/compaction.c:perf_trace_kcompactd_wake_template
  - mm/compaction.c:perf_trace_mm_compaction_kcompactd_sleep
  - mm/compaction.c:perf_trace_mm_compaction_defer_template
  - mm/compaction.c:perf_trace_mm_compaction_suitable_template
  - mm/compaction.c:perf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:perf_trace_mm_compaction_end
  - mm/compaction.c:perf_trace_mm_compaction_begin
  - mm/compaction.c:perf_trace_mm_compaction_migratepages
  - mm/compaction.c:perf_trace_mm_compaction_isolate_template
```
```
In mm/mmu_notifier.c (ffffffff8125e674)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_mm_destroy
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (ffffffff81261442)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
```
```
In mm/migrate.c (ffffffff8126cb33)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_numa_migrate_ratelimit
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff8127a044)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff8128b284)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffffffff8128ef34)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffffffff8129592d)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/super.c (ffffffff8129deb6)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - fs/super.c:do_remount_sb
```
```
In fs/dcache.c (ffffffff812b60c3)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_find_any_alias
```
```
In fs/namespace.c (ffffffff812c0666)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:namespace_unlock
```
```
In fs/seq_file.c (ffffffff812c34fb)
Location: include/linux/list.h:639
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812c7f9a)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_writeback_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_congest_waited_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_pages_written
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_page
```
```
In fs/notify/mark.c (ffffffff812e5c32)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/dax.c (ffffffff812f64a4)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - fs/dax.c:perf_trace_dax_writeback_one
  - fs/dax.c:perf_trace_dax_writeback_range_class
  - fs/dax.c:perf_trace_dax_insert_mapping
  - fs/dax.c:perf_trace_dax_pte_fault_class
  - fs/dax.c:perf_trace_dax_pmd_insert_mapping_class
  - fs/dax.c:perf_trace_dax_pmd_load_hole_class
  - fs/dax.c:perf_trace_dax_pmd_fault_class
```
```
In fs/locks.c (ffffffff812fd0cf)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffff8137a164)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_error
  - fs/ext4/super.c:perf_trace_ext4_shutdown
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:perf_trace_ext4_insert_range
  - fs/ext4/super.c:perf_trace_ext4_collapse_range
  - fs/ext4/super.c:perf_trace_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:perf_trace_ext4__es_shrink_enter
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:perf_trace_ext4_es_find_delayed_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_delayed_extent_range_enter
  - fs/ext4/super.c:perf_trace_ext4_es_remove_extent
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_idx
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_show_extent
  - fs/ext4/super.c:perf_trace_ext4_get_reserved_cluster_alloc
  - fs/ext4/super.c:perf_trace_ext4_find_delalloc_range
  - fs/ext4/super.c:perf_trace_ext4_ext_in_cache
  - fs/ext4/super.c:perf_trace_ext4_ext_put_in_cache
  - fs/ext4/super.c:perf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:perf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:perf_trace_ext4__trim
  - fs/ext4/super.c:perf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:perf_trace_ext4_journal_start
  - fs/ext4/super.c:perf_trace_ext4_load_inode
  - fs/ext4/super.c:perf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_exit
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_enter
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:perf_trace_ext4__truncate
  - fs/ext4/super.c:perf_trace_ext4_unlink_exit
  - fs/ext4/super.c:perf_trace_ext4_unlink_enter
  - fs/ext4/super.c:perf_trace_ext4_fallocate_exit
  - fs/ext4/super.c:perf_trace_ext4__fallocate_mode
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_exit
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_enter
  - fs/ext4/super.c:perf_trace_ext4__bitmap_load
  - fs/ext4/super.c:perf_trace_ext4_da_release_space
  - fs/ext4/super.c:perf_trace_ext4_da_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_da_update_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_forget
  - fs/ext4/super.c:perf_trace_ext4__mballoc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_prealloc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_alloc
  - fs/ext4/super.c:perf_trace_ext4_alloc_da_blocks
  - fs/ext4/super.c:perf_trace_ext4_sync_fs
  - fs/ext4/super.c:perf_trace_ext4_sync_file_exit
  - fs/ext4/super.c:perf_trace_ext4_sync_file_enter
  - fs/ext4/super.c:perf_trace_ext4_free_blocks
  - fs/ext4/super.c:perf_trace_ext4_allocate_blocks
  - fs/ext4/super.c:perf_trace_ext4_request_blocks
  - fs/ext4/super.c:perf_trace_ext4_mb_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_mb_release_group_pa
  - fs/ext4/super.c:perf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:perf_trace_ext4__mb_new_pa
  - fs/ext4/super.c:perf_trace_ext4_discard_blocks
  - fs/ext4/super.c:perf_trace_ext4_invalidatepage_op
  - fs/ext4/super.c:perf_trace_ext4__page_op
  - fs/ext4/super.c:perf_trace_ext4_writepages_result
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages_extent
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages
  - fs/ext4/super.c:perf_trace_ext4_writepages
  - fs/ext4/super.c:perf_trace_ext4__write_end
  - fs/ext4/super.c:perf_trace_ext4__write_begin
  - fs/ext4/super.c:perf_trace_ext4_begin_ordered_truncate
  - fs/ext4/super.c:perf_trace_ext4_mark_inode_dirty
  - fs/ext4/super.c:perf_trace_ext4_drop_inode
  - fs/ext4/super.c:perf_trace_ext4_evict_inode
  - fs/ext4/super.c:perf_trace_ext4_allocate_inode
  - fs/ext4/super.c:perf_trace_ext4_request_inode
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
```
```
In fs/jbd2/journal.c (ffffffff8139a38f)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - fs/jbd2/journal.c:perf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:perf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:perf_trace_jbd2_update_log_tail
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_run_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_extend
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_start
  - fs/jbd2/journal.c:perf_trace_jbd2_submit_inode_data
  - fs/jbd2/journal.c:perf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint
```
```
In security/selinux/avc.c (ffffffff813f7f68)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_get_hash_stats
```
```
In block/blk-core.c (ffffffff8147e7c1)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_unplug
  - block/blk-core.c:perf_trace_block_plug
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_buffer
```
```
In block/blk-ioc.c (ffffffff81489100)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff814a8992)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_free
```
```
In block/blk-wbt.c (ffffffff814b87f8)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In arch/x86/lib/msr.c (ffffffff814f97e4)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff81506814)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (ffffffff815e2f00)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff8160bdd0)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff816455b4)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/char/random.c:perf_trace_urandom_read
  - drivers/char/random.c:perf_trace_random_read
  - drivers/char/random.c:perf_trace_random__extract_entropy
  - drivers/char/random.c:perf_trace_random__get_random_bytes
  - drivers/char/random.c:perf_trace_xfer_secondary_pool
  - drivers/char/random.c:perf_trace_add_disk_randomness
  - drivers/char/random.c:perf_trace_add_input_randomness
  - drivers/char/random.c:perf_trace_debit_entropy
  - drivers/char/random.c:perf_trace_push_to_pool
  - drivers/char/random.c:perf_trace_credit_entropy_bits
  - drivers/char/random.c:perf_trace_random__mix_pool_bytes
  - drivers/char/random.c:perf_trace_add_device_randomness
```
```
In drivers/iommu/iommu-traces.c (ffffffff81663a09)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff8169fb41)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
```
```
In drivers/dma-buf/dma-fence.c (ffffffff816e47e3)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816e6cb2)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff816e7b4a)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff8170b81a)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff8172eaaf)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff817391bc)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff817b0e8a)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_dbc_log_request
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_slot_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ep_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_free_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_trb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
```
```
In drivers/rtc/interface.c (ffffffff817cc54a)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/rtc/interface.c:perf_trace_rtc_timer_class
  - drivers/rtc/interface.c:perf_trace_rtc_offset_class
  - drivers/rtc/interface.c:perf_trace_rtc_alarm_irq_enable
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_state
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_freq
  - drivers/rtc/interface.c:perf_trace_rtc_time_alarm_class
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817d22d4)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff817d5d04)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/thermal/thermal_core.c (ffffffff817e7d99)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (ffffffff817ec354)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff818322fd)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/ras/ras.c (ffffffff81864604)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_memory_failure_event
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_non_standard_event
  - drivers/ras/ras.c:perf_trace_arm_event
  - drivers/ras/ras.c:perf_trace_mc_event
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
```
```
In net/core/net-traces.c (ffffffff818c4ca8)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_br_fdb_update
  - net/core/net-traces.c:perf_trace_fdb_delete
  - net/core/net-traces.c:perf_trace_br_fdb_external_learn_add
  - net/core/net-traces.c:perf_trace_br_fdb_add
  - net/core/net-traces.c:perf_trace_qdisc_dequeue
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_rcvqueue_full
  - net/core/net-traces.c:perf_trace_napi_poll
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_template
  - net/core/net-traces.c:perf_trace_net_dev_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:perf_trace_consume_skb
  - net/core/net-traces.c:perf_trace_kfree_skb
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f2fe5)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f46ab)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81910b84)
Location: include/linux/list.h:639
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81918dcc)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff8191c5e7)
Location: include/linux/list.h:639
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff819383d9)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194c82a)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff8195542e)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
```
```
In net/unix/af_unix.c (ffffffff81958c41)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/addrconf.c (ffffffff8196f34a)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
```
```
In net/ipv6/route.c (ffffffff819701f7)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
```
In net/ipv6/raw.c (ffffffff819888cd)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffff819adbd0)
Location: include/linux/list.h:639
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
In init/main.c (ffffffff8100217f)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/common.c (ffffffff8100378f)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004dea)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff81027d6f)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_set_ldt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_gdt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_load_idt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_one_user
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_alloc_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pte_at
  - arch/x86/xen/trace.c:perf_trace_xen_mmu__set_pte
  - arch/x86/xen/trace.c:perf_trace_xen_mc_extend_args
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush_reason
  - arch/x86/xen/trace.c:perf_trace_xen_mc_callback
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry_alloc
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mc__batch
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102c421)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/irq.c (ffffffff81030d54)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:perf_trace_vector_free_moved
  - arch/x86/kernel/irq.c:perf_trace_vector_setup
  - arch/x86/kernel/irq.c:perf_trace_vector_teardown
  - arch/x86/kernel/irq.c:perf_trace_vector_activate
  - arch/x86/kernel/irq.c:perf_trace_vector_alloc_managed
  - arch/x86/kernel/irq.c:perf_trace_vector_alloc
  - arch/x86/kernel/irq.c:perf_trace_vector_reserve
  - arch/x86/kernel/irq.c:perf_trace_vector_mod
  - arch/x86/kernel/irq.c:perf_trace_vector_config
  - arch/x86/kernel/irq.c:perf_trace_x86_irq_vector
```
```
In arch/x86/kernel/nmi.c (ffffffff81033824)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103b44a)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81048cda)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105bd9f)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/init.c (ffffffff81078d6f)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff8107a964)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff81088b5a)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:perf_trace_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:perf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:perf_trace_bounds_exception_mpx
  - arch/x86/mm/mpx.c:perf_trace_mpx_bounds_register_exception
```
```
In kernel/fork.c (ffffffff81092590)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff81098ccc)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/exit.c (ffffffff8109ad7e)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/softirq.c (ffffffff8109c84a)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810a4344)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810b338a)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/pid.c (ffffffff810b9c67)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/sched/core.c (ffffffff810c1e0a)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_wake_idle_without_ipi
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:perf_trace_sched_process_hang
  - kernel/sched/core.c:perf_trace_sched_pi_setprio
  - kernel/sched/core.c:perf_trace_sched_stat_runtime
  - kernel/sched/core.c:perf_trace_sched_process_exec
  - kernel/sched/core.c:perf_trace_sched_process_fork
  - kernel/sched/core.c:perf_trace_sched_process_wait
  - kernel/sched/core.c:perf_trace_sched_process_template
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:perf_trace_sched_kthread_stop_ret
  - kernel/sched/core.c:perf_trace_sched_kthread_stop
```
```
In kernel/printk/printk.c (ffffffff810fceb4)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff8110ca54)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff8110db1a)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff81119256)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/time/timer.c (ffffffff8112077b)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:perf_trace_tick_stop
  - kernel/time/timer.c:perf_trace_itimer_expire
  - kernel/time/timer.c:perf_trace_itimer_state
  - kernel/time/timer.c:perf_trace_hrtimer_class
  - kernel/time/timer.c:perf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:perf_trace_hrtimer_start
  - kernel/time/timer.c:perf_trace_hrtimer_init
  - kernel/time/timer.c:perf_trace_timer_expire_entry
  - kernel/time/timer.c:perf_trace_timer_start
  - kernel/time/timer.c:perf_trace_timer_class
```
```
In kernel/time/alarmtimer.c (ffffffff8112831f)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff8113b6d4)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff811488a1)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/kprobes.c (ffffffff81168bca)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/trace/ftrace.c (ffffffff8117f9d4)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:profile_graph_return
```
```
In kernel/trace/trace_syscalls.c (ffffffff811a495d)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811b694d)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/power-traces.c (ffffffff811b8603)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:perf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:perf_trace_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_power_domain
  - kernel/trace/power-traces.c:perf_trace_clock
  - kernel/trace/power-traces.c:perf_trace_wakeup_source
  - kernel/trace/power-traces.c:perf_trace_suspend_resume
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:perf_trace_cpu_frequency_limits
  - kernel/trace/power-traces.c:perf_trace_pstate_sample
  - kernel/trace/power-traces.c:perf_trace_powernv_throttle
  - kernel/trace/power-traces.c:perf_trace_cpu
```
```
In kernel/trace/rpm-traces.c (ffffffff811b9e55)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffffffff811bcaac)
Location: include/linux/list.h:692
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811bf128)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/events/core.c (ffffffff811e6eb5)
Location: include/linux/list.h:692
Inline: True
```
```
In kernel/user-return-notifier.c (ffffffff811f7a54)
Location: include/linux/list.h:692
Inline: True
```
```
In kernel/rseq.c (ffffffff811fa834)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff811fba2f)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff81204008)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:perf_trace_skip_task_reaping
  - mm/oom_kill.c:perf_trace_finish_task_reaping
  - mm/oom_kill.c:perf_trace_start_task_reaping
  - mm/oom_kill.c:perf_trace_wake_reaper
  - mm/oom_kill.c:perf_trace_mark_victim
  - mm/oom_kill.c:perf_trace_reclaim_retry_zone
  - mm/oom_kill.c:perf_trace_oom_score_adj_update
```
```
In mm/swap.c (ffffffff812130da)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff81217f44)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - mm/vmscan.c:perf_trace_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_isolate
  - mm/vmscan.c:perf_trace_mm_shrink_slab_end
  - mm/vmscan.c:perf_trace_mm_shrink_slab_start
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_end_template
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:perf_trace_mm_vmscan_wakeup_kswapd
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_wake
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_sleep
```
```
In mm/percpu.c (ffffffff8122c93a)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff8122ffe4)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:perf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:perf_trace_mm_page
  - mm/slab_common.c:perf_trace_mm_page_alloc
  - mm/slab_common.c:perf_trace_mm_page_free_batched
  - mm/slab_common.c:perf_trace_mm_page_free
  - mm/slab_common.c:perf_trace_kmem_free
  - mm/slab_common.c:perf_trace_kmem_alloc_node
  - mm/slab_common.c:perf_trace_kmem_alloc
```
```
In mm/compaction.c (ffffffff81232c74)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - mm/compaction.c:perf_trace_kcompactd_wake_template
  - mm/compaction.c:perf_trace_mm_compaction_kcompactd_sleep
  - mm/compaction.c:perf_trace_mm_compaction_defer_template
  - mm/compaction.c:perf_trace_mm_compaction_suitable_template
  - mm/compaction.c:perf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:perf_trace_mm_compaction_end
  - mm/compaction.c:perf_trace_mm_compaction_begin
  - mm/compaction.c:perf_trace_mm_compaction_migratepages
  - mm/compaction.c:perf_trace_mm_compaction_isolate_template
```
```
In mm/mmu_notifier.c (ffffffff81272e54)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_mm_destroy
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (ffffffff81275c20)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
```
```
In mm/migrate.c (ffffffff81281234)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff8128e644)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff812a01d4)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffffffff812a3e34)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffffffff812aa71d)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/super.c (ffffffff812b2e76)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - fs/super.c:do_remount_sb
```
```
In fs/dcache.c (ffffffff812cb643)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_find_any_alias
```
```
In fs/namespace.c (ffffffff812d58b6)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:namespace_unlock
```
```
In fs/seq_file.c (ffffffff812d874b)
Location: include/linux/list.h:692
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812dd19a)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_writeback_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_congest_waited_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_pages_written
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_page
```
```
In fs/notify/mark.c (ffffffff812fa821)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/dax.c (ffffffff8130b594)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - fs/dax.c:perf_trace_dax_writeback_one
  - fs/dax.c:perf_trace_dax_writeback_range_class
  - fs/dax.c:perf_trace_dax_insert_mapping
  - fs/dax.c:perf_trace_dax_pte_fault_class
  - fs/dax.c:perf_trace_dax_pmd_insert_mapping_class
  - fs/dax.c:perf_trace_dax_pmd_load_hole_class
  - fs/dax.c:perf_trace_dax_pmd_fault_class
```
```
In fs/locks.c (ffffffff8131293f)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffff81392c04)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_error
  - fs/ext4/super.c:perf_trace_ext4_shutdown
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:perf_trace_ext4_insert_range
  - fs/ext4/super.c:perf_trace_ext4_collapse_range
  - fs/ext4/super.c:perf_trace_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:perf_trace_ext4__es_shrink_enter
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_enter
  - fs/ext4/super.c:perf_trace_ext4_es_remove_extent
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_idx
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_show_extent
  - fs/ext4/super.c:perf_trace_ext4_get_reserved_cluster_alloc
  - fs/ext4/super.c:perf_trace_ext4_find_delalloc_range
  - fs/ext4/super.c:perf_trace_ext4_ext_in_cache
  - fs/ext4/super.c:perf_trace_ext4_ext_put_in_cache
  - fs/ext4/super.c:perf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:perf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:perf_trace_ext4__trim
  - fs/ext4/super.c:perf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:perf_trace_ext4_journal_start
  - fs/ext4/super.c:perf_trace_ext4_load_inode
  - fs/ext4/super.c:perf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_exit
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_enter
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:perf_trace_ext4__truncate
  - fs/ext4/super.c:perf_trace_ext4_unlink_exit
  - fs/ext4/super.c:perf_trace_ext4_unlink_enter
  - fs/ext4/super.c:perf_trace_ext4_fallocate_exit
  - fs/ext4/super.c:perf_trace_ext4__fallocate_mode
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_exit
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_enter
  - fs/ext4/super.c:perf_trace_ext4__bitmap_load
  - fs/ext4/super.c:perf_trace_ext4_da_release_space
  - fs/ext4/super.c:perf_trace_ext4_da_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_da_update_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_forget
  - fs/ext4/super.c:perf_trace_ext4__mballoc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_prealloc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_alloc
  - fs/ext4/super.c:perf_trace_ext4_alloc_da_blocks
  - fs/ext4/super.c:perf_trace_ext4_sync_fs
  - fs/ext4/super.c:perf_trace_ext4_sync_file_exit
  - fs/ext4/super.c:perf_trace_ext4_sync_file_enter
  - fs/ext4/super.c:perf_trace_ext4_free_blocks
  - fs/ext4/super.c:perf_trace_ext4_allocate_blocks
  - fs/ext4/super.c:perf_trace_ext4_request_blocks
  - fs/ext4/super.c:perf_trace_ext4_mb_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_mb_release_group_pa
  - fs/ext4/super.c:perf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:perf_trace_ext4__mb_new_pa
  - fs/ext4/super.c:perf_trace_ext4_discard_blocks
  - fs/ext4/super.c:perf_trace_ext4_invalidatepage_op
  - fs/ext4/super.c:perf_trace_ext4__page_op
  - fs/ext4/super.c:perf_trace_ext4_writepages_result
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages_extent
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages
  - fs/ext4/super.c:perf_trace_ext4_writepages
  - fs/ext4/super.c:perf_trace_ext4__write_end
  - fs/ext4/super.c:perf_trace_ext4__write_begin
  - fs/ext4/super.c:perf_trace_ext4_begin_ordered_truncate
  - fs/ext4/super.c:perf_trace_ext4_mark_inode_dirty
  - fs/ext4/super.c:perf_trace_ext4_nfs_commit_metadata
  - fs/ext4/super.c:perf_trace_ext4_drop_inode
  - fs/ext4/super.c:perf_trace_ext4_evict_inode
  - fs/ext4/super.c:perf_trace_ext4_allocate_inode
  - fs/ext4/super.c:perf_trace_ext4_request_inode
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
```
```
In fs/jbd2/journal.c (ffffffff813b30ff)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - fs/jbd2/journal.c:perf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:perf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:perf_trace_jbd2_update_log_tail
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_run_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_extend
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_start
  - fs/jbd2/journal.c:perf_trace_jbd2_submit_inode_data
  - fs/jbd2/journal.c:perf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint
```
```
In security/selinux/avc.c (ffffffff81413a18)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_get_hash_stats
```
```
In block/blk-core.c (ffffffff8149be11)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_unplug
  - block/blk-core.c:perf_trace_block_plug
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_buffer
```
```
In block/blk-ioc.c (ffffffff814a2ec0)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff814c2ff2)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In block/blk-wbt.c (ffffffff814cc7e8)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In arch/x86/lib/msr.c (ffffffff8150e084)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff8151ae14)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (ffffffff815fc880)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff81623c40)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff816638b4)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - drivers/char/random.c:perf_trace_urandom_read
  - drivers/char/random.c:perf_trace_random_read
  - drivers/char/random.c:perf_trace_random__extract_entropy
  - drivers/char/random.c:perf_trace_random__get_random_bytes
  - drivers/char/random.c:perf_trace_xfer_secondary_pool
  - drivers/char/random.c:perf_trace_add_disk_randomness
  - drivers/char/random.c:perf_trace_add_input_randomness
  - drivers/char/random.c:perf_trace_debit_entropy
  - drivers/char/random.c:perf_trace_push_to_pool
  - drivers/char/random.c:perf_trace_credit_entropy_bits
  - drivers/char/random.c:perf_trace_random__mix_pool_bytes
  - drivers/char/random.c:perf_trace_add_device_randomness
```
```
In drivers/iommu/iommu-traces.c (ffffffff81681ff9)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff816bff51)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81707bd3)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8170a042)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff8170b64a)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff8172dc9a)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff8175101f)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff8175c8dc)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff817d740a)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_dbc_log_request
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_slot_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ep_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_free_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_trb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
```
```
In drivers/rtc/interface.c (ffffffff817f384a)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - drivers/rtc/interface.c:perf_trace_rtc_timer_class
  - drivers/rtc/interface.c:perf_trace_rtc_offset_class
  - drivers/rtc/interface.c:perf_trace_rtc_alarm_irq_enable
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_state
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_freq
  - drivers/rtc/interface.c:perf_trace_rtc_time_alarm_class
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817f9434)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff817fce34)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff818117f7)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff81813c49)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (ffffffff81818224)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff8185e4fd)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/ras/ras.c (ffffffff818841d4)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_memory_failure_event
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_non_standard_event
  - drivers/ras/ras.c:perf_trace_arm_event
  - drivers/ras/ras.c:perf_trace_mc_event
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
```
```
In net/core/net-traces.c (ffffffff818edd18)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_br_fdb_update
  - net/core/net-traces.c:perf_trace_fdb_delete
  - net/core/net-traces.c:perf_trace_br_fdb_external_learn_add
  - net/core/net-traces.c:perf_trace_br_fdb_add
  - net/core/net-traces.c:perf_trace_qdisc_dequeue
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_rcvqueue_full
  - net/core/net-traces.c:perf_trace_napi_poll
  - net/core/net-traces.c:perf_trace_net_dev_rx_exit_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_template
  - net/core/net-traces.c:perf_trace_net_dev_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:perf_trace_consume_skb
  - net/core/net-traces.c:perf_trace_kfree_skb
```
```
In net/ipv4/inet_hashtables.c (ffffffff819209ff)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8192240f)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193e874)
Location: include/linux/list.h:692
Inline: True
```
```
In net/ipv4/raw.c (ffffffff8194761c)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff8194ab87)
Location: include/linux/list.h:692
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff81967dcb)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff819802ba)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff8198a043)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
```
```
In net/unix/af_unix.c (ffffffff8198d7f1)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/anycast.c (ffffffff8199492e)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_anycast_cleanup
```
```
In net/ipv6/addrconf.c (ffffffff819a4efa)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
```
```
In net/ipv6/route.c (ffffffff819a5e27)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
```
In net/ipv6/raw.c (ffffffff819bf23d)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffff819e4560)
Location: include/linux/list.h:692
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
In init/main.c (ffffffff8100220f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/common.c (ffffffff810038cf)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004eba)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff810299df)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_set_ldt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_gdt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_load_idt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_one_user
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_alloc_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pte_at
  - arch/x86/xen/trace.c:perf_trace_xen_mmu__set_pte
  - arch/x86/xen/trace.c:perf_trace_xen_mc_extend_args
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush_reason
  - arch/x86/xen/trace.c:perf_trace_xen_mc_callback
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry_alloc
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mc__batch
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102d801)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/irq.c (ffffffff81032aa8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:perf_trace_vector_free_moved
  - arch/x86/kernel/irq.c:perf_trace_vector_setup
  - arch/x86/kernel/irq.c:perf_trace_vector_teardown
  - arch/x86/kernel/irq.c:perf_trace_vector_activate
  - arch/x86/kernel/irq.c:perf_trace_vector_alloc_managed
  - arch/x86/kernel/irq.c:perf_trace_vector_alloc
  - arch/x86/kernel/irq.c:perf_trace_vector_reserve
  - arch/x86/kernel/irq.c:perf_trace_vector_mod
  - arch/x86/kernel/irq.c:perf_trace_vector_config
  - arch/x86/kernel/irq.c:perf_trace_x86_irq_vector
```
```
In arch/x86/kernel/nmi.c (ffffffff810355b4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103da1a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104bd8a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105f10f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/init.c (ffffffff8107c95f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff8107e6d4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff8108c72a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:perf_trace_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:perf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:perf_trace_bounds_exception_mpx
  - arch/x86/mm/mpx.c:perf_trace_mpx_bounds_register_exception
```
```
In kernel/fork.c (ffffffff81096420)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff8109d25f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/exit.c (ffffffff8109f3ed)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/softirq.c (ffffffff810a0e8a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810a9004)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810b8f3a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/pid.c (ffffffff810bfb73)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/sched/core.c (ffffffff810c7e5a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_wake_idle_without_ipi
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:perf_trace_sched_process_hang
  - kernel/sched/core.c:perf_trace_sched_pi_setprio
  - kernel/sched/core.c:perf_trace_sched_stat_runtime
  - kernel/sched/core.c:perf_trace_sched_process_exec
  - kernel/sched/core.c:perf_trace_sched_process_fork
  - kernel/sched/core.c:perf_trace_sched_process_wait
  - kernel/sched/core.c:perf_trace_sched_process_template
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:perf_trace_sched_kthread_stop_ret
  - kernel/sched/core.c:perf_trace_sched_kthread_stop
```
```
In kernel/printk/printk.c (ffffffff811055a4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff81116133)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff811171ba)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff81123cb8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/time/timer.c (ffffffff8112b068)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:perf_trace_tick_stop
  - kernel/time/timer.c:perf_trace_itimer_expire
  - kernel/time/timer.c:perf_trace_itimer_state
  - kernel/time/timer.c:perf_trace_hrtimer_class
  - kernel/time/timer.c:perf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:perf_trace_hrtimer_start
  - kernel/time/timer.c:perf_trace_hrtimer_init
  - kernel/time/timer.c:perf_trace_timer_expire_entry
  - kernel/time/timer.c:perf_trace_timer_start
  - kernel/time/timer.c:perf_trace_timer_class
```
```
In kernel/time/alarmtimer.c (ffffffff81132d5f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff81146d15)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff811538a1)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/kprobes.c (ffffffff8117585d)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/trace/ftrace.c (ffffffff8118cac4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:profile_graph_return
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b28a6)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c59dc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/power-traces.c (ffffffff811c7704)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:perf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:perf_trace_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_power_domain
  - kernel/trace/power-traces.c:perf_trace_clock
  - kernel/trace/power-traces.c:perf_trace_wakeup_source
  - kernel/trace/power-traces.c:perf_trace_suspend_resume
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:perf_trace_cpu_frequency_limits
  - kernel/trace/power-traces.c:perf_trace_pstate_sample
  - kernel/trace/power-traces.c:perf_trace_powernv_throttle
  - kernel/trace/power-traces.c:perf_trace_cpu
```
```
In kernel/trace/rpm-traces.c (ffffffff811c8ea3)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cc1ff)
Location: include/linux/list.h:752
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811cf43f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_mem_return_failed
  - kernel/bpf/core.c:perf_trace_mem_connect
  - kernel/bpf/core.c:perf_trace_mem_disconnect
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_bulk_tx
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/events/core.c (ffffffff811fe525)
Location: include/linux/list.h:752
Inline: True
```
```
In kernel/user-return-notifier.c (ffffffff8120f892)
Location: include/linux/list.h:752
Inline: True
```
```
In kernel/rseq.c (ffffffff81211f88)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff812130ff)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff8121b3eb)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:perf_trace_skip_task_reaping
  - mm/oom_kill.c:perf_trace_finish_task_reaping
  - mm/oom_kill.c:perf_trace_start_task_reaping
  - mm/oom_kill.c:perf_trace_wake_reaper
  - mm/oom_kill.c:perf_trace_mark_victim
  - mm/oom_kill.c:perf_trace_reclaim_retry_zone
  - mm/oom_kill.c:perf_trace_oom_score_adj_update
```
```
In mm/swap.c (ffffffff812229fa)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff81227984)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/vmscan.c:perf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:perf_trace_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_isolate
  - mm/vmscan.c:perf_trace_mm_shrink_slab_end
  - mm/vmscan.c:perf_trace_mm_shrink_slab_start
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_end_template
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:perf_trace_mm_vmscan_wakeup_kswapd
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_wake
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_sleep
```
```
In mm/percpu.c (ffffffff8123c9ba)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff8124002b)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:perf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:perf_trace_mm_page
  - mm/slab_common.c:perf_trace_mm_page_alloc
  - mm/slab_common.c:perf_trace_mm_page_free_batched
  - mm/slab_common.c:perf_trace_mm_page_free
  - mm/slab_common.c:perf_trace_kmem_free
  - mm/slab_common.c:perf_trace_kmem_alloc_node
  - mm/slab_common.c:perf_trace_kmem_alloc
```
```
In mm/compaction.c (ffffffff81243204)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/compaction.c:perf_trace_kcompactd_wake_template
  - mm/compaction.c:perf_trace_mm_compaction_kcompactd_sleep
  - mm/compaction.c:perf_trace_mm_compaction_defer_template
  - mm/compaction.c:perf_trace_mm_compaction_suitable_template
  - mm/compaction.c:perf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:perf_trace_mm_compaction_end
  - mm/compaction.c:perf_trace_mm_compaction_begin
  - mm/compaction.c:perf_trace_mm_compaction_migratepages
  - mm/compaction.c:perf_trace_mm_compaction_isolate_template
```
```
In mm/mmu_notifier.c (ffffffff8128e654)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_mm_destroy
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (ffffffff81291854)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
```
```
In mm/migrate.c (ffffffff8129d568)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff812a8f78)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff812bb454)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffffffff812bf244)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffffffff812c6eee)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/super.c (ffffffff812cfbfb)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/super.c:reconfigure_super
```
```
In fs/dcache.c (ffffffff812e8327)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_find_any_alias
```
```
In fs/namespace.c (ffffffff812f3a86)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:namespace_unlock
```
```
In fs/seq_file.c (ffffffff812f6c6c)
Location: include/linux/list.h:752
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812fb84a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_writeback_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_congest_waited_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_pages_written
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
```
```
In fs/notify/mark.c (ffffffff8131aa1c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/dax.c (ffffffff81332a24)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/dax.c:perf_trace_dax_writeback_one
  - fs/dax.c:perf_trace_dax_writeback_range_class
  - fs/dax.c:perf_trace_dax_insert_mapping
  - fs/dax.c:perf_trace_dax_pte_fault_class
  - fs/dax.c:perf_trace_dax_pmd_insert_mapping_class
  - fs/dax.c:perf_trace_dax_pmd_load_hole_class
  - fs/dax.c:perf_trace_dax_pmd_fault_class
```
```
In fs/locks.c (ffffffff8133a003)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffff813bcaa4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_error
  - fs/ext4/super.c:perf_trace_ext4_shutdown
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:perf_trace_ext4_insert_range
  - fs/ext4/super.c:perf_trace_ext4_collapse_range
  - fs/ext4/super.c:perf_trace_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:perf_trace_ext4__es_shrink_enter
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_enter
  - fs/ext4/super.c:perf_trace_ext4_es_remove_extent
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_idx
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_show_extent
  - fs/ext4/super.c:perf_trace_ext4_get_reserved_cluster_alloc
  - fs/ext4/super.c:perf_trace_ext4_find_delalloc_range
  - fs/ext4/super.c:perf_trace_ext4_ext_in_cache
  - fs/ext4/super.c:perf_trace_ext4_ext_put_in_cache
  - fs/ext4/super.c:perf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:perf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:perf_trace_ext4__trim
  - fs/ext4/super.c:perf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:perf_trace_ext4_journal_start
  - fs/ext4/super.c:perf_trace_ext4_load_inode
  - fs/ext4/super.c:perf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_exit
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_enter
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:perf_trace_ext4__truncate
  - fs/ext4/super.c:perf_trace_ext4_unlink_exit
  - fs/ext4/super.c:perf_trace_ext4_unlink_enter
  - fs/ext4/super.c:perf_trace_ext4_fallocate_exit
  - fs/ext4/super.c:perf_trace_ext4__fallocate_mode
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_exit
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_enter
  - fs/ext4/super.c:perf_trace_ext4__bitmap_load
  - fs/ext4/super.c:perf_trace_ext4_da_release_space
  - fs/ext4/super.c:perf_trace_ext4_da_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_da_update_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_forget
  - fs/ext4/super.c:perf_trace_ext4__mballoc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_prealloc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_alloc
  - fs/ext4/super.c:perf_trace_ext4_alloc_da_blocks
  - fs/ext4/super.c:perf_trace_ext4_sync_fs
  - fs/ext4/super.c:perf_trace_ext4_sync_file_exit
  - fs/ext4/super.c:perf_trace_ext4_sync_file_enter
  - fs/ext4/super.c:perf_trace_ext4_free_blocks
  - fs/ext4/super.c:perf_trace_ext4_allocate_blocks
  - fs/ext4/super.c:perf_trace_ext4_request_blocks
  - fs/ext4/super.c:perf_trace_ext4_mb_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_mb_release_group_pa
  - fs/ext4/super.c:perf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:perf_trace_ext4__mb_new_pa
  - fs/ext4/super.c:perf_trace_ext4_discard_blocks
  - fs/ext4/super.c:perf_trace_ext4_invalidatepage_op
  - fs/ext4/super.c:perf_trace_ext4__page_op
  - fs/ext4/super.c:perf_trace_ext4_writepages_result
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages_extent
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages
  - fs/ext4/super.c:perf_trace_ext4_writepages
  - fs/ext4/super.c:perf_trace_ext4__write_end
  - fs/ext4/super.c:perf_trace_ext4__write_begin
  - fs/ext4/super.c:perf_trace_ext4_begin_ordered_truncate
  - fs/ext4/super.c:perf_trace_ext4_mark_inode_dirty
  - fs/ext4/super.c:perf_trace_ext4_nfs_commit_metadata
  - fs/ext4/super.c:perf_trace_ext4_drop_inode
  - fs/ext4/super.c:perf_trace_ext4_evict_inode
  - fs/ext4/super.c:perf_trace_ext4_allocate_inode
  - fs/ext4/super.c:perf_trace_ext4_request_inode
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
```
```
In fs/jbd2/journal.c (ffffffff813dd6cf)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/jbd2/journal.c:perf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:perf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:perf_trace_jbd2_update_log_tail
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_run_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_extend
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_start
  - fs/jbd2/journal.c:perf_trace_jbd2_submit_inode_data
  - fs/jbd2/journal.c:perf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint
```
```
In security/selinux/avc.c (ffffffff8144150a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_get_hash_stats
```
```
In block/blk-core.c (ffffffff814c9f21)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_unplug
  - block/blk-core.c:perf_trace_block_plug
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_buffer
```
```
In block/blk-ioc.c (ffffffff814d0f70)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff814f1642)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In block/blk-wbt.c (ffffffff814fb038)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In arch/x86/lib/msr.c (ffffffff8153c6f4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff81548d84)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (ffffffff8162f4e0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff8165684e)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff81699234)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/char/random.c:perf_trace_urandom_read
  - drivers/char/random.c:perf_trace_random_read
  - drivers/char/random.c:perf_trace_random__extract_entropy
  - drivers/char/random.c:perf_trace_random__get_random_bytes
  - drivers/char/random.c:perf_trace_xfer_secondary_pool
  - drivers/char/random.c:perf_trace_add_disk_randomness
  - drivers/char/random.c:perf_trace_add_input_randomness
  - drivers/char/random.c:perf_trace_debit_entropy
  - drivers/char/random.c:perf_trace_push_to_pool
  - drivers/char/random.c:perf_trace_credit_entropy_bits
  - drivers/char/random.c:perf_trace_random__mix_pool_bytes
  - drivers/char/random.c:perf_trace_add_device_randomness
```
```
In drivers/iommu/iommu-traces.c (ffffffff816b974c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff816fadaf)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81742e07)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81745862)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff81746d8a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff8176940a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff8178f32d)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81799dec)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81817a2a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_dbc_log_request
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_slot_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ep_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_free_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_trb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
```
```
In drivers/rtc/interface.c (ffffffff8183453a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/rtc/interface.c:perf_trace_rtc_timer_class
  - drivers/rtc/interface.c:perf_trace_rtc_offset_class
  - drivers/rtc/interface.c:perf_trace_rtc_alarm_irq_enable
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_state
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_freq
  - drivers/rtc/interface.c:perf_trace_rtc_time_alarm_class
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8183a134)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8183deac)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff818537ff)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff818557f8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (ffffffff8185a34c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff818a1ef4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffffffff818bed9a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_cmd_class
```
```
In drivers/devfreq/devfreq.c (ffffffff818c77c2)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
```
```
In drivers/ras/ras.c (ffffffff818ce8c4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_memory_failure_event
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_non_standard_event
  - drivers/ras/ras.c:perf_trace_arm_event
  - drivers/ras/ras.c:perf_trace_mc_event
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
```
```
In net/core/net-traces.c (ffffffff8193e627)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:perf_trace_neigh_create
  - net/core/net-traces.c:perf_trace_page_pool_state_hold
  - net/core/net-traces.c:perf_trace_page_pool_state_release
  - net/core/net-traces.c:perf_trace_page_pool_inflight
  - net/core/net-traces.c:perf_trace_br_fdb_update
  - net/core/net-traces.c:perf_trace_fdb_delete
  - net/core/net-traces.c:perf_trace_br_fdb_external_learn_add
  - net/core/net-traces.c:perf_trace_br_fdb_add
  - net/core/net-traces.c:perf_trace_qdisc_dequeue
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_rcvqueue_full
  - net/core/net-traces.c:perf_trace_napi_poll
  - net/core/net-traces.c:perf_trace_net_dev_rx_exit_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_template
  - net/core/net-traces.c:perf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:perf_trace_net_dev_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:perf_trace_consume_skb
  - net/core/net-traces.c:perf_trace_kfree_skb
```
```
In net/core/devlink.c (ffffffff81949f80)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/core/bpf_sk_storage.c (ffffffff819530e1)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_update
```
```
In net/bpf/test_run.c (ffffffff8196cf8a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv4/inet_hashtables.c (ffffffff81983540)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81984bd2)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a2ca4)
Location: include/linux/list.h:752
Inline: True
```
```
In net/ipv4/raw.c (ffffffff819abcac)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819af1c7)
Location: include/linux/list.h:752
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff819ce045)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e9ffe)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff819f41b4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
```
```
In net/unix/af_unix.c (ffffffff819f8ef0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/anycast.c (ffffffff81a0047d)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_anycast_cleanup
```
```
In net/ipv6/addrconf.c (ffffffff81a111f8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
```
```
In net/ipv6/route.c (ffffffff81a12447)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
```
In net/ipv6/raw.c (ffffffff81a2de7d)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffff81a53520)
Location: include/linux/list.h:752
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81a748d5)
Location: include/linux/list.h:752
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
In init/main.c (ffffffff8100220f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/common.c (ffffffff810038cf)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004f3a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff8102a2df)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_set_ldt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_gdt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_load_idt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_one_user
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_alloc_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pte_at
  - arch/x86/xen/trace.c:perf_trace_xen_mmu__set_pte
  - arch/x86/xen/trace.c:perf_trace_xen_mc_extend_args
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush_reason
  - arch/x86/xen/trace.c:perf_trace_xen_mc_callback
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry_alloc
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mc__batch
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102e111)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/irq.c (ffffffff81033368)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:perf_trace_vector_free_moved
  - arch/x86/kernel/irq.c:perf_trace_vector_setup
  - arch/x86/kernel/irq.c:perf_trace_vector_teardown
  - arch/x86/kernel/irq.c:perf_trace_vector_activate
  - arch/x86/kernel/irq.c:perf_trace_vector_alloc_managed
  - arch/x86/kernel/irq.c:perf_trace_vector_alloc
  - arch/x86/kernel/irq.c:perf_trace_vector_reserve
  - arch/x86/kernel/irq.c:perf_trace_vector_mod
  - arch/x86/kernel/irq.c:perf_trace_vector_config
  - arch/x86/kernel/irq.c:perf_trace_x86_irq_vector
```
```
In arch/x86/kernel/nmi.c (ffffffff81035de4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103e1da)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c74a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105f98f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/init.c (ffffffff8107da0f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff8107f764)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff8108d38a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:perf_trace_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:perf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:perf_trace_bounds_exception_mpx
  - arch/x86/mm/mpx.c:perf_trace_mpx_bounds_register_exception
```
```
In kernel/fork.c (ffffffff8109c9e0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff810a37af)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/exit.c (ffffffff810a597d)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/softirq.c (ffffffff810a744a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810af5d4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810bf47a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/pid.c (ffffffff810c5f44)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/sched/core.c (ffffffff810d0f2a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_wake_idle_without_ipi
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:perf_trace_sched_process_hang
  - kernel/sched/core.c:perf_trace_sched_pi_setprio
  - kernel/sched/core.c:perf_trace_sched_stat_runtime
  - kernel/sched/core.c:perf_trace_sched_process_exec
  - kernel/sched/core.c:perf_trace_sched_process_fork
  - kernel/sched/core.c:perf_trace_sched_process_wait
  - kernel/sched/core.c:perf_trace_sched_process_template
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:perf_trace_sched_kthread_stop_ret
  - kernel/sched/core.c:perf_trace_sched_kthread_stop
```
```
In kernel/printk/printk.c (ffffffff81111924)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff81122503)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff8112358a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff8112fc48)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/time/timer.c (ffffffff81137008)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:perf_trace_tick_stop
  - kernel/time/timer.c:perf_trace_itimer_expire
  - kernel/time/timer.c:perf_trace_itimer_state
  - kernel/time/timer.c:perf_trace_hrtimer_class
  - kernel/time/timer.c:perf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:perf_trace_hrtimer_start
  - kernel/time/timer.c:perf_trace_hrtimer_init
  - kernel/time/timer.c:perf_trace_timer_expire_entry
  - kernel/time/timer.c:perf_trace_timer_start
  - kernel/time/timer.c:perf_trace_timer_class
```
```
In kernel/time/alarmtimer.c (ffffffff8113ecbf)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff811528f5)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff8115f4f1)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/kprobes.c (ffffffff811816cd)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/trace/ftrace.c (ffffffff811986c4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:profile_graph_return
```
```
In kernel/trace/trace_syscalls.c (ffffffff811bde96)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811d16bf)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/power-traces.c (ffffffff811d33f4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:perf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:perf_trace_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_power_domain
  - kernel/trace/power-traces.c:perf_trace_clock
  - kernel/trace/power-traces.c:perf_trace_wakeup_source
  - kernel/trace/power-traces.c:perf_trace_suspend_resume
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:perf_trace_cpu_frequency_limits
  - kernel/trace/power-traces.c:perf_trace_pstate_sample
  - kernel/trace/power-traces.c:perf_trace_powernv_throttle
  - kernel/trace/power-traces.c:perf_trace_cpu
```
```
In kernel/trace/rpm-traces.c (ffffffff811d4b93)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d8716)
Location: include/linux/list.h:752
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811dba3f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_mem_return_failed
  - kernel/bpf/core.c:perf_trace_mem_connect
  - kernel/bpf/core.c:perf_trace_mem_disconnect
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_bulk_tx
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/events/core.c (ffffffff8120b7c5)
Location: include/linux/list.h:752
Inline: True
```
```
In kernel/user-return-notifier.c (ffffffff8121cec2)
Location: include/linux/list.h:752
Inline: True
```
```
In kernel/rseq.c (ffffffff8121f768)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff812208bf)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff8122855b)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:perf_trace_skip_task_reaping
  - mm/oom_kill.c:perf_trace_finish_task_reaping
  - mm/oom_kill.c:perf_trace_start_task_reaping
  - mm/oom_kill.c:perf_trace_wake_reaper
  - mm/oom_kill.c:perf_trace_mark_victim
  - mm/oom_kill.c:perf_trace_reclaim_retry_zone
  - mm/oom_kill.c:perf_trace_oom_score_adj_update
```
```
In mm/swap.c (ffffffff812304aa)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff81235824)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/vmscan.c:perf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:perf_trace_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_isolate
  - mm/vmscan.c:perf_trace_mm_shrink_slab_end
  - mm/vmscan.c:perf_trace_mm_shrink_slab_start
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_end_template
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:perf_trace_mm_vmscan_wakeup_kswapd
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_wake
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_sleep
```
```
In mm/percpu.c (ffffffff8124ae0a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff8124e43b)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:perf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:perf_trace_mm_page
  - mm/slab_common.c:perf_trace_mm_page_alloc
  - mm/slab_common.c:perf_trace_mm_page_free_batched
  - mm/slab_common.c:perf_trace_mm_page_free
  - mm/slab_common.c:perf_trace_kmem_free
  - mm/slab_common.c:perf_trace_kmem_alloc_node
  - mm/slab_common.c:perf_trace_kmem_alloc
```
```
In mm/compaction.c (ffffffff812516c4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/compaction.c:perf_trace_kcompactd_wake_template
  - mm/compaction.c:perf_trace_mm_compaction_kcompactd_sleep
  - mm/compaction.c:perf_trace_mm_compaction_defer_template
  - mm/compaction.c:perf_trace_mm_compaction_suitable_template
  - mm/compaction.c:perf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:perf_trace_mm_compaction_end
  - mm/compaction.c:perf_trace_mm_compaction_begin
  - mm/compaction.c:perf_trace_mm_compaction_migratepages
  - mm/compaction.c:perf_trace_mm_compaction_isolate_template
```
```
In mm/mmu_notifier.c (ffffffff8129e414)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_mm_destroy
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (ffffffff812a15d4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
```
```
In mm/migrate.c (ffffffff812acd48)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff812ba4e8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff812cd334)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffffffff812d1194)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffffffff812d88fe)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/super.c (ffffffff812e168b)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/super.c:reconfigure_super
```
```
In fs/dcache.c (ffffffff812f9eb7)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_find_any_alias
```
```
In fs/namespace.c (ffffffff8130563f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:namespace_unlock
```
```
In fs/seq_file.c (ffffffff8130883c)
Location: include/linux/list.h:752
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8130e1ba)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_writeback_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_congest_waited_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_pages_written
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
```
```
In fs/notify/mark.c (ffffffff8132df11)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/dax.c (ffffffff813465d4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/dax.c:perf_trace_dax_writeback_one
  - fs/dax.c:perf_trace_dax_writeback_range_class
  - fs/dax.c:perf_trace_dax_insert_mapping
  - fs/dax.c:perf_trace_dax_pte_fault_class
  - fs/dax.c:perf_trace_dax_pmd_insert_mapping_class
  - fs/dax.c:perf_trace_dax_pmd_load_hole_class
  - fs/dax.c:perf_trace_dax_pmd_fault_class
```
```
In fs/locks.c (ffffffff81352533)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffff813d5d74)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_error
  - fs/ext4/super.c:perf_trace_ext4_shutdown
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:perf_trace_ext4_insert_range
  - fs/ext4/super.c:perf_trace_ext4_collapse_range
  - fs/ext4/super.c:perf_trace_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:perf_trace_ext4__es_shrink_enter
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_enter
  - fs/ext4/super.c:perf_trace_ext4_es_remove_extent
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_idx
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_show_extent
  - fs/ext4/super.c:perf_trace_ext4_get_reserved_cluster_alloc
  - fs/ext4/super.c:perf_trace_ext4_find_delalloc_range
  - fs/ext4/super.c:perf_trace_ext4_ext_in_cache
  - fs/ext4/super.c:perf_trace_ext4_ext_put_in_cache
  - fs/ext4/super.c:perf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:perf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:perf_trace_ext4__trim
  - fs/ext4/super.c:perf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:perf_trace_ext4_journal_start
  - fs/ext4/super.c:perf_trace_ext4_load_inode
  - fs/ext4/super.c:perf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_exit
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_enter
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:perf_trace_ext4__truncate
  - fs/ext4/super.c:perf_trace_ext4_unlink_exit
  - fs/ext4/super.c:perf_trace_ext4_unlink_enter
  - fs/ext4/super.c:perf_trace_ext4_fallocate_exit
  - fs/ext4/super.c:perf_trace_ext4__fallocate_mode
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_exit
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_enter
  - fs/ext4/super.c:perf_trace_ext4__bitmap_load
  - fs/ext4/super.c:perf_trace_ext4_da_release_space
  - fs/ext4/super.c:perf_trace_ext4_da_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_da_update_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_forget
  - fs/ext4/super.c:perf_trace_ext4__mballoc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_prealloc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_alloc
  - fs/ext4/super.c:perf_trace_ext4_alloc_da_blocks
  - fs/ext4/super.c:perf_trace_ext4_sync_fs
  - fs/ext4/super.c:perf_trace_ext4_sync_file_exit
  - fs/ext4/super.c:perf_trace_ext4_sync_file_enter
  - fs/ext4/super.c:perf_trace_ext4_free_blocks
  - fs/ext4/super.c:perf_trace_ext4_allocate_blocks
  - fs/ext4/super.c:perf_trace_ext4_request_blocks
  - fs/ext4/super.c:perf_trace_ext4_mb_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_mb_release_group_pa
  - fs/ext4/super.c:perf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:perf_trace_ext4__mb_new_pa
  - fs/ext4/super.c:perf_trace_ext4_discard_blocks
  - fs/ext4/super.c:perf_trace_ext4_invalidatepage_op
  - fs/ext4/super.c:perf_trace_ext4__page_op
  - fs/ext4/super.c:perf_trace_ext4_writepages_result
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages_extent
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages
  - fs/ext4/super.c:perf_trace_ext4_writepages
  - fs/ext4/super.c:perf_trace_ext4__write_end
  - fs/ext4/super.c:perf_trace_ext4__write_begin
  - fs/ext4/super.c:perf_trace_ext4_begin_ordered_truncate
  - fs/ext4/super.c:perf_trace_ext4_mark_inode_dirty
  - fs/ext4/super.c:perf_trace_ext4_nfs_commit_metadata
  - fs/ext4/super.c:perf_trace_ext4_drop_inode
  - fs/ext4/super.c:perf_trace_ext4_evict_inode
  - fs/ext4/super.c:perf_trace_ext4_allocate_inode
  - fs/ext4/super.c:perf_trace_ext4_request_inode
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
```
```
In fs/jbd2/journal.c (ffffffff813f771f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/jbd2/journal.c:perf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:perf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:perf_trace_jbd2_update_log_tail
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_run_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_extend
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_start
  - fs/jbd2/journal.c:perf_trace_jbd2_submit_inode_data
  - fs/jbd2/journal.c:perf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint
```
```
In security/selinux/avc.c (ffffffff8145adea)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_get_hash_stats
```
```
In block/blk-core.c (ffffffff814e3101)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_unplug
  - block/blk-core.c:perf_trace_block_plug
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_buffer
```
```
In block/blk-ioc.c (ffffffff814ea330)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff8150ac32)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In block/blk-iocost.c (ffffffff815114fe)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_activate
```
```
In block/blk-wbt.c (ffffffff81518f78)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In arch/x86/lib/msr.c (ffffffff8155d504)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff81569e04)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (ffffffff81651034)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff81679d8e)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff816bbe44)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/char/random.c:perf_trace_urandom_read
  - drivers/char/random.c:perf_trace_random_read
  - drivers/char/random.c:perf_trace_random__extract_entropy
  - drivers/char/random.c:perf_trace_random__get_random_bytes
  - drivers/char/random.c:perf_trace_xfer_secondary_pool
  - drivers/char/random.c:perf_trace_add_disk_randomness
  - drivers/char/random.c:perf_trace_add_input_randomness
  - drivers/char/random.c:perf_trace_debit_entropy
  - drivers/char/random.c:perf_trace_push_to_pool
  - drivers/char/random.c:perf_trace_credit_entropy_bits
  - drivers/char/random.c:perf_trace_random__mix_pool_bytes
  - drivers/char/random.c:perf_trace_add_device_randomness
```
```
In drivers/iommu/iommu-traces.c (ffffffff816dc53c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/iommu/intel-trace.c (ffffffff816f1124)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/iommu/intel-trace.c:perf_trace_dma_unmap
  - drivers/iommu/intel-trace.c:perf_trace_dma_map
```
```
In drivers/base/regmap/regmap.c (ffffffff8171f15f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81766dd7)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff817699e2)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff8176aeda)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff8178d46a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff817b2eed)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff817bd8bc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81848d6a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_dbc_log_request
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_slot_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ep_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_free_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_trb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
```
```
In drivers/rtc/interface.c (ffffffff81865e8a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/rtc/interface.c:perf_trace_rtc_timer_class
  - drivers/rtc/interface.c:perf_trace_rtc_offset_class
  - drivers/rtc/interface.c:perf_trace_rtc_alarm_irq_enable
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_state
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_freq
  - drivers/rtc/interface.c:perf_trace_rtc_time_alarm_class
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8186baa4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8186f84c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff8188526f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff81887258)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (ffffffff8188be5c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff818d41f4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffffffff818f18ea)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_cmd_class
```
```
In drivers/devfreq/devfreq.c (ffffffff818f9ca2)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
```
```
In drivers/ras/ras.c (ffffffff81900cb4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_memory_failure_event
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_non_standard_event
  - drivers/ras/ras.c:perf_trace_arm_event
  - drivers/ras/ras.c:perf_trace_mc_event
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
```
```
In net/core/net-traces.c (ffffffff819714b7)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:perf_trace_neigh_create
  - net/core/net-traces.c:perf_trace_page_pool_state_hold
  - net/core/net-traces.c:perf_trace_page_pool_state_release
  - net/core/net-traces.c:perf_trace_page_pool_inflight
  - net/core/net-traces.c:perf_trace_br_fdb_update
  - net/core/net-traces.c:perf_trace_fdb_delete
  - net/core/net-traces.c:perf_trace_br_fdb_external_learn_add
  - net/core/net-traces.c:perf_trace_br_fdb_add
  - net/core/net-traces.c:perf_trace_qdisc_dequeue
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_rcvqueue_full
  - net/core/net-traces.c:perf_trace_napi_poll
  - net/core/net-traces.c:perf_trace_net_dev_rx_exit_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_template
  - net/core/net-traces.c:perf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:perf_trace_net_dev_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:perf_trace_consume_skb
  - net/core/net-traces.c:perf_trace_kfree_skb
```
```
In net/core/devlink.c (ffffffff8197f9d0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/core/bpf_sk_storage.c (ffffffff81989c15)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_update
```
```
In net/bpf/test_run.c (ffffffff819a38aa)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b9db6)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bb645)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/raw.c (ffffffff819e295c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819e5ed7)
Location: include/linux/list.h:752
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff81a04b0c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2104a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2b080)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
```
```
In net/unix/af_unix.c (ffffffff81a2fb40)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/anycast.c (ffffffff81a3706a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_anycast_cleanup
```
```
In net/ipv6/addrconf.c (ffffffff81a47f66)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
```
```
In net/ipv6/route.c (ffffffff81a49037)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
```
In net/ipv6/raw.c (ffffffff81a649ed)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffff81a8a110)
Location: include/linux/list.h:752
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81aab7e5)
Location: include/linux/list.h:752
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
In init/main.c (ffffffff810032c8)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/common.c (ffffffff81004c1a)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005ed9)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff8102c268)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_set_ldt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_gdt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_load_idt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_one_user
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_alloc_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pte_at
  - arch/x86/xen/trace.c:perf_trace_xen_mmu__set_pte
  - arch/x86/xen/trace.c:perf_trace_xen_mc_extend_args
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush_reason
  - arch/x86/xen/trace.c:perf_trace_xen_mc_callback
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry_alloc
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mc__batch
```
```
In arch/x86/hyperv/mmu.c (ffffffff81030448)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_one
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/irq.c (ffffffff8103523e)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:perf_trace_vector_free_moved
  - arch/x86/kernel/irq.c:perf_trace_vector_setup
  - arch/x86/kernel/irq.c:perf_trace_vector_teardown
  - arch/x86/kernel/irq.c:perf_trace_vector_activate
  - arch/x86/kernel/irq.c:perf_trace_vector_alloc_managed
  - arch/x86/kernel/irq.c:perf_trace_vector_alloc
  - arch/x86/kernel/irq.c:perf_trace_vector_reserve
  - arch/x86/kernel/irq.c:perf_trace_vector_mod
  - arch/x86/kernel/irq.c:perf_trace_vector_config
  - arch/x86/kernel/irq.c:perf_trace_x86_irq_vector
```
```
In arch/x86/kernel/nmi.c (ffffffff81037e82)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff810416fa)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105109a)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810654f8)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/init.c (ffffffff81084148)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff810867da)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In kernel/fork.c (ffffffff810a3b3c)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_show_fdinfo
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff810aa84f)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/exit.c (ffffffff810ad49d)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/softirq.c (ffffffff810aec19)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810b7392)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810c68a8)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_end
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_activate_work
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
```
```
In kernel/pid.c (ffffffff810cd738)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:__change_pid
```
```
In kernel/sched/core.c (ffffffff810dacf9)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_wake_idle_without_ipi
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:perf_trace_sched_process_hang
  - kernel/sched/core.c:perf_trace_sched_pi_setprio
  - kernel/sched/core.c:perf_trace_sched_stat_runtime
  - kernel/sched/core.c:perf_trace_sched_process_exec
  - kernel/sched/core.c:perf_trace_sched_process_fork
  - kernel/sched/core.c:perf_trace_sched_process_wait
  - kernel/sched/core.c:perf_trace_sched_process_template
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:perf_trace_sched_kthread_stop_ret
  - kernel/sched/core.c:perf_trace_sched_kthread_stop
```
```
In kernel/printk/printk.c (ffffffff8111d0e3)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff8112ec0d)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff8112fc89)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff8113eb23)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/time/timer.c (ffffffff81145cbb)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:perf_trace_tick_stop
  - kernel/time/timer.c:perf_trace_itimer_expire
  - kernel/time/timer.c:perf_trace_itimer_state
  - kernel/time/timer.c:perf_trace_hrtimer_class
  - kernel/time/timer.c:perf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:perf_trace_hrtimer_start
  - kernel/time/timer.c:perf_trace_hrtimer_init
  - kernel/time/timer.c:perf_trace_timer_expire_entry
  - kernel/time/timer.c:perf_trace_timer_start
  - kernel/time/timer.c:perf_trace_timer_class
```
```
In kernel/time/alarmtimer.c (ffffffff8114df57)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81152788)
Location: include/linux/list.h:801
Inline: True
```
```
In kernel/module.c (ffffffff81164254)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff8116faba)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/kprobes.c (ffffffff8119510d)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/trace/ftrace.c (ffffffff811ad226)
Location: include/linux/list.h:801
Inline: True
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d7c98)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811ed1a1)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/power-traces.c (ffffffff811efec1)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:perf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update
  - kernel/trace/power-traces.c:perf_trace_cpu_latency_qos_request
  - kernel/trace/power-traces.c:perf_trace_power_domain
  - kernel/trace/power-traces.c:perf_trace_clock
  - kernel/trace/power-traces.c:perf_trace_wakeup_source
  - kernel/trace/power-traces.c:perf_trace_suspend_resume
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:perf_trace_cpu_frequency_limits
  - kernel/trace/power-traces.c:perf_trace_pstate_sample
  - kernel/trace/power-traces.c:perf_trace_powernv_throttle
  - kernel/trace/power-traces.c:perf_trace_cpu
```
```
In kernel/trace/rpm-traces.c (ffffffff811f127e)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f47aa)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/core.c (ffffffff811f8681)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_mem_return_failed
  - kernel/bpf/core.c:perf_trace_mem_connect
  - kernel/bpf/core.c:perf_trace_mem_disconnect
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_bulk_tx
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/bpf/trampoline.c (ffffffff8121f0f5)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_put
  - kernel/bpf/trampoline.c:bpf_trampoline_put
```
```
In kernel/events/core.c (ffffffff81237505)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - kernel/events/core.c:perf_trace_run_bpf_submit
```
```
In kernel/user-return-notifier.c (ffffffff81249242)
Location: include/linux/list.h:801
Inline: True
```
```
In kernel/rseq.c (ffffffff8124bacf)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In kernel/watch_queue.c (ffffffff8124d3b6)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
```
```
In mm/filemap.c (ffffffff8124dd30)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff81254fd8)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:perf_trace_skip_task_reaping
  - mm/oom_kill.c:perf_trace_finish_task_reaping
  - mm/oom_kill.c:perf_trace_start_task_reaping
  - mm/oom_kill.c:perf_trace_wake_reaper
  - mm/oom_kill.c:perf_trace_mark_victim
  - mm/oom_kill.c:perf_trace_reclaim_retry_zone
  - mm/oom_kill.c:perf_trace_oom_score_adj_update
```
```
In mm/swap.c (ffffffff8125d7ed)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff81262f42)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - mm/vmscan.c:perf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:perf_trace_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_isolate
  - mm/vmscan.c:perf_trace_mm_shrink_slab_end
  - mm/vmscan.c:perf_trace_mm_shrink_slab_start
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_end_template
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:perf_trace_mm_vmscan_wakeup_kswapd
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_wake
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_sleep
```
```
In mm/percpu.c (ffffffff81278d49)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff8127d93a)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - mm/slab_common.c:perf_trace_rss_stat
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:perf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:perf_trace_mm_page
  - mm/slab_common.c:perf_trace_mm_page_alloc
  - mm/slab_common.c:perf_trace_mm_page_free_batched
  - mm/slab_common.c:perf_trace_mm_page_free
  - mm/slab_common.c:perf_trace_kmem_free
  - mm/slab_common.c:perf_trace_kmem_alloc_node
  - mm/slab_common.c:perf_trace_kmem_alloc
```
```
In mm/compaction.c (ffffffff8127fe72)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - mm/compaction.c:perf_trace_kcompactd_wake_template
  - mm/compaction.c:perf_trace_mm_compaction_kcompactd_sleep
  - mm/compaction.c:perf_trace_mm_compaction_defer_template
  - mm/compaction.c:perf_trace_mm_compaction_suitable_template
  - mm/compaction.c:perf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:perf_trace_mm_compaction_end
  - mm/compaction.c:perf_trace_mm_compaction_begin
  - mm/compaction.c:perf_trace_mm_compaction_migratepages
  - mm/compaction.c:perf_trace_mm_compaction_isolate_template
```
```
In mm/mmap.c (ffffffff812983f4)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - mm/mmap.c:perf_trace_vm_unmapped_area
```
```
In mm/mmu_notifier.c (ffffffff812d2a14)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_subscriptions_destroy
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_release
  - mm/mmu_notifier.c:mn_hlist_release
```
```
In mm/ksm.c (ffffffff812d335a)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
```
```
In mm/migrate.c (ffffffff812e1e8d)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff812ef19d)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff81303624)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In fs/super.c (ffffffff81318a03)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - fs/super.c:reconfigure_super
```
```
In fs/dcache.c (ffffffff813330c1)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_find_alias
  - fs/dcache.c:d_find_alias
```
```
In fs/namespace.c (ffffffff8133ef7c)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:namespace_unlock
```
```
In fs/seq_file.c (ffffffff81341a1c)
Location: include/linux/list.h:801
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81347ac9)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_writeback_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_congest_waited_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_pages_written
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
```
```
In fs/notify/mark.c (ffffffff813675d2)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/io_uring.c (ffffffff8137a634)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - fs/io_uring.c:perf_trace_io_uring_task_run
  - fs/io_uring.c:perf_trace_io_uring_task_add
  - fs/io_uring.c:perf_trace_io_uring_poll_wake
  - fs/io_uring.c:perf_trace_io_uring_poll_arm
  - fs/io_uring.c:perf_trace_io_uring_submit_sqe
  - fs/io_uring.c:perf_trace_io_uring_complete
  - fs/io_uring.c:perf_trace_io_uring_fail_link
  - fs/io_uring.c:perf_trace_io_uring_cqring_wait
  - fs/io_uring.c:perf_trace_io_uring_link
  - fs/io_uring.c:perf_trace_io_uring_defer
  - fs/io_uring.c:perf_trace_io_uring_queue_async_work
  - fs/io_uring.c:perf_trace_io_uring_file_get
  - fs/io_uring.c:perf_trace_io_uring_register
  - fs/io_uring.c:perf_trace_io_uring_create
```
```
In fs/dax.c (ffffffff8138be82)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - fs/dax.c:perf_trace_dax_writeback_one
  - fs/dax.c:perf_trace_dax_writeback_range_class
  - fs/dax.c:perf_trace_dax_insert_mapping
  - fs/dax.c:perf_trace_dax_pte_fault_class
  - fs/dax.c:perf_trace_dax_pmd_insert_mapping_class
  - fs/dax.c:perf_trace_dax_pmd_load_hole_class
  - fs/dax.c:perf_trace_dax_pmd_fault_class
```
```
In fs/locks.c (ffffffff81398fa0)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/iomap/trace.c (ffffffff813a923c)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - fs/iomap/trace.c:perf_trace_iomap_apply
  - fs/iomap/trace.c:perf_trace_iomap_class
  - fs/iomap/trace.c:perf_trace_iomap_range_class
  - fs/iomap/trace.c:perf_trace_iomap_readpage_class
```
```
In fs/ext4/super.c (ffffffff81422526)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_error
  - fs/ext4/super.c:perf_trace_ext4_shutdown
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:perf_trace_ext4_insert_range
  - fs/ext4/super.c:perf_trace_ext4_collapse_range
  - fs/ext4/super.c:perf_trace_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:perf_trace_ext4__es_shrink_enter
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_enter
  - fs/ext4/super.c:perf_trace_ext4_es_remove_extent
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_idx
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_show_extent
  - fs/ext4/super.c:perf_trace_ext4_get_reserved_cluster_alloc
  - fs/ext4/super.c:perf_trace_ext4_find_delalloc_range
  - fs/ext4/super.c:perf_trace_ext4_ext_in_cache
  - fs/ext4/super.c:perf_trace_ext4_ext_put_in_cache
  - fs/ext4/super.c:perf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:perf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:perf_trace_ext4__trim
  - fs/ext4/super.c:perf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:perf_trace_ext4_journal_start
  - fs/ext4/super.c:perf_trace_ext4_load_inode
  - fs/ext4/super.c:perf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_exit
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_enter
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:perf_trace_ext4__truncate
  - fs/ext4/super.c:perf_trace_ext4_unlink_exit
  - fs/ext4/super.c:perf_trace_ext4_unlink_enter
  - fs/ext4/super.c:perf_trace_ext4_fallocate_exit
  - fs/ext4/super.c:perf_trace_ext4__fallocate_mode
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_exit
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_enter
  - fs/ext4/super.c:perf_trace_ext4__bitmap_load
  - fs/ext4/super.c:perf_trace_ext4_da_release_space
  - fs/ext4/super.c:perf_trace_ext4_da_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_da_update_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_forget
  - fs/ext4/super.c:perf_trace_ext4__mballoc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_prealloc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_alloc
  - fs/ext4/super.c:perf_trace_ext4_alloc_da_blocks
  - fs/ext4/super.c:perf_trace_ext4_sync_fs
  - fs/ext4/super.c:perf_trace_ext4_sync_file_exit
  - fs/ext4/super.c:perf_trace_ext4_sync_file_enter
  - fs/ext4/super.c:perf_trace_ext4_free_blocks
  - fs/ext4/super.c:perf_trace_ext4_allocate_blocks
  - fs/ext4/super.c:perf_trace_ext4_request_blocks
  - fs/ext4/super.c:perf_trace_ext4_mb_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_mb_release_group_pa
  - fs/ext4/super.c:perf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:perf_trace_ext4__mb_new_pa
  - fs/ext4/super.c:perf_trace_ext4_discard_blocks
  - fs/ext4/super.c:perf_trace_ext4_invalidatepage_op
  - fs/ext4/super.c:perf_trace_ext4__page_op
  - fs/ext4/super.c:perf_trace_ext4_writepages_result
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages_extent
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages
  - fs/ext4/super.c:perf_trace_ext4_writepages
  - fs/ext4/super.c:perf_trace_ext4__write_end
  - fs/ext4/super.c:perf_trace_ext4__write_begin
  - fs/ext4/super.c:perf_trace_ext4_begin_ordered_truncate
  - fs/ext4/super.c:perf_trace_ext4_mark_inode_dirty
  - fs/ext4/super.c:perf_trace_ext4_nfs_commit_metadata
  - fs/ext4/super.c:perf_trace_ext4_drop_inode
  - fs/ext4/super.c:perf_trace_ext4_evict_inode
  - fs/ext4/super.c:perf_trace_ext4_allocate_inode
  - fs/ext4/super.c:perf_trace_ext4_request_inode
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
```
```
In fs/jbd2/journal.c (ffffffff81444bd8)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - fs/jbd2/journal.c:perf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:perf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:perf_trace_jbd2_update_log_tail
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_run_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_extend
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_start_class
  - fs/jbd2/journal.c:perf_trace_jbd2_submit_inode_data
  - fs/jbd2/journal.c:perf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint
```
```
In security/selinux/avc.c (ffffffff814ae0f0)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_get_hash_stats
```
```
In block/blk-core.c (ffffffff81541c65)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_unplug
  - block/blk-core.c:perf_trace_block_plug
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_buffer
```
```
In block/blk-ioc.c (ffffffff815493c0)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - block/blk-ioc.c:put_io_context
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff8156bc82)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In block/blk-iocost.c (ffffffff815721b4)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_activate
```
```
In block/blk-wbt.c (ffffffff81579651)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In arch/x86/lib/msr.c (ffffffff815e6eb2)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff8160c7f2)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/pwm/core.c (ffffffff8161aed2)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - drivers/pwm/core.c:perf_trace_pwm
```
```
In drivers/clk/clk.c (ffffffff81700810)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff81728ce5)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff81770262)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - drivers/char/random.c:perf_trace_urandom_read
  - drivers/char/random.c:perf_trace_random_read
  - drivers/char/random.c:perf_trace_random__extract_entropy
  - drivers/char/random.c:perf_trace_random__get_random_bytes
  - drivers/char/random.c:perf_trace_xfer_secondary_pool
  - drivers/char/random.c:perf_trace_add_disk_randomness
  - drivers/char/random.c:perf_trace_add_input_randomness
  - drivers/char/random.c:perf_trace_debit_entropy
  - drivers/char/random.c:perf_trace_push_to_pool
  - drivers/char/random.c:perf_trace_credit_entropy_bits
  - drivers/char/random.c:perf_trace_random__mix_pool_bytes
  - drivers/char/random.c:perf_trace_add_device_randomness
```
```
In drivers/iommu/iommu-traces.c (ffffffff81791564)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/iommu/intel/trace.c (ffffffff817a8dd2)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - drivers/iommu/intel/trace.c:perf_trace_dma_map_sg
  - drivers/iommu/intel/trace.c:perf_trace_dma_unmap
  - drivers/iommu/intel/trace.c:perf_trace_dma_map
```
```
In drivers/base/regmap/regmap.c (ffffffff817dae9c)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
```
```
In drivers/dma-buf/dma-fence.c (ffffffff818265fc)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8182bc5f)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff8182d253)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff81851d99)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff818795d0)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff8188638d)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff8191b63a)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_dbc_log_request
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_doorbell
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_slot_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ep_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_free_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_trb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
```
```
In drivers/rtc/interface.c (ffffffff819398bd)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - drivers/rtc/interface.c:perf_trace_rtc_timer_class
  - drivers/rtc/interface.c:perf_trace_rtc_offset_class
  - drivers/rtc/interface.c:perf_trace_rtc_alarm_irq_enable
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_state
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_freq
  - drivers/rtc/interface.c:perf_trace_rtc_time_alarm_class
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8193f86b)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8194383f)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff81953897)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff81955713)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff8195aadc)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff819a6ae2)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffffffff819c7097)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_start
```
```
In drivers/devfreq/devfreq.c (ffffffff819d0212)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
```
```
In drivers/ras/ras.c (ffffffff819d7d62)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_memory_failure_event
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_non_standard_event
  - drivers/ras/ras.c:perf_trace_arm_event
  - drivers/ras/ras.c:perf_trace_mc_event
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
```
```
In drivers/interconnect/core.c (ffffffff819dbcd0)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_node_destroy
  - drivers/interconnect/core.c:perf_trace_icc_set_bw_end
  - drivers/interconnect/core.c:perf_trace_icc_set_bw
```
```
In net/core/net-traces.c (ffffffff81a450cc)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:perf_trace_neigh_create
  - net/core/net-traces.c:perf_trace_page_pool_update_nid
  - net/core/net-traces.c:perf_trace_page_pool_state_hold
  - net/core/net-traces.c:perf_trace_page_pool_state_release
  - net/core/net-traces.c:perf_trace_page_pool_release
  - net/core/net-traces.c:perf_trace_br_fdb_update
  - net/core/net-traces.c:perf_trace_fdb_delete
  - net/core/net-traces.c:perf_trace_br_fdb_external_learn_add
  - net/core/net-traces.c:perf_trace_br_fdb_add
  - net/core/net-traces.c:perf_trace_qdisc_create
  - net/core/net-traces.c:perf_trace_qdisc_destroy
  - net/core/net-traces.c:perf_trace_qdisc_reset
  - net/core/net-traces.c:perf_trace_qdisc_dequeue
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_rcvqueue_full
  - net/core/net-traces.c:perf_trace_napi_poll
  - net/core/net-traces.c:perf_trace_net_dev_rx_exit_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_template
  - net/core/net-traces.c:perf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:perf_trace_net_dev_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:perf_trace_consume_skb
  - net/core/net-traces.c:perf_trace_kfree_skb
```
```
In net/core/devlink.c (ffffffff81a51c6e)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/core/bpf_sk_storage.c (ffffffff81a61807)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put_all
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_update
```
```
In net/bpf/test_run.c (ffffffff81a7dfd0)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa46ba)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_put_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa748e)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse
```
```
In net/ipv4/raw.c (ffffffff81acff4b)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81ad255c)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_first
```
```
In net/ipv4/fib_trie.c (ffffffff81af454d)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b13f54)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1d350)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
```
```
In net/unix/af_unix.c (ffffffff81b23bcc)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/anycast.c (ffffffff81b2c2e3)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_anycast_cleanup
```
```
In net/ipv6/addrconf.c (ffffffff81b3ea3f)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
```
```
In net/ipv6/route.c (ffffffff81b3fcd9)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
```
In net/ipv6/raw.c (ffffffff81b5d339)
Location: include/linux/list.h:801
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/packet/af_packet.c (ffffffff81b85aa0)
Location: include/linux/list.h:801
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81ba6eb5)
Location: include/linux/list.h:801
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
In init/main.c (ffffffff81003388)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005089)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff8102d218)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_set_ldt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_gdt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_load_idt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_one_user
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_alloc_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu__set_pte
  - arch/x86/xen/trace.c:perf_trace_xen_mc_extend_args
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush_reason
  - arch/x86/xen/trace.c:perf_trace_xen_mc_callback
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry_alloc
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mc__batch
```
```
In arch/x86/hyperv/mmu.c (ffffffff810311b8)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_one
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/irq.c (ffffffff8103644e)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:perf_trace_vector_free_moved
  - arch/x86/kernel/irq.c:perf_trace_vector_setup
  - arch/x86/kernel/irq.c:perf_trace_vector_teardown
  - arch/x86/kernel/irq.c:perf_trace_vector_activate
  - arch/x86/kernel/irq.c:perf_trace_vector_alloc_managed
  - arch/x86/kernel/irq.c:perf_trace_vector_alloc
  - arch/x86/kernel/irq.c:perf_trace_vector_reserve
  - arch/x86/kernel/irq.c:perf_trace_vector_mod
  - arch/x86/kernel/irq.c:perf_trace_vector_config
  - arch/x86/kernel/irq.c:perf_trace_x86_irq_vector
```
```
In arch/x86/kernel/nmi.c (ffffffff810389c2)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8104179a)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105036a)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810637a8)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/init.c (ffffffff81085698)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff810870ca)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In kernel/fork.c (ffffffff8109f28c)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_show_fdinfo
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff810a60df)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/exit.c (ffffffff810a8b6d)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/softirq.c (ffffffff810aa3e9)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810b2622)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810c1938)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_end
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_activate_work
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
```
```
In kernel/pid.c (ffffffff810c827f)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:__change_pid
```
```
In kernel/sched/core.c (ffffffff810d7279)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_wake_idle_without_ipi
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:perf_trace_sched_process_hang
  - kernel/sched/core.c:perf_trace_sched_pi_setprio
  - kernel/sched/core.c:perf_trace_sched_stat_runtime
  - kernel/sched/core.c:perf_trace_sched_process_exec
  - kernel/sched/core.c:perf_trace_sched_process_fork
  - kernel/sched/core.c:perf_trace_sched_process_wait
  - kernel/sched/core.c:perf_trace_sched_process_template
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:perf_trace_sched_kthread_work_execute_end
  - kernel/sched/core.c:perf_trace_sched_kthread_work_execute_start
  - kernel/sched/core.c:perf_trace_sched_kthread_work_queue_work
  - kernel/sched/core.c:perf_trace_sched_kthread_stop_ret
  - kernel/sched/core.c:perf_trace_sched_kthread_stop
```
```
In kernel/printk/printk.c (ffffffff81117bb3)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff8112abed)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff8112bae9)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff8113a193)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/entry/common.c (ffffffff8113b25a)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/entry/common.c:perf_trace_sys_exit
  - kernel/entry/common.c:perf_trace_sys_enter
```
```
In kernel/time/timer.c (ffffffff811422c9)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:perf_trace_tick_stop
  - kernel/time/timer.c:perf_trace_itimer_expire
  - kernel/time/timer.c:perf_trace_itimer_state
  - kernel/time/timer.c:perf_trace_hrtimer_class
  - kernel/time/timer.c:perf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:perf_trace_hrtimer_start
  - kernel/time/timer.c:perf_trace_hrtimer_init
  - kernel/time/timer.c:perf_trace_timer_expire_entry
  - kernel/time/timer.c:perf_trace_timer_start
  - kernel/time/timer.c:perf_trace_timer_class
```
```
In kernel/time/alarmtimer.c (ffffffff8114a1e7)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114e9d8)
Location: include/linux/list.h:828
Inline: True
```
```
In kernel/module.c (ffffffff811601e4)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff8116c56a)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/ftrace.c (ffffffff811aab36)
Location: include/linux/list.h:828
Inline: True
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d4d65)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/bpf_trace.c (ffffffff811e8223)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_trace_bpf_trace_printk
```
```
In kernel/trace/trace_kprobe.c (ffffffff811eb2f1)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/power-traces.c (ffffffff811ee761)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:perf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update
  - kernel/trace/power-traces.c:perf_trace_cpu_latency_qos_request
  - kernel/trace/power-traces.c:perf_trace_power_domain
  - kernel/trace/power-traces.c:perf_trace_clock
  - kernel/trace/power-traces.c:perf_trace_wakeup_source
  - kernel/trace/power-traces.c:perf_trace_suspend_resume
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:perf_trace_cpu_frequency_limits
  - kernel/trace/power-traces.c:perf_trace_pstate_sample
  - kernel/trace/power-traces.c:perf_trace_powernv_throttle
  - kernel/trace/power-traces.c:perf_trace_cpu
```
```
In kernel/trace/rpm-traces.c (ffffffff811efcae)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f313a)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/core.c (ffffffff811f7671)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_mem_return_failed
  - kernel/bpf/core.c:perf_trace_mem_connect
  - kernel/bpf/core.c:perf_trace_mem_disconnect
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_bulk_tx
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/bpf/trampoline.c (ffffffff812229ed)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_put
  - kernel/bpf/trampoline.c:bpf_trampoline_put
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8122ff22)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
```
```
In kernel/events/core.c (ffffffff81241115)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/events/core.c:perf_trace_run_bpf_submit
```
```
In kernel/user-return-notifier.c (ffffffff812537c2)
Location: include/linux/list.h:828
Inline: True
```
```
In kernel/rseq.c (ffffffff81255f5f)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In kernel/watch_queue.c (ffffffff81257816)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
```
```
In mm/filemap.c (ffffffff81258280)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff8125fca8)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:perf_trace_skip_task_reaping
  - mm/oom_kill.c:perf_trace_finish_task_reaping
  - mm/oom_kill.c:perf_trace_start_task_reaping
  - mm/oom_kill.c:perf_trace_wake_reaper
  - mm/oom_kill.c:perf_trace_mark_victim
  - mm/oom_kill.c:perf_trace_reclaim_retry_zone
  - mm/oom_kill.c:perf_trace_oom_score_adj_update
```
```
In mm/swap.c (ffffffff81267c2d)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff8126d8d2)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/vmscan.c:perf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:perf_trace_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_isolate
  - mm/vmscan.c:perf_trace_mm_shrink_slab_end
  - mm/vmscan.c:perf_trace_mm_shrink_slab_start
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_end_template
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:perf_trace_mm_vmscan_wakeup_kswapd
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_wake
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_sleep
```
```
In mm/percpu.c (ffffffff812835b9)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff8128810a)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/slab_common.c:perf_trace_rss_stat
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:perf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:perf_trace_mm_page
  - mm/slab_common.c:perf_trace_mm_page_alloc
  - mm/slab_common.c:perf_trace_mm_page_free_batched
  - mm/slab_common.c:perf_trace_mm_page_free
  - mm/slab_common.c:perf_trace_kmem_free
  - mm/slab_common.c:perf_trace_kmem_alloc_node
  - mm/slab_common.c:perf_trace_kmem_alloc
```
```
In mm/compaction.c (ffffffff81289f12)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/compaction.c:perf_trace_kcompactd_wake_template
  - mm/compaction.c:perf_trace_mm_compaction_kcompactd_sleep
  - mm/compaction.c:perf_trace_mm_compaction_defer_template
  - mm/compaction.c:perf_trace_mm_compaction_suitable_template
  - mm/compaction.c:perf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:perf_trace_mm_compaction_end
  - mm/compaction.c:perf_trace_mm_compaction_begin
  - mm/compaction.c:perf_trace_mm_compaction_migratepages
  - mm/compaction.c:perf_trace_mm_compaction_isolate_template
```
```
In mm/mmap_lock.c (ffffffff812964f4)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/mmap_lock.c:perf_trace_mmap_lock_released
  - mm/mmap_lock.c:perf_trace_mmap_lock_acquire_returned
  - mm/mmap_lock.c:perf_trace_mmap_lock_start_locking
```
```
In mm/mmap.c (ffffffff812a35a4)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/mmap.c:perf_trace_vm_unmapped_area
```
```
In mm/mmu_notifier.c (ffffffff812de444)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_subscriptions_destroy
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_release
  - mm/mmu_notifier.c:mn_hlist_release
```
```
In mm/ksm.c (ffffffff812ded0a)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
```
```
In mm/migrate.c (ffffffff812ecd97)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff812fa96d)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff8130f554)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In fs/super.c (ffffffff81323f43)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - fs/super.c:reconfigure_super
```
```
In fs/dcache.c (ffffffff8133ea21)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_find_alias
  - fs/dcache.c:d_find_alias
```
```
In fs/namespace.c (ffffffff8134afdc)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:namespace_unlock
```
```
In fs/seq_file.c (ffffffff8134e0dc)
Location: include/linux/list.h:828
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81354cd9)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_writeback_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_congest_waited_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_pages_written
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
```
```
In fs/notify/mark.c (ffffffff81374932)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/eventpoll.c (ffffffff8137cd21)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:reverse_path_check_proc
```
```
In fs/io_uring.c (ffffffff81388904)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - fs/io_uring.c:perf_trace_io_uring_task_run
  - fs/io_uring.c:perf_trace_io_uring_task_add
  - fs/io_uring.c:perf_trace_io_uring_poll_wake
  - fs/io_uring.c:perf_trace_io_uring_poll_arm
  - fs/io_uring.c:perf_trace_io_uring_submit_sqe
  - fs/io_uring.c:perf_trace_io_uring_complete
  - fs/io_uring.c:perf_trace_io_uring_fail_link
  - fs/io_uring.c:perf_trace_io_uring_cqring_wait
  - fs/io_uring.c:perf_trace_io_uring_link
  - fs/io_uring.c:perf_trace_io_uring_defer
  - fs/io_uring.c:perf_trace_io_uring_queue_async_work
  - fs/io_uring.c:perf_trace_io_uring_file_get
  - fs/io_uring.c:perf_trace_io_uring_register
  - fs/io_uring.c:perf_trace_io_uring_create
```
```
In fs/dax.c (ffffffff8139d5b2)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - fs/dax.c:perf_trace_dax_writeback_one
  - fs/dax.c:perf_trace_dax_writeback_range_class
  - fs/dax.c:perf_trace_dax_insert_mapping
  - fs/dax.c:perf_trace_dax_pte_fault_class
  - fs/dax.c:perf_trace_dax_pmd_insert_mapping_class
  - fs/dax.c:perf_trace_dax_pmd_load_hole_class
  - fs/dax.c:perf_trace_dax_pmd_fault_class
```
```
In fs/locks.c (ffffffff813aaa80)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/iomap/trace.c (ffffffff813ba8dc)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - fs/iomap/trace.c:perf_trace_iomap_apply
  - fs/iomap/trace.c:perf_trace_iomap_class
  - fs/iomap/trace.c:perf_trace_iomap_range_class
  - fs/iomap/trace.c:perf_trace_iomap_readpage_class
```
```
In fs/ext4/super.c (ffffffff8143973a)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_fc_track_range
  - fs/ext4/super.c:perf_trace_ext4_fc_track_inode
  - fs/ext4/super.c:perf_trace_ext4_fc_track_unlink
  - fs/ext4/super.c:perf_trace_ext4_fc_track_link
  - fs/ext4/super.c:perf_trace_ext4_fc_track_create
  - fs/ext4/super.c:perf_trace_ext4_fc_stats
  - fs/ext4/super.c:perf_trace_ext4_fc_commit_stop
  - fs/ext4/super.c:perf_trace_ext4_fc_commit_start
  - fs/ext4/super.c:perf_trace_ext4_fc_replay
  - fs/ext4/super.c:perf_trace_ext4_fc_replay_scan
  - fs/ext4/super.c:perf_trace_ext4_lazy_itable_init
  - fs/ext4/super.c:perf_trace_ext4_prefetch_bitmaps
  - fs/ext4/super.c:perf_trace_ext4_error
  - fs/ext4/super.c:perf_trace_ext4_shutdown
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:perf_trace_ext4_insert_range
  - fs/ext4/super.c:perf_trace_ext4_collapse_range
  - fs/ext4/super.c:perf_trace_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:perf_trace_ext4__es_shrink_enter
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_enter
  - fs/ext4/super.c:perf_trace_ext4_es_remove_extent
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_idx
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_show_extent
  - fs/ext4/super.c:perf_trace_ext4_get_reserved_cluster_alloc
  - fs/ext4/super.c:perf_trace_ext4_find_delalloc_range
  - fs/ext4/super.c:perf_trace_ext4_ext_in_cache
  - fs/ext4/super.c:perf_trace_ext4_ext_put_in_cache
  - fs/ext4/super.c:perf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:perf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:perf_trace_ext4__trim
  - fs/ext4/super.c:perf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:perf_trace_ext4_journal_start
  - fs/ext4/super.c:perf_trace_ext4_load_inode
  - fs/ext4/super.c:perf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_exit
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_enter
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:perf_trace_ext4__truncate
  - fs/ext4/super.c:perf_trace_ext4_unlink_exit
  - fs/ext4/super.c:perf_trace_ext4_unlink_enter
  - fs/ext4/super.c:perf_trace_ext4_fallocate_exit
  - fs/ext4/super.c:perf_trace_ext4__fallocate_mode
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_exit
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_enter
  - fs/ext4/super.c:perf_trace_ext4_read_block_bitmap_load
  - fs/ext4/super.c:perf_trace_ext4__bitmap_load
  - fs/ext4/super.c:perf_trace_ext4_da_release_space
  - fs/ext4/super.c:perf_trace_ext4_da_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_da_update_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_forget
  - fs/ext4/super.c:perf_trace_ext4__mballoc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_prealloc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_alloc
  - fs/ext4/super.c:perf_trace_ext4_alloc_da_blocks
  - fs/ext4/super.c:perf_trace_ext4_sync_fs
  - fs/ext4/super.c:perf_trace_ext4_sync_file_exit
  - fs/ext4/super.c:perf_trace_ext4_sync_file_enter
  - fs/ext4/super.c:perf_trace_ext4_free_blocks
  - fs/ext4/super.c:perf_trace_ext4_allocate_blocks
  - fs/ext4/super.c:perf_trace_ext4_request_blocks
  - fs/ext4/super.c:perf_trace_ext4_mb_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_mb_release_group_pa
  - fs/ext4/super.c:perf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:perf_trace_ext4__mb_new_pa
  - fs/ext4/super.c:perf_trace_ext4_discard_blocks
  - fs/ext4/super.c:perf_trace_ext4_invalidatepage_op
  - fs/ext4/super.c:perf_trace_ext4__page_op
  - fs/ext4/super.c:perf_trace_ext4_writepages_result
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages_extent
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages
  - fs/ext4/super.c:perf_trace_ext4_writepages
  - fs/ext4/super.c:perf_trace_ext4__write_end
  - fs/ext4/super.c:perf_trace_ext4__write_begin
  - fs/ext4/super.c:perf_trace_ext4_begin_ordered_truncate
  - fs/ext4/super.c:perf_trace_ext4_mark_inode_dirty
  - fs/ext4/super.c:perf_trace_ext4_nfs_commit_metadata
  - fs/ext4/super.c:perf_trace_ext4_drop_inode
  - fs/ext4/super.c:perf_trace_ext4_evict_inode
  - fs/ext4/super.c:perf_trace_ext4_allocate_inode
  - fs/ext4/super.c:perf_trace_ext4_request_inode
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
```
```
In fs/jbd2/journal.c (ffffffff81461298)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - fs/jbd2/journal.c:perf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:perf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:perf_trace_jbd2_update_log_tail
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_run_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_extend
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_start_class
  - fs/jbd2/journal.c:perf_trace_jbd2_submit_inode_data
  - fs/jbd2/journal.c:perf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint
```
```
In security/selinux/avc.c (ffffffff814cbb8b)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_get_hash_stats
  - security/selinux/avc.c:perf_trace_selinux_audited
```
```
In block/blk-core.c (ffffffff8155e755)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_unplug
  - block/blk-core.c:perf_trace_block_plug
  - block/blk-core.c:perf_trace_block_bio
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_buffer
```
```
In block/blk-ioc.c (ffffffff815651e0)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - block/blk-ioc.c:put_io_context
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff81586962)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In block/blk-iocost.c (ffffffff8158eaac)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_iocg_forgive_debt
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_state
```
```
In block/blk-wbt.c (ffffffff8159648b)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In arch/x86/lib/msr.c (ffffffff8160c122)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff816335c2)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/pwm/core.c (ffffffff81641653)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/pwm/core.c:perf_trace_pwm
```
```
In drivers/clk/clk.c (ffffffff8171dd30)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate_range
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff81745895)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff8178b279)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/char/random.c:perf_trace_prandom_u32
  - drivers/char/random.c:perf_trace_urandom_read
  - drivers/char/random.c:perf_trace_random_read
  - drivers/char/random.c:perf_trace_random__extract_entropy
  - drivers/char/random.c:perf_trace_random__get_random_bytes
  - drivers/char/random.c:perf_trace_xfer_secondary_pool
  - drivers/char/random.c:perf_trace_add_disk_randomness
  - drivers/char/random.c:perf_trace_add_input_randomness
  - drivers/char/random.c:perf_trace_debit_entropy
  - drivers/char/random.c:perf_trace_push_to_pool
  - drivers/char/random.c:perf_trace_credit_entropy_bits
  - drivers/char/random.c:perf_trace_random__mix_pool_bytes
  - drivers/char/random.c:perf_trace_add_device_randomness
```
```
In drivers/iommu/intel/trace.c (ffffffff817b4cf2)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/iommu/intel/trace.c:perf_trace_dma_map_sg
  - drivers/iommu/intel/trace.c:perf_trace_dma_unmap
  - drivers/iommu/intel/trace.c:perf_trace_dma_map
```
```
In drivers/iommu/iommu-traces.c (ffffffff817bd794)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff817f006c)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8183711c)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8183cbfe)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff8183e293)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff818620f9)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff81887e40)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff8189481d)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81922caa)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_dbc_log_request
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_doorbell
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_slot_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ep_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_free_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_trb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
```
```
In drivers/rtc/interface.c (ffffffff8193fd1d)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/rtc/interface.c:perf_trace_rtc_timer_class
  - drivers/rtc/interface.c:perf_trace_rtc_offset_class
  - drivers/rtc/interface.c:perf_trace_rtc_alarm_irq_enable
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_state
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_freq
  - drivers/rtc/interface.c:perf_trace_rtc_time_alarm_class
```
```
In drivers/i2c/i2c-core-base.c (ffffffff819459fb)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff819498bf)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff819586b7)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff8195b1ce)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff8196176c)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff819a9b92)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffffffff819c6f25)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_start
```
```
In drivers/devfreq/devfreq.c (ffffffff819d0832)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_frequency
```
```
In drivers/ras/ras.c (ffffffff819d7112)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_memory_failure_event
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_non_standard_event
  - drivers/ras/ras.c:perf_trace_arm_event
  - drivers/ras/ras.c:perf_trace_mc_event
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
```
```
In drivers/interconnect/core.c (ffffffff819db320)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_node_destroy
  - drivers/interconnect/core.c:perf_trace_icc_set_bw_end
  - drivers/interconnect/core.c:perf_trace_icc_set_bw
```
```
In net/core/net-traces.c (ffffffff81a4920a)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:perf_trace_neigh_create
  - net/core/net-traces.c:perf_trace_page_pool_update_nid
  - net/core/net-traces.c:perf_trace_page_pool_state_hold
  - net/core/net-traces.c:perf_trace_page_pool_state_release
  - net/core/net-traces.c:perf_trace_page_pool_release
  - net/core/net-traces.c:perf_trace_br_fdb_update
  - net/core/net-traces.c:perf_trace_fdb_delete
  - net/core/net-traces.c:perf_trace_br_fdb_external_learn_add
  - net/core/net-traces.c:perf_trace_br_fdb_add
  - net/core/net-traces.c:perf_trace_qdisc_create
  - net/core/net-traces.c:perf_trace_qdisc_destroy
  - net/core/net-traces.c:perf_trace_qdisc_reset
  - net/core/net-traces.c:perf_trace_qdisc_dequeue
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_rcvqueue_full
  - net/core/net-traces.c:perf_trace_napi_poll
  - net/core/net-traces.c:perf_trace_net_dev_rx_exit_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_template
  - net/core/net-traces.c:perf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:perf_trace_net_dev_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:perf_trace_consume_skb
  - net/core/net-traces.c:perf_trace_kfree_skb
```
```
In net/core/devlink.c (ffffffff81a5805e)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_trap_report
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/core/bpf_sk_storage.c (ffffffff81a6a0e7)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put_all
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
```
In net/bpf/test_run.c (ffffffff81a87660)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aaed0a)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_put_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab1b1e)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse
```
```
In net/ipv4/raw.c (ffffffff81adbecb)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81aded04)
Location: include/linux/list.h:828
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff81b0134d)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b222f4)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/xfrm/xfrm_state.c (ffffffff81b2bb90)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
```
```
In net/unix/af_unix.c (ffffffff81b3259c)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/anycast.c (ffffffff81b3ad03)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_anycast_cleanup
```
```
In net/ipv6/addrconf.c (ffffffff81b4d5cf)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
```
```
In net/ipv6/route.c (ffffffff81b4e799)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
```
In net/ipv6/raw.c (ffffffff81b6bb29)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/packet/af_packet.c (ffffffff81b954b0)
Location: include/linux/list.h:828
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81bb61f5)
Location: include/linux/list.h:828
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
In init/main.c (ffffffff81003388)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005029)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff8102dd28)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_set_ldt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_gdt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_load_idt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_multi
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_one_user
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_alloc_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu__set_pte
  - arch/x86/xen/trace.c:perf_trace_xen_mc_extend_args
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush_reason
  - arch/x86/xen/trace.c:perf_trace_xen_mc_callback
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry_alloc
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mc__batch
```
```
In arch/x86/hyperv/mmu.c (ffffffff81031d18)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_one
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_multi
```
```
In arch/x86/kernel/irq.c (ffffffff81037e6e)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:perf_trace_vector_free_moved
  - arch/x86/kernel/irq.c:perf_trace_vector_setup
  - arch/x86/kernel/irq.c:perf_trace_vector_teardown
  - arch/x86/kernel/irq.c:perf_trace_vector_activate
  - arch/x86/kernel/irq.c:perf_trace_vector_alloc_managed
  - arch/x86/kernel/irq.c:perf_trace_vector_alloc
  - arch/x86/kernel/irq.c:perf_trace_vector_reserve
  - arch/x86/kernel/irq.c:perf_trace_vector_mod
  - arch/x86/kernel/irq.c:perf_trace_vector_config
  - arch/x86/kernel/irq.c:perf_trace_x86_irq_vector
```
```
In arch/x86/kernel/nmi.c (ffffffff8103a4d2)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8104319a)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81051e8a)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81063f28)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/init.c (ffffffff81086398)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff81087cea)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In kernel/fork.c (ffffffff810a015c)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_show_fdinfo
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff810a6f2f)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/exit.c (ffffffff810a9b6d)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/softirq.c (ffffffff810ab429)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810b3c52)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810c3218)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_end
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_activate_work
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
```
```
In kernel/pid.c (ffffffff810c9da4)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:__change_pid
```
```
In kernel/sched/core.c (ffffffff810d8f29)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_wake_idle_without_ipi
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:perf_trace_sched_process_hang
  - kernel/sched/core.c:perf_trace_sched_pi_setprio
  - kernel/sched/core.c:perf_trace_sched_stat_runtime
  - kernel/sched/core.c:perf_trace_sched_process_exec
  - kernel/sched/core.c:perf_trace_sched_process_fork
  - kernel/sched/core.c:perf_trace_sched_process_wait
  - kernel/sched/core.c:perf_trace_sched_process_template
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:perf_trace_sched_kthread_work_execute_end
  - kernel/sched/core.c:perf_trace_sched_kthread_work_execute_start
  - kernel/sched/core.c:perf_trace_sched_kthread_work_queue_work
  - kernel/sched/core.c:perf_trace_sched_kthread_stop_ret
  - kernel/sched/core.c:perf_trace_sched_kthread_stop
```
```
In kernel/printk/printk.c (ffffffff81118293)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff8112ae6d)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff8112bef8)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_stall_warning
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff8113b6e3)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/entry/common.c (ffffffff8113c54a)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/entry/common.c:perf_trace_sys_exit
  - kernel/entry/common.c:perf_trace_sys_enter
```
```
In kernel/time/timer.c (ffffffff811434b9)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:perf_trace_tick_stop
  - kernel/time/timer.c:perf_trace_itimer_expire
  - kernel/time/timer.c:perf_trace_itimer_state
  - kernel/time/timer.c:perf_trace_hrtimer_class
  - kernel/time/timer.c:perf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:perf_trace_hrtimer_start
  - kernel/time/timer.c:perf_trace_hrtimer_init
  - kernel/time/timer.c:perf_trace_timer_expire_entry
  - kernel/time/timer.c:perf_trace_timer_start
  - kernel/time/timer.c:perf_trace_timer_class
```
```
In kernel/time/alarmtimer.c (ffffffff8114b6a7)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114fe71)
Location: include/linux/list.h:828
Inline: True
```
```
In kernel/module.c (ffffffff811610b1)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff8116d1c7)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/ftrace.c (ffffffff811ab726)
Location: include/linux/list.h:828
Inline: True
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d65b8)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/bpf_trace.c (ffffffff811e9023)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_trace_bpf_trace_printk
```
```
In kernel/trace/trace_kprobe.c (ffffffff811ec6c1)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/error_report-traces.c (ffffffff811ed898)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/trace/error_report-traces.c:perf_trace_error_report_template
```
```
In kernel/trace/power-traces.c (ffffffff811ef6ae)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:perf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update
  - kernel/trace/power-traces.c:perf_trace_cpu_latency_qos_request
  - kernel/trace/power-traces.c:perf_trace_power_domain
  - kernel/trace/power-traces.c:perf_trace_clock
  - kernel/trace/power-traces.c:perf_trace_wakeup_source
  - kernel/trace/power-traces.c:perf_trace_suspend_resume
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:perf_trace_cpu_frequency_limits
  - kernel/trace/power-traces.c:perf_trace_pstate_sample
  - kernel/trace/power-traces.c:perf_trace_powernv_throttle
  - kernel/trace/power-traces.c:perf_trace_cpu
```
```
In kernel/trace/rpm-traces.c (ffffffff811f0bde)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f406a)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/core.c (ffffffff811f84c1)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_mem_return_failed
  - kernel/bpf/core.c:perf_trace_mem_connect
  - kernel/bpf/core.c:perf_trace_mem_disconnect
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_bulk_tx
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff812254e3)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
```
```
In kernel/bpf/trampoline.c (ffffffff8122718d)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_put
  - kernel/bpf/trampoline.c:bpf_trampoline_put
```
```
In kernel/events/core.c (ffffffff81244ec5)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/events/core.c:perf_trace_run_bpf_submit
```
```
In kernel/user-return-notifier.c (ffffffff81257de2)
Location: include/linux/list.h:828
Inline: True
```
```
In kernel/rseq.c (ffffffff8125a51f)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In kernel/watch_queue.c (ffffffff8125bc76)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
```
```
In mm/filemap.c (ffffffff8125c860)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff812647f1)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:perf_trace_skip_task_reaping
  - mm/oom_kill.c:perf_trace_finish_task_reaping
  - mm/oom_kill.c:perf_trace_start_task_reaping
  - mm/oom_kill.c:perf_trace_wake_reaper
  - mm/oom_kill.c:perf_trace_mark_victim
  - mm/oom_kill.c:perf_trace_reclaim_retry_zone
  - mm/oom_kill.c:perf_trace_oom_score_adj_update
```
```
In mm/swap.c (ffffffff8126c82d)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff81272612)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/vmscan.c:perf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:perf_trace_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_isolate
  - mm/vmscan.c:perf_trace_mm_shrink_slab_end
  - mm/vmscan.c:perf_trace_mm_shrink_slab_start
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_end_template
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:perf_trace_mm_vmscan_wakeup_kswapd
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_wake
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_sleep
```
```
In mm/percpu.c (ffffffff812886b9)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff8128d4ab)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/slab_common.c:perf_trace_rss_stat
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:perf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:perf_trace_mm_page
  - mm/slab_common.c:perf_trace_mm_page_alloc
  - mm/slab_common.c:perf_trace_mm_page_free_batched
  - mm/slab_common.c:perf_trace_mm_page_free
  - mm/slab_common.c:perf_trace_kmem_cache_free
  - mm/slab_common.c:perf_trace_kfree
  - mm/slab_common.c:perf_trace_kmem_alloc_node
  - mm/slab_common.c:perf_trace_kmem_alloc
```
```
In mm/compaction.c (ffffffff8128f582)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/compaction.c:perf_trace_kcompactd_wake_template
  - mm/compaction.c:perf_trace_mm_compaction_kcompactd_sleep
  - mm/compaction.c:perf_trace_mm_compaction_defer_template
  - mm/compaction.c:perf_trace_mm_compaction_suitable_template
  - mm/compaction.c:perf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:perf_trace_mm_compaction_end
  - mm/compaction.c:perf_trace_mm_compaction_begin
  - mm/compaction.c:perf_trace_mm_compaction_migratepages
  - mm/compaction.c:perf_trace_mm_compaction_isolate_template
```
```
In mm/mmap_lock.c (ffffffff8129be91)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/mmap_lock.c:perf_trace_mmap_lock_released
  - mm/mmap_lock.c:perf_trace_mmap_lock_acquire_returned
  - mm/mmap_lock.c:perf_trace_mmap_lock_start_locking
```
```
In mm/mmap.c (ffffffff812a8de4)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/mmap.c:perf_trace_vm_unmapped_area
```
```
In mm/mmu_notifier.c (ffffffff812e5c24)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_subscriptions_destroy
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_release
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (ffffffff812e64f4)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
```
```
In mm/migrate.c (ffffffff812f3048)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages_start
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff8130172d)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff813158a4)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In fs/super.c (ffffffff8132a003)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - fs/super.c:reconfigure_super
```
```
In fs/dcache.c (ffffffff81344e11)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_find_alias_rcu
  - fs/dcache.c:d_find_alias
  - fs/dcache.c:d_find_alias
```
```
In fs/namespace.c (ffffffff8135188c)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:namespace_unlock
```
```
In fs/seq_file.c (ffffffff813544ac)
Location: include/linux/list.h:828
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8135b979)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_writeback_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_congest_waited_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_pages_written
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
```
```
In fs/notify/mark.c (ffffffff8137b2e8)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/eventpoll.c (ffffffff813836e5)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:reverse_path_check_proc
```
```
In fs/io_uring.c (ffffffff8138fa24)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - fs/io_uring.c:perf_trace_io_uring_task_run
  - fs/io_uring.c:perf_trace_io_uring_task_add
  - fs/io_uring.c:perf_trace_io_uring_poll_wake
  - fs/io_uring.c:perf_trace_io_uring_poll_arm
  - fs/io_uring.c:perf_trace_io_uring_submit_sqe
  - fs/io_uring.c:perf_trace_io_uring_complete
  - fs/io_uring.c:perf_trace_io_uring_fail_link
  - fs/io_uring.c:perf_trace_io_uring_cqring_wait
  - fs/io_uring.c:perf_trace_io_uring_link
  - fs/io_uring.c:perf_trace_io_uring_defer
  - fs/io_uring.c:perf_trace_io_uring_queue_async_work
  - fs/io_uring.c:perf_trace_io_uring_file_get
  - fs/io_uring.c:perf_trace_io_uring_register
  - fs/io_uring.c:perf_trace_io_uring_create
```
```
In fs/dax.c (ffffffff813a47c2)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - fs/dax.c:perf_trace_dax_writeback_one
  - fs/dax.c:perf_trace_dax_writeback_range_class
  - fs/dax.c:perf_trace_dax_insert_mapping
  - fs/dax.c:perf_trace_dax_pte_fault_class
  - fs/dax.c:perf_trace_dax_pmd_insert_mapping_class
  - fs/dax.c:perf_trace_dax_pmd_load_hole_class
  - fs/dax.c:perf_trace_dax_pmd_fault_class
```
```
In fs/locks.c (ffffffff813b1f50)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/iomap/trace.c (ffffffff813c19fc)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - fs/iomap/trace.c:perf_trace_iomap_apply
  - fs/iomap/trace.c:perf_trace_iomap_class
  - fs/iomap/trace.c:perf_trace_iomap_range_class
  - fs/iomap/trace.c:perf_trace_iomap_readpage_class
```
```
In fs/ext4/super.c (ffffffff8143f8ea)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_fc_track_range
  - fs/ext4/super.c:perf_trace_ext4_fc_track_inode
  - fs/ext4/super.c:perf_trace_ext4_fc_track_unlink
  - fs/ext4/super.c:perf_trace_ext4_fc_track_link
  - fs/ext4/super.c:perf_trace_ext4_fc_track_create
  - fs/ext4/super.c:perf_trace_ext4_fc_stats
  - fs/ext4/super.c:perf_trace_ext4_fc_commit_stop
  - fs/ext4/super.c:perf_trace_ext4_fc_commit_start
  - fs/ext4/super.c:perf_trace_ext4_fc_replay
  - fs/ext4/super.c:perf_trace_ext4_fc_replay_scan
  - fs/ext4/super.c:perf_trace_ext4_lazy_itable_init
  - fs/ext4/super.c:perf_trace_ext4_prefetch_bitmaps
  - fs/ext4/super.c:perf_trace_ext4_error
  - fs/ext4/super.c:perf_trace_ext4_shutdown
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:perf_trace_ext4_insert_range
  - fs/ext4/super.c:perf_trace_ext4_collapse_range
  - fs/ext4/super.c:perf_trace_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:perf_trace_ext4__es_shrink_enter
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_enter
  - fs/ext4/super.c:perf_trace_ext4_es_remove_extent
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_idx
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_show_extent
  - fs/ext4/super.c:perf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:perf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:perf_trace_ext4__trim
  - fs/ext4/super.c:perf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:perf_trace_ext4_journal_start
  - fs/ext4/super.c:perf_trace_ext4_load_inode
  - fs/ext4/super.c:perf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_exit
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_enter
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:perf_trace_ext4__truncate
  - fs/ext4/super.c:perf_trace_ext4_unlink_exit
  - fs/ext4/super.c:perf_trace_ext4_unlink_enter
  - fs/ext4/super.c:perf_trace_ext4_fallocate_exit
  - fs/ext4/super.c:perf_trace_ext4__fallocate_mode
  - fs/ext4/super.c:perf_trace_ext4_read_block_bitmap_load
  - fs/ext4/super.c:perf_trace_ext4__bitmap_load
  - fs/ext4/super.c:perf_trace_ext4_da_release_space
  - fs/ext4/super.c:perf_trace_ext4_da_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_da_update_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_forget
  - fs/ext4/super.c:perf_trace_ext4__mballoc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_prealloc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_alloc
  - fs/ext4/super.c:perf_trace_ext4_alloc_da_blocks
  - fs/ext4/super.c:perf_trace_ext4_sync_fs
  - fs/ext4/super.c:perf_trace_ext4_sync_file_exit
  - fs/ext4/super.c:perf_trace_ext4_sync_file_enter
  - fs/ext4/super.c:perf_trace_ext4_free_blocks
  - fs/ext4/super.c:perf_trace_ext4_allocate_blocks
  - fs/ext4/super.c:perf_trace_ext4_request_blocks
  - fs/ext4/super.c:perf_trace_ext4_mb_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_mb_release_group_pa
  - fs/ext4/super.c:perf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:perf_trace_ext4__mb_new_pa
  - fs/ext4/super.c:perf_trace_ext4_discard_blocks
  - fs/ext4/super.c:perf_trace_ext4_invalidatepage_op
  - fs/ext4/super.c:perf_trace_ext4__page_op
  - fs/ext4/super.c:perf_trace_ext4_writepages_result
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages_extent
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages
  - fs/ext4/super.c:perf_trace_ext4_writepages
  - fs/ext4/super.c:perf_trace_ext4__write_end
  - fs/ext4/super.c:perf_trace_ext4__write_begin
  - fs/ext4/super.c:perf_trace_ext4_begin_ordered_truncate
  - fs/ext4/super.c:perf_trace_ext4_mark_inode_dirty
  - fs/ext4/super.c:perf_trace_ext4_nfs_commit_metadata
  - fs/ext4/super.c:perf_trace_ext4_drop_inode
  - fs/ext4/super.c:perf_trace_ext4_evict_inode
  - fs/ext4/super.c:perf_trace_ext4_allocate_inode
  - fs/ext4/super.c:perf_trace_ext4_request_inode
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
```
```
In fs/jbd2/journal.c (ffffffff81466a48)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - fs/jbd2/journal.c:perf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:perf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:perf_trace_jbd2_update_log_tail
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_run_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_extend
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_start_class
  - fs/jbd2/journal.c:perf_trace_jbd2_submit_inode_data
  - fs/jbd2/journal.c:perf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint
```
```
In security/selinux/avc.c (ffffffff814d21bb)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_get_hash_stats
  - security/selinux/avc.c:perf_trace_selinux_audited
```
```
In block/blk-core.c (ffffffff81566fa2)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_unplug
  - block/blk-core.c:perf_trace_block_plug
  - block/blk-core.c:perf_trace_block_bio
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_buffer
```
```
In block/blk-ioc.c (ffffffff8156d850)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - block/blk-ioc.c:put_io_context
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff8158d672)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In block/blk-iocost.c (ffffffff815957fe)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_iocg_forgive_debt
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_state
```
```
In block/blk-wbt.c (ffffffff8159d2ca)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In arch/x86/lib/msr.c (ffffffff815ef442)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff816172b2)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/pwm/core.c (ffffffff81624593)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/pwm/core.c:perf_trace_pwm
```
```
In drivers/clk/clk.c (ffffffff816fedc0)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate_range
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff817292a2)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff8176e649)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/char/random.c:perf_trace_prandom_u32
  - drivers/char/random.c:perf_trace_urandom_read
  - drivers/char/random.c:perf_trace_random__extract_entropy
  - drivers/char/random.c:perf_trace_random__get_random_bytes
  - drivers/char/random.c:perf_trace_add_disk_randomness
  - drivers/char/random.c:perf_trace_add_input_randomness
  - drivers/char/random.c:perf_trace_debit_entropy
  - drivers/char/random.c:perf_trace_credit_entropy_bits
  - drivers/char/random.c:perf_trace_random__mix_pool_bytes
  - drivers/char/random.c:perf_trace_add_device_randomness
```
```
In drivers/iommu/intel/trace.c (ffffffff81797a48)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/iommu/intel/trace.c:perf_trace_qi_submit
```
```
In drivers/iommu/iommu-traces.c (ffffffff817a09d4)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff817d4aac)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8181a2dc)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8181fdb9)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff81821433)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff81844ec9)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff8186a69e)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff8187711d)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff819063ba)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_dbc_log_request
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_doorbell
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_slot_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ep_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_free_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_trb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
```
```
In drivers/rtc/interface.c (ffffffff819234bd)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/rtc/interface.c:perf_trace_rtc_timer_class
  - drivers/rtc/interface.c:perf_trace_rtc_offset_class
  - drivers/rtc/interface.c:perf_trace_rtc_alarm_irq_enable
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_state
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_freq
  - drivers/rtc/interface.c:perf_trace_rtc_time_alarm_class
```
```
In drivers/i2c/i2c-core-base.c (ffffffff819291cb)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8192d1bf)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff8193c850)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff8193e09f)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81944bbc)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff8198e852)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffffffff819abe75)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_start
```
```
In drivers/devfreq/devfreq.c (ffffffff819b5aa2)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_frequency
```
```
In drivers/ras/ras.c (ffffffff819bd282)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_memory_failure_event
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_non_standard_event
  - drivers/ras/ras.c:perf_trace_arm_event
  - drivers/ras/ras.c:perf_trace_mc_event
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
```
```
In drivers/interconnect/core.c (ffffffff819c15d0)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_node_destroy
  - drivers/interconnect/core.c:perf_trace_icc_set_bw_end
  - drivers/interconnect/core.c:perf_trace_icc_set_bw
```
```
In net/core/net-traces.c (ffffffff81a2e15a)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:perf_trace_neigh_create
  - net/core/net-traces.c:perf_trace_page_pool_update_nid
  - net/core/net-traces.c:perf_trace_page_pool_state_hold
  - net/core/net-traces.c:perf_trace_page_pool_state_release
  - net/core/net-traces.c:perf_trace_page_pool_release
  - net/core/net-traces.c:perf_trace_br_fdb_update
  - net/core/net-traces.c:perf_trace_fdb_delete
  - net/core/net-traces.c:perf_trace_br_fdb_external_learn_add
  - net/core/net-traces.c:perf_trace_br_fdb_add
  - net/core/net-traces.c:perf_trace_qdisc_create
  - net/core/net-traces.c:perf_trace_qdisc_destroy
  - net/core/net-traces.c:perf_trace_qdisc_reset
  - net/core/net-traces.c:perf_trace_qdisc_dequeue
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_rcvqueue_full
  - net/core/net-traces.c:perf_trace_napi_poll
  - net/core/net-traces.c:perf_trace_net_dev_rx_exit_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_template
  - net/core/net-traces.c:perf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:perf_trace_net_dev_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:perf_trace_consume_skb
  - net/core/net-traces.c:perf_trace_kfree_skb
```
```
In net/core/devlink.c (ffffffff81a3ad4e)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_trap_report
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/core/bpf_sk_storage.c (ffffffff81a5271e)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
```
In net/netlink/af_netlink.c (ffffffff81a69263)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:perf_trace_netlink_extack
```
```
In net/bpf/test_run.c (ffffffff81a70730)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a99f88)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9cd8d)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse
```
```
In net/ipv4/raw.c (ffffffff81ac6d6c)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81ac9cf4)
Location: include/linux/list.h:828
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff81aeca10)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0fef4)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/xfrm/xfrm_state.c (ffffffff81b19800)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
```
```
In net/unix/af_unix.c (ffffffff81b200c5)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/anycast.c (ffffffff81b289e3)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_anycast_cleanup
```
```
In net/ipv6/addrconf.c (ffffffff81b3b47f)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
```
```
In net/ipv6/route.c (ffffffff81b3c5de)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
```
In net/ipv6/raw.c (ffffffff81b59e49)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/packet/af_packet.c (ffffffff81b84440)
Location: include/linux/list.h:828
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81ba51d5)
Location: include/linux/list.h:828
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81baa028)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/mptcp/protocol.c:perf_trace_subflow_check_data_avail
  - net/mptcp/protocol.c:perf_trace_ack_update_msk
  - net/mptcp/protocol.c:perf_trace_mptcp_dump_mpext
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
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
In init/main.c (ffffffff810033c8)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005639)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff810325d8)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_set_ldt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_gdt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_load_idt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_multi
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_one_user
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_alloc_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu__set_pte
  - arch/x86/xen/trace.c:perf_trace_xen_mc_extend_args
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush_reason
  - arch/x86/xen/trace.c:perf_trace_xen_mc_callback
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry_alloc
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mc__batch
```
```
In arch/x86/hyperv/mmu.c (ffffffff81036e98)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_one
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_multi
```
```
In arch/x86/kernel/irq.c (ffffffff8103d11e)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:perf_trace_vector_free_moved
  - arch/x86/kernel/irq.c:perf_trace_vector_setup
  - arch/x86/kernel/irq.c:perf_trace_vector_teardown
  - arch/x86/kernel/irq.c:perf_trace_vector_activate
  - arch/x86/kernel/irq.c:perf_trace_vector_alloc_managed
  - arch/x86/kernel/irq.c:perf_trace_vector_alloc
  - arch/x86/kernel/irq.c:perf_trace_vector_reserve
  - arch/x86/kernel/irq.c:perf_trace_vector_mod
  - arch/x86/kernel/irq.c:perf_trace_vector_config
  - arch/x86/kernel/irq.c:perf_trace_x86_irq_vector
```
```
In arch/x86/kernel/nmi.c (ffffffff8103fe82)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8104950a)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105a31a)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106df18)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/init.c (ffffffff810955a8)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff8109706a)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In kernel/fork.c (ffffffff810b156c)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_show_fdinfo
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff810b88aa)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/exit.c (ffffffff810bb6a9)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/softirq.c (ffffffff810bcf49)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810c5e62)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810d5d58)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_end
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_activate_work
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
```
```
In kernel/pid.c (ffffffff810dd999)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:__change_pid
```
```
In kernel/sched/core.c (ffffffff810ec869)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_wake_idle_without_ipi
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:perf_trace_sched_process_hang
  - kernel/sched/core.c:perf_trace_sched_pi_setprio
  - kernel/sched/core.c:perf_trace_sched_stat_runtime
  - kernel/sched/core.c:perf_trace_sched_process_exec
  - kernel/sched/core.c:perf_trace_sched_process_fork
  - kernel/sched/core.c:perf_trace_sched_process_wait
  - kernel/sched/core.c:perf_trace_sched_process_template
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:perf_trace_sched_kthread_work_execute_end
  - kernel/sched/core.c:perf_trace_sched_kthread_work_execute_start
  - kernel/sched/core.c:perf_trace_sched_kthread_work_queue_work
  - kernel/sched/core.c:perf_trace_sched_kthread_stop_ret
  - kernel/sched/core.c:perf_trace_sched_kthread_stop
```
```
In kernel/printk/printk.c (ffffffff81138593)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff8114b932)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff8114ca88)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_stall_warning
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff8115e823)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/entry/common.c (ffffffff8115f66a)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/entry/common.c:perf_trace_sys_exit
  - kernel/entry/common.c:perf_trace_sys_enter
```
```
In kernel/time/timer.c (ffffffff81166a7c)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:perf_trace_tick_stop
  - kernel/time/timer.c:perf_trace_itimer_expire
  - kernel/time/timer.c:perf_trace_itimer_state
  - kernel/time/timer.c:perf_trace_hrtimer_class
  - kernel/time/timer.c:perf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:perf_trace_hrtimer_start
  - kernel/time/timer.c:perf_trace_hrtimer_init
  - kernel/time/timer.c:perf_trace_timer_expire_entry
  - kernel/time/timer.c:perf_trace_timer_start
  - kernel/time/timer.c:perf_trace_timer_class
```
```
In kernel/time/alarmtimer.c (ffffffff8116f387)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811740a1)
Location: include/linux/list.h:828
Inline: True
```
```
In kernel/module.c (ffffffff81186281)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff81192ea7)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/ftrace.c (ffffffff811d5470)
Location: include/linux/list.h:828
Inline: True
```
```
In kernel/trace/trace_syscalls.c (ffffffff81203448)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/bpf_trace.c (ffffffff81219dc3)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_trace_bpf_trace_printk
```
```
In kernel/trace/trace_kprobe.c (ffffffff8121d701)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/error_report-traces.c (ffffffff8121e908)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/trace/error_report-traces.c:perf_trace_error_report_template
```
```
In kernel/trace/power-traces.c (ffffffff8122073e)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:perf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update
  - kernel/trace/power-traces.c:perf_trace_cpu_latency_qos_request
  - kernel/trace/power-traces.c:perf_trace_power_domain
  - kernel/trace/power-traces.c:perf_trace_clock
  - kernel/trace/power-traces.c:perf_trace_wakeup_source
  - kernel/trace/power-traces.c:perf_trace_suspend_resume
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:perf_trace_cpu_frequency_limits
  - kernel/trace/power-traces.c:perf_trace_pstate_sample
  - kernel/trace/power-traces.c:perf_trace_powernv_throttle
  - kernel/trace/power-traces.c:perf_trace_cpu
```
```
In kernel/trace/rpm-traces.c (ffffffff81221c7e)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffffffff8122554a)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/core.c (ffffffff81229aa1)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_mem_return_failed
  - kernel/bpf/core.c:perf_trace_mem_connect
  - kernel/bpf/core.c:perf_trace_mem_disconnect
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_bulk_tx
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8125d4d3)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
```
```
In kernel/bpf/trampoline.c (ffffffff8125f28d)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_put
  - kernel/bpf/trampoline.c:bpf_trampoline_put
```
```
In kernel/events/core.c (ffffffff8127fe75)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/events/core.c:perf_trace_run_bpf_submit
```
```
In kernel/user-return-notifier.c (ffffffff81293952)
Location: include/linux/list.h:828
Inline: True
```
```
In kernel/rseq.c (ffffffff8129630f)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In kernel/watch_queue.c (ffffffff81297b26)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
```
```
In mm/filemap.c (ffffffff81298720)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff812a1011)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:perf_trace_skip_task_reaping
  - mm/oom_kill.c:perf_trace_finish_task_reaping
  - mm/oom_kill.c:perf_trace_start_task_reaping
  - mm/oom_kill.c:perf_trace_wake_reaper
  - mm/oom_kill.c:perf_trace_mark_victim
  - mm/oom_kill.c:perf_trace_reclaim_retry_zone
  - mm/oom_kill.c:perf_trace_oom_score_adj_update
```
```
In mm/swap.c (ffffffff812a954d)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff812af9e2)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/vmscan.c:perf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_isolate
  - mm/vmscan.c:perf_trace_mm_shrink_slab_end
  - mm/vmscan.c:perf_trace_mm_shrink_slab_start
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_end_template
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:perf_trace_mm_vmscan_wakeup_kswapd
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_wake
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_sleep
```
```
In mm/percpu.c (ffffffff812c7df9)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff812cd2eb)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/slab_common.c:perf_trace_rss_stat
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:perf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:perf_trace_mm_page
  - mm/slab_common.c:perf_trace_mm_page_alloc
  - mm/slab_common.c:perf_trace_mm_page_free_batched
  - mm/slab_common.c:perf_trace_mm_page_free
  - mm/slab_common.c:perf_trace_kmem_cache_free
  - mm/slab_common.c:perf_trace_kfree
  - mm/slab_common.c:perf_trace_kmem_alloc_node
  - mm/slab_common.c:perf_trace_kmem_alloc
```
```
In mm/compaction.c (ffffffff812cf432)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/compaction.c:perf_trace_kcompactd_wake_template
  - mm/compaction.c:perf_trace_mm_compaction_kcompactd_sleep
  - mm/compaction.c:perf_trace_mm_compaction_defer_template
  - mm/compaction.c:perf_trace_mm_compaction_suitable_template
  - mm/compaction.c:perf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:perf_trace_mm_compaction_end
  - mm/compaction.c:perf_trace_mm_compaction_begin
  - mm/compaction.c:perf_trace_mm_compaction_migratepages
  - mm/compaction.c:perf_trace_mm_compaction_isolate_template
```
```
In mm/mmap_lock.c (ffffffff812dc991)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/mmap_lock.c:perf_trace_mmap_lock_released
  - mm/mmap_lock.c:perf_trace_mmap_lock_acquire_returned
  - mm/mmap_lock.c:perf_trace_mmap_lock_start_locking
```
```
In mm/mmap.c (ffffffff812ea454)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/mmap.c:perf_trace_vm_unmapped_area
```
```
In mm/mmu_notifier.c (ffffffff8132db14)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_subscriptions_destroy
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_release
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (ffffffff8132e3c4)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
```
```
In mm/migrate.c (ffffffff8133d4b8)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages_start
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff8134b42d)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff81361954)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In fs/super.c (ffffffff81377633)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - fs/super.c:reconfigure_super
```
```
In fs/dcache.c (ffffffff81392901)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_find_alias_rcu
  - fs/dcache.c:d_find_alias
  - fs/dcache.c:d_find_alias
```
```
In fs/namespace.c (ffffffff8139fbfc)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:namespace_unlock
```
```
In fs/seq_file.c (ffffffff813a2962)
Location: include/linux/list.h:828
Inline: True
```
```
In fs/fs-writeback.c (ffffffff813a9e19)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_writeback_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_congest_waited_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_pages_written
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
```
```
In fs/notify/mark.c (ffffffff813c802b)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813ccd82)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
```
```
In fs/eventpoll.c (ffffffff813d0985)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:reverse_path_check_proc
```
```
In fs/io_uring.c (ffffffff813dd2ef)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - fs/io_uring.c:perf_trace_io_uring_task_run
  - fs/io_uring.c:perf_trace_io_uring_task_add
  - fs/io_uring.c:perf_trace_io_uring_poll_wake
  - fs/io_uring.c:perf_trace_io_uring_poll_arm
  - fs/io_uring.c:perf_trace_io_uring_submit_sqe
  - fs/io_uring.c:perf_trace_io_uring_complete
  - fs/io_uring.c:perf_trace_io_uring_fail_link
  - fs/io_uring.c:perf_trace_io_uring_cqring_wait
  - fs/io_uring.c:perf_trace_io_uring_link
  - fs/io_uring.c:perf_trace_io_uring_defer
  - fs/io_uring.c:perf_trace_io_uring_queue_async_work
  - fs/io_uring.c:perf_trace_io_uring_file_get
  - fs/io_uring.c:perf_trace_io_uring_register
  - fs/io_uring.c:perf_trace_io_uring_create
```
```
In fs/dax.c (ffffffff813f40e2)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - fs/dax.c:perf_trace_dax_writeback_one
  - fs/dax.c:perf_trace_dax_writeback_range_class
  - fs/dax.c:perf_trace_dax_insert_mapping
  - fs/dax.c:perf_trace_dax_pte_fault_class
  - fs/dax.c:perf_trace_dax_pmd_insert_mapping_class
  - fs/dax.c:perf_trace_dax_pmd_load_hole_class
  - fs/dax.c:perf_trace_dax_pmd_fault_class
```
```
In fs/locks.c (ffffffff81401c40)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/iomap/trace.c (ffffffff81411c32)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - fs/iomap/trace.c:perf_trace_iomap_iter
  - fs/iomap/trace.c:perf_trace_iomap_class
  - fs/iomap/trace.c:perf_trace_iomap_range_class
  - fs/iomap/trace.c:perf_trace_iomap_readpage_class
```
```
In fs/ext4/super.c (ffffffff8149357a)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_fc_track_range
  - fs/ext4/super.c:perf_trace_ext4_fc_track_inode
  - fs/ext4/super.c:perf_trace_ext4_fc_track_unlink
  - fs/ext4/super.c:perf_trace_ext4_fc_track_link
  - fs/ext4/super.c:perf_trace_ext4_fc_track_create
  - fs/ext4/super.c:perf_trace_ext4_fc_stats
  - fs/ext4/super.c:perf_trace_ext4_fc_commit_stop
  - fs/ext4/super.c:perf_trace_ext4_fc_commit_start
  - fs/ext4/super.c:perf_trace_ext4_fc_replay
  - fs/ext4/super.c:perf_trace_ext4_fc_replay_scan
  - fs/ext4/super.c:perf_trace_ext4_lazy_itable_init
  - fs/ext4/super.c:perf_trace_ext4_prefetch_bitmaps
  - fs/ext4/super.c:perf_trace_ext4_error
  - fs/ext4/super.c:perf_trace_ext4_shutdown
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:perf_trace_ext4_insert_range
  - fs/ext4/super.c:perf_trace_ext4_collapse_range
  - fs/ext4/super.c:perf_trace_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:perf_trace_ext4__es_shrink_enter
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_enter
  - fs/ext4/super.c:perf_trace_ext4_es_remove_extent
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_idx
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_show_extent
  - fs/ext4/super.c:perf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:perf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:perf_trace_ext4__trim
  - fs/ext4/super.c:perf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:perf_trace_ext4_journal_start
  - fs/ext4/super.c:perf_trace_ext4_load_inode
  - fs/ext4/super.c:perf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_exit
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_enter
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:perf_trace_ext4__truncate
  - fs/ext4/super.c:perf_trace_ext4_unlink_exit
  - fs/ext4/super.c:perf_trace_ext4_unlink_enter
  - fs/ext4/super.c:perf_trace_ext4_fallocate_exit
  - fs/ext4/super.c:perf_trace_ext4__fallocate_mode
  - fs/ext4/super.c:perf_trace_ext4_read_block_bitmap_load
  - fs/ext4/super.c:perf_trace_ext4__bitmap_load
  - fs/ext4/super.c:perf_trace_ext4_da_release_space
  - fs/ext4/super.c:perf_trace_ext4_da_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_da_update_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_forget
  - fs/ext4/super.c:perf_trace_ext4__mballoc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_prealloc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_alloc
  - fs/ext4/super.c:perf_trace_ext4_alloc_da_blocks
  - fs/ext4/super.c:perf_trace_ext4_sync_fs
  - fs/ext4/super.c:perf_trace_ext4_sync_file_exit
  - fs/ext4/super.c:perf_trace_ext4_sync_file_enter
  - fs/ext4/super.c:perf_trace_ext4_free_blocks
  - fs/ext4/super.c:perf_trace_ext4_allocate_blocks
  - fs/ext4/super.c:perf_trace_ext4_request_blocks
  - fs/ext4/super.c:perf_trace_ext4_mb_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_mb_release_group_pa
  - fs/ext4/super.c:perf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:perf_trace_ext4__mb_new_pa
  - fs/ext4/super.c:perf_trace_ext4_discard_blocks
  - fs/ext4/super.c:perf_trace_ext4_invalidatepage_op
  - fs/ext4/super.c:perf_trace_ext4__page_op
  - fs/ext4/super.c:perf_trace_ext4_writepages_result
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages_extent
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages
  - fs/ext4/super.c:perf_trace_ext4_writepages
  - fs/ext4/super.c:perf_trace_ext4__write_end
  - fs/ext4/super.c:perf_trace_ext4__write_begin
  - fs/ext4/super.c:perf_trace_ext4_begin_ordered_truncate
  - fs/ext4/super.c:perf_trace_ext4_mark_inode_dirty
  - fs/ext4/super.c:perf_trace_ext4_nfs_commit_metadata
  - fs/ext4/super.c:perf_trace_ext4_drop_inode
  - fs/ext4/super.c:perf_trace_ext4_evict_inode
  - fs/ext4/super.c:perf_trace_ext4_allocate_inode
  - fs/ext4/super.c:perf_trace_ext4_request_inode
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
```
```
In fs/jbd2/journal.c (ffffffff814bc820)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - fs/jbd2/journal.c:perf_trace_jbd2_shrink_checkpoint_list
  - fs/jbd2/journal.c:perf_trace_jbd2_shrink_scan_exit
  - fs/jbd2/journal.c:perf_trace_jbd2_journal_shrink
  - fs/jbd2/journal.c:perf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:perf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:perf_trace_jbd2_update_log_tail
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_run_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_extend
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_start_class
  - fs/jbd2/journal.c:perf_trace_jbd2_submit_inode_data
  - fs/jbd2/journal.c:perf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint
```
```
In security/selinux/avc.c (ffffffff8152b00d)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_get_hash_stats
  - security/selinux/avc.c:perf_trace_selinux_audited
```
```
In block/blk-core.c (ffffffff815cb522)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_unplug
  - block/blk-core.c:perf_trace_block_plug
  - block/blk-core.c:perf_trace_block_bio
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_buffer
```
```
In block/blk-ioc.c (ffffffff815d1d2d)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff815f30f2)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In block/blk-iocost.c (ffffffff815fcd77)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_iocg_forgive_debt
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_state
```
```
In block/blk-wbt.c (ffffffff8160597a)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In arch/x86/lib/msr.c (ffffffff8165c552)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff81686532)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/pwm/core.c (ffffffff8169407d)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/pwm/core.c:perf_trace_pwm
```
```
In drivers/clk/clk.c (ffffffff817795c0)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate_range
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff817a85c2)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff817f3e19)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/char/random.c:perf_trace_prandom_u32
  - drivers/char/random.c:perf_trace_urandom_read
  - drivers/char/random.c:perf_trace_random__extract_entropy
  - drivers/char/random.c:perf_trace_random__get_random_bytes
  - drivers/char/random.c:perf_trace_add_disk_randomness
  - drivers/char/random.c:perf_trace_add_input_randomness
  - drivers/char/random.c:perf_trace_debit_entropy
  - drivers/char/random.c:perf_trace_credit_entropy_bits
  - drivers/char/random.c:perf_trace_random__mix_pool_bytes
  - drivers/char/random.c:perf_trace_add_device_randomness
```
```
In drivers/iommu/intel/trace.c (ffffffff81820263)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/iommu/intel/trace.c:perf_trace_prq_report
  - drivers/iommu/intel/trace.c:perf_trace_qi_submit
```
```
In drivers/iommu/iommu-traces.c (ffffffff818299d4)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff8185fc7c)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
```
```
In drivers/base/trace.c (ffffffff8186bf02)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/base/trace.c:perf_trace_devres
```
```
In drivers/dma-buf/dma-fence.c (ffffffff818a478c)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff818aa479)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff818abd83)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff818d1949)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff818faa0e)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_set_cs
  - drivers/spi/spi.c:perf_trace_spi_setup
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81907e2d)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff819a6bea)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_dbc_log_request
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_doorbell
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_slot_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ep_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_free_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_trb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
```
```
In drivers/rtc/interface.c (ffffffff819c646d)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/rtc/interface.c:perf_trace_rtc_timer_class
  - drivers/rtc/interface.c:perf_trace_rtc_offset_class
  - drivers/rtc/interface.c:perf_trace_rtc_alarm_irq_enable
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_state
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_freq
  - drivers/rtc/interface.c:perf_trace_rtc_time_alarm_class
```
```
In drivers/i2c/i2c-core-base.c (ffffffff819cc31b)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff819d03cf)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff819e10f0)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff819e295f)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff819e95ec)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff81a39ee2)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffffffff81a59e44)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_sensorhub_filter
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_sensorhub_data
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_sensorhub_timestamp
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_start
```
```
In drivers/devfreq/devfreq.c (ffffffff81a64602)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_frequency
```
```
In drivers/ras/ras.c (ffffffff81a6c812)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_memory_failure_event
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_non_standard_event
  - drivers/ras/ras.c:perf_trace_arm_event
  - drivers/ras/ras.c:perf_trace_mc_event
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
```
```
In drivers/interconnect/core.c (ffffffff81a70da0)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_node_destroy
  - drivers/interconnect/core.c:perf_trace_icc_set_bw_end
  - drivers/interconnect/core.c:perf_trace_icc_set_bw
```
```
In net/core/net-traces.c (ffffffff81ae373a)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:perf_trace_neigh_create
  - net/core/net-traces.c:perf_trace_page_pool_update_nid
  - net/core/net-traces.c:perf_trace_page_pool_state_hold
  - net/core/net-traces.c:perf_trace_page_pool_state_release
  - net/core/net-traces.c:perf_trace_page_pool_release
  - net/core/net-traces.c:perf_trace_br_fdb_update
  - net/core/net-traces.c:perf_trace_fdb_delete
  - net/core/net-traces.c:perf_trace_br_fdb_external_learn_add
  - net/core/net-traces.c:perf_trace_br_fdb_add
  - net/core/net-traces.c:perf_trace_qdisc_create
  - net/core/net-traces.c:perf_trace_qdisc_destroy
  - net/core/net-traces.c:perf_trace_qdisc_reset
  - net/core/net-traces.c:perf_trace_qdisc_enqueue
  - net/core/net-traces.c:perf_trace_qdisc_dequeue
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:perf_trace_inet_sk_error_report
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_rcvqueue_full
  - net/core/net-traces.c:perf_trace_napi_poll
  - net/core/net-traces.c:perf_trace_net_dev_rx_exit_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_template
  - net/core/net-traces.c:perf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:perf_trace_net_dev_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:perf_trace_consume_skb
  - net/core/net-traces.c:perf_trace_kfree_skb
```
```
In net/core/devlink.c (ffffffff81af10ae)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_trap_report
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/core/bpf_sk_storage.c (ffffffff81b0b18e)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
```
In net/netlink/af_netlink.c (ffffffff81b22813)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:perf_trace_netlink_extack
```
```
In net/bpf/test_run.c (ffffffff81b29e80)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b553f8)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b58acd)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7b3c9)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:listening_get_first
```
```
In net/ipv4/raw.c (ffffffff81b8558c)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81b88584)
Location: include/linux/list.h:828
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff81bacdee)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd3514)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/xfrm/xfrm_state.c (ffffffff81bddc40)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
```
```
In net/unix/af_unix.c (ffffffff81be4f62)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/anycast.c (ffffffff81bee9c3)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_anycast_cleanup
```
```
In net/ipv6/addrconf.c (ffffffff81c01c8e)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
```
```
In net/ipv6/route.c (ffffffff81c02ed8)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
```
In net/ipv6/raw.c (ffffffff81c214b9)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/packet/af_packet.c (ffffffff81c4f940)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_net_exit
```
```
In net/xdp/xsk.c (ffffffff81c722e5)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_net_exit
```
```
In net/mptcp/protocol.c (ffffffff81c773a8)
Location: include/linux/list.h:828
Inline: True
Inline callers:
  - net/mptcp/protocol.c:perf_trace_subflow_check_data_avail
  - net/mptcp/protocol.c:perf_trace_ack_update_msk
  - net/mptcp/protocol.c:perf_trace_mptcp_dump_mpext
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
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
In init/main.c (ffffffff8100104b)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810047b0)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff810380cb)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_set_ldt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_gdt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_load_idt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_multi
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_one_user
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_alloc_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu__set_pte
  - arch/x86/xen/trace.c:perf_trace_xen_mc_extend_args
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush_reason
  - arch/x86/xen/trace.c:perf_trace_xen_mc_callback
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry_alloc
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mc__batch
```
```
In arch/x86/hyperv/mmu.c (ffffffff8103cf7b)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_one
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_multi
```
```
In arch/x86/kernel/irq.c (ffffffff81044541)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:perf_trace_vector_free_moved
  - arch/x86/kernel/irq.c:perf_trace_vector_setup
  - arch/x86/kernel/irq.c:perf_trace_vector_teardown
  - arch/x86/kernel/irq.c:perf_trace_vector_activate
  - arch/x86/kernel/irq.c:perf_trace_vector_alloc_managed
  - arch/x86/kernel/irq.c:perf_trace_vector_alloc
  - arch/x86/kernel/irq.c:perf_trace_vector_reserve
  - arch/x86/kernel/irq.c:perf_trace_vector_mod
  - arch/x86/kernel/irq.c:perf_trace_vector_config
  - arch/x86/kernel/irq.c:perf_trace_x86_irq_vector
```
```
In arch/x86/kernel/nmi.c (ffffffff81047685)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff810526c6)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81066aed)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8107b59b)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/fault.c (ffffffff810a9b7d)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In kernel/fork.c (ffffffff810c787c)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_show_fdinfo
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff810cf158)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/exit.c (ffffffff810d20e9)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/softirq.c (ffffffff810d3e40)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810dd48f)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810ef30b)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_end
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_activate_work
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
```
```
In kernel/pid.c (ffffffff810f7458)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:__change_pid
```
```
In kernel/sched/core.c (ffffffff811079f0)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_wake_idle_without_ipi
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:perf_trace_sched_process_hang
  - kernel/sched/core.c:perf_trace_sched_pi_setprio
  - kernel/sched/core.c:perf_trace_sched_stat_runtime
  - kernel/sched/core.c:perf_trace_sched_process_exec
  - kernel/sched/core.c:perf_trace_sched_process_fork
  - kernel/sched/core.c:perf_trace_sched_process_wait
  - kernel/sched/core.c:perf_trace_sched_process_template
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:perf_trace_sched_kthread_work_execute_end
  - kernel/sched/core.c:perf_trace_sched_kthread_work_execute_start
  - kernel/sched/core.c:perf_trace_sched_kthread_work_queue_work
  - kernel/sched/core.c:perf_trace_sched_kthread_stop_ret
  - kernel/sched/core.c:perf_trace_sched_kthread_stop
```
```
In kernel/locking/mutex.c (ffffffff8114d6db)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/locking/mutex.c:perf_trace_contention_end
  - kernel/locking/mutex.c:perf_trace_contention_begin
```
```
In kernel/printk/printk.c (ffffffff8115ae68)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff811712c6)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff8117260b)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_stall_warning
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff81188442)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/entry/common.c (ffffffff81189ac1)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/entry/common.c:perf_trace_sys_exit
  - kernel/entry/common.c:perf_trace_sys_enter
```
```
In kernel/module/main.c (ffffffff8118ba81)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/module/main.c:perf_trace_module_request
  - kernel/module/main.c:perf_trace_module_refcnt
  - kernel/module/main.c:perf_trace_module_free
  - kernel/module/main.c:perf_trace_module_load
```
```
In kernel/time/timer.c (ffffffff8119a19f)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:__run_timers
  - kernel/time/timer.c:perf_trace_tick_stop
  - kernel/time/timer.c:perf_trace_itimer_expire
  - kernel/time/timer.c:perf_trace_itimer_state
  - kernel/time/timer.c:perf_trace_hrtimer_class
  - kernel/time/timer.c:perf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:perf_trace_hrtimer_start
  - kernel/time/timer.c:perf_trace_hrtimer_init
  - kernel/time/timer.c:perf_trace_timer_expire_entry
  - kernel/time/timer.c:perf_trace_timer_start
  - kernel/time/timer.c:perf_trace_timer_class
```
```
In kernel/time/alarmtimer.c (ffffffff811a377a)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811a8d9f)
Location: include/linux/list.h:874
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff811c25db)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/ftrace.c (ffffffff8120b6e5)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:profile_graph_return
```
```
In kernel/trace/trace_syscalls.c (ffffffff8123e274)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/bpf_trace.c (ffffffff8125614c)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_trace_bpf_trace_printk
```
```
In kernel/trace/trace_kprobe.c (ffffffff8125c4a0)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/error_report-traces.c (ffffffff8125dfab)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/trace/error_report-traces.c:perf_trace_error_report_template
```
```
In kernel/trace/power-traces.c (ffffffff8125fe41)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:perf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update
  - kernel/trace/power-traces.c:perf_trace_cpu_latency_qos_request
  - kernel/trace/power-traces.c:perf_trace_power_domain
  - kernel/trace/power-traces.c:perf_trace_clock
  - kernel/trace/power-traces.c:perf_trace_wakeup_source
  - kernel/trace/power-traces.c:perf_trace_suspend_resume
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:perf_trace_cpu_frequency_limits
  - kernel/trace/power-traces.c:perf_trace_pstate_sample
  - kernel/trace/power-traces.c:perf_trace_powernv_throttle
  - kernel/trace/power-traces.c:perf_trace_cpu
```
```
In kernel/trace/rpm-traces.c (ffffffff812616a1)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffffffff8126576c)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/core.c (ffffffff8126aca4)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_mem_return_failed
  - kernel/bpf/core.c:perf_trace_mem_connect
  - kernel/bpf/core.c:perf_trace_mem_disconnect
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_bulk_tx
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff812a7680)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
```
```
In kernel/bpf/trampoline.c (ffffffff812a98f8)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_put
```
```
In kernel/events/core.c (ffffffff812d4f1a)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/events/core.c:perf_trace_run_bpf_submit
```
```
In kernel/user-return-notifier.c (ffffffff812e9422)
Location: include/linux/list.h:874
Inline: True
```
```
In kernel/rseq.c (ffffffff812ec162)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In kernel/watch_queue.c (ffffffff812eddf8)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
```
```
In mm/filemap.c (ffffffff812eec03)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff812f87fe)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:perf_trace_skip_task_reaping
  - mm/oom_kill.c:perf_trace_finish_task_reaping
  - mm/oom_kill.c:perf_trace_start_task_reaping
  - mm/oom_kill.c:perf_trace_wake_reaper
  - mm/oom_kill.c:perf_trace_mark_victim
  - mm/oom_kill.c:perf_trace_reclaim_retry_zone
  - mm/oom_kill.c:perf_trace_oom_score_adj_update
```
```
In mm/swap.c (ffffffff81302950)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff8130b6fb)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - mm/vmscan.c:perf_trace_mm_vmscan_throttled
  - mm/vmscan.c:perf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:perf_trace_mm_vmscan_write_folio
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_isolate
  - mm/vmscan.c:perf_trace_mm_shrink_slab_end
  - mm/vmscan.c:perf_trace_mm_shrink_slab_start
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_end_template
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:perf_trace_mm_vmscan_wakeup_kswapd
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_wake
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_sleep
```
```
In mm/percpu.c (ffffffff81325320)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff8132ad4f)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - mm/slab_common.c:perf_trace_rss_stat
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:perf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:perf_trace_mm_page
  - mm/slab_common.c:perf_trace_mm_page_alloc
  - mm/slab_common.c:perf_trace_mm_page_free_batched
  - mm/slab_common.c:perf_trace_mm_page_free
  - mm/slab_common.c:perf_trace_kmem_cache_free
  - mm/slab_common.c:perf_trace_kfree
  - mm/slab_common.c:perf_trace_kmem_alloc_node
  - mm/slab_common.c:perf_trace_kmem_alloc
```
```
In mm/compaction.c (ffffffff8132d6b5)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - mm/compaction.c:perf_trace_kcompactd_wake_template
  - mm/compaction.c:perf_trace_mm_compaction_kcompactd_sleep
  - mm/compaction.c:perf_trace_mm_compaction_defer_template
  - mm/compaction.c:perf_trace_mm_compaction_suitable_template
  - mm/compaction.c:perf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:perf_trace_mm_compaction_end
  - mm/compaction.c:perf_trace_mm_compaction_begin
  - mm/compaction.c:perf_trace_mm_compaction_migratepages
  - mm/compaction.c:perf_trace_mm_compaction_isolate_template
```
```
In mm/mmap_lock.c (ffffffff8133c0e0)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - mm/mmap_lock.c:perf_trace_mmap_lock_acquire_returned
  - mm/mmap_lock.c:perf_trace_mmap_lock
```
```
In mm/mmap.c (ffffffff8134d027)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - mm/mmap.c:perf_trace_vm_unmapped_area
```
```
In mm/rmap.c (ffffffff8135a945)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - mm/rmap.c:perf_trace_migration_pte
  - mm/rmap.c:perf_trace_mm_migrate_pages_start
  - mm/rmap.c:perf_trace_mm_migrate_pages
  - mm/rmap.c:perf_trace_tlb_flush
```
```
In mm/mmu_notifier.c (ffffffff8139dd34)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_subscriptions_destroy
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_release
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (ffffffff8139e734)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
```
```
In mm/huge_memory.c (ffffffff813b8a7b)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - mm/huge_memory.c:perf_trace_migration_pmd
  - mm/huge_memory.c:perf_trace_hugepage_update
  - mm/huge_memory.c:perf_trace_hugepage_set_pmd
```
```
In mm/khugepaged.c (ffffffff813c27b0)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff813dd8f7)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In fs/super.c (ffffffff813f68fa)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - fs/super.c:reconfigure_super
```
```
In fs/dcache.c (ffffffff814141a2)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_find_alias_rcu
  - fs/dcache.c:d_find_alias
  - fs/dcache.c:d_find_alias
```
```
In fs/namespace.c (ffffffff814231a7)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:namespace_unlock
```
```
In fs/seq_file.c (ffffffff8142663b)
Location: include/linux/list.h:874
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8142f2bc)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_writeback_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_pages_written
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_folio_template
```
```
In fs/notify/mark.c (ffffffff8144f38f)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff814559c0)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
```
```
In fs/eventpoll.c (ffffffff81459b79)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:reverse_path_check_proc
```
```
In fs/dax.c (ffffffff81466977)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - fs/dax.c:perf_trace_dax_writeback_one
  - fs/dax.c:perf_trace_dax_writeback_range_class
  - fs/dax.c:perf_trace_dax_insert_mapping
  - fs/dax.c:perf_trace_dax_pte_fault_class
  - fs/dax.c:perf_trace_dax_pmd_insert_mapping_class
  - fs/dax.c:perf_trace_dax_pmd_load_hole_class
  - fs/dax.c:perf_trace_dax_pmd_fault_class
```
```
In fs/locks.c (ffffffff81476045)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/iomap/trace.c (ffffffff81487358)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - fs/iomap/trace.c:perf_trace_iomap_iter
  - fs/iomap/trace.c:perf_trace_iomap_class
  - fs/iomap/trace.c:perf_trace_iomap_range_class
  - fs/iomap/trace.c:perf_trace_iomap_readpage_class
```
```
In fs/ext4/super.c (ffffffff81518749)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_update_sb
  - fs/ext4/super.c:perf_trace_ext4_fc_cleanup
  - fs/ext4/super.c:perf_trace_ext4_fc_track_range
  - fs/ext4/super.c:perf_trace_ext4_fc_track_inode
  - fs/ext4/super.c:perf_trace_ext4_fc_track_dentry
  - fs/ext4/super.c:perf_trace_ext4_fc_stats
  - fs/ext4/super.c:perf_trace_ext4_fc_commit_stop
  - fs/ext4/super.c:perf_trace_ext4_fc_commit_start
  - fs/ext4/super.c:perf_trace_ext4_fc_replay
  - fs/ext4/super.c:perf_trace_ext4_fc_replay_scan
  - fs/ext4/super.c:perf_trace_ext4_lazy_itable_init
  - fs/ext4/super.c:perf_trace_ext4_prefetch_bitmaps
  - fs/ext4/super.c:perf_trace_ext4_error
  - fs/ext4/super.c:perf_trace_ext4_shutdown
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:perf_trace_ext4_insert_range
  - fs/ext4/super.c:perf_trace_ext4_collapse_range
  - fs/ext4/super.c:perf_trace_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:perf_trace_ext4__es_shrink_enter
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_enter
  - fs/ext4/super.c:perf_trace_ext4_es_remove_extent
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_idx
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_show_extent
  - fs/ext4/super.c:perf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:perf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:perf_trace_ext4__trim
  - fs/ext4/super.c:perf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:perf_trace_ext4_journal_start
  - fs/ext4/super.c:perf_trace_ext4_load_inode
  - fs/ext4/super.c:perf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_exit
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_enter
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:perf_trace_ext4__truncate
  - fs/ext4/super.c:perf_trace_ext4_unlink_exit
  - fs/ext4/super.c:perf_trace_ext4_unlink_enter
  - fs/ext4/super.c:perf_trace_ext4_fallocate_exit
  - fs/ext4/super.c:perf_trace_ext4__fallocate_mode
  - fs/ext4/super.c:perf_trace_ext4_read_block_bitmap_load
  - fs/ext4/super.c:perf_trace_ext4__bitmap_load
  - fs/ext4/super.c:perf_trace_ext4_da_release_space
  - fs/ext4/super.c:perf_trace_ext4_da_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_da_update_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_forget
  - fs/ext4/super.c:perf_trace_ext4__mballoc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_prealloc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_alloc
  - fs/ext4/super.c:perf_trace_ext4_alloc_da_blocks
  - fs/ext4/super.c:perf_trace_ext4_sync_fs
  - fs/ext4/super.c:perf_trace_ext4_sync_file_exit
  - fs/ext4/super.c:perf_trace_ext4_sync_file_enter
  - fs/ext4/super.c:perf_trace_ext4_free_blocks
  - fs/ext4/super.c:perf_trace_ext4_allocate_blocks
  - fs/ext4/super.c:perf_trace_ext4_request_blocks
  - fs/ext4/super.c:perf_trace_ext4_mb_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_mb_release_group_pa
  - fs/ext4/super.c:perf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:perf_trace_ext4__mb_new_pa
  - fs/ext4/super.c:perf_trace_ext4_discard_blocks
  - fs/ext4/super.c:perf_trace_ext4_invalidate_folio_op
  - fs/ext4/super.c:perf_trace_ext4__page_op
  - fs/ext4/super.c:perf_trace_ext4_writepages_result
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages_extent
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages
  - fs/ext4/super.c:perf_trace_ext4_writepages
  - fs/ext4/super.c:perf_trace_ext4__write_end
  - fs/ext4/super.c:perf_trace_ext4__write_begin
  - fs/ext4/super.c:perf_trace_ext4_begin_ordered_truncate
  - fs/ext4/super.c:perf_trace_ext4_mark_inode_dirty
  - fs/ext4/super.c:perf_trace_ext4_nfs_commit_metadata
  - fs/ext4/super.c:perf_trace_ext4_drop_inode
  - fs/ext4/super.c:perf_trace_ext4_evict_inode
  - fs/ext4/super.c:perf_trace_ext4_allocate_inode
  - fs/ext4/super.c:perf_trace_ext4_request_inode
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
```
```
In fs/jbd2/journal.c (ffffffff81546b74)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - fs/jbd2/journal.c:perf_trace_jbd2_shrink_checkpoint_list
  - fs/jbd2/journal.c:perf_trace_jbd2_shrink_scan_exit
  - fs/jbd2/journal.c:perf_trace_jbd2_journal_shrink
  - fs/jbd2/journal.c:perf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:perf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:perf_trace_jbd2_update_log_tail
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_run_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_extend
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_start_class
  - fs/jbd2/journal.c:perf_trace_jbd2_submit_inode_data
  - fs/jbd2/journal.c:perf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint
```
```
In security/selinux/avc.c (ffffffff815c0a29)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_get_hash_stats
  - security/selinux/avc.c:perf_trace_selinux_audited
```
```
In block/blk-core.c (ffffffff816773f5)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_unplug
  - block/blk-core.c:perf_trace_block_plug
  - block/blk-core.c:perf_trace_block_bio
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_completion
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_buffer
```
```
In block/blk-ioc.c (ffffffff8167dbed)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff816a4669)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_unpin_online
```
```
In block/blk-iocost.c (ffffffff816ad32d)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_iocg_forgive_debt
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_state
```
```
In block/blk-wbt.c (ffffffff816b922c)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In io_uring/io_uring.c (ffffffff816c5b4d)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - io_uring/io_uring.c:perf_trace_io_uring_cqe_overflow
  - io_uring/io_uring.c:perf_trace_io_uring_req_failed
  - io_uring/io_uring.c:perf_trace_io_uring_task_add
  - io_uring/io_uring.c:perf_trace_io_uring_poll_arm
  - io_uring/io_uring.c:perf_trace_io_uring_submit_sqe
  - io_uring/io_uring.c:perf_trace_io_uring_complete
  - io_uring/io_uring.c:perf_trace_io_uring_fail_link
  - io_uring/io_uring.c:perf_trace_io_uring_cqring_wait
  - io_uring/io_uring.c:perf_trace_io_uring_link
  - io_uring/io_uring.c:perf_trace_io_uring_defer
  - io_uring/io_uring.c:perf_trace_io_uring_queue_async_work
  - io_uring/io_uring.c:perf_trace_io_uring_file_get
  - io_uring/io_uring.c:perf_trace_io_uring_register
  - io_uring/io_uring.c:perf_trace_io_uring_create
```
```
In arch/x86/lib/msr.c (ffffffff81775625)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff817a2f55)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/pwm/core.c (ffffffff817b4d6f)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/pwm/core.c:perf_trace_pwm
```
```
In drivers/clk/clk.c (ffffffff818af93c)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate_range
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff818e1ed9)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/iommu/intel/trace.c (ffffffff8195fd7d)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/iommu/intel/trace.c:perf_trace_prq_report
  - drivers/iommu/intel/trace.c:perf_trace_qi_submit
```
```
In drivers/iommu/iommu-traces.c (ffffffff8196988e)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff819a6e19)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
```
```
In drivers/base/trace.c (ffffffff819b4bb3)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/base/trace.c:perf_trace_devres
```
```
In drivers/dma-buf/dma-fence.c (ffffffff819ee117)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff819f4528)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff819f6716)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff81a2056d)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_sff_template
  - drivers/ata/libata-core.c:perf_trace_ata_transfer_data_template
  - drivers/ata/libata-core.c:perf_trace_ata_sff_hsm_template
  - drivers/ata/libata-core.c:perf_trace_ata_port_eh_begin_template
  - drivers/ata/libata-core.c:perf_trace_ata_link_reset_end_template
  - drivers/ata/libata-core.c:perf_trace_ata_link_reset_begin_template
  - drivers/ata/libata-core.c:perf_trace_ata_eh_action_template
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_bmdma_status
  - drivers/ata/libata-core.c:perf_trace_ata_exec_command_template
  - drivers/ata/libata-core.c:perf_trace_ata_tf_load
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue_template
```
```
In drivers/spi/spi.c (ffffffff81a48d0b)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_set_cs
  - drivers/spi/spi.c:perf_trace_spi_setup
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81a5af68)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81b049fd)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_dbc_log_request
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_doorbell
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_slot_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ep_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_free_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_trb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
```
```
In drivers/rtc/interface.c (ffffffff81b26da0)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/rtc/interface.c:perf_trace_rtc_timer_class
  - drivers/rtc/interface.c:perf_trace_rtc_offset_class
  - drivers/rtc/interface.c:perf_trace_rtc_alarm_irq_enable
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_state
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_freq
  - drivers/rtc/interface.c:perf_trace_rtc_time_alarm_class
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81b2db9e)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81b323b2)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff81b44d6a)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff81b47374)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81b4f232)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/cpufreq/amd-pstate-trace.c (ffffffff81b97963)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate-trace.c:perf_trace_amd_pstate_perf
```
```
In drivers/mmc/core/core.c (ffffffff81ba5237)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffffffff81bc994a)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_start
```
```
In drivers/devfreq/devfreq.c (ffffffff81bd1c44)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_frequency
```
```
In drivers/ras/ras.c (ffffffff81bdd415)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_memory_failure_event
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_non_standard_event
  - drivers/ras/ras.c:perf_trace_arm_event
  - drivers/ras/ras.c:perf_trace_mc_event
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
```
```
In drivers/interconnect/core.c (ffffffff81be245e)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_node_destroy
  - drivers/interconnect/core.c:perf_trace_icc_set_bw_end
  - drivers/interconnect/core.c:perf_trace_icc_set_bw
```
```
In net/core/net-traces.c (ffffffff81c683d7)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:perf_trace_neigh_create
  - net/core/net-traces.c:perf_trace_page_pool_update_nid
  - net/core/net-traces.c:perf_trace_page_pool_state_hold
  - net/core/net-traces.c:perf_trace_page_pool_state_release
  - net/core/net-traces.c:perf_trace_page_pool_release
  - net/core/net-traces.c:perf_trace_br_fdb_update
  - net/core/net-traces.c:perf_trace_fdb_delete
  - net/core/net-traces.c:perf_trace_br_fdb_external_learn_add
  - net/core/net-traces.c:perf_trace_br_fdb_add
  - net/core/net-traces.c:perf_trace_qdisc_create
  - net/core/net-traces.c:perf_trace_qdisc_destroy
  - net/core/net-traces.c:perf_trace_qdisc_reset
  - net/core/net-traces.c:perf_trace_qdisc_enqueue
  - net/core/net-traces.c:perf_trace_qdisc_dequeue
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:perf_trace_tcp_cong_state_set
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:perf_trace_inet_sk_error_report
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_rcvqueue_full
  - net/core/net-traces.c:perf_trace_napi_poll
  - net/core/net-traces.c:perf_trace_net_dev_rx_exit_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_template
  - net/core/net-traces.c:perf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:perf_trace_net_dev_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:perf_trace_consume_skb
  - net/core/net-traces.c:perf_trace_kfree_skb
```
```
In net/core/devlink.c (ffffffff81c747e9)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_trap_report
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/core/bpf_sk_storage.c (ffffffff81c9209d)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
```
In net/netlink/af_netlink.c (ffffffff81ca9bec)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:perf_trace_netlink_extack
```
```
In net/bpf/test_run.c (ffffffff81cb30f3)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce30ef)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce6ce3)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse
```
```
In net/ipv4/udp.c (ffffffff81d199ac)
Location: include/linux/list.h:874
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff81d3fd3b)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d68a84)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/xfrm/xfrm_state.c (ffffffff81d74960)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
```
```
In net/unix/af_unix.c (ffffffff81d7cd7d)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_get_first
```
```
In net/ipv6/anycast.c (ffffffff81d86f53)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_anycast_cleanup
```
```
In net/ipv6/addrconf.c (ffffffff81d94d97)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_exit_net
```
```
In net/ipv6/route.c (ffffffff81d9cda8)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
```
In net/packet/af_packet.c (ffffffff81df03c0)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_net_exit
```
```
In net/xdp/xsk.c (ffffffff81e15ec5)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_net_exit
```
```
In net/mptcp/protocol.c (ffffffff81e1bfbb)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - net/mptcp/protocol.c:perf_trace_subflow_check_data_avail
  - net/mptcp/protocol.c:perf_trace_ack_update_msk
  - net/mptcp/protocol.c:perf_trace_mptcp_dump_mpext
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
```
```
In net/mctp/af_mctp.c (ffffffff81e368fd)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:perf_trace_mctp_key_release
  - net/mctp/af_mctp.c:perf_trace_mctp_key_acquire
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
In init/main.c (ffffffff810015d8)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8100516d)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff81040168)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_set_ldt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_gdt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_load_idt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_multi
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_one_user
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_alloc_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu__set_pte
  - arch/x86/xen/trace.c:perf_trace_xen_mc_extend_args
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush_reason
  - arch/x86/xen/trace.c:perf_trace_xen_mc_callback
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry_alloc
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mc__batch
```
```
In arch/x86/hyperv/mmu.c (ffffffff81045c58)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_one
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_multi
```
```
In arch/x86/kernel/irq.c (ffffffff8104e24e)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:perf_trace_vector_free_moved
  - arch/x86/kernel/irq.c:perf_trace_vector_setup
  - arch/x86/kernel/irq.c:perf_trace_vector_teardown
  - arch/x86/kernel/irq.c:perf_trace_vector_activate
  - arch/x86/kernel/irq.c:perf_trace_vector_alloc_managed
  - arch/x86/kernel/irq.c:perf_trace_vector_alloc
  - arch/x86/kernel/irq.c:perf_trace_vector_reserve
  - arch/x86/kernel/irq.c:perf_trace_vector_mod
  - arch/x86/kernel/irq.c:perf_trace_vector_config
  - arch/x86/kernel/irq.c:perf_trace_x86_irq_vector
```
```
In arch/x86/kernel/nmi.c (ffffffff810520a2)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81060733)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81075e2a)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108c8f8)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/fault.c (ffffffff810c2fda)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In kernel/fork.c (ffffffff810e43ec)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_show_fdinfo
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff810ed5a6)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/exit.c (ffffffff810f0b5d)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/softirq.c (ffffffff810f2c0d)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810fd88c)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff811109e8)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_end
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_activate_work
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
```
```
In kernel/pid.c (ffffffff81119bc8)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:__change_pid
```
```
In kernel/sched/core.c (ffffffff8112dd7d)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_wake_idle_without_ipi
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:perf_trace_sched_process_hang
  - kernel/sched/core.c:perf_trace_sched_pi_setprio
  - kernel/sched/core.c:perf_trace_sched_stat_runtime
  - kernel/sched/core.c:perf_trace_sched_process_exec
  - kernel/sched/core.c:perf_trace_sched_process_fork
  - kernel/sched/core.c:perf_trace_sched_process_wait
  - kernel/sched/core.c:perf_trace_sched_process_template
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:perf_trace_sched_kthread_work_execute_end
  - kernel/sched/core.c:perf_trace_sched_kthread_work_execute_start
  - kernel/sched/core.c:perf_trace_sched_kthread_work_queue_work
  - kernel/sched/core.c:perf_trace_sched_kthread_stop_ret
  - kernel/sched/core.c:perf_trace_sched_kthread_stop
```
```
In kernel/locking/mutex.c (ffffffff8117c7e8)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/locking/mutex.c:perf_trace_contention_end
  - kernel/locking/mutex.c:perf_trace_contention_begin
```
```
In kernel/printk/printk.c (ffffffff8118da42)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/printk/printk.c:unregister_console_locked
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff811a78b3)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff811a8f48)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_stall_warning
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff811c433f)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/entry/common.c (ffffffff811c5f5e)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/entry/common.c:perf_trace_sys_exit
  - kernel/entry/common.c:perf_trace_sys_enter
```
```
In kernel/module/main.c (ffffffff811c814e)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/module/main.c:perf_trace_module_request
  - kernel/module/main.c:perf_trace_module_refcnt
  - kernel/module/main.c:perf_trace_module_free
  - kernel/module/main.c:perf_trace_module_load
```
```
In kernel/time/timer.c (ffffffff811d88a9)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:__run_timers
  - kernel/time/timer.c:perf_trace_tick_stop
  - kernel/time/timer.c:perf_trace_itimer_expire
  - kernel/time/timer.c:perf_trace_itimer_state
  - kernel/time/timer.c:perf_trace_hrtimer_class
  - kernel/time/timer.c:perf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:perf_trace_hrtimer_start
  - kernel/time/timer.c:perf_trace_hrtimer_init
  - kernel/time/timer.c:perf_trace_timer_expire_entry
  - kernel/time/timer.c:perf_trace_timer_start
  - kernel/time/timer.c:perf_trace_timer_class
```
```
In kernel/time/alarmtimer.c (ffffffff811e2e07)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811e8bef)
Location: include/linux/list.h:874
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81204948)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/ftrace.c (ffffffff81254117)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:profile_graph_return
```
```
In kernel/trace/trace_syscalls.c (ffffffff8128bc41)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/bpf_trace.c (ffffffff812a5799)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_trace_bpf_trace_printk
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ae010)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/error_report-traces.c (ffffffff812aea88)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/trace/error_report-traces.c:perf_trace_error_report_template
```
```
In kernel/trace/power-traces.c (ffffffff812aff02)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:perf_trace_guest_halt_poll_ns
  - kernel/trace/power-traces.c:perf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update
  - kernel/trace/power-traces.c:perf_trace_cpu_latency_qos_request
  - kernel/trace/power-traces.c:perf_trace_power_domain
  - kernel/trace/power-traces.c:perf_trace_clock
  - kernel/trace/power-traces.c:perf_trace_wakeup_source
  - kernel/trace/power-traces.c:perf_trace_suspend_resume
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:perf_trace_cpu_frequency_limits
  - kernel/trace/power-traces.c:perf_trace_pstate_sample
  - kernel/trace/power-traces.c:perf_trace_powernv_throttle
  - kernel/trace/power-traces.c:perf_trace_cpu_idle_miss
  - kernel/trace/power-traces.c:perf_trace_cpu
```
```
In kernel/trace/rpm-traces.c (ffffffff812b2d5e)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffffffff812b80a1)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/trace/rv/rv.c (ffffffff812bbdaa)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/trace/rv/rv.c:perf_trace_error_da_monitor_id
  - kernel/trace/rv/rv.c:perf_trace_event_da_monitor_id
```
```
In kernel/bpf/core.c (ffffffff812bfd31)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_mem_return_failed
  - kernel/bpf/core.c:perf_trace_mem_connect
  - kernel/bpf/core.c:perf_trace_mem_disconnect
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_bulk_tx
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff81305da0)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
```
```
In kernel/bpf/trampoline.c (ffffffff8130846f)
Location: include/linux/list.h:874
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff81327c2c)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
```
In kernel/events/core.c (ffffffff8133d6e7)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/events/core.c:perf_trace_run_bpf_submit
```
```
In kernel/user-return-notifier.c (ffffffff81353192)
Location: include/linux/list.h:874
Inline: True
```
```
In kernel/rseq.c (ffffffff8135636f)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In kernel/watch_queue.c (ffffffff81358218)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
```
```
In mm/filemap.c (ffffffff81359320)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff8136224b)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:perf_trace_skip_task_reaping
  - mm/oom_kill.c:perf_trace_finish_task_reaping
  - mm/oom_kill.c:perf_trace_start_task_reaping
  - mm/oom_kill.c:perf_trace_wake_reaper
  - mm/oom_kill.c:perf_trace_mark_victim
  - mm/oom_kill.c:perf_trace_reclaim_retry_zone
  - mm/oom_kill.c:perf_trace_oom_score_adj_update
```
```
In mm/swap.c (ffffffff8136cf8d)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff81375ab8)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - mm/vmscan.c:perf_trace_mm_vmscan_throttled
  - mm/vmscan.c:perf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:perf_trace_mm_vmscan_write_folio
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_isolate
  - mm/vmscan.c:perf_trace_mm_shrink_slab_end
  - mm/vmscan.c:perf_trace_mm_shrink_slab_start
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_end_template
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:perf_trace_mm_vmscan_wakeup_kswapd
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_wake
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_sleep
```
```
In mm/percpu.c (ffffffff81399e5d)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff813a009b)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - mm/slab_common.c:perf_trace_rss_stat
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:perf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:perf_trace_mm_page
  - mm/slab_common.c:perf_trace_mm_page_alloc
  - mm/slab_common.c:perf_trace_mm_page_free_batched
  - mm/slab_common.c:perf_trace_mm_page_free
  - mm/slab_common.c:perf_trace_kmem_cache_free
  - mm/slab_common.c:perf_trace_kfree
  - mm/slab_common.c:perf_trace_kmalloc
  - mm/slab_common.c:perf_trace_kmem_cache_alloc
```
```
In mm/compaction.c (ffffffff813a3d12)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - mm/compaction.c:perf_trace_kcompactd_wake_template
  - mm/compaction.c:perf_trace_mm_compaction_kcompactd_sleep
  - mm/compaction.c:perf_trace_mm_compaction_defer_template
  - mm/compaction.c:perf_trace_mm_compaction_suitable_template
  - mm/compaction.c:perf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:perf_trace_mm_compaction_end
  - mm/compaction.c:perf_trace_mm_compaction_begin
  - mm/compaction.c:perf_trace_mm_compaction_migratepages
  - mm/compaction.c:perf_trace_mm_compaction_isolate_template
```
```
In mm/mmap_lock.c (ffffffff813b3bfd)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - mm/mmap_lock.c:perf_trace_mmap_lock_acquire_returned
  - mm/mmap_lock.c:perf_trace_mmap_lock
```
```
In mm/mmap.c (ffffffff813c5cb1)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - mm/mmap.c:perf_trace_exit_mmap
  - mm/mmap.c:perf_trace_vma_store
  - mm/mmap.c:perf_trace_vma_mas_szero
  - mm/mmap.c:perf_trace_vm_unmapped_area
```
```
In mm/rmap.c (ffffffff813d54a2)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - mm/rmap.c:perf_trace_migration_pte
  - mm/rmap.c:perf_trace_mm_migrate_pages_start
  - mm/rmap.c:perf_trace_mm_migrate_pages
  - mm/rmap.c:perf_trace_tlb_flush
```
```
In mm/vmalloc.c (ffffffff813db764)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - mm/vmalloc.c:perf_trace_free_vmap_area_noflush
  - mm/vmalloc.c:perf_trace_purge_vmap_area_lazy
  - mm/vmalloc.c:perf_trace_alloc_vmap_area
```
```
In mm/mmu_notifier.c (ffffffff8141d2c4)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_subscriptions_destroy
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_release
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (ffffffff8141df44)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
```
```
In mm/huge_memory.c (ffffffff8143ac08)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - mm/huge_memory.c:perf_trace_migration_pmd
  - mm/huge_memory.c:perf_trace_hugepage_update
  - mm/huge_memory.c:perf_trace_hugepage_set_pmd
```
```
In mm/khugepaged.c (ffffffff8144668d)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_khugepaged_collapse_file
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_file
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff81464534)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In fs/super.c (ffffffff8147fa1d)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - fs/super.c:reconfigure_super
```
```
In fs/dcache.c (ffffffff8149f622)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_find_alias_rcu
  - fs/dcache.c:d_find_alias
  - fs/dcache.c:d_find_alias
```
```
In fs/namespace.c (ffffffff814af8c7)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:namespace_unlock
```
```
In fs/seq_file.c (ffffffff814b3262)
Location: include/linux/list.h:874
Inline: True
```
```
In fs/fs-writeback.c (ffffffff814bccf9)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_writeback_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_pages_written
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_folio_template
```
```
In fs/notify/mark.c (ffffffff814ddbff)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e4940)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
```
```
In fs/eventpoll.c (ffffffff814e8fe9)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:reverse_path_check_proc
```
```
In fs/dax.c (ffffffff814f6b34)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - fs/dax.c:perf_trace_dax_writeback_one
  - fs/dax.c:perf_trace_dax_writeback_range_class
  - fs/dax.c:perf_trace_dax_insert_mapping
  - fs/dax.c:perf_trace_dax_pte_fault_class
  - fs/dax.c:perf_trace_dax_pmd_insert_mapping_class
  - fs/dax.c:perf_trace_dax_pmd_load_hole_class
  - fs/dax.c:perf_trace_dax_pmd_fault_class
```
```
In fs/locks.c (ffffffff815085b2)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/iomap/trace.c (ffffffff8151ae18)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - fs/iomap/trace.c:perf_trace_iomap_iter
  - fs/iomap/trace.c:perf_trace_iomap_class
  - fs/iomap/trace.c:perf_trace_iomap_range_class
  - fs/iomap/trace.c:perf_trace_iomap_readpage_class
```
```
In fs/ext4/super.c (ffffffff815b4316)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_update_sb
  - fs/ext4/super.c:perf_trace_ext4_fc_cleanup
  - fs/ext4/super.c:perf_trace_ext4_fc_track_range
  - fs/ext4/super.c:perf_trace_ext4_fc_track_inode
  - fs/ext4/super.c:perf_trace_ext4_fc_track_dentry
  - fs/ext4/super.c:perf_trace_ext4_fc_stats
  - fs/ext4/super.c:perf_trace_ext4_fc_commit_stop
  - fs/ext4/super.c:perf_trace_ext4_fc_commit_start
  - fs/ext4/super.c:perf_trace_ext4_fc_replay
  - fs/ext4/super.c:perf_trace_ext4_fc_replay_scan
  - fs/ext4/super.c:perf_trace_ext4_lazy_itable_init
  - fs/ext4/super.c:perf_trace_ext4_prefetch_bitmaps
  - fs/ext4/super.c:perf_trace_ext4_error
  - fs/ext4/super.c:perf_trace_ext4_shutdown
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:perf_trace_ext4_insert_range
  - fs/ext4/super.c:perf_trace_ext4_collapse_range
  - fs/ext4/super.c:perf_trace_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:perf_trace_ext4__es_shrink_enter
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_enter
  - fs/ext4/super.c:perf_trace_ext4_es_remove_extent
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_idx
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_show_extent
  - fs/ext4/super.c:perf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:perf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:perf_trace_ext4__trim
  - fs/ext4/super.c:perf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:perf_trace_ext4_journal_start_inode
  - fs/ext4/super.c:perf_trace_ext4_journal_start_sb
  - fs/ext4/super.c:perf_trace_ext4_load_inode
  - fs/ext4/super.c:perf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_exit
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_enter
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:perf_trace_ext4__truncate
  - fs/ext4/super.c:perf_trace_ext4_unlink_exit
  - fs/ext4/super.c:perf_trace_ext4_unlink_enter
  - fs/ext4/super.c:perf_trace_ext4_fallocate_exit
  - fs/ext4/super.c:perf_trace_ext4__fallocate_mode
  - fs/ext4/super.c:perf_trace_ext4_read_block_bitmap_load
  - fs/ext4/super.c:perf_trace_ext4__bitmap_load
  - fs/ext4/super.c:perf_trace_ext4_da_release_space
  - fs/ext4/super.c:perf_trace_ext4_da_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_da_update_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_forget
  - fs/ext4/super.c:perf_trace_ext4__mballoc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_prealloc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_alloc
  - fs/ext4/super.c:perf_trace_ext4_alloc_da_blocks
  - fs/ext4/super.c:perf_trace_ext4_sync_fs
  - fs/ext4/super.c:perf_trace_ext4_sync_file_exit
  - fs/ext4/super.c:perf_trace_ext4_sync_file_enter
  - fs/ext4/super.c:perf_trace_ext4_free_blocks
  - fs/ext4/super.c:perf_trace_ext4_allocate_blocks
  - fs/ext4/super.c:perf_trace_ext4_request_blocks
  - fs/ext4/super.c:perf_trace_ext4_mb_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_mb_release_group_pa
  - fs/ext4/super.c:perf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:perf_trace_ext4__mb_new_pa
  - fs/ext4/super.c:perf_trace_ext4_discard_blocks
  - fs/ext4/super.c:perf_trace_ext4_invalidate_folio_op
  - fs/ext4/super.c:perf_trace_ext4__page_op
  - fs/ext4/super.c:perf_trace_ext4_writepages_result
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages_extent
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages
  - fs/ext4/super.c:perf_trace_ext4_writepages
  - fs/ext4/super.c:perf_trace_ext4__write_end
  - fs/ext4/super.c:perf_trace_ext4__write_begin
  - fs/ext4/super.c:perf_trace_ext4_begin_ordered_truncate
  - fs/ext4/super.c:perf_trace_ext4_mark_inode_dirty
  - fs/ext4/super.c:perf_trace_ext4_nfs_commit_metadata
  - fs/ext4/super.c:perf_trace_ext4_drop_inode
  - fs/ext4/super.c:perf_trace_ext4_evict_inode
  - fs/ext4/super.c:perf_trace_ext4_allocate_inode
  - fs/ext4/super.c:perf_trace_ext4_request_inode
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
```
```
In fs/jbd2/journal.c (ffffffff815e5f71)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - fs/jbd2/journal.c:perf_trace_jbd2_shrink_checkpoint_list
  - fs/jbd2/journal.c:perf_trace_jbd2_shrink_scan_exit
  - fs/jbd2/journal.c:perf_trace_jbd2_journal_shrink
  - fs/jbd2/journal.c:perf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:perf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:perf_trace_jbd2_update_log_tail
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_run_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_extend
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_start_class
  - fs/jbd2/journal.c:perf_trace_jbd2_submit_inode_data
  - fs/jbd2/journal.c:perf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint
```
```
In security/selinux/avc.c (ffffffff8166d009)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_get_hash_stats
  - security/selinux/avc.c:perf_trace_selinux_audited
```
```
In block/blk-core.c (ffffffff81733592)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_unplug
  - block/blk-core.c:perf_trace_block_plug
  - block/blk-core.c:perf_trace_block_bio
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_completion
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_buffer
```
```
In block/blk-ioc.c (ffffffff8173a81d)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff81763399)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_unpin_online
```
```
In block/blk-iocost.c (ffffffff8176bd46)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_iocg_forgive_debt
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_state
```
```
In block/blk-wbt.c (ffffffff817795b9)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In io_uring/io_uring.c (ffffffff8178b938)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:perf_trace_io_uring_local_work_run
  - io_uring/io_uring.c:perf_trace_io_uring_short_write
  - io_uring/io_uring.c:perf_trace_io_uring_task_work_run
  - io_uring/io_uring.c:perf_trace_io_uring_cqe_overflow
  - io_uring/io_uring.c:perf_trace_io_uring_req_failed
  - io_uring/io_uring.c:perf_trace_io_uring_task_add
  - io_uring/io_uring.c:perf_trace_io_uring_poll_arm
  - io_uring/io_uring.c:perf_trace_io_uring_submit_sqe
  - io_uring/io_uring.c:perf_trace_io_uring_complete
  - io_uring/io_uring.c:perf_trace_io_uring_fail_link
  - io_uring/io_uring.c:perf_trace_io_uring_cqring_wait
  - io_uring/io_uring.c:perf_trace_io_uring_link
  - io_uring/io_uring.c:perf_trace_io_uring_defer
  - io_uring/io_uring.c:perf_trace_io_uring_queue_async_work
  - io_uring/io_uring.c:perf_trace_io_uring_file_get
  - io_uring/io_uring.c:perf_trace_io_uring_register
  - io_uring/io_uring.c:perf_trace_io_uring_create
```
```
In io_uring/net.c (ffffffff817966de)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - io_uring/net.c:io_recvmsg_prep_async
  - io_uring/net.c:io_sendmsg_prep_async
```
```
In io_uring/poll.c (ffffffff8179dac1)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - io_uring/poll.c:io_arm_poll_handler
```
```
In arch/x86/lib/msr.c (ffffffff818a6252)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff818ba382)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/pwm/core.c (ffffffff818cf032)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/pwm/core.c:perf_trace_pwm
```
```
In drivers/clk/clk.c (ffffffff819fbb6c)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:perf_trace_clk_rate_request
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate_range
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff81a37196)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/iommu/intel/trace.c (ffffffff81ac7a5a)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/iommu/intel/trace.c:perf_trace_prq_report
  - drivers/iommu/intel/trace.c:perf_trace_qi_submit
```
```
In drivers/iommu/iommu-traces.c (ffffffff81ad385b)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff81b19c76)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bulk
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
```
```
In drivers/base/trace.c (ffffffff81b29bd0)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/base/trace.c:perf_trace_devres
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81b6b504)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81b718e7)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff81b73da3)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/scsi/sd_zbc.c (ffffffff81b95742)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:perf_trace_scsi_zone_wp_update
  - drivers/scsi/sd_zbc.c:perf_trace_scsi_prepare_zone_append
```
```
In drivers/ata/libata-core.c (ffffffff81ba1c9a)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_sff_template
  - drivers/ata/libata-core.c:perf_trace_ata_transfer_data_template
  - drivers/ata/libata-core.c:perf_trace_ata_sff_hsm_template
  - drivers/ata/libata-core.c:perf_trace_ata_port_eh_begin_template
  - drivers/ata/libata-core.c:perf_trace_ata_link_reset_end_template
  - drivers/ata/libata-core.c:perf_trace_ata_link_reset_begin_template
  - drivers/ata/libata-core.c:perf_trace_ata_eh_action_template
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_bmdma_status
  - drivers/ata/libata-core.c:perf_trace_ata_exec_command_template
  - drivers/ata/libata-core.c:perf_trace_ata_tf_load
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue_template
```
```
In drivers/spi/spi.c (ffffffff81bd0ec8)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_set_cs
  - drivers/spi/spi.c:perf_trace_spi_setup
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81be58a5)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81c93f9a)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_dbc_log_request
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_doorbell
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_slot_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ep_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_free_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_trb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
```
```
In drivers/rtc/interface.c (ffffffff81cba63d)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/rtc/interface.c:perf_trace_rtc_timer_class
  - drivers/rtc/interface.c:perf_trace_rtc_offset_class
  - drivers/rtc/interface.c:perf_trace_rtc_alarm_irq_enable
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_state
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_freq
  - drivers/rtc/interface.c:perf_trace_rtc_time_alarm_class
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81cc1d0b)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81cc704f)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff81cdbeb6)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff81cdea61)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81ce709f)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/watchdog/watchdog_core.c (ffffffff81ceb2c5)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:perf_trace_watchdog_set_timeout
  - drivers/watchdog/watchdog_core.c:perf_trace_watchdog_template
```
```
In drivers/cpufreq/amd-pstate-trace.c (ffffffff81d38850)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate-trace.c:perf_trace_amd_pstate_perf
```
```
In drivers/mmc/core/core.c (ffffffff81d474a4)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffffffff81d72d87)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_start
```
```
In drivers/devfreq/devfreq.c (ffffffff81d7d7d1)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_frequency
```
```
In drivers/ras/ras.c (ffffffff81d886d2)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_memory_failure_event
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_non_standard_event
  - drivers/ras/ras.c:perf_trace_arm_event
  - drivers/ras/ras.c:perf_trace_mc_event
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
```
```
In drivers/interconnect/core.c (ffffffff81d8df0e)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_node_destroy
  - drivers/interconnect/core.c:perf_trace_icc_set_bw_end
  - drivers/interconnect/core.c:perf_trace_icc_set_bw
```
```
In net/core/net-traces.c (ffffffff81e1f6a3)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:perf_trace_neigh_create
  - net/core/net-traces.c:perf_trace_page_pool_update_nid
  - net/core/net-traces.c:perf_trace_page_pool_state_hold
  - net/core/net-traces.c:perf_trace_page_pool_state_release
  - net/core/net-traces.c:perf_trace_page_pool_release
  - net/core/net-traces.c:perf_trace_br_fdb_update
  - net/core/net-traces.c:perf_trace_fdb_delete
  - net/core/net-traces.c:perf_trace_br_fdb_external_learn_add
  - net/core/net-traces.c:perf_trace_br_fdb_add
  - net/core/net-traces.c:perf_trace_qdisc_create
  - net/core/net-traces.c:perf_trace_qdisc_destroy
  - net/core/net-traces.c:perf_trace_qdisc_reset
  - net/core/net-traces.c:perf_trace_qdisc_enqueue
  - net/core/net-traces.c:perf_trace_qdisc_dequeue
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:perf_trace_tcp_cong_state_set
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:perf_trace_inet_sk_error_report
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_rcvqueue_full
  - net/core/net-traces.c:perf_trace_napi_poll
  - net/core/net-traces.c:perf_trace_net_dev_rx_exit_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_template
  - net/core/net-traces.c:perf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:perf_trace_net_dev_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:perf_trace_consume_skb
  - net/core/net-traces.c:perf_trace_kfree_skb
```
```
In net/core/devlink.c (ffffffff81e2d39d)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_trap_report
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/core/bpf_sk_storage.c (ffffffff81e4d66d)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
```
In net/netlink/af_netlink.c (ffffffff81e66bc9)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:perf_trace_netlink_extack
```
```
In net/bpf/test_run.c (ffffffff81e711b0)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea558b)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea9fdb)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse
```
```
In net/ipv4/udp.c (ffffffff81ee037a)
Location: include/linux/list.h:874
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff81f0896b)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f33d24)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/xfrm/xfrm_state.c (ffffffff81f40fa0)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
```
```
In net/unix/af_unix.c (ffffffff81f49eb0)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_get_first
```
```
In net/ipv6/anycast.c (ffffffff81f54b53)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_anycast_cleanup
```
```
In net/ipv6/addrconf.c (ffffffff81f63567)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_exit_net
```
```
In net/ipv6/route.c (ffffffff81f6bb29)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
```
In net/packet/af_packet.c (ffffffff81fc4510)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_net_exit
```
```
In net/xdp/xsk.c (ffffffff81fecef5)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_net_exit
```
```
In net/mptcp/protocol.c (ffffffff81ff3618)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - net/mptcp/protocol.c:perf_trace_subflow_check_data_avail
  - net/mptcp/protocol.c:perf_trace_ack_update_msk
  - net/mptcp/protocol.c:perf_trace_mptcp_dump_mpext
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
```
```
In net/mctp/af_mctp.c (ffffffff8200f94a)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:perf_trace_mctp_key_release
  - net/mctp/af_mctp.c:perf_trace_mctp_key_acquire
```
```
In lib/maple_tree.c (ffffffff82025c38)
Location: include/linux/list.h:874
Inline: True
Inline callers:
  - lib/maple_tree.c:perf_trace_ma_write
  - lib/maple_tree.c:perf_trace_ma_read
  - lib/maple_tree.c:perf_trace_ma_op
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
In init/main.c (ffffffff81001398)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8100498d)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff810402a8)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_set_ldt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_gdt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_load_idt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_multi
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_one_user
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_alloc_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu__set_pte
  - arch/x86/xen/trace.c:perf_trace_xen_mc_extend_args
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush_reason
  - arch/x86/xen/trace.c:perf_trace_xen_mc_callback
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry_alloc
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mc__batch
```
```
In arch/x86/hyperv/mmu.c (ffffffff81045e08)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_one
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_multi
```
```
In arch/x86/kernel/irq.c (ffffffff8104ebfe)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:perf_trace_vector_free_moved
  - arch/x86/kernel/irq.c:perf_trace_vector_setup
  - arch/x86/kernel/irq.c:perf_trace_vector_teardown
  - arch/x86/kernel/irq.c:perf_trace_vector_activate
  - arch/x86/kernel/irq.c:perf_trace_vector_alloc_managed
  - arch/x86/kernel/irq.c:perf_trace_vector_alloc
  - arch/x86/kernel/irq.c:perf_trace_vector_reserve
  - arch/x86/kernel/irq.c:perf_trace_vector_mod
  - arch/x86/kernel/irq.c:perf_trace_vector_config
  - arch/x86/kernel/irq.c:perf_trace_x86_irq_vector
```
```
In arch/x86/kernel/nmi.c (ffffffff81052e02)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81061fe3)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81077faa)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108f788)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/fault.c (ffffffff810c66da)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In kernel/fork.c (ffffffff810f30fa)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_prepare
  - kernel/fork.c:pidfd_show_fdinfo
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff810f9136)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/exit.c (ffffffff810fcb0d)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/softirq.c (ffffffff810fedd8)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_tasklet
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff811098fc)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff8111cbe8)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_end
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_activate_work
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
```
```
In kernel/pid.c (ffffffff811264b7)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/notifier.c (ffffffff8113221d)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - kernel/notifier.c:perf_trace_notifier_info
```
```
In kernel/sched/core.c (ffffffff8113b3dd)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_ipi_handler
  - kernel/sched/core.c:perf_trace_ipi_send_cpumask
  - kernel/sched/core.c:perf_trace_ipi_send_cpu
  - kernel/sched/core.c:perf_trace_ipi_raise
  - kernel/sched/core.c:perf_trace_sched_wake_idle_without_ipi
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:perf_trace_sched_process_hang
  - kernel/sched/core.c:perf_trace_sched_pi_setprio
  - kernel/sched/core.c:perf_trace_sched_stat_runtime
  - kernel/sched/core.c:perf_trace_sched_process_exec
  - kernel/sched/core.c:perf_trace_sched_process_fork
  - kernel/sched/core.c:perf_trace_sched_process_wait
  - kernel/sched/core.c:perf_trace_sched_process_template
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:perf_trace_sched_kthread_work_execute_end
  - kernel/sched/core.c:perf_trace_sched_kthread_work_execute_start
  - kernel/sched/core.c:perf_trace_sched_kthread_work_queue_work
  - kernel/sched/core.c:perf_trace_sched_kthread_stop_ret
  - kernel/sched/core.c:perf_trace_sched_kthread_stop
```
```
In kernel/locking/mutex.c (ffffffff8118d4c8)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - kernel/locking/mutex.c:perf_trace_contention_end
  - kernel/locking/mutex.c:perf_trace_contention_begin
```
```
In kernel/printk/printk.c (ffffffff8119f1f2)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - kernel/printk/printk.c:unregister_console_locked
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/resend.c (ffffffff811abea8)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - kernel/irq/resend.c:resend_irqs
```
```
In kernel/irq/matrix.c (ffffffff811b9473)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff811bac98)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_stall_warning
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff811d74df)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/entry/common.c (ffffffff811d8b5e)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - kernel/entry/common.c:perf_trace_sys_exit
  - kernel/entry/common.c:perf_trace_sys_enter
```
```
In kernel/module/main.c (ffffffff811db1ae)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - kernel/module/main.c:perf_trace_module_request
  - kernel/module/main.c:perf_trace_module_refcnt
  - kernel/module/main.c:perf_trace_module_free
  - kernel/module/main.c:perf_trace_module_load
```
```
In kernel/time/timer.c (ffffffff811eccd9)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:__run_timers
  - kernel/time/timer.c:perf_trace_tick_stop
  - kernel/time/timer.c:perf_trace_itimer_expire
  - kernel/time/timer.c:perf_trace_itimer_state
  - kernel/time/timer.c:perf_trace_hrtimer_class
  - kernel/time/timer.c:perf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:perf_trace_hrtimer_start
  - kernel/time/timer.c:perf_trace_hrtimer_init
  - kernel/time/timer.c:perf_trace_timer_expire_entry
  - kernel/time/timer.c:perf_trace_timer_start
  - kernel/time/timer.c:perf_trace_timer_class
```
```
In kernel/time/alarmtimer.c (ffffffff811f7437)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811fd1fd)
Location: include/linux/list.h:889
Inline: True
```
```
In kernel/smp.c (ffffffff8120d7b8)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - kernel/smp.c:perf_trace_csd_function
  - kernel/smp.c:perf_trace_csd_queue_cpu
```
```
In kernel/cgroup/cgroup.c (ffffffff81219f38)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/ftrace.c (ffffffff8126b1b7)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:profile_graph_return
```
```
In kernel/trace/trace_osnoise.c (ffffffff81295174)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:perf_trace_sample_threshold
  - kernel/trace/trace_osnoise.c:perf_trace_nmi_noise
  - kernel/trace/trace_osnoise.c:perf_trace_irq_noise
  - kernel/trace/trace_osnoise.c:perf_trace_softirq_noise
  - kernel/trace/trace_osnoise.c:perf_trace_thread_noise
```
```
In kernel/trace/trace_syscalls.c (ffffffff812a8b4d)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/trace_events_user.c (ffffffff812c39f8)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_perf
```
```
In kernel/trace/bpf_trace.c (ffffffff812c7c49)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_trace_bpf_trace_printk
```
```
In kernel/trace/trace_kprobe.c (ffffffff812cfc4e)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/error_report-traces.c (ffffffff812d0fc8)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - kernel/trace/error_report-traces.c:perf_trace_error_report_template
```
```
In kernel/trace/power-traces.c (ffffffff812d2602)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:perf_trace_guest_halt_poll_ns
  - kernel/trace/power-traces.c:perf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update
  - kernel/trace/power-traces.c:perf_trace_cpu_latency_qos_request
  - kernel/trace/power-traces.c:perf_trace_power_domain
  - kernel/trace/power-traces.c:perf_trace_clock
  - kernel/trace/power-traces.c:perf_trace_wakeup_source
  - kernel/trace/power-traces.c:perf_trace_suspend_resume
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:perf_trace_cpu_frequency_limits
  - kernel/trace/power-traces.c:perf_trace_pstate_sample
  - kernel/trace/power-traces.c:perf_trace_powernv_throttle
  - kernel/trace/power-traces.c:perf_trace_cpu_idle_miss
  - kernel/trace/power-traces.c:perf_trace_cpu
```
```
In kernel/trace/rpm-traces.c (ffffffff812d55ee)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffffffff812db6c5)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/trace/trace_fprobe.c (ffffffff812e1f6a)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:fexit_perf_func
  - kernel/trace/trace_fprobe.c:fentry_perf_func
```
```
In kernel/trace/rv/rv.c (ffffffff812e299a)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - kernel/trace/rv/rv.c:perf_trace_error_da_monitor_id
  - kernel/trace/rv/rv.c:perf_trace_event_da_monitor_id
```
```
In kernel/bpf/core.c (ffffffff812e6ae1)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_mem_return_failed
  - kernel/bpf/core.c:perf_trace_mem_connect
  - kernel/bpf/core.c:perf_trace_mem_disconnect
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_bulk_tx
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff81334ae0)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
```
```
In kernel/bpf/trampoline.c (ffffffff8133724f)
Location: include/linux/list.h:889
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff81357f87)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
```
In kernel/events/core.c (ffffffff8136e8b7)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - kernel/events/core.c:perf_trace_run_bpf_submit
```
```
In kernel/user-return-notifier.c (ffffffff81384392)
Location: include/linux/list.h:889
Inline: True
```
```
In kernel/rseq.c (ffffffff81387a9f)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In kernel/watch_queue.c (ffffffff81389a96)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
```
```
In mm/filemap.c (ffffffff8138ac70)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff81394677)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:perf_trace_skip_task_reaping
  - mm/oom_kill.c:perf_trace_finish_task_reaping
  - mm/oom_kill.c:perf_trace_start_task_reaping
  - mm/oom_kill.c:perf_trace_wake_reaper
  - mm/oom_kill.c:perf_trace_mark_victim
  - mm/oom_kill.c:perf_trace_reclaim_retry_zone
  - mm/oom_kill.c:perf_trace_oom_score_adj_update
```
```
In mm/swap.c (ffffffff8139f20d)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff813a7398)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - mm/vmscan.c:perf_trace_mm_vmscan_throttled
  - mm/vmscan.c:perf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:perf_trace_mm_vmscan_write_folio
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_isolate
  - mm/vmscan.c:perf_trace_mm_shrink_slab_end
  - mm/vmscan.c:perf_trace_mm_shrink_slab_start
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_end_template
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:perf_trace_mm_vmscan_wakeup_kswapd
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_wake
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_sleep
```
```
In mm/percpu.c (ffffffff813cceed)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff813d335b)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - mm/slab_common.c:perf_trace_rss_stat
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:perf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:perf_trace_mm_page
  - mm/slab_common.c:perf_trace_mm_page_alloc
  - mm/slab_common.c:perf_trace_mm_page_free_batched
  - mm/slab_common.c:perf_trace_mm_page_free
  - mm/slab_common.c:perf_trace_kmem_cache_free
  - mm/slab_common.c:perf_trace_kfree
  - mm/slab_common.c:perf_trace_kmalloc
  - mm/slab_common.c:perf_trace_kmem_cache_alloc
```
```
In mm/compaction.c (ffffffff813d7502)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - mm/compaction.c:perf_trace_kcompactd_wake_template
  - mm/compaction.c:perf_trace_mm_compaction_kcompactd_sleep
  - mm/compaction.c:perf_trace_mm_compaction_defer_template
  - mm/compaction.c:perf_trace_mm_compaction_suitable_template
  - mm/compaction.c:perf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:perf_trace_mm_compaction_end
  - mm/compaction.c:perf_trace_mm_compaction_begin
  - mm/compaction.c:perf_trace_mm_compaction_migratepages
  - mm/compaction.c:perf_trace_mm_compaction_isolate_template
```
```
In mm/mmap_lock.c (ffffffff813e8a9d)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - mm/mmap_lock.c:perf_trace_mmap_lock_acquire_returned
  - mm/mmap_lock.c:perf_trace_mmap_lock
```
```
In mm/mmap.c (ffffffff813fa105)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - mm/mmap.c:perf_trace_exit_mmap
  - mm/mmap.c:perf_trace_vma_store
  - mm/mmap.c:perf_trace_vma_mas_szero
  - mm/mmap.c:perf_trace_vm_unmapped_area
```
```
In mm/rmap.c (ffffffff8140a362)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - mm/rmap.c:perf_trace_migration_pte
  - mm/rmap.c:perf_trace_mm_migrate_pages_start
  - mm/rmap.c:perf_trace_mm_migrate_pages
  - mm/rmap.c:perf_trace_tlb_flush
```
```
In mm/vmalloc.c (ffffffff8140fef4)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - mm/vmalloc.c:perf_trace_free_vmap_area_noflush
  - mm/vmalloc.c:perf_trace_purge_vmap_area_lazy
  - mm/vmalloc.c:perf_trace_alloc_vmap_area
```
```
In mm/mmu_notifier.c (ffffffff81450884)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_subscriptions_destroy
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_release
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (ffffffff81452bc9)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:perf_trace_ksm_remove_rmap_item
  - mm/ksm.c:perf_trace_ksm_remove_ksm_page
  - mm/ksm.c:perf_trace_ksm_merge_with_ksm_page
  - mm/ksm.c:perf_trace_ksm_merge_one_page
  - mm/ksm.c:perf_trace_ksm_enter_exit_template
  - mm/ksm.c:perf_trace_ksm_scan_template
```
```
In mm/huge_memory.c (ffffffff81470558)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - mm/huge_memory.c:perf_trace_migration_pmd
  - mm/huge_memory.c:perf_trace_hugepage_update
  - mm/huge_memory.c:perf_trace_hugepage_set_pmd
```
```
In mm/khugepaged.c (ffffffff8147bade)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_khugepaged_collapse_file
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_file
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff8149a034)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In fs/super.c (ffffffff814b45ea)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - fs/super.c:reconfigure_super
```
```
In fs/dcache.c (ffffffff814d4942)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_find_alias_rcu
  - fs/dcache.c:d_find_alias
  - fs/dcache.c:d_find_alias
```
```
In fs/namespace.c (ffffffff814e48cc)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:namespace_unlock
```
```
In fs/seq_file.c (ffffffff814e82b2)
Location: include/linux/list.h:889
Inline: True
```
```
In fs/fs-writeback.c (ffffffff814f1e19)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_writeback_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_pages_written
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_folio_template
```
```
In fs/notify/mark.c (ffffffff815143e4)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151b76e)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
```
```
In fs/eventpoll.c (ffffffff8151fd5e)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:reverse_path_check_proc
```
```
In fs/dax.c (ffffffff8152d984)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - fs/dax.c:perf_trace_dax_writeback_one
  - fs/dax.c:perf_trace_dax_writeback_range_class
  - fs/dax.c:perf_trace_dax_insert_mapping
  - fs/dax.c:perf_trace_dax_pte_fault_class
  - fs/dax.c:perf_trace_dax_pmd_insert_mapping_class
  - fs/dax.c:perf_trace_dax_pmd_load_hole_class
  - fs/dax.c:perf_trace_dax_pmd_fault_class
```
```
In fs/locks.c (ffffffff8153fb72)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/iomap/trace.c (ffffffff81552b63)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - fs/iomap/trace.c:perf_trace_iomap_dio_complete
  - fs/iomap/trace.c:perf_trace_iomap_dio_rw_begin
  - fs/iomap/trace.c:perf_trace_iomap_iter
  - fs/iomap/trace.c:perf_trace_iomap_class
  - fs/iomap/trace.c:perf_trace_iomap_range_class
  - fs/iomap/trace.c:perf_trace_iomap_readpage_class
```
```
In fs/ext4/super.c (ffffffff815eb076)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_update_sb
  - fs/ext4/super.c:perf_trace_ext4_fc_cleanup
  - fs/ext4/super.c:perf_trace_ext4_fc_track_range
  - fs/ext4/super.c:perf_trace_ext4_fc_track_inode
  - fs/ext4/super.c:perf_trace_ext4_fc_track_dentry
  - fs/ext4/super.c:perf_trace_ext4_fc_stats
  - fs/ext4/super.c:perf_trace_ext4_fc_commit_stop
  - fs/ext4/super.c:perf_trace_ext4_fc_commit_start
  - fs/ext4/super.c:perf_trace_ext4_fc_replay
  - fs/ext4/super.c:perf_trace_ext4_fc_replay_scan
  - fs/ext4/super.c:perf_trace_ext4_lazy_itable_init
  - fs/ext4/super.c:perf_trace_ext4_prefetch_bitmaps
  - fs/ext4/super.c:perf_trace_ext4_error
  - fs/ext4/super.c:perf_trace_ext4_shutdown
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:perf_trace_ext4_insert_range
  - fs/ext4/super.c:perf_trace_ext4_collapse_range
  - fs/ext4/super.c:perf_trace_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:perf_trace_ext4__es_shrink_enter
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_enter
  - fs/ext4/super.c:perf_trace_ext4_es_remove_extent
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_idx
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_show_extent
  - fs/ext4/super.c:perf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:perf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:perf_trace_ext4__trim
  - fs/ext4/super.c:perf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:perf_trace_ext4_journal_start_inode
  - fs/ext4/super.c:perf_trace_ext4_journal_start_sb
  - fs/ext4/super.c:perf_trace_ext4_load_inode
  - fs/ext4/super.c:perf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_exit
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_enter
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:perf_trace_ext4__truncate
  - fs/ext4/super.c:perf_trace_ext4_unlink_exit
  - fs/ext4/super.c:perf_trace_ext4_unlink_enter
  - fs/ext4/super.c:perf_trace_ext4_fallocate_exit
  - fs/ext4/super.c:perf_trace_ext4__fallocate_mode
  - fs/ext4/super.c:perf_trace_ext4_read_block_bitmap_load
  - fs/ext4/super.c:perf_trace_ext4__bitmap_load
  - fs/ext4/super.c:perf_trace_ext4_da_release_space
  - fs/ext4/super.c:perf_trace_ext4_da_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_da_update_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_forget
  - fs/ext4/super.c:perf_trace_ext4__mballoc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_prealloc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_alloc
  - fs/ext4/super.c:perf_trace_ext4_alloc_da_blocks
  - fs/ext4/super.c:perf_trace_ext4_sync_fs
  - fs/ext4/super.c:perf_trace_ext4_sync_file_exit
  - fs/ext4/super.c:perf_trace_ext4_sync_file_enter
  - fs/ext4/super.c:perf_trace_ext4_free_blocks
  - fs/ext4/super.c:perf_trace_ext4_allocate_blocks
  - fs/ext4/super.c:perf_trace_ext4_request_blocks
  - fs/ext4/super.c:perf_trace_ext4_mb_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_mb_release_group_pa
  - fs/ext4/super.c:perf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:perf_trace_ext4__mb_new_pa
  - fs/ext4/super.c:perf_trace_ext4_discard_blocks
  - fs/ext4/super.c:perf_trace_ext4_invalidate_folio_op
  - fs/ext4/super.c:perf_trace_ext4__folio_op
  - fs/ext4/super.c:perf_trace_ext4_writepages_result
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages_extent
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages
  - fs/ext4/super.c:perf_trace_ext4_writepages
  - fs/ext4/super.c:perf_trace_ext4__write_end
  - fs/ext4/super.c:perf_trace_ext4__write_begin
  - fs/ext4/super.c:perf_trace_ext4_begin_ordered_truncate
  - fs/ext4/super.c:perf_trace_ext4_mark_inode_dirty
  - fs/ext4/super.c:perf_trace_ext4_nfs_commit_metadata
  - fs/ext4/super.c:perf_trace_ext4_drop_inode
  - fs/ext4/super.c:perf_trace_ext4_evict_inode
  - fs/ext4/super.c:perf_trace_ext4_allocate_inode
  - fs/ext4/super.c:perf_trace_ext4_request_inode
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
```
```
In fs/jbd2/journal.c (ffffffff8161d8a9)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - fs/jbd2/journal.c:perf_trace_jbd2_shrink_checkpoint_list
  - fs/jbd2/journal.c:perf_trace_jbd2_shrink_scan_exit
  - fs/jbd2/journal.c:perf_trace_jbd2_journal_shrink
  - fs/jbd2/journal.c:perf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:perf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:perf_trace_jbd2_update_log_tail
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_run_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_extend
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_start_class
  - fs/jbd2/journal.c:perf_trace_jbd2_submit_inode_data
  - fs/jbd2/journal.c:perf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint
```
```
In security/selinux/avc.c (ffffffff816a5672)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_get_hash_stats
  - security/selinux/avc.c:perf_trace_selinux_audited
```
```
In block/blk-core.c (ffffffff8176f9b2)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_unplug
  - block/blk-core.c:perf_trace_block_plug
  - block/blk-core.c:perf_trace_block_bio
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_completion
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_buffer
```
```
In block/blk-ioc.c (ffffffff81776f25)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff817a24e9)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_unpin_online
```
```
In block/blk-iocost.c (ffffffff817ab30b)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_iocg_forgive_debt
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_state
```
```
In block/blk-wbt.c (ffffffff817b91e5)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In io_uring/io_uring.c (ffffffff817c7422)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - io_uring/io_uring.c:perf_trace_io_uring_local_work_run
  - io_uring/io_uring.c:perf_trace_io_uring_short_write
  - io_uring/io_uring.c:perf_trace_io_uring_task_work_run
  - io_uring/io_uring.c:perf_trace_io_uring_cqe_overflow
  - io_uring/io_uring.c:perf_trace_io_uring_req_failed
  - io_uring/io_uring.c:perf_trace_io_uring_task_add
  - io_uring/io_uring.c:perf_trace_io_uring_poll_arm
  - io_uring/io_uring.c:perf_trace_io_uring_submit_req
  - io_uring/io_uring.c:perf_trace_io_uring_complete
  - io_uring/io_uring.c:perf_trace_io_uring_fail_link
  - io_uring/io_uring.c:perf_trace_io_uring_cqring_wait
  - io_uring/io_uring.c:perf_trace_io_uring_link
  - io_uring/io_uring.c:perf_trace_io_uring_defer
  - io_uring/io_uring.c:perf_trace_io_uring_queue_async_work
  - io_uring/io_uring.c:perf_trace_io_uring_file_get
  - io_uring/io_uring.c:perf_trace_io_uring_register
  - io_uring/io_uring.c:perf_trace_io_uring_create
```
```
In arch/x86/lib/msr.c (ffffffff818e9082)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff818fd482)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/pwm/core.c (ffffffff81912072)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - drivers/pwm/core.c:perf_trace_pwm
```
```
In drivers/clk/clk.c (ffffffff81a4461c)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:perf_trace_clk_rate_request
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate_range
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff81a80ed6)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/iommu/intel/trace.c (ffffffff81b147dd)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - drivers/iommu/intel/trace.c:perf_trace_prq_report
  - drivers/iommu/intel/trace.c:perf_trace_qi_submit
```
```
In drivers/iommu/iommu-traces.c (ffffffff81b22023)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff81b688a6)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bulk
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
```
```
In drivers/base/trace.c (ffffffff81b79da0)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - drivers/base/trace.c:perf_trace_devres
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81bbe96c)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81bc516d)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff81bc7553)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/scsi/sd_zbc.c (ffffffff81bebce2)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:perf_trace_scsi_zone_wp_update
  - drivers/scsi/sd_zbc.c:perf_trace_scsi_prepare_zone_append
```
```
In drivers/ata/libata-core.c (ffffffff81bf84aa)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_sff_template
  - drivers/ata/libata-core.c:perf_trace_ata_transfer_data_template
  - drivers/ata/libata-core.c:perf_trace_ata_sff_hsm_template
  - drivers/ata/libata-core.c:perf_trace_ata_port_eh_begin_template
  - drivers/ata/libata-core.c:perf_trace_ata_link_reset_end_template
  - drivers/ata/libata-core.c:perf_trace_ata_link_reset_begin_template
  - drivers/ata/libata-core.c:perf_trace_ata_eh_action_template
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_bmdma_status
  - drivers/ata/libata-core.c:perf_trace_ata_exec_command_template
  - drivers/ata/libata-core.c:perf_trace_ata_tf_load
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue_template
```
```
In drivers/spi/spi.c (ffffffff81c28b38)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_set_cs
  - drivers/spi/spi.c:perf_trace_spi_setup
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81c3d2c5)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81cfa6da)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_dbc_log_request
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_doorbell
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_slot_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ep_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_free_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_trb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
```
```
In drivers/rtc/interface.c (ffffffff81d21ded)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - drivers/rtc/interface.c:perf_trace_rtc_timer_class
  - drivers/rtc/interface.c:perf_trace_rtc_offset_class
  - drivers/rtc/interface.c:perf_trace_rtc_alarm_irq_enable
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_state
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_freq
  - drivers/rtc/interface.c:perf_trace_rtc_time_alarm_class
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81d2971b)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81d2ed7f)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff81d44435)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff81d46971)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81d4f79f)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/watchdog/watchdog_core.c (ffffffff81d53f15)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:perf_trace_watchdog_set_timeout
  - drivers/watchdog/watchdog_core.c:perf_trace_watchdog_template
```
```
In drivers/cpufreq/amd-pstate-trace.c (ffffffff81da32d0)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate-trace.c:perf_trace_amd_pstate_perf
```
```
In drivers/mmc/core/core.c (ffffffff81db1d34)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffffffff81de0b67)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_start
```
```
In drivers/devfreq/devfreq.c (ffffffff81debb51)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_frequency
```
```
In drivers/ras/ras.c (ffffffff81df6ce2)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_memory_failure_event
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_non_standard_event
  - drivers/ras/ras.c:perf_trace_arm_event
  - drivers/ras/ras.c:perf_trace_mc_event
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
```
```
In drivers/interconnect/core.c (ffffffff81dfc7ce)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_node_destroy
  - drivers/interconnect/core.c:perf_trace_icc_set_bw_end
  - drivers/interconnect/core.c:perf_trace_icc_set_bw
```
```
In net/core/net-traces.c (ffffffff81e91d9e)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:perf_trace_neigh_create
  - net/core/net-traces.c:perf_trace_page_pool_update_nid
  - net/core/net-traces.c:perf_trace_page_pool_state_hold
  - net/core/net-traces.c:perf_trace_page_pool_state_release
  - net/core/net-traces.c:perf_trace_page_pool_release
  - net/core/net-traces.c:perf_trace_br_mdb_full
  - net/core/net-traces.c:perf_trace_br_fdb_update
  - net/core/net-traces.c:perf_trace_fdb_delete
  - net/core/net-traces.c:perf_trace_br_fdb_external_learn_add
  - net/core/net-traces.c:perf_trace_br_fdb_add
  - net/core/net-traces.c:perf_trace_qdisc_create
  - net/core/net-traces.c:perf_trace_qdisc_destroy
  - net/core/net-traces.c:perf_trace_qdisc_reset
  - net/core/net-traces.c:perf_trace_qdisc_enqueue
  - net/core/net-traces.c:perf_trace_qdisc_dequeue
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:perf_trace_tcp_cong_state_set
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:perf_trace_sock_msg_length
  - net/core/net-traces.c:perf_trace_sk_data_ready
  - net/core/net-traces.c:perf_trace_inet_sk_error_report
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_rcvqueue_full
  - net/core/net-traces.c:perf_trace_napi_poll
  - net/core/net-traces.c:perf_trace_net_dev_rx_exit_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_template
  - net/core/net-traces.c:perf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:perf_trace_net_dev_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:perf_trace_consume_skb
  - net/core/net-traces.c:perf_trace_kfree_skb
```
```
In net/core/bpf_sk_storage.c (ffffffff81ea8cbd)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
```
In net/netlink/af_netlink.c (ffffffff81ec2989)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:perf_trace_netlink_extack
```
```
In net/bpf/test_run.c (ffffffff81ecd2f0)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f03d12)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f0884c)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse
```
```
In net/ipv4/udp.c (ffffffff81f402c0)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_batch
  - net/ipv4/udp.c:udp_get_first
```
```
In net/ipv4/fib_trie.c (ffffffff81f6847b)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
```
```
In net/ipv4/ping.c (ffffffff81f6b764)
Location: include/linux/list.h:889
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f930e4)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/xfrm/xfrm_state.c (ffffffff81fa0830)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
```
```
In net/unix/af_unix.c (ffffffff81fa9b50)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_get_first
```
```
In net/ipv6/anycast.c (ffffffff81fb4563)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_anycast_cleanup
```
```
In net/ipv6/addrconf.c (ffffffff81fc3527)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_exit_net
```
```
In net/ipv6/route.c (ffffffff81fcbc84)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
```
In net/packet/af_packet.c (ffffffff82025550)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_net_exit
```
```
In net/devlink/leftover.c (ffffffff8203193e)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - net/devlink/leftover.c:perf_trace_devlink_trap_report
  - net/devlink/leftover.c:perf_trace_devlink_health_reporter_state_update
  - net/devlink/leftover.c:perf_trace_devlink_health_recover_aborted
  - net/devlink/leftover.c:perf_trace_devlink_health_report
  - net/devlink/leftover.c:perf_trace_devlink_hwerr
  - net/devlink/leftover.c:perf_trace_devlink_hwmsg
```
```
In net/xdp/xsk.c (ffffffff82069195)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_net_exit
```
```
In net/mptcp/protocol.c (ffffffff8206f988)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - net/mptcp/protocol.c:perf_trace_subflow_check_data_avail
  - net/mptcp/protocol.c:perf_trace_ack_update_msk
  - net/mptcp/protocol.c:perf_trace_mptcp_dump_mpext
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
```
```
In net/mctp/af_mctp.c (ffffffff8208c56a)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:perf_trace_mctp_key_release
  - net/mctp/af_mctp.c:perf_trace_mctp_key_acquire
```
```
In net/handshake/trace.c (ffffffff82094f74)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - net/handshake/trace.c:perf_trace_handshake_complete
  - net/handshake/trace.c:perf_trace_handshake_error_class
  - net/handshake/trace.c:perf_trace_handshake_fd_class
  - net/handshake/trace.c:perf_trace_handshake_event_class
```
```
In lib/maple_tree.c (ffffffff820a5d88)
Location: include/linux/list.h:889
Inline: True
Inline callers:
  - lib/maple_tree.c:perf_trace_ma_write
  - lib/maple_tree.c:perf_trace_ma_read
  - lib/maple_tree.c:perf_trace_ma_op
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
In init/main.c (ffffffff810013a8)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8100729d)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff81046778)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_set_ldt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_gdt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_load_idt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_multi
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_one_user
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_alloc_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu__set_pte
  - arch/x86/xen/trace.c:perf_trace_xen_mc_extend_args
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush_reason
  - arch/x86/xen/trace.c:perf_trace_xen_mc_callback
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry_alloc
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mc__batch
```
```
In arch/x86/hyperv/mmu.c (ffffffff8104c4d8)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_one
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_multi
```
```
In arch/x86/kernel/irq.c (ffffffff81055e2e)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:perf_trace_vector_free_moved
  - arch/x86/kernel/irq.c:perf_trace_vector_setup
  - arch/x86/kernel/irq.c:perf_trace_vector_teardown
  - arch/x86/kernel/irq.c:perf_trace_vector_activate
  - arch/x86/kernel/irq.c:perf_trace_vector_alloc_managed
  - arch/x86/kernel/irq.c:perf_trace_vector_alloc
  - arch/x86/kernel/irq.c:perf_trace_vector_reserve
  - arch/x86/kernel/irq.c:perf_trace_vector_mod
  - arch/x86/kernel/irq.c:perf_trace_vector_config
  - arch/x86/kernel/irq.c:perf_trace_x86_irq_vector
```
```
In arch/x86/kernel/nmi.c (ffffffff8105a022)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81069223)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8107f45a)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81096b18)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810abfe8)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_offline
```
```
In arch/x86/mm/fault.c (ffffffff810ceb5a)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In kernel/fork.c (ffffffff810fc4aa)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_prepare
  - kernel/fork.c:pidfd_show_fdinfo
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff81102546)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/exit.c (ffffffff81106f20)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/exit.c:__do_wait
```
```
In kernel/softirq.c (ffffffff81108488)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_tasklet
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff8111329c)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff81126668)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_end
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_activate_work
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
```
```
In kernel/pid.c (ffffffff81130abf)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/notifier.c (ffffffff8113d12d)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/notifier.c:perf_trace_notifier_info
```
```
In kernel/sched/core.c (ffffffff8114639d)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_ipi_handler
  - kernel/sched/core.c:perf_trace_ipi_send_cpumask
  - kernel/sched/core.c:perf_trace_ipi_send_cpu
  - kernel/sched/core.c:perf_trace_ipi_raise
  - kernel/sched/core.c:perf_trace_sched_wake_idle_without_ipi
  - kernel/sched/core.c:perf_trace_sched_skip_vma_numa
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:perf_trace_sched_process_hang
  - kernel/sched/core.c:perf_trace_sched_pi_setprio
  - kernel/sched/core.c:perf_trace_sched_stat_runtime
  - kernel/sched/core.c:perf_trace_sched_process_exec
  - kernel/sched/core.c:perf_trace_sched_process_fork
  - kernel/sched/core.c:perf_trace_sched_process_wait
  - kernel/sched/core.c:perf_trace_sched_process_template
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:perf_trace_sched_kthread_work_execute_end
  - kernel/sched/core.c:perf_trace_sched_kthread_work_execute_start
  - kernel/sched/core.c:perf_trace_sched_kthread_work_queue_work
  - kernel/sched/core.c:perf_trace_sched_kthread_stop_ret
  - kernel/sched/core.c:perf_trace_sched_kthread_stop
```
```
In kernel/locking/mutex.c (ffffffff8119be78)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/locking/mutex.c:perf_trace_contention_end
  - kernel/locking/mutex.c:perf_trace_contention_begin
```
```
In kernel/printk/printk.c (ffffffff811ae3c8)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/printk/printk.c:unregister_console_locked
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/resend.c (ffffffff811bbaa8)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/irq/resend.c:resend_irqs
```
```
In kernel/irq/matrix.c (ffffffff811c9333)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff811cac58)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_stall_warning
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff811ec48f)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/entry/common.c (ffffffff811ee66e)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/entry/common.c:perf_trace_sys_exit
  - kernel/entry/common.c:perf_trace_sys_enter
```
```
In kernel/module/main.c (ffffffff811f0e5e)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/module/main.c:perf_trace_module_request
  - kernel/module/main.c:perf_trace_module_refcnt
  - kernel/module/main.c:perf_trace_module_free
  - kernel/module/main.c:perf_trace_module_load
```
```
In kernel/time/timer.c (ffffffff81202e33)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:__run_timers
  - kernel/time/timer.c:perf_trace_tick_stop
  - kernel/time/timer.c:perf_trace_itimer_expire
  - kernel/time/timer.c:perf_trace_itimer_state
  - kernel/time/timer.c:perf_trace_hrtimer_class
  - kernel/time/timer.c:perf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:perf_trace_hrtimer_start
  - kernel/time/timer.c:perf_trace_hrtimer_init
  - kernel/time/timer.c:perf_trace_timer_base_idle
  - kernel/time/timer.c:perf_trace_timer_expire_entry
  - kernel/time/timer.c:perf_trace_timer_start
  - kernel/time/timer.c:perf_trace_timer_class
```
```
In kernel/time/alarmtimer.c (ffffffff8120d5d7)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/time/posix-cpu-timers.c (ffffffff812133fd)
Location: include/linux/list.h:978
Inline: True
```
```
In kernel/smp.c (ffffffff81224f48)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/smp.c:perf_trace_csd_function
  - kernel/smp.c:perf_trace_csd_queue_cpu
```
```
In kernel/cgroup/cgroup.c (ffffffff81231a68)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/ftrace.c (ffffffff81285667)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:profile_graph_return
```
```
In kernel/trace/trace_osnoise.c (ffffffff812b07d4)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:perf_trace_sample_threshold
  - kernel/trace/trace_osnoise.c:perf_trace_nmi_noise
  - kernel/trace/trace_osnoise.c:perf_trace_irq_noise
  - kernel/trace/trace_osnoise.c:perf_trace_softirq_noise
  - kernel/trace/trace_osnoise.c:perf_trace_thread_noise
```
```
In kernel/trace/trace_syscalls.c (ffffffff812c4864)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/trace_events_user.c (ffffffff812e0248)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_perf
```
```
In kernel/trace/bpf_trace.c (ffffffff812e45f9)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_trace_bpf_trace_printk
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ed64e)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/error_report-traces.c (ffffffff812eeac8)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/trace/error_report-traces.c:perf_trace_error_report_template
```
```
In kernel/trace/power-traces.c (ffffffff812f0102)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:perf_trace_guest_halt_poll_ns
  - kernel/trace/power-traces.c:perf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update
  - kernel/trace/power-traces.c:perf_trace_cpu_latency_qos_request
  - kernel/trace/power-traces.c:perf_trace_power_domain
  - kernel/trace/power-traces.c:perf_trace_clock
  - kernel/trace/power-traces.c:perf_trace_wakeup_source
  - kernel/trace/power-traces.c:perf_trace_suspend_resume
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:perf_trace_cpu_frequency_limits
  - kernel/trace/power-traces.c:perf_trace_pstate_sample
  - kernel/trace/power-traces.c:perf_trace_powernv_throttle
  - kernel/trace/power-traces.c:perf_trace_cpu_idle_miss
  - kernel/trace/power-traces.c:perf_trace_cpu
```
```
In kernel/trace/rpm-traces.c (ffffffff812f30fe)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffffffff812f97a4)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/trace/trace_fprobe.c (ffffffff812fffba)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:fexit_perf_func
  - kernel/trace/trace_fprobe.c:fentry_perf_func
```
```
In kernel/trace/rv/rv.c (ffffffff813009ea)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/trace/rv/rv.c:perf_trace_error_da_monitor_id
  - kernel/trace/rv/rv.c:perf_trace_event_da_monitor_id
```
```
In kernel/bpf/core.c (ffffffff81305d59)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_bpf_xdp_link_attach_failed
  - kernel/bpf/core.c:perf_trace_mem_return_failed
  - kernel/bpf/core.c:perf_trace_mem_connect
  - kernel/bpf/core.c:perf_trace_mem_disconnect
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_bulk_tx
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff813591f0)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
```
```
In kernel/bpf/trampoline.c (ffffffff8135d0cf)
Location: include/linux/list.h:978
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff81380b07)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
```
In kernel/events/core.c (ffffffff813979a7)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/events/core.c:perf_trace_run_bpf_submit
```
```
In kernel/user-return-notifier.c (ffffffff813ad7a2)
Location: include/linux/list.h:978
Inline: True
```
```
In kernel/context_tracking.c (ffffffff813b08fd)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/context_tracking.c:perf_trace_context_tracking_user
```
```
In kernel/rseq.c (ffffffff813b14ff)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In kernel/watch_queue.c (ffffffff813b34e6)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
```
```
In mm/filemap.c (ffffffff813b4790)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff813be437)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:perf_trace_skip_task_reaping
  - mm/oom_kill.c:perf_trace_finish_task_reaping
  - mm/oom_kill.c:perf_trace_start_task_reaping
  - mm/oom_kill.c:perf_trace_wake_reaper
  - mm/oom_kill.c:perf_trace_mark_victim
  - mm/oom_kill.c:perf_trace_reclaim_retry_zone
  - mm/oom_kill.c:perf_trace_oom_score_adj_update
```
```
In mm/swap.c (ffffffff813c8e6d)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff813d0ef8)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - mm/vmscan.c:perf_trace_mm_vmscan_throttled
  - mm/vmscan.c:perf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:perf_trace_mm_vmscan_write_folio
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_isolate
  - mm/vmscan.c:perf_trace_mm_shrink_slab_end
  - mm/vmscan.c:perf_trace_mm_shrink_slab_start
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_end_template
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:perf_trace_mm_vmscan_wakeup_kswapd
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_wake
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_sleep
```
```
In mm/percpu.c (ffffffff813f785d)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff813fdd5b)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - mm/slab_common.c:perf_trace_rss_stat
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:perf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:perf_trace_mm_page
  - mm/slab_common.c:perf_trace_mm_page_alloc
  - mm/slab_common.c:perf_trace_mm_page_free_batched
  - mm/slab_common.c:perf_trace_mm_page_free
  - mm/slab_common.c:perf_trace_kmem_cache_free
  - mm/slab_common.c:perf_trace_kfree
  - mm/slab_common.c:perf_trace_kmalloc
  - mm/slab_common.c:perf_trace_kmem_cache_alloc
```
```
In mm/compaction.c (ffffffff814011e2)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - mm/compaction.c:perf_trace_kcompactd_wake_template
  - mm/compaction.c:perf_trace_mm_compaction_kcompactd_sleep
  - mm/compaction.c:perf_trace_mm_compaction_defer_template
  - mm/compaction.c:perf_trace_mm_compaction_suitable_template
  - mm/compaction.c:perf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:perf_trace_mm_compaction_end
  - mm/compaction.c:perf_trace_mm_compaction_begin
  - mm/compaction.c:perf_trace_mm_compaction_migratepages
  - mm/compaction.c:perf_trace_mm_compaction_isolate_template
```
```
In mm/mmap_lock.c (ffffffff8141370d)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - mm/mmap_lock.c:perf_trace_mmap_lock_acquire_returned
  - mm/mmap_lock.c:perf_trace_mmap_lock
```
```
In mm/mmap.c (ffffffff81425ec5)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - mm/mmap.c:perf_trace_exit_mmap
  - mm/mmap.c:perf_trace_vma_store
  - mm/mmap.c:perf_trace_vma_mas_szero
  - mm/mmap.c:perf_trace_vm_unmapped_area
```
```
In mm/rmap.c (ffffffff81436ba2)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - mm/rmap.c:perf_trace_migration_pte
  - mm/rmap.c:perf_trace_mm_migrate_pages_start
  - mm/rmap.c:perf_trace_mm_migrate_pages
  - mm/rmap.c:perf_trace_tlb_flush
```
```
In mm/vmalloc.c (ffffffff8143c854)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - mm/vmalloc.c:perf_trace_free_vmap_area_noflush
  - mm/vmalloc.c:perf_trace_purge_vmap_area_lazy
  - mm/vmalloc.c:perf_trace_alloc_vmap_area
```
```
In mm/mmu_notifier.c (ffffffff8148a584)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_subscriptions_destroy
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_release
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (ffffffff8148d3c9)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:perf_trace_ksm_advisor
  - mm/ksm.c:perf_trace_ksm_remove_rmap_item
  - mm/ksm.c:perf_trace_ksm_remove_ksm_page
  - mm/ksm.c:perf_trace_ksm_merge_with_ksm_page
  - mm/ksm.c:perf_trace_ksm_merge_one_page
  - mm/ksm.c:perf_trace_ksm_enter_exit_template
  - mm/ksm.c:perf_trace_ksm_scan_template
```
```
In mm/huge_memory.c (ffffffff8149f918)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - mm/huge_memory.c:perf_trace_migration_pmd
  - mm/huge_memory.c:perf_trace_hugepage_update
  - mm/huge_memory.c:perf_trace_hugepage_set
```
```
In mm/khugepaged.c (ffffffff814aad5e)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_khugepaged_collapse_file
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_file
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff814c97b4)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In fs/super.c (ffffffff814e6ada)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - fs/super.c:reconfigure_super
```
```
In fs/dcache.c (ffffffff81506c82)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_find_alias_rcu
  - fs/dcache.c:d_find_alias
  - fs/dcache.c:d_find_alias
```
```
In fs/namespace.c (ffffffff815186c7)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:namespace_unlock
```
```
In fs/seq_file.c (ffffffff8151c142)
Location: include/linux/list.h:978
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81526529)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_writeback_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_pages_written
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_folio_template
```
```
In fs/notify/mark.c (ffffffff815488b4)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8154fd6e)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
```
```
In fs/eventpoll.c (ffffffff8155436e)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:reverse_path_check_proc
```
```
In fs/dax.c (ffffffff81562864)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - fs/dax.c:perf_trace_dax_writeback_one
  - fs/dax.c:perf_trace_dax_writeback_range_class
  - fs/dax.c:perf_trace_dax_insert_mapping
  - fs/dax.c:perf_trace_dax_pte_fault_class
  - fs/dax.c:perf_trace_dax_pmd_insert_mapping_class
  - fs/dax.c:perf_trace_dax_pmd_load_hole_class
  - fs/dax.c:perf_trace_dax_pmd_fault_class
```
```
In fs/locks.c (ffffffff81575052)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/iomap/trace.c (ffffffff81588b23)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - fs/iomap/trace.c:perf_trace_iomap_dio_complete
  - fs/iomap/trace.c:perf_trace_iomap_dio_rw_begin
  - fs/iomap/trace.c:perf_trace_iomap_iter
  - fs/iomap/trace.c:perf_trace_iomap_class
  - fs/iomap/trace.c:perf_trace_iomap_range_class
  - fs/iomap/trace.c:perf_trace_iomap_readpage_class
```
```
In fs/ext4/super.c (ffffffff81623a66)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_update_sb
  - fs/ext4/super.c:perf_trace_ext4_fc_cleanup
  - fs/ext4/super.c:perf_trace_ext4_fc_track_range
  - fs/ext4/super.c:perf_trace_ext4_fc_track_inode
  - fs/ext4/super.c:perf_trace_ext4_fc_track_dentry
  - fs/ext4/super.c:perf_trace_ext4_fc_stats
  - fs/ext4/super.c:perf_trace_ext4_fc_commit_stop
  - fs/ext4/super.c:perf_trace_ext4_fc_commit_start
  - fs/ext4/super.c:perf_trace_ext4_fc_replay
  - fs/ext4/super.c:perf_trace_ext4_fc_replay_scan
  - fs/ext4/super.c:perf_trace_ext4_lazy_itable_init
  - fs/ext4/super.c:perf_trace_ext4_prefetch_bitmaps
  - fs/ext4/super.c:perf_trace_ext4_error
  - fs/ext4/super.c:perf_trace_ext4_shutdown
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:perf_trace_ext4_insert_range
  - fs/ext4/super.c:perf_trace_ext4_collapse_range
  - fs/ext4/super.c:perf_trace_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:perf_trace_ext4__es_shrink_enter
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_enter
  - fs/ext4/super.c:perf_trace_ext4_es_remove_extent
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_idx
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_show_extent
  - fs/ext4/super.c:perf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:perf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:perf_trace_ext4__trim
  - fs/ext4/super.c:perf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:perf_trace_ext4_journal_start_inode
  - fs/ext4/super.c:perf_trace_ext4_journal_start_sb
  - fs/ext4/super.c:perf_trace_ext4_load_inode
  - fs/ext4/super.c:perf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_exit
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_enter
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:perf_trace_ext4__truncate
  - fs/ext4/super.c:perf_trace_ext4_unlink_exit
  - fs/ext4/super.c:perf_trace_ext4_unlink_enter
  - fs/ext4/super.c:perf_trace_ext4_fallocate_exit
  - fs/ext4/super.c:perf_trace_ext4__fallocate_mode
  - fs/ext4/super.c:perf_trace_ext4_read_block_bitmap_load
  - fs/ext4/super.c:perf_trace_ext4__bitmap_load
  - fs/ext4/super.c:perf_trace_ext4_da_release_space
  - fs/ext4/super.c:perf_trace_ext4_da_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_da_update_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_forget
  - fs/ext4/super.c:perf_trace_ext4__mballoc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_prealloc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_alloc
  - fs/ext4/super.c:perf_trace_ext4_alloc_da_blocks
  - fs/ext4/super.c:perf_trace_ext4_sync_fs
  - fs/ext4/super.c:perf_trace_ext4_sync_file_exit
  - fs/ext4/super.c:perf_trace_ext4_sync_file_enter
  - fs/ext4/super.c:perf_trace_ext4_free_blocks
  - fs/ext4/super.c:perf_trace_ext4_allocate_blocks
  - fs/ext4/super.c:perf_trace_ext4_request_blocks
  - fs/ext4/super.c:perf_trace_ext4_mb_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_mb_release_group_pa
  - fs/ext4/super.c:perf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:perf_trace_ext4__mb_new_pa
  - fs/ext4/super.c:perf_trace_ext4_discard_blocks
  - fs/ext4/super.c:perf_trace_ext4_invalidate_folio_op
  - fs/ext4/super.c:perf_trace_ext4__folio_op
  - fs/ext4/super.c:perf_trace_ext4_writepages_result
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages_extent
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages
  - fs/ext4/super.c:perf_trace_ext4_writepages
  - fs/ext4/super.c:perf_trace_ext4__write_end
  - fs/ext4/super.c:perf_trace_ext4__write_begin
  - fs/ext4/super.c:perf_trace_ext4_begin_ordered_truncate
  - fs/ext4/super.c:perf_trace_ext4_mark_inode_dirty
  - fs/ext4/super.c:perf_trace_ext4_nfs_commit_metadata
  - fs/ext4/super.c:perf_trace_ext4_drop_inode
  - fs/ext4/super.c:perf_trace_ext4_evict_inode
  - fs/ext4/super.c:perf_trace_ext4_allocate_inode
  - fs/ext4/super.c:perf_trace_ext4_request_inode
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
```
```
In fs/jbd2/journal.c (ffffffff816567b9)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - fs/jbd2/journal.c:perf_trace_jbd2_shrink_checkpoint_list
  - fs/jbd2/journal.c:perf_trace_jbd2_shrink_scan_exit
  - fs/jbd2/journal.c:perf_trace_jbd2_journal_shrink
  - fs/jbd2/journal.c:perf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:perf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:perf_trace_jbd2_update_log_tail
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_run_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_extend
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_start_class
  - fs/jbd2/journal.c:perf_trace_jbd2_submit_inode_data
  - fs/jbd2/journal.c:perf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint
```
```
In security/selinux/avc.c (ffffffff816e20b2)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_get_hash_stats
  - security/selinux/avc.c:perf_trace_selinux_audited
```
```
In block/blk-core.c (ffffffff817b1c1f)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_unplug
  - block/blk-core.c:perf_trace_block_plug
  - block/blk-core.c:perf_trace_block_bio
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_completion
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_buffer
```
```
In block/blk-ioc.c (ffffffff817b9155)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff817e6029)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_unpin_online
```
```
In block/blk-iocost.c (ffffffff817ef0bb)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_iocg_forgive_debt
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_state
```
```
In block/blk-wbt.c (ffffffff817fdad5)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In io_uring/io_uring.c (ffffffff8180c0f2)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - io_uring/io_uring.c:perf_trace_io_uring_local_work_run
  - io_uring/io_uring.c:perf_trace_io_uring_short_write
  - io_uring/io_uring.c:perf_trace_io_uring_task_work_run
  - io_uring/io_uring.c:perf_trace_io_uring_cqe_overflow
  - io_uring/io_uring.c:perf_trace_io_uring_req_failed
  - io_uring/io_uring.c:perf_trace_io_uring_task_add
  - io_uring/io_uring.c:perf_trace_io_uring_poll_arm
  - io_uring/io_uring.c:perf_trace_io_uring_submit_req
  - io_uring/io_uring.c:perf_trace_io_uring_complete
  - io_uring/io_uring.c:perf_trace_io_uring_fail_link
  - io_uring/io_uring.c:perf_trace_io_uring_cqring_wait
  - io_uring/io_uring.c:perf_trace_io_uring_link
  - io_uring/io_uring.c:perf_trace_io_uring_defer
  - io_uring/io_uring.c:perf_trace_io_uring_queue_async_work
  - io_uring/io_uring.c:perf_trace_io_uring_file_get
  - io_uring/io_uring.c:perf_trace_io_uring_register
  - io_uring/io_uring.c:perf_trace_io_uring_create
```
```
In arch/x86/lib/msr.c (ffffffff81930522)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff81944a82)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/pwm/core.c (ffffffff81959ee2)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - drivers/pwm/core.c:perf_trace_pwm
```
```
In drivers/clk/clk.c (ffffffff81a9012c)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:perf_trace_clk_rate_request
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate_range
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff81ad3486)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/iommu/intel/trace.c (ffffffff81b6a11d)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - drivers/iommu/intel/trace.c:perf_trace_prq_report
  - drivers/iommu/intel/trace.c:perf_trace_qi_submit
```
```
In drivers/iommu/iommu-traces.c (ffffffff81b78bc3)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff81bbc536)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bulk
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
```
```
In drivers/base/trace.c (ffffffff81bcdd00)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - drivers/base/trace.c:perf_trace_devres
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81c130bc)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81c19b1d)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff81c1c0c3)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/scsi/sd_zbc.c (ffffffff81c413a2)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:perf_trace_scsi_zone_wp_update
  - drivers/scsi/sd_zbc.c:perf_trace_scsi_prepare_zone_append
```
```
In drivers/ata/libata-core.c (ffffffff81c4dd4a)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_sff_template
  - drivers/ata/libata-core.c:perf_trace_ata_transfer_data_template
  - drivers/ata/libata-core.c:perf_trace_ata_sff_hsm_template
  - drivers/ata/libata-core.c:perf_trace_ata_port_eh_begin_template
  - drivers/ata/libata-core.c:perf_trace_ata_link_reset_end_template
  - drivers/ata/libata-core.c:perf_trace_ata_link_reset_begin_template
  - drivers/ata/libata-core.c:perf_trace_ata_eh_action_template
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_bmdma_status
  - drivers/ata/libata-core.c:perf_trace_ata_exec_command_template
  - drivers/ata/libata-core.c:perf_trace_ata_tf_load
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue_template
```
```
In drivers/gpu/drm/drm_trace_points.c (ffffffff81cb38b2)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_trace_points.c:perf_trace_drm_vblank_event_delivered
  - drivers/gpu/drm/drm_trace_points.c:perf_trace_drm_vblank_event_queued
  - drivers/gpu/drm/drm_trace_points.c:perf_trace_drm_vblank_event
```
```
In drivers/spi/spi.c (ffffffff81cdb508)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_set_cs
  - drivers/spi/spi.c:perf_trace_spi_setup
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81cf2675)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81db003a)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_dbc_log_request
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_doorbell
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_slot_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ep_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_free_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_trb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
```
```
In drivers/rtc/interface.c (ffffffff81dd7b4d)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - drivers/rtc/interface.c:perf_trace_rtc_timer_class
  - drivers/rtc/interface.c:perf_trace_rtc_offset_class
  - drivers/rtc/interface.c:perf_trace_rtc_alarm_irq_enable
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_state
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_freq
  - drivers/rtc/interface.c:perf_trace_rtc_time_alarm_class
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81ddf5db)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81de4d2f)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff81dfae05)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff81dfd3a1)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81e064df)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_actor
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/watchdog/watchdog_core.c (ffffffff81e0ade5)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:perf_trace_watchdog_set_timeout
  - drivers/watchdog/watchdog_core.c:perf_trace_watchdog_template
```
```
In drivers/cpufreq/amd-pstate-trace.c (ffffffff81e5b350)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate-trace.c:perf_trace_amd_pstate_perf
```
```
In drivers/mmc/core/core.c (ffffffff81e69d54)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffffffff81e96b27)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_start
```
```
In drivers/devfreq/devfreq.c (ffffffff81ea1f41)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_frequency
```
```
In drivers/ras/ras.c (ffffffff81ead3f2)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_memory_failure_event
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_non_standard_event
  - drivers/ras/ras.c:perf_trace_arm_event
  - drivers/ras/ras.c:perf_trace_mc_event
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
```
```
In drivers/interconnect/core.c (ffffffff81eb321e)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_node_destroy
  - drivers/interconnect/core.c:perf_trace_icc_set_bw_end
  - drivers/interconnect/core.c:perf_trace_icc_set_bw
```
```
In net/core/page_pool_user.c (ffffffff81f4561b)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - net/core/page_pool_user.c:page_pool_netdevice_event
```
```
In net/core/net-traces.c (ffffffff81f5416f)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:perf_trace_neigh_create
  - net/core/net-traces.c:perf_trace_page_pool_update_nid
  - net/core/net-traces.c:perf_trace_page_pool_state_hold
  - net/core/net-traces.c:perf_trace_page_pool_state_release
  - net/core/net-traces.c:perf_trace_page_pool_release
  - net/core/net-traces.c:perf_trace_br_mdb_full
  - net/core/net-traces.c:perf_trace_br_fdb_update
  - net/core/net-traces.c:perf_trace_fdb_delete
  - net/core/net-traces.c:perf_trace_br_fdb_external_learn_add
  - net/core/net-traces.c:perf_trace_br_fdb_add
  - net/core/net-traces.c:perf_trace_qdisc_create
  - net/core/net-traces.c:perf_trace_qdisc_destroy
  - net/core/net-traces.c:perf_trace_qdisc_reset
  - net/core/net-traces.c:perf_trace_qdisc_enqueue
  - net/core/net-traces.c:perf_trace_qdisc_dequeue
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:perf_trace_tcp_cong_state_set
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:perf_trace_sock_msg_length
  - net/core/net-traces.c:perf_trace_sk_data_ready
  - net/core/net-traces.c:perf_trace_inet_sk_error_report
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_rcvqueue_full
  - net/core/net-traces.c:perf_trace_napi_poll
  - net/core/net-traces.c:perf_trace_net_dev_rx_exit_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_template
  - net/core/net-traces.c:perf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:perf_trace_net_dev_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:perf_trace_consume_skb
  - net/core/net-traces.c:perf_trace_kfree_skb
```
```
In net/core/bpf_sk_storage.c (ffffffff81f6b77d)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
```
In net/netlink/af_netlink.c (ffffffff81f85cd9)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:perf_trace_netlink_extack
```
```
In net/bpf/test_run.c (ffffffff81f90b20)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc7f9b)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fccb98)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse
```
```
In net/ipv4/udp.c (ffffffff82005c35)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_batch
  - net/ipv4/udp.c:udp_get_first
```
```
In net/ipv4/fib_trie.c (ffffffff8202eaa7)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
```
```
In net/ipv4/ping.c (ffffffff82031a64)
Location: include/linux/list.h:978
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff82060af4)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/xfrm/xfrm_state.c (ffffffff8206db90)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
```
```
In net/unix/af_unix.c (ffffffff82076fd0)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_get_first
```
```
In net/ipv6/anycast.c (ffffffff82081e13)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_anycast_cleanup
```
```
In net/ipv6/addrconf.c (ffffffff82090ae7)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_exit_net
```
```
In net/ipv6/route.c (ffffffff820993cb)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
```
In net/packet/af_packet.c (ffffffff820f4ec0)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_net_exit
```
```
In net/devlink/core.c (ffffffff820ff313)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - net/devlink/core.c:perf_trace_devlink_trap_report
  - net/devlink/core.c:perf_trace_devlink_health_reporter_state_update
  - net/devlink/core.c:perf_trace_devlink_health_recover_aborted
  - net/devlink/core.c:perf_trace_devlink_health_report
  - net/devlink/core.c:perf_trace_devlink_hwerr
  - net/devlink/core.c:perf_trace_devlink_hwmsg
```
```
In net/xdp/xsk.c (ffffffff8213c425)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_net_exit
```
```
In net/mptcp/protocol.c (ffffffff82143a98)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - net/mptcp/protocol.c:perf_trace_subflow_check_data_avail
  - net/mptcp/protocol.c:perf_trace_ack_update_msk
  - net/mptcp/protocol.c:perf_trace_mptcp_dump_mpext
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
```
```
In net/mctp/af_mctp.c (ffffffff82162a2a)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:perf_trace_mctp_key_release
  - net/mctp/af_mctp.c:perf_trace_mctp_key_acquire
```
```
In net/handshake/trace.c (ffffffff8216cb53)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - net/handshake/trace.c:perf_trace_tls_contenttype
  - net/handshake/trace.c:perf_trace_handshake_complete
  - net/handshake/trace.c:perf_trace_handshake_alert_class
  - net/handshake/trace.c:perf_trace_handshake_error_class
  - net/handshake/trace.c:perf_trace_handshake_fd_class
  - net/handshake/trace.c:perf_trace_handshake_event_class
```
```
In lib/maple_tree.c (ffffffff8217e008)
Location: include/linux/list.h:978
Inline: True
Inline callers:
  - lib/maple_tree.c:perf_trace_ma_write
  - lib/maple_tree.c:perf_trace_ma_read
  - lib/maple_tree.c:perf_trace_ma_op
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
In init/main.c (ffff800010084ca0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/arm64/kernel/ptrace.c (ffff80001008a940)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/arm64/kernel/ptrace.c:perf_trace_sys_exit
  - arch/arm64/kernel/ptrace.c:perf_trace_sys_enter
```
```
In arch/arm64/kernel/smp.c (ffff80001009be74)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:perf_trace_ipi_handler
  - arch/arm64/kernel/smp.c:perf_trace_ipi_raise
```
```
In arch/arm64/kernel/armv8_deprecated.c (ffff8000100a8500)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/arm64/kernel/armv8_deprecated.c:perf_trace_instruction_emulation
```
```
In virt/kvm/kvm_main.c (ffff8000100ba518)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:perf_trace_kvm_halt_poll_ns
  - virt/kvm/kvm_main.c:perf_trace_kvm_age_page
  - virt/kvm/kvm_main.c:perf_trace_kvm_fpu
  - virt/kvm/kvm_main.c:perf_trace_kvm_mmio
  - virt/kvm/kvm_main.c:perf_trace_kvm_ack_irq
  - virt/kvm/kvm_main.c:perf_trace_kvm_set_irq
  - virt/kvm/kvm_main.c:perf_trace_kvm_vcpu_wakeup
  - virt/kvm/kvm_main.c:perf_trace_kvm_userspace_exit
```
```
In virt/kvm/arm/arm.c (ffff8000100c4f3c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:perf_trace_kvm_timer_emulate
  - virt/kvm/arm/arm.c:perf_trace_kvm_timer_hrtimer_expire
  - virt/kvm/arm/arm.c:perf_trace_kvm_timer_restore_state
  - virt/kvm/arm/arm.c:perf_trace_kvm_timer_save_state
  - virt/kvm/arm/arm.c:perf_trace_kvm_get_timer_map
  - virt/kvm/arm/arm.c:perf_trace_kvm_timer_update_irq
  - virt/kvm/arm/arm.c:perf_trace_kvm_toggle_cache
  - virt/kvm/arm/arm.c:perf_trace_kvm_set_way_flush
  - virt/kvm/arm/arm.c:perf_trace_kvm_test_age_hva
  - virt/kvm/arm/arm.c:perf_trace_kvm_age_hva
  - virt/kvm/arm/arm.c:perf_trace_kvm_set_spte_hva
  - virt/kvm/arm/arm.c:perf_trace_kvm_unmap_hva_range
  - virt/kvm/arm/arm.c:perf_trace_kvm_mmio_emulate
  - virt/kvm/arm/arm.c:perf_trace_kvm_irq_line
  - virt/kvm/arm/arm.c:perf_trace_kvm_access_fault
  - virt/kvm/arm/arm.c:perf_trace_kvm_guest_fault
  - virt/kvm/arm/arm.c:perf_trace_kvm_exit
  - virt/kvm/arm/arm.c:perf_trace_kvm_entry
```
```
In arch/arm64/kvm/handle_exit.c (ffff8000100d0d50)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/arm64/kvm/handle_exit.c:perf_trace_kvm_set_guest_debug
  - arch/arm64/kvm/handle_exit.c:perf_trace_kvm_sys_access
  - arch/arm64/kvm/handle_exit.c:perf_trace_kvm_handle_sys_reg
  - arch/arm64/kvm/handle_exit.c:perf_trace_trap_reg
  - arch/arm64/kvm/handle_exit.c:perf_trace_kvm_arm_set_regset
  - arch/arm64/kvm/handle_exit.c:perf_trace_kvm_arm_set_dreg32
  - arch/arm64/kvm/handle_exit.c:perf_trace_kvm_arm_clear_debug
  - arch/arm64/kvm/handle_exit.c:perf_trace_kvm_arm_setup_debug
  - arch/arm64/kvm/handle_exit.c:perf_trace_kvm_hvc_arm64
  - arch/arm64/kvm/handle_exit.c:perf_trace_kvm_wfx_arm64
```
```
In virt/kvm/arm/vgic/vgic.c (ffff8000100db884)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic.c:perf_trace_vgic_update_irq_pending
```
```
In kernel/fork.c (ffff8000100f178c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffff8000100f9004)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/exit.c (ffff8000100fb9c0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/softirq.c (ffff8000100fecd4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffff80001010b0e8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffff80001011d514)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/pid.c (ffff8000101245d8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/sched/core.c (ffff80001013545c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_wake_idle_without_ipi
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:perf_trace_sched_process_hang
  - kernel/sched/core.c:perf_trace_sched_pi_setprio
  - kernel/sched/core.c:perf_trace_sched_stat_runtime
  - kernel/sched/core.c:perf_trace_sched_process_exec
  - kernel/sched/core.c:perf_trace_sched_process_fork
  - kernel/sched/core.c:perf_trace_sched_process_wait
  - kernel/sched/core.c:perf_trace_sched_process_template
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:perf_trace_sched_kthread_stop_ret
  - kernel/sched/core.c:perf_trace_sched_kthread_stop
```
```
In kernel/printk/printk.c (ffff800010172af4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/rcu/update.c (ffff80001018867c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffff800010196420)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/time/timer.c (ffff8000101a032c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:perf_trace_tick_stop
  - kernel/time/timer.c:perf_trace_itimer_expire
  - kernel/time/timer.c:perf_trace_itimer_state
  - kernel/time/timer.c:perf_trace_hrtimer_class
  - kernel/time/timer.c:perf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:perf_trace_hrtimer_start
  - kernel/time/timer.c:perf_trace_hrtimer_init
  - kernel/time/timer.c:perf_trace_timer_expire_entry
  - kernel/time/timer.c:perf_trace_timer_start
  - kernel/time/timer.c:perf_trace_timer_class
```
```
In kernel/time/alarmtimer.c (ffff8000101a8f10)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffff8000101c243c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffff8000101d0620)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/kprobes.c (ffff8000101f846c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/trace/ftrace.c (ffff80001021104c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:profile_graph_return
```
```
In kernel/trace/trace_syscalls.c (ffff80001023d984)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffff800010251038)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/power-traces.c (ffff8000102541cc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:perf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:perf_trace_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_power_domain
  - kernel/trace/power-traces.c:perf_trace_clock
  - kernel/trace/power-traces.c:perf_trace_wakeup_source
  - kernel/trace/power-traces.c:perf_trace_suspend_resume
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:perf_trace_cpu_frequency_limits
  - kernel/trace/power-traces.c:perf_trace_pstate_sample
  - kernel/trace/power-traces.c:perf_trace_powernv_throttle
  - kernel/trace/power-traces.c:perf_trace_cpu
```
```
In kernel/trace/rpm-traces.c (ffff800010254cbc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffff800010259884)
Location: include/linux/list.h:752
Inline: True
```
```
In kernel/bpf/core.c (ffff80001025cc38)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_mem_return_failed
  - kernel/bpf/core.c:perf_trace_mem_connect
  - kernel/bpf/core.c:perf_trace_mem_disconnect
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_bulk_tx
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/events/core.c (ffff8000102a0bfc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/events/core.c:perf_trace_run_bpf_submit
```
```
In kernel/rseq.c (ffff8000102ac12c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffff8000102aeae8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffff8000102b6de0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:perf_trace_skip_task_reaping
  - mm/oom_kill.c:perf_trace_finish_task_reaping
  - mm/oom_kill.c:perf_trace_start_task_reaping
  - mm/oom_kill.c:perf_trace_wake_reaper
  - mm/oom_kill.c:perf_trace_mark_victim
  - mm/oom_kill.c:perf_trace_reclaim_retry_zone
  - mm/oom_kill.c:perf_trace_oom_score_adj_update
```
```
In mm/swap.c (ffff8000102c040c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffff8000102c7208)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/vmscan.c:perf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:perf_trace_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_isolate
  - mm/vmscan.c:perf_trace_mm_shrink_slab_end
  - mm/vmscan.c:perf_trace_mm_shrink_slab_start
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_end_template
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:perf_trace_mm_vmscan_wakeup_kswapd
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_wake
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_sleep
```
```
In mm/percpu.c (ffff8000102e2014)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffff8000102e69a8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:perf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:perf_trace_mm_page
  - mm/slab_common.c:perf_trace_mm_page_alloc
  - mm/slab_common.c:perf_trace_mm_page_free_batched
  - mm/slab_common.c:perf_trace_mm_page_free
  - mm/slab_common.c:perf_trace_kmem_free
  - mm/slab_common.c:perf_trace_kmem_alloc_node
  - mm/slab_common.c:perf_trace_kmem_alloc
```
```
In mm/compaction.c (ffff8000102e9548)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/compaction.c:perf_trace_kcompactd_wake_template
  - mm/compaction.c:perf_trace_mm_compaction_kcompactd_sleep
  - mm/compaction.c:perf_trace_mm_compaction_defer_template
  - mm/compaction.c:perf_trace_mm_compaction_suitable_template
  - mm/compaction.c:perf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:perf_trace_mm_compaction_end
  - mm/compaction.c:perf_trace_mm_compaction_begin
  - mm/compaction.c:perf_trace_mm_compaction_migratepages
  - mm/compaction.c:perf_trace_mm_compaction_isolate_template
```
```
In mm/mmu_notifier.c (ffff80001033d994)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_mm_destroy
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (ffff800010340fbc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
```
```
In mm/migrate.c (ffff80001034ea44)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffff80001035c3d4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffff800010371958)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffff800010376cb8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffff80001037d3e8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/super.c (ffff800010388a74)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/super.c:reconfigure_super
```
```
In fs/dcache.c (ffff8000103a8a50)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_find_any_alias
```
```
In fs/namespace.c (ffff8000103b8cf4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:namespace_unlock
```
```
In fs/seq_file.c (ffff8000103bc54c)
Location: include/linux/list.h:752
Inline: True
```
```
In fs/fs-writeback.c (ffff8000103c5394)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_writeback_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_congest_waited_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_pages_written
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
```
```
In fs/notify/mark.c (ffff8000103e9954)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/dax.c (ffff8000104081e8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/dax.c:perf_trace_dax_writeback_one
  - fs/dax.c:perf_trace_dax_writeback_range_class
  - fs/dax.c:perf_trace_dax_insert_mapping
  - fs/dax.c:perf_trace_dax_pte_fault_class
  - fs/dax.c:perf_trace_dax_pmd_insert_mapping_class
  - fs/dax.c:perf_trace_dax_pmd_load_hole_class
  - fs/dax.c:perf_trace_dax_pmd_fault_class
```
```
In fs/locks.c (ffff800010415aec)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffff8000104b3348)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_error
  - fs/ext4/super.c:perf_trace_ext4_shutdown
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:perf_trace_ext4_insert_range
  - fs/ext4/super.c:perf_trace_ext4_collapse_range
  - fs/ext4/super.c:perf_trace_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:perf_trace_ext4__es_shrink_enter
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_enter
  - fs/ext4/super.c:perf_trace_ext4_es_remove_extent
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_idx
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_show_extent
  - fs/ext4/super.c:perf_trace_ext4_get_reserved_cluster_alloc
  - fs/ext4/super.c:perf_trace_ext4_find_delalloc_range
  - fs/ext4/super.c:perf_trace_ext4_ext_in_cache
  - fs/ext4/super.c:perf_trace_ext4_ext_put_in_cache
  - fs/ext4/super.c:perf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:perf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:perf_trace_ext4__trim
  - fs/ext4/super.c:perf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:perf_trace_ext4_journal_start
  - fs/ext4/super.c:perf_trace_ext4_load_inode
  - fs/ext4/super.c:perf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_exit
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_enter
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:perf_trace_ext4__truncate
  - fs/ext4/super.c:perf_trace_ext4_unlink_exit
  - fs/ext4/super.c:perf_trace_ext4_unlink_enter
  - fs/ext4/super.c:perf_trace_ext4_fallocate_exit
  - fs/ext4/super.c:perf_trace_ext4__fallocate_mode
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_exit
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_enter
  - fs/ext4/super.c:perf_trace_ext4__bitmap_load
  - fs/ext4/super.c:perf_trace_ext4_da_release_space
  - fs/ext4/super.c:perf_trace_ext4_da_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_da_update_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_forget
  - fs/ext4/super.c:perf_trace_ext4__mballoc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_prealloc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_alloc
  - fs/ext4/super.c:perf_trace_ext4_alloc_da_blocks
  - fs/ext4/super.c:perf_trace_ext4_sync_fs
  - fs/ext4/super.c:perf_trace_ext4_sync_file_exit
  - fs/ext4/super.c:perf_trace_ext4_sync_file_enter
  - fs/ext4/super.c:perf_trace_ext4_free_blocks
  - fs/ext4/super.c:perf_trace_ext4_allocate_blocks
  - fs/ext4/super.c:perf_trace_ext4_request_blocks
  - fs/ext4/super.c:perf_trace_ext4_mb_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_mb_release_group_pa
  - fs/ext4/super.c:perf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:perf_trace_ext4__mb_new_pa
  - fs/ext4/super.c:perf_trace_ext4_discard_blocks
  - fs/ext4/super.c:perf_trace_ext4_invalidatepage_op
  - fs/ext4/super.c:perf_trace_ext4__page_op
  - fs/ext4/super.c:perf_trace_ext4_writepages_result
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages_extent
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages
  - fs/ext4/super.c:perf_trace_ext4_writepages
  - fs/ext4/super.c:perf_trace_ext4__write_end
  - fs/ext4/super.c:perf_trace_ext4__write_begin
  - fs/ext4/super.c:perf_trace_ext4_begin_ordered_truncate
  - fs/ext4/super.c:perf_trace_ext4_mark_inode_dirty
  - fs/ext4/super.c:perf_trace_ext4_nfs_commit_metadata
  - fs/ext4/super.c:perf_trace_ext4_drop_inode
  - fs/ext4/super.c:perf_trace_ext4_evict_inode
  - fs/ext4/super.c:perf_trace_ext4_allocate_inode
  - fs/ext4/super.c:perf_trace_ext4_request_inode
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
```
```
In fs/jbd2/journal.c (ffff8000104d4f78)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/jbd2/journal.c:perf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:perf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:perf_trace_jbd2_update_log_tail
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_run_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_extend
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_start
  - fs/jbd2/journal.c:perf_trace_jbd2_submit_inode_data
  - fs/jbd2/journal.c:perf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint
```
```
In security/selinux/avc.c (ffff800010547680)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_get_hash_stats
```
```
In block/blk-core.c (ffff8000105e2230)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_unplug
  - block/blk-core.c:perf_trace_block_plug
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_buffer
```
```
In block/blk-ioc.c (ffff8000105e8688)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffff80001060e39c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In block/blk-iocost.c (ffff800010614adc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_activate
```
```
In block/blk-wbt.c (ffff800010621aa8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In drivers/gpio/gpiolib.c (ffff8000106bf8c8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (ffff8000107c1774)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/soc/qcom/rpmh-rsc.c (ffff80001081b8b8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/soc/qcom/rpmh-rsc.c:perf_trace_rpmh_send_msg
  - drivers/soc/qcom/rpmh-rsc.c:perf_trace_rpmh_tx_done
```
```
In drivers/regulator/core.c (ffff800010843aa8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffff8000108ad690)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/char/random.c:perf_trace_urandom_read
  - drivers/char/random.c:perf_trace_random_read
  - drivers/char/random.c:perf_trace_random__extract_entropy
  - drivers/char/random.c:perf_trace_random__get_random_bytes
  - drivers/char/random.c:perf_trace_xfer_secondary_pool
  - drivers/char/random.c:perf_trace_add_disk_randomness
  - drivers/char/random.c:perf_trace_add_input_randomness
  - drivers/char/random.c:perf_trace_debit_entropy
  - drivers/char/random.c:perf_trace_push_to_pool
  - drivers/char/random.c:perf_trace_credit_entropy_bits
  - drivers/char/random.c:perf_trace_random__mix_pool_bytes
  - drivers/char/random.c:perf_trace_add_device_randomness
```
```
In drivers/iommu/iommu-traces.c (ffff8000108c8610)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffff800010913ef8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
```
```
In drivers/dma-buf/dma-fence.c (ffff800010966ed0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffff80001096b150)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffff80001096e444)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffff800010998c44)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffff8000109c4708)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffff8000109d7770)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffff800010a89e9c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_dbc_log_request
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_slot_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ep_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_free_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_trb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
```
```
In drivers/rtc/interface.c (ffff800010aa8434)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/rtc/interface.c:perf_trace_rtc_timer_class
  - drivers/rtc/interface.c:perf_trace_rtc_offset_class
  - drivers/rtc/interface.c:perf_trace_rtc_alarm_irq_enable
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_state
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_freq
  - drivers/rtc/interface.c:perf_trace_rtc_time_alarm_class
```
```
In drivers/i2c/i2c-core-base.c (ffff800010ab0da8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffff800010ab40a8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffff800010ad21d8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffff800010ad4640)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (ffff800010adb114)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffff800010b2c5bc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffff800010b799fc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_cmd_class
```
```
In drivers/devfreq/devfreq.c (ffff800010b866e4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
```
```
In drivers/ras/ras.c (ffff800010b9dc38)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_memory_failure_event
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_non_standard_event
  - drivers/ras/ras.c:perf_trace_arm_event
  - drivers/ras/ras.c:perf_trace_mc_event
```
```
In net/core/net-traces.c (ffff800010c198a0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:perf_trace_neigh_create
  - net/core/net-traces.c:perf_trace_page_pool_state_hold
  - net/core/net-traces.c:perf_trace_page_pool_state_release
  - net/core/net-traces.c:perf_trace_page_pool_inflight
  - net/core/net-traces.c:perf_trace_br_fdb_update
  - net/core/net-traces.c:perf_trace_fdb_delete
  - net/core/net-traces.c:perf_trace_br_fdb_external_learn_add
  - net/core/net-traces.c:perf_trace_br_fdb_add
  - net/core/net-traces.c:perf_trace_qdisc_dequeue
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_rcvqueue_full
  - net/core/net-traces.c:perf_trace_napi_poll
  - net/core/net-traces.c:perf_trace_net_dev_rx_exit_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_template
  - net/core/net-traces.c:perf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:perf_trace_net_dev_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:perf_trace_consume_skb
  - net/core/net-traces.c:perf_trace_kfree_skb
```
```
In net/core/devlink.c (ffff800010c27694)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/core/bpf_sk_storage.c (ffff800010c322ac)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_update
```
```
In net/bpf/test_run.c (ffff800010c52f74)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv4/inet_hashtables.c (ffff800010c6b388)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6e320)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/raw.c (ffff800010c96874)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffff800010c9ac04)
Location: include/linux/list.h:752
Inline: True
```
```
In net/ipv4/fib_trie.c (ffff800010cbd6f8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdd550)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffff800010ce9470)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
```
```
In net/unix/af_unix.c (ffff800010cef05c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/anycast.c (ffff800010cf7ec0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_anycast_cleanup
```
```
In net/ipv6/addrconf.c (ffff800010d0ab6c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
```
```
In net/ipv6/route.c (ffff800010d0f874)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
```
In net/ipv6/raw.c (ffff800010d2a88c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffff800010d57050)
Location: include/linux/list.h:752
Inline: True
```
```
In net/xdp/xsk.c (ffff800010d7e970)
Location: include/linux/list.h:752
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
In init/main.c (c0302f7c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/arm/kernel/ptrace.c (c030b78c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/arm/kernel/ptrace.c:perf_trace_sys_exit
  - arch/arm/kernel/ptrace.c:perf_trace_sys_enter
```
```
In arch/arm/kernel/smp.c (c0311f4c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/arm/kernel/smp.c:perf_trace_ipi_handler
  - arch/arm/kernel/smp.c:perf_trace_ipi_raise
```
```
In arch/arm/common/bL_switcher.c (c032647c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/arm/common/bL_switcher.c:perf_trace_cpu_migrate
```
```
In kernel/fork.c (c034ff40)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (c03571f8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/exit.c (c0359954)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/softirq.c (c035b440)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (c0363794)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (c0370c2c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/pid.c (c037773c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/sched/core.c (c0380d00)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_wake_idle_without_ipi
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:perf_trace_sched_process_hang
  - kernel/sched/core.c:perf_trace_sched_pi_setprio
  - kernel/sched/core.c:perf_trace_sched_stat_runtime
  - kernel/sched/core.c:perf_trace_sched_process_exec
  - kernel/sched/core.c:perf_trace_sched_process_fork
  - kernel/sched/core.c:perf_trace_sched_process_wait
  - kernel/sched/core.c:perf_trace_sched_process_template
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:perf_trace_sched_kthread_stop_ret
  - kernel/sched/core.c:perf_trace_sched_kthread_stop
```
```
In kernel/printk/printk.c (c03c4a1c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/rcu/update.c (c03d6fd8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/time/timer.c (c03e9f9c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:perf_trace_tick_stop
  - kernel/time/timer.c:perf_trace_itimer_expire
  - kernel/time/timer.c:perf_trace_itimer_state
  - kernel/time/timer.c:perf_trace_hrtimer_class
  - kernel/time/timer.c:perf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:perf_trace_hrtimer_start
  - kernel/time/timer.c:perf_trace_hrtimer_init
  - kernel/time/timer.c:perf_trace_timer_expire_entry
  - kernel/time/timer.c:perf_trace_timer_start
  - kernel/time/timer.c:perf_trace_timer_class
```
```
In kernel/time/alarmtimer.c (c03f3ef4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (c0409064)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (c0413a18)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/kprobes.c (c0436d00)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/trace/ftrace.c (c044e5b4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:t_probe_next
  - kernel/trace/ftrace.c:ftrace_find_profiled_func
```
```
In kernel/trace/trace_syscalls.c (c04789f4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (c0482640)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/power-traces.c (c04863f0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:perf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:perf_trace_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_power_domain
  - kernel/trace/power-traces.c:perf_trace_clock
  - kernel/trace/power-traces.c:perf_trace_wakeup_source
  - kernel/trace/power-traces.c:perf_trace_suspend_resume
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:perf_trace_cpu_frequency_limits
  - kernel/trace/power-traces.c:perf_trace_pstate_sample
  - kernel/trace/power-traces.c:perf_trace_powernv_throttle
  - kernel/trace/power-traces.c:perf_trace_cpu
```
```
In kernel/trace/rpm-traces.c (c0487ef4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (c048b28c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/core.c (c048fa3c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_mem_return_failed
  - kernel/bpf/core.c:perf_trace_mem_connect
  - kernel/bpf/core.c:perf_trace_mem_disconnect
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_bulk_tx
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/events/core.c (c04d0bac)
Location: include/linux/list.h:752
Inline: True
```
```
In kernel/rseq.c (c04d91a4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (c04da4f0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (c04e2e98)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:perf_trace_skip_task_reaping
  - mm/oom_kill.c:perf_trace_finish_task_reaping
  - mm/oom_kill.c:perf_trace_start_task_reaping
  - mm/oom_kill.c:perf_trace_wake_reaper
  - mm/oom_kill.c:perf_trace_mark_victim
  - mm/oom_kill.c:perf_trace_reclaim_retry_zone
  - mm/oom_kill.c:perf_trace_oom_score_adj_update
```
```
In mm/swap.c (c04eb818)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (c04f05dc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/vmscan.c:perf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:perf_trace_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_isolate
  - mm/vmscan.c:perf_trace_mm_shrink_slab_end
  - mm/vmscan.c:perf_trace_mm_shrink_slab_start
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_end_template
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:perf_trace_mm_vmscan_wakeup_kswapd
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_wake
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_sleep
```
```
In mm/percpu.c (c05055d0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (c05092c8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:perf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:perf_trace_mm_page
  - mm/slab_common.c:perf_trace_mm_page_alloc
  - mm/slab_common.c:perf_trace_mm_page_free_batched
  - mm/slab_common.c:perf_trace_mm_page_free
  - mm/slab_common.c:perf_trace_kmem_free
  - mm/slab_common.c:perf_trace_kmem_alloc_node
  - mm/slab_common.c:perf_trace_kmem_alloc
```
```
In mm/compaction.c (c050c9a0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/compaction.c:perf_trace_kcompactd_wake_template
  - mm/compaction.c:perf_trace_mm_compaction_kcompactd_sleep
  - mm/compaction.c:perf_trace_mm_compaction_defer_template
  - mm/compaction.c:perf_trace_mm_compaction_suitable_template
  - mm/compaction.c:perf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:perf_trace_mm_compaction_end
  - mm/compaction.c:perf_trace_mm_compaction_begin
  - mm/compaction.c:perf_trace_mm_compaction_migratepages
  - mm/compaction.c:perf_trace_mm_compaction_isolate_template
```
```
In mm/mmu_notifier.c (c0544018)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_mm_destroy
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (c0547278)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
```
```
In mm/migrate.c (c0550bc8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/page_isolation.c (c055e584)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (c0562678)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (c0568700)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/super.c (c05710b0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/super.c:reconfigure_super
```
```
In fs/dcache.c (c058a0bc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_find_any_alias
```
```
In fs/namespace.c (c05966a0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:namespace_unlock
```
```
In fs/seq_file.c (c0599cd8)
Location: include/linux/list.h:752
Inline: True
```
```
In fs/fs-writeback.c (c059f800)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_writeback_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_congest_waited_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_pages_written
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
```
```
In fs/notify/mark.c (c05c1108)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/locks.c (c05e06f8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (c0670b38)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_error
  - fs/ext4/super.c:perf_trace_ext4_shutdown
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:perf_trace_ext4_insert_range
  - fs/ext4/super.c:perf_trace_ext4_collapse_range
  - fs/ext4/super.c:perf_trace_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:perf_trace_ext4__es_shrink_enter
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_enter
  - fs/ext4/super.c:perf_trace_ext4_es_remove_extent
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_idx
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_show_extent
  - fs/ext4/super.c:perf_trace_ext4_get_reserved_cluster_alloc
  - fs/ext4/super.c:perf_trace_ext4_find_delalloc_range
  - fs/ext4/super.c:perf_trace_ext4_ext_in_cache
  - fs/ext4/super.c:perf_trace_ext4_ext_put_in_cache
  - fs/ext4/super.c:perf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:perf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:perf_trace_ext4__trim
  - fs/ext4/super.c:perf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:perf_trace_ext4_journal_start
  - fs/ext4/super.c:perf_trace_ext4_load_inode
  - fs/ext4/super.c:perf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_exit
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_enter
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:perf_trace_ext4__truncate
  - fs/ext4/super.c:perf_trace_ext4_unlink_exit
  - fs/ext4/super.c:perf_trace_ext4_unlink_enter
  - fs/ext4/super.c:perf_trace_ext4_fallocate_exit
  - fs/ext4/super.c:perf_trace_ext4__fallocate_mode
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_exit
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_enter
  - fs/ext4/super.c:perf_trace_ext4__bitmap_load
  - fs/ext4/super.c:perf_trace_ext4_da_release_space
  - fs/ext4/super.c:perf_trace_ext4_da_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_da_update_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_forget
  - fs/ext4/super.c:perf_trace_ext4__mballoc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_prealloc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_alloc
  - fs/ext4/super.c:perf_trace_ext4_alloc_da_blocks
  - fs/ext4/super.c:perf_trace_ext4_sync_fs
  - fs/ext4/super.c:perf_trace_ext4_sync_file_exit
  - fs/ext4/super.c:perf_trace_ext4_sync_file_enter
  - fs/ext4/super.c:perf_trace_ext4_free_blocks
  - fs/ext4/super.c:perf_trace_ext4_allocate_blocks
  - fs/ext4/super.c:perf_trace_ext4_request_blocks
  - fs/ext4/super.c:perf_trace_ext4_mb_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_mb_release_group_pa
  - fs/ext4/super.c:perf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:perf_trace_ext4__mb_new_pa
  - fs/ext4/super.c:perf_trace_ext4_discard_blocks
  - fs/ext4/super.c:perf_trace_ext4_invalidatepage_op
  - fs/ext4/super.c:perf_trace_ext4__page_op
  - fs/ext4/super.c:perf_trace_ext4_writepages_result
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages_extent
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages
  - fs/ext4/super.c:perf_trace_ext4_writepages
  - fs/ext4/super.c:perf_trace_ext4__write_end
  - fs/ext4/super.c:perf_trace_ext4__write_begin
  - fs/ext4/super.c:perf_trace_ext4_begin_ordered_truncate
  - fs/ext4/super.c:perf_trace_ext4_mark_inode_dirty
  - fs/ext4/super.c:perf_trace_ext4_nfs_commit_metadata
  - fs/ext4/super.c:perf_trace_ext4_drop_inode
  - fs/ext4/super.c:perf_trace_ext4_evict_inode
  - fs/ext4/super.c:perf_trace_ext4_allocate_inode
  - fs/ext4/super.c:perf_trace_ext4_request_inode
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
```
```
In fs/jbd2/journal.c (c0695f7c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/jbd2/journal.c:perf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:perf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:perf_trace_jbd2_update_log_tail
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_run_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_extend
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_start
  - fs/jbd2/journal.c:perf_trace_jbd2_submit_inode_data
  - fs/jbd2/journal.c:perf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint
```
```
In security/selinux/avc.c (c06fd2a4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_get_hash_stats
```
```
In block/blk-core.c (c078d290)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_unplug
  - block/blk-core.c:perf_trace_block_plug
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_buffer
```
```
In block/blk-ioc.c (c079502c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (c07b8cf0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In block/blk-iocost.c (c07c0844)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_activate
```
```
In block/blk-wbt.c (c07c81b8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In drivers/gpio/gpiolib.c (c085d144)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (c08ee018)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/dma/tegra20-apb-dma.c (c092c70c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/dma/tegra20-apb-dma.c:perf_trace_tegra_dma_isr
  - drivers/dma/tegra20-apb-dma.c:perf_trace_tegra_dma_complete_cb
  - drivers/dma/tegra20-apb-dma.c:perf_trace_tegra_dma_tx_status
```
```
In drivers/regulator/core.c (c094cb48)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (c09a8ba0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/char/random.c:perf_trace_urandom_read
  - drivers/char/random.c:perf_trace_random_read
  - drivers/char/random.c:perf_trace_random__extract_entropy
  - drivers/char/random.c:perf_trace_random__get_random_bytes
  - drivers/char/random.c:perf_trace_xfer_secondary_pool
  - drivers/char/random.c:perf_trace_add_disk_randomness
  - drivers/char/random.c:perf_trace_add_input_randomness
  - drivers/char/random.c:perf_trace_debit_entropy
  - drivers/char/random.c:perf_trace_push_to_pool
  - drivers/char/random.c:perf_trace_credit_entropy_bits
  - drivers/char/random.c:perf_trace_random__mix_pool_bytes
  - drivers/char/random.c:perf_trace_add_device_randomness
```
```
In drivers/iommu/iommu-traces.c (c09bf5d0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (c09f8fac)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
```
```
In drivers/dma-buf/dma-fence.c (c0a3df4c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (c0a416e0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (c0a427c0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (c0a667c0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (c0ab1228)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (c0abe470)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (c0b5acb4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_dbc_log_request
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_slot_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ep_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_free_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_trb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
```
```
In drivers/usb/musb/musb_trace.c (c0b67e50)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/usb/musb/musb_trace.c:perf_trace_musb_req
  - drivers/usb/musb/musb_trace.c:perf_trace_musb_urb
  - drivers/usb/musb/musb_trace.c:perf_trace_musb_isr
  - drivers/usb/musb/musb_trace.c:perf_trace_musb_regl
  - drivers/usb/musb/musb_trace.c:perf_trace_musb_regw
  - drivers/usb/musb/musb_trace.c:perf_trace_musb_regb
  - drivers/usb/musb/musb_trace.c:perf_trace_musb_log
```
```
In drivers/usb/gadget/udc/trace.c (c0b74898)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/usb/gadget/udc/trace.c:perf_trace_udc_log_req
  - drivers/usb/gadget/udc/trace.c:perf_trace_udc_log_ep
  - drivers/usb/gadget/udc/trace.c:perf_trace_udc_log_gadget
```
```
In drivers/rtc/interface.c (c0b86414)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/rtc/interface.c:perf_trace_rtc_timer_class
  - drivers/rtc/interface.c:perf_trace_rtc_offset_class
  - drivers/rtc/interface.c:perf_trace_rtc_alarm_irq_enable
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_state
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_freq
  - drivers/rtc/interface.c:perf_trace_rtc_time_alarm_class
```
```
In drivers/i2c/i2c-core-base.c (c0b9028c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (c0b945ac)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (c0bb202c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (c0bb52f0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (c0bbac40)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (c0c08dac)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (c0c5f378)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_cmd_class
```
```
In drivers/devfreq/devfreq.c (c0c69700)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
```
```
In drivers/ras/ras.c (c0c7fa30)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_non_standard_event
  - drivers/ras/ras.c:perf_trace_arm_event
  - drivers/ras/ras.c:perf_trace_mc_event
```
```
In sound/soc/soc-core.c (c0ca4a0c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - sound/soc/soc-core.c:perf_trace_snd_soc_jack_notify
  - sound/soc/soc-core.c:perf_trace_snd_soc_jack_report
  - sound/soc/soc-core.c:perf_trace_snd_soc_jack_irq
  - sound/soc/soc-core.c:perf_trace_snd_soc_dapm_connected
  - sound/soc/soc-core.c:perf_trace_snd_soc_dapm_path
  - sound/soc/soc-core.c:perf_trace_snd_soc_dapm_walk_done
  - sound/soc/soc-core.c:perf_trace_snd_soc_dapm_widget
  - sound/soc/soc-core.c:perf_trace_snd_soc_dapm_basic
  - sound/soc/soc-core.c:perf_trace_snd_soc_card
```
```
In net/core/net-traces.c (c0d2f2ec)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:perf_trace_neigh_create
  - net/core/net-traces.c:perf_trace_page_pool_state_hold
  - net/core/net-traces.c:perf_trace_page_pool_state_release
  - net/core/net-traces.c:perf_trace_page_pool_inflight
  - net/core/net-traces.c:perf_trace_br_fdb_update
  - net/core/net-traces.c:perf_trace_fdb_delete
  - net/core/net-traces.c:perf_trace_br_fdb_external_learn_add
  - net/core/net-traces.c:perf_trace_br_fdb_add
  - net/core/net-traces.c:perf_trace_qdisc_dequeue
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_rcvqueue_full
  - net/core/net-traces.c:perf_trace_napi_poll
  - net/core/net-traces.c:perf_trace_net_dev_rx_exit_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_template
  - net/core/net-traces.c:perf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:perf_trace_net_dev_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:perf_trace_consume_skb
  - net/core/net-traces.c:perf_trace_kfree_skb
```
```
In net/core/devlink.c (c0d3ecc8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/core/bpf_sk_storage.c (c0d48d18)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_update
```
```
In net/bpf/test_run.c (c0d622bc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv4/inet_hashtables.c (c0d7a47c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_connection_sock.c (c0d7cf10)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/raw.c (c0da4f00)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (c0da7dbc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_first
```
```
In net/ipv4/fib_trie.c (c0dc90a0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/xfrm/xfrm_policy.c (c0de743c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (c0df19bc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
```
```
In net/unix/af_unix.c (c0df6a48)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/anycast.c (c0dfe3a8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_anycast_cleanup
```
```
In net/ipv6/addrconf.c (c0e11200)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
```
```
In net/ipv6/route.c (c0e12210)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
```
In net/ipv6/raw.c (c0e2e858)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (c0e577e8)
Location: include/linux/list.h:752
Inline: True
```
```
In net/xdp/xsk.c (c0e79548)
Location: include/linux/list.h:752
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
In init/main.c (c00000000000f544)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/powerpc/kernel/ptrace.c (c000000000011694)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/powerpc/kernel/ptrace.c:perf_trace_sys_exit
  - arch/powerpc/kernel/ptrace.c:perf_trace_sys_enter
```
```
In arch/powerpc/kernel/irq.c (c00000000001a31c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/powerpc/kernel/irq.c:perf_trace_tlbia
  - arch/powerpc/kernel/irq.c:perf_trace_tlbie
  - arch/powerpc/kernel/irq.c:perf_trace_hash_fault
  - arch/powerpc/kernel/irq.c:perf_trace_opal_exit
  - arch/powerpc/kernel/irq.c:perf_trace_opal_entry
  - arch/powerpc/kernel/irq.c:perf_trace_hcall_exit
  - arch/powerpc/kernel/irq.c:perf_trace_hcall_entry
  - arch/powerpc/kernel/irq.c:perf_trace_ppc64_interrupt_class
```
```
In arch/powerpc/mm/book3s64/hash_pgtable.c (c00000000008ac54)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_pgtable.c:perf_trace_hugepage_splitting
  - arch/powerpc/mm/book3s64/hash_pgtable.c:perf_trace_hugepage_update
  - arch/powerpc/mm/book3s64/hash_pgtable.c:perf_trace_hugepage_set_pmd
  - arch/powerpc/mm/book3s64/hash_pgtable.c:perf_trace_hugepage_invalidate
```
```
In arch/powerpc/platforms/powernv/vas-window.c (c0000000000e1a34)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/vas-window.c:perf_trace_vas_paste_crb
  - arch/powerpc/platforms/powernv/vas-window.c:perf_trace_vas_tx_win_open
  - arch/powerpc/platforms/powernv/vas-window.c:perf_trace_vas_rx_win_open
```
```
In arch/powerpc/kvm/book3s_hv_rm_xics.c (c000000000123bd8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_xics.c:xics_rm_h_eoi
```
```
In kernel/fork.c (c000000000136994)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (c00000000013fc50)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/exit.c (c000000000142fcc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/softirq.c (c0000000001455bc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (c00000000015189c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (c0000000001644dc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/pid.c (c00000000016e270)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/sched/core.c (c00000000017b01c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_wake_idle_without_ipi
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:perf_trace_sched_process_hang
  - kernel/sched/core.c:perf_trace_sched_pi_setprio
  - kernel/sched/core.c:perf_trace_sched_stat_runtime
  - kernel/sched/core.c:perf_trace_sched_process_exec
  - kernel/sched/core.c:perf_trace_sched_process_fork
  - kernel/sched/core.c:perf_trace_sched_process_wait
  - kernel/sched/core.c:perf_trace_sched_process_template
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:perf_trace_sched_kthread_stop_ret
  - kernel/sched/core.c:perf_trace_sched_kthread_stop
```
```
In kernel/printk/printk.c (c0000000001caacc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/rcu/update.c (c0000000001e26fc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (c0000000001f65d8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/time/timer.c (c0000000002012d8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:perf_trace_tick_stop
  - kernel/time/timer.c:perf_trace_itimer_expire
  - kernel/time/timer.c:perf_trace_itimer_state
  - kernel/time/timer.c:perf_trace_hrtimer_class
  - kernel/time/timer.c:perf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:perf_trace_hrtimer_start
  - kernel/time/timer.c:perf_trace_hrtimer_init
  - kernel/time/timer.c:perf_trace_timer_expire_entry
  - kernel/time/timer.c:perf_trace_timer_start
  - kernel/time/timer.c:perf_trace_timer_class
```
```
In kernel/time/alarmtimer.c (c00000000020baf4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (c00000000022840c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (c00000000023a51c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/kprobes.c (c00000000026cd1c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/trace/ftrace.c (c00000000028dbe8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:t_probe_next
  - kernel/trace/ftrace.c:profile_graph_return
```
```
In kernel/trace/trace_syscalls.c (c0000000002cc740)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (c0000000002ec028)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/power-traces.c (c0000000002f26ac)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:perf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:perf_trace_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_power_domain
  - kernel/trace/power-traces.c:perf_trace_clock
  - kernel/trace/power-traces.c:perf_trace_wakeup_source
  - kernel/trace/power-traces.c:perf_trace_suspend_resume
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:perf_trace_cpu_frequency_limits
  - kernel/trace/power-traces.c:perf_trace_pstate_sample
  - kernel/trace/power-traces.c:perf_trace_powernv_throttle
  - kernel/trace/power-traces.c:perf_trace_cpu
```
```
In kernel/trace/rpm-traces.c (c0000000002f47e0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (c0000000002fb1fc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/core.c (c0000000003006c4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_mem_return_failed
  - kernel/bpf/core.c:perf_trace_mem_connect
  - kernel/bpf/core.c:perf_trace_mem_disconnect
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_bulk_tx
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/events/core.c (c0000000003526c8)
Location: include/linux/list.h:752
Inline: True
```
```
In kernel/rseq.c (c000000000360054)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (c000000000361ba4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (c00000000036d474)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:perf_trace_skip_task_reaping
  - mm/oom_kill.c:perf_trace_finish_task_reaping
  - mm/oom_kill.c:perf_trace_start_task_reaping
  - mm/oom_kill.c:perf_trace_wake_reaper
  - mm/oom_kill.c:perf_trace_mark_victim
  - mm/oom_kill.c:perf_trace_reclaim_retry_zone
  - mm/oom_kill.c:perf_trace_oom_score_adj_update
```
```
In mm/swap.c (c000000000378e6c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (c000000000380dbc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/vmscan.c:perf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:perf_trace_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_isolate
  - mm/vmscan.c:perf_trace_mm_shrink_slab_end
  - mm/vmscan.c:perf_trace_mm_shrink_slab_start
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_end_template
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:perf_trace_mm_vmscan_wakeup_kswapd
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_wake
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_sleep
```
```
In mm/percpu.c (c0000000003a0a2c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (c0000000003a5e5c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:perf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:perf_trace_mm_page
  - mm/slab_common.c:perf_trace_mm_page_alloc
  - mm/slab_common.c:perf_trace_mm_page_free_batched
  - mm/slab_common.c:perf_trace_mm_page_free
  - mm/slab_common.c:perf_trace_kmem_free
  - mm/slab_common.c:perf_trace_kmem_alloc_node
  - mm/slab_common.c:perf_trace_kmem_alloc
```
```
In mm/compaction.c (c0000000003aad0c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/compaction.c:perf_trace_kcompactd_wake_template
  - mm/compaction.c:perf_trace_mm_compaction_kcompactd_sleep
  - mm/compaction.c:perf_trace_mm_compaction_defer_template
  - mm/compaction.c:perf_trace_mm_compaction_suitable_template
  - mm/compaction.c:perf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:perf_trace_mm_compaction_end
  - mm/compaction.c:perf_trace_mm_compaction_begin
  - mm/compaction.c:perf_trace_mm_compaction_migratepages
  - mm/compaction.c:perf_trace_mm_compaction_isolate_template
```
```
In mm/mmu_notifier.c (c000000000419258)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_mm_destroy
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (c00000000041e8fc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
```
```
In mm/migrate.c (c000000000430ea4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (c000000000444b84)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (c000000000462afc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (c000000000468c9c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (c0000000004734fc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/super.c (c00000000047f880)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/super.c:reconfigure_super
```
```
In fs/dcache.c (c0000000004a3580)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_find_any_alias
```
```
In fs/namespace.c (c0000000004b5dd0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:namespace_unlock
```
```
In fs/seq_file.c (c0000000004b9dc4)
Location: include/linux/list.h:752
Inline: True
```
```
In fs/fs-writeback.c (c0000000004c27ac)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_writeback_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_congest_waited_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_pages_written
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
```
```
In fs/notify/mark.c (c0000000004f0b2c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/dax.c (c0000000005117dc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/dax.c:perf_trace_dax_writeback_one
  - fs/dax.c:perf_trace_dax_writeback_range_class
  - fs/dax.c:perf_trace_dax_insert_mapping
  - fs/dax.c:perf_trace_dax_pte_fault_class
  - fs/dax.c:perf_trace_dax_pmd_insert_mapping_class
  - fs/dax.c:perf_trace_dax_pmd_load_hole_class
  - fs/dax.c:perf_trace_dax_pmd_fault_class
```
```
In fs/locks.c (c000000000522bdc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (c0000000005deb4c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_error
  - fs/ext4/super.c:perf_trace_ext4_shutdown
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:perf_trace_ext4_insert_range
  - fs/ext4/super.c:perf_trace_ext4_collapse_range
  - fs/ext4/super.c:perf_trace_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:perf_trace_ext4__es_shrink_enter
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_enter
  - fs/ext4/super.c:perf_trace_ext4_es_remove_extent
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_idx
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_show_extent
  - fs/ext4/super.c:perf_trace_ext4_get_reserved_cluster_alloc
  - fs/ext4/super.c:perf_trace_ext4_find_delalloc_range
  - fs/ext4/super.c:perf_trace_ext4_ext_in_cache
  - fs/ext4/super.c:perf_trace_ext4_ext_put_in_cache
  - fs/ext4/super.c:perf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:perf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:perf_trace_ext4__trim
  - fs/ext4/super.c:perf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:perf_trace_ext4_journal_start
  - fs/ext4/super.c:perf_trace_ext4_load_inode
  - fs/ext4/super.c:perf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_exit
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_enter
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:perf_trace_ext4__truncate
  - fs/ext4/super.c:perf_trace_ext4_unlink_exit
  - fs/ext4/super.c:perf_trace_ext4_unlink_enter
  - fs/ext4/super.c:perf_trace_ext4_fallocate_exit
  - fs/ext4/super.c:perf_trace_ext4__fallocate_mode
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_exit
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_enter
  - fs/ext4/super.c:perf_trace_ext4__bitmap_load
  - fs/ext4/super.c:perf_trace_ext4_da_release_space
  - fs/ext4/super.c:perf_trace_ext4_da_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_da_update_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_forget
  - fs/ext4/super.c:perf_trace_ext4__mballoc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_prealloc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_alloc
  - fs/ext4/super.c:perf_trace_ext4_alloc_da_blocks
  - fs/ext4/super.c:perf_trace_ext4_sync_fs
  - fs/ext4/super.c:perf_trace_ext4_sync_file_exit
  - fs/ext4/super.c:perf_trace_ext4_sync_file_enter
  - fs/ext4/super.c:perf_trace_ext4_free_blocks
  - fs/ext4/super.c:perf_trace_ext4_allocate_blocks
  - fs/ext4/super.c:perf_trace_ext4_request_blocks
  - fs/ext4/super.c:perf_trace_ext4_mb_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_mb_release_group_pa
  - fs/ext4/super.c:perf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:perf_trace_ext4__mb_new_pa
  - fs/ext4/super.c:perf_trace_ext4_discard_blocks
  - fs/ext4/super.c:perf_trace_ext4_invalidatepage_op
  - fs/ext4/super.c:perf_trace_ext4__page_op
  - fs/ext4/super.c:perf_trace_ext4_writepages_result
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages_extent
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages
  - fs/ext4/super.c:perf_trace_ext4_writepages
  - fs/ext4/super.c:perf_trace_ext4__write_end
  - fs/ext4/super.c:perf_trace_ext4__write_begin
  - fs/ext4/super.c:perf_trace_ext4_begin_ordered_truncate
  - fs/ext4/super.c:perf_trace_ext4_mark_inode_dirty
  - fs/ext4/super.c:perf_trace_ext4_nfs_commit_metadata
  - fs/ext4/super.c:perf_trace_ext4_drop_inode
  - fs/ext4/super.c:perf_trace_ext4_evict_inode
  - fs/ext4/super.c:perf_trace_ext4_allocate_inode
  - fs/ext4/super.c:perf_trace_ext4_request_inode
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
```
```
In fs/jbd2/journal.c (c00000000060d9c4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/jbd2/journal.c:perf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:perf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:perf_trace_jbd2_update_log_tail
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_run_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_extend
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_start
  - fs/jbd2/journal.c:perf_trace_jbd2_submit_inode_data
  - fs/jbd2/journal.c:perf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint
```
```
In security/selinux/avc.c (c00000000069e55c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_get_hash_stats
```
```
In block/blk-core.c (c000000000772d5c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_unplug
  - block/blk-core.c:perf_trace_block_plug
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_buffer
```
```
In block/blk-ioc.c (c00000000077d26c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (c0000000007ab7c8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In block/blk-iocost.c (c0000000007b45b0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_activate
```
```
In block/blk-wbt.c (c0000000007c0404)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In drivers/gpio/gpiolib.c (c00000000083949c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/regulator/core.c (c0000000008ddce4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (c000000000944a2c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/char/random.c:perf_trace_urandom_read
  - drivers/char/random.c:perf_trace_random_read
  - drivers/char/random.c:perf_trace_random__extract_entropy
  - drivers/char/random.c:perf_trace_random__get_random_bytes
  - drivers/char/random.c:perf_trace_xfer_secondary_pool
  - drivers/char/random.c:perf_trace_add_disk_randomness
  - drivers/char/random.c:perf_trace_add_input_randomness
  - drivers/char/random.c:perf_trace_debit_entropy
  - drivers/char/random.c:perf_trace_push_to_pool
  - drivers/char/random.c:perf_trace_credit_entropy_bits
  - drivers/char/random.c:perf_trace_random__mix_pool_bytes
  - drivers/char/random.c:perf_trace_add_device_randomness
```
```
In drivers/iommu/iommu-traces.c (c00000000096fc88)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (c0000000009b50cc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
```
```
In drivers/dma-buf/dma-fence.c (c000000000a1f240)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (c000000000a244e4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (c000000000a25c6c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (c000000000a588ac)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (c000000000a87088)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (c000000000a9831c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/vfio/pci/vfio_pci_nvlink2.c (c000000000abd76c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_nvlink2.c:perf_trace_vfio_pci_npu2_mmap
  - drivers/vfio/pci/vfio_pci_nvlink2.c:perf_trace_vfio_pci_nvgpu_mmap
  - drivers/vfio/pci/vfio_pci_nvlink2.c:perf_trace_vfio_pci_nvgpu_mmap_fault
```
```
In drivers/usb/host/xhci-trace.c (c000000000b625bc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_dbc_log_request
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_slot_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ep_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_free_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_trb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
```
```
In drivers/rtc/interface.c (c000000000b88bcc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/rtc/interface.c:perf_trace_rtc_timer_class
  - drivers/rtc/interface.c:perf_trace_rtc_offset_class
  - drivers/rtc/interface.c:perf_trace_rtc_alarm_irq_enable
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_state
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_freq
  - drivers/rtc/interface.c:perf_trace_rtc_time_alarm_class
```
```
In drivers/i2c/i2c-core-base.c (c000000000b90b8c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (c000000000b96aa0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (c000000000bb5cc0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (c000000000bb9384)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (c000000000bc2590)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (c000000000c26a78)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/devfreq/devfreq.c (c000000000c65110)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
```
```
In drivers/ras/ras.c (c000000000c6f9cc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_memory_failure_event
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_non_standard_event
  - drivers/ras/ras.c:perf_trace_arm_event
  - drivers/ras/ras.c:perf_trace_mc_event
```
```
In net/core/net-traces.c (c000000000d06218)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:perf_trace_neigh_create
  - net/core/net-traces.c:perf_trace_page_pool_state_hold
  - net/core/net-traces.c:perf_trace_page_pool_state_release
  - net/core/net-traces.c:perf_trace_page_pool_inflight
  - net/core/net-traces.c:perf_trace_br_fdb_update
  - net/core/net-traces.c:perf_trace_fdb_delete
  - net/core/net-traces.c:perf_trace_br_fdb_external_learn_add
  - net/core/net-traces.c:perf_trace_br_fdb_add
  - net/core/net-traces.c:perf_trace_qdisc_dequeue
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_rcvqueue_full
  - net/core/net-traces.c:perf_trace_napi_poll
  - net/core/net-traces.c:perf_trace_net_dev_rx_exit_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_template
  - net/core/net-traces.c:perf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:perf_trace_net_dev_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:perf_trace_consume_skb
  - net/core/net-traces.c:perf_trace_kfree_skb
```
```
In net/core/devlink.c (c000000000d1c2d8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/core/bpf_sk_storage.c (c000000000d2b5bc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_update
```
```
In net/bpf/test_run.c (c000000000d51ddc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv4/inet_hashtables.c (c000000000d70b7c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_connection_sock.c (c000000000d73ef4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/raw.c (c000000000da8318)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (c000000000dab940)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_first
```
```
In net/ipv4/fib_trie.c (c000000000dd78e4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/xfrm/xfrm_policy.c (c000000000dfda20)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_bydst_resize
```
```
In net/xfrm/xfrm_state.c (c000000000e0d170)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
```
```
In net/unix/af_unix.c (c000000000e14bdc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/anycast.c (c000000000e1e8f0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_anycast_cleanup
```
```
In net/ipv6/addrconf.c (c000000000e35890)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
```
```
In net/ipv6/route.c (c000000000e36f74)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
```
In net/ipv6/raw.c (c000000000e5ba9c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (c000000000e90698)
Location: include/linux/list.h:752
Inline: True
```
```
In net/xdp/xsk.c (c000000000ebe9b8)
Location: include/linux/list.h:752
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
In init/main.c (ffffffe0000b3ede)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/riscv/kernel/ptrace.c (ffffffe0000b5be8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/riscv/kernel/ptrace.c:perf_trace_sys_exit
  - arch/riscv/kernel/ptrace.c:perf_trace_sys_enter
```
```
In kernel/fork.c (ffffffe0000be53e)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffe0000c3c06)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/exit.c (ffffffe0000c550a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/softirq.c (ffffffe0000c694e)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffe0000cd22e)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffe0000d6430)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/pid.c (ffffffe0000dc626)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/sched/core.c (ffffffe0000e4da2)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_wake_idle_without_ipi
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:perf_trace_sched_process_hang
  - kernel/sched/core.c:perf_trace_sched_pi_setprio
  - kernel/sched/core.c:perf_trace_sched_stat_runtime
  - kernel/sched/core.c:perf_trace_sched_process_exec
  - kernel/sched/core.c:perf_trace_sched_process_fork
  - kernel/sched/core.c:perf_trace_sched_process_wait
  - kernel/sched/core.c:perf_trace_sched_process_template
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:perf_trace_sched_kthread_stop_ret
  - kernel/sched/core.c:perf_trace_sched_kthread_stop
```
```
In kernel/printk/printk.c (ffffffe00010e118)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/rcu/update.c (ffffffe00011dcae)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffe000127e26)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/time/timer.c (ffffffe00012c5ee)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:perf_trace_tick_stop
  - kernel/time/timer.c:perf_trace_itimer_expire
  - kernel/time/timer.c:perf_trace_itimer_state
  - kernel/time/timer.c:perf_trace_hrtimer_class
  - kernel/time/timer.c:perf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:perf_trace_hrtimer_start
  - kernel/time/timer.c:perf_trace_hrtimer_init
  - kernel/time/timer.c:perf_trace_timer_expire_entry
  - kernel/time/timer.c:perf_trace_timer_start
  - kernel/time/timer.c:perf_trace_timer_class
```
```
In kernel/time/alarmtimer.c (ffffffe00013458e)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffe000141496)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffe000148990)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/ftrace.c (ffffffe00016fe78)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:t_probe_next
  - kernel/trace/ftrace.c:profile_graph_return
```
```
In kernel/trace/trace_syscalls.c (ffffffe00019325e)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/power-traces.c (ffffffe000198724)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:perf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:perf_trace_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_power_domain
  - kernel/trace/power-traces.c:perf_trace_clock
  - kernel/trace/power-traces.c:perf_trace_wakeup_source
  - kernel/trace/power-traces.c:perf_trace_suspend_resume
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:perf_trace_cpu_frequency_limits
  - kernel/trace/power-traces.c:perf_trace_pstate_sample
  - kernel/trace/power-traces.c:perf_trace_powernv_throttle
  - kernel/trace/power-traces.c:perf_trace_cpu
```
```
In kernel/trace/rpm-traces.c (ffffffe000199d90)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/bpf/core.c (ffffffe00019add0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_mem_return_failed
  - kernel/bpf/core.c:perf_trace_mem_connect
  - kernel/bpf/core.c:perf_trace_mem_disconnect
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_bulk_tx
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/events/core.c (ffffffe0001c6248)
Location: include/linux/list.h:752
Inline: True
```
```
In mm/filemap.c (ffffffe0001d3fde)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffe0001da992)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:perf_trace_skip_task_reaping
  - mm/oom_kill.c:perf_trace_finish_task_reaping
  - mm/oom_kill.c:perf_trace_start_task_reaping
  - mm/oom_kill.c:perf_trace_wake_reaper
  - mm/oom_kill.c:perf_trace_mark_victim
  - mm/oom_kill.c:perf_trace_reclaim_retry_zone
  - mm/oom_kill.c:perf_trace_oom_score_adj_update
```
```
In mm/swap.c (ffffffe0001e1cc2)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffe0001e5f6c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/vmscan.c:perf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:perf_trace_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_isolate
  - mm/vmscan.c:perf_trace_mm_shrink_slab_end
  - mm/vmscan.c:perf_trace_mm_shrink_slab_start
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_end_template
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:perf_trace_mm_vmscan_wakeup_kswapd
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_wake
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_sleep
```
```
In mm/percpu.c (ffffffe0001f8336)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffe0001fb468)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:perf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:perf_trace_mm_page
  - mm/slab_common.c:perf_trace_mm_page_alloc
  - mm/slab_common.c:perf_trace_mm_page_free_batched
  - mm/slab_common.c:perf_trace_mm_page_free
  - mm/slab_common.c:perf_trace_kmem_free
  - mm/slab_common.c:perf_trace_kmem_alloc_node
  - mm/slab_common.c:perf_trace_kmem_alloc
```
```
In mm/compaction.c (ffffffe0001fdfb6)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/compaction.c:perf_trace_kcompactd_wake_template
  - mm/compaction.c:perf_trace_mm_compaction_kcompactd_sleep
  - mm/compaction.c:perf_trace_mm_compaction_defer_template
  - mm/compaction.c:perf_trace_mm_compaction_suitable_template
  - mm/compaction.c:perf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:perf_trace_mm_compaction_end
  - mm/compaction.c:perf_trace_mm_compaction_begin
  - mm/compaction.c:perf_trace_mm_compaction_migratepages
  - mm/compaction.c:perf_trace_mm_compaction_isolate_template
```
```
In mm/mmu_notifier.c (ffffffe000232fc8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_mm_destroy
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (ffffffe0002351fe)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
```
```
In mm/migrate.c (ffffffe00023dfd8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/page_isolation.c (ffffffe00024abc6)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffffffe00024ec9e)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffffffe000252d2c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/super.c (ffffffe00025b000)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/super.c:reconfigure_super
```
```
In fs/dcache.c (ffffffe00026edcc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_find_any_alias
```
```
In fs/namespace.c (ffffffe00027b0a4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:namespace_unlock
```
```
In fs/seq_file.c (ffffffe00027de04)
Location: include/linux/list.h:752
Inline: True
```
```
In fs/fs-writeback.c (ffffffe000282bec)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_writeback_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_congest_waited_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_pages_written
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
```
```
In fs/notify/mark.c (ffffffe00029e25e)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/dax.c (ffffffe0002b198e)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/dax.c:perf_trace_dax_writeback_one
  - fs/dax.c:perf_trace_dax_writeback_range_class
  - fs/dax.c:perf_trace_dax_insert_mapping
  - fs/dax.c:perf_trace_dax_pte_fault_class
  - fs/dax.c:perf_trace_dax_pmd_insert_mapping_class
  - fs/dax.c:perf_trace_dax_pmd_load_hole_class
  - fs/dax.c:perf_trace_dax_pmd_fault_class
```
```
In fs/locks.c (ffffffe0002bbc8e)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffe00032ca3e)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_error
  - fs/ext4/super.c:perf_trace_ext4_shutdown
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:perf_trace_ext4_insert_range
  - fs/ext4/super.c:perf_trace_ext4_collapse_range
  - fs/ext4/super.c:perf_trace_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:perf_trace_ext4__es_shrink_enter
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_enter
  - fs/ext4/super.c:perf_trace_ext4_es_remove_extent
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_idx
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_show_extent
  - fs/ext4/super.c:perf_trace_ext4_get_reserved_cluster_alloc
  - fs/ext4/super.c:perf_trace_ext4_find_delalloc_range
  - fs/ext4/super.c:perf_trace_ext4_ext_in_cache
  - fs/ext4/super.c:perf_trace_ext4_ext_put_in_cache
  - fs/ext4/super.c:perf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:perf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:perf_trace_ext4__trim
  - fs/ext4/super.c:perf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:perf_trace_ext4_journal_start
  - fs/ext4/super.c:perf_trace_ext4_load_inode
  - fs/ext4/super.c:perf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_exit
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_enter
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:perf_trace_ext4__truncate
  - fs/ext4/super.c:perf_trace_ext4_unlink_exit
  - fs/ext4/super.c:perf_trace_ext4_unlink_enter
  - fs/ext4/super.c:perf_trace_ext4_fallocate_exit
  - fs/ext4/super.c:perf_trace_ext4__fallocate_mode
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_exit
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_enter
  - fs/ext4/super.c:perf_trace_ext4__bitmap_load
  - fs/ext4/super.c:perf_trace_ext4_da_release_space
  - fs/ext4/super.c:perf_trace_ext4_da_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_da_update_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_forget
  - fs/ext4/super.c:perf_trace_ext4__mballoc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_prealloc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_alloc
  - fs/ext4/super.c:perf_trace_ext4_alloc_da_blocks
  - fs/ext4/super.c:perf_trace_ext4_sync_fs
  - fs/ext4/super.c:perf_trace_ext4_sync_file_exit
  - fs/ext4/super.c:perf_trace_ext4_sync_file_enter
  - fs/ext4/super.c:perf_trace_ext4_free_blocks
  - fs/ext4/super.c:perf_trace_ext4_allocate_blocks
  - fs/ext4/super.c:perf_trace_ext4_request_blocks
  - fs/ext4/super.c:perf_trace_ext4_mb_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_mb_release_group_pa
  - fs/ext4/super.c:perf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:perf_trace_ext4__mb_new_pa
  - fs/ext4/super.c:perf_trace_ext4_discard_blocks
  - fs/ext4/super.c:perf_trace_ext4_invalidatepage_op
  - fs/ext4/super.c:perf_trace_ext4__page_op
  - fs/ext4/super.c:perf_trace_ext4_writepages_result
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages_extent
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages
  - fs/ext4/super.c:perf_trace_ext4_writepages
  - fs/ext4/super.c:perf_trace_ext4__write_end
  - fs/ext4/super.c:perf_trace_ext4__write_begin
  - fs/ext4/super.c:perf_trace_ext4_begin_ordered_truncate
  - fs/ext4/super.c:perf_trace_ext4_mark_inode_dirty
  - fs/ext4/super.c:perf_trace_ext4_nfs_commit_metadata
  - fs/ext4/super.c:perf_trace_ext4_drop_inode
  - fs/ext4/super.c:perf_trace_ext4_evict_inode
  - fs/ext4/super.c:perf_trace_ext4_allocate_inode
  - fs/ext4/super.c:perf_trace_ext4_request_inode
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
```
```
In fs/jbd2/journal.c (ffffffe00034a548)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/jbd2/journal.c:perf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:perf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:perf_trace_jbd2_update_log_tail
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_run_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_extend
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_start
  - fs/jbd2/journal.c:perf_trace_jbd2_submit_inode_data
  - fs/jbd2/journal.c:perf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint
```
```
In security/selinux/avc.c (ffffffe0003a2d2e)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_get_hash_stats
```
```
In block/blk-core.c (ffffffe000422d14)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_unplug
  - block/blk-core.c:perf_trace_block_plug
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_buffer
```
```
In block/blk-ioc.c (ffffffe00042928a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffe0004468d0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In block/blk-iocost.c (ffffffe00044be70)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_activate
```
```
In block/blk-wbt.c (ffffffe000452e90)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In drivers/gpio/gpiolib.c (ffffffe0004a4346)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (ffffffe00050f462)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffe000521736)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffe000561004)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/char/random.c:perf_trace_urandom_read
  - drivers/char/random.c:perf_trace_random_read
  - drivers/char/random.c:perf_trace_random__extract_entropy
  - drivers/char/random.c:perf_trace_random__get_random_bytes
  - drivers/char/random.c:perf_trace_xfer_secondary_pool
  - drivers/char/random.c:perf_trace_add_disk_randomness
  - drivers/char/random.c:perf_trace_add_input_randomness
  - drivers/char/random.c:perf_trace_debit_entropy
  - drivers/char/random.c:perf_trace_push_to_pool
  - drivers/char/random.c:perf_trace_credit_entropy_bits
  - drivers/char/random.c:perf_trace_random__mix_pool_bytes
  - drivers/char/random.c:perf_trace_add_device_randomness
```
```
In drivers/base/regmap/regmap.c (ffffffe000595248)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
```
```
In drivers/dma-buf/dma-fence.c (ffffffe0005d37b8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffe0005d61dc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffe0005d7ca2)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffe0005f792a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffe000617392)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffe000622c22)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffe00069d1e6)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_dbc_log_request
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_slot_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ep_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_free_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_trb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
```
```
In drivers/rtc/interface.c (ffffffe0006b3468)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/rtc/interface.c:perf_trace_rtc_timer_class
  - drivers/rtc/interface.c:perf_trace_rtc_offset_class
  - drivers/rtc/interface.c:perf_trace_rtc_alarm_irq_enable
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_state
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_freq
  - drivers/rtc/interface.c:perf_trace_rtc_time_alarm_class
```
```
In drivers/i2c/i2c-core-base.c (ffffffe0006b700c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffe0006bad78)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffe0006cdc60)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffe0006ceaac)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (ffffffe0006d4f5c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffe0007065ae)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/devfreq/devfreq.c (ffffffe00072f7d2)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
```
```
In drivers/ras/ras.c (ffffffe000735adc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_non_standard_event
  - drivers/ras/ras.c:perf_trace_arm_event
  - drivers/ras/ras.c:perf_trace_mc_event
```
```
In net/core/net-traces.c (ffffffe000791df8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:perf_trace_neigh_create
  - net/core/net-traces.c:perf_trace_page_pool_state_hold
  - net/core/net-traces.c:perf_trace_page_pool_state_release
  - net/core/net-traces.c:perf_trace_page_pool_inflight
  - net/core/net-traces.c:perf_trace_br_fdb_update
  - net/core/net-traces.c:perf_trace_fdb_delete
  - net/core/net-traces.c:perf_trace_br_fdb_external_learn_add
  - net/core/net-traces.c:perf_trace_br_fdb_add
  - net/core/net-traces.c:perf_trace_qdisc_dequeue
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_rcvqueue_full
  - net/core/net-traces.c:perf_trace_napi_poll
  - net/core/net-traces.c:perf_trace_net_dev_rx_exit_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_template
  - net/core/net-traces.c:perf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:perf_trace_net_dev_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:perf_trace_consume_skb
  - net/core/net-traces.c:perf_trace_kfree_skb
```
```
In net/core/devlink.c (ffffffe00079e2fe)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/core/bpf_sk_storage.c (ffffffe0007a7c48)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_update
```
```
In net/bpf/test_run.c (ffffffe0007bd65a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007d0ff6)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d2a02)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/raw.c (ffffffe0007f5a92)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffe0007f748e)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_first
```
```
In net/ipv4/fib_trie.c (ffffffe0008139da)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082af24)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffe00083769a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
```
```
In net/unix/af_unix.c (ffffffe00083c116)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/anycast.c (ffffffe000843054)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_anycast_cleanup
```
```
In net/ipv6/addrconf.c (ffffffe000852532)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
```
```
In net/ipv6/route.c (ffffffe0008533ba)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
```
In net/ipv6/raw.c (ffffffe00086afb0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffe00088e906)
Location: include/linux/list.h:752
Inline: True
```
```
In net/xdp/xsk.c (ffffffe0008ac4ba)
Location: include/linux/list.h:752
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
In init/main.c (ffffffff8100220f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/common.c (ffffffff810038cf)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004f3a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff8102a43f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_set_ldt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_gdt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_load_idt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_one_user
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_alloc_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pte_at
  - arch/x86/xen/trace.c:perf_trace_xen_mmu__set_pte
  - arch/x86/xen/trace.c:perf_trace_xen_mc_extend_args
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush_reason
  - arch/x86/xen/trace.c:perf_trace_xen_mc_callback
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry_alloc
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mc__batch
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102e271)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/irq.c (ffffffff810334c8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:perf_trace_vector_free_moved
  - arch/x86/kernel/irq.c:perf_trace_vector_setup
  - arch/x86/kernel/irq.c:perf_trace_vector_teardown
  - arch/x86/kernel/irq.c:perf_trace_vector_activate
  - arch/x86/kernel/irq.c:perf_trace_vector_alloc_managed
  - arch/x86/kernel/irq.c:perf_trace_vector_alloc
  - arch/x86/kernel/irq.c:perf_trace_vector_reserve
  - arch/x86/kernel/irq.c:perf_trace_vector_mod
  - arch/x86/kernel/irq.c:perf_trace_vector_config
  - arch/x86/kernel/irq.c:perf_trace_x86_irq_vector
```
```
In arch/x86/kernel/nmi.c (ffffffff81035f44)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103e35a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c8ba)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105f50f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/init.c (ffffffff8107ca0f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff8107e764)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff8108c34a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:perf_trace_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:perf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:perf_trace_bounds_exception_mpx
  - arch/x86/mm/mpx.c:perf_trace_mpx_bounds_register_exception
```
```
In kernel/fork.c (ffffffff81096300)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff8109d0cf)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/exit.c (ffffffff8109f29d)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/softirq.c (ffffffff810a0d6a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810a9944)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810b97ea)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/pid.c (ffffffff810c02c3)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/sched/core.c (ffffffff810cb2aa)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_wake_idle_without_ipi
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:perf_trace_sched_process_hang
  - kernel/sched/core.c:perf_trace_sched_pi_setprio
  - kernel/sched/core.c:perf_trace_sched_stat_runtime
  - kernel/sched/core.c:perf_trace_sched_process_exec
  - kernel/sched/core.c:perf_trace_sched_process_fork
  - kernel/sched/core.c:perf_trace_sched_process_wait
  - kernel/sched/core.c:perf_trace_sched_process_template
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:perf_trace_sched_kthread_stop_ret
  - kernel/sched/core.c:perf_trace_sched_kthread_stop
```
```
In kernel/printk/printk.c (ffffffff81109f04)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff8111aae3)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff8111bb6a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff811283f8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/time/timer.c (ffffffff8112f7b8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:perf_trace_tick_stop
  - kernel/time/timer.c:perf_trace_itimer_expire
  - kernel/time/timer.c:perf_trace_itimer_state
  - kernel/time/timer.c:perf_trace_hrtimer_class
  - kernel/time/timer.c:perf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:perf_trace_hrtimer_start
  - kernel/time/timer.c:perf_trace_hrtimer_init
  - kernel/time/timer.c:perf_trace_timer_expire_entry
  - kernel/time/timer.c:perf_trace_timer_start
  - kernel/time/timer.c:perf_trace_timer_class
```
```
In kernel/time/alarmtimer.c (ffffffff8113746f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff8114af15)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff81157b11)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/kprobes.c (ffffffff81179ced)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/trace/ftrace.c (ffffffff81190ce4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:profile_graph_return
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b64b6)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c9cdf)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/power-traces.c (ffffffff811cba14)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:perf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:perf_trace_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_power_domain
  - kernel/trace/power-traces.c:perf_trace_clock
  - kernel/trace/power-traces.c:perf_trace_wakeup_source
  - kernel/trace/power-traces.c:perf_trace_suspend_resume
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:perf_trace_cpu_frequency_limits
  - kernel/trace/power-traces.c:perf_trace_pstate_sample
  - kernel/trace/power-traces.c:perf_trace_powernv_throttle
  - kernel/trace/power-traces.c:perf_trace_cpu
```
```
In kernel/trace/rpm-traces.c (ffffffff811cd1b3)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d0d36)
Location: include/linux/list.h:752
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811d405f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_mem_return_failed
  - kernel/bpf/core.c:perf_trace_mem_connect
  - kernel/bpf/core.c:perf_trace_mem_disconnect
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_bulk_tx
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/events/core.c (ffffffff81203de5)
Location: include/linux/list.h:752
Inline: True
```
```
In kernel/user-return-notifier.c (ffffffff81215512)
Location: include/linux/list.h:752
Inline: True
```
```
In kernel/rseq.c (ffffffff81217db8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff81218f0f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff81220bab)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:perf_trace_skip_task_reaping
  - mm/oom_kill.c:perf_trace_finish_task_reaping
  - mm/oom_kill.c:perf_trace_start_task_reaping
  - mm/oom_kill.c:perf_trace_wake_reaper
  - mm/oom_kill.c:perf_trace_mark_victim
  - mm/oom_kill.c:perf_trace_reclaim_retry_zone
  - mm/oom_kill.c:perf_trace_oom_score_adj_update
```
```
In mm/swap.c (ffffffff81228afa)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff8122de74)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/vmscan.c:perf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:perf_trace_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_isolate
  - mm/vmscan.c:perf_trace_mm_shrink_slab_end
  - mm/vmscan.c:perf_trace_mm_shrink_slab_start
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_end_template
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:perf_trace_mm_vmscan_wakeup_kswapd
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_wake
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_sleep
```
```
In mm/percpu.c (ffffffff8124345a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff81246a8b)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:perf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:perf_trace_mm_page
  - mm/slab_common.c:perf_trace_mm_page_alloc
  - mm/slab_common.c:perf_trace_mm_page_free_batched
  - mm/slab_common.c:perf_trace_mm_page_free
  - mm/slab_common.c:perf_trace_kmem_free
  - mm/slab_common.c:perf_trace_kmem_alloc_node
  - mm/slab_common.c:perf_trace_kmem_alloc
```
```
In mm/compaction.c (ffffffff81249d14)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/compaction.c:perf_trace_kcompactd_wake_template
  - mm/compaction.c:perf_trace_mm_compaction_kcompactd_sleep
  - mm/compaction.c:perf_trace_mm_compaction_defer_template
  - mm/compaction.c:perf_trace_mm_compaction_suitable_template
  - mm/compaction.c:perf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:perf_trace_mm_compaction_end
  - mm/compaction.c:perf_trace_mm_compaction_begin
  - mm/compaction.c:perf_trace_mm_compaction_migratepages
  - mm/compaction.c:perf_trace_mm_compaction_isolate_template
```
```
In mm/mmu_notifier.c (ffffffff812969f4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_mm_destroy
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (ffffffff81299bb4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
```
```
In mm/migrate.c (ffffffff812a5328)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff812b2ac8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff812c5914)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffffffff812c9774)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffffffff812d0ede)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/super.c (ffffffff812d9c6b)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/super.c:reconfigure_super
```
```
In fs/dcache.c (ffffffff812f2497)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_find_any_alias
```
```
In fs/namespace.c (ffffffff812fdc1f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:namespace_unlock
```
```
In fs/seq_file.c (ffffffff81300e1c)
Location: include/linux/list.h:752
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8130679a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_writeback_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_congest_waited_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_pages_written
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
```
```
In fs/notify/mark.c (ffffffff813264f1)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/dax.c (ffffffff8133ebb4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/dax.c:perf_trace_dax_writeback_one
  - fs/dax.c:perf_trace_dax_writeback_range_class
  - fs/dax.c:perf_trace_dax_insert_mapping
  - fs/dax.c:perf_trace_dax_pte_fault_class
  - fs/dax.c:perf_trace_dax_pmd_insert_mapping_class
  - fs/dax.c:perf_trace_dax_pmd_load_hole_class
  - fs/dax.c:perf_trace_dax_pmd_fault_class
```
```
In fs/locks.c (ffffffff8134ab13)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffff813ce354)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_error
  - fs/ext4/super.c:perf_trace_ext4_shutdown
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:perf_trace_ext4_insert_range
  - fs/ext4/super.c:perf_trace_ext4_collapse_range
  - fs/ext4/super.c:perf_trace_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:perf_trace_ext4__es_shrink_enter
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_enter
  - fs/ext4/super.c:perf_trace_ext4_es_remove_extent
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_idx
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_show_extent
  - fs/ext4/super.c:perf_trace_ext4_get_reserved_cluster_alloc
  - fs/ext4/super.c:perf_trace_ext4_find_delalloc_range
  - fs/ext4/super.c:perf_trace_ext4_ext_in_cache
  - fs/ext4/super.c:perf_trace_ext4_ext_put_in_cache
  - fs/ext4/super.c:perf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:perf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:perf_trace_ext4__trim
  - fs/ext4/super.c:perf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:perf_trace_ext4_journal_start
  - fs/ext4/super.c:perf_trace_ext4_load_inode
  - fs/ext4/super.c:perf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_exit
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_enter
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:perf_trace_ext4__truncate
  - fs/ext4/super.c:perf_trace_ext4_unlink_exit
  - fs/ext4/super.c:perf_trace_ext4_unlink_enter
  - fs/ext4/super.c:perf_trace_ext4_fallocate_exit
  - fs/ext4/super.c:perf_trace_ext4__fallocate_mode
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_exit
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_enter
  - fs/ext4/super.c:perf_trace_ext4__bitmap_load
  - fs/ext4/super.c:perf_trace_ext4_da_release_space
  - fs/ext4/super.c:perf_trace_ext4_da_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_da_update_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_forget
  - fs/ext4/super.c:perf_trace_ext4__mballoc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_prealloc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_alloc
  - fs/ext4/super.c:perf_trace_ext4_alloc_da_blocks
  - fs/ext4/super.c:perf_trace_ext4_sync_fs
  - fs/ext4/super.c:perf_trace_ext4_sync_file_exit
  - fs/ext4/super.c:perf_trace_ext4_sync_file_enter
  - fs/ext4/super.c:perf_trace_ext4_free_blocks
  - fs/ext4/super.c:perf_trace_ext4_allocate_blocks
  - fs/ext4/super.c:perf_trace_ext4_request_blocks
  - fs/ext4/super.c:perf_trace_ext4_mb_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_mb_release_group_pa
  - fs/ext4/super.c:perf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:perf_trace_ext4__mb_new_pa
  - fs/ext4/super.c:perf_trace_ext4_discard_blocks
  - fs/ext4/super.c:perf_trace_ext4_invalidatepage_op
  - fs/ext4/super.c:perf_trace_ext4__page_op
  - fs/ext4/super.c:perf_trace_ext4_writepages_result
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages_extent
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages
  - fs/ext4/super.c:perf_trace_ext4_writepages
  - fs/ext4/super.c:perf_trace_ext4__write_end
  - fs/ext4/super.c:perf_trace_ext4__write_begin
  - fs/ext4/super.c:perf_trace_ext4_begin_ordered_truncate
  - fs/ext4/super.c:perf_trace_ext4_mark_inode_dirty
  - fs/ext4/super.c:perf_trace_ext4_nfs_commit_metadata
  - fs/ext4/super.c:perf_trace_ext4_drop_inode
  - fs/ext4/super.c:perf_trace_ext4_evict_inode
  - fs/ext4/super.c:perf_trace_ext4_allocate_inode
  - fs/ext4/super.c:perf_trace_ext4_request_inode
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
```
```
In fs/jbd2/journal.c (ffffffff813efcff)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/jbd2/journal.c:perf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:perf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:perf_trace_jbd2_update_log_tail
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_run_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_extend
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_start
  - fs/jbd2/journal.c:perf_trace_jbd2_submit_inode_data
  - fs/jbd2/journal.c:perf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint
```
```
In security/selinux/avc.c (ffffffff814533ca)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_get_hash_stats
```
```
In block/blk-core.c (ffffffff814db6e1)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_unplug
  - block/blk-core.c:perf_trace_block_plug
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_buffer
```
```
In block/blk-ioc.c (ffffffff814e2910)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff81503212)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In block/blk-iocost.c (ffffffff81509ade)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_activate
```
```
In block/blk-wbt.c (ffffffff81511558)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In arch/x86/lib/msr.c (ffffffff81555af4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff8155f5c4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (ffffffff81617094)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff8163f88e)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff816818a4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/char/random.c:perf_trace_urandom_read
  - drivers/char/random.c:perf_trace_random_read
  - drivers/char/random.c:perf_trace_random__extract_entropy
  - drivers/char/random.c:perf_trace_random__get_random_bytes
  - drivers/char/random.c:perf_trace_xfer_secondary_pool
  - drivers/char/random.c:perf_trace_add_disk_randomness
  - drivers/char/random.c:perf_trace_add_input_randomness
  - drivers/char/random.c:perf_trace_debit_entropy
  - drivers/char/random.c:perf_trace_push_to_pool
  - drivers/char/random.c:perf_trace_credit_entropy_bits
  - drivers/char/random.c:perf_trace_random__mix_pool_bytes
  - drivers/char/random.c:perf_trace_add_device_randomness
```
```
In drivers/iommu/iommu-traces.c (ffffffff816a1f8c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/iommu/intel-trace.c (ffffffff816b6914)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/iommu/intel-trace.c:perf_trace_dma_unmap
  - drivers/iommu/intel-trace.c:perf_trace_dma_map
```
```
In drivers/base/regmap/regmap.c (ffffffff816e548f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8171b4c7)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8171e0d2)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff8171f5ca)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/nvme/host/core.c (ffffffff817458b4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:perf_trace_nvme_sq
  - drivers/nvme/host/core.c:perf_trace_nvme_async_event
  - drivers/nvme/host/core.c:perf_trace_nvme_complete_rq
  - drivers/nvme/host/core.c:perf_trace_nvme_setup_cmd
```
```
In drivers/ata/libata-core.c (ffffffff817525fa)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff817779cd)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff8178238c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff8180111a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_dbc_log_request
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_slot_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ep_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_free_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_trb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
```
```
In drivers/rtc/interface.c (ffffffff81818b3a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/rtc/interface.c:perf_trace_rtc_timer_class
  - drivers/rtc/interface.c:perf_trace_rtc_offset_class
  - drivers/rtc/interface.c:perf_trace_rtc_alarm_irq_enable
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_state
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_freq
  - drivers/rtc/interface.c:perf_trace_rtc_time_alarm_class
```
```
In drivers/hwmon/hwmon.c (ffffffff8182b0ef)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff8182d0d8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (ffffffff81831cdc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff81877bb4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffffffff81892c1a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_cmd_class
```
```
In drivers/devfreq/devfreq.c (ffffffff8189afd2)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
```
```
In drivers/ras/ras.c (ffffffff818a0534)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_memory_failure_event
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_non_standard_event
  - drivers/ras/ras.c:perf_trace_arm_event
  - drivers/ras/ras.c:perf_trace_mc_event
```
```
In net/core/net-traces.c (ffffffff81911487)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:perf_trace_neigh_create
  - net/core/net-traces.c:perf_trace_page_pool_state_hold
  - net/core/net-traces.c:perf_trace_page_pool_state_release
  - net/core/net-traces.c:perf_trace_page_pool_inflight
  - net/core/net-traces.c:perf_trace_br_fdb_update
  - net/core/net-traces.c:perf_trace_fdb_delete
  - net/core/net-traces.c:perf_trace_br_fdb_external_learn_add
  - net/core/net-traces.c:perf_trace_br_fdb_add
  - net/core/net-traces.c:perf_trace_qdisc_dequeue
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_rcvqueue_full
  - net/core/net-traces.c:perf_trace_napi_poll
  - net/core/net-traces.c:perf_trace_net_dev_rx_exit_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_template
  - net/core/net-traces.c:perf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:perf_trace_net_dev_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:perf_trace_consume_skb
  - net/core/net-traces.c:perf_trace_kfree_skb
```
```
In net/core/devlink.c (ffffffff8191f840)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/core/bpf_sk_storage.c (ffffffff81929a85)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_update
```
```
In net/bpf/test_run.c (ffffffff8194371a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv4/inet_hashtables.c (ffffffff81959c26)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195b4b5)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/raw.c (ffffffff819827cc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81985d47)
Location: include/linux/list.h:752
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff819a48ac)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c06da)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff819ca710)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
```
```
In net/unix/af_unix.c (ffffffff819cf1d0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/anycast.c (ffffffff819d66fa)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_anycast_cleanup
```
```
In net/ipv6/addrconf.c (ffffffff819e75f6)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
```
```
In net/ipv6/route.c (ffffffff819e86c7)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
```
In net/ipv6/raw.c (ffffffff81a0407d)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffff81a297a0)
Location: include/linux/list.h:752
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81a4ab75)
Location: include/linux/list.h:752
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
In init/main.c (ffffffff810006ff)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/common.c (ffffffff81001daf)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8100361a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/hyperv/mmu.c (ffffffff8101dc31)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/irq.c (ffffffff81022e08)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:perf_trace_vector_free_moved
  - arch/x86/kernel/irq.c:perf_trace_vector_setup
  - arch/x86/kernel/irq.c:perf_trace_vector_teardown
  - arch/x86/kernel/irq.c:perf_trace_vector_activate
  - arch/x86/kernel/irq.c:perf_trace_vector_alloc_managed
  - arch/x86/kernel/irq.c:perf_trace_vector_alloc
  - arch/x86/kernel/irq.c:perf_trace_vector_reserve
  - arch/x86/kernel/irq.c:perf_trace_vector_mod
  - arch/x86/kernel/irq.c:perf_trace_vector_config
  - arch/x86/kernel/irq.c:perf_trace_x86_irq_vector
```
```
In arch/x86/kernel/nmi.c (ffffffff81025894)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8102db5a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103bc6a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8104f83f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/init.c (ffffffff8106c17f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff8106d854)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff8107ae7a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:perf_trace_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:perf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:perf_trace_bounds_exception_mpx
  - arch/x86/mm/mpx.c:perf_trace_mpx_bounds_register_exception
```
```
In kernel/fork.c (ffffffff81084d80)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff8108baff)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/exit.c (ffffffff8108dccd)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/softirq.c (ffffffff8108f78a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810982f4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810a812a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/pid.c (ffffffff810aead4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/sched/core.c (ffffffff810b9b7a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_wake_idle_without_ipi
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:perf_trace_sched_process_hang
  - kernel/sched/core.c:perf_trace_sched_pi_setprio
  - kernel/sched/core.c:perf_trace_sched_stat_runtime
  - kernel/sched/core.c:perf_trace_sched_process_exec
  - kernel/sched/core.c:perf_trace_sched_process_fork
  - kernel/sched/core.c:perf_trace_sched_process_wait
  - kernel/sched/core.c:perf_trace_sched_process_template
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:perf_trace_sched_kthread_stop_ret
  - kernel/sched/core.c:perf_trace_sched_kthread_stop
```
```
In kernel/printk/printk.c (ffffffff810fade4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff8110bb53)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff8110cbda)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff8111ac88)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/time/timer.c (ffffffff81122238)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:perf_trace_tick_stop
  - kernel/time/timer.c:perf_trace_itimer_expire
  - kernel/time/timer.c:perf_trace_itimer_state
  - kernel/time/timer.c:perf_trace_hrtimer_class
  - kernel/time/timer.c:perf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:perf_trace_hrtimer_start
  - kernel/time/timer.c:perf_trace_hrtimer_init
  - kernel/time/timer.c:perf_trace_timer_expire_entry
  - kernel/time/timer.c:perf_trace_timer_start
  - kernel/time/timer.c:perf_trace_timer_class
```
```
In kernel/time/alarmtimer.c (ffffffff81129ebf)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff8113e1c5)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff8114ae31)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/kprobes.c (ffffffff8116ce8d)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/trace/ftrace.c (ffffffff81182c57)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:profile_graph_return
```
```
In kernel/trace/trace_syscalls.c (ffffffff811a92b6)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811bcaaf)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/power-traces.c (ffffffff811be7e4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:perf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:perf_trace_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_power_domain
  - kernel/trace/power-traces.c:perf_trace_clock
  - kernel/trace/power-traces.c:perf_trace_wakeup_source
  - kernel/trace/power-traces.c:perf_trace_suspend_resume
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:perf_trace_cpu_frequency_limits
  - kernel/trace/power-traces.c:perf_trace_pstate_sample
  - kernel/trace/power-traces.c:perf_trace_powernv_throttle
  - kernel/trace/power-traces.c:perf_trace_cpu
```
```
In kernel/trace/rpm-traces.c (ffffffff811bff83)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c3b06)
Location: include/linux/list.h:752
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811c6e1f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_mem_return_failed
  - kernel/bpf/core.c:perf_trace_mem_connect
  - kernel/bpf/core.c:perf_trace_mem_disconnect
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_bulk_tx
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/events/core.c (ffffffff811f6b75)
Location: include/linux/list.h:752
Inline: True
```
```
In kernel/user-return-notifier.c (ffffffff81208272)
Location: include/linux/list.h:752
Inline: True
```
```
In kernel/context_tracking.c (ffffffff8120a73a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/context_tracking.c:perf_trace_context_tracking_user
```
```
In kernel/rseq.c (ffffffff8120afc8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff8120c11f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff81213d5b)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:perf_trace_skip_task_reaping
  - mm/oom_kill.c:perf_trace_finish_task_reaping
  - mm/oom_kill.c:perf_trace_start_task_reaping
  - mm/oom_kill.c:perf_trace_wake_reaper
  - mm/oom_kill.c:perf_trace_mark_victim
  - mm/oom_kill.c:perf_trace_reclaim_retry_zone
  - mm/oom_kill.c:perf_trace_oom_score_adj_update
```
```
In mm/swap.c (ffffffff8121bc3a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff81220f34)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/vmscan.c:perf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:perf_trace_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_isolate
  - mm/vmscan.c:perf_trace_mm_shrink_slab_end
  - mm/vmscan.c:perf_trace_mm_shrink_slab_start
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_end_template
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:perf_trace_mm_vmscan_wakeup_kswapd
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_wake
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_sleep
```
```
In mm/percpu.c (ffffffff8123642a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff81239a3b)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:perf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:perf_trace_mm_page
  - mm/slab_common.c:perf_trace_mm_page_alloc
  - mm/slab_common.c:perf_trace_mm_page_free_batched
  - mm/slab_common.c:perf_trace_mm_page_free
  - mm/slab_common.c:perf_trace_kmem_free
  - mm/slab_common.c:perf_trace_kmem_alloc_node
  - mm/slab_common.c:perf_trace_kmem_alloc
```
```
In mm/compaction.c (ffffffff8123ccc4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/compaction.c:perf_trace_kcompactd_wake_template
  - mm/compaction.c:perf_trace_mm_compaction_kcompactd_sleep
  - mm/compaction.c:perf_trace_mm_compaction_defer_template
  - mm/compaction.c:perf_trace_mm_compaction_suitable_template
  - mm/compaction.c:perf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:perf_trace_mm_compaction_end
  - mm/compaction.c:perf_trace_mm_compaction_begin
  - mm/compaction.c:perf_trace_mm_compaction_migratepages
  - mm/compaction.c:perf_trace_mm_compaction_isolate_template
```
```
In mm/mmu_notifier.c (ffffffff81288604)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_mm_destroy
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (ffffffff8128b774)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
```
```
In mm/migrate.c (ffffffff81296df8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff812a3e48)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff812b6954)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffffffff812ba7b4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffffffff812c1b5e)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/super.c (ffffffff812ca8eb)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/super.c:reconfigure_super
```
```
In fs/dcache.c (ffffffff812e30c7)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_find_any_alias
```
```
In fs/namespace.c (ffffffff812ee83f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:namespace_unlock
```
```
In fs/seq_file.c (ffffffff812f1a3c)
Location: include/linux/list.h:752
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812f73ba)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_writeback_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_congest_waited_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_pages_written
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
```
```
In fs/notify/mark.c (ffffffff81317091)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/dax.c (ffffffff8132f874)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/dax.c:perf_trace_dax_writeback_one
  - fs/dax.c:perf_trace_dax_writeback_range_class
  - fs/dax.c:perf_trace_dax_insert_mapping
  - fs/dax.c:perf_trace_dax_pte_fault_class
  - fs/dax.c:perf_trace_dax_pmd_insert_mapping_class
  - fs/dax.c:perf_trace_dax_pmd_load_hole_class
  - fs/dax.c:perf_trace_dax_pmd_fault_class
```
```
In fs/locks.c (ffffffff8133b7f3)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffff813bedd4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_error
  - fs/ext4/super.c:perf_trace_ext4_shutdown
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:perf_trace_ext4_insert_range
  - fs/ext4/super.c:perf_trace_ext4_collapse_range
  - fs/ext4/super.c:perf_trace_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:perf_trace_ext4__es_shrink_enter
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_enter
  - fs/ext4/super.c:perf_trace_ext4_es_remove_extent
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_idx
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_show_extent
  - fs/ext4/super.c:perf_trace_ext4_get_reserved_cluster_alloc
  - fs/ext4/super.c:perf_trace_ext4_find_delalloc_range
  - fs/ext4/super.c:perf_trace_ext4_ext_in_cache
  - fs/ext4/super.c:perf_trace_ext4_ext_put_in_cache
  - fs/ext4/super.c:perf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:perf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:perf_trace_ext4__trim
  - fs/ext4/super.c:perf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:perf_trace_ext4_journal_start
  - fs/ext4/super.c:perf_trace_ext4_load_inode
  - fs/ext4/super.c:perf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_exit
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_enter
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:perf_trace_ext4__truncate
  - fs/ext4/super.c:perf_trace_ext4_unlink_exit
  - fs/ext4/super.c:perf_trace_ext4_unlink_enter
  - fs/ext4/super.c:perf_trace_ext4_fallocate_exit
  - fs/ext4/super.c:perf_trace_ext4__fallocate_mode
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_exit
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_enter
  - fs/ext4/super.c:perf_trace_ext4__bitmap_load
  - fs/ext4/super.c:perf_trace_ext4_da_release_space
  - fs/ext4/super.c:perf_trace_ext4_da_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_da_update_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_forget
  - fs/ext4/super.c:perf_trace_ext4__mballoc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_prealloc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_alloc
  - fs/ext4/super.c:perf_trace_ext4_alloc_da_blocks
  - fs/ext4/super.c:perf_trace_ext4_sync_fs
  - fs/ext4/super.c:perf_trace_ext4_sync_file_exit
  - fs/ext4/super.c:perf_trace_ext4_sync_file_enter
  - fs/ext4/super.c:perf_trace_ext4_free_blocks
  - fs/ext4/super.c:perf_trace_ext4_allocate_blocks
  - fs/ext4/super.c:perf_trace_ext4_request_blocks
  - fs/ext4/super.c:perf_trace_ext4_mb_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_mb_release_group_pa
  - fs/ext4/super.c:perf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:perf_trace_ext4__mb_new_pa
  - fs/ext4/super.c:perf_trace_ext4_discard_blocks
  - fs/ext4/super.c:perf_trace_ext4_invalidatepage_op
  - fs/ext4/super.c:perf_trace_ext4__page_op
  - fs/ext4/super.c:perf_trace_ext4_writepages_result
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages_extent
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages
  - fs/ext4/super.c:perf_trace_ext4_writepages
  - fs/ext4/super.c:perf_trace_ext4__write_end
  - fs/ext4/super.c:perf_trace_ext4__write_begin
  - fs/ext4/super.c:perf_trace_ext4_begin_ordered_truncate
  - fs/ext4/super.c:perf_trace_ext4_mark_inode_dirty
  - fs/ext4/super.c:perf_trace_ext4_nfs_commit_metadata
  - fs/ext4/super.c:perf_trace_ext4_drop_inode
  - fs/ext4/super.c:perf_trace_ext4_evict_inode
  - fs/ext4/super.c:perf_trace_ext4_allocate_inode
  - fs/ext4/super.c:perf_trace_ext4_request_inode
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
```
```
In fs/jbd2/journal.c (ffffffff813e077f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/jbd2/journal.c:perf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:perf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:perf_trace_jbd2_update_log_tail
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_run_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_extend
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_start
  - fs/jbd2/journal.c:perf_trace_jbd2_submit_inode_data
  - fs/jbd2/journal.c:perf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint
```
```
In security/selinux/avc.c (ffffffff81443e0a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_get_hash_stats
```
```
In block/blk-core.c (ffffffff814cc091)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_unplug
  - block/blk-core.c:perf_trace_block_plug
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_buffer
```
```
In block/blk-ioc.c (ffffffff814d32a0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff814f36f2)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In block/blk-iocost.c (ffffffff814f9f8e)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_activate
```
```
In block/blk-wbt.c (ffffffff81501878)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In arch/x86/lib/msr.c (ffffffff81545cd4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff81550414)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (ffffffff8160b5c4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff8161fc6e)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff8165f724)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/char/random.c:perf_trace_urandom_read
  - drivers/char/random.c:perf_trace_random_read
  - drivers/char/random.c:perf_trace_random__extract_entropy
  - drivers/char/random.c:perf_trace_random__get_random_bytes
  - drivers/char/random.c:perf_trace_xfer_secondary_pool
  - drivers/char/random.c:perf_trace_add_disk_randomness
  - drivers/char/random.c:perf_trace_add_input_randomness
  - drivers/char/random.c:perf_trace_debit_entropy
  - drivers/char/random.c:perf_trace_push_to_pool
  - drivers/char/random.c:perf_trace_credit_entropy_bits
  - drivers/char/random.c:perf_trace_random__mix_pool_bytes
  - drivers/char/random.c:perf_trace_add_device_randomness
```
```
In drivers/iommu/iommu-traces.c (ffffffff8167f97c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/iommu/intel-trace.c (ffffffff81694554)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/iommu/intel-trace.c:perf_trace_dma_unmap
  - drivers/iommu/intel-trace.c:perf_trace_dma_map
```
```
In drivers/base/regmap/regmap.c (ffffffff816bfacf)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
```
```
In drivers/dma-buf/dma-fence.c (ffffffff816f4927)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816f7652)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff816f89fa)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/nvme/host/core.c (ffffffff81727544)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:perf_trace_nvme_sq
  - drivers/nvme/host/core.c:perf_trace_nvme_async_event
  - drivers/nvme/host/core.c:perf_trace_nvme_complete_rq
  - drivers/nvme/host/core.c:perf_trace_nvme_setup_cmd
```
```
In drivers/ata/libata-core.c (ffffffff8173249a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff8175777d)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff8176211c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/net/vxlan.c (ffffffff8176c356)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_exit_batch_net
```
```
In drivers/usb/host/xhci-trace.c (ffffffff817c62ba)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_dbc_log_request
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_slot_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ep_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_free_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_trb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
```
```
In drivers/rtc/interface.c (ffffffff817e022a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/rtc/interface.c:perf_trace_rtc_timer_class
  - drivers/rtc/interface.c:perf_trace_rtc_offset_class
  - drivers/rtc/interface.c:perf_trace_rtc_alarm_irq_enable
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_state
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_freq
  - drivers/rtc/interface.c:perf_trace_rtc_time_alarm_class
```
```
In drivers/hwmon/hwmon.c (ffffffff817f277f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff817f4768)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (ffffffff817f936c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/hv/hv_trace.c (ffffffff81854a5a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/hv/hv_trace.c:perf_trace_vmbus_channel
  - drivers/hv/hv_trace.c:perf_trace_vmbus_send_tl_connect_request
  - drivers/hv/hv_trace.c:perf_trace_vmbus_release_relid
  - drivers/hv/hv_trace.c:perf_trace_vmbus_negotiate_version
  - drivers/hv/hv_trace.c:perf_trace_vmbus_teardown_gpadl
  - drivers/hv/hv_trace.c:perf_trace_vmbus_establish_gpadl_body
  - drivers/hv/hv_trace.c:perf_trace_vmbus_establish_gpadl_header
  - drivers/hv/hv_trace.c:perf_trace_vmbus_close_internal
  - drivers/hv/hv_trace.c:perf_trace_vmbus_open
  - drivers/hv/hv_trace.c:perf_trace_vmbus_request_offers
  - drivers/hv/hv_trace.c:perf_trace_vmbus_onversion_response
  - drivers/hv/hv_trace.c:perf_trace_vmbus_ongpadl_torndown
  - drivers/hv/hv_trace.c:perf_trace_vmbus_ongpadl_created
  - drivers/hv/hv_trace.c:perf_trace_vmbus_onopen_result
  - drivers/hv/hv_trace.c:perf_trace_vmbus_onoffer_rescind
  - drivers/hv/hv_trace.c:perf_trace_vmbus_onoffer
  - drivers/hv/hv_trace.c:perf_trace_vmbus_hdr_msg
```
```
In drivers/devfreq/devfreq.c (ffffffff818584a2)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
```
```
In drivers/ras/ras.c (ffffffff8185bca4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_memory_failure_event
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_non_standard_event
  - drivers/ras/ras.c:perf_trace_arm_event
  - drivers/ras/ras.c:perf_trace_mc_event
```
```
In net/core/net-traces.c (ffffffff818cb247)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:perf_trace_neigh_create
  - net/core/net-traces.c:perf_trace_page_pool_state_hold
  - net/core/net-traces.c:perf_trace_page_pool_state_release
  - net/core/net-traces.c:perf_trace_page_pool_inflight
  - net/core/net-traces.c:perf_trace_br_fdb_update
  - net/core/net-traces.c:perf_trace_fdb_delete
  - net/core/net-traces.c:perf_trace_br_fdb_external_learn_add
  - net/core/net-traces.c:perf_trace_br_fdb_add
  - net/core/net-traces.c:perf_trace_qdisc_dequeue
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_rcvqueue_full
  - net/core/net-traces.c:perf_trace_napi_poll
  - net/core/net-traces.c:perf_trace_net_dev_rx_exit_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_template
  - net/core/net-traces.c:perf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:perf_trace_net_dev_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:perf_trace_consume_skb
  - net/core/net-traces.c:perf_trace_kfree_skb
```
```
In net/core/devlink.c (ffffffff818d95f0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/core/bpf_sk_storage.c (ffffffff818e3835)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_update
```
```
In net/bpf/test_run.c (ffffffff818fd20a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv4/inet_hashtables.c (ffffffff81913716)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81914fa5)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/raw.c (ffffffff8193c28c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff8193f807)
Location: include/linux/list.h:752
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff8195e36c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197d4ca)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81987500)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
```
```
In net/unix/af_unix.c (ffffffff8198bf90)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/anycast.c (ffffffff819934ba)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_anycast_cleanup
```
```
In net/ipv6/addrconf.c (ffffffff819a43b6)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
```
```
In net/ipv6/route.c (ffffffff819a5487)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
```
In net/ipv6/raw.c (ffffffff819c0e3d)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffff819e6990)
Location: include/linux/list.h:752
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81a07765)
Location: include/linux/list.h:752
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
In init/main.c (ffffffff8100220f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/common.c (ffffffff810038cf)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004efa)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff8102a29f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_set_ldt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_gdt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_load_idt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_one_user
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_alloc_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pte_at
  - arch/x86/xen/trace.c:perf_trace_xen_mmu__set_pte
  - arch/x86/xen/trace.c:perf_trace_xen_mc_extend_args
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush_reason
  - arch/x86/xen/trace.c:perf_trace_xen_mc_callback
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry_alloc
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mc__batch
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102e0d1)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/irq.c (ffffffff81033328)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:perf_trace_vector_free_moved
  - arch/x86/kernel/irq.c:perf_trace_vector_setup
  - arch/x86/kernel/irq.c:perf_trace_vector_teardown
  - arch/x86/kernel/irq.c:perf_trace_vector_activate
  - arch/x86/kernel/irq.c:perf_trace_vector_alloc_managed
  - arch/x86/kernel/irq.c:perf_trace_vector_alloc
  - arch/x86/kernel/irq.c:perf_trace_vector_reserve
  - arch/x86/kernel/irq.c:perf_trace_vector_mod
  - arch/x86/kernel/irq.c:perf_trace_vector_config
  - arch/x86/kernel/irq.c:perf_trace_x86_irq_vector
```
```
In arch/x86/kernel/nmi.c (ffffffff81035da4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103e19a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c6fa)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105f93f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/init.c (ffffffff8107c9bf)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff8107e714)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff8108c2fa)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:perf_trace_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:perf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:perf_trace_bounds_exception_mpx
  - arch/x86/mm/mpx.c:perf_trace_mpx_bounds_register_exception
```
```
In kernel/fork.c (ffffffff810962b0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff8109d07f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/exit.c (ffffffff8109f24d)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/softirq.c (ffffffff810a0d1a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810a8ea4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810b8d4a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/pid.c (ffffffff810bf814)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/sched/core.c (ffffffff810ca7ca)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_wake_idle_without_ipi
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:perf_trace_sched_process_hang
  - kernel/sched/core.c:perf_trace_sched_pi_setprio
  - kernel/sched/core.c:perf_trace_sched_stat_runtime
  - kernel/sched/core.c:perf_trace_sched_process_exec
  - kernel/sched/core.c:perf_trace_sched_process_fork
  - kernel/sched/core.c:perf_trace_sched_process_wait
  - kernel/sched/core.c:perf_trace_sched_process_template
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:perf_trace_sched_kthread_stop_ret
  - kernel/sched/core.c:perf_trace_sched_kthread_stop
```
```
In kernel/printk/printk.c (ffffffff81107df4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff811189d3)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff81119a5a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff81126118)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/time/timer.c (ffffffff8112d4d8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:perf_trace_tick_stop
  - kernel/time/timer.c:perf_trace_itimer_expire
  - kernel/time/timer.c:perf_trace_itimer_state
  - kernel/time/timer.c:perf_trace_hrtimer_class
  - kernel/time/timer.c:perf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:perf_trace_hrtimer_start
  - kernel/time/timer.c:perf_trace_hrtimer_init
  - kernel/time/timer.c:perf_trace_timer_expire_entry
  - kernel/time/timer.c:perf_trace_timer_start
  - kernel/time/timer.c:perf_trace_timer_class
```
```
In kernel/time/alarmtimer.c (ffffffff8113518f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff81148dc5)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff811558e1)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/kprobes.c (ffffffff81177abd)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/trace/ftrace.c (ffffffff8118eab4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:profile_graph_return
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b4286)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c7aaf)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/power-traces.c (ffffffff811c97e4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:perf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:perf_trace_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_power_domain
  - kernel/trace/power-traces.c:perf_trace_clock
  - kernel/trace/power-traces.c:perf_trace_wakeup_source
  - kernel/trace/power-traces.c:perf_trace_suspend_resume
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:perf_trace_cpu_frequency_limits
  - kernel/trace/power-traces.c:perf_trace_pstate_sample
  - kernel/trace/power-traces.c:perf_trace_powernv_throttle
  - kernel/trace/power-traces.c:perf_trace_cpu
```
```
In kernel/trace/rpm-traces.c (ffffffff811caf83)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ceb06)
Location: include/linux/list.h:752
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811d1e2f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_mem_return_failed
  - kernel/bpf/core.c:perf_trace_mem_connect
  - kernel/bpf/core.c:perf_trace_mem_disconnect
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_bulk_tx
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/events/core.c (ffffffff81201bb5)
Location: include/linux/list.h:752
Inline: True
```
```
In kernel/user-return-notifier.c (ffffffff812132b2)
Location: include/linux/list.h:752
Inline: True
```
```
In kernel/rseq.c (ffffffff81215b58)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff81216caf)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff8121e94b)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:perf_trace_skip_task_reaping
  - mm/oom_kill.c:perf_trace_finish_task_reaping
  - mm/oom_kill.c:perf_trace_start_task_reaping
  - mm/oom_kill.c:perf_trace_wake_reaper
  - mm/oom_kill.c:perf_trace_mark_victim
  - mm/oom_kill.c:perf_trace_reclaim_retry_zone
  - mm/oom_kill.c:perf_trace_oom_score_adj_update
```
```
In mm/swap.c (ffffffff8122689a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff8122bc14)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/vmscan.c:perf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:perf_trace_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_isolate
  - mm/vmscan.c:perf_trace_mm_shrink_slab_end
  - mm/vmscan.c:perf_trace_mm_shrink_slab_start
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_end_template
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:perf_trace_mm_vmscan_wakeup_kswapd
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_wake
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_sleep
```
```
In mm/percpu.c (ffffffff812411fa)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff8124482b)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:perf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:perf_trace_mm_page
  - mm/slab_common.c:perf_trace_mm_page_alloc
  - mm/slab_common.c:perf_trace_mm_page_free_batched
  - mm/slab_common.c:perf_trace_mm_page_free
  - mm/slab_common.c:perf_trace_kmem_free
  - mm/slab_common.c:perf_trace_kmem_alloc_node
  - mm/slab_common.c:perf_trace_kmem_alloc
```
```
In mm/compaction.c (ffffffff81247ab4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/compaction.c:perf_trace_kcompactd_wake_template
  - mm/compaction.c:perf_trace_mm_compaction_kcompactd_sleep
  - mm/compaction.c:perf_trace_mm_compaction_defer_template
  - mm/compaction.c:perf_trace_mm_compaction_suitable_template
  - mm/compaction.c:perf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:perf_trace_mm_compaction_end
  - mm/compaction.c:perf_trace_mm_compaction_begin
  - mm/compaction.c:perf_trace_mm_compaction_migratepages
  - mm/compaction.c:perf_trace_mm_compaction_isolate_template
```
```
In mm/mmu_notifier.c (ffffffff81294804)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_mm_destroy
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (ffffffff812979c4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
```
```
In mm/migrate.c (ffffffff812a3138)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff812b08d8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff812c3724)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffffffff812c7584)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffffffff812cecee)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/super.c (ffffffff812d7a7b)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/super.c:reconfigure_super
```
```
In fs/dcache.c (ffffffff812f02a7)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_find_any_alias
```
```
In fs/namespace.c (ffffffff812fba0f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:namespace_unlock
```
```
In fs/seq_file.c (ffffffff812fec0c)
Location: include/linux/list.h:752
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8130458a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_writeback_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_congest_waited_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_pages_written
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
```
```
In fs/notify/mark.c (ffffffff81323fc1)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/dax.c (ffffffff8133c684)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/dax.c:perf_trace_dax_writeback_one
  - fs/dax.c:perf_trace_dax_writeback_range_class
  - fs/dax.c:perf_trace_dax_insert_mapping
  - fs/dax.c:perf_trace_dax_pte_fault_class
  - fs/dax.c:perf_trace_dax_pmd_insert_mapping_class
  - fs/dax.c:perf_trace_dax_pmd_load_hole_class
  - fs/dax.c:perf_trace_dax_pmd_fault_class
```
```
In fs/locks.c (ffffffff813485e3)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffff813cb7e4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_error
  - fs/ext4/super.c:perf_trace_ext4_shutdown
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:perf_trace_ext4_insert_range
  - fs/ext4/super.c:perf_trace_ext4_collapse_range
  - fs/ext4/super.c:perf_trace_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:perf_trace_ext4__es_shrink_enter
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_enter
  - fs/ext4/super.c:perf_trace_ext4_es_remove_extent
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_idx
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_show_extent
  - fs/ext4/super.c:perf_trace_ext4_get_reserved_cluster_alloc
  - fs/ext4/super.c:perf_trace_ext4_find_delalloc_range
  - fs/ext4/super.c:perf_trace_ext4_ext_in_cache
  - fs/ext4/super.c:perf_trace_ext4_ext_put_in_cache
  - fs/ext4/super.c:perf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:perf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:perf_trace_ext4__trim
  - fs/ext4/super.c:perf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:perf_trace_ext4_journal_start
  - fs/ext4/super.c:perf_trace_ext4_load_inode
  - fs/ext4/super.c:perf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_exit
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_enter
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:perf_trace_ext4__truncate
  - fs/ext4/super.c:perf_trace_ext4_unlink_exit
  - fs/ext4/super.c:perf_trace_ext4_unlink_enter
  - fs/ext4/super.c:perf_trace_ext4_fallocate_exit
  - fs/ext4/super.c:perf_trace_ext4__fallocate_mode
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_exit
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_enter
  - fs/ext4/super.c:perf_trace_ext4__bitmap_load
  - fs/ext4/super.c:perf_trace_ext4_da_release_space
  - fs/ext4/super.c:perf_trace_ext4_da_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_da_update_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_forget
  - fs/ext4/super.c:perf_trace_ext4__mballoc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_prealloc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_alloc
  - fs/ext4/super.c:perf_trace_ext4_alloc_da_blocks
  - fs/ext4/super.c:perf_trace_ext4_sync_fs
  - fs/ext4/super.c:perf_trace_ext4_sync_file_exit
  - fs/ext4/super.c:perf_trace_ext4_sync_file_enter
  - fs/ext4/super.c:perf_trace_ext4_free_blocks
  - fs/ext4/super.c:perf_trace_ext4_allocate_blocks
  - fs/ext4/super.c:perf_trace_ext4_request_blocks
  - fs/ext4/super.c:perf_trace_ext4_mb_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_mb_release_group_pa
  - fs/ext4/super.c:perf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:perf_trace_ext4__mb_new_pa
  - fs/ext4/super.c:perf_trace_ext4_discard_blocks
  - fs/ext4/super.c:perf_trace_ext4_invalidatepage_op
  - fs/ext4/super.c:perf_trace_ext4__page_op
  - fs/ext4/super.c:perf_trace_ext4_writepages_result
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages_extent
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages
  - fs/ext4/super.c:perf_trace_ext4_writepages
  - fs/ext4/super.c:perf_trace_ext4__write_end
  - fs/ext4/super.c:perf_trace_ext4__write_begin
  - fs/ext4/super.c:perf_trace_ext4_begin_ordered_truncate
  - fs/ext4/super.c:perf_trace_ext4_mark_inode_dirty
  - fs/ext4/super.c:perf_trace_ext4_nfs_commit_metadata
  - fs/ext4/super.c:perf_trace_ext4_drop_inode
  - fs/ext4/super.c:perf_trace_ext4_evict_inode
  - fs/ext4/super.c:perf_trace_ext4_allocate_inode
  - fs/ext4/super.c:perf_trace_ext4_request_inode
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
```
```
In fs/jbd2/journal.c (ffffffff813ed07f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/jbd2/journal.c:perf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:perf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:perf_trace_jbd2_update_log_tail
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_run_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_extend
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_start
  - fs/jbd2/journal.c:perf_trace_jbd2_submit_inode_data
  - fs/jbd2/journal.c:perf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint
```
```
In security/selinux/avc.c (ffffffff8144f46a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_get_hash_stats
```
```
In block/blk-core.c (ffffffff814d7771)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_unplug
  - block/blk-core.c:perf_trace_block_plug
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_buffer
```
```
In block/blk-ioc.c (ffffffff814de9a0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff814ff2a2)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In block/blk-iocost.c (ffffffff81505b6e)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_activate
```
```
In block/blk-wbt.c (ffffffff8150d5e8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In arch/x86/lib/msr.c (ffffffff81551834)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff8155e134)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (ffffffff81644e74)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff8166dbce)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff816afc84)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/char/random.c:perf_trace_urandom_read
  - drivers/char/random.c:perf_trace_random_read
  - drivers/char/random.c:perf_trace_random__extract_entropy
  - drivers/char/random.c:perf_trace_random__get_random_bytes
  - drivers/char/random.c:perf_trace_xfer_secondary_pool
  - drivers/char/random.c:perf_trace_add_disk_randomness
  - drivers/char/random.c:perf_trace_add_input_randomness
  - drivers/char/random.c:perf_trace_debit_entropy
  - drivers/char/random.c:perf_trace_push_to_pool
  - drivers/char/random.c:perf_trace_credit_entropy_bits
  - drivers/char/random.c:perf_trace_random__mix_pool_bytes
  - drivers/char/random.c:perf_trace_add_device_randomness
```
```
In drivers/iommu/iommu-traces.c (ffffffff816d01fc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/iommu/intel-trace.c (ffffffff816e4de4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/iommu/intel-trace.c:perf_trace_dma_unmap
  - drivers/iommu/intel-trace.c:perf_trace_dma_map
```
```
In drivers/base/regmap/regmap.c (ffffffff8171261f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8175a297)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8175cea2)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff8175e39a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff817822ea)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff817a7d6d)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff817b273c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff8183dbea)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_dbc_log_request
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_slot_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ep_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_free_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_trb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
```
```
In drivers/rtc/interface.c (ffffffff8185a01a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/rtc/interface.c:perf_trace_rtc_timer_class
  - drivers/rtc/interface.c:perf_trace_rtc_offset_class
  - drivers/rtc/interface.c:perf_trace_rtc_alarm_irq_enable
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_state
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_freq
  - drivers/rtc/interface.c:perf_trace_rtc_time_alarm_class
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8185fc34)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff818639dc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff8187a71f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff8187c708)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (ffffffff8188130c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff818c9054)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffffffff818e671a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_cmd_class
```
```
In drivers/devfreq/devfreq.c (ffffffff818ea6c2)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
```
```
In drivers/ras/ras.c (ffffffff818f16d4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_memory_failure_event
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_non_standard_event
  - drivers/ras/ras.c:perf_trace_arm_event
  - drivers/ras/ras.c:perf_trace_mc_event
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
```
```
In net/core/net-traces.c (ffffffff819624b7)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:perf_trace_neigh_create
  - net/core/net-traces.c:perf_trace_page_pool_state_hold
  - net/core/net-traces.c:perf_trace_page_pool_state_release
  - net/core/net-traces.c:perf_trace_page_pool_inflight
  - net/core/net-traces.c:perf_trace_br_fdb_update
  - net/core/net-traces.c:perf_trace_fdb_delete
  - net/core/net-traces.c:perf_trace_br_fdb_external_learn_add
  - net/core/net-traces.c:perf_trace_br_fdb_add
  - net/core/net-traces.c:perf_trace_qdisc_dequeue
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_rcvqueue_full
  - net/core/net-traces.c:perf_trace_napi_poll
  - net/core/net-traces.c:perf_trace_net_dev_rx_exit_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_template
  - net/core/net-traces.c:perf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:perf_trace_net_dev_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:perf_trace_consume_skb
  - net/core/net-traces.c:perf_trace_kfree_skb
```
```
In net/core/devlink.c (ffffffff819709d0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/core/bpf_sk_storage.c (ffffffff8197ac15)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_update
```
```
In net/bpf/test_run.c (ffffffff819948aa)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/netfilter/nfnetlink_queue.c (ffffffff819991df)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_queue.c:nfnl_queue_net_exit
  - net/netfilter/nfnetlink_queue.c:seq_start
```
```
In net/netfilter/nfnetlink_log.c (ffffffff8199b528)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_log.c:nfnl_log_net_exit
  - net/netfilter/nfnetlink_log.c:seq_start
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff8199cd6f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_alter_reply
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c43f6)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c5c85)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/raw.c (ffffffff819ecf9c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819f0517)
Location: include/linux/list.h:752
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff81a0f14c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2b15a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81a35190)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
```
```
In net/unix/af_unix.c (ffffffff81a39c50)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/anycast.c (ffffffff81a4117a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_anycast_cleanup
```
```
In net/ipv6/addrconf.c (ffffffff81a52076)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
```
```
In net/ipv6/route.c (ffffffff81a53147)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
```
In net/ipv6/raw.c (ffffffff81a6eafd)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffff81a95350)
Location: include/linux/list.h:752
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81ab6a25)
Location: include/linux/list.h:752
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
In init/main.c (ffffffff8100220f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/common.c (ffffffff8100399f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8100503a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff8102b08f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_set_ldt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_gdt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_load_idt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_one_user
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_alloc_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pte_at
  - arch/x86/xen/trace.c:perf_trace_xen_mmu__set_pte
  - arch/x86/xen/trace.c:perf_trace_xen_mc_extend_args
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush_reason
  - arch/x86/xen/trace.c:perf_trace_xen_mc_callback
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry_alloc
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mc__batch
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102eec1)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/irq.c (ffffffff81034288)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:perf_trace_vector_free_moved
  - arch/x86/kernel/irq.c:perf_trace_vector_setup
  - arch/x86/kernel/irq.c:perf_trace_vector_teardown
  - arch/x86/kernel/irq.c:perf_trace_vector_activate
  - arch/x86/kernel/irq.c:perf_trace_vector_alloc_managed
  - arch/x86/kernel/irq.c:perf_trace_vector_alloc
  - arch/x86/kernel/irq.c:perf_trace_vector_reserve
  - arch/x86/kernel/irq.c:perf_trace_vector_mod
  - arch/x86/kernel/irq.c:perf_trace_vector_config
  - arch/x86/kernel/irq.c:perf_trace_x86_irq_vector
```
```
In arch/x86/kernel/nmi.c (ffffffff81036d84)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103f31a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104db0a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060e9f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/init.c (ffffffff8107eabf)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff81080804)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff8108e65a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:perf_trace_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:perf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:perf_trace_bounds_exception_mpx
  - arch/x86/mm/mpx.c:perf_trace_mpx_bounds_register_exception
```
```
In kernel/fork.c (ffffffff8109ded0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff810a4eaf)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/exit.c (ffffffff810a719d)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/softirq.c (ffffffff810a8c9a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810b0ff4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810c17aa)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/pid.c (ffffffff810c7c23)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/sched/core.c (ffffffff810d2cca)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_wake_idle_without_ipi
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:perf_trace_sched_process_hang
  - kernel/sched/core.c:perf_trace_sched_pi_setprio
  - kernel/sched/core.c:perf_trace_sched_stat_runtime
  - kernel/sched/core.c:perf_trace_sched_process_exec
  - kernel/sched/core.c:perf_trace_sched_process_fork
  - kernel/sched/core.c:perf_trace_sched_process_wait
  - kernel/sched/core.c:perf_trace_sched_process_template
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:perf_trace_sched_kthread_stop_ret
  - kernel/sched/core.c:perf_trace_sched_kthread_stop
```
```
In kernel/printk/printk.c (ffffffff81113194)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff81124063)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff811251ca)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff81132758)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/time/timer.c (ffffffff81139def)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:perf_trace_tick_stop
  - kernel/time/timer.c:perf_trace_itimer_expire
  - kernel/time/timer.c:perf_trace_itimer_state
  - kernel/time/timer.c:perf_trace_hrtimer_class
  - kernel/time/timer.c:perf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:perf_trace_hrtimer_start
  - kernel/time/timer.c:perf_trace_hrtimer_init
  - kernel/time/timer.c:perf_trace_timer_expire_entry
  - kernel/time/timer.c:perf_trace_timer_start
  - kernel/time/timer.c:perf_trace_timer_class
```
```
In kernel/time/alarmtimer.c (ffffffff81141baf)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff811559e5)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff81163051)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/kprobes.c (ffffffff8118537d)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/trace/ftrace.c (ffffffff8119c644)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:profile_graph_return
```
```
In kernel/trace/trace_syscalls.c (ffffffff811c2326)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811d5d0f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/power-traces.c (ffffffff811d7a44)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:perf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:perf_trace_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_power_domain
  - kernel/trace/power-traces.c:perf_trace_clock
  - kernel/trace/power-traces.c:perf_trace_wakeup_source
  - kernel/trace/power-traces.c:perf_trace_suspend_resume
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:perf_trace_cpu_frequency_limits
  - kernel/trace/power-traces.c:perf_trace_pstate_sample
  - kernel/trace/power-traces.c:perf_trace_powernv_throttle
  - kernel/trace/power-traces.c:perf_trace_cpu
```
```
In kernel/trace/rpm-traces.c (ffffffff811d91e3)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffffffff811dcd7d)
Location: include/linux/list.h:752
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811e011f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_mem_return_failed
  - kernel/bpf/core.c:perf_trace_mem_connect
  - kernel/bpf/core.c:perf_trace_mem_disconnect
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_bulk_tx
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/events/core.c (ffffffff81210f45)
Location: include/linux/list.h:752
Inline: True
```
```
In kernel/user-return-notifier.c (ffffffff81222252)
Location: include/linux/list.h:752
Inline: True
```
```
In kernel/rseq.c (ffffffff81224b58)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff81225d2f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff8122d99b)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:perf_trace_skip_task_reaping
  - mm/oom_kill.c:perf_trace_finish_task_reaping
  - mm/oom_kill.c:perf_trace_start_task_reaping
  - mm/oom_kill.c:perf_trace_wake_reaper
  - mm/oom_kill.c:perf_trace_mark_victim
  - mm/oom_kill.c:perf_trace_reclaim_retry_zone
  - mm/oom_kill.c:perf_trace_oom_score_adj_update
```
```
In mm/swap.c (ffffffff81235bca)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff8123b004)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/vmscan.c:perf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:perf_trace_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_isolate
  - mm/vmscan.c:perf_trace_mm_shrink_slab_end
  - mm/vmscan.c:perf_trace_mm_shrink_slab_start
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_end_template
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:perf_trace_mm_vmscan_wakeup_kswapd
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_wake
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_sleep
```
```
In mm/percpu.c (ffffffff8125097a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff81253feb)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:perf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:perf_trace_mm_page
  - mm/slab_common.c:perf_trace_mm_page_alloc
  - mm/slab_common.c:perf_trace_mm_page_free_batched
  - mm/slab_common.c:perf_trace_mm_page_free
  - mm/slab_common.c:perf_trace_kmem_free
  - mm/slab_common.c:perf_trace_kmem_alloc_node
  - mm/slab_common.c:perf_trace_kmem_alloc
```
```
In mm/compaction.c (ffffffff812572e4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/compaction.c:perf_trace_kcompactd_wake_template
  - mm/compaction.c:perf_trace_mm_compaction_kcompactd_sleep
  - mm/compaction.c:perf_trace_mm_compaction_defer_template
  - mm/compaction.c:perf_trace_mm_compaction_suitable_template
  - mm/compaction.c:perf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:perf_trace_mm_compaction_end
  - mm/compaction.c:perf_trace_mm_compaction_begin
  - mm/compaction.c:perf_trace_mm_compaction_migratepages
  - mm/compaction.c:perf_trace_mm_compaction_isolate_template
```
```
In mm/mmu_notifier.c (ffffffff812a4674)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_mm_destroy
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (ffffffff812a7796)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:remove_all_stable_nodes
```
```
In mm/migrate.c (ffffffff812b33c8)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff812c0c18)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff812d41c4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffffffff812d8274)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffffffff812dfafe)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/super.c (ffffffff812e88bb)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/super.c:reconfigure_super
```
```
In fs/dcache.c (ffffffff81301398)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_find_any_alias
```
```
In fs/namespace.c (ffffffff8130cd3a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:namespace_unlock
```
```
In fs/seq_file.c (ffffffff8130ff4c)
Location: include/linux/list.h:752
Inline: True
```
```
In fs/fs-writeback.c (ffffffff813158fa)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_writeback_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_congest_waited_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_pages_written
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
```
```
In fs/notify/mark.c (ffffffff81335d00)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/dax.c (ffffffff8134f834)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/dax.c:perf_trace_dax_writeback_one
  - fs/dax.c:perf_trace_dax_writeback_range_class
  - fs/dax.c:perf_trace_dax_insert_mapping
  - fs/dax.c:perf_trace_dax_pte_fault_class
  - fs/dax.c:perf_trace_dax_pmd_insert_mapping_class
  - fs/dax.c:perf_trace_dax_pmd_load_hole_class
  - fs/dax.c:perf_trace_dax_pmd_fault_class
```
```
In fs/locks.c (ffffffff8135b923)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffff813e0a34)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_error
  - fs/ext4/super.c:perf_trace_ext4_shutdown
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:perf_trace_ext4_insert_range
  - fs/ext4/super.c:perf_trace_ext4_collapse_range
  - fs/ext4/super.c:perf_trace_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:perf_trace_ext4__es_shrink_enter
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_enter
  - fs/ext4/super.c:perf_trace_ext4_es_remove_extent
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_idx
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_show_extent
  - fs/ext4/super.c:perf_trace_ext4_get_reserved_cluster_alloc
  - fs/ext4/super.c:perf_trace_ext4_find_delalloc_range
  - fs/ext4/super.c:perf_trace_ext4_ext_in_cache
  - fs/ext4/super.c:perf_trace_ext4_ext_put_in_cache
  - fs/ext4/super.c:perf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:perf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:perf_trace_ext4__trim
  - fs/ext4/super.c:perf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:perf_trace_ext4_journal_start
  - fs/ext4/super.c:perf_trace_ext4_load_inode
  - fs/ext4/super.c:perf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_exit
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_enter
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:perf_trace_ext4__truncate
  - fs/ext4/super.c:perf_trace_ext4_unlink_exit
  - fs/ext4/super.c:perf_trace_ext4_unlink_enter
  - fs/ext4/super.c:perf_trace_ext4_fallocate_exit
  - fs/ext4/super.c:perf_trace_ext4__fallocate_mode
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_exit
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_enter
  - fs/ext4/super.c:perf_trace_ext4__bitmap_load
  - fs/ext4/super.c:perf_trace_ext4_da_release_space
  - fs/ext4/super.c:perf_trace_ext4_da_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_da_update_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_forget
  - fs/ext4/super.c:perf_trace_ext4__mballoc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_prealloc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_alloc
  - fs/ext4/super.c:perf_trace_ext4_alloc_da_blocks
  - fs/ext4/super.c:perf_trace_ext4_sync_fs
  - fs/ext4/super.c:perf_trace_ext4_sync_file_exit
  - fs/ext4/super.c:perf_trace_ext4_sync_file_enter
  - fs/ext4/super.c:perf_trace_ext4_free_blocks
  - fs/ext4/super.c:perf_trace_ext4_allocate_blocks
  - fs/ext4/super.c:perf_trace_ext4_request_blocks
  - fs/ext4/super.c:perf_trace_ext4_mb_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_mb_release_group_pa
  - fs/ext4/super.c:perf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:perf_trace_ext4__mb_new_pa
  - fs/ext4/super.c:perf_trace_ext4_discard_blocks
  - fs/ext4/super.c:perf_trace_ext4_invalidatepage_op
  - fs/ext4/super.c:perf_trace_ext4__page_op
  - fs/ext4/super.c:perf_trace_ext4_writepages_result
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages_extent
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages
  - fs/ext4/super.c:perf_trace_ext4_writepages
  - fs/ext4/super.c:perf_trace_ext4__write_end
  - fs/ext4/super.c:perf_trace_ext4__write_begin
  - fs/ext4/super.c:perf_trace_ext4_begin_ordered_truncate
  - fs/ext4/super.c:perf_trace_ext4_mark_inode_dirty
  - fs/ext4/super.c:perf_trace_ext4_nfs_commit_metadata
  - fs/ext4/super.c:perf_trace_ext4_drop_inode
  - fs/ext4/super.c:perf_trace_ext4_evict_inode
  - fs/ext4/super.c:perf_trace_ext4_allocate_inode
  - fs/ext4/super.c:perf_trace_ext4_request_inode
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
```
```
In fs/jbd2/journal.c (ffffffff81402a4f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - fs/jbd2/journal.c:perf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:perf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:perf_trace_jbd2_update_log_tail
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_run_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_extend
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_start
  - fs/jbd2/journal.c:perf_trace_jbd2_submit_inode_data
  - fs/jbd2/journal.c:perf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint
```
```
In security/selinux/avc.c (ffffffff81466886)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_get_hash_stats
```
```
In block/blk-core.c (ffffffff814f0381)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_unplug
  - block/blk-core.c:perf_trace_block_plug
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_buffer
```
```
In block/blk-ioc.c (ffffffff814f77b0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff81518412)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In block/blk-iocost.c (ffffffff8152140e)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_activate
```
```
In block/blk-wbt.c (ffffffff81526c08)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In arch/x86/lib/msr.c (ffffffff8156b544)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff81577fc4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (ffffffff8165f394)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff8168822e)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff816ca2e4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/char/random.c:perf_trace_urandom_read
  - drivers/char/random.c:perf_trace_random_read
  - drivers/char/random.c:perf_trace_random__extract_entropy
  - drivers/char/random.c:perf_trace_random__get_random_bytes
  - drivers/char/random.c:perf_trace_xfer_secondary_pool
  - drivers/char/random.c:perf_trace_add_disk_randomness
  - drivers/char/random.c:perf_trace_add_input_randomness
  - drivers/char/random.c:perf_trace_debit_entropy
  - drivers/char/random.c:perf_trace_push_to_pool
  - drivers/char/random.c:perf_trace_credit_entropy_bits
  - drivers/char/random.c:perf_trace_random__mix_pool_bytes
  - drivers/char/random.c:perf_trace_add_device_randomness
```
```
In drivers/iommu/iommu-traces.c (ffffffff816ea78c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/iommu/intel-trace.c (ffffffff816ff4a4)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/iommu/intel-trace.c:perf_trace_dma_unmap
  - drivers/iommu/intel-trace.c:perf_trace_dma_map
```
```
In drivers/base/regmap/regmap.c (ffffffff8172d80f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81775857)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81778672)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff817799fa)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff8179c0da)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff817c1bed)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff817cc6cc)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff818580ba)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_dbc_log_request
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_slot_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ep_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_free_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_trb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
```
```
In drivers/rtc/interface.c (ffffffff818750fa)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/rtc/interface.c:perf_trace_rtc_timer_class
  - drivers/rtc/interface.c:perf_trace_rtc_offset_class
  - drivers/rtc/interface.c:perf_trace_rtc_alarm_irq_enable
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_state
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_freq
  - drivers/rtc/interface.c:perf_trace_rtc_time_alarm_class
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8187ae44)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8187ec3c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff8189611f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff81898138)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (ffffffff8189cd7c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff818e5b74)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffffffff8190339a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_cmd_class
```
```
In drivers/devfreq/devfreq.c (ffffffff8190b742)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
```
```
In drivers/ras/ras.c (ffffffff81912754)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_memory_failure_event
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_non_standard_event
  - drivers/ras/ras.c:perf_trace_arm_event
  - drivers/ras/ras.c:perf_trace_mc_event
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
```
```
In net/core/net-traces.c (ffffffff81984727)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:perf_trace_neigh_create
  - net/core/net-traces.c:perf_trace_page_pool_state_hold
  - net/core/net-traces.c:perf_trace_page_pool_state_release
  - net/core/net-traces.c:perf_trace_page_pool_inflight
  - net/core/net-traces.c:perf_trace_br_fdb_update
  - net/core/net-traces.c:perf_trace_fdb_delete
  - net/core/net-traces.c:perf_trace_br_fdb_external_learn_add
  - net/core/net-traces.c:perf_trace_br_fdb_add
  - net/core/net-traces.c:perf_trace_qdisc_dequeue
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_rcvqueue_full
  - net/core/net-traces.c:perf_trace_napi_poll
  - net/core/net-traces.c:perf_trace_net_dev_rx_exit_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_template
  - net/core/net-traces.c:perf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:perf_trace_net_dev_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:perf_trace_consume_skb
  - net/core/net-traces.c:perf_trace_kfree_skb
```
```
In net/core/devlink.c (ffffffff81992ec0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/core/bpf_sk_storage.c (ffffffff8199d16d)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_update
```
```
In net/bpf/test_run.c (ffffffff819b73ba)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv4/inet_hashtables.c (ffffffff819cde7f)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cf765)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/raw.c (ffffffff819f6e8c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819fb597)
Location: include/linux/list.h:752
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff81a1999c)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a3678a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81a40ab0)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
```
```
In net/unix/af_unix.c (ffffffff81a46290)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/anycast.c (ffffffff81a4cd6a)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_anycast_cleanup
```
```
In net/ipv6/addrconf.c (ffffffff81a5dfc6)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
```
```
In net/ipv6/route.c (ffffffff81a5f097)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
```
In net/ipv6/raw.c (ffffffff81a7b12d)
Location: include/linux/list.h:752
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffff81aa1770)
Location: include/linux/list.h:752
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81ac2b65)
Location: include/linux/list.h:752
Inline: True
```
</details>
</li>
</ul>

## Differences
