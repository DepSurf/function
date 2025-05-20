# Function: <code>timer_delete</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
int timer_delete(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811d70f0)
Location: kernel/time/timer.c:1359
Inline: False
Direct callers:
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/sched/build_utility.c:psi_trigger_destroy
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
ffffffff811d70f0-ffffffff811d717f: timer_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int timer_delete(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811eb570)
Location: kernel/time/timer.c:1359
Inline: False
Direct callers:
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/sched/build_utility.c:psi_trigger_destroy
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
ffffffff811eb570-ffffffff811eb5f5: timer_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int timer_delete(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff812015a0)
Location: kernel/time/timer.c:1359
Inline: False
Direct callers:
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/sched/build_utility.c:psi_trigger_destroy
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:nocb_gp_wait
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
ffffffff812015a0-ffffffff81201625: timer_delete (STB_GLOBAL)
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
