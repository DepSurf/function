# Function: <code>hlist_unhashed_lockless</code>

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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105231a)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
```
```
In kernel/workqueue.c (ffffffff810c6f6d)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_enter_idle
  - kernel/workqueue.c:__queue_delayed_work
```
```
In kernel/time/timer.c (ffffffff81145782)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/time/clocksource.c (ffffffff8114be84)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In block/blk-timeout.c (ffffffff8154d2ff)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - block/blk-timeout.c:blk_add_timer
  - block/blk-timeout.c:blk_add_timer
```
```
In block/blk-mq.c (ffffffff81552c2a)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
```
```
In block/blk-stat.c (ffffffff81555af8)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add
```
```
In block/blk-wbt.c (ffffffff8157a123)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_wait
```
```
In drivers/xen/grant-table.c (ffffffff8171200f)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/random.c (ffffffff817711d2)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
```
```
In drivers/iommu/iova.c (ffffffff81793a5e)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
```
```
In drivers/net/tun.c (ffffffff8188c1ab)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818e4b6d)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81913e0e)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
```
```
In drivers/leds/led-core.c (ffffffff819b76ad)
Location: include/linux/list.h:792
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81a49334)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_summary_probe
```
```
In net/sched/sch_generic.c (ffffffff81a669c4)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa68e1)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_queue_unlink
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac471e)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv6/addrconf.c (ffffffff81b3e8a2)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4ed96)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_force_start_gc
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b66ed6)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b6feac)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/ipv6/addrconf_core.c (ffffffff81b81b90)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
```
```
In net/mptcp/protocol.c (ffffffff81baccfb)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff810514fa)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
```
```
In kernel/workqueue.c (ffffffff810c207d)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_enter_idle
  - kernel/workqueue.c:__queue_delayed_work
```
```
In kernel/sched/psi.c (ffffffff8110a37f)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_group_change
  - kernel/sched/psi.c:psi_poll_work
```
```
In kernel/time/timer.c (ffffffff81141852)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/time/clocksource.c (ffffffff811482e4)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In block/blk-timeout.c (ffffffff81569706)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - block/blk-timeout.c:blk_add_timer
  - block/blk-timeout.c:blk_add_timer
```
```
In block/blk-mq.c (ffffffff8156ecd3)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
```
```
In block/blk-stat.c (ffffffff81572348)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add
```
```
In block/blk-wbt.c (ffffffff81597033)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_wait
```
```
In drivers/xen/grant-table.c (ffffffff8172ed9f)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/random.c (ffffffff8178c202)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
```
```
In drivers/iommu/iova.c (ffffffff817c05ae)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
```
```
In drivers/net/tun.c (ffffffff8189a298)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818ee03d)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8191b42e)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
```
```
In drivers/leds/led-core.c (ffffffff819b9bad)
Location: include/linux/list.h:819
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81a4ebc5)
Location: include/linux/list.h:819
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81a6eaa4)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab0f31)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_queue_unlink
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad005e)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv6/addrconf.c (ffffffff81b4d432)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
```
```
In net/ipv6/ip6_fib.c (ffffffff81b5da16)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_force_start_gc
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b75436)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b7e9bc)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/ipv6/addrconf_core.c (ffffffff81b91290)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
```
```
In net/mptcp/protocol.c (ffffffff81bc058c)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:__mptcp_push_pending
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff810538aa)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
```
```
In kernel/workqueue.c (ffffffff810c395d)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_enter_idle
  - kernel/workqueue.c:__queue_delayed_work
```
```
In kernel/sched/psi.c (ffffffff8110bf1c)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_group_change
  - kernel/sched/psi.c:psi_poll_worker
```
```
In kernel/time/timer.c (ffffffff81142ca2)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/time/clocksource.c (ffffffff811491cf)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In block/blk-timeout.c (ffffffff81571676)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - block/blk-timeout.c:blk_add_timer
  - block/blk-timeout.c:blk_add_timer
```
```
In block/blk-mq.c (ffffffff815768af)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
```
```
In block/blk-stat.c (ffffffff8157a368)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add
```
```
In block/blk-wbt.c (ffffffff8159dc8f)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_wait
```
```
In drivers/xen/grant-table.c (ffffffff81bf6761)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_end_foreign_access
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/random.c (ffffffff8176f13f)
Location: include/linux/list.h:819
Inline: True
```
```
In drivers/iommu/iova.c (ffffffff817a3664)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
```
```
In drivers/net/tun.c (ffffffff8187c068)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818d16e3)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
```
In drivers/usb/host/xhci-ring.c (ffffffff818fe9ee)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
```
```
In drivers/leds/led-core.c (ffffffff8199e49d)
Location: include/linux/list.h:819
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81a33be4)
Location: include/linux/list.h:819
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81a57334)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9c2ad)
Location: include/linux/list.h:819
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abb0ba)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv6/addrconf.c (ffffffff81b3b25c)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4bc85)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_force_start_gc
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b63ce6)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b6d5bc)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/ipv6/addrconf_core.c (ffffffff81b80492)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
```
```
In net/mptcp/protocol.c (ffffffff81baee59)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:__mptcp_push_pending
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105c0ca)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
```
```
In kernel/workqueue.c (ffffffff810d64fd)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_enter_idle
  - kernel/workqueue.c:__queue_delayed_work
```
```
In kernel/sched/psi.c (ffffffff8112ac47)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_group_change
  - kernel/sched/psi.c:psi_poll_worker
```
```
In kernel/time/timer.c (ffffffff811661e6)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:add_timer
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/time/clocksource.c (ffffffff8116d2d0)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In block/blk-timeout.c (ffffffff815d5d36)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - block/blk-timeout.c:blk_add_timer
  - block/blk-timeout.c:blk_add_timer
```
```
In block/blk-mq.c (ffffffff815db561)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
```
```
In block/blk-stat.c (ffffffff815df6cf)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add
```
```
In block/blk-wbt.c (ffffffff8160636f)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_wait
```
```
In drivers/xen/grant-table.c (ffffffff81790e5c)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/random.c (ffffffff817f497c)
Location: include/linux/list.h:819
Inline: True
```
```
In drivers/net/tun.c (ffffffff8190d5a9)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8196bc93)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8199db34)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
```
```
In drivers/leds/led-core.c (ffffffff81a4b11d)
Location: include/linux/list.h:819
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81ae95d4)
Location: include/linux/list.h:819
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81b1018c)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b57b6d)
Location: include/linux/list.h:819
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7840a)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv6/addrconf.c (ffffffff81c01a69)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
```
```
In net/ipv6/ip6_fib.c (ffffffff81c12fcf)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_force_start_gc
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2b7a6)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81c3541c)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/ipv6/addrconf_core.c (ffffffff81c4c4b2)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
```
```
In net/mptcp/protocol.c (ffffffff81c7ca39)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:__mptcp_push_pending
  - net/mptcp/protocol.c:__mptcp_clean_una
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff81067178)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
```
```
In kernel/workqueue.c (ffffffff810efe4d)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_enter_idle
  - kernel/workqueue.c:__queue_delayed_work
```
```
In kernel/sched/build_utility.c (ffffffff8113f811)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_group_change
  - kernel/sched/build_utility.c:psi_poll_worker
```
```
In kernel/time/timer.c (ffffffff81198b3c)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - kernel/time/timer.c:del_timer
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:add_timer
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/time/clocksource.c (ffffffff811a0e90)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In block/blk-timeout.c (ffffffff81681ace)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - block/blk-timeout.c:blk_add_timer
  - block/blk-timeout.c:blk_add_timer
```
```
In block/blk-mq.c (ffffffff81689677)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_end_request_batch
```
```
In block/blk-stat.c (ffffffff8168dde8)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add
```
```
In block/blk-wbt.c (ffffffff816ba058)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_wait
```
```
In drivers/xen/grant-table.c (ffffffff818c94ae)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/random.c (ffffffff81ec2d36)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
```
```
In drivers/net/tun.c (ffffffff81a606af)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81ac614e)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
```
In drivers/leds/led-core.c (ffffffff81bb961d)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_blink_set_oneshot
```
```
In net/core/drop_monitor.c (ffffffff81c6bd94)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_summary_probe
```
```
In net/sched/sch_generic.c (ffffffff81c9734c)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce5b5f)
Location: include/linux/list.h:865
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d080b5)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv6/addrconf.c (ffffffff81d9b783)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
```
```
In net/ipv6/ip6_fib.c (ffffffff81dae570)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_force_start_gc
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dc8d3e)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81dd2dfc)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/ipv6/addrconf_core.c (ffffffff81dec842)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
```
```
In net/mptcp/protocol.c (ffffffff81e21e20)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:__mptcp_push_pending
  - net/mptcp/protocol.c:__mptcp_clean_una
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff810766d8)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
```
```
In kernel/workqueue.c (ffffffff811117cd)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_enter_idle
  - kernel/workqueue.c:__queue_delayed_work
```
```
In kernel/time/timer.c (ffffffff811d6f00)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - kernel/time/timer.c:timer_shutdown
  - kernel/time/timer.c:timer_delete
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:add_timer
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/time/clocksource.c (ffffffff811e080a)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In block/blk-timeout.c (ffffffff8173f10e)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - block/blk-timeout.c:blk_add_timer
  - block/blk-timeout.c:blk_add_timer
```
```
In block/blk-mq.c (ffffffff81744709)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:__blk_mq_end_request
```
```
In block/blk-stat.c (ffffffff8174c6d8)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add
```
```
In block/blk-wbt.c (ffffffff8177a587)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_wait
```
```
In drivers/xen/grant-table.c (ffffffff81a1a31e)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/random.c (ffffffff81a94e1d)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:add_interrupt_randomness
```
```
In drivers/net/tun.c (ffffffff81bebd9f)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81c5027e)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
```
In drivers/leds/led-core.c (ffffffff81d5e92d)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_blink_set_oneshot
```
```
In net/core/drop_monitor.c (ffffffff81e2381f)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_summary_probe
```
```
In net/sched/sch_generic.c (ffffffff81e5317c)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea8d78)
Location: include/linux/list.h:865
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81eccb75)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv6/addrconf.c (ffffffff81f6a3c3)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
```
```
In net/ipv6/ip6_fib.c (ffffffff81f7e07f)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_force_start_gc
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f99a3e)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81fa42ec)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/ipv6/addrconf_core.c (ffffffff81fc05d2)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
```
```
In net/mptcp/protocol.c (ffffffff81ff93b0)
Location: include/linux/list.h:865
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:__mptcp_push_pending
  - net/mptcp/protocol.c:__mptcp_clean_una
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff81078958)
Location: include/linux/list.h:880
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
```
```
In kernel/workqueue.c (ffffffff8111e3bd)
Location: include/linux/list.h:880
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_enter_idle
  - kernel/workqueue.c:__queue_delayed_work
```
```
In kernel/time/timer.c (ffffffff811eb379)
Location: include/linux/list.h:880
Inline: True
Inline callers:
  - kernel/time/timer.c:timer_shutdown
  - kernel/time/timer.c:timer_delete
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:add_timer
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/time/clocksource.c (ffffffff811f4d0e)
Location: include/linux/list.h:880
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff81334e5f)
Location: include/linux/list.h:880
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_map
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_storage
```
```
In block/blk-timeout.c (ffffffff8177b67e)
Location: include/linux/list.h:880
Inline: True
Inline callers:
  - block/blk-timeout.c:blk_add_timer
  - block/blk-timeout.c:blk_add_timer
```
```
In block/blk-stat.c (ffffffff81788e18)
Location: include/linux/list.h:880
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add
```
```
In block/blk-wbt.c (ffffffff817ba377)
Location: include/linux/list.h:880
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_wait
```
```
In drivers/xen/grant-table.c (ffffffff81a636fe)
Location: include/linux/list.h:880
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/random.c (ffffffff81ae063d)
Location: include/linux/list.h:880
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:add_interrupt_randomness
```
```
In drivers/net/tun.c (ffffffff81c44250)
Location: include/linux/list.h:880
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81cb782e)
Location: include/linux/list.h:880
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
```
In drivers/leds/led-core.c (ffffffff81dc989d)
Location: include/linux/list.h:880
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_blink_set_oneshot
```
```
In net/core/drop_monitor.c (ffffffff81e98d5f)
Location: include/linux/list.h:880
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_summary_probe
```
```
In net/sched/sch_generic.c (ffffffff81eae9fb)
Location: include/linux/list.h:880
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f075f8)
Location: include/linux/list.h:880
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2b852)
Location: include/linux/list.h:880
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv6/ip6_fib.c (ffffffff81fde28e)
Location: include/linux/list.h:880
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_force_start_gc
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffa40b)
Location: include/linux/list.h:880
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff82004b9c)
Location: include/linux/list.h:880
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/ipv6/addrconf_core.c (ffffffff82021552)
Location: include/linux/list.h:880
Inline: True
Inline callers:
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
```
```
In net/mptcp/protocol.c (ffffffff820758c0)
Location: include/linux/list.h:880
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:__mptcp_push_pending
  - net/mptcp/protocol.c:__mptcp_clean_una
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8107fe08)
Location: include/linux/list.h:969
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810aa15a)
Location: include/linux/list.h:969
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:__vector_schedule_cleanup
```
```
In kernel/workqueue.c (ffffffff8112ba64)
Location: include/linux/list.h:969
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/workqueue.c:worker_enter_idle
```
```
In kernel/rcu/update.c (ffffffff811cb89b)
Location: include/linux/list.h:969
Inline: True
Inline callers:
  - kernel/rcu/update.c:call_rcu_tasks_generic
```
```
In kernel/rcu/tree.c (ffffffff811d3b45)
Location: include/linux/list.h:969
Inline: True
Inline callers:
  - kernel/rcu/tree.c:show_rcu_nocb_gp_state
  - kernel/rcu/tree.c:__call_rcu_nocb_wake
```
```
In kernel/time/timer.c (ffffffff812013a9)
Location: include/linux/list.h:969
Inline: True
Inline callers:
  - kernel/time/timer.c:timer_shutdown
  - kernel/time/timer.c:timer_delete
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:add_timer
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/time/clocksource.c (ffffffff8120ae65)
Location: include/linux/list.h:969
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8135942d)
Location: include/linux/list.h:969
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_map
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_storage
```
```
In block/blk-timeout.c (ffffffff817bda6b)
Location: include/linux/list.h:969
Inline: True
Inline callers:
  - block/blk-timeout.c:blk_add_timer
  - block/blk-timeout.c:blk_add_timer
```
```
In block/blk-stat.c (ffffffff817cb53b)
Location: include/linux/list.h:969
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add
```
```
In block/blk-wbt.c (ffffffff817feae7)
Location: include/linux/list.h:969
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_wait
```
```
In drivers/xen/grant-table.c (ffffffff81ab5f4d)
Location: include/linux/list.h:969
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/random.c (ffffffff81b33a3d)
Location: include/linux/list.h:969
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:add_interrupt_randomness
```
```
In drivers/net/tun.c (ffffffff81cf9b10)
Location: include/linux/list.h:969
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81d6c57e)
Location: include/linux/list.h:969
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
```
In drivers/leds/led-core.c (ffffffff81e8234d)
Location: include/linux/list.h:969
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_blink_set_oneshot
```
```
In net/core/drop_monitor.c (ffffffff81f5b3ef)
Location: include/linux/list.h:969
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_summary_probe
```
```
In net/sched/sch_generic.c (ffffffff81f71498)
Location: include/linux/list.h:969
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fcb958)
Location: include/linux/list.h:969
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff058e)
Location: include/linux/list.h:969
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv6/ip6_fib.c (ffffffff820abe0e)
Location: include/linux/list.h:969
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_force_start_gc
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820c8087)
Location: include/linux/list.h:969
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff820d396c)
Location: include/linux/list.h:969
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/ipv6/addrconf_core.c (ffffffff820f0682)
Location: include/linux/list.h:969
Inline: True
Inline callers:
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
```
```
In net/mptcp/protocol.c (ffffffff82149f30)
Location: include/linux/list.h:969
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:__mptcp_push_pending
  - net/mptcp/protocol.c:__mptcp_clean_una
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
