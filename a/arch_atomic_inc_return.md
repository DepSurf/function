# Function: <code>arch_atomic_inc_return</code>

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
In arch/x86/events/core.c (ffffffff8100741e)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101938b)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81051ec1)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81093de8)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:ioremap_trace_core
```
```
In kernel/signal.c (ffffffff810b78f8)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sched/topology.c (ffffffff81101509)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:init_overlap_sched_group
```
```
In kernel/sched/autogroup.c (ffffffff81104abf)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/irq/spurious.c (ffffffff81125c25)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:misrouted_irq
```
```
In kernel/irq/irqdomain.c (ffffffff81129e34)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/audit.c (ffffffff8118a16d)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/trace/ftrace.c (ffffffff811ad580)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_profile_alloc
```
```
In kernel/trace/trace.c (ffffffff811c4f30)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff811c88c0)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:get_free_elt
```
```
In kernel/trace/trace_functions.c (ffffffff811ca412)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811cafa8)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811ce21a)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff811d5914)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811dcc08)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff81217e93)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffffffff812446aa)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/watch_queue.c (ffffffff8124c828)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/zswap.c (ffffffff812c1245)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/memremap.c (ffffffff8130a377)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/inode.c (ffffffff813351a5)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
```
```
In fs/notify/notification.c (ffffffff81366a25)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/io_uring.c (ffffffff81385da0)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_cancel_files
  - fs/io_uring.c:__io_cqring_fill_event
  - fs/io_uring.c:io_cqring_overflow_flush
```
```
In fs/coredump.c (ffffffff813a7fe9)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/kernfs/inode.c (ffffffff813cd3e3)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
```
```
In fs/devpts/inode.c (ffffffff813d82e5)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ecryptfs/main.c (ffffffff81461e15)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffffffff814ada10)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffffffff814fb040)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In block/keyslot-manager.c (ffffffff8158121a)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
```
```
In drivers/pci/pci.c (ffffffff8162b4d7)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f0d7d)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff8172f55c)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff817326cf)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff817ce624)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_activate
```
```
In drivers/base/devcoredump.c (ffffffff817e5e56)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/scsi/scsi_lib.c (ffffffff8183598d)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff818430f1)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff8184e637)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff818587fe)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-sata.c (ffffffff81868051)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff819242db)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff81929936)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/edac/edac_device.c (ffffffff81989505)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff8198b4c5)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff8198bef5)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_main_kobj_setup
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c9e4c)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (ffffffff819cfa8e)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffffffff819d1070)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff819d2f0f)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffffffff819ede23)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/neighbour.c (ffffffff81a16f95)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/page_pool.c (ffffffff81a3a86b)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release_page
```
```
In net/core/netpoll.c (ffffffff81a3ecee)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff81a4db85)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_alloc_elem
```
```
In net/core/bpf_sk_storage.c (ffffffff81a61767)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/ip_fragment.c (ffffffff81a991e8)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1653e)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/packet/af_packet.c (ffffffff81b865b1)
Location: include/linux/atomic-arch-fallback.h:284
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff81b970de)
Location: include/linux/atomic-arch-fallback.h:284
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
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff810186ea)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81050fe1)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81093338)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:ioremap_trace_core
```
```
In kernel/signal.c (ffffffff810b2b8f)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sched/topology.c (ffffffff81100069)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:init_overlap_sched_group
```
```
In kernel/sched/autogroup.c (ffffffff8110313f)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/irq/spurious.c (ffffffff81121935)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:misrouted_irq
```
```
In kernel/irq/irqdomain.c (ffffffff811256fa)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/audit.c (ffffffff8118747d)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/trace/ftrace.c (ffffffff811aae90)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_profile_alloc
```
```
In kernel/trace/trace.c (ffffffff811c2b70)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff811c5fa0)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:get_free_elt
```
```
In kernel/trace/trace_functions.c (ffffffff811c7a82)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c8688)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811cb6fa)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff811d2be4)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811d9d38)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff8121a02e)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffffffff8124ec7a)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/watch_queue.c (ffffffff81256c68)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/zswap.c (ffffffff812ccd65)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In fs/inode.c (ffffffff81340b15)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
```
```
In fs/notify/notification.c (ffffffff81373d75)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/coredump.c (ffffffff813b9069)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/kernfs/inode.c (ffffffff813df013)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
```
```
In fs/devpts/inode.c (ffffffff813e9f85)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/mballoc.c (ffffffff8141c38e)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ecryptfs/main.c (ffffffff8147d985)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffffffff814cb490)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffffffff81517f11)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In block/keyslot-manager.c (ffffffff8159e24a)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8163b849)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
```
```
In drivers/pci/pci.c (ffffffff816511d7)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff8170e01d)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff8174c1a0)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff8174e81f)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff817e328c)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_activate
```
```
In drivers/base/devcoredump.c (ffffffff817faae6)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/scsi/scsi_lib.c (ffffffff818464ba)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff81857876)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff8185ea27)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff81868a5e)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-sata.c (ffffffff81876e61)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff8192c08b)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff81930f36)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/edac/edac_device.c (ffffffff8198d295)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff8198f0d5)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff8198fa25)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_main_kobj_setup
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819ca52c)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (ffffffff819cf7ae)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffffffff819d0d30)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff819d2aef)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffffffff819edac3)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/neighbour.c (ffffffff81a17285)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/page_pool.c (ffffffff81a3cd35)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release_page
```
```
In net/core/netpoll.c (ffffffff81a41a8e)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff81a538e5)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_alloc_elem
```
```
In net/ipv4/ip_fragment.c (ffffffff81aa3158)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/xfrm/xfrm_state.c (ffffffff81b2491e)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/packet/af_packet.c (ffffffff81b95ec8)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff81ba6d7e)
Location: include/linux/atomic-arch-fallback.h:354
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
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81019a0d)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81052d11)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81093d5e)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/signal.c (ffffffff810b41d2)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sched/topology.c (ffffffff8110213c)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/autogroup.c (ffffffff8110547f)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/irq/spurious.c (ffffffff81121de1)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff811259d2)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
```
```
In kernel/audit.c (ffffffff811883bd)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/trace/ftrace.c (ffffffff811acbdc)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811c3c10)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff811c7642)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/trace/trace_functions.c (ffffffff811c9300)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c991d)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811cca1f)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff811d3891)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811db298)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff8121d7d1)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffffffff8125358a)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/watch_queue.c (ffffffff8125b108)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/zswap.c (ffffffff812d3905)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In fs/inode.c (ffffffff81346f95)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
```
```
In fs/notify/notification.c (ffffffff8137a6d5)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/coredump.c (ffffffff813bffcb)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/kernfs/inode.c (ffffffff813e5cb1)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/devpts/inode.c (ffffffff813f0ac5)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/mballoc.c (ffffffff8142260c)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ecryptfs/main.c (ffffffff81483545)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffffffff814d1ac0)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffffffff8151e787)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In block/keyslot-manager.c (ffffffff815a501a)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
```
```
In lib/percpu-refcount.c (ffffffff815b4ffb)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8161f729)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
```
```
In drivers/pci/pci.c (ffffffff81633c15)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff816ef7bd)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff8172f9b0)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff8173233b)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff817c764c)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_activate
```
```
In drivers/base/devcoredump.c (ffffffff817df7f6)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182ac6f)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff8183a7d0)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff81841697)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff8184b489)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-sata.c (ffffffff81859651)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (ffffffff8188820c)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff8190f59b)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff819140a6)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/edac/edac_device.c (ffffffff81971955)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff81973725)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81974065)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819af53c)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (ffffffff819b48de)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffffffff819b5fdf)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff819b7d9f)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffffffff819d59a3)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_alloc
```
```
In net/core/neighbour.c (ffffffff819fdf60)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/page_pool.c (ffffffff81a23a75)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release_page
```
```
In net/core/netpoll.c (ffffffff81a26551)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff81a50dec)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/ipv4/ip_fragment.c (ffffffff81a8e16e)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1253e)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/packet/af_packet.c (ffffffff81b84da8)
Location: include/linux/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff81b95f0e)
Location: include/linux/atomic-arch-fallback.h:354
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
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101e72d)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105b211)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810a3b3e)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/sched/topology.c (ffffffff8111e6b9)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/autogroup.c (ffffffff811230ef)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/irq/spurious.c (ffffffff81142391)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff81146175)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
```
```
In kernel/audit.c (ffffffff811b08dd)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/trace/ftrace.c (ffffffff811d683c)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811eee80)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff811f2d73)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/trace/trace_functions.c (ffffffff811f4d2f)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811f53e7)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811f9169)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff81200711)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812088a8)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff812568a7)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffffffff8128eeca)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/watch_queue.c (ffffffff81296f08)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/zswap.c (ffffffff81319587)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/kfence/core.c (ffffffff8133c70c)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - mm/kfence/core.c:__kfence_alloc
```
```
In fs/inode.c (ffffffff81394355)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - fs/inode.c:ihold
```
```
In fs/notify/notification.c (ffffffff813c7355)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/coredump.c (ffffffff8140fdfb)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/kernfs/inode.c (ffffffff81437831)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/devpts/inode.c (ffffffff814429b5)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/mballoc.c (ffffffff81475d70)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ecryptfs/main.c (ffffffff814dacc5)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffffffff8152a840)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffffffff8157c8d7)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In block/keyslot-manager.c (ffffffff8160daba)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
```
```
In lib/percpu-refcount.c (ffffffff8161b356)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8168ecb9)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
```
```
In drivers/pci/pci.c (ffffffff816a3db7)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff8176981d)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff817af7ac)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff817b2b2e)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81851ca8)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_report_event
```
```
In drivers/base/devcoredump.c (ffffffff8186b27e)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b66ef)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff818c6e80)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff818ce327)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff818d889b)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-sata.c (ffffffff818e8201)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff819b03db)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff819b61c6)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/edac/edac_device.c (ffffffff81a1a605)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff81a1c425)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81a1cd65)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81a5de6c)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (ffffffff81a6341e)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffffffff81a64b1f)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff81a66c9f)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffffffff81a855d3)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_alloc
```
```
In net/core/neighbour.c (ffffffff81ab0063)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/netpoll.c (ffffffff81adb2cc)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff81b09e99)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/ipv4/ip_fragment.c (ffffffff81b4935e)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff81b4d795)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81b862cd)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd640e)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/ipv6/ip6_output.c (ffffffff81bf0b4f)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81c20a84)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81c524ef)
Location: include/linux/atomic/atomic-arch-fallback.h:354
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff81c62966)
Location: include/linux/atomic/atomic-arch-fallback.h:354
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
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81021259)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81f15a2f)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810b821e)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/sched/build_utility.c (ffffffff81144d6b)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:build_overlap_sched_groups
```
```
In kernel/irq/spurious.c (ffffffff81165eea)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff8116a539)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
```
```
In kernel/audit.c (ffffffff811e2ae9)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_start
```
```
In kernel/trace/ftrace.c (ffffffff8120b9d1)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
```
```
In kernel/trace/trace.c (ffffffff812272f0)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff8122c32a)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/trace/trace_functions.c (ffffffff8122de5d)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8122ec41)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
```
```
In kernel/trace/trace_functions_graph.c (ffffffff81232fe9)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff8123a90c)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81243e98)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff8129f211)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffffffff812e3de8)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/watch_queue.c (ffffffff812ed52c)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/vmscan.c (ffffffff81310d5a)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_throttle
```
```
In mm/zswap.c (ffffffff8138484c)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/kfence/core.c (ffffffff813af9b4)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - mm/kfence/core.c:__kfence_alloc
```
```
In fs/inode.c (ffffffff814160a5)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - fs/inode.c:ihold
```
```
In fs/notify/notification.c (ffffffff8144e735)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/coredump.c (ffffffff814857ca)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/kernfs/inode.c (ffffffff814b25a9)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/devpts/inode.c (ffffffff814be735)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/mballoc.c (ffffffff814f80ad)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ecryptfs/main.c (ffffffff81568645)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffffffff815c020f)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffffffff8161ade6)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In block/blk-mq-tag.c (ffffffff8168c76d)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/blk-crypto-profile.c (ffffffff816c2369)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
```
```
In io_uring/io_uring.c (ffffffff816d3841)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_async_cancel
```
```
In lib/percpu-refcount.c (ffffffff816e8b46)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff817aca30)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
```
```
In drivers/pci/pci.c (ffffffff817c6167)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff8189e1ce)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff818eab64)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff818ef657)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_deassert
  - drivers/reset/core.c:reset_control_reset
```
```
In drivers/base/power/wakeup.c (ffffffff819970e0)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_activate
```
```
In drivers/base/devcoredump.c (ffffffff819b3fdf)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/scsi/scsi_lib.c (ffffffff819ff32f)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff81a13b61)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff81a1c897)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff81a299fb)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-sata.c (ffffffff81a39ca1)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff81b0f12d)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff81b1576b)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/edac/edac_device.c (ffffffff81b83395)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff81b854d5)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81b85e35)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81bce044)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (ffffffff81bd227d)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_suspend_device
```
```
In drivers/devfreq/devfreq-event.c (ffffffff81bd5809)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff81bd81b3)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffffffff81bf838d)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_realloc
```
```
In net/core/neighbour.c (ffffffff81c28faf)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/netpoll.c (ffffffff81c5c7d2)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff81c90112)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/ipv4/ip_fragment.c (ffffffff81cd69ff)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff81cdb002)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81d16c1c)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6cb9e)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/ipv6/ip6_output.c (ffffffff81d89323)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
```
```
In net/ipv6/route.c (ffffffff81d9d9ca)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_gc
```
```
In net/ipv6/raw.c (ffffffff81dbd7f3)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81df457f)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff81e05246)
Location: include/linux/atomic/atomic-arch-fallback.h:438
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
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81025c39)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff820bd15f)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810d3a3e)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/panic.c (ffffffff810ea7e9)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
```
```
In kernel/exit.c (ffffffff810f1fc5)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - kernel/exit.c:make_task_dead
```
```
In kernel/sched/build_utility.c (ffffffff8117115b)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:build_overlap_sched_groups
```
```
In kernel/irq/spurious.c (ffffffff81199fda)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff8119f061)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_create
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
```
```
In kernel/audit.c (ffffffff812289c9)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_start
```
```
In kernel/trace/ftrace.c (ffffffff81254420)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
```
```
In kernel/trace/trace.c (ffffffff81272780)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff81277e5a)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/trace/trace_functions.c (ffffffff81279cfd)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8127ac61)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8127f779)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff812894bf)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81291ac8)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
```
```
In kernel/events/callchain.c (ffffffff8134c4f8)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/watch_queue.c (ffffffff813578fc)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/vmscan.c (ffffffff81384238)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_throttle
```
```
In mm/zswap.c (ffffffff8140247c)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/kfence/core.c (ffffffff8142ff7e)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - mm/kfence/core.c:__kfence_alloc
```
```
In fs/inode.c (ffffffff814a1115)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - fs/inode.c:ihold
```
```
In fs/notify/notification.c (ffffffff814dce55)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/coredump.c (ffffffff81518e2f)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/kernfs/inode.c (ffffffff81549129)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/devpts/inode.c (ffffffff815565b5)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/mballoc.c (ffffffff815926ab)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ecryptfs/main.c (ffffffff8160bf25)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffffffff8166c73f)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffffffff816ce006)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_learning_profile
```
```
In block/blk-mq-tag.c (ffffffff8174af28)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/blk-crypto-profile.c (ffffffff81783689)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
```
```
In io_uring/cancel.c (ffffffff8179e822)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - io_uring/cancel.c:io_sync_cancel
  - io_uring/cancel.c:io_sync_cancel
  - io_uring/cancel.c:io_async_cancel
```
```
In lib/percpu-refcount.c (ffffffff817d8b91)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c4d8a)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
```
```
In drivers/pci/pci.c (ffffffff818e34c7)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff819e71ce)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff81a415e4)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff81a47377)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_deassert
  - drivers/reset/core.c:reset_control_reset
```
```
In drivers/char/random.c (ffffffff81a949e2)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81b087c0)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_activate
```
```
In drivers/base/devcoredump.c (ffffffff81b28e73)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b7d92f)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff81b93f34)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff81b9db37)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff81bac53d)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-sata.c (ffffffff81bbef81)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff81c9f4bd)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff81ca6bdb)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/edac/edac_device.c (ffffffff81d21d25)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff81d24515)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81d251b5)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d784f4)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (ffffffff81d7df1d)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_suspend_device
```
```
In drivers/devfreq/devfreq-event.c (ffffffff81d81e29)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff81d84bb2)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffffffff81da71df)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_realloc
```
```
In net/core/neighbour.c (ffffffff81ddbccf)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/netpoll.c (ffffffff81e12ec2)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff81e492a5)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_alloc_elem
```
```
In net/ipv4/ip_fragment.c (ffffffff81e96ff0)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff81e9b8bf)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81edd3db)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/xfrm/xfrm_state.c (ffffffff81f37f9e)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/ipv6/ip6_output.c (ffffffff81f57133)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
```
```
In net/ipv6/route.c (ffffffff81f6c90a)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_gc
```
```
In net/ipv6/raw.c (ffffffff81f8dd33)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81fc938f)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff81fda4c6)
Location: include/linux/atomic/atomic-arch-fallback.h:438
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
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
