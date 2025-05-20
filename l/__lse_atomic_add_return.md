# Function: <code>__lse_atomic_add_return</code>

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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/insn.c (ffff800010da79a8)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - arch/arm64/kernel/insn.c:aarch64_insn_patch_text_cb
```
```
In arch/arm64/kernel/cpu_errata.c (ffff800010098914)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
```
```
In virt/kvm/arm/arm.c (ffff8000100c5778)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:init_hyp_mode
```
```
In kernel/signal.c (ffff80001010b464)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sched/topology.c (ffff80001015c260)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/autogroup.c (ffff80001015f104)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/irq/spurious.c (ffff80001017d080)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffff800010183f64)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/rcu/tree.c (ffff80001018f6bc)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_momentary_dyntick_idle
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
  - kernel/rcu/tree.c:rcu_dynticks_eqs_enter
```
```
In kernel/audit.c (ffff8000101ec498)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/trace/ftrace.c (ffff800010210eb0)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
```
```
In kernel/trace/trace.c (ffff80001022a13c)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
```
```
In kernel/trace/tracing_map.c (ffff80001022e1e8)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
```
```
In kernel/trace/trace_functions.c (ffff800010230144)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffff800010230704)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffff8000102333cc)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffff80001023b33c)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffff800010242938)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
```
```
In kernel/bpf/syscall.c (ffff80001025fed0)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_add
  - kernel/bpf/syscall.c:bpf_map_inc
```
```
In kernel/bpf/hashtab.c (ffff8000102783b4)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffff8000102a356c)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (ffff8000102aa0f8)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In mm/rmap.c (ffff80001030b688)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/zswap.c (ffff80001032b218)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/huge_memory.c (ffff800010355fac)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memcontrol.c (ffff80001036965c)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In fs/inode.c (ffff8000103accb0)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/notify/notification.c (ffff8000103e88a8)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/io_uring.c (ffff800010401328)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
```
```
In fs/coredump.c (ffff80001042865c)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/netlink.c (ffff800010437550)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffff80001043bf48)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/devpts/inode.c (ffff80001045ead0)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/jbd2/transaction.c (ffff8000104c9dd4)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/ecryptfs/main.c (ffff8000104f5168)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffff800010546ce8)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffff800010596c40)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In block/blk-iocost.c (ffff8000106153d8)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In drivers/pci/pci.c (ffff8000106ea848)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_find_domain_nr
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffff8000107aff44)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/dma/of-dma.c (ffff8000107ff880)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
```
```
In drivers/regulator/core.c (ffff800010847bb4)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffff80001084cf24)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
```
```
In drivers/tty/serial/msm_serial.c (ffff8000108a1d94)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_serial_probe
```
```
In drivers/iommu/arm-smmu.c (ffff8000108d1520)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_attach_dev
```
```
In drivers/base/power/wakeup.c (ffff800010903aa8)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
```
```
In drivers/base/devcoredump.c (ffff80001091f3a4)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/mfd/mfd-core.c (ffff800010940848)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/scsi/scsi_lib.c (ffff800010978b8c)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffff8000109879b8)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffff8000109913e4)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffff80001099ecc8)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-scsi.c (ffff8000109a3740)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
```
```
In drivers/input/serio/serio.c (ffff800010a92948)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffff800010a979f0)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/power/reset/vexpress-poweroff.c (ffff800010aca3d8)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - drivers/power/reset/vexpress-poweroff.c:_vexpress_register_restart_handler
```
```
In drivers/md/dm.c (ffff800010b01104)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In drivers/edac/edac_device.c (ffff800010b11610)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffff800010b137f0)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffff800010b14114)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/firmware/arm_sdei.c (ffff800010b4bde8)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - drivers/firmware/arm_sdei.c:_local_event_register
  - drivers/firmware/arm_sdei.c:_local_event_unregister
  - drivers/firmware/arm_sdei.c:_ipi_event_disable
  - drivers/firmware/arm_sdei.c:_local_event_enable
```
```
In drivers/firmware/arm_scmi/clock.c (ffff800010b57d5c)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_rate_set
```
```
In drivers/remoteproc/remoteproc_core.c (ffff800010b81054)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (ffff800010b86440)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffff800010b87178)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
```
```
In drivers/extcon/extcon.c (ffff800010b88cbc)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffff800010bb5534)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/dev.c (ffff800010bcb0e4)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/core/neighbour.c (ffff800010be8278)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/page_pool.c (ffff800010c0c8bc)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
```
```
In net/core/netpoll.c (ffff800010c11714)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffff800010c20e10)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (ffff800010c310d8)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/ip_fragment.c (ffff800010c5f984)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/udp.c (ffff800010c9c4c4)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_state.c (ffff800010ce36b0)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/packet/af_packet.c (ffff800010d5abb0)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffff800010d6bbe4)
Location: arch/arm64/include/asm/atomic_lse.h:76
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
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
