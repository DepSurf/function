# Function: <code>size_add</code>

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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8344e54f)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_type_init
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff8345e77e)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
```
```
In arch/x86/kernel/crash.c (ffffffff81097a72)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff83479e3c)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
```
```
In kernel/workqueue.c (ffffffff810f4205)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - kernel/workqueue.c:apply_wqattrs_prepare
```
```
In kernel/groups.c (ffffffff811062d0)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
```
```
In kernel/irq/devres.c (ffffffff81168812)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In kernel/irq/generic-chip.c (ffffffff811691a0)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:irq_alloc_generic_chip
```
```
In kernel/irq/irqdomain.c (ffffffff8116a3c7)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/module/sysfs.c (ffffffff81192358)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - kernel/module/sysfs.c:add_notes_attrs
  - kernel/module/sysfs.c:add_sect_attrs
```
```
In kernel/cgroup/cgroup.c (ffffffff811c8d4a)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
```
```
In kernel/audit.c (ffffffff811e1fe8)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/auditfilter.c (ffffffff811e4dca)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_krule_to_data
```
```
In kernel/audit_tree.c (ffffffff811ecacd)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
  - kernel/audit_tree.c:alloc_tree
```
```
In kernel/tracepoint.c (ffffffff81207d8b)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
```
```
In kernel/trace/trace_eprobe.c (ffffffff81246bcb)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
```
```
In kernel/trace/trace_kprobe.c (ffffffff8125d07d)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff81265b39)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
```
```
In kernel/bpf/core.c (ffffffff8126c0b0)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - kernel/bpf/core.c:alloc_new_pack
```
```
In kernel/bpf/local_storage.c (ffffffff812a547f)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
```
```
In kernel/bpf/reuseport_array.c (ffffffff812c6147)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
```
In kernel/watch_queue.c (ffffffff812edc66)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_filter
```
```
In mm/percpu.c (ffffffff8348a698)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/list_lru.c (ffffffff81334d55)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_init_list_lru_one
```
```
In mm/madvise.c (ffffffff81377f43)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - mm/madvise.c:anon_vma_name_alloc
```
```
In mm/swapfile.c (ffffffff8137d945)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_swap_info
```
```
In mm/memcontrol.c (ffffffff813cab15)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
```
```
In mm/hugetlb_cgroup.c (ffffffff813d7033)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/select.c (ffffffff8140fa83)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/aio.c (ffffffff814619f7)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - fs/aio.c:ioctx_add_table
```
```
In fs/crypto/inline_crypt.c (ffffffff81471e69)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
```
```
In fs/verity/enable.c (ffffffff81472716)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
```
```
In fs/iomap/buffered-io.c (ffffffff8148912a)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In ipc/sem.c (ffffffff81598552)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - ipc/sem.c:newary
```
```
In security/selinux/ss/sidtab.c (ffffffff815d6385)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_sid2str_put
```
```
In security/selinux/xfrm.c (ffffffff815e8725)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
```
In security/apparmor/lib.c (ffffffff816115d5)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/label.c (ffffffff8162ba13)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
```
```
In security/landlock/ruleset.c (ffffffff81638e46)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:create_rule
```
```
In security/integrity/ima/ima_api.c (ffffffff8164137e)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
```
```
In security/integrity/ima/ima_policy.c (ffffffff816424e4)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_alloc_rule_opt_list
```
```
In security/integrity/ima/ima_template.c (ffffffff81645016)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_template_data
```
```
In block/bio.c (ffffffff816713ac)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - block/bio.c:bio_kmalloc
```
```
In block/blk-map.c (ffffffff8167e24c)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - block/blk-map.c:bio_alloc_map_data
```
```
In block/blk-ia-ranges.c (ffffffff8169fcb3)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - block/blk-ia-ranges.c:disk_alloc_independent_access_ranges
```
```
In block/blk-iocost.c (ffffffff816ac8a1)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_alloc
```
```
In block/bio-integrity.c (ffffffff816b5159)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_alloc
```
```
In io_uring/io_uring.c (ffffffff816ce226)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_register_pbuf_ring
  - io_uring/io_uring.c:io_allocate_scq_urings
  - io_uring/io_uring.c:io_sqe_buffer_register
```
```
In io_uring/io-wq.c (ffffffff816db6da)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_create
```
```
In lib/rhashtable.c (ffffffff816e9726)
Location: include/linux/overflow.h:151
Inline: True
```
```
In lib/assoc_array.c (ffffffff816f8a14)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
```
```
In lib/stackdepot.c (ffffffff8176f50a)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - lib/stackdepot.c:depot_alloc_stack
```
```
In drivers/gpio/gpiolib.c (ffffffff817a86f2)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff817acb40)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff81808da2)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_pci_framebuffers
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: include/linux/overflow.h:151
Inline: True
```
```
In drivers/video/fbdev/efifb.c (0)
Location: include/linux/overflow.h:151
Inline: True
```
```
In drivers/acpi/prmt.c (ffffffff834ab537)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/prmt.c:acpi_parse_prmt
```
```
In drivers/reset/core.c (0)
Location: include/linux/overflow.h:151
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8192927d)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
```
```
In drivers/tty/serial/max310x.c (ffffffff8192aef1)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/char/virtio_console.c (ffffffff81936da2)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/char/hpet.c (ffffffff8193accd)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
```
```
In drivers/char/tpm/eventlog/tpm2.c (ffffffff81948fd1)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
```
```
In drivers/iommu/intel/dmar.c (ffffffff8195654f)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/iommu/iommu.c (ffffffff819654cf)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
```
```
In drivers/block/xen-blkfront.c (ffffffff819b98ba)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:negotiate_mq
```
```
In drivers/nvdimm/region_devs.c (ffffffff819da732)
Location: include/linux/overflow.h:151
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff819f0625)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_list_alloc
```
```
In drivers/ata/libata-core.c (ffffffff81a26c75)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_config_cpr
```
```
In drivers/spi/spi.c (ffffffff81a4ab7c)
Location: include/linux/overflow.h:151
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a7a386)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_iova_build_caps
```
```
In drivers/usb/core/urb.c (ffffffff81a9c6aa)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_alloc_urb
```
```
In drivers/usb/core/config.c (ffffffff81ee1a28)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81ac0df7)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad22d4)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:itd_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81adc1b2)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
```
In drivers/usb/host/xhci.c (ffffffff81af05aa)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/input/input-mt.c (ffffffff81b195de)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_init_slots
```
```
In drivers/input/evdev.c (ffffffff81b1d5a5)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stripe.c (ffffffff81b78760)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/md/dm-ioctl.c (ffffffff81b7bcf5)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
```
```
In drivers/md/dm-stats.c (ffffffff81b7fbe2)
Location: include/linux/overflow.h:151
Inline: True
```
```
In drivers/firmware/efi/efi.c (ffffffff834c6ab6)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
```
In drivers/remoteproc/remoteproc_core.c (0)
Location: include/linux/overflow.h:151
Inline: True
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff81bd0ff8)
Location: include/linux/overflow.h:151
Inline: True
```
```
In drivers/interconnect/core.c (ffffffff81be32aa)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - drivers/interconnect/core.c:path_find
```
```
In drivers/hte/hte.c (ffffffff81be4ce9)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - drivers/hte/hte.c:hte_register_chip
```
```
In net/core/flow_offload.c (ffffffff81c53258)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - net/core/flow_offload.c:offload_action_alloc
  - net/core/flow_offload.c:flow_rule_alloc
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/overflow.h:151
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff81c912cb)
Location: include/linux/overflow.h:151
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81c9989a)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/netlink/policy.c (ffffffff81cb2615)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - net/netlink/policy.c:add_policy
```
```
In net/ipv4/tcp_input.c (ffffffff81cf1619)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/igmp.c (ffffffff81d3387b)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
```
```
In net/ipv4/fib_semantics.c (ffffffff81d39f34)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/nexthop.c (ffffffff81d4be3c)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:nh_notifier_info_init
  - net/ipv4/nexthop.c:nh_notifier_mpath_info_init
```
```
In net/ipv6/mcast.c (ffffffff81dc67e7)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
```
```
In net/ipv6/exthdrs.c (ffffffff81dcf7c4)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/packet/af_packet.c (ffffffff81df1b34)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
```
```
In net/switchdev/switchdev.c (ffffffff81e0ccb5)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
```
```
In net/xdp/xsk_queue.c (0)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xskq_create
```
```
In net/xdp/xskmap.c (ffffffff81e19905)
Location: include/linux/overflow.h:151
Inline: True
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81e1af27)
Location: include/linux/overflow.h:151
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
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
In arch/x86/events/intel/uncore.c (ffffffff83e69b13)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_type_init
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff83e7f9b1)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
```
```
In arch/x86/kernel/crash.c (ffffffff810ade72)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff83ea431e)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
```
```
In kernel/workqueue.c (ffffffff811164a6)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/workqueue.c:apply_wqattrs_prepare
```
```
In kernel/groups.c (ffffffff8112bf1d)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
```
```
In kernel/irq/devres.c (ffffffff8119cfc2)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In kernel/irq/generic-chip.c (ffffffff8119da60)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:irq_alloc_generic_chip
```
```
In kernel/irq/irqdomain.c (ffffffff8119ef57)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_create
```
```
In kernel/module/sysfs.c (ffffffff811cfad8)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/module/sysfs.c:add_notes_attrs
  - kernel/module/sysfs.c:add_sect_attrs
```
```
In kernel/cgroup/cgroup.c (ffffffff8120bdea)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
```
```
In kernel/audit.c (ffffffff81227e8c)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/auditfilter.c (ffffffff8122adea)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_krule_to_data
```
```
In kernel/audit_tree.c (ffffffff8123302d)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
  - kernel/audit_tree.c:alloc_tree
```
```
In kernel/tracepoint.c (ffffffff812507fb)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
```
```
In kernel/trace/trace_eprobe.c (ffffffff81293d15)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ac31d)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff812b7479)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
```
```
In kernel/bpf/core.c (ffffffff812c12b0)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/bpf/core.c:alloc_new_pack
```
```
In kernel/bpf/local_storage.c (ffffffff813032b4)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
```
```
In kernel/bpf/reuseport_array.c (ffffffff8132b897)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
```
In kernel/watch_queue.c (ffffffff81358066)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_filter
```
```
In mm/percpu.c (ffffffff83ebb044)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/list_lru.c (ffffffff813ab6c5)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_init_list_lru_one
```
```
In mm/madvise.c (ffffffff813f5843)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - mm/madvise.c:anon_vma_name_alloc
```
```
In mm/swapfile.c (ffffffff813fac05)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_swap_info
```
```
In mm/memcontrol.c (ffffffff8144f5b5)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
```
```
In mm/hugetlb_cgroup.c (ffffffff8145ce93)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/select.c (ffffffff8149a6c3)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/aio.c (ffffffff814f1b87)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - fs/aio.c:ioctx_add_table
```
```
In fs/verity/enable.c (ffffffff81504406)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
```
```
In fs/iomap/buffered-io.c (ffffffff8151cd85)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In ipc/sem.c (ffffffff81641792)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - ipc/sem.c:newary
```
```
In security/selinux/ss/sidtab.c (ffffffff81684665)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_sid2str_put
```
```
In security/selinux/xfrm.c (ffffffff81697f25)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
```
In security/apparmor/lib.c (ffffffff816c4275)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/label.c (ffffffff816e0301)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
```
```
In security/landlock/ruleset.c (ffffffff816f0366)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:create_rule
```
```
In security/integrity/ima/ima_api.c (ffffffff816f934e)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
```
```
In security/integrity/ima/ima_policy.c (ffffffff816faaf4)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_alloc_rule_opt_list
```
```
In security/integrity/ima/ima_template.c (ffffffff816fd467)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_template_data
```
```
In block/bio.c (ffffffff8172cb5c)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - block/bio.c:bio_kmalloc
```
```
In block/blk-map.c (ffffffff8173b41c)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - block/blk-map.c:bio_alloc_map_data
```
```
In block/blk-ia-ranges.c (ffffffff8175e743)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - block/blk-ia-ranges.c:disk_alloc_independent_access_ranges
```
```
In block/blk-iocost.c (ffffffff8176b3a1)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_alloc
```
```
In block/bio-integrity.c (ffffffff81774c89)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_alloc
```
```
In io_uring/io_uring.c (ffffffff8178a4e2)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_allocate_scq_urings
```
```
In io_uring/rsrc.c (ffffffff817a245d)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_buffer_register
```
```
In io_uring/io-wq.c (ffffffff817a77c6)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_create
```
```
In lib/rhashtable.c (ffffffff817d98b6)
Location: include/linux/overflow.h:206
Inline: True
```
```
In lib/assoc_array.c (ffffffff817eb2b4)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
```
```
In lib/stackdepot.c (ffffffff8189effa)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - lib/stackdepot.c:depot_alloc_stack
```
```
In drivers/gpio/gpiolib.c (ffffffff818c110b)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c5e20)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: include/linux/overflow.h:206
Inline: True
```
```
In drivers/video/fbdev/efifb.c (0)
Location: include/linux/overflow.h:206
Inline: True
```
```
In drivers/acpi/prmt.c (ffffffff83ee3a18)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/prmt.c:acpi_parse_prmt
```
```
In drivers/reset/core.c (0)
Location: include/linux/overflow.h:206
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81a85c2d)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
```
```
In drivers/tty/serial/max310x.c (ffffffff81a89681)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/char/virtio_console.c (ffffffff81a96c62)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/char/hpet.c (ffffffff81a9b14e)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
```
```
In drivers/char/tpm/eventlog/tpm2.c (ffffffff81aac521)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
```
```
In drivers/iommu/intel/dmar.c (ffffffff81abd34f)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/iommu/iommu.c (ffffffff81acecaf)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
```
```
In drivers/block/xen-blkfront.c (ffffffff81b2ecfa)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:negotiate_mq
```
```
In drivers/nvdimm/region_devs.c (ffffffff81b55b07)
Location: include/linux/overflow.h:206
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81b6e175)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_list_alloc
```
```
In drivers/ata/libata-core.c (ffffffff81ba8935)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_config_cpr
```
```
In drivers/spi/spi.c (ffffffff81bd1cbc)
Location: include/linux/overflow.h:206
Inline: True
```
```
In drivers/usb/core/urb.c (ffffffff81c2162a)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_alloc_urb
```
```
In drivers/usb/core/config.c (ffffffff81c2a6b4)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81c4a9e9)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81c5ced8)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:itd_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81c674b3)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
```
In drivers/usb/host/xhci.c (ffffffff81c7d3aa)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/input/input-mt.c (ffffffff81caaffe)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_init_slots
```
```
In drivers/input/evdev.c (ffffffff81caf585)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stripe.c (ffffffff81d15da0)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/md/dm-ioctl.c (ffffffff81d19205)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
```
```
In drivers/md/dm-stats.c (ffffffff81d1d2f2)
Location: include/linux/overflow.h:206
Inline: True
```
```
In drivers/firmware/efi/efi.c (ffffffff83f07a0f)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d76bdf)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff81d7c8ba)
Location: include/linux/overflow.h:206
Inline: True
```
```
In drivers/interconnect/core.c (ffffffff81d8ef0a)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/interconnect/core.c:path_find
```
```
In drivers/hte/hte.c (ffffffff81d90df9)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/hte/hte.c:hte_register_chip
```
```
In net/core/flow_offload.c (ffffffff81e08878)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/core/flow_offload.c:offload_action_alloc
  - net/core/flow_offload.c:flow_rule_alloc
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/overflow.h:206
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff81e4c81b)
Location: include/linux/overflow.h:206
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81e55bba)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/netlink/policy.c (ffffffff81e70645)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/netlink/policy.c:add_policy
```
```
In net/ethtool/common.c (ffffffff81e7c5bf)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/ethtool/common.c:ethtool_get_max_rxnfc_channel
```
```
In net/ipv4/tcp_input.c (ffffffff81eb5e19)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/igmp.c (ffffffff81efbbbb)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
```
```
In net/ipv4/fib_semantics.c (ffffffff81f02894)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/nexthop.c (ffffffff81f1544c)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:nh_notifier_info_init
  - net/ipv4/nexthop.c:nh_notifier_mpath_info_init
```
```
In net/ipv6/mcast.c (ffffffff81f97407)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
```
```
In net/ipv6/exthdrs.c (ffffffff81fa0b47)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/packet/af_packet.c (ffffffff81fc5b04)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
```
```
In net/switchdev/switchdev.c (ffffffff81fe2ea5)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
```
```
In net/xdp/xsk_queue.c (0)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xskq_create
```
```
In net/xdp/xskmap.c (ffffffff81ff0c95)
Location: include/linux/overflow.h:206
Inline: True
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ff2487)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
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
In arch/x86/events/intel/uncore.c (ffffffff8368a4ae)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_type_init
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff836a2711)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
```
```
In arch/x86/kernel/crash.c (ffffffff810b0e72)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff836c8664)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
```
```
In kernel/workqueue.c (ffffffff81123246)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/workqueue.c:apply_wqattrs_prepare
```
```
In kernel/groups.c (ffffffff81138d7d)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
```
```
In kernel/irq/devres.c (ffffffff811aee50)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In kernel/irq/generic-chip.c (ffffffff811af91b)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:irq_alloc_generic_chip
```
```
In kernel/irq/irqdomain.c (ffffffff811b0e37)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_create
```
```
In kernel/module/sysfs.c (ffffffff811e3c78)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/module/sysfs.c:add_notes_attrs
  - kernel/module/sysfs.c:add_sect_attrs
```
```
In kernel/cgroup/cgroup.c (ffffffff81221407)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
```
```
In kernel/pid_namespace.c (ffffffff81238b57)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit.c (ffffffff8123df36)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/auditfilter.c (ffffffff812413e4)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_krule_to_data
```
```
In kernel/audit_tree.c (ffffffff81249ceb)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
  - kernel/audit_tree.c:alloc_tree
```
```
In kernel/tracepoint.c (ffffffff81267b9d)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
```
```
In kernel/trace/trace_eprobe.c (ffffffff812b0e05)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
```
```
In kernel/trace/trace_events_synth.c (ffffffff812b4ef4)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:trace_string
```
```
In kernel/trace/trace_events_user.c (ffffffff812c6f03)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_events_ioctl_reg
```
```
In kernel/trace/trace_kprobe.c (ffffffff812cff66)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff812daae3)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
```
```
In kernel/trace/trace_fprobe.c (ffffffff812dfde1)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:alloc_trace_fprobe
```
```
In kernel/bpf/core.c (ffffffff812e8072)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/bpf/core.c:alloc_new_pack
```
```
In kernel/bpf/local_storage.c (ffffffff81331d45)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
```
```
In kernel/bpf/reuseport_array.c (ffffffff8135b955)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:reuseport_array_mem_usage
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
```
In kernel/watch_queue.c (ffffffff81389905)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_filter
```
```
In mm/percpu.c (ffffffff836e367b)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/list_lru.c (ffffffff813dfa65)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_init_list_lru_one
```
```
In mm/madvise.c (ffffffff81428593)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - mm/madvise.c:anon_vma_name_alloc
```
```
In mm/swapfile.c (ffffffff8142dc55)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_swap_info
```
```
In mm/memcontrol.c (ffffffff814850e5)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
```
```
In mm/hugetlb_cgroup.c (ffffffff81492ee3)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/select.c (ffffffff814cf773)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/aio.c (ffffffff815280d3)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - fs/aio.c:ioctx_add_table
```
```
In fs/verity/enable.c (ffffffff8153bb94)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
```
```
In fs/iomap/buffered-io.c (ffffffff81554f35)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In ipc/sem.c (ffffffff81679d12)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - ipc/sem.c:newary
```
```
In security/selinux/ss/sidtab.c (ffffffff816bc9d5)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_sid2str_put
```
```
In security/selinux/xfrm.c (ffffffff816d03f0)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
```
In security/apparmor/lib.c (ffffffff816fce45)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/label.c (ffffffff8171993c)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
```
```
In security/landlock/ruleset.c (ffffffff8172a721)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:create_rule
```
```
In security/integrity/ima/ima_api.c (ffffffff817334b3)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
```
```
In security/integrity/ima/ima_policy.c (ffffffff81734bfe)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_alloc_rule_opt_list
```
```
In security/integrity/ima/ima_template.c (ffffffff817374a1)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_template_data
```
```
In block/bio.c (ffffffff81768edc)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - block/bio.c:bio_kmalloc
```
```
In block/blk-map.c (ffffffff81777b38)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - block/blk-map.c:bio_alloc_map_data
```
```
In block/blk-ia-ranges.c (ffffffff8179d653)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - block/blk-ia-ranges.c:disk_alloc_independent_access_ranges
```
```
In block/blk-iocost.c (ffffffff817aa494)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_alloc
```
```
In block/bio-integrity.c (ffffffff817b49a9)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_alloc
```
```
In io_uring/io_uring.c (ffffffff817cb72c)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_allocate_scq_urings
```
```
In io_uring/rsrc.c (ffffffff817e34e6)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_buffer_register
```
```
In lib/rhashtable.c (ffffffff81818c41)
Location: include/linux/overflow.h:206
Inline: True
```
```
In lib/assoc_array.c (ffffffff8182b452)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
```
```
In lib/stackdepot.c (ffffffff818e15d4)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - lib/stackdepot.c:depot_alloc_stack
```
```
In drivers/gpio/gpiolib.c (ffffffff81903fa7)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81908ed1)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
```
```
In drivers/acpi/prmt.c (ffffffff837094d9)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/prmt.c:acpi_parse_prmt
```
```
In drivers/reset/core.c (0)
Location: include/linux/overflow.h:206
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81ad139f)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
```
```
In drivers/tty/serial/max310x.c (ffffffff81ad4e4f)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/char/virtio_console.c (ffffffff81ae247c)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/char/hpet.c (ffffffff81ae69de)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
```
```
In drivers/char/tpm/eventlog/tpm2.c (ffffffff81af7d71)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b09c6c)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/iommu/iommu.c (ffffffff81b1d61f)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
```
```
In drivers/block/xen-blkfront.c (ffffffff81b82163)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:negotiate_mq
```
```
In drivers/nvdimm/region_devs.c (ffffffff81ba9057)
Location: include/linux/overflow.h:206
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81bc1985)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_list_alloc
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81be3437)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
```
```
In drivers/ata/libata-core.c (ffffffff81c0004d)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_config_cpr
```
```
In drivers/spi/spi.c (ffffffff81c29530)
Location: include/linux/overflow.h:206
Inline: True
```
```
In drivers/usb/core/urb.c (ffffffff81c885af)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_alloc_urb
```
```
In drivers/usb/core/config.c (ffffffff81c91649)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81cb1fb9)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc4557)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:itd_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81cce84a)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
```
In drivers/usb/host/xhci.c (ffffffff81ce44dc)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/input/input-mt.c (ffffffff81d125e2)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_init_slots
```
```
In drivers/input/evdev.c (ffffffff81d16b85)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stripe.c (ffffffff81d7f011)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/md/dm-ioctl.c (ffffffff81d824fe)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
```
```
In drivers/md/dm-stats.c (ffffffff81d864e7)
Location: include/linux/overflow.h:206
Inline: True
```
```
In drivers/firmware/efi/efi.c (ffffffff8372dae0)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de4b1f)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff81deaa7a)
Location: include/linux/overflow.h:206
Inline: True
```
```
In drivers/interconnect/core.c (0)
Location: include/linux/overflow.h:206
Inline: True
```
```
In drivers/hte/hte.c (ffffffff81dff0ab)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/hte/hte.c:hte_register_chip
```
```
In net/core/flow_offload.c (ffffffff81e7b188)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/core/flow_offload.c:offload_action_alloc
  - net/core/flow_offload.c:flow_rule_alloc
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/overflow.h:206
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff81ea7f5b)
Location: include/linux/overflow.h:206
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81eb145a)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/netlink/policy.c (ffffffff81ecc759)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/netlink/policy.c:add_policy
```
```
In net/ethtool/common.c (ffffffff81ed8957)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/ethtool/common.c:ethtool_get_max_rxnfc_channel
```
```
In net/ipv4/tcp_input.c (ffffffff81f14239)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/igmp.c (ffffffff81f5b5e9)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
```
```
In net/ipv4/fib_semantics.c (ffffffff81f623aa)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/nexthop.c (ffffffff81f750df)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:nh_notifier_info_init
  - net/ipv4/nexthop.c:nh_notifier_mpath_info_init
```
```
In net/ipv6/mcast.c (ffffffff81ff7dc1)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/overflow.h:206
Inline: True
```
```
In net/packet/af_packet.c (ffffffff8202a04e)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
```
```
In net/switchdev/switchdev.c (ffffffff8205f1c5)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
```
```
In net/xdp/xsk_queue.c (0)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xskq_create
```
```
In net/xdp/xskmap.c (ffffffff8206ce80)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_alloc
```
```
In net/xdp/xsk_buff_pool.c (ffffffff8206e6b7)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
```
```
In net/handshake/request.c (ffffffff82092ab7)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/handshake/request.c:handshake_req_alloc
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
In arch/x86/events/intel/uncore.c (ffffffff838ba06e)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_type_init
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff838d2808)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
```
```
In arch/x86/kernel/crash.c (ffffffff810b792f)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:prepare_elf_headers
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff838f9264)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
```
```
In kernel/workqueue.c (ffffffff8112d2ef)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/workqueue.c:apply_wqattrs_prepare
```
```
In kernel/params.c (ffffffff811325b7)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/params.c:param_set_charp
```
```
In kernel/groups.c (ffffffff81143abd)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
```
```
In kernel/irq/devres.c (ffffffff811bea50)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In kernel/irq/generic-chip.c (ffffffff811bf475)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:irq_alloc_generic_chip
```
```
In kernel/irq/irqdomain.c (ffffffff811c0bb7)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_create
```
```
In kernel/module/sysfs.c (ffffffff811f99d8)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/module/sysfs.c:add_notes_attrs
  - kernel/module/sysfs.c:add_sect_attrs
```
```
In kernel/cgroup/cgroup.c (ffffffff812390e7)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
```
```
In kernel/pid_namespace.c (ffffffff81252827)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit.c (ffffffff81257e4c)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/auditfilter.c (ffffffff8125b213)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_krule_to_data
```
```
In kernel/audit_tree.c (ffffffff81263bfb)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
  - kernel/audit_tree.c:alloc_tree
```
```
In kernel/tracepoint.c (ffffffff8128154d)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
```
```
In kernel/trace/trace.c (ffffffff8129c30d)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
```
```
In kernel/trace/trace_eprobe.c (ffffffff812cd3c5)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
```
```
In kernel/trace/trace_events_synth.c (ffffffff812d15c0)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:trace_string
```
```
In kernel/trace/trace_events_user.c (ffffffff812e38c7)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_events_ioctl_reg
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ed966)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff812f8d33)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
```
```
In kernel/trace/trace_fprobe.c (ffffffff812fdeb1)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:alloc_trace_fprobe
```
```
In kernel/bpf/core.c (ffffffff81307c82)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/bpf/core.c:alloc_new_pack
```
```
In kernel/bpf/local_storage.c (ffffffff813562e5)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
```
```
In kernel/bpf/reuseport_array.c (ffffffff813845e5)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:reuseport_array_mem_usage
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
```
In kernel/watch_queue.c (ffffffff813b3355)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_filter
```
```
In mm/percpu.c (ffffffff83915f0b)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/list_lru.c (ffffffff8140a175)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_init_list_lru_one
```
```
In mm/madvise.c (ffffffff81461e43)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - mm/madvise.c:anon_vma_name_alloc
```
```
In mm/swapfile.c (ffffffff81467715)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_swap_info
```
```
In mm/memcontrol.c (ffffffff814b71c5)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
```
```
In mm/hugetlb_cgroup.c (ffffffff814c28e3)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/select.c (ffffffff815020b3)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/aio.c (ffffffff8155d1c1)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - fs/aio.c:ioctx_add_table
```
```
In fs/verity/enable.c (ffffffff81570e74)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
```
```
In fs/iomap/buffered-io.c (ffffffff8158b5e7)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:ifs_alloc
```
```
In ipc/sem.c (ffffffff816b71ee)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:newary
```
```
In security/security.c (ffffffff816da0e5)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - security/security.c:lsm_fill_user_ctx
```
```
In security/selinux/ss/sidtab.c (ffffffff816f9505)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_sid2str_put
```
```
In security/selinux/xfrm.c (ffffffff8170ca10)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
```
In security/apparmor/lib.c (ffffffff8173a3a5)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/label.c (ffffffff817583dc)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
```
```
In security/landlock/ruleset.c (ffffffff8176bdc1)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
```
```
In security/integrity/ima/ima_api.c (ffffffff81773ed3)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
```
```
In security/integrity/ima/ima_policy.c (ffffffff8177570e)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_alloc_rule_opt_list
```
```
In security/integrity/ima/ima_template.c (ffffffff81777f91)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_template_data
```
```
In security/integrity/ima/ima_modsig.c (ffffffff8177b717)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - security/integrity/ima/ima_modsig.c:ima_read_modsig
```
```
In block/bio.c (ffffffff817aaf0c)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - block/bio.c:bio_kmalloc
```
```
In block/blk-map.c (ffffffff817b9d5c)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - block/blk-map.c:bio_alloc_map_data
```
```
In block/blk-ia-ranges.c (ffffffff817e10a3)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - block/blk-ia-ranges.c:disk_alloc_independent_access_ranges
```
```
In block/blk-iocost.c (ffffffff817ee244)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_alloc
```
```
In block/bio-integrity.c (ffffffff817f89d0)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_alloc
```
```
In io_uring/io_uring.c (ffffffff8181661c)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_allocate_scq_urings
```
```
In io_uring/rsrc.c (ffffffff81827596)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_buffer_register
```
```
In io_uring/register.c (ffffffff8182b1c8)
Location: include/linux/overflow.h:206
Inline: True
```
```
In lib/rhashtable.c (ffffffff8185df71)
Location: include/linux/overflow.h:206
Inline: True
```
```
In lib/assoc_array.c (ffffffff8187d001)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
```
```
In drivers/gpio/gpiolib.c (ffffffff8194b9e7)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81951a0d)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
```
```
In drivers/acpi/mipi-disco-img.c (ffffffff819f2762)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/acpi/mipi-disco-img.c:parse_csi2_resource
```
```
In drivers/acpi/prmt.c (ffffffff8393c968)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/prmt.c:acpi_parse_prmt
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81ac6ce7)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:queue_reply
```
```
In drivers/reset/core.c (0)
Location: include/linux/overflow.h:206
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff81af189d)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_alloc
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81b0d25e)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81b251ff)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
```
```
In drivers/tty/serial/max310x.c (ffffffff81b28311)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/char/virtio_console.c (ffffffff81b3586c)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/char/hpet.c (ffffffff81b39d6e)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
```
```
In drivers/char/tpm/eventlog/tpm2.c (ffffffff81b4b391)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b5dcbc)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/iommu/iommu.c (ffffffff81b73cbf)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b7c080)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81b7f2c7)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:__viommu_add_req
```
```
In drivers/block/xen-blkfront.c (ffffffff81bd6023)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:negotiate_mq
```
```
In drivers/nvdimm/region_devs.c (ffffffff81bfd397)
Location: include/linux/overflow.h:206
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81c16115)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_list_alloc
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81c38897)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
```
```
In drivers/ata/libata-core.c (ffffffff81c560bd)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_config_cpr
```
```
In drivers/spi/spi.c (ffffffff81cdbd70)
Location: include/linux/overflow.h:206
Inline: True
```
```
In drivers/usb/core/urb.c (ffffffff81d3cfff)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_alloc_urb
```
```
In drivers/usb/core/config.c (ffffffff81d46209)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81d66cc9)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81d79447)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:itd_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81d8374a)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
```
In drivers/usb/host/xhci.c (ffffffff81d930e6)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/input/input-mt.c (ffffffff81dc81e2)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_init_slots
```
```
In drivers/input/evdev.c (ffffffff81dcc835)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stripe.c (ffffffff81e36631)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/md/dm-ioctl.c (ffffffff81e39b85)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
```
```
In drivers/md/dm-stats.c (ffffffff81e3dc24)
Location: include/linux/overflow.h:206
Inline: True
```
```
In drivers/firmware/efi/efi.c (ffffffff83961ec0)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9ac0f)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff81ea0cea)
Location: include/linux/overflow.h:206
Inline: True
```
```
In drivers/interconnect/core.c (ffffffff81eb3857)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/interconnect/core.c:path_find
```
```
In drivers/hte/hte.c (ffffffff81eb639b)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - drivers/hte/hte.c:hte_register_chip
```
```
In net/core/flow_offload.c (ffffffff81f3b418)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/core/flow_offload.c:offload_action_alloc
  - net/core/flow_offload.c:flow_rule_alloc
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/overflow.h:206
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff81f6aa0e)
Location: include/linux/overflow.h:206
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81f73efe)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/netlink/policy.c (ffffffff81f8ff2a)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/netlink/policy.c:add_policy
```
```
In net/ethtool/common.c (ffffffff81f9c777)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/ethtool/common.c:ethtool_get_max_rxnfc_channel
```
```
In net/ipv4/tcp_input.c (ffffffff81fd8719)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/igmp.c (ffffffff82021b29)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
```
```
In net/ipv4/fib_semantics.c (ffffffff8202897a)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/nexthop.c (ffffffff8203ba1c)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:nh_notifier_info_init
  - net/ipv4/nexthop.c:nh_notifier_mpath_info_init
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204cbe1)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/ipv4/tcp_sigpool.c:sigpool_reserve_scratch
```
```
In net/ipv6/mcast.c (ffffffff820c5a11)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/overflow.h:206
Inline: True
```
```
In net/packet/af_packet.c (ffffffff820f9b4d)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
```
```
In net/devlink/netlink.c (ffffffff8210140b)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/devlink/netlink.c:devlink_nl_notify_filter_set_doit
  - net/devlink/netlink.c:devlink_nl_notify_filter_set_doit
```
```
In net/switchdev/switchdev.c (ffffffff82132115)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
```
```
In net/xdp/xsk_queue.c (0)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xskq_create
```
```
In net/xdp/xskmap.c (ffffffff82140d20)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_alloc
```
```
In net/xdp/xsk_buff_pool.c (ffffffff82142737)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
```
```
In net/handshake/request.c (ffffffff82169367)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - net/handshake/request.c:handshake_req_alloc
```
```
In arch/x86/pci/irq.c (ffffffff83971398)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_find_routing_table
  - arch/x86/pci/irq.c:pirq_find_routing_table
```
```
In lib/objpool.c (ffffffff821919f4)
Location: include/linux/overflow.h:206
Inline: True
Inline callers:
  - lib/objpool.c:objpool_init_percpu_slots
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
