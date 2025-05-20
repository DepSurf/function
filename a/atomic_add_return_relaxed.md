# Function: <code>atomic_add_return_relaxed</code>

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
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff813d7dd7)
Location: include/linux/atomic/atomic-instrumented.h:84
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_anon_rmap
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8140c825)
Location: include/linux/atomic/atomic-instrumented.h:176
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_anon_rmap
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff814390aa)
Location: include/linux/atomic/atomic-instrumented.h:176
Inline: True
Inline callers:
  - mm/rmap.c:folio_add_file_rmap_pmd
  - mm/rmap.c:folio_add_anon_rmap_pmd
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
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0363d34)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sched/topology.c (c03a8c64)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/autogroup.c (c03ab9ac)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/locking/rwsem.c (c03b5858)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/irq/spurious.c (c03cdb38)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (c03d3180)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/rcu/tree.c (c03daf08)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
  - kernel/rcu/tree.c:rcu_dynticks_eqs_enter
```
```
In kernel/audit.c (c042bff4)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/trace/ftrace.c (c044f598)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:profile_graph_entry
```
```
In kernel/trace/ring_buffer.c (c045a238)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/trace/trace.c (c04677f8)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
```
```
In kernel/trace/trace_functions.c (c046b6d8)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (c046c71c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (c046f164)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (c0475a24)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (c047dac4)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
```
```
In kernel/bpf/core.c (c0491eb4)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (c0496728)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/bpf/hashtab.c (c04aa450)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/core.c (c04cea7c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
```
```
In kernel/events/callchain.c (c04d2df0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (c04d81ac)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In mm/page-writeback.c (c04e65f0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_update_write_bandwidth
```
```
In mm/vmscan.c (c04f1844)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/workingset.c (c051391c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (c05261e0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/vmalloc.c (c0529de0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/zswap.c (c0541484)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/page_counter.c (c0553328)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/super.c (c056f178)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/pipe.c (c0578168)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/inode.c (c058c578)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/notify/notification.c (c05c0064)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/io_uring.c (c05d292c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
```
```
In fs/coredump.c (c05f1334)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/netlink.c (c05ff190)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (c060220c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/devpts/inode.c (c061f570)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/jbd2/transaction.c (c068d8d0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/ecryptfs/main.c (c06b2a38)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (c06fc68c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (c0747cec)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In block/blk-iocost.c (c07be510)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In drivers/pci/pci.c (c0885738)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_find_domain_nr
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/dma/of-dma.c (c092009c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
```
```
In drivers/regulator/core.c (c094c854)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_lock_dependent
```
```
In drivers/reset/core.c (c0958db4)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
```
```
In drivers/tty/tty_ldsem.c (c0966b68)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_up_write
  - drivers/tty/tty_ldsem.c:ldsem_up_read
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/tty/serial/msm_serial.c (c099b384)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_serial_probe
```
```
In drivers/base/power/wakeup.c (c09edde8)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_report_event
```
```
In drivers/base/devcoredump.c (c0a045f8)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/mfd/mfd-core.c (c0a295fc)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/scsi/scsi_lib.c (c0a4c9a4)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (c0a597d0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (c0a60cb8)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (c0a6f374)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-scsi.c (c0a73fb4)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
```
```
In drivers/input/serio/serio.c (c0b75d40)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (c0b784cc)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/power/reset/vexpress-poweroff.c (c0bab1b8)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/power/reset/vexpress-poweroff.c:_vexpress_register_restart_handler
```
```
In drivers/md/dm.c (c0be09c8)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In drivers/edac/edac_device.c (c0bef104)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (c0bf11bc)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (c0bf1f78)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/cpufreq/omap-cpufreq.c (c0c007e0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/cpufreq/omap-cpufreq.c:omap_cpu_init
```
```
In drivers/cpuidle/coupled.c (c0c0535c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/cpuidle/coupled.c:cpuidle_enter_state_coupled
  - drivers/cpuidle/coupled.c:cpuidle_coupled_parallel_barrier
```
```
In drivers/firmware/arm_scmi/clock.c (c0c38c98)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_rate_set
```
```
In drivers/remoteproc/remoteproc_core.c (c0c64660)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (c0c687c4)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (c0c6a098)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
```
```
In drivers/extcon/extcon.c (c0c6dba4)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/sock.c (c0cc86b8)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (c0cd25f8)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/neighbour.c (c0d01228)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/page_pool.c (c0d24aa4)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
```
```
In net/core/netpoll.c (c0d29484)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (c0d386e0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (c0d485d8)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/ip_fragment.c (c0d6e9fc)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/tcp_output.c (c0d969f0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/udp.c (c0da7664)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_state.c (c0dead30)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/unix/scm.c (c0dfbda8)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
```
```
In net/packet/af_packet.c (c0e5a2fc)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (c0e69ca4)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
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
In kernel/rcu/tree.c (c0000000001e7678)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/rcu/tree.c:rcu_nmi_exit
  - kernel/rcu/tree.c:rcu_idle_enter
  - kernel/rcu/tree.c:rcu_momentary_dyntick_idle
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
```
```
In kernel/audit.c (c00000000025b2a0)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
```
```
In kernel/bpf/syscall.c (c000000000304c20)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
```
```
In mm/rmap.c (c0000000003d8f54)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
```
```
In mm/huge_memory.c (c00000000043c4b8)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In fs/inode.c (c0000000004a65f4)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/quota/netlink.c (c000000000549954)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (c00000000054fc6c)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/jbd2/transaction.c (c000000000602b94)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In block/blk-iocost.c (c0000000007b2258)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In drivers/base/power/wakeup.c (c0000000009a2524)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
```
```
In drivers/md/dm.c (c000000000bf0460)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In net/core/dev.c (c000000000ca400c)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/ipv4/udp.c (c000000000dae974)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
</details>
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
