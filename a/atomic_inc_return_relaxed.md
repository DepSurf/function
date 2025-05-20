# Function: <code>atomic_inc_return_relaxed</code>

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
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81ad80cf)
Location: include/linux/atomic/atomic-instrumented.h:207
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release_page
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
In net/core/page_pool.c (ffffffff81c58e90)
Location: include/linux/atomic/atomic-instrumented.h:218
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release_page
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
In kernel/events/hw_breakpoint.c (ffffffff8134de5f)
Location: include/linux/atomic/atomic-instrumented.h:218
Inline: True
```
```
In mm/rmap.c (ffffffff813d7ce4)
Location: include/linux/atomic/atomic-instrumented.h:218
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_anon_rmap
```
```
In net/core/page_pool.c (ffffffff81e0edd0)
Location: include/linux/atomic/atomic-instrumented.h:218
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release_page
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
In kernel/events/hw_breakpoint.c (ffffffff8137ef07)
Location: include/linux/atomic/atomic-instrumented.h:503
Inline: True
```
```
In mm/rmap.c (ffffffff8140c79a)
Location: include/linux/atomic/atomic-instrumented.h:503
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_anon_rmap
```
```
In net/core/page_pool.c (ffffffff81e82590)
Location: include/linux/atomic/atomic-instrumented.h:503
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release_page
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
In kernel/events/hw_breakpoint.c (ffffffff813a8167)
Location: include/linux/atomic/atomic-instrumented.h:503
Inline: True
```
```
In mm/rmap.c (ffffffff8143900b)
Location: include/linux/atomic/atomic-instrumented.h:503
Inline: True
Inline callers:
  - mm/rmap.c:folio_add_file_rmap_ptes
  - mm/rmap.c:folio_add_anon_rmap_ptes
```
```
In net/core/page_pool.c (ffffffff81f4369e)
Location: include/linux/atomic/atomic-instrumented.h:503
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_return_page
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
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c094c854)
Location: include/linux/atomic-fallback.h:309
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_lock_dependent
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
In kernel/signal.c (c000000000151f7c)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sched/topology.c (c0000000001b09fc)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/autogroup.c (c0000000001b44b0)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/irq/spurious.c (c0000000001d7b04)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (c0000000001de658)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/audit.c (c00000000025ddbc)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/trace/ftrace.c (c00000000028f904)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
```
```
In kernel/trace/trace.c (c0000000002b1d18)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
```
```
In kernel/trace/tracing_map.c (c0000000002b7538)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
```
```
In kernel/trace/trace_functions.c (c0000000002b952c)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (c0000000002badc4)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (c0000000002be324)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (c0000000002c5948)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (c0000000002d503c)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
```
```
In kernel/bpf/syscall.c (c000000000304ba0)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
```
```
In kernel/bpf/hashtab.c (c00000000032064c)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (c000000000355aa4)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (c00000000035c26c)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In mm/rmap.c (c0000000003db808)
Location: arch/powerpc/include/asm/atomic.h:142
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
In mm/zswap.c (c00000000040323c)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/memcontrol.c (c000000000457e80)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/memremap.c (c00000000046df34)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/inode.c (c0000000004a6510)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - fs/inode.c:ihold
```
```
In fs/notify/notification.c (c0000000004ef214)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/io_uring.c (c000000000509dd8)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
```
```
In fs/coredump.c (c0000000005388e0)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/devpts/inode.c (c00000000057ac50)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ecryptfs/main.c (c000000000635aac)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (c00000000069d684)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (c00000000070cc78)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In drivers/pci/pci.c (c000000000863c58)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/dma/of-dma.c (c0000000008c993c)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
```
```
In drivers/regulator/core.c (c0000000008e4198)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (c0000000008eaeb8)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
```
```
In drivers/tty/hvc/hvsi_lib.c (c00000000091d464)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - drivers/tty/hvc/hvsi_lib.c:hvsilib_write_mctrl
  - drivers/tty/hvc/hvsi_lib.c:hvsilib_put_chars
  - drivers/tty/hvc/hvsi_lib.c:hvsi_get_packet
  - drivers/tty/hvc/hvsi_lib.c:hvsi_send_close
  - drivers/tty/hvc/hvsi_lib.c:hvsi_start_handshake
```
```
In drivers/tty/hvc/hvsi.c (c00000000091e6e0)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - drivers/tty/hvc/hvsi.c:hvsi_close_protocol
  - drivers/tty/hvc/hvsi.c:hvsi_put_chars
  - drivers/tty/hvc/hvsi.c:hvsi_set_mctrl
  - drivers/tty/hvc/hvsi.c:hvsi_query
  - drivers/tty/hvc/hvsi.c:hvsi_interrupt
```
```
In drivers/base/power/wakeup.c (c0000000009a2a88)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
```
```
In drivers/base/devcoredump.c (c0000000009c471c)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/mfd/mfd-core.c (c0000000009e8814)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/scsi/scsi_lib.c (c000000000a33204)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/scsi_transport_srp.c (c000000000a43294)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - drivers/scsi/scsi_transport_srp.c:srp_rport_add
```
```
In drivers/scsi/sd.c (c000000000a46f78)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (c000000000a507f4)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (c000000000a63154)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-scsi.c (c000000000a68bd8)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
```
```
In drivers/input/serio/serio.c (c000000000b6e43c)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (c000000000b77298)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/edac/edac_device.c (c000000000c04a04)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (c000000000c07b84)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (c000000000c08f34)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/remoteproc/remoteproc_core.c (c000000000c5db24)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (c000000000c63a28)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (c000000000c65f74)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
```
```
In drivers/extcon/extcon.c (c000000000c68e34)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (c000000000c8c678)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/neighbour.c (c000000000cca4a0)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/page_pool.c (c000000000cf79f0)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
```
```
In net/core/netpoll.c (c000000000cfe48c)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (c000000000d12fa4)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (c000000000d2b35c)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/ip_fragment.c (c000000000d61f44)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/xfrm/xfrm_state.c (c000000000e044c4)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/packet/af_packet.c (c000000000e93658)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (c000000000ea91c0)
Location: arch/powerpc/include/asm/atomic.h:142
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
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
