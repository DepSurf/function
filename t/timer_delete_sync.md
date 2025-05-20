# Function: <code>timer_delete_sync</code>

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
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int timer_delete_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff820d3dc5)
Location: kernel/time/timer.c:1626
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_delete_all
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:__kthread_cancel_work_sync
  - kernel/kthread.c:kthread_mod_delayed_work
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - mm/page-writeback.c:wb_domain_exit
  - mm/backing-dev.c:bdi_unregister
  - fs/ext4/super.c:__ext4_fill_super
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - block/blk-core.c:blk_sync_queue
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:throtl_pd_free
  - block/blk-wbt.c:wbt_disable_default
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/iommu/dma-iommu.c:iommu_put_dma_cookie
  - drivers/base/power/wakeup.c:wakeup_source_remove
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
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_clear
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
  - net/ipv6/ip6_fib.c:fib6_net_exit
  - net/packet/af_packet.c:packet_set_ring
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor
  - net/mctp/af_mctp.c:mctp_sk_unhash
```
**Symbols:**

```
ffffffff811d7090-ffffffff811d70aa: timer_delete_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int timer_delete_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff82158045)
Location: kernel/time/timer.c:1626
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_delete_all
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:__kthread_cancel_work_sync
  - kernel/kthread.c:kthread_mod_delayed_work
  - kernel/rcu/update.c:rcu_tasks_postscan
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - mm/page-writeback.c:wb_domain_exit
  - mm/backing-dev.c:bdi_unregister
  - fs/ext4/super.c:__ext4_fill_super
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - block/blk-core.c:blk_sync_queue
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:throtl_pd_free
  - block/blk-wbt.c:wbt_disable_default
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/iommu/dma-iommu.c:iommu_put_dma_cookie
  - drivers/base/power/wakeup.c:wakeup_source_remove
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
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_clear
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
  - net/ipv6/ip6_fib.c:fib6_net_exit
  - net/packet/af_packet.c:packet_set_ring
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor
  - net/mctp/af_mctp.c:mctp_sk_unhash
```
**Symbols:**

```
ffffffff811eb510-ffffffff811eb52a: timer_delete_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int timer_delete_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8223aeb5)
Location: kernel/time/timer.c:1626
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_delete_all
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:__kthread_cancel_work_sync
  - kernel/kthread.c:kthread_mod_delayed_work
  - kernel/rcu/update.c:rcu_tasks_postscan
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - mm/page-writeback.c:wb_domain_exit
  - mm/backing-dev.c:bdi_unregister
  - fs/ext4/super.c:__ext4_fill_super
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - block/blk-core.c:blk_sync_queue
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:throtl_pd_free
  - block/blk-wbt.c:wbt_disable_default
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/iommu/dma-iommu.c:iommu_put_dma_cookie
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/gpu/drm/drm_vblank.c:drm_vblank_init_release
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
  - drivers/md/md.c:mddev_suspend
  - drivers/mmc/core/host.c:mmc_retune_timer_stop
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:set_brightness_delayed
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_table_clear
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
  - net/ipv6/ip6_fib.c:fib6_net_exit
  - net/packet/af_packet.c:packet_set_ring
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor
  - net/mctp/af_mctp.c:mctp_sk_unhash
```
**Symbols:**

```
ffffffff81201540-ffffffff8120155a: timer_delete_sync (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
