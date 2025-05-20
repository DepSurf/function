# Function: <code>static_key_slow_inc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void static_key_slow_inc(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8118aeb0)
Location: kernel/jump_label.c:59
Inline: True
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/tsc.c:tsc_init
  - kernel/sched/core.c:preempt_notifier_inc
  - kernel/sched/core.c:sched_feat_write
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/clock.c:__set_sched_clock_stable
  - kernel/sched/fair.c:cfs_bandwidth_usage_inc
  - kernel/cgroup.c:rebind_subsystems
  - kernel/cpuset.c:cpuset_css_online
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/events/core.c:perf_swevent_init
  - mm/memcontrol.c:memcg_activate_kmem
  - drivers/i2c/i2c-core.c:i2c_transfer_trace_reg
  - net/core/sock.c:sk_set_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:net_inc_ingress_queue
  - net/core/dev.c:net_enable_timestamp
  - net/core/net-sysfs.c:store_rps_map
  - net/netfilter/core.c:nf_register_net_hook
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata
  - net/ipv4/tcp_memcontrol.c:tcp_cgroup_write
  - net/ipv6/udp.c:udpv6_encap_enable
```
**Symbols:**

```
ffffffff8118aeb0-ffffffff8118af46: static_key_slow_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void static_key_slow_inc(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8119d520)
Location: kernel/jump_label.c:103
Inline: True
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - kernel/sched/core.c:preempt_notifier_inc
  - kernel/sched/clock.c:__set_sched_clock_stable
  - kernel/sched/fair.c:cfs_bandwidth_usage_inc
  - kernel/cpuset.c:cpuset_css_online
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/events/core.c:perf_swevent_init
  - kernel/jump_label.c:static_key_enable
  - mm/frontswap.c:frontswap_register_ops
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_write
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/i2c/i2c-core.c:i2c_transfer_trace_reg
  - net/core/sock.c:sk_set_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:net_enable_timestamp
  - net/core/dev.c:net_inc_egress_queue
  - net/core/dev.c:net_inc_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/netfilter/core.c:nf_register_net_hook
  - net/ipv4/udp.c:udp_encap_enable
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata
  - net/ipv6/udp.c:udpv6_encap_enable
```
**Symbols:**

```
ffffffff8119d520-ffffffff8119d5bd: static_key_slow_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void static_key_slow_inc(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811acf40)
Location: kernel/jump_label.c:103
Inline: True
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/quirks.c:quirk_intel_purley_xeon_ras_cap
  - arch/x86/kernel/quirks.c:quirk_intel_brickland_xeon_ras_cap
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init
  - kernel/sched/core.c:preempt_notifier_inc
  - kernel/sched/clock.c:__set_sched_clock_stable
  - kernel/sched/fair.c:cfs_bandwidth_usage_inc
  - kernel/cpuset.c:cpuset_css_online
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/bpf/cgroup.c:__cgroup_bpf_update
  - kernel/events/core.c:perf_swevent_init
  - kernel/jump_label.c:static_key_enable
  - mm/frontswap.c:frontswap_register_ops
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_write
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/i2c/i2c-core.c:i2c_transfer_trace_reg
  - net/core/sock.c:sk_set_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:net_inc_egress_queue
  - net/core/dev.c:net_inc_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/netfilter/core.c:nf_register_net_hook
  - net/ipv4/udp.c:udp_encap_enable
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata
  - net/ipv6/udp.c:udpv6_encap_enable
```
**Symbols:**

```
ffffffff811acf40-ffffffff811acfdd: static_key_slow_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void static_key_slow_inc(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811b43f0)
Location: kernel/jump_label.c:104
Inline: True
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/quirks.c:quirk_intel_purley_xeon_ras_cap
  - arch/x86/kernel/quirks.c:quirk_intel_brickland_xeon_ras_cap
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init
  - kernel/sched/core.c:preempt_notifier_inc
  - kernel/sched/fair.c:cfs_bandwidth_usage_inc
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/bpf/cgroup.c:__cgroup_bpf_update
  - kernel/events/core.c:perf_swevent_init
  - kernel/jump_label.c:static_key_enable
  - mm/frontswap.c:frontswap_register_ops
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_write
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg
  - net/core/sock.c:sk_set_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:net_inc_egress_queue
  - net/core/dev.c:net_inc_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/netfilter/core.c:nf_register_net_hook
  - net/ipv4/udp.c:udp_encap_enable
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata
  - net/ipv6/udp.c:udpv6_encap_enable
```
**Symbols:**

```
ffffffff811b43f0-ffffffff811b448d: static_key_slow_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void static_key_slow_inc(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811c8810)
Location: kernel/jump_label.c:121
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/quirks.c:quirk_intel_purley_xeon_ras_cap
  - arch/x86/kernel/quirks.c:quirk_intel_brickland_xeon_ras_cap
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init
  - arch/x86/kernel/tracepoint.c:trace_resched_ipi_reg
  - arch/x86/kernel/tracepoint.c:trace_pagefault_reg
  - kernel/sched/core.c:preempt_notifier_inc
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/events/core.c:perf_swevent_init
  - mm/frontswap.c:frontswap_register_ops
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_write
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg
  - net/core/sock.c:sk_set_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:net_inc_egress_queue
  - net/core/dev.c:net_inc_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/netfilter/core.c:nf_register_net_hook
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata
```
**Symbols:**

```
ffffffff811c8810-ffffffff811c8832: static_key_slow_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void static_key_slow_inc(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811e8d70)
Location: kernel/jump_label.c:122
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/quirks.c:quirk_intel_purley_xeon_ras_cap
  - arch/x86/kernel/quirks.c:quirk_intel_brickland_xeon_ras_cap
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init
  - arch/x86/kernel/kvm.c:activate_jump_labels
  - arch/x86/kernel/kvm.c:activate_jump_labels
  - arch/x86/kernel/tracepoint.c:trace_resched_ipi_reg
  - arch/x86/kernel/tracepoint.c:trace_pagefault_reg
  - kernel/sched/core.c:preempt_notifier_inc
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/events/core.c:perf_swevent_init
  - mm/frontswap.c:frontswap_register_ops
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_write
  - lib/crc-t10dif.c:crc_t10dif_mod_init
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg
  - net/core/sock.c:sk_set_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:net_inc_egress_queue
  - net/core/dev.c:net_inc_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/netfilter/core.c:__nf_register_net_hook
  - net/ipv4/tcp_input.c:clean_acked_data_enable
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata
```
**Symbols:**

```
ffffffff811e8d70-ffffffff811e8d92: static_key_slow_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void static_key_slow_inc(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811f9a70)
Location: kernel/jump_label.c:141
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/quirks.c:quirk_intel_purley_xeon_ras_cap
  - arch/x86/kernel/quirks.c:quirk_intel_brickland_xeon_ras_cap
  - arch/x86/kernel/cpu/mce/core.c:mcheck_late_init
  - arch/x86/kernel/kvm.c:activate_jump_labels
  - arch/x86/kernel/kvm.c:activate_jump_labels
  - arch/x86/kernel/tracepoint.c:trace_resched_ipi_reg
  - arch/x86/kernel/tracepoint.c:trace_pagefault_reg
  - kernel/sched/core.c:preempt_notifier_inc
  - kernel/sched/clock.c:sched_clock_init_late
  - kernel/sched/clock.c:sched_clock_init
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/events/core.c:perf_swevent_init
  - mm/frontswap.c:frontswap_register_ops
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_write
  - lib/crc-t10dif.c:crc_t10dif_mod_init
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg
  - net/core/sock.c:sk_set_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:net_inc_egress_queue
  - net/core/dev.c:net_inc_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/netfilter/core.c:__nf_register_net_hook
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
  - net/ipv4/tcp_input.c:clean_acked_data_enable
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata
  - net/ipv6/udp.c:udpv6_encap_enable
```
**Symbols:**

```
ffffffff811f9a70-ffffffff811f9a92: static_key_slow_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void static_key_slow_inc(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81211990)
Location: kernel/jump_label.c:156
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/quirks.c:quirk_intel_purley_xeon_ras_cap
  - arch/x86/kernel/quirks.c:quirk_intel_brickland_xeon_ras_cap
  - arch/x86/kernel/cpu/mce/core.c:mcheck_late_init
  - arch/x86/kernel/kvm.c:activate_jump_labels
  - arch/x86/kernel/kvm.c:activate_jump_labels
  - arch/x86/kernel/tracepoint.c:trace_resched_ipi_reg
  - arch/x86/kernel/tracepoint.c:trace_pagefault_reg
  - kernel/sched/core.c:preempt_notifier_inc
  - kernel/sched/clock.c:sched_clock_init_late
  - kernel/sched/clock.c:sched_clock_init
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/events/core.c:perf_swevent_init
  - mm/frontswap.c:frontswap_register_ops
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_write
  - lib/crc-t10dif.c:crc_t10dif_mod_init
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg
  - net/core/sock.c:sk_set_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:net_inc_egress_queue
  - net/core/dev.c:net_inc_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/netfilter/core.c:__nf_register_net_hook
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
  - net/ipv4/tcp_input.c:clean_acked_data_enable
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata
  - net/ipv6/udp.c:udpv6_encap_enable
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff81211990-ffffffff812119b4: static_key_slow_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void static_key_slow_inc(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8121f190)
Location: kernel/jump_label.c:156
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/quirks.c:quirk_intel_purley_xeon_ras_cap
  - arch/x86/kernel/quirks.c:quirk_intel_brickland_xeon_ras_cap
  - arch/x86/kernel/cpu/mce/core.c:mcheck_late_init
  - arch/x86/kernel/kvm.c:activate_jump_labels
  - arch/x86/kernel/kvm.c:activate_jump_labels
  - arch/x86/kernel/tracepoint.c:trace_resched_ipi_reg
  - arch/x86/kernel/tracepoint.c:trace_pagefault_reg
  - kernel/sched/core.c:preempt_notifier_inc
  - kernel/sched/clock.c:sched_clock_init_late
  - kernel/sched/clock.c:sched_clock_init
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/events/core.c:perf_swevent_init
  - mm/frontswap.c:frontswap_register_ops
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_write
  - lib/crc-t10dif.c:crc_t10dif_mod_init
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg
  - net/core/sock.c:sk_set_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:net_inc_egress_queue
  - net/core/dev.c:net_inc_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/netfilter/core.c:__nf_register_net_hook
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
  - net/ipv4/tcp_input.c:clean_acked_data_enable
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata
  - net/ipv6/udp.c:udpv6_encap_enable
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff8121f190-ffffffff8121f1b4: static_key_slow_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void static_key_slow_inc(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8124b450)
Location: kernel/jump_label.c:156
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/quirks.c:quirk_intel_purley_xeon_ras_cap
  - arch/x86/kernel/quirks.c:quirk_intel_brickland_xeon_ras_cap
  - arch/x86/kernel/cpu/mce/core.c:mcheck_late_init
  - arch/x86/kernel/cpu/vmware.c:activate_jump_labels
  - arch/x86/kernel/cpu/vmware.c:activate_jump_labels
  - arch/x86/kernel/kvm.c:activate_jump_labels
  - arch/x86/kernel/kvm.c:activate_jump_labels
  - arch/x86/kernel/tracepoint.c:trace_pagefault_reg
  - kernel/sysctl.c:bpf_stats_handler
  - kernel/sched/core.c:preempt_notifier_inc
  - kernel/sched/clock.c:sched_clock_init_late
  - kernel/sched/clock.c:sched_clock_init
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/bpf/syscall.c:bpf_enable_stats
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/events/core.c:perf_swevent_init
  - mm/frontswap.c:frontswap_register_ops
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_write
  - lib/crc-t10dif.c:crc_t10dif_mod_init
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg
  - net/core/sock.c:sk_set_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:net_inc_egress_queue
  - net/core/dev.c:net_inc_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/netfilter/core.c:__nf_register_net_hook
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
  - net/ipv4/tcp_input.c:clean_acked_data_enable
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata
  - net/ipv6/udp.c:udpv6_encap_enable
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff8124b450-ffffffff8124b476: static_key_slow_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void static_key_slow_inc(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812558b0)
Location: kernel/jump_label.c:156
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/cpu/vmware.c:activate_jump_labels
  - arch/x86/kernel/cpu/vmware.c:activate_jump_labels
  - arch/x86/kernel/kvm.c:activate_jump_labels
  - arch/x86/kernel/kvm.c:activate_jump_labels
  - arch/x86/kernel/tracepoint.c:trace_pagefault_reg
  - kernel/sysctl.c:bpf_stats_handler
  - kernel/sched/core.c:preempt_notifier_inc
  - kernel/sched/clock.c:sched_clock_init_late
  - kernel/sched/clock.c:sched_clock_init
  - kernel/trace/trace.c:register_ftrace_export
  - kernel/trace/trace.c:register_ftrace_export
  - kernel/trace/trace.c:register_ftrace_export
  - kernel/bpf/syscall.c:bpf_enable_stats
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/events/core.c:perf_swevent_init
  - mm/frontswap.c:frontswap_register_ops
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memremap.c:memremap_pages
  - arch/x86/lib/copy_mc.c:enable_copy_mc_fragile
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg
  - net/core/sock.c:sk_set_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:net_inc_egress_queue
  - net/core/dev.c:net_inc_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/netfilter/core.c:__nf_register_net_hook
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
  - net/ipv4/tcp_input.c:clean_acked_data_enable
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata
  - net/ipv6/udp.c:udpv6_encap_enable
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff812558b0-ffffffff812558d6: static_key_slow_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void static_key_slow_inc(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81259d90)
Location: kernel/jump_label.c:156
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/cpu/vmware.c:activate_jump_labels
  - arch/x86/kernel/cpu/vmware.c:activate_jump_labels
  - arch/x86/kernel/kvm.c:activate_jump_labels
  - arch/x86/kernel/kvm.c:activate_jump_labels
  - arch/x86/kernel/tracepoint.c:trace_pagefault_reg
  - kernel/sysctl.c:bpf_stats_handler
  - kernel/sched/core.c:preempt_notifier_inc
  - kernel/sched/clock.c:sched_clock_init_late
  - kernel/sched/clock.c:sched_clock_init
  - kernel/trace/trace.c:register_ftrace_export
  - kernel/trace/trace.c:register_ftrace_export
  - kernel/trace/trace.c:register_ftrace_export
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/events/core.c:perf_swevent_init
  - mm/frontswap.c:frontswap_register_ops
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memremap.c:memremap_pages
  - arch/x86/lib/copy_mc.c:enable_copy_mc_fragile
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg
  - net/core/sock.c:sk_set_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:net_inc_egress_queue
  - net/core/dev.c:net_inc_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/netfilter/core.c:__nf_register_net_hook
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
  - net/ipv4/tcp_input.c:clean_acked_data_enable
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata
  - net/ipv6/udp.c:udpv6_encap_enable
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff81259d90-ffffffff81259db6: static_key_slow_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void static_key_slow_inc(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81295b10)
Location: kernel/jump_label.c:156
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/cpu/vmware.c:activate_jump_labels
  - arch/x86/kernel/cpu/vmware.c:activate_jump_labels
  - arch/x86/kernel/kvm.c:activate_jump_labels
  - arch/x86/kernel/kvm.c:activate_jump_labels
  - arch/x86/kernel/tracepoint.c:trace_pagefault_reg
  - kernel/sysctl.c:bpf_stats_handler
  - kernel/sched/core.c:preempt_notifier_inc
  - kernel/sched/clock.c:sched_clock_init_late
  - kernel/sched/clock.c:sched_clock_init
  - kernel/trace/trace.c:register_ftrace_export
  - kernel/trace/trace.c:register_ftrace_export
  - kernel/trace/trace.c:register_ftrace_export
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/events/core.c:perf_swevent_init
  - mm/frontswap.c:frontswap_register_ops
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memremap.c:memremap_pages
  - arch/x86/lib/copy_mc.c:enable_copy_mc_fragile
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg
  - net/core/sock.c:sk_set_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:net_inc_egress_queue
  - net/core/dev.c:net_inc_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/netfilter/core.c:__nf_register_net_hook
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
  - net/ipv4/tcp_input.c:clean_acked_data_enable
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata
  - net/ipv6/udp.c:udpv6_encap_enable
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff81295b10-ffffffff81295b36: static_key_slow_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void static_key_slow_inc(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812eb810)
Location: kernel/jump_label.c:156
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/cpu/vmware.c:activate_jump_labels
  - arch/x86/kernel/cpu/vmware.c:activate_jump_labels
  - arch/x86/kernel/kvm.c:activate_jump_labels
  - arch/x86/kernel/kvm.c:activate_jump_labels
  - arch/x86/kernel/tracepoint.c:trace_pagefault_reg
  - kernel/sched/core.c:preempt_notifier_inc
  - kernel/sched/build_utility.c:sched_clock_init_late
  - kernel/sched/build_utility.c:sched_clock_init
  - kernel/trace/trace.c:register_ftrace_export
  - kernel/trace/trace.c:register_ftrace_export
  - kernel/trace/trace.c:register_ftrace_export
  - kernel/bpf/syscall.c:bpf_stats_handler
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/events/core.c:perf_swevent_init
  - mm/frontswap.c:frontswap_register_ops
  - mm/hugetlb_vmemmap.c:hugetlb_optimize_vmemmap_handler
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_free
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memremap.c:memremap_pages
  - arch/x86/lib/copy_mc.c:enable_copy_mc_fragile
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg
  - net/core/sock.c:sk_set_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:net_inc_egress_queue
  - net/core/dev.c:net_inc_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/sched/cls_api.c:tc_skb_ext_tc_enable
  - net/netfilter/core.c:__nf_register_net_hook
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
  - net/ipv4/tcp_input.c:clean_acked_data_enable
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata
  - net/ipv6/udp.c:udpv6_encap_enable
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff812eb810-ffffffff812eb83b: static_key_slow_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool static_key_slow_inc(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81355910)
Location: kernel/jump_label.c:181
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/cpu/vmware.c:activate_jump_labels
  - arch/x86/kernel/cpu/vmware.c:activate_jump_labels
  - arch/x86/kernel/kvm.c:activate_jump_labels
  - arch/x86/kernel/kvm.c:activate_jump_labels
  - arch/x86/kernel/tracepoint.c:trace_pagefault_reg
  - kernel/sched/core.c:preempt_notifier_inc
  - kernel/sched/build_utility.c:sched_clock_init_late
  - kernel/sched/build_utility.c:sched_clock_init
  - kernel/power/process.c:freeze_processes
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_css_online
  - kernel/trace/trace.c:register_ftrace_export
  - kernel/trace/trace.c:register_ftrace_export
  - kernel/trace/trace.c:register_ftrace_export
  - kernel/bpf/syscall.c:bpf_stats_handler
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/events/core.c:perf_swevent_init
  - mm/frontswap.c:frontswap_register_ops
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_optimize
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memremap.c:memremap_pages
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg
  - net/core/sock.c:sk_set_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:net_inc_egress_queue
  - net/core/dev.c:net_inc_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/sched/cls_api.c:tc_skb_ext_tc_enable
  - net/netfilter/core.c:__nf_register_net_hook
  - net/ipv4/tcp_input.c:clean_acked_data_enable
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_add
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata
  - net/ipv6/udp.c:udpv6_encap_enable
  - net/ipv6/ip6_flowlabel.c:fl_create
  - arch/x86/lib/copy_mc.c:enable_copy_mc_fragile
```
**Symbols:**

```
ffffffff81355910-ffffffff8135593f: static_key_slow_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool static_key_slow_inc(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81386f90)
Location: kernel/jump_label.c:181
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/cpu/vmware.c:activate_jump_labels
  - arch/x86/kernel/cpu/vmware.c:activate_jump_labels
  - arch/x86/kernel/kvm.c:activate_jump_labels
  - arch/x86/kernel/kvm.c:activate_jump_labels
  - arch/x86/kernel/tracepoint.c:trace_pagefault_reg
  - kernel/sched/core.c:preempt_notifier_inc
  - kernel/sched/build_utility.c:sched_clock_init_late
  - kernel/sched/build_utility.c:sched_clock_init
  - kernel/power/process.c:freeze_processes
  - kernel/trace/trace.c:register_ftrace_export
  - kernel/trace/trace.c:register_ftrace_export
  - kernel/trace/trace.c:register_ftrace_export
  - kernel/bpf/syscall.c:bpf_stats_handler
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/events/core.c:perf_swevent_init
  - mm/page_alloc.c:__free_pages_core
  - mm/frontswap.c:frontswap_register_ops
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_optimize
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memremap.c:memremap_pages
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg
  - net/core/sock.c:sk_set_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:net_inc_egress_queue
  - net/core/dev.c:net_inc_ingress_queue
  - net/core/net-sysfs.c:netdev_rx_queue_set_rps_mask
  - net/sched/cls_api.c:tc_skb_ext_tc_enable
  - net/netfilter/core.c:__nf_register_net_hook
  - net/ipv4/tcp_input.c:clean_acked_data_enable
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_add
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata
  - net/ipv6/udp.c:udpv6_encap_enable
  - net/ipv6/ip6_flowlabel.c:fl_create
  - arch/x86/lib/copy_mc.c:enable_copy_mc_fragile
```
**Symbols:**

```
ffffffff81386f90-ffffffff81386fbf: static_key_slow_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool static_key_slow_inc(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff813b04a0)
Location: kernel/jump_label.c:181
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/cpu/vmware.c:activate_jump_labels
  - arch/x86/kernel/cpu/vmware.c:activate_jump_labels
  - arch/x86/kernel/kvm.c:activate_jump_labels
  - arch/x86/kernel/kvm.c:activate_jump_labels
  - arch/x86/kernel/tracepoint.c:trace_pagefault_reg
  - kernel/sched/core.c:preempt_notifier_inc
  - kernel/sched/build_utility.c:sched_clock_init_late
  - kernel/sched/build_utility.c:sched_clock_init
  - kernel/power/process.c:freeze_processes
  - kernel/trace/trace.c:register_ftrace_export
  - kernel/trace/trace.c:register_ftrace_export
  - kernel/trace/trace.c:register_ftrace_export
  - kernel/bpf/syscall.c:bpf_stats_handler
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/events/core.c:perf_swevent_init
  - kernel/context_tracking.c:ct_cpu_track_user
  - mm/page_alloc.c:__free_pages_core
  - mm/hugetlb_vmemmap.c:__hugetlb_vmemmap_optimize_folio
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memremap.c:memremap_pages
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg
  - net/core/sock.c:sk_set_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:tcx_inc
  - net/core/dev.c:net_inc_egress_queue
  - net/core/dev.c:net_inc_ingress_queue
  - net/core/net-sysfs.c:netdev_rx_queue_set_rps_mask
  - net/sched/cls_api.c:tc_skb_ext_tc_enable
  - net/netfilter/core.c:__nf_register_net_hook
  - net/ipv4/tcp_input.c:clean_acked_data_enable
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_add
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata
  - net/ipv4/tcp_ao.c:tcp_ao_add_cmd
  - net/ipv6/udp.c:udpv6_encap_enable
  - net/ipv6/ip6_flowlabel.c:fl_create
  - arch/x86/lib/copy_mc.c:enable_copy_mc_fragile
```
**Symbols:**

```
ffffffff813b04a0-ffffffff813b04cf: static_key_slow_inc (STB_GLOBAL)
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
void static_key_slow_inc(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffff8000102ab5d8)
Location: kernel/jump_label.c:156
Inline: False
Direct callers:
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
  - kernel/sched/core.c:preempt_notifier_inc
  - kernel/sched/clock.c:sched_clock_init
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/events/core.c:perf_swevent_init
  - mm/frontswap.c:frontswap_register_ops
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_write
  - lib/crc-t10dif.c:crc_t10dif_mod_init
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg
  - net/core/sock.c:sk_set_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:net_inc_egress_queue
  - net/core/dev.c:net_inc_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/netfilter/core.c:__nf_register_net_hook
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
  - net/ipv4/tcp_input.c:clean_acked_data_enable
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata
  - net/ipv6/udp.c:udpv6_encap_enable
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffff8000102ab5d8-ffff8000102ab60c: static_key_slow_inc (STB_GLOBAL)
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
In kernel/sched/clock.c (c151f0dc)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_init
```
```
In kernel/sched/topology.c (c03a90a0)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/cgroup/cpuset.c (c0423294)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
```
```
In kernel/tracepoint.c (c044d63c)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_register_prio
```
```
In kernel/bpf/cgroup.c (c04becb4)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
```
In kernel/events/core.c (c04c3518)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_init
```
```
In mm/frontswap.c (c0540e60)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/memcontrol.c (c0e98eb0)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_write
```
```
In lib/crc-t10dif.c (c1548f94)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_mod_init
```
```
In drivers/i2c/i2c-core-base.c (c0b92acc)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg
```
```
In net/core/sock.c (c0cc9804)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - net/core/sock.c:sk_set_memalloc
```
```
In net/core/sysctl_net_core.c (c0ce1198)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/core/dev.c (c0ceab2c)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:net_enable_timestamp
  - net/core/dev.c:net_inc_egress_queue
  - net/core/dev.c:net_inc_ingress_queue
```
```
In net/core/net-sysfs.c (c0d23810)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/ipv4/tcp.c (c0d7e85c)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
```
```
In net/ipv4/tcp_input.c (c0d86cfc)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:clean_acked_data_enable
```
```
In net/ipv4/udp.c (c0daa100)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
```
```
In net/ipv4/ip_tunnel_core.c (c0dce0a0)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata
```
```
In net/ipv6/udp.c (c0e288a4)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_encap_enable
```
```
In net/ipv6/ip6_flowlabel.c (c0e422e8)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void static_key_slow_inc(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (c00000000035f750)
Location: kernel/jump_label.c:156
Inline: False
Direct callers:
  - arch/powerpc/platforms/powernv/opal-call.c:opal_tracepoint_regfunc
  - arch/powerpc/platforms/pseries/lpar.c:hcall_tracepoint_regfunc
  - kernel/sched/core.c:preempt_notifier_inc
  - kernel/sched/clock.c:sched_clock_init
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/events/core.c:perf_swevent_init
  - mm/frontswap.c:frontswap_register_ops
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_write
  - lib/crc-t10dif.c:crc_t10dif_mod_init
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg
  - net/core/sock.c:sk_set_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:net_inc_egress_queue
  - net/core/dev.c:net_inc_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/netfilter/core.c:__nf_register_net_hook
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
  - net/ipv4/tcp_input.c:clean_acked_data_enable
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata
  - net/ipv6/udp.c:udpv6_encap_enable
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
c00000000035f750-c00000000035f798: static_key_slow_inc (STB_GLOBAL)
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
In kernel/sched/clock.c (ffffffe000006e02)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_init
```
```
In kernel/sched/topology.c (ffffffe000101884)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/cgroup/cpuset.c (ffffffe0001598fa)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
```
```
In kernel/tracepoint.c (ffffffe00016f800)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_register_prio
```
```
In kernel/bpf/cgroup.c (ffffffe0001c24fe)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
```
In kernel/events/core.c (ffffffe0001c7e6a)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_init
```
```
In mm/frontswap.c (ffffffe000229a58)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/memcontrol.c (ffffffe0008c499e)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_write
```
```
In lib/crc-t10dif.c (ffffffe00002a2c2)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_mod_init
```
```
In drivers/i2c/i2c-core-base.c (ffffffe0006b9436)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg
```
```
In net/core/sock.c (ffffffe00073e556)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - net/core/sock.c:sk_set_memalloc
```
```
In net/core/sysctl_net_core.c (ffffffe000752368)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/core/dev.c (ffffffe00075a992)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:net_enable_timestamp
  - net/core/dev.c:net_inc_egress_queue
  - net/core/dev.c:net_inc_ingress_queue
```
```
In net/core/net-sysfs.c (ffffffe000789104)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/ipv4/tcp.c (ffffffe0007d49f6)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
```
```
In net/ipv4/tcp_input.c (ffffffe0007db7ce)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:clean_acked_data_enable
```
```
In net/ipv4/udp.c (ffffffe0007f8dba)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
```
```
In net/ipv4/ip_tunnel_core.c (ffffffe000817cf8)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata
```
```
In net/ipv6/udp.c (ffffffe000865cd6)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_encap_enable
```
```
In net/ipv6/ip6_flowlabel.c (ffffffe00087b3ee)
Location: include/linux/jump_label.h:276
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
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
void static_key_slow_inc(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812177e0)
Location: kernel/jump_label.c:156
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/quirks.c:quirk_intel_purley_xeon_ras_cap
  - arch/x86/kernel/quirks.c:quirk_intel_brickland_xeon_ras_cap
  - arch/x86/kernel/cpu/mce/core.c:mcheck_late_init
  - arch/x86/kernel/kvm.c:activate_jump_labels
  - arch/x86/kernel/kvm.c:activate_jump_labels
  - arch/x86/kernel/tracepoint.c:trace_resched_ipi_reg
  - arch/x86/kernel/tracepoint.c:trace_pagefault_reg
  - kernel/sched/core.c:preempt_notifier_inc
  - kernel/sched/clock.c:sched_clock_init_late
  - kernel/sched/clock.c:sched_clock_init
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/events/core.c:perf_swevent_init
  - mm/frontswap.c:frontswap_register_ops
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_write
  - lib/crc-t10dif.c:crc_t10dif_mod_init
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/xen/time.c:xen_time_setup_guest
  - net/core/sock.c:sk_set_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:net_inc_egress_queue
  - net/core/dev.c:net_inc_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/netfilter/core.c:__nf_register_net_hook
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
  - net/ipv4/tcp_input.c:clean_acked_data_enable
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata
  - net/ipv6/udp.c:udpv6_encap_enable
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff812177e0-ffffffff81217804: static_key_slow_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void static_key_slow_inc(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8120a540)
Location: kernel/jump_label.c:156
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/quirks.c:quirk_intel_purley_xeon_ras_cap
  - arch/x86/kernel/quirks.c:quirk_intel_brickland_xeon_ras_cap
  - arch/x86/kernel/cpu/mce/core.c:mcheck_late_init
  - arch/x86/kernel/kvm.c:activate_jump_labels
  - arch/x86/kernel/kvm.c:activate_jump_labels
  - arch/x86/kernel/tracepoint.c:trace_resched_ipi_reg
  - arch/x86/kernel/tracepoint.c:trace_pagefault_reg
  - kernel/sched/core.c:preempt_notifier_inc
  - kernel/sched/clock.c:sched_clock_init_late
  - kernel/sched/clock.c:sched_clock_init
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/events/core.c:perf_swevent_init
  - kernel/context_tracking.c:context_tracking_cpu_set
  - mm/frontswap.c:frontswap_register_ops
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_write
  - lib/crc-t10dif.c:crc_t10dif_mod_init
  - net/core/sock.c:sk_set_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:net_inc_egress_queue
  - net/core/dev.c:net_inc_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/netfilter/core.c:__nf_register_net_hook
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
  - net/ipv4/tcp_input.c:clean_acked_data_enable
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata
  - net/ipv6/udp.c:udpv6_encap_enable
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff8120a540-ffffffff8120a564: static_key_slow_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void static_key_slow_inc(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81215580)
Location: kernel/jump_label.c:156
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/quirks.c:quirk_intel_purley_xeon_ras_cap
  - arch/x86/kernel/quirks.c:quirk_intel_brickland_xeon_ras_cap
  - arch/x86/kernel/cpu/mce/core.c:mcheck_late_init
  - arch/x86/kernel/kvm.c:activate_jump_labels
  - arch/x86/kernel/kvm.c:activate_jump_labels
  - arch/x86/kernel/tracepoint.c:trace_resched_ipi_reg
  - arch/x86/kernel/tracepoint.c:trace_pagefault_reg
  - kernel/sched/core.c:preempt_notifier_inc
  - kernel/sched/clock.c:sched_clock_init_late
  - kernel/sched/clock.c:sched_clock_init
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/events/core.c:perf_swevent_init
  - mm/frontswap.c:frontswap_register_ops
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_write
  - lib/crc-t10dif.c:crc_t10dif_mod_init
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg
  - net/core/sock.c:sk_set_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:net_inc_egress_queue
  - net/core/dev.c:net_inc_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/netfilter/core.c:__nf_register_net_hook
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
  - net/ipv4/tcp_input.c:clean_acked_data_enable
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata
  - net/ipv6/udp.c:udpv6_encap_enable
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff81215580-ffffffff812155a4: static_key_slow_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void static_key_slow_inc(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81224570)
Location: kernel/jump_label.c:156
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/quirks.c:quirk_intel_purley_xeon_ras_cap
  - arch/x86/kernel/quirks.c:quirk_intel_brickland_xeon_ras_cap
  - arch/x86/kernel/cpu/mce/core.c:mcheck_late_init
  - arch/x86/kernel/kvm.c:activate_jump_labels
  - arch/x86/kernel/kvm.c:activate_jump_labels
  - arch/x86/kernel/tracepoint.c:trace_resched_ipi_reg
  - arch/x86/kernel/tracepoint.c:trace_pagefault_reg
  - kernel/sched/core.c:preempt_notifier_inc
  - kernel/sched/clock.c:sched_clock_init_late
  - kernel/sched/clock.c:sched_clock_init
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/events/core.c:perf_swevent_init
  - mm/frontswap.c:frontswap_register_ops
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_write
  - lib/crc-t10dif.c:crc_t10dif_mod_init
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg
  - net/core/sock.c:sk_set_memalloc
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:net_inc_egress_queue
  - net/core/dev.c:net_inc_ingress_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/netfilter/core.c:__nf_register_net_hook
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
  - net/ipv4/tcp_input.c:clean_acked_data_enable
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata
  - net/ipv6/udp.c:udpv6_encap_enable
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff81224570-ffffffff81224594: static_key_slow_inc (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
