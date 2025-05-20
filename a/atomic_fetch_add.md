# Function: <code>atomic_fetch_add</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff810d0906)
Location: arch/x86/include/asm/atomic.h:174
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff810d7376)
Location: arch/x86/include/asm/atomic.h:174
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff810d63b6)
Location: arch/x86/include/asm/atomic.h:174
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff8115bdf2)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff8116a962)
Location: include/asm-generic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff81177972)
Location: include/asm-generic/atomic-instrumented.h:315
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff811847d2)
Location: include/asm-generic/atomic-instrumented.h:109
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff81190652)
Location: include/asm-generic/atomic-instrumented.h:109
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_enable
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81193456)
Location: include/asm-generic/atomic-instrumented.h:110
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81194406)
Location: include/asm-generic/atomic-instrumented.h:110
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811bd2a6)
Location: include/linux/atomic/atomic-instrumented.h:88
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/rethook.c (ffffffff81268c95)
Location: include/linux/atomic/atomic-instrumented.h:91
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_try_get
  - kernel/trace/rethook.c:rethook_try_get
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/rethook.c (ffffffff812baf55)
Location: include/linux/atomic/atomic-instrumented.h:91
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_try_get
  - kernel/trace/rethook.c:rethook_try_get
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
In kernel/trace/rethook.c (ffffffff812deb55)
Location: include/linux/atomic/atomic-instrumented.h:194
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_try_get
  - kernel/trace/rethook.c:rethook_try_get
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/arm-smmu-impl.c (ffff8000108d30f4)
Location: include/asm-generic/atomic-instrumented.h:109
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-impl.c:cavium_cfg_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (c03b53ac)
Location: include/linux/atomic-fallback.h:167
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/perf_event.c (ffffffe0000b973a)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - arch/riscv/kernel/perf_event.c:riscv_event_init
```
```
In kernel/signal.c (ffffffe0000cd4c4)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sched/topology.c (ffffffe000101316)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/sched/autogroup.c (ffffffe0001033fa)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/irq/spurious.c (ffffffe0001161c8)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffe00011b0de)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/rcu/tree.c (ffffffe000121980)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_irq_enter
  - kernel/rcu/tree.c:rcu_idle_exit
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/rcu/tree.c:rcu_idle_enter
```
```
In kernel/audit.c (ffffffe000160a9c)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/trace/ftrace.c (ffffffe00017105c)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
```
```
In kernel/trace/trace.c (ffffffe000184aa6)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_panic_handler
```
```
In kernel/trace/trace_functions.c (ffffffe000187a66)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffe00018908a)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffe00018a6f8)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffe00018fce8)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffe000197708)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/bpf/syscall.c (ffffffe00019de08)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
```
```
In kernel/bpf/hashtab.c (ffffffe0001afbb4)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffffffe0001d1c6e)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (ffffffe0001d2fde)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In mm/rmap.c (ffffffe000214fde)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/zswap.c (ffffffe000229de0)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In fs/inode.c (ffffffe000270d9a)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/notify/notification.c (ffffffe00029d408)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/io_uring.c (ffffffe0002acd02)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
```
```
In fs/coredump.c (ffffffe0002c68bc)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/netlink.c (ffffffe0002d17b4)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffe0002d445a)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/devpts/inode.c (ffffffe0002ee710)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/jbd2/transaction.c (ffffffe000343282)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/ecryptfs/main.c (ffffffe0003641d2)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffffffe0003a2326)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffffffe0003e3972)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In block/blk-iocost.c (ffffffe00044ada0)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In drivers/pci/pci.c (ffffffe0004c08b0)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_find_domain_nr
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/dma/of-dma.c (ffffffe000517a54)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
```
```
In drivers/regulator/core.c (ffffffe000527fd2)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffe00052c1d6)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffe00059e376)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/mfd/mfd-core.c (ffffffe0005b3a34)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005e0428)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffffffe0005eb9ae)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffe0005f2c2e)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffe0005fec02)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-scsi.c (ffffffe0005ff93a)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_port_init
```
```
In drivers/input/serio/serio.c (ffffffe0006a4c2c)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffe0006a8950)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/md/dm.c (ffffffe0006f11e0)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In drivers/edac/edac_device.c (ffffffe0006fdc2e)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffe0006ffc3c)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffe00070088a)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/devfreq/devfreq.c (ffffffe00072eda4)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffffffe00073007a)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffe000731d2c)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffffffe000745580)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/neighbour.c (ffffffe00076c63e)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/page_pool.c (ffffffe000789886)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
```
```
In net/core/netpoll.c (ffffffe00078d93c)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffe000799bfc)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (ffffffe0007a7a4e)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/ip_fragment.c (ffffffe0007c778a)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/udp.c (ffffffe0007fa52a)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_state.c (ffffffe00083067c)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/packet/af_packet.c (ffffffe00088f678)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffe00089e1b6)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff81188c72)
Location: include/asm-generic/atomic-instrumented.h:109
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff8117bdb2)
Location: include/asm-generic/atomic-instrumented.h:109
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff81186a42)
Location: include/asm-generic/atomic-instrumented.h:109
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff81194392)
Location: include/asm-generic/atomic-instrumented.h:109
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_enable
```
</details>
</li>
</ul>

## Differences
