# Function: <code>atomic_inc_return</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810062fe)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015177)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104d468)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_panic
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_panic
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810812fa)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/sched/topology.c (ffffffff810db8e5)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/sched/autogroup.c (ffffffff810dd417)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/irq/spurious.c (ffffffff810f923f)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff810fd2e2)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/auditsc.c (ffffffff81157ac0)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_set_loginuid
```
```
In kernel/trace/ftrace.c (ffffffff811721ab)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:profile_graph_entry
```
```
In kernel/trace/trace.c (ffffffff81186190)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff81189edf)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_insert
```
```
In kernel/trace/trace_functions.c (ffffffff8118afb0)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8118bc78)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8118e96c)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff81193234)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8119b1e0)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811b35e5)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811c15e0)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/sockmap.c (ffffffff811cdbcf)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
```
```
In kernel/events/callchain.c (ffffffff811e3400)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (ffffffff811e8204)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In kernel/memremap.c (ffffffff811e9345)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - kernel/memremap.c:dev_pagemap_get_ops
```
```
In mm/zswap.c (ffffffff8124f8b4)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/memcontrol.c (ffffffff81284c04)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In fs/inode.c (ffffffff812b8e95)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
```
```
In fs/notify/notification.c (ffffffff812e4cd5)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/coredump.c (ffffffff8130cd6d)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ecryptfs/main.c (ffffffff813b5c65)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffffffff813f76ee)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffffffff8143cac1)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In block/blk-mq.c (ffffffff8148e945)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
```
```
In drivers/pci/pci.c (ffffffff8151e4d5)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff815d673d)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff8160b5f1)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
```
```
In drivers/reset/core.c (ffffffff8160e68a)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81694f0d)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff816a91fc)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/mfd/mfd-core.c (ffffffff816c4f6a)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/scsi/scsi_lib.c (ffffffff816f24f3)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
```
```
In drivers/scsi/sd.c (ffffffff816fed3d)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff81706149)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff81712760)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffff817170e1)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff817b92ed)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff817bf10b)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/md/dm.c (ffffffff818074ca)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_io
```
```
In drivers/edac/edac_device.c (ffffffff818186c5)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff8181a6e5)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff8181b1d5)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/edac/ghes_edac.c (ffffffff8181c692)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In drivers/devfreq/devfreq.c (ffffffff8185d85a)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffffffff8185e389)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff8185ff4a)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffffffff8187db43)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/neighbour.c (ffffffff818a4649)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_create
```
```
In net/core/netpoll.c (ffffffff818bfa94)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/ip_fragment.c (ffffffff818e9182)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/xfrm/xfrm_state.c (ffffffff8195086e)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/packet/af_packet.c (ffffffff819ae3e5)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff819be6dd)
Location: include/asm-generic/atomic-instrumented.h:184
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
```
</details>
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
In arch/x86/events/core.c (ffffffff8100635e)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016e4d)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104dbbb)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108bb5a)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/sched/topology.c (ffffffff810ec36e)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/autogroup.c (ffffffff810eeadf)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/irq/spurious.c (ffffffff8110dc01)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff81112362)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/audit.c (ffffffff8116b52a)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/trace/ftrace.c (ffffffff8118c99e)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811a1770)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff811a51fe)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In kernel/trace/trace_functions.c (ffffffff811a64a0)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a72b8)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811a9cff)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff811af2cb)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811b7330)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811d2315)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811e757d)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffffffff8120b68a)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (ffffffff8120fc35)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In mm/zswap.c (ffffffff8127eb55)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/memcontrol.c (ffffffff812b4d06)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/memremap.c (ffffffff812c2805)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
```
In fs/inode.c (ffffffff812eae05)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In fs/notify/notification.c (ffffffff81319e55)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/coredump.c (ffffffff81349d74)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/devpts/inode.c (ffffffff81374c15)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ecryptfs/main.c (ffffffff813f9da5)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffffffff81440b89)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffffffff8148706f)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In drivers/pci/pci.c (ffffffff81563735)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff81621d9d)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff8165c094)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff8165ef0f)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff816ef14d)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff81705396)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/mfd/mfd-core.c (ffffffff8171faea)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/scsi/scsi_lib.c (ffffffff81750825)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffffffff8175d380)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff81766047)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff8177058e)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-scsi.c (ffffffff81775731)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff81820fbb)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff81826c26)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/edac/edac_device.c (ffffffff81886d35)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff81888cb5)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81889775)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/edac/ghes_edac.c (ffffffff8188ae86)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In drivers/devfreq/devfreq.c (ffffffff818c7426)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/devfreq/devfreq-event.c (ffffffff818c835f)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff818c9ed4)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffffffff818e8f84)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/neighbour.c (ffffffff819146b7)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/netpoll.c (ffffffff819380c6)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff8194495f)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (ffffffff819536ad)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/ip_fragment.c (ffffffff81978464)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/xfrm/xfrm_state.c (ffffffff819ed94e)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/packet/af_packet.c (ffffffff81a53e01)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff81a64bae)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
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
In arch/x86/events/core.c (ffffffff8100640e)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff810177f7)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e55e)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108c7ca)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/signal.c (ffffffff810afaa4)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sched/topology.c (ffffffff810f7e15)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/autogroup.c (ffffffff810fa6df)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/irq/spurious.c (ffffffff81119ec1)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff8111e5f2)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/audit.c (ffffffff8117740a)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/trace/ftrace.c (ffffffff8119859e)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811ad220)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff811b0a2e)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In kernel/trace/trace_functions.c (ffffffff811b1c90)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b2aa8)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811b54ef)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff811ba79b)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811c29a0)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811de8b5)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811f3cdd)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffffffff8121896a)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (ffffffff8121d620)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In mm/zswap.c (ffffffff8128e595)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/memcontrol.c (ffffffff812c67f6)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/memremap.c (ffffffff812d471c)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/inode.c (ffffffff812fc945)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In fs/notify/notification.c (ffffffff8132cc85)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/io_uring.c (ffffffff81340629)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In fs/coredump.c (ffffffff81362014)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/devpts/inode.c (ffffffff8138ce95)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ecryptfs/main.c (ffffffff81413c75)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffffffff8145a499)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffffffff814a0f1f)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In drivers/pci/pci.c (ffffffff815848f5)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff8164387d)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff8167de7b)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff816815df)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff817132ad)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff81729626)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/mfd/mfd-core.c (ffffffff81743dba)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/scsi/scsi_lib.c (ffffffff81774a48)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffffffff81781250)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff8178a037)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff817945ee)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-scsi.c (ffffffff817996a1)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff8185242b)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff81858156)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/edac/edac_device.c (ffffffff818b8cf5)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff818bac65)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff818bb725)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff818f4eac)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (ffffffff818f8ea8)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffffffff818fa7ef)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff818fc324)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffffffff8191b0e4)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/neighbour.c (ffffffff81946d27)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/page_pool.c (ffffffff81966ddb)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
```
```
In net/core/netpoll.c (ffffffff8196af86)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff8197995f)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (ffffffff81989a4d)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/ip_fragment.c (ffffffff819aedd4)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/xfrm/xfrm_state.c (ffffffff81a247fe)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/packet/af_packet.c (ffffffff81a8aa11)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff81a9b94e)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
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
In arch/x86/events/core.c (ffffffff8100741e)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101938b)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81051ec1)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81093de8)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:ioremap_trace_core
```
```
In kernel/signal.c (ffffffff810b78f8)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sched/topology.c (ffffffff81101509)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:init_overlap_sched_group
```
```
In kernel/sched/autogroup.c (ffffffff81104abf)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/irq/spurious.c (ffffffff81125c25)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:misrouted_irq
```
```
In kernel/irq/irqdomain.c (ffffffff81129e34)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/audit.c (ffffffff8118a16d)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/trace/ftrace.c (ffffffff811ad580)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_profile_alloc
```
```
In kernel/trace/trace.c (ffffffff811c4f30)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff811c88c0)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:get_free_elt
```
```
In kernel/trace/trace_functions.c (ffffffff811ca412)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811cafa8)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811ce21a)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff811d5914)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811dcc08)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff81217e93)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffffffff812446aa)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/watch_queue.c (ffffffff8124c828)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/zswap.c (ffffffff812c1245)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/memremap.c (ffffffff8130a377)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/inode.c (ffffffff813351a5)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
```
```
In fs/notify/notification.c (ffffffff81366a25)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/io_uring.c (ffffffff81385da0)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_cancel_files
  - fs/io_uring.c:__io_cqring_fill_event
  - fs/io_uring.c:io_cqring_overflow_flush
```
```
In fs/coredump.c (ffffffff813a7fe9)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/kernfs/inode.c (ffffffff813cd3e3)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
```
```
In fs/devpts/inode.c (ffffffff813d82e5)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ecryptfs/main.c (ffffffff81461e15)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffffffff814ada10)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffffffff814fb040)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In block/keyslot-manager.c (ffffffff8158121a)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
```
```
In drivers/pci/pci.c (ffffffff8162b4d7)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f0d7d)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff8172f55c)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff817326cf)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff817ce624)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_activate
```
```
In drivers/base/devcoredump.c (ffffffff817e5e56)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/scsi/scsi_lib.c (ffffffff8183598d)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff818430f1)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff8184e637)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff818587fe)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-sata.c (ffffffff81868051)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff819242db)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff81929936)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/edac/edac_device.c (ffffffff81989505)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff8198b4c5)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff8198bef5)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_main_kobj_setup
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c9e4c)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (ffffffff819cfa8e)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffffffff819d1070)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff819d2f0f)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffffffff819ede23)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/neighbour.c (ffffffff81a16f95)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/page_pool.c (ffffffff81a3a86b)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release_page
```
```
In net/core/netpoll.c (ffffffff81a3ecee)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff81a4db85)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_alloc_elem
```
```
In net/core/bpf_sk_storage.c (ffffffff81a61767)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/ip_fragment.c (ffffffff81a991e8)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1653e)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/packet/af_packet.c (ffffffff81b865b1)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff81b970de)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
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
In arch/x86/events/core.c (ffffffff8100660e)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff810186ea)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81050fe1)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81093338)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:ioremap_trace_core
```
```
In kernel/signal.c (ffffffff810b2b8f)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sched/topology.c (ffffffff81100069)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:init_overlap_sched_group
```
```
In kernel/sched/autogroup.c (ffffffff8110313f)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/irq/spurious.c (ffffffff81121935)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:misrouted_irq
```
```
In kernel/irq/irqdomain.c (ffffffff811256fa)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/audit.c (ffffffff8118747d)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/trace/ftrace.c (ffffffff811aae90)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_profile_alloc
```
```
In kernel/trace/trace.c (ffffffff811c2b70)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff811c5fa0)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:get_free_elt
```
```
In kernel/trace/trace_functions.c (ffffffff811c7a82)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c8688)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811cb6fa)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff811d2be4)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811d9d38)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff8121a02e)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffffffff8124ec7a)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/watch_queue.c (ffffffff81256c68)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/zswap.c (ffffffff812ccd65)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In fs/inode.c (ffffffff81340b15)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
```
```
In fs/notify/notification.c (ffffffff81373d75)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/coredump.c (ffffffff813b9069)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/kernfs/inode.c (ffffffff813df013)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
```
```
In fs/devpts/inode.c (ffffffff813e9f85)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/mballoc.c (ffffffff8141c38e)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ecryptfs/main.c (ffffffff8147d985)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffffffff814cb490)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffffffff81517f11)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In block/keyslot-manager.c (ffffffff8159e24a)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8163b849)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
```
```
In drivers/pci/pci.c (ffffffff816511d7)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff8170e01d)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff8174c1a0)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff8174e81f)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff817e328c)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_activate
```
```
In drivers/base/devcoredump.c (ffffffff817faae6)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/scsi/scsi_lib.c (ffffffff818464ba)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff81857876)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff8185ea27)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff81868a5e)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-sata.c (ffffffff81876e61)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff8192c08b)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff81930f36)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/edac/edac_device.c (ffffffff8198d295)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff8198f0d5)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff8198fa25)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_main_kobj_setup
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819ca52c)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (ffffffff819cf7ae)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffffffff819d0d30)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff819d2aef)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffffffff819edac3)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/neighbour.c (ffffffff81a17285)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/page_pool.c (ffffffff81a3cd35)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release_page
```
```
In net/core/netpoll.c (ffffffff81a41a8e)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff81a538e5)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_alloc_elem
```
```
In net/ipv4/ip_fragment.c (ffffffff81aa3158)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/xfrm/xfrm_state.c (ffffffff81b2491e)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/packet/af_packet.c (ffffffff81b95ec8)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff81ba6d7e)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
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
In arch/x86/events/core.c (ffffffff8100642e)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81019a0d)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81052d11)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81093d5e)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/signal.c (ffffffff810b41d2)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sched/topology.c (ffffffff8110213c)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/autogroup.c (ffffffff8110547f)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/irq/spurious.c (ffffffff81121de1)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff811259d2)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/rcu/tree.c (0)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
```
```
In kernel/audit.c (ffffffff811883bd)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/trace/ftrace.c (ffffffff811acbdc)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811c3c10)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff811c7642)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/trace/trace_functions.c (ffffffff811c9300)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c991d)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811cca1f)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff811d3891)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811db298)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff8121d7d1)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffffffff8125358a)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/watch_queue.c (ffffffff8125b108)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/zswap.c (ffffffff812d3905)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In fs/inode.c (ffffffff81346f95)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
```
```
In fs/notify/notification.c (ffffffff8137a6d5)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/coredump.c (ffffffff813bffcb)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/kernfs/inode.c (ffffffff813e5cb1)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/devpts/inode.c (ffffffff813f0ac5)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/mballoc.c (ffffffff8142260c)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ecryptfs/main.c (ffffffff81483545)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffffffff814d1ac0)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffffffff8151e787)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In block/keyslot-manager.c (ffffffff815a501a)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
```
```
In lib/percpu-refcount.c (ffffffff815b4ffb)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8161f729)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
```
```
In drivers/pci/pci.c (ffffffff81633c15)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff816ef7bd)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff8172f9b0)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff8173233b)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff817c764c)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_activate
```
```
In drivers/base/devcoredump.c (ffffffff817df7f6)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182ac6f)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff8183a7d0)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff81841697)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff8184b489)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-sata.c (ffffffff81859651)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (ffffffff8188820c)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff8190f59b)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff819140a6)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/edac/edac_device.c (ffffffff81971955)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff81973725)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81974065)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819af53c)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (ffffffff819b48de)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffffffff819b5fdf)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff819b7d9f)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffffffff819d59a3)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_alloc
```
```
In net/core/neighbour.c (ffffffff819fdf60)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/page_pool.c (ffffffff81a23a75)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release_page
```
```
In net/core/netpoll.c (ffffffff81a26551)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff81a50dec)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/ipv4/ip_fragment.c (ffffffff81a8e16e)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1253e)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/packet/af_packet.c (ffffffff81b84da8)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff81b95f0e)
Location: include/asm-generic/atomic-instrumented.h:248
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
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
In arch/x86/events/core.c (ffffffff810067ae)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101e72d)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105b211)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810a3b3e)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/sched/topology.c (ffffffff8111e6b9)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/autogroup.c (ffffffff811230ef)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/irq/spurious.c (ffffffff81142391)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff81146175)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
```
```
In kernel/audit.c (ffffffff811b08dd)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/trace/ftrace.c (ffffffff811d683c)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811eee80)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff811f2d73)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/trace/trace_functions.c (ffffffff811f4d2f)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811f53e7)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811f9169)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff81200711)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812088a8)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff812568a7)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffffffff8128eeca)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/watch_queue.c (ffffffff81296f08)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/zswap.c (ffffffff81319587)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/kfence/core.c (ffffffff8133c70c)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - mm/kfence/core.c:__kfence_alloc
```
```
In fs/inode.c (ffffffff81394355)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - fs/inode.c:ihold
```
```
In fs/notify/notification.c (ffffffff813c7355)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/coredump.c (ffffffff8140fdfb)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/kernfs/inode.c (ffffffff81437831)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/devpts/inode.c (ffffffff814429b5)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/mballoc.c (ffffffff81475d70)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ecryptfs/main.c (ffffffff814dacc5)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffffffff8152a840)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffffffff8157c8d7)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In block/keyslot-manager.c (ffffffff8160daba)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
```
```
In lib/percpu-refcount.c (ffffffff8161b356)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8168ecb9)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
```
```
In drivers/pci/pci.c (ffffffff816a3db7)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff8176981d)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff817af7ac)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff817b2b2e)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81851ca8)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_report_event
```
```
In drivers/base/devcoredump.c (ffffffff8186b27e)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b66ef)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff818c6e80)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff818ce327)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff818d889b)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-sata.c (ffffffff818e8201)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff819b03db)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff819b61c6)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/edac/edac_device.c (ffffffff81a1a605)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff81a1c425)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81a1cd65)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81a5de6c)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (ffffffff81a6341e)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffffffff81a64b1f)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff81a66c9f)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffffffff81a855d3)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_alloc
```
```
In net/core/neighbour.c (ffffffff81ab0063)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/netpoll.c (ffffffff81adb2cc)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff81b09e99)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/ipv4/ip_fragment.c (ffffffff81b4935e)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff81b4d795)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81b862cd)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd640e)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/ipv6/ip6_output.c (ffffffff81bf0b4f)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81c20a84)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81c524ef)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff81c62966)
Location: include/linux/atomic/atomic-instrumented.h:186
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
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
In arch/x86/events/core.c (ffffffff81005bbf)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81021259)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81f1576d)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810b821e)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/sched/build_utility.c (ffffffff81144d6b)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:build_overlap_sched_groups
```
```
In kernel/irq/spurious.c (ffffffff81165eea)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff8116a539)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
```
```
In kernel/audit.c (ffffffff811e2ae9)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_start
```
```
In kernel/trace/ftrace.c (ffffffff8120b9d1)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
```
```
In kernel/trace/trace.c (ffffffff812272f0)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff8122c32a)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/trace/trace_functions.c (ffffffff8122de5d)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8122ec41)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
```
```
In kernel/trace/trace_functions_graph.c (ffffffff81232fe9)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff8123a90c)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81243e98)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff8129f211)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffffffff812e3de8)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/watch_queue.c (ffffffff812ed52c)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/vmscan.c (ffffffff81310d5a)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_throttle
```
```
In mm/zswap.c (ffffffff8138484c)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/kfence/core.c (ffffffff813af9b4)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - mm/kfence/core.c:__kfence_alloc
```
```
In fs/inode.c (ffffffff814160a5)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - fs/inode.c:ihold
```
```
In fs/notify/notification.c (ffffffff8144e735)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/coredump.c (ffffffff814857ca)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/kernfs/inode.c (ffffffff814b25a9)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/devpts/inode.c (ffffffff814be735)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/mballoc.c (ffffffff814f80ad)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ecryptfs/main.c (ffffffff81568645)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffffffff815c020f)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffffffff8161ade6)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In block/blk-mq-tag.c (ffffffff8168c76d)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/blk-crypto-profile.c (ffffffff816c2369)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
```
```
In io_uring/io_uring.c (ffffffff816d3841)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_async_cancel
```
```
In lib/percpu-refcount.c (ffffffff816e8b46)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff817aca30)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
```
```
In drivers/pci/pci.c (ffffffff817c6167)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff8189e1ce)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff818eab64)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff818ef657)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_deassert
  - drivers/reset/core.c:reset_control_reset
```
```
In drivers/base/power/wakeup.c (ffffffff819970e0)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_activate
```
```
In drivers/base/devcoredump.c (ffffffff819b3fdf)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/scsi/scsi_lib.c (ffffffff819ff32f)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff81a13b61)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff81a1c897)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff81a299fb)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-sata.c (ffffffff81a39ca1)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff81b0f12d)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff81b1576b)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/edac/edac_device.c (ffffffff81b83395)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff81b854d5)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81b85e35)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81bce044)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (ffffffff81bd227d)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_suspend_device
```
```
In drivers/devfreq/devfreq-event.c (ffffffff81bd5809)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff81bd81b3)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffffffff81bf838d)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_realloc
```
```
In net/core/neighbour.c (ffffffff81c28faf)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/netpoll.c (ffffffff81c5c7d2)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff81c90112)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/ipv4/ip_fragment.c (ffffffff81cd69ff)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff81cdb002)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81d16c1c)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6cb9e)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/ipv6/ip6_output.c (ffffffff81d89323)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
```
```
In net/ipv6/route.c (ffffffff81d9d9ca)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_gc
```
```
In net/ipv6/raw.c (ffffffff81dbd7f3)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81df457f)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff81e05246)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
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
In arch/x86/events/core.c (ffffffff8100750f)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81025c39)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff820bcdef)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810d3a3e)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/panic.c (ffffffff810ea7e9)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
```
```
In kernel/exit.c (ffffffff810f1fc5)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - kernel/exit.c:make_task_dead
```
```
In kernel/sched/build_utility.c (ffffffff8117115b)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:build_overlap_sched_groups
```
```
In kernel/irq/spurious.c (ffffffff81199fda)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff8119f061)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_create
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
```
```
In kernel/audit.c (ffffffff812289c9)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_start
```
```
In kernel/trace/ftrace.c (ffffffff81254420)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
```
```
In kernel/trace/trace.c (ffffffff81272780)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff81277e5a)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/trace/trace_functions.c (ffffffff81279cfd)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8127ac61)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8127f779)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff812894bf)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81291ac8)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
```
```
In kernel/events/callchain.c (ffffffff8134c4f8)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/watch_queue.c (ffffffff813578fc)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/vmscan.c (ffffffff81384238)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_throttle
```
```
In mm/zswap.c (ffffffff8140247c)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/kfence/core.c (ffffffff8142ff7e)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - mm/kfence/core.c:__kfence_alloc
```
```
In fs/inode.c (ffffffff814a1115)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - fs/inode.c:ihold
```
```
In fs/notify/notification.c (ffffffff814dce55)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/coredump.c (ffffffff81518e2f)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/kernfs/inode.c (ffffffff81549129)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/devpts/inode.c (ffffffff815565b5)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/mballoc.c (ffffffff815926ab)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ecryptfs/main.c (ffffffff8160bf25)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffffffff8166c73f)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffffffff816ce006)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_learning_profile
```
```
In block/blk-mq-tag.c (ffffffff8174af28)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/blk-crypto-profile.c (ffffffff81783689)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
```
```
In io_uring/cancel.c (ffffffff8179e822)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - io_uring/cancel.c:io_sync_cancel
  - io_uring/cancel.c:io_sync_cancel
  - io_uring/cancel.c:io_async_cancel
```
```
In lib/percpu-refcount.c (ffffffff817d8b91)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c4d8a)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
```
```
In drivers/pci/pci.c (ffffffff818e34c7)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff819e71ce)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff81a415e4)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff81a47377)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_deassert
  - drivers/reset/core.c:reset_control_reset
```
```
In drivers/char/random.c (ffffffff81a949e2)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81b087c0)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_activate
```
```
In drivers/base/devcoredump.c (ffffffff81b28e73)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b7d92f)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff81b93f34)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff81b9db37)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff81bac53d)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-sata.c (ffffffff81bbef81)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff81c9f4bd)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff81ca6bdb)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/edac/edac_device.c (ffffffff81d21d25)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff81d24515)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81d251b5)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d784f4)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (ffffffff81d7df1d)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_suspend_device
```
```
In drivers/devfreq/devfreq-event.c (ffffffff81d81e29)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff81d84bb2)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffffffff81da71df)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_realloc
```
```
In net/core/neighbour.c (ffffffff81ddbccf)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/netpoll.c (ffffffff81e12ec2)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff81e492a5)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_alloc_elem
```
```
In net/ipv4/ip_fragment.c (ffffffff81e96ff0)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff81e9b8bf)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81edd3db)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/xfrm/xfrm_state.c (ffffffff81f37f9e)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/ipv6/ip6_output.c (ffffffff81f57133)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
```
```
In net/ipv6/route.c (ffffffff81f6c90a)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_gc
```
```
In net/ipv6/raw.c (ffffffff81f8dd33)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81fc938f)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff81fda4c6)
Location: include/linux/atomic/atomic-instrumented.h:195
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
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
In arch/x86/events/core.c (ffffffff81006d2f)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81025b59)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8213e7ff)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810d6e1e)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/panic.c (ffffffff810f63c9)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
```
```
In kernel/exit.c (ffffffff810fdf45)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - kernel/exit.c:make_task_dead
```
```
In kernel/sched/build_utility.c (ffffffff8118195b)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:build_overlap_sched_groups
```
```
In kernel/irq/spurious.c (ffffffff811abbfe)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff811b0f52)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_create
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
```
```
In kernel/audit.c (ffffffff8123efc9)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_start
```
```
In kernel/watchdog.c (ffffffff8125e47a)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/trace/ftrace.c (ffffffff8126b310)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
```
```
In kernel/trace/trace.c (ffffffff81289a80)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff8128f89a)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/trace/trace_functions.c (ffffffff8129173d)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81292781)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8129c309)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff812a61a4)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812aed28)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
```
```
In kernel/events/callchain.c (ffffffff8137d548)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/watch_queue.c (ffffffff8138915e)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/vmscan.c (ffffffff813b5cd5)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_throttle
```
```
In mm/zswap.c (ffffffff8143533c)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/kfence/core.c (ffffffff8146590e)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - mm/kfence/core.c:__kfence_alloc
```
```
In fs/inode.c (ffffffff814d6425)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - fs/inode.c:ihold
```
```
In fs/notify/notification.c (ffffffff815136b5)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/coredump.c (ffffffff8155072f)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/kernfs/inode.c (ffffffff81580d05)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/devpts/inode.c (ffffffff8158e375)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/mballoc.c (ffffffff815c963d)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ecryptfs/main.c (ffffffff81643e05)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffffffff816a4a5a)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffffffff81706c66)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_learning_profile
```
```
In block/blk-crypto-profile.c (ffffffff817c3979)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
```
```
In io_uring/cancel.c (ffffffff817dfa12)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - io_uring/cancel.c:io_sync_cancel
  - io_uring/cancel.c:io_sync_cancel
  - io_uring/cancel.c:io_async_cancel
```
```
In lib/percpu-refcount.c (ffffffff81818078)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81907e5a)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
```
```
In drivers/pci/pci.c (ffffffff81926917)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a2f8de)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff81a8b6bf)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff81a91517)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_deassert
  - drivers/reset/core.c:reset_control_reset
```
```
In drivers/char/random.c (ffffffff81ae0202)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81b567f0)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_activate
```
```
In drivers/base/devcoredump.c (ffffffff81b79023)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd16cf)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff81bea486)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff81bf4157)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff81c036cd)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-sata.c (ffffffff81c16c31)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff81d067fd)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff81d0e31b)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/edac/edac_device.c (ffffffff81d8af25)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff81d8d725)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81d8e3d5)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de6434)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (ffffffff81dec29d)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_suspend_device
```
```
In drivers/devfreq/devfreq-event.c (ffffffff81df01e9)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
```
```
In net/core/skbuff.c (ffffffff81e1928f)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_realloc
```
```
In net/core/neighbour.c (ffffffff81e4ca1f)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/netpoll.c (ffffffff81e867ec)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff81ea49c5)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_alloc_elem
```
```
In net/ipv4/ip_fragment.c (ffffffff81ef57e1)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff81efa05d)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81f3c629)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9798e)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/ipv6/ip6_output.c (ffffffff81fb6a6a)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
```
```
In net/ipv6/route.c (ffffffff81fcc9cc)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_gc
```
```
In net/ipv6/raw.c (ffffffff81fee51d)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff82029cf9)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff8205618a)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
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
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff8102bcb9)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff822207ef)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810df67d)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/panic.c (ffffffff810ff779)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
```
```
In kernel/exit.c (ffffffff81106bf5)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - kernel/exit.c:make_task_dead
```
```
In kernel/sched/build_utility.c (ffffffff8119023a)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:build_overlap_sched_groups
```
```
In kernel/irq/spurious.c (ffffffff811bb7fe)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff811c0cd2)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_create
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
```
```
In kernel/audit.c (ffffffff81258e31)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_start
```
```
In kernel/watchdog.c (ffffffff812783ba)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/trace/ftrace.c (ffffffff812857c0)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
```
```
In kernel/trace/trace.c (ffffffff812a4e00)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff812aadfa)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/trace/trace_functions.c (ffffffff812acd4d)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812ade67)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
```
```
In kernel/trace/trace_functions_graph.c (ffffffff812b79e9)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff812c1cc4)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812cb248)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
```
```
In kernel/events/core.c (ffffffff81394c47)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
```
```
In kernel/events/callchain.c (ffffffff813a67a8)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/watch_queue.c (ffffffff813b2bae)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/vmscan.c (ffffffff813deb95)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_throttle
```
```
In mm/zswap.c (ffffffff8146e42e)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/kfence/core.c (ffffffff81494bee)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - mm/kfence/core.c:__kfence_alloc
```
```
In fs/inode.c (ffffffff815087f5)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - fs/inode.c:ihold
```
```
In fs/notify/notification.c (ffffffff81547b45)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/coredump.c (ffffffff815865bf)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/kernfs/inode.c (ffffffff815b977a)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/devpts/inode.c (ffffffff815c70a5)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/mballoc.c (ffffffff81602411)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ecryptfs/main.c (ffffffff8167d395)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffffffff816e14ba)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffffffff81744706)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_learning_profile
```
```
In block/bdev.c (ffffffff817a8480)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - block/bdev.c:bdev_freeze
```
```
In block/blk-crypto-profile.c (ffffffff81808609)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
```
```
In io_uring/cancel.c (ffffffff81823ea2)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - io_uring/cancel.c:io_sync_cancel
  - io_uring/cancel.c:io_sync_cancel
  - io_uring/cancel.c:io_async_cancel
```
```
In lib/percpu-refcount.c (ffffffff8185d378)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8194f66c)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
```
```
In drivers/pci/pci.c (ffffffff8196f0b7)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7ac1e)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff81adde45)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/regulator/event.c (ffffffff81ae254e)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - drivers/regulator/event.c:reg_generate_netlink_event
```
```
In drivers/reset/core.c (ffffffff81ae3e87)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_deassert
  - drivers/reset/core.c:reset_control_reset
```
```
In drivers/char/random.c (ffffffff81b33602)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81baede0)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_activate
```
```
In drivers/base/devcoredump.c (ffffffff81bccf0f)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c2633f)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff81c3faa6)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff81c49a97)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff81c58e8d)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-sata.c (ffffffff81c6b3fb)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_sas_port_alloc
```
```
In drivers/input/serio/serio.c (ffffffff81dbc42d)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff81dc3f6a)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/edac/edac_device.c (ffffffff81e427a5)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff81e44fd5)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81e45cb5)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9c614)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (ffffffff81ea25ed)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_suspend_device
```
```
In drivers/devfreq/devfreq-event.c (ffffffff81ea67d8)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
```
```
In net/core/skbuff.c (ffffffff81ed671f)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_realloc
```
```
In net/core/neighbour.c (ffffffff81f0b72f)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/netpoll.c (ffffffff81f487f9)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff81f673e5)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_alloc_elem
```
```
In net/ipv4/ip_fragment.c (ffffffff81fb9791)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff81fbdd5c)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
```
```
In net/ipv4/raw.c (ffffffff82002758)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/xfrm/xfrm_state.c (ffffffff82064cfe)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/ipv6/ip6_output.c (ffffffff82083ce8)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
```
```
In net/ipv6/route.c (ffffffff8209a1ac)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_gc
```
```
In net/ipv6/raw.c (ffffffff820bc0fd)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff820f97cd)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff82128a0a)
Location: include/linux/atomic/atomic-instrumented.h:450
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
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
In arch/arm64/kernel/insn.c (ffff800010da79a0)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - arch/arm64/kernel/insn.c:aarch64_insn_patch_text_cb
```
```
In arch/arm64/kernel/cpu_errata.c (ffff80001009890c)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In virt/kvm/arm/arm.c (ffff8000100c5770)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:init_hyp_mode
```
```
In kernel/signal.c (ffff80001010b45c)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sched/topology.c (ffff80001015c258)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/autogroup.c (ffff80001015f0fc)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/irq/spurious.c (ffff80001017d078)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffff800010183f5c)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/audit.c (ffff8000101ec490)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/trace/ftrace.c (ffff800010210ea8)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In kernel/trace/trace.c (ffff80001022a120)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In kernel/trace/tracing_map.c (ffff80001022e1e0)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In kernel/trace/trace_functions.c (ffff80001023013c)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffff8000102306f4)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffff8000102333c4)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffff80001023b334)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffff800010242930)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In kernel/bpf/syscall.c (ffff8000102600c8)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_inc
```
```
In kernel/bpf/hashtab.c (ffff8000102783ac)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffff8000102a3564)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (ffff8000102aa0f0)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In mm/rmap.c (ffff80001030b680)
Location: include/linux/atomic-fallback.h:282
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
In mm/zswap.c (ffff80001032b210)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/memcontrol.c (ffff800010369654)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In fs/inode.c (ffff8000103ac66c)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In fs/notify/notification.c (ffff8000103e88a0)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/io_uring.c (ffff800010401320)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In fs/coredump.c (ffff800010428654)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/devpts/inode.c (ffff80001045eac8)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ecryptfs/main.c (ffff8000104f5160)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffff800010546ce0)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffff800010596c38)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In drivers/pci/pci.c (ffff8000106ea840)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_find_domain_nr
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffff8000107af978)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/dma/of-dma.c (ffff8000107ff878)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/regulator/core.c (ffff800010847bac)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffff80001084cf1c)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/tty/serial/msm_serial.c (ffff8000108a1d8c)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_serial_probe
```
```
In drivers/iommu/arm-smmu.c (ffff8000108d1518)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_attach_dev
```
```
In drivers/base/power/wakeup.c (ffff800010903cf8)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/base/devcoredump.c (ffff80001091f39c)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/mfd/mfd-core.c (ffff800010940840)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/scsi/scsi_lib.c (ffff800010978b84)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffff8000109879b0)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffff8000109913dc)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffff80001099ecc0)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-scsi.c (ffff8000109a3738)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/input/serio/serio.c (ffff800010a92940)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffff800010a979e8)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/power/reset/vexpress-poweroff.c (ffff800010aca3d0)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/power/reset/vexpress-poweroff.c:_vexpress_register_restart_handler
```
```
In drivers/edac/edac_device.c (ffff800010b11608)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffff800010b137e8)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffff800010b1410c)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/firmware/arm_sdei.c (ffff800010b4bde0)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/firmware/arm_sdei.c:_local_event_register
  - drivers/firmware/arm_sdei.c:_local_event_unregister
  - drivers/firmware/arm_sdei.c:_ipi_event_disable
  - drivers/firmware/arm_sdei.c:_local_event_enable
```
```
In drivers/firmware/arm_scmi/clock.c (ffff800010b57d54)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_rate_set
```
```
In drivers/remoteproc/remoteproc_core.c (ffff800010b8104c)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (ffff800010b86438)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffff800010b87170)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/extcon/extcon.c (ffff800010b88cb4)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffff800010bb552c)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/neighbour.c (ffff800010be8270)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/page_pool.c (ffff800010c0c8b4)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
```
```
In net/core/netpoll.c (ffff800010c1170c)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffff800010c20e04)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (ffff800010c310d0)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/ip_fragment.c (ffff800010c5f97c)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/xfrm/xfrm_state.c (ffff800010ce36a8)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/packet/af_packet.c (ffff800010d5aba8)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffff800010d6bbdc)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
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
In kernel/signal.c (c0363d30)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sched/topology.c (c03a8c60)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/autogroup.c (c03ab9a8)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/irq/spurious.c (c03cdb34)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (c03d317c)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/audit.c (c042bff0)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/trace/ftrace.c (c044f594)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:profile_graph_entry
```
```
In kernel/trace/trace.c (c04677f0)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In kernel/trace/trace_functions.c (c046b6d4)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (c046c718)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (c046f160)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (c0475a20)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (c047dabc)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In kernel/bpf/syscall.c (c04932d4)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In kernel/bpf/hashtab.c (c04aa44c)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/core.c (c04cea78)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
```
```
In kernel/events/callchain.c (c04d2dec)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (c04d81a8)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In mm/workingset.c (c0513914)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (c05261dc)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/zswap.c (c0541480)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In fs/super.c (c056f174)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/inode.c (c058d78c)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In fs/notify/notification.c (c05c0060)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/io_uring.c (c05d2928)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In fs/coredump.c (c05f1330)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/devpts/inode.c (c061f56c)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ecryptfs/main.c (c06b2a34)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (c06fc688)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (c0747ce8)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In drivers/pci/pci.c (c0885734)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_find_domain_nr
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/dma/of-dma.c (c0920098)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/regulator/core.c (c0951484)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (c0958db0)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/tty/serial/msm_serial.c (c099b380)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_serial_probe
```
```
In drivers/base/power/wakeup.c (c09edde4)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_report_event
```
```
In drivers/base/devcoredump.c (c0a045f4)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/mfd/mfd-core.c (c0a295f8)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/scsi/scsi_lib.c (c0a4c9a0)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (c0a597cc)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (c0a60cb4)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (c0a6f370)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-scsi.c (c0a73fb0)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/input/serio/serio.c (c0b75d3c)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (c0b784c8)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/power/reset/vexpress-poweroff.c (c0bab1b4)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/power/reset/vexpress-poweroff.c:_vexpress_register_restart_handler
```
```
In drivers/edac/edac_device.c (c0bef100)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (c0bf11b8)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (c0bf1f70)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/cpufreq/omap-cpufreq.c (c0c007dc)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/cpufreq/omap-cpufreq.c:omap_cpu_init
```
```
In drivers/cpuidle/coupled.c (c0c05358)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/cpuidle/coupled.c:cpuidle_enter_state_coupled
  - drivers/cpuidle/coupled.c:cpuidle_coupled_parallel_barrier
```
```
In drivers/firmware/arm_scmi/clock.c (c0c38c94)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_rate_set
```
```
In drivers/remoteproc/remoteproc_core.c (c0c6465c)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (c0c687c0)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (c0c6a094)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/extcon/extcon.c (c0c6dba0)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (c0cd25f4)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/neighbour.c (c0d01224)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/page_pool.c (c0d24aa0)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
```
```
In net/core/netpoll.c (c0d29480)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (c0d386dc)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (c0d485d4)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/ip_fragment.c (c0d6e9f8)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/xfrm/xfrm_state.c (c0dead2c)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/unix/scm.c (c0dfbda4)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
```
```
In net/packet/af_packet.c (c0e5a2f8)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (c0e69ca0)
Location: include/linux/atomic-fallback.h:282
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
In kernel/signal.c (c000000000151f78)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sched/topology.c (c0000000001b09f8)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/autogroup.c (c0000000001b44ac)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/irq/spurious.c (c0000000001d7b00)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (c0000000001de654)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/audit.c (c00000000025ddb8)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/trace/ftrace.c (c00000000028f900)
Location: include/linux/atomic-fallback.h:341
Inline: True
```
```
In kernel/trace/trace.c (c0000000002b1d14)
Location: include/linux/atomic-fallback.h:341
Inline: True
```
```
In kernel/trace/tracing_map.c (c0000000002b7534)
Location: include/linux/atomic-fallback.h:341
Inline: True
```
```
In kernel/trace/trace_functions.c (c0000000002b9528)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (c0000000002badc0)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (c0000000002be320)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (c0000000002c5944)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (c0000000002d5038)
Location: include/linux/atomic-fallback.h:341
Inline: True
```
```
In kernel/bpf/syscall.c (c000000000304b9c)
Location: include/linux/atomic-fallback.h:341
Inline: True
```
```
In kernel/bpf/hashtab.c (c000000000320648)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (c000000000355aa0)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (c00000000035c268)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In mm/rmap.c (c0000000003db804)
Location: include/linux/atomic-fallback.h:341
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
In mm/zswap.c (c000000000403238)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/memcontrol.c (c000000000457e7c)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/memremap.c (c00000000046df30)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/inode.c (c0000000004a650c)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - fs/inode.c:ihold
```
```
In fs/notify/notification.c (c0000000004ef210)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/io_uring.c (c000000000509dd4)
Location: include/linux/atomic-fallback.h:341
Inline: True
```
```
In fs/coredump.c (c0000000005388dc)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/devpts/inode.c (c00000000057ac48)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ecryptfs/main.c (c000000000635aa8)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (c00000000069d680)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (c00000000070cc74)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In drivers/pci/pci.c (c000000000863c54)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/dma/of-dma.c (c0000000008c9938)
Location: include/linux/atomic-fallback.h:341
Inline: True
```
```
In drivers/regulator/core.c (c0000000008e4194)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (c0000000008eaeb4)
Location: include/linux/atomic-fallback.h:341
Inline: True
```
```
In drivers/tty/hvc/hvsi_lib.c (c00000000091d460)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - drivers/tty/hvc/hvsi_lib.c:hvsilib_write_mctrl
  - drivers/tty/hvc/hvsi_lib.c:hvsilib_put_chars
  - drivers/tty/hvc/hvsi_lib.c:hvsi_get_packet
  - drivers/tty/hvc/hvsi_lib.c:hvsi_send_close
  - drivers/tty/hvc/hvsi_lib.c:hvsi_start_handshake
```
```
In drivers/tty/hvc/hvsi.c (c00000000091e6dc)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - drivers/tty/hvc/hvsi.c:hvsi_close_protocol
  - drivers/tty/hvc/hvsi.c:hvsi_put_chars
  - drivers/tty/hvc/hvsi.c:hvsi_set_mctrl
  - drivers/tty/hvc/hvsi.c:hvsi_query
  - drivers/tty/hvc/hvsi.c:hvsi_interrupt
```
```
In drivers/base/power/wakeup.c (c0000000009a2a84)
Location: include/linux/atomic-fallback.h:341
Inline: True
```
```
In drivers/base/devcoredump.c (c0000000009c4718)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/mfd/mfd-core.c (c0000000009e8810)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/scsi/scsi_lib.c (c000000000a33200)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/scsi_transport_srp.c (c000000000a43290)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - drivers/scsi/scsi_transport_srp.c:srp_rport_add
```
```
In drivers/scsi/sd.c (c000000000a46f74)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (c000000000a507f0)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (c000000000a63150)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-scsi.c (c000000000a68bd4)
Location: include/linux/atomic-fallback.h:341
Inline: True
```
```
In drivers/input/serio/serio.c (c000000000b6e438)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (c000000000b77294)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/edac/edac_device.c (c000000000c04a00)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (c000000000c07b80)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (c000000000c08f2c)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/remoteproc/remoteproc_core.c (c000000000c5db20)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (c000000000c63a24)
Location: include/linux/atomic-fallback.h:341
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (c000000000c65f70)
Location: include/linux/atomic-fallback.h:341
Inline: True
```
```
In drivers/extcon/extcon.c (c000000000c68e30)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (c000000000c8c674)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/neighbour.c (c000000000cca49c)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/page_pool.c (c000000000cf79ec)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
```
```
In net/core/netpoll.c (c000000000cfe488)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (c000000000d12fa0)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (c000000000d2b358)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/ip_fragment.c (c000000000d61f40)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/xfrm/xfrm_state.c (c000000000e044c0)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/packet/af_packet.c (c000000000e93654)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (c000000000ea91bc)
Location: include/linux/atomic-fallback.h:341
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
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
In arch/riscv/kernel/perf_event.c (ffffffe0000b973a)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - arch/riscv/kernel/perf_event.c:riscv_event_init
```
```
In kernel/signal.c (ffffffe0000cd4c4)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sched/topology.c (ffffffe000101316)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/sched/autogroup.c (ffffffe0001033fa)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/irq/spurious.c (ffffffe0001161c8)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffe00011b0de)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/audit.c (ffffffe000160a9c)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/trace/ftrace.c (ffffffe00017105c)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In kernel/trace/trace.c (ffffffe000184aa6)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_panic_handler
```
```
In kernel/trace/trace_functions.c (ffffffe000187a66)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffe00018908a)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffe00018a6f8)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffe00018fce8)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffe000197708)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/bpf/syscall.c (ffffffe00019fde0)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
```
```
In kernel/bpf/hashtab.c (ffffffe0001afbb4)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffffffe0001d1c6e)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (ffffffe0001d2fde)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In mm/rmap.c (ffffffe000214fde)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/zswap.c (ffffffe000229de0)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In fs/inode.c (ffffffe0002718e2)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In fs/notify/notification.c (ffffffe00029d408)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/io_uring.c (ffffffe0002acd02)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In fs/coredump.c (ffffffe0002c68bc)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/devpts/inode.c (ffffffe0002ee710)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ecryptfs/main.c (ffffffe0003641d2)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffffffe0003a2326)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffffffe0003e3972)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In drivers/pci/pci.c (ffffffe0004c08b0)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_find_domain_nr
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/dma/of-dma.c (ffffffe000517a54)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/regulator/core.c (ffffffe000527fd2)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffe00052c1d6)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffe00059e376)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/mfd/mfd-core.c (ffffffe0005b3a34)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005e0428)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffffffe0005eb9ae)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffe0005f2c2e)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffe0005fec02)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-scsi.c (ffffffe0005ff93a)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_port_init
```
```
In drivers/input/serio/serio.c (ffffffe0006a4c2c)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffe0006a8950)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/edac/edac_device.c (ffffffe0006fdc2e)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffe0006ffc3c)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffe00070088a)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/devfreq/devfreq.c (ffffffe00072eda4)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffffffe00073007a)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffe000731d2c)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffffffe000745580)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/neighbour.c (ffffffe00076c63e)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/page_pool.c (ffffffe000789886)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
```
```
In net/core/netpoll.c (ffffffe00078d93c)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffe000799bfc)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (ffffffe0007a7a4e)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/ip_fragment.c (ffffffe0007c778a)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/xfrm/xfrm_state.c (ffffffe00083067c)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/packet/af_packet.c (ffffffe00088f678)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffe00089e1b6)
Location: include/linux/atomic-fallback.h:282
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff8100640e)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff810177f7)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e6be)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108b78a)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/signal.c (ffffffff810a9e14)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sched/topology.c (ffffffff810f1215)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/autogroup.c (ffffffff810f3abf)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/irq/spurious.c (ffffffff811124a1)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff81116bd2)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/audit.c (ffffffff8116fa2a)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/trace/ftrace.c (ffffffff81190bbe)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811a5840)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff811a904e)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In kernel/trace/trace_functions.c (ffffffff811aa2b0)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811ab0c8)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811adb0f)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff811b2dbb)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811bafc0)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811d6ed5)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811ec2fd)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffffffff81210fba)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (ffffffff81215c70)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In mm/zswap.c (ffffffff81286b75)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/memcontrol.c (ffffffff812bedd6)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/memremap.c (ffffffff812cccfc)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/inode.c (ffffffff812f4f25)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In fs/notify/notification.c (ffffffff81325265)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/io_uring.c (ffffffff81338c09)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In fs/coredump.c (ffffffff8135a5f4)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/devpts/inode.c (ffffffff81385475)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ecryptfs/main.c (ffffffff8140c255)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffffffff81452a79)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffffffff814994ff)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In drivers/pci/pci.c (ffffffff81578e15)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/regulator/core.c (ffffffff816438db)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff8164705f)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff816d9634)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff816ef406)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/mfd/mfd-core.c (ffffffff81701e5a)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/scsi/scsi_lib.c (ffffffff81729138)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffffffff81735940)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff8173e727)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff817596fe)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-scsi.c (ffffffff8175e791)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff8180750b)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff8180d166)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/edac/edac_device.c (ffffffff8185eb75)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff81860ae5)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff818615a5)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff818961dc)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (ffffffff8189a1d8)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffffffff8189bb1f)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff8189d654)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffffffff818bb0e4)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/neighbour.c (ffffffff818e6cf7)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/page_pool.c (ffffffff81906dab)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
```
```
In net/core/netpoll.c (ffffffff8190af56)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff819197cf)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (ffffffff819298bd)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/ip_fragment.c (ffffffff8194ec44)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/xfrm/xfrm_state.c (ffffffff819c3e8e)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/packet/af_packet.c (ffffffff81a2a0a1)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff81a3acde)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
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
In arch/x86/events/core.c (ffffffff81004b8e)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016c27)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103db8e)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8107a2ba)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/signal.c (ffffffff810987c4)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sched/topology.c (ffffffff810e1285)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/autogroup.c (ffffffff810e3bef)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/irq/spurious.c (ffffffff811031c1)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff811078c2)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/audit.c (ffffffff81162bca)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/trace/ftrace.c (ffffffff81183743)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811986b0)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff8119bfce)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In kernel/trace/trace_functions.c (ffffffff8119d215)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8119e3d8)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811a0951)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff811a5bbb)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811adda0)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811c9c95)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811df08d)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/core.c (ffffffff811fb3ab)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/callchain.c (ffffffff81203d4a)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (ffffffff812089d0)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In mm/zswap.c (ffffffff812789d5)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/memcontrol.c (ffffffff812afec6)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/memremap.c (ffffffff812bdb6c)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/inode.c (ffffffff812e5b45)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In fs/notify/notification.c (ffffffff81315e05)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/io_uring.c (ffffffff81329939)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In fs/coredump.c (ffffffff8134b29e)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/devpts/inode.c (ffffffff81375f05)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ecryptfs/main.c (ffffffff813fccd5)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffffffff814434c9)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffffffff81489f1f)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In drivers/pci/pci.c (ffffffff81567555)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/regulator/core.c (ffffffff81623d5b)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff816274bf)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff816b3c6d)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffffffff816d5c6a)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/scsi/scsi_lib.c (ffffffff81702568)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffffffff817175e0)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff817203c7)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff8173959e)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-scsi.c (ffffffff8173e631)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff817cec1b)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff817d48d6)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/edac/edac_device.c (ffffffff81826145)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff818280b5)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81828b55)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/hv/channel.c (ffffffff81850fc5)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/hv/channel.c:vmbus_establish_gpadl
```
```
In drivers/devfreq/devfreq.c (ffffffff818576a8)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffffffff81858fef)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In net/core/skbuff.c (ffffffff81875024)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/neighbour.c (ffffffff818a0b37)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/page_pool.c (ffffffff818c0bbb)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
```
```
In net/core/netpoll.c (ffffffff818c4cf1)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff818d357f)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (ffffffff818e366d)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/ip_fragment.c (ffffffff81908734)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/xfrm/xfrm_state.c (ffffffff81980c7e)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/packet/af_packet.c (ffffffff819e7291)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff819f78fe)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
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
In arch/x86/events/core.c (ffffffff810063ce)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff810177b7)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e50e)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108b73a)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/signal.c (ffffffff810a9374)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sched/topology.c (ffffffff810ee345)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/autogroup.c (ffffffff810f0c0f)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/irq/spurious.c (ffffffff81110391)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff81114ac2)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/audit.c (ffffffff8116d7fa)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/trace/ftrace.c (ffffffff8118e98e)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811a3610)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff811a6e1e)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In kernel/trace/trace_functions.c (ffffffff811a8080)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a8e98)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811ab8df)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff811b0b8b)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811b8d90)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811d4ca5)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811ea0cd)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffffffff8120ed5a)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (ffffffff81213a10)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In mm/zswap.c (ffffffff81284985)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/memcontrol.c (ffffffff812bcbe6)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/memremap.c (ffffffff812cab0c)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/inode.c (ffffffff812f2d35)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In fs/notify/notification.c (ffffffff81322d35)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/io_uring.c (ffffffff813366d9)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In fs/coredump.c (ffffffff813580c4)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/devpts/inode.c (ffffffff81382f45)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ecryptfs/main.c (ffffffff814095d5)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffffffff8144eb19)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffffffff8149559f)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In drivers/pci/pci.c (ffffffff81578645)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff816376bd)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff81671cbb)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff8167541f)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81706f6d)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff8171cae6)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/mfd/mfd-core.c (ffffffff8173727a)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/scsi/scsi_lib.c (ffffffff81767f08)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffffffff817760d0)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff8177eeb7)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff8178946e)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-scsi.c (ffffffff8178e521)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff818465bb)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff8184c2e6)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/edac/edac_device.c (ffffffff818ae1a5)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff818b0115)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff818b0bd5)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/devfreq/devfreq.c (ffffffff818e98c8)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffffffff818eb20f)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff818ecd44)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffffffff8190c0e4)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/neighbour.c (ffffffff81937d27)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/page_pool.c (ffffffff81957ddb)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
```
```
In net/core/netpoll.c (ffffffff8195bf86)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff8196a95f)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (ffffffff8197aa4d)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/netfilter/nfnetlink_log.c (ffffffff8199c3a1)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_log.c:__build_packet_message
```
```
In net/ipv4/ip_fragment.c (ffffffff819b9414)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2e90e)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/packet/af_packet.c (ffffffff81a95c51)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff81aa6b8e)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
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
In arch/x86/events/core.c (ffffffff8100652e)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff810179f7)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104f94e)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108da9a)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/signal.c (ffffffff810b1595)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sched/topology.c (ffffffff810f9385)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/autogroup.c (ffffffff810fbc9f)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/irq/spurious.c (ffffffff8111b911)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff811200f2)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/audit.c (ffffffff8117afef)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/trace/ftrace.c (ffffffff8119c51e)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811b13a0)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff811b4bbe)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In kernel/trace/trace_functions.c (ffffffff811b5e30)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b6cd8)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811b97af)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff811bec1b)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811c6e30)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811e2fd5)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811f84ad)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffffffff8121dc6a)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (ffffffff81222b90)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In mm/zswap.c (ffffffff81294625)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/memcontrol.c (ffffffff812cd3d6)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/memremap.c (ffffffff812db82c)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/inode.c (ffffffff81304445)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In fs/notify/notification.c (ffffffff81334a75)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/io_uring.c (ffffffff813497a9)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In fs/coredump.c (ffffffff8136b7f6)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/devpts/inode.c (ffffffff81396a65)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ecryptfs/main.c (ffffffff8141f295)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffffffff81465ef9)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffffffff814ad5ff)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In drivers/pci/pci.c (ffffffff81592b05)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff816519cd)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff8168c31b)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff8168fa7f)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff8172199d)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff81737e46)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/mfd/mfd-core.c (ffffffff817526ba)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/scsi/scsi_lib.c (ffffffff81783647)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffffffff8178feb0)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff81798cb7)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff817a32be)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-scsi.c (ffffffff817a8371)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff81861bcb)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff81867546)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/edac/edac_device.c (ffffffff818ca435)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff818cc3a5)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff818cce65)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff8190693c)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (ffffffff8190a948)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffffffff8190c28f)
Location: include/linux/atomic-fallback.h:282
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff8190ddc4)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffffffff8192d214)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/neighbour.c (ffffffff81959505)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/page_pool.c (ffffffff81979ebb)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
```
```
In net/core/netpoll.c (ffffffff8197e366)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff8198cdcf)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (ffffffff8199cf7d)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/ip_fragment.c (ffffffff819c2d04)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3a10e)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/packet/af_packet.c (ffffffff81aa2891)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff81ab2f2e)
Location: include/linux/atomic-fallback.h:282
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
```
</details>
</li>
</ul>

## Differences
