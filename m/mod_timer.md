# Function: <code>mod_timer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mod_timer(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810ee260)
Location: kernel/time/timer.c:906
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_watchdog
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/workqueue.c:worker_enter_idle
  - kernel/workqueue.c:idle_worker_timeout
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:worker_thread
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:note_interrupt
  - kernel/relay.c:relay_switch_subbuf
  - kernel/padata.c:padata_reorder
  - mm/page-writeback.c:wb_domain_writeout_inc
  - mm/page-writeback.c:writeout_period
  - mm/page-writeback.c:laptop_io_completion
  - fs/ext4/super.c:__save_error_info
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:ext4_fill_super
  - fs/pstore/platform.c:pstore_timefunc
  - block/blk-timeout.c:blk_add_timer
  - block/blk-timeout.c:blk_rq_timed_out_timer
  - block/blk-mq.c:blk_mq_rq_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/cfq-iosched.c:cfq_arm_slice_timer
  - drivers/video/console/fbcon.c:cursor_timer_handler
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/serial/8250/8250_core.c:serial8250_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm-dev.c:tpm_write
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/wakeup.c:__pm_wakeup_event
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/host/ehci-hcd.c:ehci_hub_status_data
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_set_next_interrupt
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/input.c:input_repeat_key
  - drivers/md/md.c:safe_delay_store
  - drivers/mmc/core/host.c:mmc_retune_enable
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - net/core/gen_estimator.c:est_timer
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_timer_handler
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/ipv6/addrconf.c:addrconf_mod_rs_timer
  - net/ipv6/addrconf.c:ipv6_regen_rndid
  - net/ipv6/ip6_fib.c:fib6_force_start_gc
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/mcast.c:igmp6_group_added
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/ip6_flowlabel.c:fl_release
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6mr.c:ipmr_do_expire_process
  - net/ipv6/ip6mr.c:ipmr_expire_process
  - net/packet/af_packet.c:prb_open_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
**Symbols:**

```
ffffffff810ee260-ffffffff810ee49a: mod_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int mod_timer(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810f4e40)
Location: kernel/time/timer.c:1084
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:__restart_timer
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_watchdog
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:idle_worker_timeout
  - kernel/workqueue.c:worker_enter_idle
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/relay.c:relay_switch_subbuf
  - kernel/padata.c:padata_reorder
  - mm/page-writeback.c:laptop_io_completion
  - mm/page-writeback.c:writeout_period
  - mm/page-writeback.c:wb_domain_writeout_inc
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:__save_error_info
  - fs/pstore/platform.c:pstore_timefunc
  - block/blk-timeout.c:blk_add_timer
  - block/blk-timeout.c:blk_timeout_work
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - drivers/video/console/fbcon.c:cursor_timer_handler
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_timeout
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm-dev.c:tpm_write
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:__pm_wakeup_event
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_set_next_interrupt
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/input.c:input_repeat_key
  - drivers/md/md.c:safe_delay_store
  - drivers/mmc/core/host.c:mmc_retune_enable
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:est_timer
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_timer_handler
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
  - net/ipv6/addrconf.c:ipv6_regen_rndid
  - net/ipv6/addrconf.c:addrconf_mod_rs_timer
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_force_start_gc
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_group_added
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6_flowlabel.c:fl_release
  - net/ipv6/ip6mr.c:ipmr_expire_process
  - net/ipv6/ip6mr.c:ipmr_do_expire_process
  - net/packet/af_packet.c:prb_open_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-manage.c:ncsi_start_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff810f4e40-ffffffff810f51f3: mod_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int mod_timer(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810fbf60)
Location: kernel/time/timer.c:1094
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:__start_timer
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_watchdog
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:idle_worker_timeout
  - kernel/workqueue.c:worker_enter_idle
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/padata.c:padata_reorder
  - mm/page-writeback.c:laptop_io_completion
  - mm/page-writeback.c:writeout_period
  - mm/page-writeback.c:wb_domain_writeout_inc
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:__save_error_info
  - fs/pstore/platform.c:pstore_timefunc
  - block/blk-timeout.c:blk_add_timer
  - block/blk-timeout.c:blk_timeout_work
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/video/console/fbcon.c:cursor_timer_handler
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_timeout
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm-dev.c:tpm_write
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:__pm_wakeup_event
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_set_next_interrupt
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/input.c:input_repeat_key
  - drivers/md/md.c:safe_delay_store
  - drivers/mmc/core/host.c:mmc_retune_enable
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:est_timer
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_timer_handler
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
  - net/ipv6/addrconf.c:addrconf_mod_rs_timer
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_force_start_gc
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_group_added
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6_flowlabel.c:fl_release
  - net/ipv6/ip6mr.c:ipmr_expire_process
  - net/ipv6/ip6mr.c:ipmr_do_expire_process
  - net/packet/af_packet.c:prb_open_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-manage.c:ncsi_start_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff810fbf60-ffffffff810fc2af: mod_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int mod_timer(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810fe390)
Location: kernel/time/timer.c:1069
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:__start_timer
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_watchdog
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:idle_worker_timeout
  - kernel/workqueue.c:worker_enter_idle
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/padata.c:padata_reorder
  - mm/page-writeback.c:laptop_io_completion
  - mm/page-writeback.c:writeout_period
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:__save_error_info
  - fs/pstore/platform.c:pstore_timefunc
  - block/blk-timeout.c:blk_add_timer
  - block/blk-timeout.c:blk_timeout_work
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:__blk_mq_complete_request
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/video/console/fbcon.c:fbcon_add_cursor_timer
  - drivers/video/console/fbcon.c:cursor_timer_handler
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_timeout
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_set_next_interrupt
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/input.c:input_repeat_key
  - drivers/md/md.c:md_write_end
  - drivers/md/md.c:safe_delay_store
  - drivers/mmc/core/host.c:mmc_retune_enable
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:est_timer
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_timer_handler
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
  - net/ipv6/addrconf.c:addrconf_mod_rs_timer
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_force_start_gc
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6_flowlabel.c:fl_release
  - net/ipv6/ip6mr.c:ipmr_expire_process
  - net/ipv6/ip6mr.c:ipmr_do_expire_process
  - net/packet/af_packet.c:prb_open_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-manage.c:ncsi_start_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff810fe390-ffffffff810fe731: mod_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int mod_timer(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81108ca0)
Location: kernel/time/timer.c:1092
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:__start_timer
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:idle_worker_timeout
  - kernel/workqueue.c:worker_enter_idle
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/padata.c:padata_reorder
  - mm/page-writeback.c:laptop_io_completion
  - mm/page-writeback.c:writeout_period
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:__save_error_info
  - fs/pstore/platform.c:pstore_timefunc
  - block/blk-timeout.c:blk_add_timer
  - block/blk-timeout.c:blk_timeout_work
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:__blk_mq_complete_request
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/video/fbdev/core/fbcon.c:fbcon_add_cursor_timer
  - drivers/video/fbdev/core/fbcon.c:cursor_timer_handler
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_timeout
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/iommu/iova.c:queue_iova
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_set_next_interrupt
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/input.c:input_repeat_key
  - drivers/md/md.c:md_write_end
  - drivers/md/md.c:safe_delay_store
  - drivers/mmc/core/host.c:mmc_retune_enable
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:est_timer
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_timer_handler
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
  - net/ipv6/addrconf.c:addrconf_mod_rs_timer
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_force_start_gc
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_dad_start_timer
  - net/ipv6/mcast.c:mld_ifc_start_timer
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6_flowlabel.c:fl_release
  - net/ipv6/ip6mr.c:ipmr_do_expire_process
  - net/packet/af_packet.c:prb_open_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-manage.c:ncsi_start_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff81108ca0-ffffffff81109051: mod_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int mod_timer(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81113b70)
Location: kernel/time/timer.c:1100
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:__start_timer
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:idle_worker_timeout
  - kernel/workqueue.c:worker_enter_idle
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/padata.c:padata_reorder
  - mm/page-writeback.c:laptop_io_completion
  - mm/page-writeback.c:writeout_period
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:__save_error_info
  - fs/pstore/platform.c:pstore_timefunc
  - block/blk-timeout.c:blk_add_timer
  - block/blk-timeout.c:blk_timeout_work
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/video/fbdev/core/fbcon.c:fbcon_add_cursor_timer
  - drivers/video/fbdev/core/fbcon.c:cursor_timer_handler
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_timeout
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/iommu/iova.c:queue_iova
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_set_next_interrupt
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/input.c:input_repeat_key
  - drivers/md/md.c:md_write_end
  - drivers/mmc/core/host.c:mmc_retune_enable
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:est_timer
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_timer_handler
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
  - net/ipv6/addrconf.c:addrconf_mod_rs_timer
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_force_start_gc
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_dad_start_timer
  - net/ipv6/mcast.c:mld_ifc_start_timer
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6_flowlabel.c:fl_release
  - net/ipv6/ip6mr.c:ipmr_do_expire_process
  - net/packet/af_packet.c:prb_open_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-manage.c:ncsi_start_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff81113b70-ffffffff81113f32: mod_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int mod_timer(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8111f560)
Location: kernel/time/timer.c:1099
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:idle_worker_timeout
  - kernel/workqueue.c:worker_enter_idle
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/padata.c:padata_reorder
  - mm/page-writeback.c:laptop_io_completion
  - mm/page-writeback.c:writeout_period
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:__save_error_info
  - fs/pstore/platform.c:pstore_timefunc
  - block/blk-timeout.c:blk_add_timer
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/video/fbdev/core/fbcon.c:fbcon_add_cursor_timer
  - drivers/video/fbdev/core/fbcon.c:cursor_timer_handler
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_timeout
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:tpm_async_work
  - drivers/iommu/iova.c:queue_iova
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_set_next_interrupt
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/input.c:input_repeat_key
  - drivers/md/md.c:md_write_end
  - drivers/mmc/core/host.c:mmc_retune_enable
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:est_timer
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_timer_handler
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
  - net/ipv6/addrconf.c:addrconf_mod_rs_timer
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_force_start_gc
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_dad_start_timer
  - net/ipv6/mcast.c:mld_ifc_start_timer
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6_flowlabel.c:fl_release
  - net/ipv6/ip6mr.c:ipmr_do_expire_process
  - net/packet/af_packet.c:prb_open_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-manage.c:ncsi_start_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff8111f7b0-ffffffff8111fb72: mod_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int mod_timer(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112a0f8)
Location: kernel/time/timer.c:1094
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:idle_worker_timeout
  - kernel/workqueue.c:worker_enter_idle
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/padata.c:padata_reorder
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:laptop_io_completion
  - mm/page-writeback.c:writeout_period
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:__save_error_info
  - fs/pstore/platform.c:pstore_timefunc
  - block/blk-timeout.c:blk_add_timer
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/video/fbdev/core/fbcon.c:fbcon_add_cursor_timer
  - drivers/video/fbdev/core/fbcon.c:cursor_timer_handler
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_timeout
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_async_work
  - drivers/iommu/iova.c:queue_iova
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_set_next_interrupt
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/input.c:input_repeat_key
  - drivers/md/md.c:md_write_end
  - drivers/md/md.c:safe_delay_store
  - drivers/mmc/core/host.c:mmc_retune_enable
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:est_timer
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_timer_handler
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
  - net/ipv6/addrconf.c:addrconf_mod_rs_timer
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_force_start_gc
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_dad_start_timer
  - net/ipv6/mcast.c:mld_ifc_start_timer
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6_flowlabel.c:fl_release
  - net/ipv6/ip6mr.c:ipmr_do_expire_process
  - net/packet/af_packet.c:prb_open_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-manage.c:ncsi_start_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff8112a600-ffffffff8112a90b: mod_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int mod_timer(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81136098)
Location: kernel/time/timer.c:1098
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:idle_worker_timeout
  - kernel/workqueue.c:worker_enter_idle
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:laptop_io_completion
  - mm/page-writeback.c:writeout_period
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:__save_error_info
  - fs/pstore/platform.c:pstore_timefunc
  - block/blk-timeout.c:blk_add_timer
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/video/fbdev/core/fbcon.c:fbcon_add_cursor_timer
  - drivers/video/fbdev/core/fbcon.c:cursor_timer_handler
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_timeout
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_async_work
  - drivers/iommu/iova.c:queue_iova
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_set_next_interrupt
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/input.c:input_repeat_key
  - drivers/md/md.c:md_write_end
  - drivers/md/md.c:safe_delay_store
  - drivers/mmc/core/host.c:mmc_retune_enable
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:est_timer
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data
  - net/core/drop_monitor.c:reset_per_cpu_data
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
  - net/ipv6/addrconf.c:addrconf_mod_rs_timer
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_force_start_gc
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_dad_start_timer
  - net/ipv6/mcast.c:mld_ifc_start_timer
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6_flowlabel.c:fl_release
  - net/ipv6/ip6mr.c:ipmr_do_expire_process
  - net/packet/af_packet.c:prb_open_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-manage.c:ncsi_start_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff811365a0-ffffffff811368ab: mod_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mod_timer(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811449b0)
Location: kernel/time/timer.c:1110
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat
  - kernel/workqueue.c:maybe_create_worker
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:idle_worker_timeout
  - kernel/workqueue.c:worker_enter_idle
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:laptop_io_completion
  - mm/page-writeback.c:writeout_period
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:__save_error_info
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - fs/pstore/platform.c:pstore_dump
  - security/keys/gc.c:key_schedule_gc
  - block/blk-timeout.c:blk_add_timer
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/video/fbdev/core/fbcon.c:fbcon_add_cursor_timer
  - drivers/video/fbdev/core/fbcon.c:cursor_timer_handler
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_timeout
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_async_work
  - drivers/iommu/iova.c:queue_iova
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
  - drivers/usb/core/hcd.c:rh_queue_status
  - drivers/usb/core/hcd.c:rh_queue_status
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_status_data
  - drivers/usb/host/ehci-platform.c:quirk_poll_init
  - drivers/usb/host/ehci-platform.c:quirk_poll_timer
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/input/input.c:input_repeat_key
  - drivers/md/md.c:md_write_end
  - drivers/md/md.c:safe_delay_store
  - drivers/mmc/core/host.c:mmc_retune_enable
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - net/core/sock.c:sk_reset_timer
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:est_timer
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data
  - net/core/drop_monitor.c:reset_per_cpu_data
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv4/ip_fragment.c:ip_frag_reinit
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_start_timer
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_force_start_gc
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6_flowlabel.c:fl_release
  - net/ipv6/ip6mr.c:ipmr_do_expire_process
  - net/packet/af_packet.c:prb_open_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-manage.c:ncsi_start_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff811449b0-ffffffff811449c2: mod_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mod_timer(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81141d70)
Location: kernel/time/timer.c:1104
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
  - kernel/workqueue.c:maybe_create_worker
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:idle_worker_timeout
  - kernel/workqueue.c:worker_enter_idle
  - kernel/sched/psi.c:psi_group_change
  - kernel/sched/psi.c:psi_poll_work
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:laptop_io_completion
  - mm/page-writeback.c:writeout_period
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:print_daily_error_info
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - fs/pstore/platform.c:pstore_dump
  - security/keys/gc.c:key_schedule_gc
  - block/blk-timeout.c:blk_add_timer
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-wbt.c:rwb_arm_timer
  - lib/random32.c:prandom_init_late
  - lib/random32.c:prandom_reseed
  - drivers/video/fbdev/core/fbcon.c:fbcon_add_cursor_timer
  - drivers/video/fbdev/core/fbcon.c:cursor_timer_handler
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_timeout
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_async_work
  - drivers/iommu/iova.c:queue_iova
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
  - drivers/usb/core/hcd.c:rh_queue_status
  - drivers/usb/core/hcd.c:rh_queue_status
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_status_data
  - drivers/usb/host/ehci-platform.c:quirk_poll_init
  - drivers/usb/host/ehci-platform.c:quirk_poll_timer
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/input/input.c:input_repeat_key
  - drivers/md/md.c:md_write_end
  - drivers/md/md.c:safe_delay_store
  - drivers/mmc/core/host.c:mmc_retune_enable
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:est_timer
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data
  - net/core/drop_monitor.c:reset_per_cpu_data
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv4/ip_fragment.c:ip_frag_reinit
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_force_start_gc
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6_flowlabel.c:fl_release
  - net/ipv6/ip6mr.c:ipmr_do_expire_process
  - net/packet/af_packet.c:prb_open_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-manage.c:ncsi_start_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff81141d70-ffffffff81141d82: mod_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mod_timer(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81142b70)
Location: kernel/time/timer.c:1106
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:idle_worker_timeout
  - kernel/workqueue.c:worker_enter_idle
  - kernel/sched/psi.c:psi_group_change
  - kernel/sched/psi.c:psi_poll_worker
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:laptop_io_completion
  - mm/page-writeback.c:writeout_period
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:print_daily_error_info
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - fs/pstore/platform.c:pstore_dump
  - security/keys/gc.c:key_schedule_gc
  - block/blk-timeout.c:blk_add_timer
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-wbt.c:rwb_arm_timer
  - lib/random32.c:prandom_init_late
  - lib/random32.c:prandom_reseed
  - drivers/video/fbdev/core/fbcon.c:fbcon_add_cursor_timer
  - drivers/video/fbdev/core/fbcon.c:cursor_timer_handler
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_timeout
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_async_work
  - drivers/iommu/iova.c:queue_iova
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_status_data
  - drivers/usb/host/ehci-platform.c:quirk_poll_init
  - drivers/usb/host/ehci-platform.c:quirk_poll_timer
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/input/input.c:input_repeat_key
  - drivers/md/md.c:md_write_end
  - drivers/md/md.c:safe_delay_store
  - drivers/mmc/core/host.c:mmc_retune_enable
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:est_timer
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data
  - net/core/drop_monitor.c:reset_per_cpu_data
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_force_start_gc
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6_flowlabel.c:fl_release
  - net/ipv6/ip6mr.c:ipmr_do_expire_process
  - net/packet/af_packet.c:prb_open_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-manage.c:ncsi_start_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff81142b70-ffffffff81142b82: mod_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mod_timer(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811660b0)
Location: kernel/time/timer.c:1106
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:idle_worker_timeout
  - kernel/workqueue.c:worker_enter_idle
  - kernel/sched/psi.c:psi_group_change
  - kernel/sched/psi.c:psi_poll_worker
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:laptop_io_completion
  - mm/page-writeback.c:writeout_period
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:print_daily_error_info
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - fs/pstore/platform.c:pstore_dump
  - security/keys/gc.c:key_schedule_gc
  - block/blk-timeout.c:blk_add_timer
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-wbt.c:rwb_arm_timer
  - lib/random32.c:prandom_init_late
  - lib/random32.c:prandom_reseed
  - drivers/video/fbdev/core/fbcon.c:fbcon_add_cursor_timer
  - drivers/video/fbdev/core/fbcon.c:cursor_timer_handler
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_timeout
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_async_work
  - drivers/iommu/iova.c:queue_iova
  - drivers/net/tun.c:tun_net_init
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_status_data
  - drivers/usb/host/ehci-platform.c:quirk_poll_init
  - drivers/usb/host/ehci-platform.c:quirk_poll_timer
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/input/input.c:input_repeat_key
  - drivers/md/md.c:md_write_end
  - drivers/md/md.c:safe_delay_store
  - drivers/mmc/core/host.c:mmc_retune_enable
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:est_timer
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data
  - net/core/drop_monitor.c:reset_per_cpu_data
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_orphan_update
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_force_start_gc
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6_flowlabel.c:fl_release
  - net/ipv6/ip6mr.c:ipmr_do_expire_process
  - net/packet/af_packet.c:prb_open_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-manage.c:ncsi_start_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff811660b0-ffffffff811660c2: mod_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mod_timer(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81199c30)
Location: kernel/time/timer.c:1159
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:idle_worker_timeout
  - kernel/workqueue.c:worker_enter_idle
  - kernel/sched/build_utility.c:psi_group_change
  - kernel/sched/build_utility.c:psi_poll_worker
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:laptop_io_completion
  - mm/page-writeback.c:writeout_period
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:print_daily_error_info
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - fs/pstore/platform.c:pstore_dump
  - block/blk-timeout.c:blk_add_timer
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_timeout
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_async_work
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/net/tun.c:tun_net_init
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_status_data
  - drivers/usb/host/ehci-platform.c:quirk_poll_init
  - drivers/usb/host/ehci-platform.c:quirk_poll_timer
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/input/input.c:input_repeat_key
  - drivers/md/md.c:safe_delay_store
  - drivers/mmc/core/host.c:mmc_retune_enable
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:est_timer
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data
  - net/core/drop_monitor.c:reset_per_cpu_data
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_orphan_update
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_force_start_gc
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6_flowlabel.c:fl_release
  - net/ipv6/ip6mr.c:ipmr_do_expire_process
  - net/packet/af_packet.c:prb_open_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-manage.c:ncsi_start_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/mctp/af_mctp.c:mctp_sk_expire_keys
```
**Symbols:**

```
ffffffff81199c30-ffffffff81199c4c: mod_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mod_timer(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811d8290)
Location: kernel/time/timer.c:1188
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:idle_worker_timeout
  - kernel/workqueue.c:worker_enter_idle
  - kernel/sched/build_utility.c:psi_group_change
  - kernel/sched/build_utility.c:psi_poll_worker
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:laptop_io_completion
  - mm/page-writeback.c:writeout_period
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:print_daily_error_info
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - fs/pstore/platform.c:pstore_dump
  - security/keys/gc.c:key_schedule_gc
  - block/blk-timeout.c:blk_add_timer
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:__blk_mq_end_request
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_timer
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_timer
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_timeout
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_async_work
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/net/tun.c:tun_net_init
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_status_data
  - drivers/usb/host/ehci-platform.c:quirk_poll_init
  - drivers/usb/host/ehci-platform.c:quirk_poll_timer
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/input/input.c:input_repeat_key
  - drivers/md/md.c:safe_delay_store
  - drivers/mmc/core/host.c:mmc_retune_enable
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:est_timer
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_add_timer
  - net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data
  - net/core/drop_monitor.c:reset_per_cpu_data
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_orphan_update
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_force_start_gc
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6_flowlabel.c:fl_release
  - net/ipv6/ip6mr.c:ipmr_do_expire_process
  - net/packet/af_packet.c:prb_open_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-manage.c:ncsi_start_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/mctp/af_mctp.c:mctp_sk_expire_keys
```
**Symbols:**

```
ffffffff811d8290-ffffffff811d82ac: mod_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mod_timer(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811ec6c0)
Location: kernel/time/timer.c:1188
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:idle_cull_fn
  - kernel/workqueue.c:idle_worker_timeout
  - kernel/workqueue.c:worker_enter_idle
  - kernel/sched/build_utility.c:psi_group_change
  - kernel/sched/build_utility.c:psi_rtpoll_work
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:laptop_io_completion
  - mm/page-writeback.c:writeout_period
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:print_daily_error_info
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - fs/pstore/platform.c:pstore_dump
  - security/keys/gc.c:key_schedule_gc
  - block/blk-timeout.c:blk_add_timer
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_timer
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_timer
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_timeout
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_async_work
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/net/tun.c:tun_net_init
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_status_data
  - drivers/usb/host/ehci-platform.c:quirk_poll_init
  - drivers/usb/host/ehci-platform.c:quirk_poll_timer
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-hub.c:xhci_handle_usb2_port_link_resume
  - drivers/input/input.c:input_repeat_key
  - drivers/md/md.c:safe_delay_store
  - drivers/mmc/core/host.c:mmc_retune_enable
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:est_timer
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_add_timer
  - net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data
  - net/core/drop_monitor.c:reset_per_cpu_data
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_orphan_update
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_force_start_gc
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6_flowlabel.c:fl_release
  - net/ipv6/ip6mr.c:ipmr_do_expire_process
  - net/packet/af_packet.c:prb_open_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-manage.c:ncsi_start_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/mctp/af_mctp.c:mctp_sk_expire_keys
```
**Symbols:**

```
ffffffff811ec6c0-ffffffff811ec6dc: mod_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mod_timer(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff812026e0)
Location: kernel/time/timer.c:1188
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
  - arch/x86/kernel/apic/vector.c:__vector_cleanup
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:idle_cull_fn
  - kernel/workqueue.c:idle_worker_timeout
  - kernel/workqueue.c:worker_enter_idle
  - kernel/sched/build_utility.c:psi_group_change
  - kernel/sched/build_utility.c:psi_rtpoll_work
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/rcu/update.c:call_rcu_tasks_generic
  - kernel/rcu/update.c:call_rcu_tasks_generic_timer
  - kernel/rcu/tree.c:nocb_gp_wait
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:laptop_io_completion
  - mm/page-writeback.c:writeout_period
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:print_daily_error_info
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - fs/pstore/platform.c:pstore_dump
  - security/keys/gc.c:key_schedule_gc
  - block/blk-timeout.c:blk_add_timer
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_timer
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_timer
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_timeout
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_async_work
  - drivers/iommu/dma-iommu.c:queue_iova
  - drivers/gpu/drm/drm_vblank.c:drm_vblank_put
  - drivers/net/tun.c:tun_net_init
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_status_data
  - drivers/usb/host/ehci-platform.c:quirk_poll_init
  - drivers/usb/host/ehci-platform.c:quirk_poll_timer
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci-hub.c:xhci_handle_usb2_port_link_resume
  - drivers/input/input.c:input_repeat_key
  - drivers/md/md.c:safe_delay_store
  - drivers/mmc/core/host.c:mmc_retune_enable
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:est_timer
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_add_timer
  - net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data
  - net/core/drop_monitor.c:reset_per_cpu_data
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_orphan_update
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_start_timer
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_force_start_gc
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6_flowlabel.c:fl_release
  - net/ipv6/ip6mr.c:ipmr_do_expire_process
  - net/packet/af_packet.c:prb_open_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-manage.c:ncsi_start_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/mctp/af_mctp.c:mctp_sk_expire_keys
```
**Symbols:**

```
ffffffff812026e0-ffffffff812026fc: mod_timer (STB_GLOBAL)
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
int mod_timer(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffff80001019f878)
Location: kernel/time/timer.c:1098
Inline: True
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:idle_worker_timeout
  - kernel/workqueue.c:worker_enter_idle
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:laptop_io_completion
  - mm/page-writeback.c:writeout_period
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:__save_error_info
  - fs/pstore/platform.c:pstore_timefunc
  - block/blk-timeout.c:blk_add_timer
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/video/fbdev/core/fbcon.c:fbcon_add_cursor_timer
  - drivers/video/fbdev/core/fbcon.c:cursor_timer_handler
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_timeout
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_poll
  - drivers/tty/serial/imx.c:imx_uart_timeout
  - drivers/tty/serial/imx.c:imx_uart_enable_ms
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_async_work
  - drivers/iommu/iova.c:queue_iova
  - drivers/ata/libahci.c:ahci_qc_issue
  - drivers/ata/libahci.c:ahci_sw_activity_blink
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_set_next_interrupt
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/input.c:input_repeat_key
  - drivers/md/md.c:md_write_end
  - drivers/md/md.c:safe_delay_store
  - drivers/mmc/core/host.c:mmc_retune_enable
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - net/core/sock.c:sk_reset_timer
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:est_timer
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data
  - net/core/drop_monitor.c:reset_per_cpu_data
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_start_timer
  - net/ipv4/igmp.c:igmp_start_timer
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
  - net/ipv6/addrconf.c:addrconf_mod_rs_timer
  - net/ipv6/addrconf.c:addrconf_mod_rs_timer
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_force_start_gc
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_dad_start_timer
  - net/ipv6/mcast.c:mld_ifc_start_timer
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6_flowlabel.c:fl_release
  - net/ipv6/ip6mr.c:ipmr_do_expire_process
  - net/packet/af_packet.c:prb_open_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-manage.c:ncsi_start_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffff80001019f878-ffff80001019fbac: mod_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int mod_timer(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c03e8dd8)
Location: kernel/time/timer.c:1098
Inline: True
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:idle_worker_timeout
  - kernel/workqueue.c:worker_enter_idle
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:laptop_io_completion
  - mm/page-writeback.c:writeout_period
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:__save_error_info
  - fs/pstore/platform.c:pstore_timefunc
  - block/blk-timeout.c:blk_add_timer
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/video/fbdev/core/fbcon.c:fbcon_add_cursor_timer
  - drivers/video/fbdev/core/fbcon.c:cursor_timer_handler
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_timeout
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_poll
  - drivers/tty/serial/imx.c:imx_uart_timeout
  - drivers/tty/serial/imx.c:imx_uart_enable_ms
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_async_work
  - drivers/ata/libahci.c:ahci_qc_issue
  - drivers/ata/libahci.c:ahci_sw_activity_blink
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_set_next_interrupt
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/musb/musb_core.c:musb_stage0_irq
  - drivers/usb/musb/musb_core.c:musb_stage0_irq
  - drivers/usb/musb/musb_virthub.c:musb_port_suspend
  - drivers/input/input.c:input_repeat_key
  - drivers/md/md.c:md_write_end
  - drivers/md/md.c:safe_delay_store
  - drivers/mmc/core/host.c:mmc_retune_enable
  - drivers/mmc/host/sdhci.c:sdhci_send_command
  - drivers/mmc/host/sdhci.c:sdhci_send_command
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - sound/core/timer.c:snd_timer_s_start
  - net/core/sock.c:sk_reset_timer
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:est_timer
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data
  - net/core/drop_monitor.c:reset_per_cpu_data
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_start_timer
  - net/ipv4/igmp.c:igmp_start_timer
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
  - net/ipv6/addrconf.c:addrconf_mod_rs_timer
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_force_start_gc
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_dad_start_timer
  - net/ipv6/mcast.c:mld_ifc_start_timer
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6_flowlabel.c:fl_release
  - net/ipv6/ip6mr.c:ipmr_do_expire_process
  - net/packet/af_packet.c:prb_open_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-manage.c:ncsi_start_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
c03e9388-c03e9694: mod_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int mod_timer(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c0000000001ffb50)
Location: kernel/time/timer.c:1098
Inline: True
Inline callers:
  - kernel/time/timer.c:add_timer
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:idle_worker_timeout
  - kernel/workqueue.c:worker_enter_idle
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:laptop_io_completion
  - mm/page-writeback.c:writeout_period
  - mm/page-writeback.c:writeout_period
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:__save_error_info
  - fs/pstore/platform.c:pstore_timefunc
  - block/blk-timeout.c:blk_add_timer
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/video/fbdev/core/fbcon.c:fbcon_add_cursor_timer
  - drivers/video/fbdev/core/fbcon.c:cursor_timer_handler
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_timeout
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_async_work
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_set_next_interrupt
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/input.c:input_repeat_key
  - drivers/md/md.c:md_write_end
  - drivers/md/md.c:safe_delay_store
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_target_index
  - drivers/cpufreq/powernv-cpufreq.c:gpstate_timer_handler
  - drivers/mmc/core/host.c:mmc_retune_enable
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:est_timer
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data
  - net/core/drop_monitor.c:reset_per_cpu_data
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
  - net/ipv6/addrconf.c:addrconf_mod_rs_timer
  - net/ipv6/addrconf.c:addrconf_mod_rs_timer
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_force_start_gc
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6_flowlabel.c:fl_release
  - net/ipv6/ip6mr.c:ipmr_do_expire_process
  - net/packet/af_packet.c:prb_open_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-manage.c:ncsi_start_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
c000000000200810-c000000000200c50: mod_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int mod_timer(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffe00012d124)
Location: kernel/time/timer.c:1098
Inline: True
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:idle_worker_timeout
  - kernel/workqueue.c:worker_enter_idle
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:laptop_io_completion
  - mm/page-writeback.c:writeout_period
  - mm/page-writeback.c:writeout_period
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:__save_error_info
  - fs/pstore/platform.c:pstore_timefunc
  - block/blk-timeout.c:blk_add_timer
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/video/fbdev/core/fbcon.c:fbcon_add_cursor_timer
  - drivers/video/fbdev/core/fbcon.c:cursor_timer_handler
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_timeout
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_async_work
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_set_next_interrupt
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/input.c:input_repeat_key
  - drivers/md/md.c:md_write_end
  - drivers/md/md.c:safe_delay_store
  - drivers/mmc/core/host.c:mmc_retune_enable
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - net/core/sock.c:sk_reset_timer
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:est_timer
  - net/core/gen_estimator.c:est_timer
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data
  - net/core/drop_monitor.c:reset_per_cpu_data
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_start_timer
  - net/ipv4/igmp.c:igmp_start_timer
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_force_start_gc
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_dad_start_timer
  - net/ipv6/mcast.c:mld_ifc_start_timer
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6_flowlabel.c:fl_release
  - net/ipv6/ip6mr.c:ipmr_do_expire_process
  - net/packet/af_packet.c:prb_open_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-manage.c:ncsi_start_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffe00012d2e4-ffffffe00012d568: mod_timer (STB_GLOBAL)
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
int mod_timer(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112e848)
Location: kernel/time/timer.c:1098
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:idle_worker_timeout
  - kernel/workqueue.c:worker_enter_idle
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:laptop_io_completion
  - mm/page-writeback.c:writeout_period
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:__save_error_info
  - fs/pstore/platform.c:pstore_timefunc
  - block/blk-timeout.c:blk_add_timer
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/video/fbdev/core/fbcon.c:fbcon_add_cursor_timer
  - drivers/video/fbdev/core/fbcon.c:cursor_timer_handler
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_timeout
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_async_work
  - drivers/iommu/iova.c:queue_iova
  - drivers/nvme/host/multipath.c:nvme_read_ana_log
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_set_next_interrupt
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/input.c:input_repeat_key
  - drivers/md/md.c:md_write_end
  - drivers/md/md.c:safe_delay_store
  - drivers/mmc/core/host.c:mmc_retune_enable
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:est_timer
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data
  - net/core/drop_monitor.c:reset_per_cpu_data
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
  - net/ipv6/addrconf.c:addrconf_mod_rs_timer
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_force_start_gc
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_dad_start_timer
  - net/ipv6/mcast.c:mld_ifc_start_timer
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6_flowlabel.c:fl_release
  - net/ipv6/ip6mr.c:ipmr_do_expire_process
  - net/packet/af_packet.c:prb_open_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-manage.c:ncsi_start_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff8112ed50-ffffffff8112f05b: mod_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int mod_timer(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811212c8)
Location: kernel/time/timer.c:1098
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:idle_worker_timeout
  - kernel/workqueue.c:worker_enter_idle
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/rcu/tree.c:nocb_gp_wait
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:laptop_io_completion
  - mm/page-writeback.c:writeout_period
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:__save_error_info
  - fs/pstore/platform.c:pstore_timefunc
  - block/blk-timeout.c:blk_add_timer
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/video/fbdev/core/fbcon.c:fbcon_add_cursor_timer
  - drivers/video/fbdev/core/fbcon.c:cursor_timer_handler
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_timeout
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_async_work
  - drivers/iommu/iova.c:queue_iova
  - drivers/nvme/host/multipath.c:nvme_read_ana_log
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/vxlan.c:vxlan_changelink
  - drivers/net/vxlan.c:vxlan_open
  - drivers/net/vxlan.c:vxlan_cleanup
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/input.c:input_repeat_key
  - drivers/md/md.c:md_write_end
  - drivers/md/md.c:safe_delay_store
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:est_timer
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data
  - net/core/drop_monitor.c:reset_per_cpu_data
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
  - net/ipv6/addrconf.c:addrconf_mod_rs_timer
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_force_start_gc
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_dad_start_timer
  - net/ipv6/mcast.c:mld_ifc_start_timer
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6_flowlabel.c:fl_release
  - net/ipv6/ip6mr.c:ipmr_do_expire_process
  - net/packet/af_packet.c:prb_open_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-manage.c:ncsi_start_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff811214a0-ffffffff811217ab: mod_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int mod_timer(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112c568)
Location: kernel/time/timer.c:1098
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:idle_worker_timeout
  - kernel/workqueue.c:worker_enter_idle
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:laptop_io_completion
  - mm/page-writeback.c:writeout_period
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:__save_error_info
  - fs/pstore/platform.c:pstore_timefunc
  - block/blk-timeout.c:blk_add_timer
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/video/fbdev/core/fbcon.c:fbcon_add_cursor_timer
  - drivers/video/fbdev/core/fbcon.c:cursor_timer_handler
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_timeout
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_async_work
  - drivers/iommu/iova.c:queue_iova
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_set_next_interrupt
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/input.c:input_repeat_key
  - drivers/md/md.c:md_write_end
  - drivers/md/md.c:safe_delay_store
  - drivers/mmc/core/host.c:mmc_retune_enable
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:est_timer
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data
  - net/core/drop_monitor.c:reset_per_cpu_data
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
  - net/ipv6/addrconf.c:addrconf_mod_rs_timer
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_force_start_gc
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_dad_start_timer
  - net/ipv6/mcast.c:mld_ifc_start_timer
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6_flowlabel.c:fl_release
  - net/ipv6/ip6mr.c:ipmr_do_expire_process
  - net/packet/af_packet.c:prb_open_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-manage.c:ncsi_start_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff8112ca70-ffffffff8112cd7b: mod_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int mod_timer(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81139200)
Location: kernel/time/timer.c:1098
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:idle_worker_timeout
  - kernel/workqueue.c:worker_enter_idle
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:laptop_io_completion
  - mm/page-writeback.c:writeout_period
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:print_daily_error_info
  - fs/ext4/super.c:__save_error_info
  - fs/pstore/platform.c:pstore_timefunc
  - block/blk-timeout.c:blk_add_timer
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/video/fbdev/core/fbcon.c:fbcon_add_cursor_timer
  - drivers/video/fbdev/core/fbcon.c:cursor_timer_handler
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_timeout
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_async_work
  - drivers/iommu/iova.c:queue_iova
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_set_next_interrupt
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/input.c:input_repeat_key
  - drivers/md/md.c:md_write_end
  - drivers/md/md.c:safe_delay_store
  - drivers/mmc/core/host.c:mmc_retune_enable
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:est_timer
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data
  - net/core/drop_monitor.c:reset_per_cpu_data
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
  - net/ipv6/addrconf.c:addrconf_mod_rs_timer
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_force_start_gc
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_dad_start_timer
  - net/ipv6/mcast.c:mld_ifc_start_timer
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6_flowlabel.c:fl_release
  - net/ipv6/ip6mr.c:ipmr_do_expire_process
  - net/packet/af_packet.c:prb_open_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-manage.c:ncsi_start_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff81139200-ffffffff8113950d: mod_timer (STB_GLOBAL)
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
