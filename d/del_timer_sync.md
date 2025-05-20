# Function: <code>del_timer_sync</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810ec5c0)
Location: kernel/time/timer.c:1103
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_delete_all
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_callback
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:flush_delayed_work
  - kernel/time/timer.c:schedule_timeout
  - kernel/relay.c:__relay_reset
  - kernel/relay.c:relay_close_buf
  - kernel/padata.c:padata_flush_queues
  - mm/page-writeback.c:wb_domain_exit
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - block/blk-core.c:blk_sync_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-throttle.c:throtl_pd_free
  - block/cfq-iosched.c:cfq_exit_queue
  - block/cfq-iosched.c:cfq_exit_queue
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
  - drivers/video/console/fbcon.c:fbcon_deinit
  - drivers/video/console/fbcon.c:fbcon_deinit
  - drivers/video/console/fbcon.c:fbcon_cursor
  - drivers/video/console/fbcon.c:fbcon_blank
  - drivers/video/console/fbcon.c:fbcon_switch
  - drivers/video/console/fbcon.c:fbcon_switch
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm-dev.c:tpm_release
  - drivers/char/tpm/tpm-dev.c:tpm_read
  - drivers/base/power/wakeup.c:wakeup_source_destroy
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/input.c:__input_unregister_device
  - drivers/md/md.c:level_store
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_stop_cpu
  - drivers/mmc/core/host.c:mmc_retune_timer_stop
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:set_brightness_delayed
  - net/core/neighbour.c:neigh_ifdown
  - net/core/neighbour.c:neigh_table_clear
  - net/core/flow.c:flow_cache_fini
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/ipv6/ip6_fib.c:fib6_net_exit
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff810ec5c0-ffffffff810ec60f: del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810f3c90)
Location: kernel/time/timer.c:1244
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_callback
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_delete_all
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:worker_thread
  - kernel/time/timer.c:schedule_timeout
  - kernel/relay.c:relay_close_buf
  - kernel/relay.c:__relay_reset
  - kernel/padata.c:padata_flush_queues
  - mm/page-writeback.c:wb_domain_exit
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_sync_queue
  - block/blk-throttle.c:throtl_pd_free
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/video/console/fbcon.c:fbcon_blank
  - drivers/video/console/fbcon.c:fbcon_switch
  - drivers/video/console/fbcon.c:fbcon_switch
  - drivers/video/console/fbcon.c:fbcon_cursor
  - drivers/video/console/fbcon.c:fbcon_deinit
  - drivers/video/console/fbcon.c:fbcon_deinit
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm-dev.c:tpm_release
  - drivers/char/tpm/tpm-dev.c:tpm_read
  - drivers/base/power/wakeup.c:wakeup_source_destroy
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/input.c:__input_unregister_device
  - drivers/md/md.c:level_store
  - drivers/mmc/core/host.c:mmc_retune_timer_stop
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:set_brightness_delayed
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:neigh_ifdown
  - net/core/flow.c:flow_cache_fini
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/ipv6/ip6_fib.c:fib6_net_exit
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/packet/af_packet.c:packet_set_ring
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor
```
**Symbols:**

```
ffffffff810f3c90-ffffffff810f3cdf: del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810facf0)
Location: kernel/time/timer.c:1254
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_delete_all
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:__kthread_cancel_work
  - kernel/time/timer.c:schedule_timeout
  - kernel/padata.c:padata_flush_queues
  - mm/page-writeback.c:wb_domain_exit
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_sync_queue
  - block/blk-throttle.c:throtl_pd_free
  - block/blk-wbt.c:wbt_exit
  - block/blk-wbt.c:wbt_disable_default
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/video/console/fbcon.c:fbcon_blank
  - drivers/video/console/fbcon.c:fbcon_switch
  - drivers/video/console/fbcon.c:fbcon_switch
  - drivers/video/console/fbcon.c:fbcon_cursor
  - drivers/video/console/fbcon.c:fbcon_deinit
  - drivers/video/console/fbcon.c:fbcon_deinit
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm-dev.c:tpm_release
  - drivers/char/tpm/tpm-dev.c:tpm_read
  - drivers/base/power/wakeup.c:wakeup_source_destroy
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/input.c:__input_unregister_device
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:level_store
  - drivers/mmc/core/host.c:mmc_retune_timer_stop
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/leds/led-core.c:led_stop_software_blink
  - drivers/leds/led-core.c:led_blink_set
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:neigh_ifdown
  - net/core/flow.c:flow_cache_fini
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/ipv6/ip6_fib.c:fib6_net_exit
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/packet/af_packet.c:packet_set_ring
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor
```
**Symbols:**

```
ffffffff810facf0-ffffffff810fad3f: del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810fd030)
Location: kernel/time/timer.c:1227
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_delete_all
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:__kthread_cancel_work
  - kernel/time/timer.c:schedule_timeout
  - kernel/padata.c:padata_flush_queues
  - mm/page-writeback.c:wb_domain_exit
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/pstore/platform.c:pstore_unregister
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-throttle.c:throtl_pd_free
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/video/console/fbcon.c:fbcon_blank
  - drivers/video/console/fbcon.c:fbcon_switch
  - drivers/video/console/fbcon.c:fbcon_switch
  - drivers/video/console/fbcon.c:fbcon_cursor
  - drivers/video/console/fbcon.c:fbcon_deinit
  - drivers/video/console/fbcon.c:fbcon_deinit
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/input.c:__input_unregister_device
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:level_store
  - drivers/mmc/core/host.c:mmc_retune_timer_stop
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/leds/led-core.c:led_stop_software_blink
  - drivers/leds/led-core.c:led_blink_set
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:neigh_ifdown
  - net/core/flow.c:flow_cache_fini
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/ipmr.c:ipmr_free_table
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/ipv6/ip6_fib.c:fib6_net_exit
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/packet/af_packet.c:packet_set_ring
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor
```
**Symbols:**

```
ffffffff810fd030-ffffffff810fd070: del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81107810)
Location: kernel/time/timer.c:1265
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_delete_all
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:__kthread_cancel_work
  - kernel/time/timer.c:schedule_timeout
  - kernel/padata.c:padata_flush_queues
  - mm/page-writeback.c:wb_domain_exit
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/pstore/platform.c:pstore_unregister
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-throttle.c:throtl_pd_free
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/input.c:__input_unregister_device
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:level_store
  - drivers/mmc/core/host.c:mmc_retune_timer_stop
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/leds/led-core.c:led_stop_software_blink
  - drivers/leds/led-core.c:led_blink_set
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:neigh_ifdown
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/ipmr.c:ipmr_free_table
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/ipv6/ip6_fib.c:fib6_net_exit
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/packet/af_packet.c:packet_set_ring
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor
```
**Symbols:**

```
ffffffff81107810-ffffffff81107850: del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811132c0)
Location: kernel/time/timer.c:1273
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_delete_all
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:__kthread_cancel_work
  - kernel/time/timer.c:schedule_timeout
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/padata.c:padata_flush_queues
  - mm/page-writeback.c:wb_domain_exit
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/pstore/platform.c:pstore_unregister
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-throttle.c:throtl_pd_free
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/input.c:__input_unregister_device
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:level_store
  - drivers/mmc/core/host.c:mmc_retune_timer_stop
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/leds/led-core.c:led_stop_software_blink
  - drivers/leds/led-core.c:led_blink_set
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:neigh_ifdown
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/ipmr.c:ipmr_free_table
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/ipv6/ip6_fib.c:fib6_net_exit
  - net/ipv6/ip6mr.c:ip6mr_free_table
  - net/packet/af_packet.c:packet_set_ring
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor
```
**Symbols:**

```
ffffffff811132c0-ffffffff81113300: del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8111d5e0)
Location: kernel/time/timer.c:1272
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_delete_all
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:__kthread_cancel_work
  - kernel/time/timer.c:schedule_timeout
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/padata.c:padata_flush_queues
  - mm/page-writeback.c:wb_domain_exit
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/pstore/platform.c:pstore_unregister
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-throttle.c:throtl_pd_free
  - block/blk-wbt.c:wbt_disable_default
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/input.c:__input_unregister_device
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:level_store
  - drivers/mmc/core/host.c:mmc_retune_timer_stop
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/leds/led-core.c:led_stop_software_blink
  - drivers/leds/led-core.c:led_blink_set
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:__neigh_ifdown
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/ipmr.c:ipmr_free_table
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
  - net/ipv6/ip6_fib.c:fib6_net_exit
  - net/ipv6/ip6mr.c:ip6mr_free_table
  - net/packet/af_packet.c:packet_set_ring
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor
```
**Symbols:**

```
ffffffff8111d5e0-ffffffff8111d620: del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timer.c (0)
Location: kernel/time/timer.c:1267
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_delete_all
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:__kthread_cancel_work
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/time/timer.c:schedule_timeout
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/padata.c:padata_flush_queues
  - mm/page-writeback.c:wb_domain_exit
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/pstore/platform.c:pstore_unregister
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-throttle.c:throtl_pd_free
  - block/blk-wbt.c:wbt_disable_default
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/input.c:__input_unregister_device
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:level_store
  - drivers/mmc/core/host.c:mmc_retune_timer_stop
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/leds/led-core.c:led_stop_software_blink
  - drivers/leds/led-core.c:led_blink_set
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:__neigh_ifdown
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
  - net/ipv4/ipmr.c:ipmr_free_table
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
  - net/ipv6/ip6_fib.c:fib6_net_exit
  - net/ipv6/ip6mr.c:ip6mr_free_table
  - net/packet/af_packet.c:packet_set_ring
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor
```
**Symbols:**

```
ffffffff8112b1c1-ffffffff8112b1d4: del_timer_sync.cold (STB_LOCAL)
ffffffff81129270-ffffffff811292a8: del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81135210)
Location: kernel/time/timer.c:1342
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_delete_all
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:__kthread_cancel_work
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/time/timer.c:schedule_timeout
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - mm/page-writeback.c:wb_domain_exit
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/pstore/platform.c:pstore_unregister
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-throttle.c:throtl_pd_free
  - block/blk-iocost.c:ioc_rqos_exit
  - block/blk-wbt.c:wbt_disable_default
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/input.c:__input_unregister_device
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:level_store
  - drivers/mmc/core/host.c:mmc_retune_timer_stop
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/leds/led-core.c:led_stop_software_blink
  - drivers/leds/led-core.c:led_blink_set
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
  - net/ipv4/ipmr.c:ipmr_free_table
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
  - net/ipv6/ip6_fib.c:fib6_net_exit
  - net/ipv6/ip6mr.c:ip6mr_free_table
  - net/packet/af_packet.c:packet_set_ring
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor
```
**Symbols:**

```
ffffffff81135210-ffffffff81135248: del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811443b0)
Location: kernel/time/timer.c:1354
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:maybe_create_worker
  - kernel/kthread.c:__kthread_cancel_work
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/time/timer.c:schedule_timeout
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - mm/page-writeback.c:wb_domain_exit
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-throttle.c:throtl_pd_free
  - block/blk-iocost.c:ioc_rqos_exit
  - block/blk-wbt.c:wbt_disable_default
  - drivers/video/fbdev/core/fbcon.c:fbcon_exit
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/host/ehci-platform.c:ehci_platform_suspend
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status
  - drivers/input/input.c:__input_unregister_device
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:level_store
  - drivers/mmc/core/host.c:mmc_retune_timer_stop
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:set_brightness_delayed
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_clear
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_connection_sock.c:reqsk_queue_unlink
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
  - net/ipv4/ipmr.c:ipmr_rules_exit
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
  - net/ipv6/ip6_fib.c:fib6_net_exit
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/packet/af_packet.c:packet_set_ring
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_stop_dev
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff811443b0-ffffffff81144457: del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81140940)
Location: kernel/time/timer.c:1348
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:maybe_create_worker
  - kernel/kthread.c:__kthread_cancel_work
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/time/timer.c:schedule_timeout
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - mm/page-writeback.c:wb_domain_exit
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-throttle.c:throtl_pd_free
  - block/blk-iocost.c:ioc_rqos_exit
  - block/blk-wbt.c:wbt_disable_default
  - drivers/video/fbdev/core/fbcon.c:fbcon_exit
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/host/ehci-platform.c:ehci_platform_suspend
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status
  - drivers/input/input.c:__input_unregister_device
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:level_store
  - drivers/mmc/core/host.c:mmc_retune_timer_stop
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:set_brightness_delayed
  - net/core/sock.c:sk_stop_timer_sync
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_clear
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_connection_sock.c:reqsk_queue_unlink
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
  - net/ipv4/ipmr.c:ipmr_rules_exit
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
  - net/ipv6/ip6_fib.c:fib6_net_exit
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/packet/af_packet.c:packet_set_ring
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_stop_dev
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff81140940-ffffffff811409e7: del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81141b90)
Location: kernel/time/timer.c:1366
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:__kthread_cancel_work_sync
  - kernel/kthread.c:kthread_mod_delayed_work
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/time/timer.c:schedule_timeout
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - mm/page-writeback.c:wb_domain_exit
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-throttle.c:throtl_pd_free
  - block/blk-iocost.c:ioc_rqos_exit
  - block/blk-wbt.c:wbt_disable_default
  - drivers/video/fbdev/core/fbcon.c:fbcon_exit
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/host/ehci-platform.c:ehci_platform_suspend
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status
  - drivers/input/input.c:__input_unregister_device
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:level_store
  - drivers/mmc/core/host.c:mmc_retune_timer_stop
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:set_brightness_delayed
  - net/core/sock.c:sk_stop_timer_sync
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_clear
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
  - net/ipv4/ipmr.c:ipmr_rules_exit
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
  - net/ipv6/ip6_fib.c:fib6_net_exit
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/packet/af_packet.c:packet_set_ring
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_stop_dev
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
```
**Symbols:**

```
ffffffff81141b90-ffffffff81141c37: del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81165000)
Location: kernel/time/timer.c:1352
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:__kthread_cancel_work_sync
  - kernel/kthread.c:kthread_mod_delayed_work
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/time/timer.c:schedule_timeout
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - mm/page-writeback.c:wb_domain_exit
  - mm/backing-dev.c:bdi_unregister
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:throtl_pd_free
  - block/blk-iocost.c:ioc_rqos_exit
  - block/blk-wbt.c:wbt_disable_default
  - drivers/video/fbdev/core/fbcon.c:fbcon_exit
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_net_init
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_stop_hcd
  - drivers/usb/core/hcd.c:usb_stop_hcd
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/host/ehci-platform.c:ehci_platform_suspend
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status
  - drivers/input/input.c:__input_unregister_device
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:level_store
  - drivers/mmc/core/host.c:mmc_retune_timer_stop
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:set_brightness_delayed
  - net/core/sock.c:sk_stop_timer_sync
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_clear
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
  - net/ipv4/ipmr.c:ipmr_rules_exit
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
  - net/ipv6/ip6_fib.c:fib6_net_exit
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/packet/af_packet.c:packet_set_ring
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor
```
**Symbols:**

```
ffffffff81165000-ffffffff811650a7: del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81198c30)
Location: kernel/time/timer.c:1405
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:__kthread_cancel_work_sync
  - kernel/kthread.c:kthread_mod_delayed_work
  - kernel/time/timer.c:schedule_timeout
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - mm/page-writeback.c:wb_domain_exit
  - mm/backing-dev.c:bdi_unregister
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:throtl_pd_free
  - block/blk-iocost.c:ioc_rqos_exit
  - block/blk-wbt.c:wbt_disable_default
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/iommu/dma-iommu.c:iommu_put_dma_cookie
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/block/loop.c:lo_free_disk
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_net_init
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_stop_hcd
  - drivers/usb/core/hcd.c:usb_stop_hcd
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/host/ehci-platform.c:ehci_platform_suspend
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status
  - drivers/input/input.c:__input_unregister_device
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:level_store
  - drivers/mmc/core/host.c:mmc_retune_timer_stop
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:set_brightness_delayed
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_clear
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
  - net/ipv4/ipmr.c:ipmr_rules_exit
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
  - net/ipv6/ip6_fib.c:fib6_net_exit
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/packet/af_packet.c:packet_set_ring
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor
  - net/mctp/af_mctp.c:mctp_sk_close
```
**Symbols:**

```
ffffffff81198c30-ffffffff81198cec: del_timer_sync (STB_GLOBAL)
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff81077cc5)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_delete_all
```
```
In kernel/workqueue.c (ffffffff81110092)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:worker_thread
```
```
In kernel/kthread.c (ffffffff8111d464)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_cancel_work_sync
  - kernel/kthread.c:kthread_mod_delayed_work
```
```
In kernel/rcu/srcutree.c (ffffffff811ad56a)
Location: include/linux/timer.h:198
Inline: True
```
```
In kernel/time/timer.c (ffffffff820d3dc5)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In kernel/cgroup/cgroup.c (ffffffff812044e8)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
```
In mm/page-writeback.c (ffffffff81369e25)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_domain_exit
```
```
In mm/backing-dev.c (ffffffff8139793d)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In fs/ext4/super.c (ffffffff815cc2d2)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
```
```
In fs/jbd2/journal.c (ffffffff815e894b)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/pstore/platform.c (ffffffff81639119)
Location: include/linux/timer.h:198
Inline: True
```
```
In block/blk-core.c (ffffffff81733805)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - block/blk-core.c:blk_sync_queue
```
```
In block/blk-stat.c (ffffffff8174ca39)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_remove_callback
```
```
In block/blk-throttle.c (ffffffff81769b2a)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:throtl_pd_free
```
```
In block/blk-wbt.c (ffffffff8177a08c)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_disable_default
```
```
In drivers/tty/vt/keyboard.c (ffffffff81a603c5)
Location: include/linux/timer.h:198
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff81a67c43)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_blank_screen
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81a7a745)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81a8c242)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
```
```
In drivers/char/random.c (ffffffff81a94dec)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81aa606b)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad710f)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_put_dma_cookie
```
```
In drivers/base/power/wakeup.c (ffffffff81b07d16)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_remove
```
```
In drivers/ata/libata-eh.c (ffffffff81bbb0cc)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/net/tun.c (ffffffff81beca4b)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_net_init
```
```
In drivers/net/xen-netfront.c (ffffffff81c051db)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
```
In drivers/usb/core/hub.c (ffffffff81c183b4)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_quiesce
```
```
In drivers/usb/core/hcd.c (ffffffff81c1d745)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_stop_hcd
  - drivers/usb/core/hcd.c:usb_stop_hcd
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81c506b5)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81c64beb)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_suspend
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81c69ee6)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81c71928)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
```
```
In drivers/usb/host/xhci.c (ffffffff81c7930d)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81c8debe)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status
```
```
In drivers/input/input.c (ffffffff81ca9efc)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/input/input.c:__input_unregister_device
```
```
In drivers/md/md.c (ffffffff81cfc512)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:level_store
```
```
In drivers/mmc/core/host.c (ffffffff81d4bd85)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_timer_stop
  - drivers/mmc/core/host.c:mmc_retune_disable
```
```
In drivers/leds/led-core.c (ffffffff81d5e8b5)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:set_brightness_delayed
```
```
In net/core/sock.c (ffffffff81d9961d)
Location: include/linux/timer.h:198
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff81db2c7e)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff81dd9f80)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_clear
```
```
In net/core/drop_monitor.c (ffffffff81e24430)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea6478)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea8d84)
Location: include/linux/timer.h:198
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0a155)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/xfrm/xfrm_state.c (ffffffff81f38cbf)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/ipv6/ip6_fib.c (ffffffff81f7a4f5)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
```
```
In net/packet/af_packet.c (ffffffff81fc78be)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/ncsi/ncsi-manage.c (ffffffff81fe8f27)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor
```
```
In net/mctp/af_mctp.c (ffffffff82010f33)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_unhash
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff81079f75)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_delete_all
```
```
In kernel/workqueue.c (ffffffff81120c96)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:worker_thread
```
```
In kernel/kthread.c (ffffffff8112a584)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_cancel_work_sync
  - kernel/kthread.c:kthread_mod_delayed_work
```
```
In kernel/rcu/update.c (ffffffff811bb699)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_postscan
```
```
In kernel/rcu/srcutree.c (ffffffff811bf74a)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
```
In kernel/time/timer.c (ffffffff82158045)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In kernel/cgroup/cgroup.c (ffffffff81219a7d)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
```
In mm/page-writeback.c (ffffffff8139bfc5)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_domain_exit
```
```
In mm/backing-dev.c (ffffffff813ca8cd)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In fs/ext4/super.c (ffffffff81603e1d)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
```
```
In fs/jbd2/journal.c (ffffffff816201fb)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/pstore/platform.c (ffffffff81671559)
Location: include/linux/timer.h:198
Inline: True
```
```
In block/blk-core.c (ffffffff8176fc25)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - block/blk-core.c:blk_sync_queue
```
```
In block/blk-stat.c (ffffffff81789179)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_remove_callback
```
```
In block/blk-throttle.c (ffffffff817a8bbf)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:throtl_pd_free
```
```
In block/blk-wbt.c (ffffffff817b9dc0)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_disable_default
```
```
In drivers/tty/vt/keyboard.c (ffffffff81aaaa95)
Location: include/linux/timer.h:198
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff81ab2323)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_blank_screen
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81ac5fb5)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81ad79f3)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
```
```
In drivers/char/random.c (ffffffff81ae060c)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81af186b)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b258ff)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_put_dma_cookie
```
```
In drivers/base/power/wakeup.c (ffffffff81b55d76)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_remove
```
```
In drivers/ata/libata-eh.c (ffffffff81c128ed)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/net/tun.c (ffffffff81c44f4b)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_net_init
```
```
In drivers/net/xen-netfront.c (ffffffff81c6a8eb)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
```
In drivers/usb/core/hub.c (ffffffff81c7f3b2)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_quiesce
```
```
In drivers/usb/core/hcd.c (ffffffff81c84635)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_stop_hcd
  - drivers/usb/core/hcd.c:usb_stop_hcd
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81cb7c35)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81ccbffb)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_suspend
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81cd12f6)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81cd8ef8)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
```
```
In drivers/usb/host/xhci.c (ffffffff81ce063f)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81cf49d7)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status
```
```
In drivers/input/input.c (ffffffff81d114cc)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/input/input.c:__input_unregister_device
```
```
In drivers/md/md.c (ffffffff81d63fe2)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:level_store
```
```
In drivers/mmc/core/host.c (ffffffff81db6625)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_timer_stop
  - drivers/mmc/core/host.c:mmc_retune_disable
```
```
In drivers/leds/led-core.c (ffffffff81dc9655)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:set_brightness_delayed
```
```
In net/core/sock.c (ffffffff81e088cd)
Location: include/linux/timer.h:198
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff81e2324e)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff81e4ace0)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_clear
```
```
In net/core/drop_monitor.c (ffffffff81e99974)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f04c50)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f07604)
Location: include/linux/timer.h:198
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f69c85)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/xfrm/xfrm_state.c (ffffffff81f989ab)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/ipv6/ip6_fib.c (ffffffff81fda705)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
```
```
In net/packet/af_packet.c (ffffffff8202884a)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/ncsi/ncsi-manage.c (ffffffff820651a7)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor
```
```
In net/mctp/af_mctp.c (ffffffff8208dcf3)
Location: include/linux/timer.h:198
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_unhash
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff810816e5)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_delete_all
```
```
In kernel/workqueue.c (ffffffff8112a546)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:worker_thread
```
```
In kernel/kthread.c (ffffffff81134c14)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_cancel_work_sync
  - kernel/kthread.c:kthread_mod_delayed_work
```
```
In kernel/rcu/update.c (ffffffff811cb749)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_postscan
```
```
In kernel/rcu/srcutree.c (ffffffff811cfbba)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
```
In kernel/time/timer.c (ffffffff8223aeb5)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In kernel/cgroup/cgroup.c (ffffffff81231585)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
```
In mm/page-writeback.c (ffffffff813c5ca5)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_domain_exit
```
```
In mm/backing-dev.c (ffffffff813f533d)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In fs/ext4/super.c (ffffffff8163ca82)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
```
```
In fs/jbd2/journal.c (ffffffff816591cb)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/pstore/platform.c (ffffffff816ad609)
Location: include/linux/timer.h:183
Inline: True
```
```
In block/blk-core.c (ffffffff817b1e95)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - block/blk-core.c:blk_sync_queue
```
```
In block/blk-stat.c (ffffffff817cb8df)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_remove_callback
```
```
In block/blk-throttle.c (ffffffff817ec94f)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:throtl_pd_free
```
```
In block/blk-wbt.c (ffffffff817fe533)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_disable_default
```
```
In drivers/tty/vt/keyboard.c (ffffffff81afd525)
Location: include/linux/timer.h:183
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff81b05003)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_blank_screen
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81b18fb5)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81b2accf)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
```
```
In drivers/char/random.c (ffffffff81b33a0c)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81b44dcb)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b7c670)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_put_dma_cookie
```
```
In drivers/base/power/wakeup.c (ffffffff81bae336)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_remove
```
```
In drivers/ata/libata-eh.c (ffffffff81c67b49)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb4961)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:drm_vblank_init_release
```
```
In drivers/net/tun.c (ffffffff81cfaaab)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_net_init
```
```
In drivers/net/xen-netfront.c (ffffffff81d1f2c8)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
```
In drivers/usb/core/hub.c (ffffffff81d33da2)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_quiesce
```
```
In drivers/usb/core/hcd.c (ffffffff81d39035)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_stop_hcd
  - drivers/usb/core/hcd.c:usb_stop_hcd
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81d6c985)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81d80edb)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_suspend
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81d862b6)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81d8df08)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
```
```
In drivers/usb/host/xhci.c (ffffffff81d95794)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81daa2cf)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status
```
```
In drivers/input/input.c (ffffffff81dc70cc)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - drivers/input/input.c:__input_unregister_device
```
```
In drivers/md/md.c (ffffffff81e1dc19)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:level_store
  - drivers/md/md.c:mddev_suspend
```
```
In drivers/mmc/core/host.c (ffffffff81e6eac5)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_timer_stop
  - drivers/mmc/core/host.c:mmc_retune_disable
```
```
In drivers/leds/led-core.c (ffffffff81e82105)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:set_brightness_delayed
```
```
In net/core/sock.c (ffffffff81ec437d)
Location: include/linux/timer.h:183
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff81ee11bd)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff81f09a00)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_clear
```
```
In net/core/drop_monitor.c (ffffffff81f5c0a4)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc8f58)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fcb964)
Location: include/linux/timer.h:183
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff82030305)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/xfrm/xfrm_state.c (ffffffff82065d1b)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/ipv6/ip6_fib.c (ffffffff820a8155)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
```
```
In net/packet/af_packet.c (ffffffff820f8282)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/ncsi/ncsi-manage.c (ffffffff82138347)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor
```
```
In net/mctp/af_mctp.c (ffffffff821641b3)
Location: include/linux/timer.h:183
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_unhash
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffff80001019ed18)
Location: kernel/time/timer.c:1342
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:__kthread_cancel_work
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/time/timer.c:schedule_timeout
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - mm/page-writeback.c:wb_domain_exit
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/pstore/platform.c:pstore_unregister
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-throttle.c:throtl_pd_free
  - block/blk-iocost.c:ioc_rqos_exit
  - block/blk-wbt.c:wbt_disable_default
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/imx.c:imx_uart_set_termios
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/input.c:__input_unregister_device
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:level_store
  - drivers/mmc/core/host.c:mmc_retune_timer_stop
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:set_brightness_delayed
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
  - net/ipv4/ipmr.c:ipmr_free_table
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
  - net/ipv6/ip6_fib.c:fib6_net_exit
  - net/ipv6/ip6mr.c:ip6mr_free_table
  - net/packet/af_packet.c:packet_set_ring
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor
```
**Symbols:**

```
ffff80001019ed18-ffff80001019ed70: del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c03e7754)
Location: kernel/time/timer.c:1342
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:__kthread_cancel_work
  - kernel/time/timer.c:schedule_timeout
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - mm/page-writeback.c:wb_domain_exit
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/pstore/platform.c:pstore_unregister
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-throttle.c:throtl_pd_free
  - block/blk-iocost.c:ioc_rqos_exit
  - block/blk-wbt.c:wbt_disable_default
  - drivers/video/fbdev/core/fbcon.c:fbcon_del_cursor_timer
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/imx.c:imx_uart_set_termios
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_stop
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/input.c:__input_unregister_device
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:level_store
  - drivers/mmc/core/host.c:mmc_retune_timer_stop
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/mmc/host/sdhci.c:sdhci_remove_host
  - drivers/mmc/host/sdhci.c:sdhci_remove_host
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:set_brightness_delayed
  - sound/core/timer.c:snd_timer_s_close
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
  - net/ipv4/ipmr.c:ipmr_free_table
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
  - net/ipv6/ip6_fib.c:fib6_net_exit
  - net/ipv6/ip6mr.c:ip6mr_free_table
  - net/packet/af_packet.c:packet_set_ring
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor
```
**Symbols:**

```
c03e7754-c03e77e4: del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c0000000001fe150)
Location: kernel/time/timer.c:1342
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:__kthread_cancel_work
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/time/timer.c:schedule_timeout
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - mm/page-writeback.c:wb_domain_exit
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/pstore/platform.c:pstore_unregister
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-throttle.c:throtl_pd_free
  - block/blk-iocost.c:ioc_rqos_exit
  - block/blk-wbt.c:wbt_disable_default
  - drivers/video/fbdev/core/fbcon.c:fbcon_del_cursor_timer
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/net/tun.c:tun_free_netdev
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/input.c:__input_unregister_device
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:level_store
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_stop_cpu
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_target_index
  - drivers/mmc/core/host.c:mmc_retune_timer_stop
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:set_brightness_delayed
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
  - net/ipv4/ipmr.c:ipmr_free_table
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
  - net/ipv6/ip6_fib.c:fib6_net_exit
  - net/ipv6/ip6mr.c:ip6mr_free_table
  - net/packet/af_packet.c:packet_set_ring
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor
```
**Symbols:**

```
c0000000001fe150-c0000000001fe1d8: del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffe00012bf5e)
Location: kernel/time/timer.c:1342
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:__kthread_cancel_work
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/time/timer.c:schedule_timeout
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - mm/page-writeback.c:wb_domain_exit
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/pstore/platform.c:pstore_unregister
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-throttle.c:throtl_pd_free
  - block/blk-iocost.c:ioc_rqos_exit
  - block/blk-wbt.c:wbt_disable_default
  - drivers/video/fbdev/core/fbcon.c:fbcon_del_cursor_timer
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/input.c:__input_unregister_device
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:level_store
  - drivers/mmc/core/host.c:mmc_retune_timer_stop
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:set_brightness_delayed
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
  - net/ipv4/ipmr.c:ipmr_free_table
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
  - net/ipv6/ip6_fib.c:fib6_net_exit
  - net/ipv6/ip6mr.c:ip6mr_free_table
  - net/packet/af_packet.c:packet_set_ring
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor
```
**Symbols:**

```
ffffffe00012bf5e-ffffffe00012bfac: del_timer_sync (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112d9c0)
Location: kernel/time/timer.c:1342
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_delete_all
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:__kthread_cancel_work
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/time/timer.c:schedule_timeout
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - mm/page-writeback.c:wb_domain_exit
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/pstore/platform.c:pstore_unregister
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-throttle.c:throtl_pd_free
  - block/blk-iocost.c:ioc_rqos_exit
  - block/blk-wbt.c:wbt_disable_default
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/nvme/host/multipath.c:nvme_mpath_stop
  - drivers/nvme/host/multipath.c:nvme_read_ana_log
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/input.c:__input_unregister_device
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:level_store
  - drivers/mmc/core/host.c:mmc_retune_timer_stop
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/leds/led-core.c:led_stop_software_blink
  - drivers/leds/led-core.c:led_blink_set
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
  - net/ipv4/ipmr.c:ipmr_free_table
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
  - net/ipv6/ip6_fib.c:fib6_net_exit
  - net/ipv6/ip6mr.c:ip6mr_free_table
  - net/packet/af_packet.c:packet_set_ring
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor
```
**Symbols:**

```
ffffffff8112d9c0-ffffffff8112d9f8: del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81120230)
Location: kernel/time/timer.c:1342
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_delete_all
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:__kthread_cancel_work
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/time/timer.c:schedule_timeout
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - mm/page-writeback.c:wb_domain_exit
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/pstore/platform.c:pstore_unregister
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-throttle.c:throtl_pd_free
  - block/blk-iocost.c:ioc_rqos_exit
  - block/blk-wbt.c:wbt_disable_default
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/nvme/host/multipath.c:nvme_mpath_stop
  - drivers/nvme/host/multipath.c:nvme_read_ana_log
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/net/vxlan.c:vxlan_stop
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/input.c:__input_unregister_device
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:level_store
  - drivers/leds/led-core.c:led_stop_software_blink
  - drivers/leds/led-core.c:led_blink_set
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
  - net/ipv4/ipmr.c:ipmr_free_table
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
  - net/ipv6/ip6_fib.c:fib6_net_exit
  - net/ipv6/ip6mr.c:ip6mr_free_table
  - net/packet/af_packet.c:packet_set_ring
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor
```
**Symbols:**

```
ffffffff81120230-ffffffff81120268: del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112b6e0)
Location: kernel/time/timer.c:1342
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_delete_all
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:__kthread_cancel_work
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/time/timer.c:schedule_timeout
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - mm/page-writeback.c:wb_domain_exit
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/pstore/platform.c:pstore_unregister
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-throttle.c:throtl_pd_free
  - block/blk-iocost.c:ioc_rqos_exit
  - block/blk-wbt.c:wbt_disable_default
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/input.c:__input_unregister_device
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:level_store
  - drivers/mmc/core/host.c:mmc_retune_timer_stop
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/leds/led-core.c:led_stop_software_blink
  - drivers/leds/led-core.c:led_blink_set
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
  - net/ipv4/ipmr.c:ipmr_free_table
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
  - net/ipv6/ip6_fib.c:fib6_net_exit
  - net/ipv6/ip6mr.c:ip6mr_free_table
  - net/packet/af_packet.c:packet_set_ring
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor
```
**Symbols:**

```
ffffffff8112b6e0-ffffffff8112b718: del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81137d60)
Location: kernel/time/timer.c:1342
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_delete_all
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:__kthread_cancel_work
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/time/timer.c:schedule_timeout
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - mm/page-writeback.c:wb_domain_exit
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/pstore/platform.c:pstore_unregister
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-throttle.c:throtl_pd_free
  - block/blk-iocost.c:ioc_rqos_exit
  - block/blk-wbt.c:wbt_disable_default
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/input.c:__input_unregister_device
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:level_store
  - drivers/mmc/core/host.c:mmc_retune_timer_stop
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/leds/led-core.c:led_stop_software_blink
  - drivers/leds/led-core.c:led_blink_set
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
  - net/ipv4/ipmr.c:ipmr_free_table
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
  - net/ipv6/ip6_fib.c:fib6_net_exit
  - net/ipv6/ip6mr.c:ip6mr_free_table
  - net/packet/af_packet.c:packet_set_ring
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor
```
**Symbols:**

```
ffffffff81137d60-ffffffff81137d98: del_timer_sync (STB_GLOBAL)
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
No changes between <code>4.13</code> and <code>4.15</code> ✅
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
