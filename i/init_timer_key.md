# Function: <code>init_timer_key</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void init_timer_key(struct timer_list *timer, unsigned int flags, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810ebb60)
Location: kernel/time/timer.c:704
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_timer
  - arch/x86/kernel/hpet.c:hpet_cpuhp_notify
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/rcu/srcu.c:init_srcu_struct
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/cgroup.c:pidlist_array_load
  - kernel/relay.c:__relay_reset
  - kernel/events/core.c:__perf_event_init_context
  - kernel/padata.c:padata_alloc_pd
  - kernel/jump_label.c:jump_label_rate_limit
  - mm/page-writeback.c:wb_domain_init
  - mm/vmstat.c:setup_vmstat
  - mm/backing-dev.c:wb_init
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:kjournald2
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/genhd.c:add_disk
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-throttle.c:blk_throtl_init
  - block/cfq-iosched.c:cfq_init_queue
  - drivers/pci/hotplug/pciehp_hpc.c:int_poll_timeout
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/video/console/fbcon.c:fbcon_add_cursor_timer
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/xen/grant-table.c:gnttab_unmap_refs_async
  - drivers/tty/sysrq.c:sysrq_connect
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/tpm/tpm-dev.c:tpm_open
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/wakeup.c:wakeup_source_add
  - drivers/base/firmware_class.c:firmware_class_init
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/scsi.c:scsi_get_command
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-sff.c:ata_sff_port_init
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hcd.c:usb_create_shared_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/input/input.c:input_allocate_device
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/power/power_supply_core.c:__power_supply_register
  - drivers/power/charger-manager.c:charger_manager_init
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/md/md.c:mddev_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_governor_dbs
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/leds/led-core.c:led_init_core
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - net/core/sock.c:sock_init_data
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:__neigh_create
  - net/core/flow.c:flow_cache_init
  - net/core/netpoll.c:__netpoll_setup
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/ipv4/inetpeer.c:inet_initpeers
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/igmp.c:ip_mc_inc_group
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/ip6_fib.c:fib6_net_init
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/ip6mr.c:ip6mr_new_table
  - net/packet/af_packet.c:packet_set_ring
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff810ebb60-ffffffff810ebc08: init_timer_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void init_timer_key(struct timer_list *timer, unsigned int flags, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810f3900)
Location: kernel/time/timer.c:811
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_timer
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/rcu/srcu.c:init_srcu_struct
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/cgroup.c:cgroup_pidlist_start
  - kernel/relay.c:__relay_reset
  - kernel/padata.c:padata_alloc_pd
  - kernel/jump_label.c:jump_label_rate_limit
  - mm/page-writeback.c:wb_domain_init
  - mm/vmstat.c:setup_vmstat
  - mm/backing-dev.c:wb_init
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:kjournald2
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/genhd.c:device_add_disk
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:int_poll_timeout
  - drivers/video/console/fbcon.c:fbcon_add_cursor_timer
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/xen/grant-table.c:gnttab_unmap_refs_async
  - drivers/tty/sysrq.c:sysrq_connect
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/tpm/tpm-dev.c:tpm_open
  - drivers/iommu/amd_iommu.c:amd_iommu_init_dma_ops
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/wakeup.c:wakeup_source_add
  - drivers/base/firmware_class.c:firmware_class_init
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/scsi.c:scsi_get_command
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-sff.c:ata_sff_port_init
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:usb_create_shared_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/input/input.c:input_allocate_device
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/power/power_supply_core.c:__power_supply_register
  - drivers/power/charger-manager.c:charger_manager_init
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/md/md.c:mddev_init
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/leds/led-core.c:led_init_core
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - net/core/sock.c:sock_init_data
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:__neigh_create
  - net/core/flow.c:flow_cache_init
  - net/core/netpoll.c:__netpoll_setup
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/ipv4/inetpeer.c:inet_initpeers
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_inc_group
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/ip6_fib.c:fib6_net_init
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/ip6mr.c:ip6mr_new_table
  - net/packet/af_packet.c:packet_set_ring
  - net/rfkill/core.c:rfkill_register
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
```
**Symbols:**

```
ffffffff810f3900-ffffffff810f3995: init_timer_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void init_timer_key(struct timer_list *timer, unsigned int flags, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810fac50)
Location: kernel/time/timer.c:811
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_timer
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/rcu/srcu.c:init_srcu_struct
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/cgroup.c:cgroup_pidlist_start
  - kernel/padata.c:padata_alloc_pd
  - kernel/jump_label.c:jump_label_rate_limit
  - mm/page-writeback.c:wb_domain_init
  - mm/vmstat.c:setup_vmstat
  - mm/backing-dev.c:wb_init
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:kjournald2
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/genhd.c:device_add_disk
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-wbt.c:wbt_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:int_poll_timeout
  - drivers/video/console/fbcon.c:fbcon_add_cursor_timer
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/xen/grant-table.c:gnttab_unmap_refs_async
  - drivers/tty/sysrq.c:sysrq_connect
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/tpm/tpm-dev.c:tpm_open
  - drivers/iommu/amd_iommu.c:amd_iommu_init_dma_ops
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/wakeup.c:wakeup_source_add
  - drivers/base/firmware_class.c:firmware_class_init
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/scsi.c:scsi_get_command
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-sff.c:ata_sff_port_init
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:usb_create_shared_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/input/input.c:input_allocate_device
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/md/md.c:mddev_init
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/leds/led-core.c:led_init_core
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - net/core/sock.c:sock_init_data
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:__neigh_create
  - net/core/flow.c:flow_cache_init
  - net/core/netpoll.c:__netpoll_setup
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/ipv4/inetpeer.c:inet_initpeers
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_inc_group
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/ip6_fib.c:fib6_net_init
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/ip6mr.c:ip6mr_new_table
  - net/packet/af_packet.c:packet_set_ring
  - net/rfkill/core.c:rfkill_register
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
```
**Symbols:**

```
ffffffff810fac50-ffffffff810face5: init_timer_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void init_timer_key(struct timer_list *timer, unsigned int flags, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81909efa)
Location: kernel/time/timer.c:777
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_timer
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/padata.c:padata_alloc_pd
  - kernel/jump_label.c:jump_label_rate_limit
  - mm/page-writeback.c:wb_domain_init
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:wb_init
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:kjournald2
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/genhd.c:device_add_disk
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:int_poll_timeout
  - drivers/video/console/fbcon.c:fbcon_add_cursor_timer
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/xen/grant-table.c:gnttab_unmap_refs_async
  - drivers/tty/sysrq.c:sysrq_connect
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/wakeup.c:wakeup_source_add
  - drivers/base/firmware_class.c:firmware_class_init
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-sff.c:ata_sff_port_init
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:__usb_create_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/input/input.c:input_allocate_device
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/md/md.c:mddev_init
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/leds/led-core.c:led_init_core
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/ras/cec.c:cec_init
  - net/core/sock.c:sock_init_data
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:__neigh_create
  - net/core/flow.c:flow_cache_init
  - net/core/netpoll.c:__netpoll_setup
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/ipv4/inetpeer.c:inet_initpeers
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_inc_group
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/ip6_fib.c:fib6_net_init
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/ip6mr.c:ip6mr_new_table
  - net/packet/af_packet.c:packet_set_ring
  - net/rfkill/core.c:rfkill_register
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
```
**Symbols:**

```
ffffffff810fd270-ffffffff810fd2e1: init_timer_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void init_timer_key(struct timer_list *timer, void (*func)(struct timer_list *), unsigned int flags, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81994238)
Location: kernel/time/timer.c:785
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_timer
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/padata.c:padata_alloc_pd
  - kernel/jump_label.c:jump_label_rate_limit
  - mm/page-writeback.c:wb_domain_init
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:wb_init
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:kjournald2
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/genhd.c:device_add_disk
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/video/fbdev/core/fbcon.c:fbcon_add_cursor_timer
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/xen/grant-table.c:gnttab_unmap_refs_async
  - drivers/tty/sysrq.c:sysrq_connect
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/wakeup.c:wakeup_source_add
  - drivers/base/firmware_class.c:firmware_class_init
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-sff.c:ata_sff_port_init
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:__usb_create_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/input/input.c:input_allocate_device
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/md/md.c:mddev_init
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/leds/led-core.c:led_init_core
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/ras/cec.c:cec_init
  - net/core/sock.c:sock_init_data
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:__neigh_create
  - net/core/netpoll.c:__netpoll_setup
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_inc_group
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/ip6mr.c:ip6mr_new_table
  - net/packet/af_packet.c:packet_set_ring
  - net/strparser/strparser.c:strp_init
  - net/rfkill/core.c:rfkill_register
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
```
**Symbols:**

```
ffffffff81107b40-ffffffff81107bc0: init_timer_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void init_timer_key(struct timer_list *timer, void (*func)(struct timer_list *), unsigned int flags, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff819f07b8)
Location: kernel/time/timer.c:802
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_timer
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/padata.c:padata_alloc_pd
  - kernel/jump_label.c:jump_label_rate_limit
  - mm/page-writeback.c:wb_domain_init
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:wb_init
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:kjournald2
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/genhd.c:__device_add_disk
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_add_cursor_timer
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/xen/grant-table.c:gnttab_unmap_refs_async
  - drivers/tty/sysrq.c:sysrq_connect
  - drivers/tty/serial/8250/8250_core.c:serial8250_isa_init_ports
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/wakeup.c:wakeup_source_add
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-sff.c:ata_sff_port_init
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:__usb_create_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/input/input.c:input_allocate_device
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/md/md.c:mddev_init
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/leds/led-core.c:led_init_core
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/ras/cec.c:cec_init
  - net/core/sock.c:sock_init_data
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:__neigh_create
  - net/core/netpoll.c:__netpoll_setup
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:__ip_mc_inc_group
  - net/ipv4/ipmr_base.c:mr_table_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/packet/af_packet.c:packet_set_ring
  - net/strparser/strparser.c:strp_init
  - net/rfkill/core.c:rfkill_register
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
```
**Symbols:**

```
ffffffff81113070-ffffffff811130f0: init_timer_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void init_timer_key(struct timer_list *timer, void (*func)(struct timer_list *), unsigned int flags, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81a2bb38)
Location: kernel/time/timer.c:801
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_timer
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/sched/psi.c:group_init
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/padata.c:padata_alloc_pd
  - kernel/jump_label.c:jump_label_rate_limit
  - mm/page-writeback.c:wb_domain_init
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:wb_init
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:kjournald2
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/genhd.c:__device_add_disk
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_add_cursor_timer
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/xen/grant-table.c:gnttab_unmap_refs_async
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/sysrq.c:sysrq_connect
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_isa_init_ports
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/base/power/wakeup.c:wakeup_source_add
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-sff.c:ata_sff_port_init
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:__usb_create_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/input/input.c:input_allocate_device
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/md/md.c:mddev_init
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/leds/led-core.c:led_init_core
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/ras/cec.c:cec_init
  - net/core/sock.c:sock_init_data
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:___neigh_create
  - net/core/netpoll.c:__netpoll_setup
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:__ip_mc_inc_group
  - net/ipv4/ipmr_base.c:mr_table_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/packet/af_packet.c:packet_set_ring
  - net/strparser/strparser.c:strp_init
  - net/rfkill/core.c:rfkill_register
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
```
**Symbols:**

```
ffffffff8111e8d0-ffffffff8111e950: init_timer_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void init_timer_key(struct timer_list *timer, void (*func)(struct timer_list *), unsigned int flags, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81a9bd69)
Location: kernel/time/timer.c:796
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_timer
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/sched/psi.c:group_init
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/padata.c:padata_alloc_pd
  - kernel/jump_label.c:jump_label_rate_limit
  - mm/page-writeback.c:wb_domain_init
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:wb_init
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:kjournald2
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/genhd.c:__device_add_disk
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_add_cursor_timer
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/xen/grant-table.c:gnttab_unmap_refs_async
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/sysrq.c:sysrq_connect
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_isa_init_ports
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/base/power/wakeup.c:wakeup_source_add
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-sff.c:ata_sff_port_init
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:__usb_create_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/input/input.c:input_allocate_device
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/md/md.c:mddev_init
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/leds/led-core.c:led_init_core
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/ras/cec.c:cec_init
  - net/core/sock.c:sock_init_data
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:___neigh_create
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/netpoll.c:__netpoll_setup
  - net/core/devlink.c:devlink_port_register
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr_base.c:mr_table_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/packet/af_packet.c:packet_set_ring
  - net/strparser/strparser.c:strp_init
  - net/rfkill/core.c:rfkill_register
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
```
**Symbols:**

```
ffffffff811295a0-ffffffff8112961f: init_timer_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void init_timer_key(struct timer_list *timer, void (*func)(struct timer_list *), unsigned int flags, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81ad36b9)
Location: kernel/time/timer.c:800
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_timer
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat_enable
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/sched/psi.c:group_init
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/jump_label.c:jump_label_rate_limit
  - mm/page-writeback.c:wb_domain_init
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:wb_init
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:kjournald2
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/genhd.c:__device_add_disk
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-iocost.c:blk_iocost_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_add_cursor_timer
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/xen/grant-table.c:gnttab_unmap_refs_async
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/sysrq.c:sysrq_connect
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_isa_init_ports
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/base/power/wakeup.c:wakeup_source_add
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-sff.c:ata_sff_port_init
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:__usb_create_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/input/input.c:input_allocate_device
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/md/md.c:mddev_init
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/leds/led-core.c:led_init_core
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/ras/cec.c:cec_init
  - net/core/sock.c:sock_init_data
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:___neigh_create
  - net/core/netpoll.c:__netpoll_setup
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/devlink.c:devlink_port_register
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr_base.c:mr_table_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/packet/af_packet.c:packet_set_ring
  - net/strparser/strparser.c:strp_init
  - net/rfkill/core.c:rfkill_register
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
```
**Symbols:**

```
ffffffff81135540-ffffffff811355bf: init_timer_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void init_timer_key(struct timer_list *timer, void (*func)(struct timer_list *), unsigned int flags, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81bcb7c3)
Location: kernel/time/timer.c:808
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_timer
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online
  - arch/x86/kernel/cpu/resctrl/core.c:domain_setup_mon_state
  - arch/x86/kernel/cpu/resctrl/core.c:domain_setup_mon_state
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat_enable
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/sched/psi.c:group_init
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/srcutree.c:init_srcu_struct_nodes
  - kernel/rcu/tree.c:kfree_rcu_batch_init
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/cgroup/cgroup.c:cgroup_add_file
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find_create
  - kernel/jump_label.c:jump_label_rate_limit
  - mm/page-writeback.c:wb_domain_init
  - mm/vmstat.c:start_shepherd_timer
  - mm/backing-dev.c:wb_init
  - mm/page_reporting.c:page_reporting_register
  - fs/io_uring.c:io_ring_ctx_alloc
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:kjournald2
  - block/blk-core.c:__blk_alloc_queue
  - block/blk-core.c:__blk_alloc_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/genhd.c:__device_add_disk
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-iocost.c:blk_iocost_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/shpchp_core.c:init_slots
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_add_cursor_timer
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/sysrq.c:sysrq_connect
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_isa_init_ports
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/base/power/wakeup.c:wakeup_source_add
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-sff.c:ata_sff_port_init
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/xen-netfront.c:xennet_init_queue
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:__usb_create_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/host/ehci-platform.c:quirk_poll_init
  - drivers/usb/host/ehci-platform.c:quirk_poll_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-dbgcap.c:xhci_do_dbc_init
  - drivers/input/input.c:input_allocate_device
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/md/md.c:mddev_init
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_pci.c:edac_pci_add_device
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/leds/led-core.c:led_init_core
  - drivers/ras/cec.c:cec_init
  - net/core/sock.c:sock_init_data
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_alloc
  - net/core/netpoll.c:__netpoll_setup
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/devlink.c:devlink_port_register
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr_base.c:mr_table_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:mca_alloc
  - net/packet/af_packet.c:init_prb_bdqc
  - net/strparser/strparser.c:strp_init
  - net/rfkill/core.c:rfkill_register
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
  - net/mptcp/protocol.c:mptcp_sk_clone
```
**Symbols:**

```
ffffffff81144160-ffffffff811441e0: init_timer_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void init_timer_key(struct timer_list *timer, void (*func)(struct timer_list *), unsigned int flags, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81c44662)
Location: kernel/time/timer.c:810
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_timer
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online
  - arch/x86/kernel/cpu/resctrl/core.c:domain_setup_mon_state
  - arch/x86/kernel/cpu/resctrl/core.c:domain_setup_mon_state
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/sched/psi.c:group_init
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/srcutree.c:init_srcu_struct_nodes
  - kernel/rcu/tree.c:kfree_rcu_batch_init
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/cgroup/cgroup.c:cgroup_add_file
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find_create
  - kernel/jump_label.c:jump_label_rate_limit
  - mm/page-writeback.c:wb_domain_init
  - mm/vmstat.c:start_shepherd_timer
  - mm/backing-dev.c:wb_init
  - mm/page_reporting.c:page_reporting_register
  - fs/io_uring.c:io_ring_ctx_alloc
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:kjournald2
  - block/blk-core.c:blk_alloc_queue
  - block/blk-core.c:blk_alloc_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/genhd.c:__device_add_disk
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-iocost.c:blk_iocost_init
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/shpchp_core.c:init_slots
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_add_cursor_timer
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
  - drivers/xen/events/events_base.c:xen_cpu_init_eoi
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/sysrq.c:sysrq_connect
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_isa_init_ports
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/base/power/wakeup.c:wakeup_source_add
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-sff.c:ata_sff_port_init
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/xen-netfront.c:xennet_init_queue
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:__usb_create_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/host/ehci-platform.c:quirk_poll_init
  - drivers/usb/host/ehci-platform.c:quirk_poll_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-dbgcap.c:xhci_do_dbc_init
  - drivers/input/input.c:input_allocate_device
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/md/md.c:mddev_init
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_pci.c:edac_pci_add_device
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/leds/led-core.c:led_init_core
  - drivers/ras/cec.c:cec_init
  - net/core/sock.c:sock_init_data
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_alloc
  - net/core/netpoll.c:__netpoll_setup
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/devlink.c:devlink_port_register
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr_base.c:mr_table_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:mca_alloc
  - net/packet/af_packet.c:init_prb_bdqc
  - net/strparser/strparser.c:strp_init
  - net/rfkill/core.c:rfkill_register
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
  - net/mptcp/protocol.c:__mptcp_init_sock
  - net/mptcp/protocol.c:__mptcp_init_sock
  - net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list
```
**Symbols:**

```
ffffffff81140710-ffffffff8114078e: init_timer_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void init_timer_key(struct timer_list *timer, void (*func)(struct timer_list *), unsigned int flags, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81c378d2)
Location: kernel/time/timer.c:812
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_timer
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/sched/psi.c:group_init
  - kernel/sched/psi.c:group_init
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/srcutree.c:init_srcu_struct_nodes
  - kernel/rcu/tree.c:rcu_init
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/jump_label.c:jump_label_rate_limit
  - mm/page-writeback.c:wb_domain_init
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:wb_init
  - mm/page_reporting.c:page_reporting_register
  - fs/io_uring.c:io_ring_ctx_alloc
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:kjournald2
  - block/blk-core.c:blk_alloc_queue
  - block/blk-core.c:blk_alloc_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/genhd.c:__device_add_disk
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-iocost.c:blk_iocost_init
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/shpchp_core.c:init_slots
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_add_cursor_timer
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
  - drivers/xen/events/events_base.c:xen_cpu_init_eoi
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/sysrq.c:sysrq_connect
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_isa_init_ports
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/base/power/wakeup.c:wakeup_source_add
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-sff.c:ata_sff_port_init
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:__usb_create_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/host/ehci-platform.c:quirk_poll_init
  - drivers/usb/host/ehci-platform.c:quirk_poll_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-dbgcap.c:xhci_do_dbc_init
  - drivers/input/input.c:input_allocate_device
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_online
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_online
  - drivers/md/md.c:mddev_init
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_pci.c:edac_pci_add_device
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/leds/led-core.c:led_init_core
  - drivers/ras/cec.c:cec_init
  - net/core/sock.c:sock_init_data
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_alloc
  - net/core/netpoll.c:__netpoll_setup
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/devlink.c:devlink_port_register
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/ipmr_base.c:mr_table_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/packet/af_packet.c:packet_set_ring
  - net/strparser/strparser.c:strp_init
  - net/rfkill/core.c:rfkill_register
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
  - net/mptcp/protocol.c:__mptcp_init_sock
  - net/mptcp/protocol.c:__mptcp_init_sock
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
```
**Symbols:**

```
ffffffff81141d40-ffffffff81141dbd: init_timer_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void init_timer_key(struct timer_list *timer, void (*func)(struct timer_list *), unsigned int flags, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81d56192)
Location: kernel/time/timer.c:812
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/tsc_sync.c:start_sync_check_timer
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/sched/psi.c:group_init
  - kernel/sched/psi.c:group_init
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/srcutree.c:init_srcu_struct_nodes
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/jump_label.c:jump_label_rate_limit
  - mm/page-writeback.c:wb_domain_init
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:bdi_alloc
  - mm/backing-dev.c:wb_init
  - mm/backing-dev.c:wb_init
  - mm/page_reporting.c:page_reporting_register
  - fs/io_uring.c:io_ring_ctx_alloc
  - fs/io_uring.c:io_ring_ctx_alloc
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:kjournald2
  - block/blk-core.c:blk_alloc_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/disk-events.c:disk_alloc_events
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-iocost.c:blk_iocost_init
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/shpchp_core.c:init_slots
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_add_cursor_timer
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
  - drivers/xen/events/events_base.c:xen_cpu_init_eoi
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/sysrq.c:sysrq_connect
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_isa_init_ports
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/base/power/wakeup.c:wakeup_source_add
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/block/loop.c:loop_configure
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-sff.c:ata_sff_port_init
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/tun.c:tun_net_init
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:__usb_create_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/host/ehci-platform.c:quirk_poll_init
  - drivers/usb/host/ehci-platform.c:quirk_poll_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-dbgcap.c:xhci_do_dbc_init
  - drivers/input/input.c:input_allocate_device
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_online
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_online
  - drivers/md/md.c:mddev_init
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_pci.c:edac_pci_add_device
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/leds/led-core.c:led_init_core
  - drivers/ras/cec.c:cec_init
  - net/core/sock.c:sock_init_data
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_alloc
  - net/core/netpoll.c:__netpoll_setup
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/devlink.c:devlink_port_register
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/ipmr_base.c:mr_table_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/packet/af_packet.c:packet_set_ring
  - net/strparser/strparser.c:strp_init
  - net/rfkill/core.c:rfkill_register
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
  - net/mptcp/protocol.c:__mptcp_init_sock
  - net/mptcp/protocol.c:__mptcp_init_sock
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
```
**Symbols:**

```
ffffffff81164dd0-ffffffff81164e4a: init_timer_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void init_timer_key(struct timer_list *timer, void (*func)(struct timer_list *), unsigned int flags, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81f281a4)
Location: kernel/time/timer.c:865
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/tsc_sync.c:start_sync_check_timer
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/sched/build_utility.c:group_init
  - kernel/sched/build_utility.c:group_init
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/jump_label.c:jump_label_rate_limit
  - mm/page-writeback.c:wb_domain_init
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:bdi_alloc
  - mm/backing-dev.c:wb_init
  - mm/backing-dev.c:wb_init
  - mm/kfence/core.c:kfence_init_enable
  - mm/kfence/core.c:kfence_init_enable
  - mm/page_reporting.c:page_reporting_register
  - fs/ext4/super.c:__ext4_fill_super
  - fs/jbd2/journal.c:kjournald2
  - block/blk-core.c:blk_alloc_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/disk-events.c:disk_alloc_events
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-iocost.c:blk_iocost_init
  - io_uring/io_uring.c:io_ring_ctx_alloc
  - io_uring/io_uring.c:io_ring_ctx_alloc
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/shpchp_core.c:init_slots
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_open
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
  - drivers/xen/events/events_base.c:xen_cpu_init_eoi
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/sysrq.c:sysrq_connect
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_isa_init_ports
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
  - drivers/base/power/wakeup.c:wakeup_source_add
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-sff.c:ata_sff_port_init
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/tun.c:tun_net_init
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:__usb_create_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/host/ehci-platform.c:quirk_poll_init
  - drivers/usb/host/ehci-platform.c:quirk_poll_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-dbgcap.c:xhci_alloc_dbc
  - drivers/input/input.c:input_allocate_device
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_online
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_online
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
  - drivers/md/md.c:mddev_init
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_pci.c:edac_pci_add_device
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/leds/led-core.c:led_init_core
  - drivers/ras/cec.c:cec_init
  - net/core/sock.c:sock_init_data
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_alloc
  - net/core/netpoll.c:__netpoll_setup
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/devlink.c:devl_port_register
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/ipmr_base.c:mr_table_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/packet/af_packet.c:packet_set_ring
  - net/strparser/strparser.c:strp_init
  - net/rfkill/core.c:rfkill_register
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
  - net/mptcp/protocol.c:__mptcp_init_sock
  - net/mptcp/protocol.c:__mptcp_init_sock
  - net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list
  - net/mctp/af_mctp.c:mctp_sk_init
```
**Symbols:**

```
ffffffff81198980-ffffffff81198a1b: init_timer_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void init_timer_key(struct timer_list *timer, void (*func)(struct timer_list *), unsigned int flags, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff820d3d94)
Location: kernel/time/timer.c:865
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - arch/x86/kernel/tsc_sync.c:start_sync_check_timer
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/sched/build_utility.c:group_init
  - kernel/sched/build_utility.c:group_init
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/jump_label.c:jump_label_rate_limit
  - mm/page-writeback.c:wb_domain_init
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:bdi_alloc
  - mm/backing-dev.c:wb_init
  - mm/backing-dev.c:wb_init
  - mm/kfence/core.c:kfence_init_enable
  - mm/kfence/core.c:kfence_init_enable
  - mm/page_reporting.c:page_reporting_register
  - fs/ext4/super.c:__ext4_fill_super
  - fs/jbd2/journal.c:kjournald2
  - block/blk-core.c:blk_alloc_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/disk-events.c:disk_alloc_events
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - io_uring/io_uring.c:io_ring_ctx_alloc
  - io_uring/io_uring.c:io_ring_ctx_alloc
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/shpchp_core.c:init_slots
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_open
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
  - drivers/xen/events/events_base.c:xen_cpu_init_eoi
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/sysrq.c:sysrq_connect
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_isa_init_ports
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
  - drivers/base/power/wakeup.c:wakeup_source_add
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-sff.c:ata_sff_port_init
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/tun.c:tun_net_init
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:__usb_create_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/host/ehci-platform.c:quirk_poll_init
  - drivers/usb/host/ehci-platform.c:quirk_poll_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-dbgcap.c:xhci_alloc_dbc
  - drivers/input/input.c:input_allocate_device
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_online
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_online
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
  - drivers/md/md.c:mddev_init
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_pci.c:edac_pci_add_device
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/leds/led-core.c:led_init_core
  - drivers/ras/cec.c:cec_init
  - net/core/sock.c:sock_init_data_uid
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_alloc
  - net/core/netpoll.c:__netpoll_setup
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/devlink.c:devl_port_register
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/ipmr_base.c:mr_table_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/packet/af_packet.c:packet_set_ring
  - net/strparser/strparser.c:strp_init
  - net/rfkill/core.c:rfkill_register
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
  - net/mptcp/protocol.c:__mptcp_init_sock
  - net/mptcp/protocol.c:__mptcp_init_sock
  - net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list
  - net/mctp/af_mctp.c:mctp_sk_init
```
**Symbols:**

```
ffffffff811d6d20-ffffffff811d6dbb: init_timer_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void init_timer_key(struct timer_list *timer, void (*func)(struct timer_list *), unsigned int flags, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff82158014)
Location: kernel/time/timer.c:865
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - arch/x86/kernel/tsc_sync.c:start_sync_check_timer
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/sched/build_utility.c:group_init
  - kernel/sched/build_utility.c:group_init
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/tree.c:kfree_rcu_batch_init
  - kernel/rcu/tree.c:kfree_rcu_batch_init
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/jump_label.c:jump_label_rate_limit
  - mm/page-writeback.c:wb_domain_init
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:bdi_alloc
  - mm/backing-dev.c:wb_init
  - mm/backing-dev.c:wb_init
  - mm/kfence/core.c:kfence_init_enable
  - mm/kfence/core.c:kfence_init_enable
  - mm/page_reporting.c:page_reporting_register
  - fs/ext4/super.c:__ext4_fill_super
  - fs/jbd2/journal.c:kjournald2
  - block/blk-core.c:blk_alloc_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/disk-events.c:disk_alloc_events
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-iocost.c:blk_iocost_init
  - io_uring/io_uring.c:io_ring_ctx_alloc
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/shpchp_core.c:init_slots
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_open
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
  - drivers/xen/events/events_base.c:xen_cpu_init_eoi
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/sysrq.c:sysrq_connect
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_setup_port
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
  - drivers/base/power/wakeup.c:wakeup_source_add
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-sff.c:ata_sff_port_init
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/tun.c:tun_net_init
  - drivers/net/virtio_net.c:virtnet_alloc_queues
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:__usb_create_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/host/ehci-platform.c:quirk_poll_init
  - drivers/usb/host/ehci-platform.c:quirk_poll_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-dbgcap.c:xhci_alloc_dbc
  - drivers/input/input.c:input_allocate_device
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_online
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_online
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
  - drivers/md/md.c:mddev_init
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_pci.c:edac_pci_add_device
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/leds/led-core.c:led_init_core
  - drivers/ras/cec.c:cec_init
  - net/core/sock.c:sock_init_data_uid
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_alloc
  - net/core/netpoll.c:__netpoll_setup
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/skmsg.c:sk_psock_init
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/ipmr_base.c:mr_table_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/packet/af_packet.c:packet_set_ring
  - net/devlink/leftover.c:devl_port_register_with_ops
  - net/strparser/strparser.c:strp_init
  - net/rfkill/core.c:rfkill_register
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
  - net/mptcp/protocol.c:__mptcp_init_sock
  - net/mptcp/protocol.c:__mptcp_init_sock
  - net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list
  - net/mctp/af_mctp.c:mctp_sk_init
```
**Symbols:**

```
ffffffff811eb1b0-ffffffff811eb24b: init_timer_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void init_timer_key(struct timer_list *timer, void (*func)(struct timer_list *), unsigned int flags, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8223ae84)
Location: kernel/time/timer.c:862
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - arch/x86/kernel/tsc_sync.c:start_sync_check_timer
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/sched/core.c:sched_cpu_starting
  - kernel/sched/build_utility.c:group_init
  - kernel/sched/build_utility.c:group_init
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/tree.c:kfree_rcu_batch_init
  - kernel/rcu/tree.c:kfree_rcu_batch_init
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/jump_label.c:jump_label_rate_limit
  - mm/page-writeback.c:wb_domain_init
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:bdi_alloc
  - mm/backing-dev.c:wb_init
  - mm/backing-dev.c:wb_init
  - mm/kfence/core.c:kfence_init_enable
  - mm/kfence/core.c:kfence_init_enable
  - mm/page_reporting.c:page_reporting_register
  - fs/ext4/super.c:__ext4_fill_super
  - fs/jbd2/journal.c:kjournald2
  - block/blk-core.c:blk_alloc_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/disk-events.c:disk_alloc_events
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-iocost.c:blk_iocost_init
  - io_uring/io_uring.c:io_ring_ctx_alloc
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/shpchp_core.c:init_slots
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_open
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
  - drivers/xen/events/events_base.c:xen_cpu_init_eoi
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/sysrq.c:sysrq_connect
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_setup_port
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
  - drivers/base/power/wakeup.c:wakeup_source_add
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-sff.c:ata_sff_port_init
  - drivers/gpu/drm/drm_probe_helper.c:drm_kms_helper_poll_init
  - drivers/gpu/drm/drm_self_refresh_helper.c:drm_self_refresh_helper_init
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/tun.c:tun_net_init
  - drivers/net/virtio_net.c:virtnet_alloc_queues
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:__usb_create_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/host/ehci-platform.c:quirk_poll_init
  - drivers/usb/host/ehci-platform.c:quirk_poll_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-dbgcap.c:xhci_alloc_dbc
  - drivers/input/input.c:input_allocate_device
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/thermal/thermal_core.c:thermal_pm_notify
  - drivers/thermal/thermal_core.c:thermal_zone_device_resume
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_online
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_online
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
  - drivers/md/md.c:mddev_init
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_pci.c:edac_pci_add_device
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/leds/led-core.c:led_init_core
  - drivers/ras/cec.c:cec_init
  - net/core/sock.c:sock_init_data_uid
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_alloc
  - net/core/netpoll.c:__netpoll_setup
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/skmsg.c:sk_psock_init
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/ipmr_base.c:mr_table_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/packet/af_packet.c:packet_set_ring
  - net/devlink/core.c:devlink_rel_nested_in_add
  - net/devlink/port.c:devl_port_register_with_ops
  - net/strparser/strparser.c:strp_init
  - net/rfkill/core.c:rfkill_register
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
  - net/mptcp/protocol.c:__mptcp_init_sock
  - net/mptcp/protocol.c:__mptcp_init_sock
  - net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list
  - net/mctp/af_mctp.c:mctp_sk_init
```
**Symbols:**

```
ffffffff812011e0-ffffffff8120127b: init_timer_key (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void init_timer_key(struct timer_list *timer, void (*func)(struct timer_list *), unsigned int flags, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffff800010da6374)
Location: kernel/time/timer.c:800
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
Direct callers:
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/sched/psi.c:group_init
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/jump_label.c:jump_label_rate_limit
  - mm/page-writeback.c:wb_domain_init
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:wb_init
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:kjournald2
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/genhd.c:__device_add_disk
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-iocost.c:blk_iocost_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_add_cursor_timer
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/xen/grant-table.c:gnttab_unmap_refs_async
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/sysrq.c:sysrq_connect
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_isa_init_ports
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/base/power/wakeup.c:wakeup_source_add
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-sff.c:ata_sff_port_init
  - drivers/ata/libahci.c:ahci_port_resume
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_init
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:__usb_create_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/input/input.c:input_allocate_device
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/md/md.c:mddev_init
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/leds/led-core.c:led_init_core
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - net/core/sock.c:sock_init_data
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:___neigh_create
  - net/core/netpoll.c:__netpoll_setup
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/devlink.c:devlink_port_register
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr_base.c:mr_table_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/packet/af_packet.c:packet_set_ring
  - net/strparser/strparser.c:strp_init
  - net/rfkill/core.c:rfkill_register
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
```
**Symbols:**

```
ffff80001019e0b0-ffff80001019e18c: init_timer_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void init_timer_key(struct timer_list *timer, void (*func)(struct timer_list *), unsigned int flags, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c0e9df88)
Location: kernel/time/timer.c:800
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
Direct callers:
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/sched/psi.c:group_init
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - mm/page-writeback.c:wb_domain_init
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:wb_init
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:kjournald2
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/genhd.c:__device_add_disk
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-iocost.c:blk_iocost_init
  - drivers/bus/ti-sysc.c:sysc_probe
  - drivers/video/fbdev/core/fbcon.c:fbcon_add_cursor_timer
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/sysrq.c:sysrq_connect
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_isa_init_ports
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/base/power/wakeup.c:wakeup_source_add
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-sff.c:ata_sff_port_init
  - drivers/ata/libahci.c:ahci_port_resume
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_init
  - drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_start
  - drivers/auxdisplay/arm-charlcd.c:charlcd_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:__usb_create_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/usb/musb/musb_core.c:musb_init_controller
  - drivers/usb/musb/musb_core.c:musb_init_controller
  - drivers/usb/musb/musb_core.c:musb_init_controller
  - drivers/usb/musb/musb_core.c:musb_init_controller
  - drivers/usb/musb/musb_gadget.c:musb_gadget_setup
  - drivers/input/input.c:input_allocate_device
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/md/md.c:mddev_init
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/host/sdhci.c:__sdhci_add_host
  - drivers/mmc/host/sdhci.c:__sdhci_add_host
  - drivers/leds/led-core.c:led_init_core
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - sound/core/timer.c:alsa_timer_init
  - sound/core/compress_offload.c:snd_compr_open
  - sound/soc/soc-jack.c:snd_soc_jack_add_gpios
  - sound/soc/soc-pcm.c:soc_new_pcm
  - sound/soc/soc-pcm.c:soc_new_pcm
  - sound/soc/soc-compress.c:snd_soc_new_compress
  - net/core/sock.c:sock_init_data
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:___neigh_create
  - net/core/netpoll.c:__netpoll_setup
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/devlink.c:devlink_port_register
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr_base.c:mr_table_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/packet/af_packet.c:packet_set_ring
  - net/strparser/strparser.c:strp_init
  - net/rfkill/core.c:rfkill_register
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
```
**Symbols:**

```
c03e7dac-c03e7e70: init_timer_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void init_timer_key(struct timer_list *timer, void (*func)(struct timer_list *), unsigned int flags, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c000000000ee8960)
Location: kernel/time/timer.c:800
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
Direct callers:
  - arch/powerpc/platforms/pseries/lpar.c:dtl_worker_online
  - arch/powerpc/platforms/pseries/vio.c:vio_bus_init
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/sched/psi.c:group_init
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/jump_label.c:jump_label_rate_limit
  - mm/page-writeback.c:wb_domain_init
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:wb_init
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:kjournald2
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/genhd.c:__device_add_disk
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-iocost.c:blk_iocost_init
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_add_cursor_timer
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/sysrq.c:sysrq_connect
  - drivers/tty/hvc/hvsi.c:hvsi_console_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_isa_init_ports
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/base/power/wakeup.c:wakeup_source_add
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_transport_srp.c:srp_rport_add
  - drivers/scsi/scsi_transport_srp.c:srp_rport_add
  - drivers/scsi/scsi_transport_srp.c:srp_rport_add
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-sff.c:ata_sff_port_init
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:__usb_create_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/input/input.c:input_allocate_device
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/md/md.c:mddev_init
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_cpu_init
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/leds/led-core.c:led_init_core
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - net/core/sock.c:sock_init_data
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:___neigh_create
  - net/core/netpoll.c:__netpoll_setup
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/devlink.c:devlink_port_register
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr_base.c:mr_table_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/packet/af_packet.c:packet_set_ring
  - net/strparser/strparser.c:strp_init
  - net/rfkill/core.c:rfkill_register
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
```
**Symbols:**

```
c0000000001fe670-c0000000001fe77c: init_timer_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void init_timer_key(struct timer_list *timer, void (*func)(struct timer_list *), unsigned int flags, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffe0008c86a4)
Location: kernel/time/timer.c:800
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
Direct callers:
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/sched/psi.c:group_init
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - mm/page-writeback.c:wb_domain_init
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:wb_init
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:kjournald2
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/genhd.c:__device_add_disk
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-iocost.c:blk_iocost_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_add_cursor_timer
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/sysrq.c:sysrq_connect
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_isa_init_ports
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-sff.c:ata_sff_port_init
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:__usb_create_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/input/input.c:input_allocate_device
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/md/md.c:mddev_init
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/leds/led-core.c:led_init_core
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - net/core/sock.c:sock_init_data
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:___neigh_create
  - net/core/netpoll.c:__netpoll_setup
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/devlink.c:devlink_port_register
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr_base.c:mr_table_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/packet/af_packet.c:packet_set_ring
  - net/strparser/strparser.c:strp_init
  - net/rfkill/core.c:rfkill_register
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
```
**Symbols:**

```
ffffffe00012c41e-ffffffe00012c4b8: init_timer_key (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void init_timer_key(struct timer_list *timer, void (*func)(struct timer_list *), unsigned int flags, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81a72529)
Location: kernel/time/timer.c:800
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_timer
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/sched/psi.c:group_init
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/jump_label.c:jump_label_rate_limit
  - mm/page-writeback.c:wb_domain_init
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:wb_init
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:kjournald2
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/genhd.c:__device_add_disk
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-iocost.c:blk_iocost_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_add_cursor_timer
  - drivers/xen/grant-table.c:gnttab_unmap_refs_async
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/sysrq.c:sysrq_connect
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_isa_init_ports
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/base/power/wakeup.c:wakeup_source_add
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/nvme/host/core.c:nvme_init_ctrl
  - drivers/nvme/host/multipath.c:nvme_mpath_init
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-sff.c:ata_sff_port_init
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:__usb_create_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/input/input.c:input_allocate_device
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/md/md.c:mddev_init
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/leds/led-core.c:led_init_core
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/ras/cec.c:cec_init
  - net/core/sock.c:sock_init_data
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:___neigh_create
  - net/core/netpoll.c:__netpoll_setup
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/devlink.c:devlink_port_register
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr_base.c:mr_table_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/packet/af_packet.c:packet_set_ring
  - net/strparser/strparser.c:strp_init
  - net/rfkill/core.c:rfkill_register
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
```
**Symbols:**

```
ffffffff8112dcf0-ffffffff8112dd6f: init_timer_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void init_timer_key(struct timer_list *timer, void (*func)(struct timer_list *), unsigned int flags, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81a2e8f9)
Location: kernel/time/timer.c:800
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_timer
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/sched/core.c:sched_cpu_starting
  - kernel/sched/psi.c:group_init
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/jump_label.c:jump_label_rate_limit
  - mm/page-writeback.c:wb_domain_init
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:wb_init
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:kjournald2
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/genhd.c:__device_add_disk
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-iocost.c:blk_iocost_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_add_cursor_timer
  - drivers/acpi/nfit/core.c:acpi_nfit_desc_init
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/sysrq.c:sysrq_connect
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_isa_init_ports
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/base/power/wakeup.c:wakeup_source_add
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_transport_fc.c:fc_remote_port_create
  - drivers/scsi/scsi_transport_fc.c:fc_remote_port_create
  - drivers/nvme/host/core.c:nvme_init_ctrl
  - drivers/nvme/host/multipath.c:nvme_mpath_init
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-sff.c:ata_sff_port_init
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/vxlan.c:vxlan_setup
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:__usb_create_hcd
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/input/input.c:input_allocate_device
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/md/md.c:mddev_init
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/leds/led-core.c:led_init_core
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/ras/cec.c:cec_init
  - net/core/sock.c:sock_init_data
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:___neigh_create
  - net/core/netpoll.c:__netpoll_setup
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/devlink.c:devlink_port_register
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr_base.c:mr_table_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/packet/af_packet.c:packet_set_ring
  - net/strparser/strparser.c:strp_init
  - net/rfkill/core.c:rfkill_register
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
```
**Symbols:**

```
ffffffff81120580-ffffffff811205ff: init_timer_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void init_timer_key(struct timer_list *timer, void (*func)(struct timer_list *), unsigned int flags, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81ade939)
Location: kernel/time/timer.c:800
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_timer
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/sched/psi.c:group_init
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/jump_label.c:jump_label_rate_limit
  - mm/page-writeback.c:wb_domain_init
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:wb_init
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:kjournald2
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/genhd.c:__device_add_disk
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-iocost.c:blk_iocost_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_add_cursor_timer
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/xen/grant-table.c:gnttab_unmap_refs_async
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/sysrq.c:sysrq_connect
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_isa_init_ports
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/base/power/wakeup.c:wakeup_source_add
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-sff.c:ata_sff_port_init
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:__usb_create_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/input/input.c:input_allocate_device
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/md/md.c:mddev_init
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/leds/led-core.c:led_init_core
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/ras/cec.c:cec_init
  - net/core/sock.c:sock_init_data
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:___neigh_create
  - net/core/netpoll.c:__netpoll_setup
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/devlink.c:devlink_port_register
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/netfilter/nfnetlink_log.c:nfulnl_recv_config
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_init_start
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expect_related_report
  - net/netfilter/nf_conntrack_ecache.c:nf_conntrack_ecache_pernet_init
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr_base.c:mr_table_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/packet/af_packet.c:packet_set_ring
  - net/strparser/strparser.c:strp_init
  - net/rfkill/core.c:rfkill_register
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
```
**Symbols:**

```
ffffffff8112ba10-ffffffff8112ba8f: init_timer_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void init_timer_key(struct timer_list *timer, void (*func)(struct timer_list *), unsigned int flags, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81aeadb9)
Location: kernel/time/timer.c:800
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_timer
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat_enable
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/sched/psi.c:group_init
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/jump_label.c:jump_label_rate_limit
  - mm/page-writeback.c:wb_domain_init
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:wb_init
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:kjournald2
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/genhd.c:__device_add_disk
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-iocost.c:blk_iocost_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_add_cursor_timer
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/xen/grant-table.c:gnttab_unmap_refs_async
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/sysrq.c:sysrq_connect
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_isa_init_ports
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/base/power/wakeup.c:wakeup_source_add
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-sff.c:ata_sff_port_init
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:__usb_create_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/input/input.c:input_allocate_device
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/md/md.c:mddev_init
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/leds/led-core.c:led_init_core
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/ras/cec.c:cec_init
  - net/core/sock.c:sock_init_data
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:___neigh_create
  - net/core/netpoll.c:__netpoll_setup
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/devlink.c:devlink_port_register
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/inet_connection_sock.c:inet_csk_init_xmit_timers
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr_base.c:mr_table_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/packet/af_packet.c:packet_set_ring
  - net/strparser/strparser.c:strp_init
  - net/rfkill/core.c:rfkill_register
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
```
**Symbols:**

```
ffffffff811380c0-ffffffff81138154: init_timer_key (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void (*func)(struct timer_list *)</code>
</li>
<li>
<b>Param reordered. </b>
<code>timer, flags, name, key</code> ➡️ <code>timer, func, flags, name, key</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
