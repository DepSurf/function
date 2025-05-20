# Function: <code>del_timer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int del_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810ec4a0)
Location: kernel/time/timer.c:1020
Inline: False
Direct callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_reorder
  - mm/page-writeback.c:laptop_sync_completion
  - block/cfq-iosched.c:__cfq_set_active_queue
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:cfq_insert_request
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/wakeup.c:__pm_stay_awake
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:pneigh_enqueue
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/ipv4/igmp.c:igmp_stop_timer
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_added
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff810ec4a0-ffffffff810ec527: del_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int del_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810f3b70)
Location: kernel/time/timer.c:1161
Inline: False
Direct callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_reorder
  - mm/page-writeback.c:laptop_sync_completion
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:__pm_stay_awake
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_proxy_process
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_stop_timer
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_added
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff810f3b70-ffffffff810f3bf7: del_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int del_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810f9ac0)
Location: kernel/time/timer.c:1171
Inline: False
Direct callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_reorder
  - mm/page-writeback.c:laptop_sync_completion
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:__pm_stay_awake
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_proxy_process
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_stop_timer
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_added
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff810f9ac0-ffffffff810f9b43: del_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int del_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810fd1b0)
Location: kernel/time/timer.c:1146
Inline: True
Direct callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_reorder
  - mm/page-writeback.c:laptop_sync_completion
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_proxy_process
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_stop_timer
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff810fd1b0-ffffffff810fd224: del_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int del_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81107a80)
Location: kernel/time/timer.c:1184
Inline: True
Direct callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_reorder
  - mm/page-writeback.c:laptop_sync_completion
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_proxy_process
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_stop_timer
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_ifc_stop_timer
  - net/ipv6/mcast.c:mld_gq_stop_timer
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff81107a80-ffffffff81107af4: del_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int del_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811131c0)
Location: kernel/time/timer.c:1192
Inline: True
Direct callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_reorder
  - mm/page-writeback.c:laptop_sync_completion
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_proxy_process
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_stop_timer
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_ifc_stop_timer
  - net/ipv6/mcast.c:mld_gq_stop_timer
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff811131c0-ffffffff8111323b: del_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int del_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8111e800)
Location: kernel/time/timer.c:1191
Inline: True
Direct callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_reorder
  - mm/page-writeback.c:laptop_sync_completion
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_proxy_process
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_stop_timer
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_ifc_stop_timer
  - net/ipv6/mcast.c:mld_gq_stop_timer
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff8111e800-ffffffff8111e87b: del_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int del_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811294e0)
Location: kernel/time/timer.c:1186
Inline: True
Direct callers:
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_reorder
  - mm/page-writeback.c:laptop_sync_completion
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_proxy_process
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_stop_timer
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_ifc_stop_timer
  - net/ipv6/mcast.c:mld_gq_stop_timer
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff811294e0-ffffffff8112955d: del_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int del_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81135480)
Location: kernel/time/timer.c:1190
Inline: True
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat_disable
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
  - mm/page-writeback.c:laptop_sync_completion
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_proxy_process
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_stop_timer
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_ifc_stop_timer
  - net/ipv6/mcast.c:mld_gq_stop_timer
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81135480-ffffffff811354fd: del_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int del_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811442b0)
Location: kernel/time/timer.c:1202
Inline: True
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat_disable
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
  - mm/page-writeback.c:laptop_sync_completion
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd_queue.c:dwc2_schedule_periodic
  - net/core/sock.c:sk_stop_timer
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_destroy
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_destroy
  - net/xfrm/xfrm_policy.c:xfrm_policy_destroy
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff811442b0-ffffffff8114432d: del_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int del_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81140840)
Location: kernel/time/timer.c:1196
Inline: True
Direct callers:
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
  - mm/page-writeback.c:laptop_sync_completion
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd_queue.c:dwc2_schedule_periodic
  - net/core/sock.c:sk_stop_timer
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_destroy
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_destroy
  - net/xfrm/xfrm_policy.c:xfrm_policy_destroy
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81140840-ffffffff811408bd: del_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int del_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811419c0)
Location: kernel/time/timer.c:1198
Inline: True
Direct callers:
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
  - mm/page-writeback.c:laptop_sync_completion
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
  - net/core/sock.c:sk_stop_timer
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_destroy
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_destroy
  - net/xfrm/xfrm_policy.c:xfrm_policy_destroy
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff811419c0-ffffffff81141a3d: del_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int del_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81164f00)
Location: kernel/time/timer.c:1198
Inline: True
Direct callers:
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
  - mm/page-writeback.c:laptop_sync_completion
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
  - net/core/sock.c:sk_stop_timer
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_destroy
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_destroy
  - net/xfrm/xfrm_policy.c:xfrm_policy_destroy
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81164f00-ffffffff81164f7d: del_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int del_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81198b10)
Location: kernel/time/timer.c:1251
Inline: False
Direct callers:
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
  - mm/page-writeback.c:laptop_sync_completion
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_destroy
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_destroy
  - net/xfrm/xfrm_policy.c:xfrm_policy_destroy
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81198b10-ffffffff81198b9f: del_timer (STB_GLOBAL)
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
In kernel/workqueue.c (ffffffff81114740)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/sched/build_utility.c (ffffffff8117bb65)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_trigger_destroy
```
```
In kernel/time/clocksource.c (ffffffff811e02bb)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
```
```
In mm/page-writeback.c (ffffffff8136a8b2)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - mm/page-writeback.c:laptop_sync_completion
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81914d79)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
```
```
In drivers/tty/sysrq.c (ffffffff81a5b07a)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/vt/vt.c (ffffffff81a6c57b)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:poke_blanked_console
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81a8ede5)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown
```
```
In drivers/base/power/wakeup.c (ffffffff81b08202)
Location: include/linux/timer.h:211
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff81c1fe46)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:unlink1
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81c47a55)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81c50955)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81c6ed3c)
Location: include/linux/timer.h:211
Inline: True
```
```
In drivers/input/input.c (ffffffff81ca67bf)
Location: include/linux/timer.h:211
Inline: True
```
```
In net/core/sock.c (ffffffff81d9a14d)
Location: include/linux/timer.h:211
Inline: True
```
```
In net/core/neighbour.c (ffffffff81dd8196)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_destroy
```
```
In net/sched/sch_generic.c (ffffffff81e52c60)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/ipv4/igmp.c (ffffffff81efb185)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
```
```
In net/ipv4/inet_fragment.c (ffffffff81f09a02)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81f20b1e)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f31057)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_destroy
  - net/xfrm/xfrm_policy.c:xfrm_policy_destroy
```
```
In net/ipv6/addrconf.c (ffffffff81f63d24)
Location: include/linux/timer.h:211
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81f7e8c0)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81fa5cbc)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
```
```
In net/ipv6/ip6mr.c (ffffffff81fae8e5)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In kernel/workqueue.c (ffffffff811206d0)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/sched/build_utility.c (ffffffff8118c773)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_trigger_destroy
```
```
In kernel/time/clocksource.c (ffffffff811f47bb)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
```
```
In mm/page-writeback.c (ffffffff8139ca42)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - mm/page-writeback.c:laptop_sync_completion
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81958399)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
```
```
In drivers/tty/sysrq.c (ffffffff81aa5672)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/vt/vt.c (ffffffff81ab6c9b)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:poke_blanked_console
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81ada595)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown
```
```
In drivers/base/power/wakeup.c (ffffffff81b56232)
Location: include/linux/timer.h:211
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff81c86dbd)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:unlink1
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81caf035)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81cb7ed5)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81cd62fc)
Location: include/linux/timer.h:211
Inline: True
```
```
In drivers/input/input.c (ffffffff81d0deff)
Location: include/linux/timer.h:211
Inline: True
```
```
In net/core/sock.c (ffffffff81e0793d)
Location: include/linux/timer.h:211
Inline: True
```
```
In net/core/neighbour.c (ffffffff81e494b3)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_destroy
```
```
In net/sched/sch_generic.c (ffffffff81eae4fd)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/ipv4/igmp.c (ffffffff81f5ac15)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
```
```
In net/ipv4/inet_fragment.c (ffffffff81f69512)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81f8133e)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f91806)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_destroy
  - net/xfrm/xfrm_policy.c:xfrm_policy_destroy
```
```
In net/ipv6/addrconf.c (ffffffff81fc3f67)
Location: include/linux/timer.h:211
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81fdeac7)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff8200652c)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
```
```
In net/ipv6/ip6mr.c (ffffffff8200fd65)
Location: include/linux/timer.h:211
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In kernel/workqueue.c (ffffffff81128720)
Location: include/linux/timer.h:196
Inline: True
Inline callers:
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/sched/build_utility.c (ffffffff8119b103)
Location: include/linux/timer.h:196
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_trigger_destroy
```
```
In kernel/rcu/tree.c (ffffffff811dff3b)
Location: include/linux/timer.h:196
Inline: True
Inline callers:
  - kernel/rcu/tree.c:nocb_gp_wait
```
```
In kernel/time/clocksource.c (ffffffff8120a8fb)
Location: include/linux/timer.h:196
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
```
```
In mm/page-writeback.c (ffffffff813c6722)
Location: include/linux/timer.h:196
Inline: True
Inline callers:
  - mm/page-writeback.c:laptop_sync_completion
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff819a1909)
Location: include/linux/timer.h:196
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
```
```
In drivers/tty/sysrq.c (ffffffff81af80c2)
Location: include/linux/timer.h:196
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/vt/vt.c (ffffffff81b0999b)
Location: include/linux/timer.h:196
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:poke_blanked_console
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81b2d895)
Location: include/linux/timer.h:196
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown
```
```
In drivers/base/power/wakeup.c (ffffffff81bae7f2)
Location: include/linux/timer.h:196
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff81d3b81d)
Location: include/linux/timer.h:196
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:unlink1
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81d63ce5)
Location: include/linux/timer.h:196
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81d6cc45)
Location: include/linux/timer.h:196
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81d8b2dc)
Location: include/linux/timer.h:196
Inline: True
```
```
In drivers/input/input.c (ffffffff81dc3b1f)
Location: include/linux/timer.h:196
Inline: True
```
```
In net/core/sock.c (ffffffff81ec533d)
Location: include/linux/timer.h:196
Inline: True
```
```
In net/core/neighbour.c (ffffffff81f081a3)
Location: include/linux/timer.h:196
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_destroy
```
```
In net/sched/sch_generic.c (ffffffff81f70f74)
Location: include/linux/timer.h:196
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/ipv4/igmp.c (ffffffff82021155)
Location: include/linux/timer.h:196
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
```
```
In net/ipv4/inet_fragment.c (ffffffff8202fb92)
Location: include/linux/timer.h:196
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff820479be)
Location: include/linux/timer.h:196
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205f566)
Location: include/linux/timer.h:196
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_destroy
  - net/xfrm/xfrm_policy.c:xfrm_policy_destroy
```
```
In net/ipv6/addrconf.c (ffffffff82091517)
Location: include/linux/timer.h:196
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff820ac647)
Location: include/linux/timer.h:196
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff820d538c)
Location: include/linux/timer.h:196
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
```
```
In net/ipv6/ip6mr.c (ffffffff820decf5)
Location: include/linux/timer.h:196
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
int del_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffff80001019ebe0)
Location: kernel/time/timer.c:1190
Inline: True
Direct callers:
  - kernel/workqueue.c:try_to_grab_pending
  - mm/page-writeback.c:laptop_sync_completion
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_poll
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - net/core/sock.c:sk_stop_timer
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_proxy_process
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_stop_timer
  - net/ipv4/igmp.c:igmp_stop_timer
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_ifc_stop_timer
  - net/ipv6/mcast.c:mld_gq_stop_timer
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffff80001019ebe0-ffff80001019ec78: del_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int del_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c03e7a50)
Location: kernel/time/timer.c:1190
Inline: True
Direct callers:
  - kernel/workqueue.c:try_to_grab_pending
  - mm/page-writeback.c:laptop_sync_completion
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_poll
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/musb/musb_core.c:musb_stage0_irq
  - drivers/usb/musb/musb_core.c:musb_stage0_irq
  - drivers/mmc/host/sdhci.c:sdhci_del_timer
  - drivers/mmc/host/sdhci.c:sdhci_del_timer
  - sound/core/timer.c:snd_timer_s_stop
  - net/core/sock.c:sk_stop_timer
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_proxy_process
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_stop_timer
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_ifc_stop_timer
  - net/ipv6/mcast.c:mld_gq_stop_timer
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
c03e7a50-c03e7ae4: del_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int del_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c0000000001fe530)
Location: kernel/time/timer.c:1190
Inline: True
Direct callers:
  - kernel/workqueue.c:try_to_grab_pending
  - mm/page-writeback.c:laptop_sync_completion
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_proxy_process
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_stop_timer
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
c0000000001fe530-c0000000001fe5ec: del_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int del_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffe00012c1ea)
Location: kernel/time/timer.c:1190
Inline: True
Direct callers:
  - kernel/workqueue.c:try_to_grab_pending
  - mm/page-writeback.c:laptop_sync_completion
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - net/core/sock.c:sk_stop_timer
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_proxy_process
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_stop_timer
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffe00012c1ea-ffffffe00012c252: del_timer (STB_GLOBAL)
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
int del_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112dc30)
Location: kernel/time/timer.c:1190
Inline: True
Direct callers:
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
  - mm/page-writeback.c:laptop_sync_completion
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_proxy_process
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_stop_timer
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_ifc_stop_timer
  - net/ipv6/mcast.c:mld_gq_stop_timer
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff8112dc30-ffffffff8112dcad: del_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int del_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811204a0)
Location: kernel/time/timer.c:1190
Inline: True
Direct callers:
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
  - mm/page-writeback.c:laptop_sync_completion
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/usb/core/hcd.c:unlink1
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_proxy_process
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_stop_timer
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_ifc_stop_timer
  - net/ipv6/mcast.c:mld_gq_stop_timer
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff811204a0-ffffffff8112051d: del_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int del_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112b950)
Location: kernel/time/timer.c:1190
Inline: True
Direct callers:
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
  - mm/page-writeback.c:laptop_sync_completion
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_proxy_process
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/netfilter/nfnetlink_log.c:__nfulnl_flush
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expect_iterate_net
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expect_iterate_destroy
  - net/netfilter/nf_conntrack_expect.c:nf_ct_find_expectation
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_new_expect
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_del_expect
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_stop_timer
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_ifc_stop_timer
  - net/ipv6/mcast.c:mld_gq_stop_timer
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff8112b950-ffffffff8112b9cd: del_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int del_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81138000)
Location: kernel/time/timer.c:1190
Inline: True
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat_disable
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
  - mm/page-writeback.c:laptop_sync_completion
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_proxy_process
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_stop_timer
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_ifc_stop_timer
  - net/ipv6/mcast.c:mld_gq_stop_timer
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81138000-ffffffff8113807d: del_timer (STB_GLOBAL)
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
