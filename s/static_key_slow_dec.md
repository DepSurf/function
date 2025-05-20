# Function: <code>static_key_slow_dec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void static_key_slow_dec(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8118afe0)
Location: kernel/jump_label.c:97
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - kernel/sched/core.c:preempt_notifier_dec
  - kernel/sched/core.c:sched_feat_write
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/clock.c:__clear_sched_clock_stable
  - kernel/sched/fair.c:cfs_bandwidth_usage_dec
  - kernel/cgroup.c:rebind_subsystems
  - kernel/cpuset.c:cpuset_css_offline
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/events/core.c:sw_perf_event_destroy
  - mm/memcontrol.c:mem_cgroup_css_free
  - drivers/i2c/i2c-core.c:i2c_transfer_trace_unreg
  - net/core/sock.c:sk_clear_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:net_dec_ingress_queue
  - net/core/dev.c:net_enable_timestamp
  - net/core/net-sysfs.c:store_rps_map
  - net/netfilter/core.c:nf_unregister_net_hook
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata
  - net/ipv4/tcp_memcontrol.c:tcp_destroy_cgroup
```
**Symbols:**

```
ffffffff8118afe0-ffffffff8118b033: static_key_slow_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void static_key_slow_dec(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8119d6a0)
Location: kernel/jump_label.c:171
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - kernel/sched/core.c:preempt_notifier_dec
  - kernel/sched/clock.c:__clear_sched_clock_stable
  - kernel/sched/fair.c:cfs_bandwidth_usage_dec
  - kernel/cpuset.c:cpuset_css_offline
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/events/core.c:sw_perf_event_destroy
  - kernel/jump_label.c:static_key_disable
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - drivers/i2c/i2c-core.c:i2c_transfer_trace_unreg
  - net/core/sock.c:sk_clear_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:net_enable_timestamp
  - net/core/dev.c:net_dec_egress_queue
  - net/core/dev.c:net_dec_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/netfilter/core.c:nf_unregister_net_hook
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata
```
**Symbols:**

```
ffffffff8119d6a0-ffffffff8119d6f3: static_key_slow_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void static_key_slow_dec(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811ad0c0)
Location: kernel/jump_label.c:171
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - kernel/sched/core.c:preempt_notifier_dec
  - kernel/sched/clock.c:__clear_sched_clock_stable
  - kernel/sched/fair.c:cfs_bandwidth_usage_dec
  - kernel/cpuset.c:cpuset_css_offline
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/bpf/cgroup.c:__cgroup_bpf_update
  - kernel/bpf/cgroup.c:cgroup_bpf_put
  - kernel/events/core.c:sw_perf_event_destroy
  - kernel/jump_label.c:static_key_disable
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - drivers/i2c/i2c-core.c:i2c_transfer_trace_unreg
  - net/core/sock.c:sk_clear_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:net_dec_egress_queue
  - net/core/dev.c:net_dec_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/netfilter/core.c:nf_unregister_net_hook
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata
```
**Symbols:**

```
ffffffff811ad0c0-ffffffff811ad113: static_key_slow_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void static_key_slow_dec(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811b4560)
Location: kernel/jump_label.c:177
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - kernel/sched/core.c:preempt_notifier_dec
  - kernel/sched/fair.c:cfs_bandwidth_usage_dec
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/bpf/cgroup.c:__cgroup_bpf_update
  - kernel/bpf/cgroup.c:cgroup_bpf_put
  - kernel/events/core.c:sw_perf_event_destroy
  - kernel/jump_label.c:static_key_disable
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg
  - net/core/sock.c:sk_clear_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:free_netdev
  - net/core/dev.c:net_dec_egress_queue
  - net/core/dev.c:net_dec_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata
```
**Symbols:**

```
ffffffff811b4560-ffffffff811b45a9: static_key_slow_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void static_key_slow_dec(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811c8370)
Location: kernel/jump_label.c:225
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/tracepoint.c:trace_resched_ipi_unreg
  - arch/x86/kernel/tracepoint.c:trace_pagefault_unreg
  - kernel/sched/core.c:preempt_notifier_dec
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_put
  - kernel/events/core.c:sw_perf_event_destroy
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg
  - net/core/sock.c:sk_clear_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:free_netdev
  - net/core/dev.c:net_dec_egress_queue
  - net/core/dev.c:net_dec_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata
```
**Symbols:**

```
ffffffff811c8370-ffffffff811c83b9: static_key_slow_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void static_key_slow_dec(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811e8780)
Location: kernel/jump_label.c:226
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/tracepoint.c:trace_resched_ipi_unreg
  - arch/x86/kernel/tracepoint.c:trace_pagefault_unreg
  - kernel/sched/core.c:preempt_notifier_dec
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_put
  - kernel/events/core.c:sw_perf_event_destroy
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg
  - net/core/sock.c:sk_clear_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:net_dec_egress_queue
  - net/core/dev.c:net_dec_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/ipv4/tcp_input.c:clean_acked_data_disable
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata
```
**Symbols:**

```
ffffffff811e8780-ffffffff811e87c9: static_key_slow_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void static_key_slow_dec(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811f9450)
Location: kernel/jump_label.c:249
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/tracepoint.c:trace_resched_ipi_unreg
  - arch/x86/kernel/tracepoint.c:trace_pagefault_unreg
  - kernel/sched/core.c:preempt_notifier_dec
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_put
  - kernel/events/core.c:sw_perf_event_destroy
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg
  - net/core/sock.c:sk_clear_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:net_dec_egress_queue
  - net/core/dev.c:net_dec_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/ipv4/tcp_input.c:clean_acked_data_disable
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata
  - net/ipv6/udp.c:udpv6_destroy_sock
```
**Symbols:**

```
ffffffff811f9450-ffffffff811f9499: static_key_slow_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void static_key_slow_dec(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81211430)
Location: kernel/jump_label.c:267
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/tracepoint.c:trace_resched_ipi_unreg
  - arch/x86/kernel/tracepoint.c:trace_pagefault_unreg
  - kernel/sched/core.c:preempt_notifier_dec
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/events/core.c:sw_perf_event_destroy
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg
  - net/core/sock.c:sk_clear_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:net_dec_egress_queue
  - net/core/dev.c:net_dec_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata
  - net/ipv6/udp.c:udpv6_destroy_sock
```
**Symbols:**

```
ffffffff81211430-ffffffff81211477: static_key_slow_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void static_key_slow_dec(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8121f070)
Location: kernel/jump_label.c:267
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/tracepoint.c:trace_resched_ipi_unreg
  - arch/x86/kernel/tracepoint.c:trace_pagefault_unreg
  - kernel/sched/core.c:preempt_notifier_dec
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/events/core.c:sw_perf_event_destroy
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg
  - net/core/sock.c:sk_clear_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:net_dec_egress_queue
  - net/core/dev.c:net_dec_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata
  - net/ipv6/udp.c:udpv6_destroy_sock
```
**Symbols:**

```
ffffffff8121f070-ffffffff8121f0b7: static_key_slow_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void static_key_slow_dec(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8124ae80)
Location: kernel/jump_label.c:267
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/tracepoint.c:trace_pagefault_unreg
  - kernel/sysctl.c:bpf_stats_handler
  - kernel/sched/core.c:preempt_notifier_dec
  - kernel/tracepoint.c:tracepoint_remove_func
  - kernel/bpf/syscall.c:bpf_stats_release
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/events/core.c:sw_perf_event_destroy
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg
  - net/core/sock.c:sk_clear_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:net_dec_egress_queue
  - net/core/dev.c:net_dec_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata
  - net/ipv6/udp.c:udpv6_destroy_sock
```
**Symbols:**

```
ffffffff8124ae80-ffffffff8124aeda: static_key_slow_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void static_key_slow_dec(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81255270)
Location: kernel/jump_label.c:267
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/tracepoint.c:trace_pagefault_unreg
  - kernel/sysctl.c:bpf_stats_handler
  - kernel/sched/core.c:preempt_notifier_dec
  - kernel/trace/trace.c:unregister_ftrace_export
  - kernel/trace/trace.c:unregister_ftrace_export
  - kernel/trace/trace.c:unregister_ftrace_export
  - kernel/bpf/syscall.c:bpf_stats_release
  - kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit
  - kernel/bpf/net_namespace.c:bpf_netns_link_release
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/events/core.c:sw_perf_event_destroy
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memremap.c:memunmap_pages
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg
  - net/core/sock.c:sk_clear_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:net_dec_egress_queue
  - net/core/dev.c:net_dec_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata
  - net/ipv6/udp.c:udpv6_destroy_sock
```
**Symbols:**

```
ffffffff81255270-ffffffff812552ca: static_key_slow_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void static_key_slow_dec(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81259770)
Location: kernel/jump_label.c:267
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/tracepoint.c:trace_pagefault_unreg
  - kernel/sysctl.c:bpf_stats_handler
  - kernel/sched/core.c:preempt_notifier_dec
  - kernel/trace/trace.c:unregister_ftrace_export
  - kernel/trace/trace.c:unregister_ftrace_export
  - kernel/trace/trace.c:unregister_ftrace_export
  - kernel/bpf/syscall.c:bpf_stats_release
  - kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit
  - kernel/bpf/net_namespace.c:bpf_netns_link_release
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/events/core.c:sw_perf_event_destroy
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memremap.c:memunmap_pages
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg
  - net/core/sock.c:sk_clear_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:net_dec_egress_queue
  - net/core/dev.c:net_dec_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_encap_disable
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata
  - net/ipv6/udp.c:udpv6_destroy_sock
```
**Symbols:**

```
ffffffff81259770-ffffffff812597ca: static_key_slow_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void static_key_slow_dec(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (0)
Location: kernel/jump_label.c:267
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/tracepoint.c:trace_pagefault_unreg
  - kernel/sysctl.c:bpf_stats_handler
  - kernel/sched/core.c:preempt_notifier_dec
  - kernel/trace/trace.c:unregister_ftrace_export
  - kernel/trace/trace.c:unregister_ftrace_export
  - kernel/trace/trace.c:unregister_ftrace_export
  - kernel/bpf/syscall.c:bpf_stats_release
  - kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit
  - kernel/bpf/net_namespace.c:bpf_netns_link_release
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/events/core.c:sw_perf_event_destroy
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memremap.c:memunmap_pages
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg
  - net/core/sock.c:sk_clear_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:net_dec_egress_queue
  - net/core/dev.c:net_dec_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_encap_disable
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata
  - net/ipv6/udp.c:udpv6_destroy_sock
```
**Symbols:**

```
ffffffff81cb9bef-ffffffff81cb9c03: static_key_slow_dec.cold (STB_LOCAL)
ffffffff812954a0-ffffffff81295506: static_key_slow_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void static_key_slow_dec(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (0)
Location: kernel/jump_label.c:267
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/tracepoint.c:trace_pagefault_unreg
  - kernel/sched/core.c:preempt_notifier_dec
  - kernel/trace/trace.c:unregister_ftrace_export
  - kernel/trace/trace.c:unregister_ftrace_export
  - kernel/trace/trace.c:unregister_ftrace_export
  - kernel/bpf/syscall.c:bpf_stats_handler
  - kernel/bpf/syscall.c:bpf_stats_release
  - kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit
  - kernel/bpf/net_namespace.c:bpf_netns_link_release
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/events/core.c:sw_perf_event_destroy
  - mm/hugetlb_vmemmap.c:hugetlb_optimize_vmemmap_handler
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_free
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_alloc
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memremap.c:memunmap_pages
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg
  - net/core/sock.c:sk_clear_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:net_dec_egress_queue
  - net/core/dev.c:net_dec_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/sched/cls_api.c:tc_skb_ext_tc_disable
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_encap_disable
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata
  - net/ipv6/udp.c:udpv6_destroy_sock
```
**Symbols:**

```
ffffffff81e6b1ea-ffffffff81e6b1ff: static_key_slow_dec.cold (STB_LOCAL)
ffffffff812eb280-ffffffff812eb2f5: static_key_slow_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void static_key_slow_dec(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (0)
Location: kernel/jump_label.c:295
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/tracepoint.c:trace_pagefault_unreg
  - kernel/sched/core.c:preempt_notifier_dec
  - kernel/power/process.c:thaw_processes
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_css_offline
  - kernel/trace/trace.c:unregister_ftrace_export
  - kernel/trace/trace.c:unregister_ftrace_export
  - kernel/trace/trace.c:unregister_ftrace_export
  - kernel/bpf/syscall.c:bpf_stats_handler
  - kernel/bpf/syscall.c:bpf_stats_release
  - kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit
  - kernel/bpf/net_namespace.c:bpf_netns_link_release
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/events/core.c:sw_perf_event_destroy
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_optimize
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_restore
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memremap.c:memunmap_pages
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg
  - net/core/sock.c:sk_clear_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:net_dec_egress_queue
  - net/core/dev.c:net_dec_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/sched/cls_api.c:tc_skb_ext_tc_disable
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_encap_disable
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata
```
**Symbols:**

```
ffffffff82061f68-ffffffff82061f7d: static_key_slow_dec.cold (STB_LOCAL)
ffffffff81355320-ffffffff81355395: static_key_slow_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void static_key_slow_dec(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (0)
Location: kernel/jump_label.c:295
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/tracepoint.c:trace_pagefault_unreg
  - kernel/sched/core.c:preempt_notifier_dec
  - kernel/power/process.c:thaw_processes
  - kernel/trace/trace.c:unregister_ftrace_export
  - kernel/trace/trace.c:unregister_ftrace_export
  - kernel/trace/trace.c:unregister_ftrace_export
  - kernel/bpf/syscall.c:bpf_stats_handler
  - kernel/bpf/syscall.c:bpf_stats_release
  - kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit
  - kernel/bpf/net_namespace.c:bpf_netns_link_release
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/events/core.c:sw_perf_event_destroy
  - mm/page_alloc.c:try_to_accept_memory
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_optimize
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_restore
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memremap.c:memunmap_pages
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg
  - net/core/sock.c:sk_clear_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:net_dec_egress_queue
  - net/core/dev.c:net_dec_ingress_queue
  - net/core/net-sysfs.c:netdev_rx_queue_set_rps_mask
  - net/sched/cls_api.c:tc_skb_ext_tc_disable
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_encap_disable
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata
```
**Symbols:**

```
ffffffff820e1796-ffffffff820e17ab: static_key_slow_dec.cold (STB_LOCAL)
ffffffff81386810-ffffffff81386885: static_key_slow_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void static_key_slow_dec(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (0)
Location: kernel/jump_label.c:295
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/tracepoint.c:trace_pagefault_unreg
  - kernel/sched/core.c:preempt_notifier_dec
  - kernel/power/process.c:thaw_processes
  - kernel/trace/trace.c:unregister_ftrace_export
  - kernel/trace/trace.c:unregister_ftrace_export
  - kernel/trace/trace.c:unregister_ftrace_export
  - kernel/bpf/syscall.c:bpf_stats_handler
  - kernel/bpf/syscall.c:bpf_stats_release
  - kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit
  - kernel/bpf/net_namespace.c:bpf_netns_link_release
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/events/core.c:sw_perf_event_destroy
  - mm/page_alloc.c:try_to_accept_memory
  - mm/hugetlb_vmemmap.c:__hugetlb_vmemmap_optimize_folio
  - mm/hugetlb_vmemmap.c:__hugetlb_vmemmap_restore_folio
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memremap.c:memunmap_pages
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg
  - net/core/sock.c:sk_clear_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:tcx_dec
  - net/core/dev.c:net_dec_egress_queue
  - net/core/dev.c:net_dec_ingress_queue
  - net/core/net-sysfs.c:netdev_rx_queue_set_rps_mask
  - net/sched/cls_api.c:tc_skb_ext_tc_disable
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_encap_disable
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata
```
**Symbols:**

```
ffffffff821be1f9-ffffffff821be20e: static_key_slow_dec.cold (STB_LOCAL)
ffffffff813afcd0-ffffffff813afd45: static_key_slow_dec (STB_GLOBAL)
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
void static_key_slow_dec(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffff8000102ab410)
Location: kernel/jump_label.c:267
Inline: False
Direct callers:
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_free
  - kernel/sched/core.c:preempt_notifier_dec
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/events/core.c:sw_perf_event_destroy
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg
  - net/core/sock.c:sk_clear_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:net_dec_egress_queue
  - net/core/dev.c:net_dec_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata
  - net/ipv6/udp.c:udpv6_destroy_sock
```
**Symbols:**

```
ffff8000102ab410-ffff8000102ab48c: static_key_slow_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (c03a9690)
Location: include/linux/jump_label.h:282
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
```
```
In kernel/cgroup/cpuset.c (c0423f88)
Location: include/linux/jump_label.h:282
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_offline
```
```
In kernel/tracepoint.c (c044d360)
Location: include/linux/jump_label.h:282
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
```
```
In kernel/bpf/cgroup.c (c04bf030)
Location: include/linux/jump_label.h:282
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (c04c32f8)
Location: include/linux/jump_label.h:282
Inline: True
Inline callers:
  - kernel/events/core.c:sw_perf_event_destroy
```
```
In mm/memcontrol.c (c0556560)
Location: include/linux/jump_label.h:282
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
```
```
In drivers/i2c/i2c-core-base.c (c0b92a40)
Location: include/linux/jump_label.h:282
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg
```
```
In net/core/sock.c (c0cca868)
Location: include/linux/jump_label.h:282
Inline: True
Inline callers:
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/sysctl_net_core.c (c0ce109c)
Location: include/linux/jump_label.h:282
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/core/dev.c (c0ceaa30)
Location: include/linux/jump_label.h:282
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:net_disable_timestamp
  - net/core/dev.c:net_dec_egress_queue
  - net/core/dev.c:net_dec_ingress_queue
```
```
In net/core/net-sysfs.c (c0d23844)
Location: include/linux/jump_label.h:282
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/ipv4/tcp_input.c (c0d86c50)
Location: include/linux/jump_label.h:282
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:clean_acked_data_disable
```
```
In net/ipv4/udp.c (c0da95a8)
Location: include/linux/jump_label.h:282
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (c0dce018)
Location: include/linux/jump_label.h:282
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata
```
```
In net/ipv6/udp.c (c0e2882c)
Location: include/linux/jump_label.h:282
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_destroy_sock
```
```
In net/ipv6/ip6_flowlabel.c (c0e41e1c)
Location: include/linux/jump_label.h:282
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_free
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void static_key_slow_dec(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (c00000000035f0a0)
Location: kernel/jump_label.c:267
Inline: False
Direct callers:
  - arch/powerpc/platforms/powernv/opal-call.c:opal_tracepoint_unregfunc
  - arch/powerpc/platforms/pseries/lpar.c:hcall_tracepoint_unregfunc
  - kernel/sched/core.c:preempt_notifier_dec
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/events/core.c:sw_perf_event_destroy
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg
  - net/core/sock.c:sk_clear_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:net_dec_egress_queue
  - net/core/dev.c:net_dec_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata
  - net/ipv6/udp.c:udpv6_destroy_sock
```
**Symbols:**

```
c00000000035f0a0-c00000000035f15c: static_key_slow_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffe000101d40)
Location: include/linux/jump_label.h:282
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
```
```
In kernel/cgroup/cpuset.c (ffffffe00015911e)
Location: include/linux/jump_label.h:282
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_offline
```
```
In kernel/tracepoint.c (ffffffe00016f55e)
Location: include/linux/jump_label.h:282
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
```
```
In kernel/bpf/cgroup.c (ffffffe0001c2760)
Location: include/linux/jump_label.h:282
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffffffe0001c46e8)
Location: include/linux/jump_label.h:282
Inline: True
Inline callers:
  - kernel/events/core.c:sw_perf_event_destroy
```
```
In mm/memcontrol.c (ffffffe000242f7a)
Location: include/linux/jump_label.h:282
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
```
```
In drivers/i2c/i2c-core-base.c (ffffffe0006b93cc)
Location: include/linux/jump_label.h:282
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg
```
```
In net/core/sock.c (ffffffe00073f2d0)
Location: include/linux/jump_label.h:282
Inline: True
Inline callers:
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/sysctl_net_core.c (ffffffe000752284)
Location: include/linux/jump_label.h:282
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/core/dev.c (ffffffe00075a8e0)
Location: include/linux/jump_label.h:282
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:net_disable_timestamp
  - net/core/dev.c:net_dec_egress_queue
  - net/core/dev.c:net_dec_ingress_queue
```
```
In net/core/net-sysfs.c (ffffffe00078911e)
Location: include/linux/jump_label.h:282
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/ipv4/tcp_input.c (ffffffe0007db76a)
Location: include/linux/jump_label.h:282
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:clean_acked_data_disable
```
```
In net/ipv4/udp.c (ffffffe0007f8676)
Location: include/linux/jump_label.h:282
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffe000817c8e)
Location: include/linux/jump_label.h:282
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata
```
```
In net/ipv6/udp.c (ffffffe000865c8e)
Location: include/linux/jump_label.h:282
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_destroy_sock
```
```
In net/ipv6/ip6_flowlabel.c (ffffffe00087b11c)
Location: include/linux/jump_label.h:282
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_free
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
void static_key_slow_dec(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812176c0)
Location: kernel/jump_label.c:267
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/tracepoint.c:trace_resched_ipi_unreg
  - arch/x86/kernel/tracepoint.c:trace_pagefault_unreg
  - kernel/sched/core.c:preempt_notifier_dec
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/events/core.c:sw_perf_event_destroy
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - net/core/sock.c:sk_clear_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:net_dec_egress_queue
  - net/core/dev.c:net_dec_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata
  - net/ipv6/udp.c:udpv6_destroy_sock
```
**Symbols:**

```
ffffffff812176c0-ffffffff81217707: static_key_slow_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void static_key_slow_dec(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8120a420)
Location: kernel/jump_label.c:267
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/tracepoint.c:trace_resched_ipi_unreg
  - arch/x86/kernel/tracepoint.c:trace_pagefault_unreg
  - kernel/sched/core.c:preempt_notifier_dec
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/events/core.c:sw_perf_event_destroy
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - net/core/sock.c:sk_clear_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:net_dec_egress_queue
  - net/core/dev.c:net_dec_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata
  - net/ipv6/udp.c:udpv6_destroy_sock
```
**Symbols:**

```
ffffffff8120a420-ffffffff8120a467: static_key_slow_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void static_key_slow_dec(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81215460)
Location: kernel/jump_label.c:267
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/tracepoint.c:trace_resched_ipi_unreg
  - arch/x86/kernel/tracepoint.c:trace_pagefault_unreg
  - kernel/sched/core.c:preempt_notifier_dec
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/events/core.c:sw_perf_event_destroy
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg
  - net/core/sock.c:sk_clear_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:net_dec_egress_queue
  - net/core/dev.c:net_dec_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata
  - net/ipv6/udp.c:udpv6_destroy_sock
```
**Symbols:**

```
ffffffff81215460-ffffffff812154a7: static_key_slow_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void static_key_slow_dec(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81224450)
Location: kernel/jump_label.c:267
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/tracepoint.c:trace_resched_ipi_unreg
  - arch/x86/kernel/tracepoint.c:trace_pagefault_unreg
  - kernel/sched/core.c:preempt_notifier_dec
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/events/core.c:sw_perf_event_destroy
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg
  - net/core/sock.c:sk_clear_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:net_dec_egress_queue
  - net/core/dev.c:net_dec_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata
  - net/ipv6/udp.c:udpv6_destroy_sock
```
**Symbols:**

```
ffffffff81224450-ffffffff81224497: static_key_slow_dec (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
